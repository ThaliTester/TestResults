#### Test 509828476dba52d_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1018): sending alarm Alarm{449415f0 type 3 android}
--------- beginning of /dev/log/main
D/AndroidRuntime( 3579): 
D/AndroidRuntime( 3579): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3579): CheckJNI is OFF
D/dalvikvm( 3579): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3579): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3579): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3579): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3579): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3579): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3579): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3579): failed to load memtrack module: -2
D/AndroidRuntime( 3579): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1018): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3579
W/WindowManager( 1018): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3595 uid=10377 gids={50377, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3579): Shutting down VM
D/dalvikvm( 3579): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+0ms, total 3ms
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3595): Binding Chromium to main looper Looper (main, tid 1) {428d9810}
I/LibraryLoader( 3595): Expected native library version number "",actual native library version number ""
I/chromium( 3595): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3595): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1018): Message: 20
D/BluetoothManagerService( 1018): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@444fbdb0:true
D/BluetoothAdapter( 3595): 1116661056: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3595): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3595): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3595): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3595): Local Branch: 
I/Adreno-EGL( 3595): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3595): Local Patches: NONE
I/Adreno-EGL( 3595): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3595): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3595): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3595): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3595): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3595): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3595): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3595): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3595): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3595): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3595): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3595): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3595): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3595): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3595): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3595): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3595): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3595): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3595): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3595): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3595): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3595): Enabling debug mode 0
,W/AwContents( 3595): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3595): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1018): Displayed com.test.thalitest/.MainActivity,cp,ca,381
I/ActivityManager( 1018): Displayed com.test.thalitest/.MainActivity: +357ms (total +381ms)
,D/JsMessageQueue( 3595): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3595): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428ddae0
,D/dalvikvm( 3595): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428ddae0
,D/jxcore_app_log( 3595): JniHelper::setJavaVM(0x41ffbf78), pthread_self() = 1615024136
,D/JX-Cordova( 3595): jxcore cordova android initializing
,I/dalvikvm( 3595): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 3595): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 3595): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 3595): GC_CONCURRENT freed 2917K, 18% free 14272K/17224K, paused 3ms+2ms, total 40ms
D/dalvikvm( 3595): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 3595): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 3595): GC_FOR_ALLOC freed 175K, 18% free 14163K/17224K, paused 25ms, total 25ms
,D/dalvikvm( 3595): GC_FOR_ALLOC freed 252K, 18% free 14217K/17224K, paused 24ms, total 24ms
,I/dalvikvm-heap( 3595): Grow heap (frag case) to 16.127MB for 220492-byte allocation
,D/dalvikvm( 3595): GC_FOR_ALLOC freed 376K, 19% free 14293K/17440K, paused 24ms, total 24ms
,I/dalvikvm-heap( 3595): Grow heap (frag case) to 16.306MB for 330734-byte allocation
,D/dalvikvm( 3595): GC_FOR_ALLOC freed 584K, 19% free 14418K/17764K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3595): Grow heap (frag case) to 16.585MB for 496096-byte allocation
,D/dalvikvm( 3595): GC_FOR_ALLOC freed 885K, 21% free 14596K/18252K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3595): Grow heap (frag case) to 16.996MB for 744140-byte allocation
,D/dalvikvm( 3595): GC_FOR_ALLOC freed 1311K, 22% free 14857K/18980K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3595): Grow heap (frag case) to 17.606MB for 1116206-byte allocation
,D/dalvikvm( 3595): GC_CONCURRENT freed 1785K, 24% free 15264K/20072K, paused 1ms+6ms, total 44ms
,D/dalvikvm( 3595): GC_CONCURRENT freed 1597K, 22% free 15753K/20072K, paused 2ms+3ms, total 40ms
,D/dalvikvm( 3595): GC_FOR_ALLOC freed 1796K, 21% free 15899K/20072K, paused 31ms, total 31ms
,I/dalvikvm-heap( 3595): Grow heap (frag case) to 19.954MB for 2511452-byte allocation
,D/dalvikvm( 3595): GC_CONCURRENT freed 257K, 19% free 18305K/22528K, paused 5ms+5ms, total 61ms
,D/dalvikvm( 3595): GC_CONCURRENT freed 4489K, 26% free 16835K/22528K, paused 1ms+8ms, total 54ms
,D/dalvikvm( 3595): WAIT_FOR_CONCURRENT_GC blocked 47ms
,I/dalvikvm-heap( 3595): Grow heap (frag case) to 22.066MB for 3767174-byte allocation
,D/dalvikvm( 3595): GC_CONCURRENT freed 2776K, 32% free 17939K/26208K, paused 1ms+5ms, total 47ms
,W/jxcore-log( 3595): Initializing JXcore engine
,W/jxcore-log( 3595): JXcore engine is ready
,D/dalvikvm( 3595): GC_CONCURRENT freed 534K, 23% free 20369K/26208K, paused 1ms+5ms, total 33ms
,D/dalvikvm( 3595): WAIT_FOR_CONCURRENT_GC blocked 26ms
,W/jxcore-log( 3595): Starting JXcore engine
,W/jxcore-log( 3595): Platform android
W/jxcore-log( 3595): 
,W/jxcore-log( 3595): Process ARCH arm
W/jxcore-log( 3595): 
,I/jxcore-log( 3595): JXcore Cordova bridge is ready!
I/jxcore-log( 3595): 
,W/jxcore-log( 3595): JXcore engine is started
,I/chromium( 3595): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3595): Turning radios to true
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1018): enable():  mBluetooth =null mBinding = false
,W/Settings( 1258): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/BluetoothManagerService( 1018): Message: 1
,D/BluetoothManagerService( 1018): MESSAGE_ENABLE: mBluetooth = null
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): New client listening to asynchronous messages
D/WifiService( 1018): setWifiEnabled: true pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
W/XTWiFiOS( 1268): Active network info is not available
,I/ActivityManager( 1018): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3650 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1023}
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1258): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiStateMachine( 1018): setting operational mode to 1
D/WifiStateMachine( 1018): handleMessage: E msg.what=131083
D/WifiStateMachine( 1018): processMsg: InitialState
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
,W/Settings( 1258): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1258): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1268): Active network info is not available
,D/AdapterServiceConfig( 3650): Adding HeadsetService
D/AdapterServiceConfig( 3650): Adding A2dpService
D/AdapterServiceConfig( 3650): Adding HidService
D/AdapterServiceConfig( 3650): Adding HealthService
D/AdapterServiceConfig( 3650): Adding PanService
D/AdapterServiceConfig( 3650): Adding GattService
,D/AdapterServiceConfig( 3650): Adding BluetoothMapService
,D/BluetoothAdapterService( 3650): REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothManagerService( 1018): Message: 20
,D/BluetoothAdapterState( 3650): make
,D/BluetoothManagerService( 1018): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44263c80:true
,I/bluedroid( 3650): init
,I/BluetoothAdapterState( 3650): Entering OffState
,I/bte_conf( 3650): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bluedroid( 3650): get_profile_interface socket
D/BluetoothManagerService( 1018): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1018): Message: 40
D/BluetoothManagerService( 1018): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/GKI_LINUX( 3650): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
,I/BluetoothAdapterProperties( 3650): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3650): Address is:F4:F1:E1:5C:3B:E2
I/bluedroid( 3650): config_hci_snoop_log
I/BluetoothAdapterProperties( 3650): adapterPropertyChangedCallback with type:1 len:6
D/BluetoothManagerService( 1018): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1018): Broadcasting onBluetoothServiceUp() to 8 receivers.
D/BluetoothManagerService( 1018): Bluetooth Adapter name changed to XT1039
,D/BluetoothManagerService( 1018): Stored Bluetooth name: XT1039
,D/BluetoothAdapterProperties( 3650): Name is: XT1039
,D/BluetoothAdapterState( 3650): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3650): Setting state to 11
I/BluetoothAdapterState( 3650): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 3650): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1018): Message: 60
D/BluetoothManagerService( 1018): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService( 1018): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3650): make
,I/BluetoothBondStateMachine( 3650): StableState(): Entering Off State
,I/ActivityManager( 1018): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3687 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/BluetoothHeadset( 1018): Proxy object connected
D/BluetoothHeadset( 1240): Proxy object connected
D/HeadsetService( 3650): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3650): classInitNative: succeeds
D/HeadsetStateMachine( 3650): Version 1.6
D/HeadsetStateMachine( 3650): make
D/BluetoothHeadset( 1240): Proxy object connected
D/BluetoothHeadset( 1240): Proxy object connected
,I/BluetoothAdapterState( 3650): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/bluedroid( 3650): get_profile_interface handsfree
,D/BluetoothA2dp( 1018): Proxy object connected
D/A2dpService( 3650): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3650): classInitNative: succeeds
,V/Avrcp   ( 3650): make
,I/bluedroid( 3650): get_profile_interface avrcp
I/BluetoothA2dpServiceJni( 3650): classInitNative: succeeds
,D/A2dpStateMachine( 3650): make
,I/bluedroid( 3650): get_profile_interface a2dp
,I/GKI_LINUX( 3650): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 3650): warning : no command pending, ignore ack
,D/A2dpStateMachine( 3650): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3650): classInitNative: succeeds
D/HidService( 3650): Received start request. Starting profile...
,I/bluedroid( 3650): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 3650): classInitNative: succeeds
,D/HealthService( 3650): Received start request. Starting profile...
I/bluedroid( 3650): get_profile_interface health
,I/BluetoothPanServiceJni( 3650): classInitNative(L105): succeeds
D/BluetoothPan( 1018): BluetoothPAN Proxy object connected
D/PanService( 3650): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3650): initializeNative(L110): pan
,I/bluedroid( 3650): get_profile_interface pan
,D/BluetoothTethering( 1018): got CMD_CHANNEL_HALF_CONNECTED
I/BtGatt.JNI( 3650): classInitNative(L684): classInitNative: Success!
,D/BluetoothTethering( 1018): CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@442022f0
D/BtGatt.DebugUtils( 3650): handleDebugAction() action=null
D/BtGatt.GattService( 3650): Received start request. Starting profile...
D/BtGatt.GattService( 3650): start()
,I/bluedroid( 3650): get_profile_interface gatt
,D/BluetoothMapService( 3650): Received start request. Starting profile...
,D/BluetoothMapService( 3650): start()
,D/HeadsetPhoneState( 3650): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState( 3650): onSignalStrengthsChanged..for signal  prevSignal=0
D/BluetoothAdapterService( 3650): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3650): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3650): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3650): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3650): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/HeadsetPhoneState( 3650): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/BluetoothAdapterService( 3650): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterState( 3650): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3650): enable
,I/bt_hci_bdroid( 3650): init
I/bt_vendor( 3650): bt-vendor : init
I/bt_hci_bdroid( 3650): ro.qualcomm.hci_transport set to smd
D/bt_userial_mct( 3650): userial_init
I/bt_hwcfg( 3650): Starting hciattach daemon
,I/bt_hwcfg( 3650): try to set false
I/bt_hwcfg( 3650): Starting hciattach daemon
,I/bt_hwcfg( 3650): try to set true
,I/bt_hci_bdroid( 3650): bt_hc_worker_thread started
,I/qcom-bluetooth( 3712): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
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
,I/MDMCTBK (  272): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
,E/MDMCTBK (  272): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ActivityManager( 1018): Killing 3419:com.android.defcontainer/u0a13 (adj 15): empty #9
D/Tethering( 1018): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/TCMD    (  422): NL - Read 1004 bytes from update socket.
D/TCMD    (  422): NL - message type is RTM_NEWLINK
D/TCMD    (  422): Listening for incoming client connection request
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
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
,D/TCMD    (  422): NL - Read 1004 bytes from update socket.
D/TCMD    (  422): NL - message type is RTM_NEWLINK
,D/TCMD    (  422): Listening for incoming client connection request
,I/qcom-bluetooth( 3721): /system/etc/init.qcom.bt.sh: Transport : smd 
D/QsoftapCmd(  269): Got softap fwreload command we are passing on
,D/SoftapController(  269): Softap fwReload - Ok
,I/qcom-bluetooth( 3722): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
D/CommandListener(  269): Setting iface cfg
,D/CommandListener(  269): Trying to bring down wlan0
,I/qcom-bluetooth( 3725): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 3726): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,E/WifiHW  ( 1018): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
,I/qcom-bluetooth( 3727): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,E/WifiHW  ( 1018): ctrl_interface != /data/misc/wifi/sockets
,E/Diag_Lib( 3729): qmi_init:  Not initialized, calling process init sequence
E/Diag_Lib( 3729): Setting internal use port to rmnet0
E/Diag_Lib( 3729):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,E/Diag_Lib( 3729): Failed on DIAG init
E/Diag_Lib( 3729): linux_qmi_qmux_if_client_get_proc_name: pid=3729, proc_name=hci_qcomm_init
E/Diag_Lib( 3729): linux_qmi_qmux_if_client_get_socket_paths: num_grps=2
E/Diag_Lib( 3729): linux_qmi_qmux_if_client_get_proc_group_name: gid=1002, grp_name=bluetooth
E/Diag_Lib( 3729): using socket paths bind=/dev/socket/qmux_bluetooth/qmux_client_socket, connect=/dev/socket/qmux_bluetooth/qmux_connect_socket
E/Diag_Lib( 3729): qmi_client [3729]: successfully connected to server, attempt=1
E/Diag_Lib( 3729): linux_qmi_qmux_if_client_get_client_id [3729]: qmux_client_id=13
E/Diag_Lib( 3729): qmi_client [3729] 13: qmux_client ID is initialized
E/Diag_Lib( 3729): qmi_client [3729] 13: pipe() system call, fd[0]=10, fd[1]=11
,E/Diag_Lib( 3729): qmi_client [3729] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3729): qmi_client [3729] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3729): Sending signal ...... to read cmd data 
E/Diag_Lib( 3729): qmi error code.........:0
E/Diag_Lib( 3729): qmi sys error code.........:0
E/Diag_Lib( 3729): qmi_qmux_if_pwr_up_init_ex:  Successfully created and added QMUX client 19
E/Diag_Lib( 3729): qmi_nas_srvc_init: NAS successfully initialized
E/Diag_Lib( 3729): qmi_qos_srvc_init: QOS successfully initialized
E/Diag_Lib( 3729): qmi_eap_srvc_init: EAP successfully initialized
E/Diag_Lib( 3729): qmi_wds_srvc_init: WDS successfully initialized
E/Diag_Lib( 3729): qmi_atcop_srvc_init: ATCOP successfully initialized
E/Diag_Lib( 3729): qmi_uim_srvc_init: UIM successfully initialized
E/Diag_Lib( 3729): qmi_cat_srvc_init: CAT successfully initialized
E/Diag_Lib( 3729): qmi_init:  Created client handle b81efb10
,E/Diag_Lib( 3729): qmi_client [3729] 13: sending 880 bytes on fd = 8
,E/Diag_Lib( 3729): qmi_client [3729] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3729): Sending signal ...... to read cmd data 
E/Diag_Lib( 3729): qmi error code.........:0
,E/Diag_Lib( 3729): qmi sys error code.........:0
E/Diag_Lib( 3729): Setting the api flag to : 1
,E/Diag_Lib( 3729): qmi_client [3729] 13: sending 54 bytes on fd = 8
,I/wpa_supplicant( 3731): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3731): rfkill: Cannot open RFKILL control device
D/TCMD    (  422): NL - Read 1000 bytes from update socket.
D/TCMD    (  422): NL - message type is RTM_NEWLINK
D/TCMD    (  422): Listening for incoming client connection request
D/TCMD    (  422): NL - Read 1000 bytes from update socket.
D/TCMD    (  422): NL - message type is RTM_NEWLINK
,D/TCMD    (  422): Listening for incoming client connection request
,V/BluetoothFtpReceiver( 3650): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,D/AuthorizationBluetoothService( 1336): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/Diag_Lib( 3731): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 3731): Setting internal use port to rmnet0
,D/WifiStateMachine( 1018): setWifiState: enabling
D/WifiStateMachine( 1018): Supplicant start successful
,D/WifiMonitor( 1018): startMonitoring(wlan0) with mConnected = false
,I/SBar.NetworkController( 1080): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
E/wpa_supplicant( 3731): baseband property is set to [msm]
I/rmt_storage(  415): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb88b01d0
I/rmt_storage(  415): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  415): wakelock acquired: 1, error no: 42
,I/rmt_storage(  415): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1198850328)
E/Diag_Lib( 3729): qmi_client [3729] 13: Received 54 bytes on fd = 8
E/Diag_Lib( 3729):  API Flag .............. 1 
,E/Diag_Lib( 3729):  Message ID ............... 92 
W/XTWiFiOS( 1268): Active network info is not available
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,E/wpa_supplicant( 3731):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3731): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3731): card_info[i].card_state: 0x2
E/wpa_supplicant( 3731): card_info[i].error_code: 0x3
E/wpa_supplicant( 3731): SIM/USIM not ready
,E/wpa_supplicant( 3731): Error while reading SIM card status
,E/wpa_supplicant( 3731): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3731): card_info[i].card_state: 0x2
E/wpa_supplicant( 3731): card_info[i].error_code: 0x3
E/wpa_supplicant( 3731): SIM/USIM not ready
,I/wpa_supplicant( 3731): eap_proxy: Card not ready
,D/Checkin ( 2147): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2147): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
E/Diag_Lib( 3729): qmi_service_release called, user_handle=30200
E/Diag_Lib( 3729): qmi_free_srvc_data : ENTRY
E/Diag_Lib( 3729): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib( 3729): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib( 3729): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib( 3729): qmi_service_delete_client_txns : ENTRY - conn_id=0, service=2, client=3
E/Diag_Lib( 3729): qmi_service_delete_client_txns : EXIT
E/Diag_Lib( 3729): qmi_free_srvc_data : EXIT
,E/Diag_Lib( 3729): qmi_client [3729] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3729): qmi_client [3729] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3729): Sending signal ...... to read cmd data 
E/Diag_Lib( 3729): qmi error code.........:0
E/Diag_Lib( 3729): qmi sys error code.........:0
E/Diag_Lib( 3729): qmi_release: Released client handle ff
E/Diag_Lib( 3729): qmi_release: Last client releases, performing library de-init
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=0
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=1
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=2
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=3
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=4
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=5
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=6
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=7
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=8
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=9
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=10
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=11
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=12
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=13
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=14
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=15
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=16
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=17
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=18
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=19
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=20
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=21
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=22
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=23
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=24
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=25
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=26
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=27
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=28
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=29
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=30
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=31
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=32
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=33
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=34
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=35
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=36
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=37
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=38
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=39
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=40
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=41
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=42
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=43
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=44
E/Diag_Lib( 3729): Call,ed qmi_service_reset_all, release on modem=1, conn_id=45
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=46
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=47
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=48
E/Diag_Lib( 3729): Called qmi_service_reset_all, release on modem=1, conn_id=49
E/Diag_Lib( 3729): qmi_nas_srvc_release: NAS successfully released
E/Diag_Lib( 3729): qmi_qos_srvc_release: QOS successfully released
E/Diag_Lib( 3729): qmi_eap_srvc_release: EAP successfully released
E/Diag_Lib( 3729): qmi_wds_srvc_release: WDS successfully released
E/Diag_Lib( 3729): qmi_atcop_srvc_release: ATCOP successfully released
E/Diag_Lib( 3729): qmi_nas_srvc_release: UIM successfully released
E/Diag_Lib( 3729): qmi_cat_srvc_release: CAT successfully released
E/Diag_Lib( 3729): qmi_client [3729] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3729): qmi_client [3729] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3729): Sending signal ...... to read cmd data 
E/Diag_Lib( 3729): qmi error code.........:0
E/Diag_Lib( 3729): qmi sys error code.........:0
E/Diag_Lib( 3729): qmi_qmux_if_pwr_down_release: Released QMUX client handle [3729] 13
E/Diag_Lib( 3729): qmi_client [3729] 13: Client release, writing pipe to kill read thread, fd = 11
E/Diag_Lib( 3729): qmi_client [3729] 13: failed to locate client data
E/Diag_Lib( 3729): qmi_client [3729] 13: calling release of fd=8
,E/Diag_Lib( 3729): qmi_qmux_if_pwr_down_release: Last client releases, performing de-init
,D/dalvikvm( 1018): GC_EXPLICIT freed 21770K, 65% free 17844K/49624K, paused 11ms+10ms, total 238ms
D/WifiService( 1018): New client listening to asynchronous messages
,I/rmt_storage(  415): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  415): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  415): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1198850328) wakelock released: 1, error no: 0
I/rmt_storage(  415): 
,I/rmt_storage(  415): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb88b01d0
,I/wpa_supplicant( 3731): Long line in configuration file truncated
,I/wpa_supplicant( 3731): rfkill: Cannot open RFKILL control device
D/TCMD    (  422): NL - Read 1000 bytes from update socket.
D/TCMD    (  422): NL - message type is RTM_NEWLINK
,D/TCMD    (  422): Listening for incoming client connection request
,I/qcom-bluetooth( 3735): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 f4:f1:e1:5c:3b:e2 
,I/qcom-bluetooth( 3736): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/bt_hwcfg( 3650): bluetooth satus is on
D/bt_userial_mct( 3650): userial_open(port:0)
I/GKI_LINUX( 3650): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
,I/bt-btu  ( 3650): btu_task pending for preload complete event
I/bt_userial_vendor( 3650): Done intiailizing UART
I/bt_userial_vendor( 3650): Done intiailizing UART
E/wpa_supplicant( 3731): COUNTRY Code Recived
,I/bt_userial_mct( 3650): CMD=72, EVT=72, ACL_Out=73, ACL_In=73
I/bt_vendor( 3650): Bluetooth Firmware and smd is initialized
,E/wpa_supplicant( 3731): COUNTRY Code Recived -COUNTRY PL
E/wpa_supplicant( 3731): baseband property is set to [msm]
I/bt-btu  ( 3650): btu_task received preload complete event
,D/bt_userial_mct( 3650): Entering userial_read_thread()
,I/        ( 3650): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3650): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3650): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3650): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3650): BTE_InitTraceLevels -- TRC_AVRC
,I/        ( 3650): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3650): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3650): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3650): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3650): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3650): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3650): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3650): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3650): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 3650): BTE_InitTraceLevels -- TRC_BTIF
,E/wpa_supplicant( 3731):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3731): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3731): card_info[i].card_state: 0x2
E/wpa_supplicant( 3731): card_info[i].error_code: 0x3
E/wpa_supplicant( 3731): SIM/USIM not ready
,E/wpa_supplicant( 3731): Error while reading SIM card status
E/wpa_supplicant( 3731): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3731): card_info[i].card_state: 0x2
E/wpa_supplicant( 3731): card_info[i].error_code: 0x3
E/wpa_supplicant( 3731): SIM/USIM not ready
,I/wpa_supplicant( 3731): eap_proxy: Card not ready
,D/WifiStateMachine( 1018): transitionTo: destState=SupplicantStartingState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
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
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131101
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131101
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147457
,D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
D/WifiStateMachine( 1018): Supplicant connection established
,D/WifiStateMachine( 1018): setWifiState: enabled
,I/SBar.NetworkController( 1080): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1268): Active network info is not available
I/SBar.NetworkController( 1080): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1080): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1080): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/WifiConfigStore( 1018): Loading config and enabling all networks
E/bt-btm  ( 3650): BTM_SecRegister:p_cb_info->p_le_callback == 0x5f14a049 
,E/bt-btm  ( 3650): BTM_SecRegister: btm_cb.api.p_le_callback = 0x5f14a049 
,E/WifiConfigStore( 1018): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
E/bt-btif ( 3650): Calling BTA_HhEnable
E/bt-btif ( 3650): btif_storage_get_adapter_property service_mask:0x140040
,I/BluetoothAdapterProperties( 3650): adapterPropertyChangedCallback with type:2 len:6
E/wpa_supplicant( 3731): COUNTRY Code Recived -COUNTRY PL
D/BluetoothAdapterProperties( 3650): Address is:F4:F1:E1:5C:3B:E2
,I/BluetoothAdapterProperties( 3650): adapterPropertyChangedCallback with type:1 len:6
,D/BluetoothManagerService( 1018): Bluetooth Adapter name changed to XT1039
D/BluetoothAdapterProperties( 3650): Name is: XT1039
I/BluetoothAdapterProperties( 3650): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothManagerService( 1018): Stored Bluetooth name: XT1039
D/BluetoothAdapterProperties( 3650): Scan Mode:21
I/BluetoothAdapterProperties( 3650): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3650): Discoverable Timeout:120
,I/BluetoothAdapterProperties( 3650): adapterPropertyChangedCallback with type:8 len:6
D/BluetoothAdapterProperties( 3650): Adding bonded device:B4:CE:F6:AB:A4:6A
,I/BluetoothAdapterProperties( 3650): adapterPropertyChangedCallback with type:3 len:48
,E/BluetoothRemoteDevices( 3650): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
,I/bte_conf( 3650): Attempt to load did conf from /etc/bluetooth/bt_did.conf
E/bt_mct  ( 3650): hci lib postload completed
I/bte_conf( 3650): [1] primary_record=1 vendor_id=0x001D vendor_id_source=0x0001 product_id=0x1200 version=0x1436
,I/bte_conf( 3650): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 3650): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,D/BluetoothPanServiceJni( 3650): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
D/BluetoothAdapterState( 3650): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3650): ScanMode =  21
D/BluetoothAdapterProperties( 3650): State =  11
D/BluetoothAdapterProperties( 3650): Setting state to 12
I/BluetoothAdapterState( 3650): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3650): Broadcasting updateAdapterState() to 1 receivers.
I/BluetoothAdapterProperties( 3650): adapterPropertyChangedCallback with type:9 len:4
,D/BluetoothAdapterProperties( 3650): Discoverable Timeout:120
D/BluetoothManagerService( 1018): Message: 60
D/BluetoothManagerService( 1018): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,D/BluetoothManagerService( 1018): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset( 1240): onBluetoothStateChange: up=true
D/BluetoothPan( 1018): onBluetoothStateChange on: true
D/BluetoothHeadset( 1240): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 3650): Entering On State
,D/BluetoothHeadset( 1240): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1018): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1018): onBluetoothStateChange: up=true
,D/BluetoothManagerService( 1018): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService( 1018): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(1116648768)( 3650): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3650): getBondedDevices: length=1
,D/BluetoothMapService( 3650): onReceive
D/BluetoothMapService( 3650): STATE_ON
,D/BluetoothMapService( 3650): Map Service startRfcommSocketListener
D/BluetoothManagerService( 1018): Message: 40
,D/BluetoothManagerService( 1018): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapService( 3650): Map Service initSocket
,D/BluetoothAdapterService(1116648768)( 3650): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3650): getBondedDevices: length=1
D/BluetoothAdapterService(1116648768)( 3650): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3650): getBondedDevices: length=1
D/WifiStateMachine( 1018): transitionTo: destState=DriverStartedState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1018): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=1,j=1
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
,D/WifiStateMachine( 1018): invokeEnterMethods: SupplicantStartedState
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/WifiStateMachine( 1018): invokeEnterMethods: DriverStartedState
,D/WifiStateMachine( 1018): setDetailed state, old =IDLE and new state=DISCONNECTED
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3650): SOCK FLAG = 1 ***********************
I/BluetoothAdapterProperties( 3650): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothMapService( 3650): Accepting socket connection...
,D/BluetoothAdapterProperties( 3650): Scan Mode:21
E/wpa_supplicant( 3731): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 3731): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1018): Attempting to reconnect to wifi network ..
,D/WifiStateMachine( 1018): transitionTo: destState=DisconnectedState
,I/qcom-bt-wlan-coex( 3751): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
W/ContextImpl( 3687): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
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
D/BluetoothManagerService( 1018): Message: 20
D/BluetoothManagerService( 1018): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42e55288:true
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131144
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131085
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131152
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): set country code PL
E/wpa_supplicant( 3731): COUNTRY Code Recived
E/wpa_supplicant( 3731): COUNTRY Code Recived
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131162
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): set frequency band 2
W/wpa_supplicant( 3731): wlan0: Failed to initiate AP scan
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131167
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/CommandListener(  269): Setting iface cfg
D/CommandListener(  269): Trying to bring up p2p0
E/SharedPreferencesImpl( 1018): Couldn't create directory for SharedPreferences file shared_prefs/wifi_sm_shared_prefs.xml
D/WifiStateMachine( 1018): handleMessage: X
D/WifiMonitor( 1018): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 1018): P2pEnablingState
D/WifiP2pService( 1018): P2pEnablingState{ when=-10ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnablingState{ when=-9ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): DefaultState{ when=-10ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D,/WifiP2pService( 1018): P2p socket connection successful
D/WifiP2pService( 1018): P2pEnabledState
D/BluetoothPbapService( 3650): action: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothPbapService( 3650): Handler(): got msg=1
D/WifiP2pService( 1018): sending p2p connection changed broadcast
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3650): SOCK FLAG = 1 ***********************
D/WifiStateMachine( 1018): handleMessage: E msg.what=143371
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/LocalBluetoothProfileManager( 3687): Adding local A2DP profile
D/BluetoothManagerService( 1018): Message: 30
D/WifiP2pService( 1018): DeviceAddress: f4:f1:e1:5c:43:c8
W/ContextImpl( 3687): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
D/LocalBluetoothProfileManager( 3687): Adding local HEADSET profile
D/BluetoothManagerService( 1018): Message: 30
D/WifiP2pService( 1018): MCC mode enabled 0
W/ContextImpl( 3687): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
D/WifiP2pService( 1018): mP2pAutoConnectSupport = 0
D/BluetoothManagerService( 1018): Message: 30
W/ContextImpl( 3687): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
D/WifiP2pService( 1018): sending p2p persistent groups changed broadcast
D/WifiP2pService( 1018): InactiveState
D/WifiP2pService( 1018): InactiveState{ when=-4m50s527ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=-4m50s527ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): InactiveState{ when=-7ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=-7ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService( 1018): Message: 30
E/wpa_supplicant( 3731): COUNTRY Code Recived
E/wpa_supplicant( 3731): COUNTRY Code Recived
W/ContextImpl( 3687): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 3687): Adding local MAP profile
D/BluetoothMap( 3687): Create BluetoothMap proxy object
D/BluetoothManagerService( 1018): Message: 30
W/ContextImpl( 3687): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
D/BluetoothManagerService( 1018): Message: 30
,W/ContextImpl( 3687): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 3687): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 3687): finishStartingService: stopping service
,D/BluetoothAdapterService(1116648768)( 3650): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3650): getBondedDevices: length=1
,D/dalvikvm( 1204): GC_EXPLICIT freed 1947K, 41% free 10256K/17224K, paused 28ms+6ms, total 98ms
,D/BluetoothAdapterService(1116648768)( 3650): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3650): getBondedDevices: length=1
,D/BluetoothA2dp( 3687): Proxy object connected
,D/A2dpProfile( 3687): Bluetooth service connected
,D/BluetoothHeadset( 3687): Proxy object connected
,D/HeadsetProfile( 3687): Bluetooth service connected
,D/BluetoothInputDevice( 3687): Proxy object connected
,D/HidProfile( 3687): Bluetooth service connected
,D/BluetoothPan( 3687): BluetoothPAN Proxy object connected
D/PanProfile( 3687): Bluetooth service connected
D/BluetoothMap( 3687): Proxy object connected
D/MapProfile( 3687): Bluetooth service connected
,D/BluetoothMap( 3687): getConnectedDevices()
,D/BluetoothPbap( 3687): Proxy object connected
,D/PbapServerProfile( 3687): Bluetooth service connected
,E/DataBuffer( 1204): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42d028b0)
,V/BluetoothFtpReceiver( 3650): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 3650): BluetoothFtpReceiver Start Service
,D/AuthorizationBluetoothService( 1336): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1336): Proximity feature is not enabled.
,D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothFtpService( 3650): Ftp Service onCreate
I/BluetoothFtpService( 3650): FFFFFtp Service onCreate
,V/BluetoothFtpService( 3650): Starting FTP service
V/BluetoothFtpService( 3650): Ftp Service onStartCommand
V/BluetoothFtpService( 3650): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpService( 3650): Handler(): got msg=1
,V/BluetoothFtpService( 3650): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 3650): Ftp Service initSocket
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3650): SOCK FLAG = 0 ***********************
,E/BluetoothServiceJni( 3650): SOCK FLAG = 3 ***********************
V/BluetoothFtpService( 3650): Succeed to create listening socket on channel 20
I/BtOppRfcommListener( 3650): Accept thread started.
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3650): Run Accept thread
,D/BluetoothAdapterService(1116648768)( 3650): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3650): getBondedDevices: length=1
,D/Checkin ( 2147): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2147): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/MDMCTBK (  272): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  272): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
,I/MDMCTBK (  272): wifi_connect_to_supplicant, current pid is = 272
D/MDMCTBK (  272): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  272): wifi_close_sockets: Exit
,E/MDMCTBK (  272): Attach monitor thread
I/MDMCTBK (  272): createWifiMonitorThread: Started the wifi monitor thread -1218673664
,D/MDMCTBK (  272): wifi_wait_on_socket: Enter monitor thread
,D/TCMD    (  422): NL - Read 1000 bytes from update socket.
D/TCMD    (  422): NL - message type is RTM_NEWLINK
,D/TCMD    (  422): Listening for incoming client connection request
,D/Checkin ( 2147): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2147): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,W/wpa_supplicant( 3731): wlan0: Failed to initiate AP scan
D/MDMCTBK (  272): reply_len: 42 reply is = IFNAME=wlan0 <4>Failed to initiate AP scan
,D/MDMCTBK (  272): Event received = Failed to initiate AP scan
,D/WifiP2pService( 1018): InactiveState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledStateupdate channel list
,I/wpa_supplicant( 3731): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  272): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c0:
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 0 c0:
D/MDMCTBK (  272): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 c2:
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 1 c2:
D/MDMCTBK (  272): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 64:
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 2 64:
D/MDMCTBK (  272): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 06:
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 3 06:
D/MDMCTBK (  272): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 38:
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 4 38:
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  272): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  272): Event received = Trying to associate with
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3730): fatal error opening "/sys/power/wake_lock"
,I/wpa_supplicant( 3730): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
D/TCMD    (  422): NL - Read 56 bytes from update socket.
D/TCMD    (  422): NL - message type is RTM_NEWLINK
,D/TCMD    (  422): Listening for incoming client connection request
,E/wpa_supplicant( 3731): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiStateMachine( 1018): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,I/wpa_supplicant( 3731): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 3731): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  422): NL - Read 312 bytes from update socket.
D/TCMD    (  422): NL - message type is RTM_NEWLINK
D/TCMD    (  422): Listening for incoming client connection request
D/TCMD    (  422): NL - Read 88 bytes from update socket.
D/TCMD    (  422): NL - message type is RTM_NEWLINK
D/TCMD    (  422): Listening for incoming client connection request
D/TCMD    (  422): NL - Read 68 bytes from update socket.
D/TCMD    (  422): NL - message type is RTM_NEWLINK
D/TCMD    (  422): Listening for incoming client connection request
D/TCMD    (  422): NL - Read 1000 bytes from update socket.
D/TCMD    (  422): NL - message type is RTM_NEWLINK
D/TCMD    (  422): Listening for incoming client connection request
I/wpa_supplicant( 3731): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  272): Event received = Associated with c0:ff:d4
D/TCMD    (  422): NL - Read 80 bytes from update socket.
D/TCMD    (  422): NL - message type is RTM_NEWLINK
D/TCMD    (  422): Listening for incoming client connection request
D/TCMD    (  422): NL - Read 80 bytes from update socket.
D/TCMD    (  422): NL - message type is RTM_NEWLINK
D/TCMD    (  422): Listening for incoming client connection request
D/TCMD    (  422): NL - Read 68 bytes from update socket.
D/TCMD    (  422): NL - message type is RTM_NEWLINK
D/TCMD    (  422): Listening for incoming client connection request
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
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
,D/Tethering( 1018): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3731): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  272): Event received = WPA: Key negotiation com
I/wpa_supplicant( 3731): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  272): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  272):  STA Connected !!
D/TCMD    (  422): NL - Read 1000 bytes from update socket.
D/TCMD    (  422): NL - message type is RTM_NEWLINK
,D/TCMD    (  422): Listening for incoming client connection request
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
,I/MDMCTBK (  272): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
,I/MDMCTBK (  272): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=0, p2p0 = 1, wlan0 = 1, data=0
E/MDMCTBK (  272): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  272): get_freq !!, resp=0
I/MDMCTBK (  272): get_freq !!, Strip data
I/MDMCTBK (  272): get_freq !!, band = 2, freq = 0
,I/MDMCTBK (  272): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  272): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): get_property_value, Enter
I/MDMCTBK (  272): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  272): get_property_value, Exit
I/MDMCTBK (  272): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1218677768
I/MDMCTBK (  272): return from set_get_from_wpa_supplicant
,I/MDMCTBK (  272): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  272): set_property_value, Enter
I/MDMCTBK (  272): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
E/MDMCTBK (  272): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  272): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  272): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  272): , reply_len: 3, ret: 0
E/MDMCTBK (  272): MdmCutbackHndler, resp=OK
E/MDMCTBK (  272): 
,D/MDMCTBK (  272): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131101
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147459
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): Network connection established
,D/WifiStateMachine( 1018): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1018): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1018): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1018): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1018): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1018): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
,D/WifiStateMachine( 1018): ObtainingIpState{ when=-41ms what=147462 obj=android.net.wifi.StateChangeResult@42a978c8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=196612
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=0 what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1018): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiP2pService( 1018): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42d9a590 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42d9a590 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 6
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 5 6
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 0
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 6 0
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  272): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 64
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 2 64
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 38
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 4 38
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 64
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 5 64
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 0c
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 6 0c
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  272): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  422): NL - Read 56 bytes from update socket.
D/TCMD    (  422): NL - message type is RTM_NEWLINK
D/TCMD    (  422): Listening for incoming client connection request
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiP2pService( 1018): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@42aa26f0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@42aa26f0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): DefaultState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@42aa26f0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): ObtainingIpState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): handleMessage: X
,I/jxcore-log( 3595): Attempting to connect to the test coordinator server
I/jxcore-log( 3595): 
,D/TCMD    (  422): NL - Read 60 bytes from update socket.
D/TCMD    (  422): NL - ignore NL message, type = 20
,D/TCMD    (  422): Listening for incoming client connection request
,D/WifiStateMachine( 1018): addressUpdated: 192.168.1.123/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1018): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.123/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=196613
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1018): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): DHCP successful
D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1018): Calling ARP set with IP = 192.168.1.123
D/WifiStateMachine( 1018): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1018): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1018): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1018): VerifyingLinkState enter
D/WifiStateMachine( 1018): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiStateMachine( 1018): handleMessage: X
,I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1018): handleMessage: E msg.what=151572
D/WifiStateMachine( 1018): processMsg: VerifyingLinkState
D/WifiStateMachine( 1018): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1080): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=135190
,D/WifiStateMachine( 1018): processMsg: VerifyingLinkState
D/WifiStateMachine( 1018): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1018): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1018): invokeExitMethods: VerifyingLinkState
,D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1018): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1018): CaptivePortalCheckState enter
,D/WifiStateMachine( 1018): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/WifiStateMachine( 1018): handleMessage: X
D/ConnectivityService( 1018): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1018): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1018): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1018): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine( 1018): handleMessage: E msg.what=131092
D/WifiStateMachine( 1018): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1018): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1018): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/ConnectivityService( 1018): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1018): WiFi NOT Tethered!
,I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,E/ConnectivityService( 1018): Unexpected mtu value: android.net.wifi.WifiStateTracker@42a6a338
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/Checkin ( 1018): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/WifiStateMachine( 1018): transitionTo: destState=ConnectedState
,D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1018): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1018): invokeEnterMethods: ConnectedState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131092
D/WifiStateMachine( 1018): processMsg: ConnectedState
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): handleMessage: X
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
I/SBar.NetworkController( 1080): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/ModemStatsDSDetect( 1286): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1286): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1286): onReceive() - done, currentInetCondition=0
,D/ConnectivityService( 1018): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1018): WiFi NOT Tethered!
,I/SBar.NetworkController( 1080): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,E/ConnectivityService( 1018): Unexpected mtu value: android.net.wifi.WifiStateTracker@42a6a338
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1080): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService( 1018): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1286): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1286): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1286): onReceive() - done, currentInetCondition=0
,D/CaptivePortalTracker( 1018): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering( 1018): MasterInitialState.processMessage what=3
D/        ( 1018): Setting time of day to sec=1447785913
,I/SBar.NetworkController( 1080): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,W/        ( 1018): Unable to set rtc to 1447785913: Invalid argument
I/SBar.NetworkController( 1080): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/PollingManager( 1534): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1240): Column apn id key is 'apn_id'
D/PollingManager( 1534): now: 297468 ,futureTime: 49516185
,D/PollingManager( 1534): Polling alarm set to expire at: 49516185 Current Time: 297469
,I/SBar.NetworkController( 1080): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1080): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1534): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1534): registerApp(): CCE
I/CCE     ( 1534): _configureNotificationMechanism(): successfully turned off push and starting polling at interval 1440
D/Checkin ( 1534): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 1534): Registering with Alarm Manager to restart CCE
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1018): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1240): Column apn id key is 'apn_id'
,D/MMApiWebService( 1534): Received data connectivity intent from PollingManager .. retry the waiting requests: 2
,D/CCE     ( 1534): trying to auto login since I haven't yet and the radio is up now
,D/MMApiProvisionService( 1534): isRequestAllowed(): already have outstanding request ... ignoring request
I/openssl ( 3170): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3170): Crypto mode 0 already enabled
D/PollingManager( 1534): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/OtaApp  ( 1534): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1534): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1534): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/PollingManager( 1534): now: 297573 ,futureTime: 49516185
D/PollingManager( 1534): Polling alarm set to expire at: 49516185 Current Time: 297573
,E/ActivityThread( 1534): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1534): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1534): isRequestAllowed(): already have outstanding request ... ignoring request
D/OtaApp  ( 1534): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1534): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1534): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1534): [debug] > CusSM.runStateMachine: server told to :continue
D/MMApiWebService( 1534): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1534): generating token using payload instead of using session token
D/OtaApp  ( 1534): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1534): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiWebService( 1534): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/OtaApp  ( 1534): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1534): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1534): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1534): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1534): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1534): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,I/ActivityManager( 1018): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=3843 uid=10056 gids={50056, 3003, 1028, 1015}
D/OtaApp  ( 1534): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/dalvikvm( 1386): GC_CONCURRENT freed 1811K, 35% free 11199K/17224K, paused 3ms+7ms, total 57ms
,I/ActivityManager( 1018): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=3857 uid=10030 gids={50030, 3003, 1028, 1015}
,I/MMApiWSBase( 1534): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1534): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWSBase( 1534): doRequest(): url: https://api.svcmot.com:443/v1/dp/devices.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1534): publish the event [tag = MOT_CCE event name = LOG]
,V/MmsConfig( 3857): mnc/mcc: 
,V/MmsConfig( 3857): tag: bool value: enabledMMS - true
V/MmsConfig( 3857): tag: int value: maxMessageSize - 307200
V/MmsConfig( 3857): tag: int value: maxImageHeight - 1944
V/MmsConfig( 3857): tag: int value: maxImageWidth - 2592
V/MmsConfig( 3857): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 3857): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 3857): tag: int value: minMessageCountPerThread - 10
,V/MmsConfig( 3857): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 3857): tag: int value: recipientLimit - 20
V/MmsConfig( 3857): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 3857): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 3857): tag: bool value: enableSlideDuration - true
V/MmsConfig( 3857): tag: int value: maxMessageTextSize - -1
,V/MmsConfig( 3857): tag: int value: maxSubjectLength - 80
V/MmsConfig( 3857): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 3857): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 3857): tag: bool value: enableGroupMms - false
,E/MmsConfig( 3857): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1018): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3886 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1018): Killing 3441:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/TelephonyProvider( 1240): Column apn id key is 'apn_id'
,I/VacuumService( 1336): Vacuum at: now=1447785913644 tag=VacuumService
,D/dalvikvm( 1240): GC_EXPLICIT freed 1387K, 45% free 9514K/17224K, paused 3ms+5ms, total 42ms
,D/MobileConnectivityChangeReceiver( 3886): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3886): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3886): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3886): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager( 1018): Killing 3134:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3901 uid=10076 gids={50076, 3003, 1028, 1015}
,I/CheckinService( 1386): Checkin interval check for package: unspecified last checkin: 1447767616203 min interval config: 0 actual interval: 18297483
,I/dalvikvm( 1386): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
,W/dalvikvm( 1386): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,I/CheckinService( 1386): Checking schedule, now: 1447785913700 next: 1447767646171
D/dalvikvm( 1386): VFY: replacing opcode 0x6e at 0x0033
,I/CheckinService( 1386): active receiver: enabled
,I/CheckinService( 1386): Preparing to send checkin request
,I/EventLogService( 1386): Accumulating logs since 1447784061789
,I/dalvikvm( 1204): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
,W/dalvikvm( 1204): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1204): VFY: replacing opcode 0x6e at 0x0033
,D/DelayedSyncController( 3843): Delaying sync.
,D/TelephonyProvider( 1240): Column apn id key is 'apn_id'
,E/Auth.Api.Credentials( 1386): [CredentialSyncAdapter] Unknown sync event.
,D/GpsLocationProvider( 1018): NTP server returned: 1447785910266 (Tue Nov 17 19:45:10 CET 2015) reference: 294509 certainty: 11 system time offset: -3511
,E/LocSvc_ApiV02( 1018): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
I/ActivityManager( 1018): Killing 3469:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 3901): Binding Chromium to main looper Looper (main, tid 1) {428e0078}
,I/LibraryLoader( 3901): Expected native library version number "",actual native library version number ""
,I/chromium( 3901): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3901): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 3901): BLUETOOTH permission is missing!
,I/Adreno-EGL( 3901): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3901): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3901): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3901): Local Branch: 
I/Adreno-EGL( 3901): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3901): Local Patches: NONE
I/Adreno-EGL( 3901): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/dalvikvm( 1018): GC_EXPLICIT freed 1683K, 64% free 17920K/49624K, paused 5ms+13ms, total 114ms
,W/chromium( 3901): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 3901): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  260): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  260): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3901): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
I/CheckinRequestBuilder( 1386): Checkin reason type: 8 attempt count: 1
,D/WifiService( 1018): New client listening to asynchronous messages
,E/ActivityThread( 1386): Failed to find provider info for com.google.android.wearable.settings
,D/DelayedSyncController( 3843): Delaying sync.
,D/dalvikvm( 1336): GC_EXPLICIT freed 1102K, 39% free 10546K/17224K, paused 2ms+11ms, total 43ms
,I/NSApplication( 3901): Starting up...
,I/ImageResourceManager( 3494): ImageResourceManager: uninitalized
,I/iu.Environment( 3494): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/iu.SyncManager( 3494): SYNC; picasa accounts
I/ActivityManager( 1018): Killing 3115:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.UploadsManager( 3494): num queued entries: 0
,I/iu.UploadsManager( 3494): num updated entries: 0
,I/iu.SyncManager( 3494): NEXT; no task
,I/iu.SyncManager( 1386): SYNC; picasa accounts
,D/NetworkLogImpl( 1386): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1386): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1386): num queued entries: 0
I/iu.UploadsManager( 1386): num updated entries: 0
,I/iu.SyncManager( 1386): NEXT; no task
,D/dalvikvm( 1534): GC_CONCURRENT freed 2697K, 38% free 10751K/17224K, paused 3ms+7ms, total 41ms
,D/DEBUG   ( 1534): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/dalvikvm( 1336): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1336): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1336): VFY: replacing opcode 0x6e at 0x0033
,I/SundryService( 1534): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1534): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1534): ServiceHandler.handleMessage: mWaitCount=1
,I/openssl ( 3170): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3170): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 3886): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3886): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3494): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/ActivityManager( 1018): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=3966 uid=10007 gids={50007, 3003}
D/WifiStateMachine( 1018): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1018): handleMessage: E msg.what=131215
D/WifiStateMachine( 1018): processMsg: ConnectedState
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1018): handleMessage: X
D/ConnectivityService( 1018): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1018):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1018): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
,D/ExtensionsFactory( 3966): No custom extensions.
,I/ActivityManager( 1018): Start proc com.android.deskclock for broadcast com.android.deskclock/.AlarmInitReceiver: pid=3985 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1018): Killing 3186:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3995 uid=10008 gids={50008, 3003, 1028, 1015}
,D/dalvikvm(  274): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 1ms+3ms, total 21ms
I/ActivityManager( 1018): Killing 3687:com.android.settings/1000 (adj 15): empty #9
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,D/WifiService( 1018): Client connection lost with reason: 4
D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,V/AlarmClock( 3985): AlarmInitReceiver android.intent.action.TIME_SET
,I/CalendarProvider2( 3995): Created com.android.providers.calendar.CalendarAlarmManager@428fbe00(com.android.providers.calendar.CalendarProvider2@428f39b8)
,I/AlarmClock( 3985): Displaying next alarm time: ''
,V/AlarmClock( 3985): AlarmInitReceiver finished
,I/ActivityManager( 1018): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4015 uid=10098 gids={50098}
,D/dalvikvm( 4015): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x428dc558, skipping init
D/TimeService( 4015): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1447785914647
D/        ( 4015): TimeServiceNative: User Time to be set is 1447785914647
D/QC-time-services( 4015): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4015): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4015): Lib:time_genoff_operation: pargs->ts_val = 1447785914647
D/QC-time-services( 4015): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  404): Daemon: Connection accepted:time_genoff
D/QC-time-services(  404): Daemon:Received base = 2, unit = 1, operation = 0,value = 1447785914647
D/QC-time-services(  404): Daemon:genoff_opr: Base = 2, val = 1447785914647, operation = 0
D/QC-time-services(  404): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS10/17/115 18:39:25
D/QC-time-services(  404): Daemon:Value read from RTC seconds = 1447785565000
D/QC-time-services(  404): Daemon:new time 1447785914647 
D/QC-time-services(  404): Daemon: delta 349647 genoff 349647 
D/QC-time-services(  404): Daemon:genoff_persistent_update: Writing genoff = 349647 to memory
D/QC-time-services(  404): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  404): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  404): Updating the TOD offset
D/QC-time-services(  404): Daemon:genoff_persistent_update: Writing genoff = 349647 to memory
D/QC-time-services(  404): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  404): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  404): Daemon:Update to modem bit set
D/QC-time-services(  404): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  404): Daemon: Base = 2, Value being sent to MODEM = 18446743757745101263
,E/QC-time-services( 4015): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/GCM     ( 1336): GCM config loaded
I/ActivityManager( 1018): Killing 3170:android.process.media/u0a18 (adj 15): empty #9
E/QC-time-services(  404): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
E/QC-time-services(  404): Daemon: Time-services: Waiting to acceptconnection
,I/CheckinService( 1386): Checkin interval check for package: unspecified last checkin: 1447767616203 min interval config: 0 actual interval: 18298479
,I/EventLogService( 1386): Aggregate from 1447785913926 (log), 1447784061789 (data)
,D/DEBUG   ( 1534): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1534): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1534): ServiceHandler.handleMessage: mWaitCount=1
,D/EmailService.MarketingOptInSetter( 1534): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1534): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1534): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1018): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1534
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/OtaApp  ( 1534): [info] > Updatetime from metadata: 10
D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1534): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1534): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1534): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/MMApiWSBase( 1534): doRequest(): v1/ns/list/messages resp length: 1465
D/CCE     ( 1534): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
D/CCE     ( 1534): AppWSProxy - sendAIDLWSResponse() sending reponse
I/OtaApp  ( 1534): [info] > Updatetime from metadata: 10
D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1534): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1534): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1534): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1534): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1018): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1534
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1534): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1534): [info] > Updatetime from metadata: 10
,D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1534): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1534): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
,I/LaunchCheckinHandler( 1018): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,117
I/OtaApp  ( 1534): [info] > Updatetime from metadata: 10
D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1534): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1534): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1534): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1534): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/ActivityManager( 1018): Activity reported stop, but no longer stopping: ActivityRecord{430ef010 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
D/UdcCache:FPQuery( 1386): Bootstrapping UDC settings cache for all accounts
D/MMApiProvisionService( 1534): ProvisionWS.Response: processing response data: {"sessionToken":"0-62d6271415ae24024c051b549cbffe5b3369896958","error":"OK","sessionExpiration":"49142","deviceId":"1135300315450105856"}
D/MMApiProvisionService( 1534): ProvisionWS.Response: Completed parsing response.. no settings sent by server
D/MMApiWSBase( 1534): doRequest(): /v1/dp/devices.json resp length: 137
D/MMApiProvisionService( 1534): MMApiProvisionService.handleResponse (update_device) : true (None)
D/Checkin ( 1534): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/MMApiProvisionService( 1534): handleResponse(): Session Expiration alarm set to expire at: Wed Nov 18 09:24:16 CET 2015
,D/MMApiProvisionService( 1534): _setMMApiCredInfo: storing credential info 
,D/SundryService( 1534): handleGetNotificationsResponse(): got 0; more=false
,E/MMApiProvisionService( 1534): handleResponse(): no settings sent by the server:
,D/Checkin ( 1534): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1534): MMApiWebService told us to retry waiting request since device is successfully provisioned: 0
,D/DEBUG   ( 1534): Received intent : com.motorola.ccc.notification.action.NOTIFY
I/SundryService( 1534): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1534): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1534): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1534): ServiceHandler.handleMessage: mWaitCount=0
,D/DEBUG   ( 1534): Received intent : com.motorola.notification.RETREIVE_NOTIFICATIONS
,D/GetNotificationsWS( 1534): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1534): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1534): bindWebServices(): registering our AIDL callback...
I/SundryService( 1534): onHandleIntent(): action=com.motorola.notification.RETREIVE_NOTIFICATIONS
,I/SundryService( 1534): Received shoulder tap
D/GetNotificationsWS( 1534): onServiceConnected()
,D/GetNotificationsWS( 1534): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1534): setWaitEnabled(): mWaitCount=1 isWaitEnabled=true
,D/GetNotificationsWS( 1534): GetNotificationsWS.Request: message={"request":{"appendDeviceId":true,"baseUrl":"v1\/ns\/list\/messages","queryParams":{"appid":"MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ"},"httpMethod":"post","requestFormat":"json","wsReqId":"com.motorola.ccc.notification.GetNotificationsWS.Request","isSecure":true,"payload":{"data":"{\"appidNotifStoreMessageidPageSizeList\":[{\"appid\":\"LX6TJJI6F2MILF1NPZW6A3HBAKK8W44Z\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SULIGJDMXLSL7T1DOVYSTVG2KCBHZ5GH\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"6U5KK17SNFB416J4SYG7LC6HYFNOPYM8\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"68OUD4VKG23F7BUH6M2QBRXPLIC7IMCO\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SZZTNOGZA6O6PRFZH2V3FF14N1J8W3HC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"D9DF2F5BB1FA45B0BA459B7FE6942DCD\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"RCEAZODHQBX3UTIE62BUQ6T6TXXI6JSR\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"L71KGK4CCWOW658MGESIRYO2428ODW11\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"OCVKVSQ5Q1EYVBX76813UOPTCKGAH4VS\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"B642GFV24HEMEDQNCF3ZED8BIUMPCBOM\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"5LWTCLJBZO4OUDU5BY7ANJI4Y2MHY8OY\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"TESULHNZGDWZ5T3EMNZRTVE51RR7EUXC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"QZYSBKU4MGE71O1PLTE8HAT11SWL5M6E\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"XX274VEJBOVSSPHDKHSPURVRQ1YT5VEM\",\"pageSize\":100,\"notifStoreMessageid\":0}]}","type":"json"},"retries":"-1","useOAuth":true}}
D/GetNotificationsWS( 1534): sendAidlRequest(): was sent by CCE successfully!
,D/WaitableIntentService( 1534): ServiceHandler.handleMessage: mWaitCount=1
,D/MMApiWebService( 1534): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
I/MMApiWSBase( 1534): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1534): publish the event [tag = MOT_CCE event name = LOG]
,D/dalvikvm( 1336): GC_CONCURRENT freed 1908K, 39% free 10583K/17224K, paused 4ms+4ms, total 38ms
,D/GetConfigurationSnapshotOperation( 1336): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1336): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1336): Using platform SSLCertificateSocketFactory
,I/ActivityManager( 1018): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4043 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,D/ConnectivityService( 1018): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1286): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1286): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1286): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1286): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1080): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1080): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1080): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,W/dalvikvm( 4043): VFY: unable to resolve static field 529 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4043): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4043): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4043): VFY: unable to resolve virtual method 10979: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4043): VFY: replacing opcode 0x6e at 0x00ca
I/MultiDex( 4043): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4043): install
,I/MultiDex( 4043): MultiDexExtractor.load(/data/app/com.google.android.gms-2.apk, false)
,I/MultiDex( 4043): loading existing secondary dex files
,I/MultiDex( 4043): load found 3 secondary dex files
,I/MultiDex( 4043): install done
,D/dalvikvm( 4043): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4043): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4043): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4043): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4043): VFY: unable to resolve instance field 46
,D/dalvikvm( 4043): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4043): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4043): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4043): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4043): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4043): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 4043): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x428dda88
D/dalvikvm( 4043): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x428dda88
,D/dalvikvm( 4043): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x428dda88, skipping init
,D/dalvikvm( 4043): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x428dda88
D/dalvikvm( 4043): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x428dda88
,V/JNIHelp ( 4043): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/GetCommittedConfigurationOperation( 1336): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 4043): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x428dda88
,D/dalvikvm( 4043): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x428dda88
D/dalvikvm( 4043): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x428dda88
,D/dalvikvm( 4043): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428dda88
,I/ProviderInstaller( 4043): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1204): callingUid 10022, callindPid: 1204
,E/MDM     ( 1204): [75] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/GCM     ( 1336): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1336): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 1386): Restart initialization of location
,E/AuthorizationBluetoothService( 1336): Proximity feature is not enabled.
,I/dalvikvm( 4043): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
W/dalvikvm( 4043): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4043): VFY: replacing opcode 0x6e at 0x000d
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/dalvikvm( 4043): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 4043): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4043): VFY: replacing opcode 0x6e at 0x0220
,V/GmsCoreStatsServiceLauncher( 1386): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/MMApiWSBase( 1534): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1534): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1534): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/dalvikvm( 4043): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4043): Link of class 'Lcom/google/android/gms/common/h/c;' failed
E/dalvikvm( 4043): Could not find class 'com.google.android.gms.common.h.c', referenced from method com.google.android.gms.common.h.b.a
W/dalvikvm( 4043): VFY: unable to resolve new-instance 2668 (Lcom/google/android/gms/common/h/c;) in Lcom/google/android/gms/common/h/b;
D/dalvikvm( 4043): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4043): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.h.b.b
W/dalvikvm( 4043): VFY: unable to resolve virtual method 328: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4043): VFY: replacing opcode 0x6e at 0x0036
,D/Checkin ( 1534): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1534): handleGetNotificationsResponse(): got 0; more=false
,I/dalvikvm( 4043): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4043): Link of class 'Lcom/google/android/gms/common/h/c;' failed
,D/dalvikvm( 4043): DexOpt: unable to opt direct call 0x2d44 at 0x02 in Lcom/google/android/gms/common/h/b;.a
,D/DEBUG   ( 1534): Received intent : com.motorola.ccc.notification.action.NOTIFY
,I/CalendarProvider2( 3995): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3995): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/SundryService( 1534): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
,D/WaitableIntentService( 1534): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1534): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1534): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1534): unbindWebServices(): un-registering our AIDL callback...
,D/AlertReceiver( 3966): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/WVCdm   (  276): Instantiating CDM.
,I/WVCdm   (  276): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  276): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
,D/QSEECOMAPI: (  276): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  276): App is not loaded in QSEE
E/QSEECOMAPI: (  276): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  276): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  276): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  276): App is not loaded in QSEE
E/QSEECOMAPI: (  276): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  276): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  276): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  276): App is not loaded in QSEE
,D/dalvikvm( 1018): GC_EXPLICIT freed 961K, 65% free 17839K/49624K, paused 5ms+10ms, total 106ms
,D/QSEECOMAPI: (  276): Loaded image: APP id = 3
,D/DrmWidevineDash(  276): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb52a0000
,E/DrmWidevineDash(  276): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb52a0000
,I/dalvikvm( 4043): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 4043): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 4043): VFY: replacing opcode 0x6e at 0x0033
,D/DrmWidevineDash(  276): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  276): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  276): calling OEMCrypto_IsKeyboxValid...
,W/GCoreFlp( 1204): No location to return for getLastLocation()
,W/FusedLocationProvider( 1336): location=null
,W/dalvikvm( 4043): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4043): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/AlertService( 3966): 0 Action = android.intent.action.PROVIDER_CHANGED
,W/dalvikvm( 4043): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/DrmWidevineDash(  276): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  276): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  276): CdmEngine::OpenSession
,D/DrmWidevineDash(  276): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  276): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  276): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetRandom...
I/dalvikvm( 4043): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 4043): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 4043): VFY: replacing opcode 0x6e at 0x00bb
,D/DrmWidevineDash(  276): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  276): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,I/GoogleURLConnFactory( 4043): Using platform SSLCertificateSocketFactory
D/DrmWidevineDash(  276): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  276): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  276): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  276): PrepareKeyRequest: nonce=1249253761
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/GetCommittedConfigurationOperation( 1336): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/NativeLibraryUtils( 4043): Install completed successfully. count=13 extracted=0
,W/Uploader( 1336):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1336): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 1336): GC_CONCURRENT freed 1529K, 37% free 11007K/17224K, paused 3ms+5ms, total 32ms
D/GetCommittedConfigurationOperation( 1336): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1336): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 4043): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42c761a8
,D/dalvikvm( 4043): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42c761a8
,D/dalvikvm( 4043): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42c761a8, skipping init
,D/dalvikvm( 4043): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4077): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4043): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4043): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 70ms
,I/Adreno-EGL( 4043): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4043): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4043): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4043): Local Branch: 
I/Adreno-EGL( 4043): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4043): Local Patches: NONE
I/Adreno-EGL( 4043): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4043): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4043): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4043): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4043): Local Branch: 
I/Adreno-EGL( 4043): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4043): Local Patches: NONE
I/Adreno-EGL( 4043): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/WVCdm   (  276): CdmEngine::OpenSession
,D/DrmWidevineDash(  276): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  276): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  276): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  276): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  276): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  276): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  276): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  276): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  276): PrepareKeyRequest: nonce=1810526676
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,I/Adreno-EGL( 4043): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4043): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4043): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4043): Local Branch: 
I/Adreno-EGL( 4043): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4043): Local Patches: NONE
I/Adreno-EGL( 4043): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4043): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4043): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4043): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4043): Local Branch: 
I/Adreno-EGL( 4043): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4043): Local Patches: NONE
I/Adreno-EGL( 4043): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 4043): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1386): Classify the device as Phone.
,D/dalvikvm( 1386): GC_CONCURRENT freed 1752K, 34% free 11368K/17224K, paused 4ms+5ms, total 36ms
,I/CheckinTask( 1386): Sending checkin request (11906 bytes)
,I/CheckinResponseProcessor( 1386): From server: 2 gservices updates and 0 deletes
,E/UlpEngine( 1018): kvs.containsKey(ENH_LOCATION_SERVICES_ENABLED) returned false
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,E/UlpEngine( 1018): kvs.containsKey(ENH_LOCATION_SERVICES_ENABLED) returned false
,I/CertBlacklister( 1018): Certificate blacklist changed, updating...
,I/CertBlacklister( 1018): Certificate blacklist updated
W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,I/GservicesProvider( 1336): main difference update completed
,I/ActivityManager( 1018): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4093 uid=10009 gids={50009, 3003, 2001}
,I/CheckinRequestBuilder( 1386): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1386): Failed to find provider info for com.google.android.wearable.settings
,W/ContextImpl( 4093): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4093): Update started
,I/ActivityManager( 1018): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4114 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,E/UpdateRequestReceiver( 4093): Received malformed URL while handling Gservices.CHANGED_ACTION
,W/ContextImpl( 4093): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4093): Update started
,E/UpdateRequestReceiver( 4093): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4093): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4093): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ActivityManager( 1018): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=4142 uid=10025 gids={50025, 3003}
,D/dalvikvm( 4114): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x428e23b0, skipping init
I/openssl ( 4114): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4114): Crypto mode 0 already enabled
,I/CheckinRequestBuilder( 1386): Classify the device as Phone.
,I/ContactAccountLoggerTas( 2184): canRun() : Opted Out
,I/CheckinTask( 1386): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/Search.GservicesUpdateTask( 2184): Updating Gservices keys
,I/CheckinService( 1386): Checking schedule, now: 1447785918994 next: 1448378988971
,I/CheckinService( 1386): active receiver: disabled
,I/GAV2    ( 3901): Thread[GAThread,5,main]: No campaign data found.
,D/CheckinService( 1386): Recording last checkin time for package unspecified as 1447785919012
,D/dalvikvm( 3494): GC_CONCURRENT freed 611K, 5% free 16487K/17224K, paused 4ms+6ms, total 53ms
,I/DownloadManager( 4114): Download 203 starting
,W/ActivityThread( 4114): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/DownloadManager( 4114): Download 204 starting
,I/ContactAccountLoggerTas( 2184): canRun() : Opted Out
I/ActivityManager( 1018): Killing 3857:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ContactAccountLoggerTas( 2184): canRun() : Opted Out
,I/ActivityManager( 1018): Killing 3843:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ContactAccountLoggerTas( 2184): canRun() : Opted Out
,I/dalvikvm( 1386): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 1386): VFY: unable to resolve static method 1165: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 1386): VFY: replacing opcode 0x71 at 0x0046
,D/dalvikvm( 3494): GC_FOR_ALLOC freed 150K, 4% free 18311K/19004K, paused 17ms, total 17ms
,D/dalvikvm( 1336): GC_EXPLICIT freed 1113K, 37% free 10873K/17224K, paused 2ms+5ms, total 34ms
,D/dalvikvm( 1386): GC_EXPLICIT freed 1262K, 35% free 11324K/17224K, paused 3ms+6ms, total 38ms
,I/DownloadManager( 4114): Ignoring Content-Length since Transfer-Encoding is also defined
,D/Checkin ( 4114): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,I/DownloadManager( 4114): Download 204 finished with status SUCCESS
,D/dalvikvm( 1336): GC_EXPLICIT freed 153K, 38% free 10810K/17224K, paused 2ms+4ms, total 33ms
,I/DownloadManager( 4114): Ignoring Content-Length since Transfer-Encoding is also defined
,D/SystemEventReceiver( 1386): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1386): Updating ocr activity enabled=false
,D/Checkin ( 4114): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,I/DownloadManager( 4114): Download 203 finished with status SUCCESS
,I/Auth    ( 1336): [BroadcastManager] Broadcasting account services changed.
I/ActivityManager( 1018): Killing 3901:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1018): GC_EXPLICIT freed 838K, 65% free 17763K/49624K, paused 4ms+10ms, total 103ms
,W/ActivityManager( 1018): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,I/CheckinService( 1386): Checkin interval check for package: unspecified last checkin: 1447785919012 min interval config: 0 actual interval: 812
,I/SystemUpdateService( 1386): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,I/CheckinService( 1386): Checking schedule, now: 1447785919845 next: 1448378988971
,I/CheckinService( 1386): active receiver: disabled
,D/SystemUpdateService( 1386): onCreate
,D/SystemUpdateService( 1386): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/OcrModelManager( 1386): Updating downloaded model state (gservices changed)
,I/SystemUpdateService( 1386): cancelUpdate (empty URL)
,I/SystemUpdateService( 1386): active receiver: disabled
,D/SystemUpdateService( 1386): onDestroy
,D/GCM     ( 1336): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/GCoreUlr( 1204): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1204): DispatchingService.onCreate()
,D/GCM     ( 1336): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GCoreUlr( 1204): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/ContextImpl( 4093): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,I/openssl ( 4114): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4114): Crypto mode 0 already enabled
,W/ContextImpl( 4093): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,I/GCoreUlr( 1204): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1204): Unbound from all location providers
,D/GCM     ( 1336): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GCoreUlr( 1204): DispatchingService.onDestroy()
,I/GCoreUlr( 1204): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1204): Unbound from all location providers
,I/DownloadManager( 4114): Download 205 starting
,I/DownloadManager( 4114): Ignoring Content-Length since Transfer-Encoding is also defined
,I/DownloadManager( 4114): Download 206 starting
,I/DownloadManager( 4114): Ignoring Content-Length since Transfer-Encoding is also defined
,D/Checkin ( 4114): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,I/ContactAccountLoggerTas( 2184): canRun() : Opted Out
,I/DownloadManager( 4114): Download 205 finished with status SUCCESS
,D/Checkin ( 4114): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,W/ContextImpl( 4093): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4093): Update downloaded, starting installation
,I/UpdateFetcherService( 4093): Started installation
,I/DownloadManager( 4114): Download 206 finished with status SUCCESS
,W/ContextImpl( 4093): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4093): Update downloaded, starting installation
,I/UpdateFetcherService( 4093): Started installation
,I/ConfigUpdateInstallReceiver( 1018): Not installing, new version is <= current version
,I/GlobalDismissManager( 3966): no sender configured
,D/AlertService( 3966): Beginning updateAlertNotification
,D/AlertService( 3966): No fired or scheduled alerts
,D/AlertService( 3966): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 3966): No events found starting within 1 week.
I/ActivityManager( 1018): Killing 3995:com.android.providers.calendar/u0a8 (adj 15): empty #9
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Killing 4015:com.qualcomm.timeservice/u0a98 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/CaptivePortalTracker( 1018): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1018): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1018): Checking http://216.58.209.46/generate_204
,I/dalvikvm( 1018): Jit: resizing JitTable from 8192 to 16384
W/ActivityThread( 1018): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/CaptivePortalTracker( 1018): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1018): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1018): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1018): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1018): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/Launcher( 1298): Deferring update until onResume
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4227 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
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
I/Launcher( 1298): Deferring update until onResume
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
,I/Babel   ( 4227): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4227): MmsConfig.loadMmsSettings
,I/Babel   ( 4227): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4227): MmsConfig.loadFromDatabase
,E/Babel   ( 4227): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4227): MmsConfig.loadFromResources
,E/Babel   ( 4227): canonicalizeMccMnc: invalid mccmnc nullnull
,V/GmsNetworkLocationProvi( 1204): DISABLE
,I/Babel   ( 4227): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4227): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/GCoreNlp( 1204): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager( 1018): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4260 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/GAV2    ( 3494): Thread[GAThread,5,main]: No campaign data found.
,D/dalvikvm( 1018): GC_EXPLICIT freed 1782K, 64% free 17977K/49624K, paused 5ms+10ms, total 95ms
,I/ActivityManager( 1018): Killing 3985:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4282 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1018): Killing 3966:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2184): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1018): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4298 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1018): Killing 4142:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4260): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4298): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4298): VFY: unable to resolve virtual method 616: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 4298): VFY: replacing opcode 0x6e at 0x000d
,D/Finsky  ( 4298): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 4298): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4298): VFY: unable to resolve virtual method 547: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4298): VFY: replacing opcode 0x6e at 0x01d3
,I/InternalIcingCorporaPro( 2184): UpdateCorporaTask done [took 216 ms] updated apps [took 216 ms] 
,I/dalvikvm( 4298): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4298): VFY: unable to resolve virtual method 612: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4298): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4298): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4298): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4298): VFY: unable to resolve virtual method 337: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4298): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4298): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4298): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4298): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4298): VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4298): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4298): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4298): VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4298): VFY: replacing opcode 0x6e at 0x0392
I/dalvikvm( 4298): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4298): VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4298): VFY: replacing opcode 0x6e at 0x0398
,I/dalvikvm( 4298): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4298): VFY: unable to resolve virtual method 8983: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4298): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4298): Skipping gmscore version check
,D/Finsky  ( 4298): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4298): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 4298): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/dalvikvm( 4298): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
,W/dalvikvm( 4298): VFY: unable to resolve virtual method 612: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4298): VFY: replacing opcode 0x6e at 0x0017
,D/PackageBroadcastService( 1386): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1386): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1386): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 4298): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1018): Killing 3886:com.google.android.setupwizard/u0a41 (adj 15): empty #9
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 3595): Attempting to connect to the test coordinator server
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): Attempting to connect to the test coordinator server
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): Attempting to connect to the test coordinator server
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): Attempting to connect to the test coordinator server
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): Attempting to connect to the test coordinator server
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): Attempting to connect to the test coordinator server
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): Test app app.js loaded
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): {"type":"test","name":"setup","id":0}
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): LogCallback not set !!!!
I/jxcore-log( 3595): 
,W/IInputConnectionWrapper( 3595): showStatusIcon on inactive InputConnection
,I/chromium( 3595): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3595): DBG, CoordinatorConnector connect called
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): DBG, CoordinatorConnector connect called
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): DBG, CoordinatorConnector connect called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): DBG, CoordinatorConnector connect called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): DBG, CoordinatorConnector connect called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): DBG, CoordinatorConnector connect called
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): DBG, CoordinatorConnector connect called
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): DBG, CoordinatorConnector too_late called
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): {"id":0,"ok":false,"name":"Coordinator server got disconnected","operator":"fail","error":{},"test":0,"type":"assert"}
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1018): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@4425bc68 mBinding = false
,D/BluetoothManagerService( 1018): Message: 2
,W/Settings( 1258): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/BluetoothManagerService( 1018): Sending off request.
W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
D/BluetoothAdapterState( 3650): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3650): Setting state to 13
I/BluetoothAdapterState( 3650): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 3650): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterProperties( 3650): onBluetoothDisable()
I/BluetoothAdapterState( 3650): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/BluetoothAdapterProperties( 3650): adapterPropertyChangedCallback with type:7 len:4
,W/Settings( 1258): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/BluetoothAdapterProperties( 3650): Scan Mode:21
D/BluetoothAdapterState( 3650): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 3650): bta_jv_rfcomm_stop_server
E/bt-btif ( 3650): bta_jv_rfcomm_stop_server
E/BtOppRfcommListener( 3650): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btif ( 3650): bta_jv_rfcomm_stop_server
E/bt-btif ( 3650): bta_jv_rfcomm_stop_server
V/BluetoothFtpService:RfcommSocketAcceptThread( 3650): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/BluetoothManagerService( 1018): Message: 60
D/BluetoothManagerService( 1018): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
W/bt-btif ( 3650): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 3650): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3650): L2CAP - PSM: 0x0017 not found for deregistration
D/BluetoothManagerService( 1018): Bluetooth State Change Intent: 12 -> 13
D/btif_config_util( 3650): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
D/BluetoothMapService( 3650): onReceive
D/BluetoothMapService( 3650): STATE_TURNING_OFF removeTimeoutMsg:false
D/BluetoothMapService( 3650): MAP Service closeService in
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
I/ActivityManager( 1018): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=4353 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/BtOppRfcommListener( 3650): stopping Accept Thread
I/BtOppRfcommListener( 3650): BluetoothSocket listen thread finished
W/Settings( 1258): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiStateMachine( 1018): handleMessage: E msg.what=131084
D/WifiStateMachine( 1018): processMsg: ConnectedState
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): transitionTo: destState=WaitForP2pDisableState
W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
D/WifiStateMachine( 1018): invokeExitMethods: ConnectedState
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiStateMachine( 1018): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1018): Stopping DHCP and clearing IP
D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 true
W/Settings( 1258): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiP2pService( 1018): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
D/CommandListener(  269): Clearing all IP addresses on wlan0
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
D/TCMD    (  422): NL - Read 60 bytes from update socket.
D/TCMD    (  422): NL - ignore NL message, type = 21
D/TCMD    (  422): Listening for incoming client connection request
D/WifiStateMachine( 1018): addressRemoved: 192.168.1.123/24 on wlan0 flags 128 scope 0
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
D/WifiStateMachine( 1018): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiStateMachine( 1018): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/WifiMetrics( 1018): connected time updated 16084
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1018): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1018): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1018): invokeExitMethods: ConnectModeState
D/WifiStateMachine( 1018): invokeExitMethods: DriverStartedState
D/Checkin ( 1018): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/ConnectivityService( 1018): Attempting to switch to mobile
D/ConnectivityService( 1018): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1018): Attempting to switch to ETHERNET
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/SBar.NetworkController( 1080): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
E/WifiStateMachine( 1018): Unexpected BatchedScanResults :OK
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
D/WifiStateMachine( 1018): invokeEnterMethods: WaitForP2pDisableState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131216
D/WifiStateMachine( 1018): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131216
D/WifiP2pService( 1018): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pDisablingState
D/WifiP2pService( 1018): P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): p2p socket connection lost
D/WifiP2pService( 1018): P2pDisabledState
D/WifiStateMachine( 1018): handleMessage: E msg.what=131205
D/WifiStateMachine( 1018): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1018): transitionTo: destState=SupplicantStoppingState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1018): invokeExitMethods: WaitForP2pDisableState
D/WifiStateMachine( 1018): invokeExitMethods: SupplicantStartedState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/WifiStateMachine( 1018): invokeEnterMethods: SupplicantStoppingState
D/WifiStateMachine( 1018): Stopping DHCP and clearing IP
D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 true
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
D/WifiP2pService( 1018): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/WifiP2pService( 1018): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  269): Clearing all IP addresses on wlan0
D/ConnectivityService( 1018): resetConnections(wlan0, 3)
D/NetUtils( 1018): android_net_utils_resetConnections in env=0x6123d030 clazz=0x64c00001 iface=wlan0 mask=0x3
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
V/NativeCrypto( 1336): Read error: ssl=0x62980550: I/O error during system call, Connection timed out
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
V/NativeCrypto( 1336): SSL shutdown failed: ssl=0x62980550: I/O error during system call, Broken pipe
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
W/ContextImpl( 4353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/WifiStateMachine( 1018): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
D/WifiStateMachine( 1018): stopping supplicant
D/Checkin ( 1018): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
D/BluetoothPbapService( 3650): action: android.bluetooth.adapter.action.STATE_CHANGED
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiStateMachine( 1018): setWifiState: disabling
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1018): handleMessage: X
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
I/SBar.NetworkController( 1080): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
D/BluetoothManagerService( 1018): Message: 20
D/BluetoothManagerService( 1018): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@430fc378:true
W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
W/XTWiFiOS( 1268): Active network info is not available
I/SBar.NetworkController( 1080): refreshSignalCluster: wifi: mWifiConnected=false Wifi=(none) Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
W/bt-btif ( 3650): ag scb idx 1 not allocated
E/bt-btif ( 3650): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3650): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3650): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3650): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3650): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3650): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3650): L2CAP - PSM: 0x0017 not found for deregistration
I/bt_hwcfg( 3650): hw_epilog_process
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
E/XTCC-3.0.0.2(  483): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  483): [WwanPosMgr] handleConnectivtyStatusChange failed
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): Message: 30
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=false
,I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/ConnectivityService( 1018): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
I/ModemStatsDSDetect( 1286): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
I/ModemStatsDSDetect( 1286): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1286): onReceive() - done, currentInetCondition=0
,D/ConnectivityService( 1018): Attempting to switch to mobile
,I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/ConnectivityService( 1018): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1018): Attempting to switch to ETHERNET
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
E/XTCC-3.0.0.2(  483): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  483): [CSMgr] handleConnectivtyStatusChange failed
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
,W/ContextImpl( 4353): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): Message: 30
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
,W/ContextImpl( 4353): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
I/bt_hwcfg( 3650): hw_epilog_cback Opcode:0x0C03 Status: 0
I/bt_hci_bdroid( 3650): bt_hc_worker_thread exiting
D/LocalBluetoothProfileManager( 4353): Adding local MAP profile
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
D/bt_userial_mct( 3650): userial_close
I/bt_userial_mct( 3650): exiting userial_read_thread
D/bt_userial_mct( 3650): Leaving userial_evt_read_thread()
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
D/BluetoothMap( 4353): Create BluetoothMap proxy object
D/BluetoothManagerService( 1018): Message: 30
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3595): 
I/ModemStatsDSDetect( 1286): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
,W/ContextImpl( 4353): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
I/ModemStatsDSDetect( 1286): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1286): onReceive() - done, currentInetCondition=0
D/BluetoothManagerService( 1018): Message: 30
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
,W/ContextImpl( 4353): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
D/LocalBluetoothProfileManager( 4353): LocalBluetoothProfileManager construction complete
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/wpa_supplicant( 3731): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/TCMD    (  422): NL - Read 1000 bytes from update socket.
D/TCMD    (  422): NL - message type is RTM_NEWLINK
D/TCMD    (  422): Listening for incoming client connection request
D/TCMD    (  422): NL - Read 68 bytes from update socket.
D/TCMD    (  422): NL - message type is RTM_NEWLINK
D/TCMD    (  422): Listening for incoming client connection request
D/TCMD    (  422): NL - Read 68 bytes from update socket.
D/TCMD    (  422): NL - message type is RTM_NEWLINK
D/TCMD    (  422): Listening for incoming client connection request
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  272): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  272):  STA Disconnected !!
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): get_property_value, Enter
I/MDMCTBK (  272): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  272): get_property_value, Exit
I/MDMCTBK (  272): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  272): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  272): set_property_value, Enter
I/MDMCTBK (  272): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
I/MDMCTBK (  272): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  272): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  272): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  272): set_property_value, Enter
I/MDMCTBK (  272): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
E/MDMCTBK (  272): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
D/Tethering( 1018): InitialState.processMessage what=4
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
D/Tethering( 1018): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/WifiStateMachine( 1018): handleMessage: E msg.what=147460
D/WifiStateMachine( 1018): processMsg: SupplicantStoppingState
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1018): handleMessage: E msg.what=131101
D/WifiStateMachine( 1018): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
D/DockEventReceiver( 4353): finishStartingService: stopping service
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService( 1018): New client listening to asynchronous messages
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
I/wpa_supplicant( 3731): eap_proxy Deinitialzed
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
,D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 6
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/BluetoothInputDevice( 4353): Proxy object connected
,D/HidProfile( 4353): Bluetooth service connected
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
V/BluetoothFtpReceiver( 3650): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothPan( 4353): BluetoothPAN Proxy object connected
D/PanProfile( 4353): Bluetooth service connected
D/BluetoothMap( 4353): Proxy object connected
D/MapProfile( 4353): Bluetooth service connected
D/BluetoothMap( 4353): getConnectedDevices()
D/TCMD    (  422): NL - Read 1000 bytes from update socket.
D/TCMD    (  422): NL - message type is RTM_NEWLINK
D/TCMD    (  422): Listening for incoming client connection request
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
I/wpa_supplicant( 3731): wlan0: CTRL-EVENT-TERMINATING 
D/BluetoothMap( 4353): Bluetooth is Not enabled
D/AuthorizationBluetoothService( 1336): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  272): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  272):  Wpa Supplicant Exiting !!
D/MDMCTBK (  272): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  272): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  272): wifi_close_sockets: Exit
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiStateMachine( 1018): handleMessage: E msg.what=147458
D/WifiStateMachine( 1018): processMsg: SupplicantStoppingState
,D/WifiStateMachine( 1018): Supplicant connection lost
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
I/ActivityManager( 1018): Killing 4093:com.google.android.configupdater/u0a9 (adj 15): empty #9
E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
D/BTSNOOP-DISP( 3650): btsnoop_close
I/bt_vendor( 3650): cleanup
I/bt_hwcfg( 3650): Starting hciattach daemon
I/bt_hwcfg( 3650): try to set false
I/GKI_LINUX( 3650): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3650): GKI_exit_task: GKI_exit_task 0 done
I/GKI_LINUX( 3650): GKI_destroy_task: GKI_shutdown(): task [BTU] terminated
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothAdapterState( 3650): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
D/HeadsetService( 3650): Received stop request...Stopping profile...
D/BluetoothHeadset( 1018): Proxy object disconnected
D/BluetoothHeadset( 1240): Proxy object disconnected
D/BluetoothHeadset( 1240): Proxy object disconnected
D/BluetoothHeadset( 1240): Proxy object disconnected
D/A2dpService( 3650): Received stop request...Stopping profile...
D/A2dpStateMachine( 3650): Exit Disconnected: -1
D/BluetoothAdapterState( 3650): Stopping profile services that were post enabled
D/BluetoothA2dp( 1018): Proxy object disconnected
D/BluetoothAdapterService( 3650): Profile still running: com.android.bluetooth.hdp.HealthService
D/HidService( 3650): Received stop request...Stopping profile...
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
W/BluetoothHeadsetServiceJni( 3650): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3650): Cleaning up Bluetooth Handsfree callback object
D/BluetoothInputDevice( 4353): Proxy object disconnected
D/HidProfile( 4353): Bluetooth service disconnected
D/HealthService( 3650): Received stop request...Stopping profile...
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/PanService( 3650): Received stop request...Stopping profile...
D/BluetoothTethering( 1018): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering( 1018): attempted to stop reverse tether with nothing tethered
D/BluetoothPan( 1018): BluetoothPAN Proxy object disconnected
D/BluetoothTethering( 1018): Disconnect CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@442022f0
D/BluetoothTethering( 1018): got CMD_CHANNEL_DISCONNECTED
D/BtGatt.DebugUtils( 3650): handleDebugAction() action=null
D/BluetoothPan( 4353): BluetoothPAN Proxy object disconnected
D/BtGatt.GattService( 3650): Received stop request...Stopping profile...
D/PanProfile( 4353): Bluetooth service disconnected
D/BtGatt.GattService( 3650): stop()
D/BluetoothAdapterService( 3650): Profile still running: com.android.bluetooth.hdp.HealthService
D/BluetoothMapService( 3650): Received stop request...Stopping profile...
D/BluetoothMapService( 3650): stop()
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
D/BluetoothMapService( 3650): MAP Service closeService in
D/BluetoothMap( 4353): Proxy object disconnected
D/MapProfile( 4353): Bluetooth service disconnected
I/GKI_LINUX( 3650): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3650): GKI_exit_task: GKI_exit_task 2 done
I/GKI_LINUX( 3650): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BluetoothAdapterService( 3650): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 3650): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3650): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3650): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 3650): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 3650): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3650): Cleaning up Bluetooth Health object
D/BluetoothAdapterService( 3650): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 3650): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3650): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService( 3650): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/BluetoothMapService( 3650): cleanup()
D/BluetoothMapService( 3650): MAP Service closeService in
D/BluetoothAdapterState( 3650): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3650): Setting state to 10
I/BluetoothAdapterState( 3650): Bluetoot,h adapter state changed: 13-> 10
D/BluetoothAdapterService( 3650): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1018): Message: 60
D/BluetoothManagerService( 1018): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
I/BluetoothAdapterState( 3650): Entering OffState
D/BluetoothManagerService( 1018): Broadcasting onBluetoothStateChange(false) to 10 receivers.
D/BluetoothPan( 4353): onBluetoothStateChange on: false
D/BluetoothHeadset( 1240): onBluetoothStateChange: up=false
D/BluetoothPan( 1018): onBluetoothStateChange on: false
D/BluetoothPbap( 4353): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1240): onBluetoothStateChange: up=false
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/BluetoothHeadset( 1240): onBluetoothStateChange: up=false
D/BluetoothMap( 4353): onBluetoothStateChange: up=false
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
,D/BluetoothHeadset( 1018): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1018): onBluetoothStateChange: up=false
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
D/BluetoothInputDevice( 4353): onBluetoothStateChange: up=false
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
D/BluetoothManagerService( 1018): Broadcasting onBluetoothServiceDown() to 9 receivers.
,I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@4425bc68 mBinding = false
D/BluetoothManagerService( 1018): Sending unbind request.
D/BluetoothManagerService( 1018): Bluetooth State Change Intent: 13 -> 10
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothAdapter( 1080): 1118115608: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1204): 1120674712: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1204): 1120674712: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapterService( 3650): Cleaning up adapter native....
I/GKI_LINUX( 3650): gki_task_entry: gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 3650): GKI_exit_task: GKI_exit_task 1 done
,I/GKI_LINUX( 3650): GKI_destroy_task: GKI_shutdown(): task [BTIF] terminated
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.sendDeviceAttachIntent:820 com.motorola.authentication.MotAuthenticationService.access$1300:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:575 
I/BluetoothServiceJni( 3650): cleanupNative: return from cleanup
D/BluetoothAdapterService( 3650): Done cleaning up adapter native....
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.handleKeepDeviceUnlockRequest:732 com.motorola.authentication.MotAuthenticationService.access$1500:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:563 
D/BluetoothAdapterService(1116648768)( 3650): ****onDestroy()********
D/BtGatt.GattService( 3650): cleanup()
W/bt-btif ( 3650): GATTC Module not enabled/already disabled
W/bt-btif ( 3650): GATTS Module not enabled/already disabled
,I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
W/ContextImpl( 4353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/DockEventReceiver( 4353): finishStartingService: stopping service
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/BluetoothAdapter( 4353): 1116694544: getState() :  mService = null. Returning STATE_OFF
V/BluetoothFtpReceiver( 3650): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
V/BluetoothFtpReceiver( 3650): BluetoothFtpReceiver Stop Service
V/BluetoothFtpService( 3650): Ftp Service onDestroy
V/BluetoothFtpService( 3650): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3650): Shutdown
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
D/AuthorizationBluetoothService( 1336): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
I/ActivityManager( 1018): Killing 4043:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): The client has disconnected!
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): Turning radios to false
I/jxcore-log( 3595): 
,I/ActivityManager( 1018): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.ConnectedUnlockReceiver: pid=4390 uid=10016 gids={50016, 3002}
D/WifiStateMachine( 1018): setWifiState: disabled
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
W/Settings( 4227): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine( 1018): transitionTo: destState=InitialState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1018): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
D/WifiStateMachine( 1018): invokeEnterMethods: InitialState
,I/jxcore-log( 3595): toggleBluetooth - 
I/jxcore-log( 3595): 
D/WifiService( 1018): setWifiEnabled: false pid=3595, uid=10377
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/SBar.NetworkController( 1080): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1268): Active network info is not available
I/jxcore-log( 3595): toggleWiFi
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
E/XTCC-3.0.0.2(  483): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  483): [WwanPosMgr] handleConnectivtyStatusChange failed
W/Settings( 1204): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
D/dalvikvm(  274): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+2ms, total 21ms
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): DBG, CoordinatorConnector too_late called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now,.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): DBG, CoordinatorConnector too_late called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
E/XTCC-3.0.0.2(  483): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  483): [CSMgr] handleConnectivtyStatusChange failed
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): DBG, CoordinatorConnector too_late called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 19ms
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): DBG, CoordinatorConnector too_late called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): DBG, CoordinatorConnector too_late called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): DBG, CoordinatorConnector too_late called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
D/BluetoothAdapter( 4353): 1116694544: getState() :  mService = null. Returning STATE_OFF
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): got too_late event, closing connection now.
I/jxcore-log( 3595): 
I/jxcore-log( 3595): CoordinatorConnector close called
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 3595): 
I/chromium( 3595): [INFO:CONSOLE(63)] "logCallback 0 isOK: false : Coordinator server got disconnected", source: file:///android_asset/www/js/thali_main.js (63)
I/ActivityManager( 1018): Killing 4227:com.google.android.talk/u0a70 (adj 15): empty #9
D/Checkin ( 4390): publish the event [tag = DEVICE_AUTH_STATS_L2 event name = DEVAUTH_CONNECT]
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Checkin ( 2147): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2147): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/AndroidRuntime( 4405): 
D/AndroidRuntime( 4405): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4405): CheckJNI is OFF
,D/dalvikvm( 4405): Trying to load lib libjavacore.so 0x0
,D/AndroidRuntime( 4407): 
D/AndroidRuntime( 4407): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4409): 
D/AndroidRuntime( 4409): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4407): CheckJNI is OFF
,D/dalvikvm( 4405): Added shared lib libjavacore.so 0x0
,D/AndroidRuntime( 4409): CheckJNI is OFF
D/dalvikvm( 4405): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4405): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4405): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4407): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4407): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 4409): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4407): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4407): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4407): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4409): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 4409): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4409): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4409): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4405): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,D/dalvikvm( 4407): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,D/NetlinkEvent(  269): Unexpected netlink message. type=0x11
W/Netd    (  269): No subsystem found in netlink event
D/TCMD    (  422): NL - Read 444 bytes from update socket.
D/TCMD    (  422): NL - ignore NL message, type = 17
D/TCMD    (  422): Listening for incoming client connection request
,I/MDMCTBK (  272): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  272): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  272): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  272): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  272): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  272): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  272): set_property_value, Enter
,I/MDMCTBK (  272): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
I/MDMCTBK (  272): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  272): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  272): set_property_value, Enter
I/MDMCTBK (  272): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
,E/MDMCTBK (  272): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/dalvikvm( 4409): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,D/Checkin ( 2147): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2147): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/TCMD    (  422): NL - Read 1000 bytes from update socket.
D/TCMD    (  422): NL - message type is RTM_NEWLINK
,D/TCMD    (  422): Listening for incoming client connection request
,D/TCMD    (  422): NL - Read 444 bytes from update socket.
,D/NetlinkEvent(  269): Unexpected netlink message. type=0x11
W/Netd    (  269): No subsystem found in netlink event
D/TCMD    (  422): NL - ignore NL message, type = 17
D/TCMD    (  422): Listening for incoming client connection request
I/MDMCTBK (  272): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  272): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  272): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  272): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  272): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  272): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
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
,E/memtrack( 4405): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4405): failed to load memtrack module: -2
E/memtrack( 4407): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4407): failed to load memtrack module: -2
,E/memtrack( 4409): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4409): failed to load memtrack module: -2
,D/AndroidRuntime( 4405): Calling main entry com.android.commands.pm.Pm
,D/AndroidRuntime( 4407): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10377 user=-1: uninstall pkg
,I/ActivityManager( 1018): Killing 3595:com.test.thalitest/u0a377 (adj 9): stop com.test.thalitest
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018):   Force finishing activity ActivityRecord{44f33290 u0 com.test.thalitest/.MainActivity t3}
,D/AndroidRuntime( 4409): Calling main entry com.android.commands.pm.Pm
,I/WindowState( 1018): WIN DEATH: Window{44ff0df0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1018): Client connection lost with reason: 4
,W/PackageSettings( 1018): Skipping PackageSetting{42bdbec8 com.example.hello/10376} due to missing metadata
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10377 user=0: pkg removed
,D/Checkin ( 2147): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/dalvikvm( 2184): GC_EXPLICIT freed 3343K, 42% free 10073K/17224K, paused 2ms+4ms, total 38ms
,D/dalvikvm( 2147): GC_EXPLICIT freed 5976K, 44% free 9753K/17224K, paused 3ms+6ms, total 41ms
,W/GeofencerStateMachine( 1204): Ignoring removeGeofence because network location is disabled.
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,D/dalvikvm( 1298): GC_EXPLICIT freed 2796K, 33% free 11592K/17224K, paused 2ms+5ms, total 72ms
,I/Launcher( 1298): Deferring update until onResume
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
I/LatinIME:LogUtils( 1187): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1187): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/VoicemailCleanupService( 4260): Cleaning up data for package: com.test.thalitest
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
,D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 1018): removePackageParticipantsLocked: uid=10377 #1
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
,I/InternalIcingCorporaPro( 2184): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 1018):   Scheme: "smsto"
,I/ActivityManager( 1018): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4442 uid=10059 gids={50059, 3003, 1028, 1015}
I/Launcher( 1298): Deferring update until onResume
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
,I/LatinIME:LogUtils( 1187): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1447785927
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
,I/InternalIcingCorporaPro( 2184): UpdateCorporaTask done [took 104 ms] updated apps [took 104 ms] 
,I/LatinIME:LogUtils( 1187): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1447785927
,D/dalvikvm( 1018): GC_EXPLICIT freed 1922K, 64% free 18087K/49624K, paused 4ms+13ms, total 193ms
,D/AndroidRuntime( 4405): Shutting down VM
,D/dalvikvm( 4405): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10377 user=-1: uninstall pkg
D/Checkin ( 2147): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/dalvikvm( 1018): Total arena pages for JIT: 15
,W/PackageSettings( 1018): Skipping PackageSetting{42bdbec8 com.example.hello/10376} due to missing metadata
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10377 user=0: pkg removed
,W/GeofencerStateMachine( 1204): Ignoring removeGeofence because network location is disabled.
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
I/Launcher( 1298): Deferring update until onResume
I/LatinIME:LogUtils( 1187): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1187): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
,I/Launcher( 1298): Deferring update until onResume
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=196614
D/WifiStateMachine( 1018): processMsg: InitialState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131208
D/WifiStateMachine( 1018): processMsg: InitialState
,D/WifiStateMachine( 1018): processMsg: DefaultState
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131208
D/WifiStateMachine( 1018): processMsg: InitialState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131208
D/WifiStateMachine( 1018): processMsg: InitialState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
,D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 1018): removePackageParticipantsLocked: uid=10377 #1
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
,I/LatinIME:LogUtils( 1187): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1447785927
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
,D/dalvikvm( 1018): GC_EXPLICIT freed 1066K, 64% free 18031K/49624K, paused 5ms+11ms, total 163ms
W/PackageManager( 1018): Package source /data/app/com.test.thalitest-1.apk does not exist.
,W/PackageManager( 1018): Couldn't delete native library directory /data/app-lib/com.test.thalitest-1
D/AndroidRuntime( 4407): Shutting down VM
I/LatinIME:LogUtils( 1187): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1447785927
D/dalvikvm( 4407): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10377 user=-1: uninstall pkg
,W/ActiveOrDefaultContextProvider( 4442): Missing scope.enter somewhere. Returning default context
,F/PackageManager( 1018): Unable to write package manager settings, current changes will be lost at reboot
F/PackageManager( 1018): java.io.IOException: write failed: EBADF (Bad file number)
F/PackageManager( 1018): 	at libcore.io.IoBridge.write(IoBridge.java:455)
F/PackageManager( 1018): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
F/PackageManager( 1018): 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
F/PackageManager( 1018): 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
F/PackageManager( 1018): 	at com.android.internal.util.FastXmlSerializer.flush(FastXmlSerializer.java:254)
F/PackageManager( 1018): 	at com.android.internal.util.FastXmlSerializer.append(FastXmlSerializer.java:73)
F/PackageManager( 1018): 	at com.android.internal.util.FastXmlSerializer.attribute(FastXmlSerializer.java:168)
F/PackageManager( 1018): 	at com.android.server.pm.Settings.writePackageLPr(Settings.java:1546)
F/PackageManager( 1018): 	at com.android.server.pm.Settings.writeLPr(Settings.java:1328)
F/PackageManager( 1018): 	at com.android.server.pm.PackageManagerService.removePackageDataLI(PackageManagerService.java:9492)
F/PackageManager( 1018): 	at com.android.server.pm.PackageManagerService.deleteInstalledPackageLI(PackageManagerService.java:9637)
F/PackageManager( 1018): 	at com.android.server.pm.PackageManagerService.deletePackageLI(PackageManagerService.java:9746)
F/PackageManager( 1018): 	at com.android.server.pm.PackageManagerService.deletePackageX(PackageManagerService.java:9353)
F/PackageManager( 1018): 	at com.android.server.pm.PackageManagerService.access$4100(PackageManagerService.java:178)
F/PackageManager( 1018): 	at com.android.server.pm.PackageManagerService$7.run(PackageManagerService.java:9287)
F/PackageManager( 1018): 	at android.os.Handler.handleCallback(Handler.java:733)
F/PackageManager( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:95)
F/PackageManager( 1018): 	at android.os.Looper.loop(Looper.java:136)
F/PackageManager( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/PackageManager( 1018): Caused by: libcore.io.ErrnoException: write failed: EBADF (Bad file number)
F/PackageManager( 1018): 	at libcore.io.Posix.writeBytes(Native Method)
F/PackageManager( 1018): 	at libcore.io.Posix.write(Posix.java:202)
F/PackageManager( 1018): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
F/PackageManager( 1018): 	at libcore.io.IoBridge.write(IoBridge.java:450)
F/PackageManager( 1018): 	... 18 more
,E/DropBoxManagerService( 1018): Can't write: system_server_wtf
E/DropBoxManagerService( 1018): java.io.FileNotFoundException: /data/system/dropbox/drop27.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1018): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1018): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1018): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1018): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10230)
E/DropBoxManagerService( 1018): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10135)
E/DropBoxManagerService( 1018): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10022)
E/DropBoxManagerService( 1018): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService( 1018): 	at android.util.Log$1.onTerribleFailure(Log.java:111)
E/DropBoxManagerService( 1018): 	at android.util.Log.wtf(Log.java:477)
E/DropBoxManagerService( 1018): 	at android.util.Log.wtf(Log.java:470)
E/DropBoxManagerService( 1018): 	at com.android.server.pm.Settings.writeLPr(Settings.java:1469)
E/DropBoxManagerService( 1018): 	at com.android.server.pm.PackageManagerService.removePackageDataLI(PackageManagerService.java:9492)
E/DropBoxManagerService( 1018): 	at com.android.server.pm.PackageManagerService.deleteInstalledPackageLI(PackageManagerService.java:9637)
E/DropBoxManagerService( 1018): 	at com.android.server.pm.PackageManagerService.deletePackageLI(PackageManagerService.java:9746)
E/DropBoxManagerService( 1018): 	at com.android.server.pm.PackageManagerService.deletePackageX(PackageManagerService.java:9353)
E/DropBoxManagerService( 1018): 	at com.android.server.pm.PackageManagerService.access$4100(PackageManagerService.java:178)
E/DropBoxManagerService( 1018): 	at com.android.server.pm.PackageManagerService$7.run(PackageManagerService.java:9287)
E/DropBoxManagerService( 1018): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 1018): 	at android.os.Looper.loop(Looper.java:136)
E/DropBoxManagerService( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 1018): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1018): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1018): 	... 23 more
,F/PackageManager( 1018): Failed to clean up mangled file: /data/system/packages.xml
E/DropBoxManagerService( 1018): Can't write: system_server_wtf
E/DropBoxManagerService( 1018): java.io.FileNotFoundException: /data/system/dropbox/drop27.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1018): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1018): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1018): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1018): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10230)
E/DropBoxManagerService( 1018): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10135)
E/DropBoxManagerService( 1018): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10022)
E/DropBoxManagerService( 1018): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService( 1018): 	at android.util.Log$1.onTerribleFailure(Log.java:111)
E/DropBoxManagerService( 1018): 	at android.util.Log.wtf(Log.java:477)
E/DropBoxManagerService( 1018): 	at android.util.Log.wtf(Log.java:440)
E/DropBoxManagerService( 1018): 	at com.android.server.pm.Settings.writeLPr(Settings.java:1475)
E/DropBoxManagerService( 1018): 	at com.android.server.pm.PackageManagerService.removePackageDataLI(PackageManagerService.java:9492)
E/DropBoxManagerService( 1018): 	at com.android.server.pm.PackageManagerService.deleteInstalledPackageLI(PackageManagerService.java:9637)
E/DropBoxManagerService( 1018): 	at com.android.server.pm.PackageManagerService.deletePackageLI(PackageManagerService.java:9746)
E/DropBoxManagerService( 1018): 	at com.android.server.pm.PackageManagerService.deletePackageX(PackageManagerService.java:9353)
E/DropBoxManagerService( 1018): 	at com.android.server.pm.PackageManagerService.access$4100(PackageManagerService.java:178)
E/DropBoxManagerService( 1018): 	at com.android.server.pm.PackageManagerService$7.run(PackageManagerService.java:9287)
E/DropBoxManagerService( 1018): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 1018): 	at android.os.Looper.loop(Looper.java:136)
E/DropBoxManagerService( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 1018): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1018): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1018): 	... 23 more
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10377 user=0: pkg removed
,I/Launcher( 1298): Deferring update until onResume
,W/GeofencerStateMachine( 1204): Ignoring removeGeofence because network location is disabled.
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,E/SQLiteLog( 1298): (3850) statement aborts at 30: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,E/SQLiteLog( 2147): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/LatinIME:LogUtils( 1187): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
E/SQLiteDatabase( 2147): Error inserting state=an=null au=null avc=-1 avn=null name=com.test.thalitest st=2 timestamp=1447785928085 timezone=3600 name=PackageInfoTrigger
E/SQLiteDatabase( 2147): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2147): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2147): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2147): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2147): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2147): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2147): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2147): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2147): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2147): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2147): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2147): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2147): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2147): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2147): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2147): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/PackageManager( 1018): Unable to backup user packages state file, current changes will be lost at reboot
I/LatinIME:LogUtils( 1187): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/LatinIME:LogUtils( 1187): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1447785927
,E/DropBoxManagerService( 1018): Can't write: system_server_wtf
E/DropBoxManagerService( 1018): java.io.FileNotFoundException: /data/system/dropbox/drop67.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1018): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1018): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1018): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1018): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10230)
E/DropBoxManagerService( 1018): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10135)
E/DropBoxManagerService( 1018): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10022)
E/DropBoxManagerService( 1018): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService( 1018): 	at android.util.Log$1.onTerribleFailure(Log.java:111)
E/DropBoxManagerService( 1018): 	at android.util.Log.wtf(Log.java:477)
E/DropBoxManagerService( 1018): 	at android.util.Log.wtf(Log.java:440)
E/DropBoxManagerService( 1018): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1046)
E/DropBoxManagerService( 1018): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:10124)
E/DropBoxManagerService( 1018): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:10180)
E/DropBoxManagerService( 1018): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:974)
E/DropBoxManagerService( 1018): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1538)
E/DropBoxManagerService( 1018): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 1018): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 1018): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1018): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1018): 	... 19 more
,I/Launcher( 1298): Deferring update until onResume
,E/SQLiteDatabase( 4442): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4442): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4442): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4442): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4442): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4442): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4442): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4442): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4442): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4442): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4442): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4442): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4442): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4442): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4442): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4442): 	at vR.b(ClientFlagDatabaseImpl.java:148)
E/SQLiteDatabase( 4442): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:205)
E/SQLiteDatabase( 4442): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1030)
E/SQLiteDatabase( 4442): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4409)
E/SQLiteDatabase( 4442): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4442): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteDatabase( 4442): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4442): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4442): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4442): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4442): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4442): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4442): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4442): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4442): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4442): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4442): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4442): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4442): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4442): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4442): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4442): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4442): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 4442): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 4442): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4442): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 4442): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 4442): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4442): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4442): 	at vR.b(ClientFlagDatabaseImpl.java:148)
E/SQLiteOpenHelper( 4442): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:205)
E/SQLiteOpenHelper( 4442): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1030)
E/SQLiteOpenHelper( 4442): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4409)
E/SQLiteOpenHelper( 4442): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 4442): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteOpenHelper( 4442): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4442): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 4442): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteOpenHelper( 4442): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4442): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4442): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteOpenHelper( 4442): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteOpenHelper( 4442): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4442): Opened ClientFlag.db in read-only mode
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
F/PackageManager( 1018): Unable to backup user packages state file, current changes will be lost at reboot

```
