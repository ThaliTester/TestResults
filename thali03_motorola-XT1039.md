#### Test 50650278c0f6ec2_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1021): sending alarm Alarm{43905cf0 type 2 com.motorola.ccc.cce}
--------- beginning of /dev/log/main
I/PollingManager( 1539): alarm fired!
D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
D/AndroidRuntime( 3538): 
D/AndroidRuntime( 3538): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3538): CheckJNI is OFF
D/dalvikvm( 3538): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3538): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3538): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3538): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3538): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3538): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3538): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3538): failed to load memtrack module: -2
D/AndroidRuntime( 3538): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1021): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3538
W/WindowManager( 1021): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1021): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3554 uid=10458 gids={50458, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3538): Shutting down VM
D/dalvikvm( 3538): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+1ms, total 2ms
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3554): Binding Chromium to main looper Looper (main, tid 1) {426a87f8}
I/LibraryLoader( 3554): Expected native library version number "",actual native library version number ""
I/chromium( 3554): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3554): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1021): Message: 20
D/BluetoothManagerService( 1021): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4442cb08:true
D/BluetoothAdapter( 3554): 1114363336: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3554): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3554): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3554): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3554): Local Branch: 
I/Adreno-EGL( 3554): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3554): Local Patches: NONE
I/Adreno-EGL( 3554): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3554): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3554): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 3554): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3554): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3554): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3554): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3554): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3554): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 3554): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3554): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3554): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3554): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3554): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3554): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3554): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3554): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3554): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3554): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3554): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3554): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3554): Enabling debug mode 0
,W/AwContents( 3554): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3554): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1021): Displayed com.test.thalitest/.MainActivity,cp,ca,396
I/ActivityManager( 1021): Displayed com.test.thalitest/.MainActivity: +369ms (total +396ms)
,D/JsMessageQueue( 3554): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3554): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x426acbf0
,D/dalvikvm( 3554): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x426acbf0
,D/jxcore_app_log( 3554): JniHelper::setJavaVM(0x41dcbf78), pthread_self() = 1614222664
,D/JX-Cordova( 3554): jxcore cordova android initializing
,I/dalvikvm( 3554): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 3554): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 3554): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 3554): GC_CONCURRENT freed 2802K, 17% free 14365K/17224K, paused 2ms+2ms, total 67ms
,D/dalvikvm( 3554): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 3554): GC_FOR_ALLOC freed 112K, 17% free 14366K/17224K, paused 25ms, total 26ms
,D/dalvikvm( 3554): GC_FOR_ALLOC freed 301K, 17% free 14431K/17224K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3554): Grow heap (frag case) to 16.262MB for 143930-byte allocation
,D/dalvikvm( 3554): GC_FOR_ALLOC freed 266K, 17% free 14468K/17368K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3554): Grow heap (frag case) to 16.367MB for 215890-byte allocation
,D/dalvikvm( 3554): GC_FOR_ALLOC freed 368K, 18% free 14541K/17580K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3554): Grow heap (frag case) to 16.541MB for 323830-byte allocation
,D/dalvikvm( 3554): GC_FOR_ALLOC freed 567K, 19% free 14662K/17900K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3554): Grow heap (frag case) to 16.814MB for 485740-byte allocation
,D/dalvikvm( 3554): GC_FOR_ALLOC freed 864K, 20% free 14837K/18376K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3554): Grow heap (frag case) to 17.216MB for 728606-byte allocation
,D/dalvikvm( 3554): GC_FOR_ALLOC freed 1283K, 21% free 15093K/19088K, paused 28ms, total 28ms
,D/dalvikvm( 3554): GC_CONCURRENT freed 1677K, 19% free 15463K/19088K, paused 1ms+3ms, total 35ms
,D/dalvikvm( 3554): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 3554): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 3554): GC_FOR_ALLOC freed 366K, 20% free 15419K/19088K, paused 26ms, total 27ms
,I/dalvikvm-heap( 3554): Grow heap (frag case) to 18.654MB for 1639352-byte allocation
,D/dalvikvm( 3554): GC_CONCURRENT freed 1725K, 23% free 15995K/20692K, paused 2ms+5ms, total 46ms
,D/dalvikvm( 3554): GC_FOR_ALLOC freed 1331K, 23% free 16064K/20692K, paused 30ms, total 30ms
,I/dalvikvm-heap( 3554): Grow heap (frag case) to 20.065MB for 2459024-byte allocation
,D/dalvikvm( 3554): GC_CONCURRENT freed 207K, 21% free 18346K/23096K, paused 5ms+4ms, total 37ms
,D/dalvikvm( 3554): GC_CONCURRENT freed 4395K, 27% free 17047K/23096K, paused 2ms+7ms, total 48ms
,D/dalvikvm( 3554): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/dalvikvm-heap( 3554): Grow heap (frag case) to 22.198MB for 3688532-byte allocation
,D/dalvikvm( 3554): GC_CONCURRENT freed 2857K, 32% free 18206K/26700K, paused 2ms+8ms, total 77ms
,D/dalvikvm( 3554): GC_FOR_ALLOC freed 716K, 33% free 17973K/26700K, paused 28ms, total 28ms
,W/jxcore-log( 3554): Initializing JXcore engine
,W/jxcore-log( 3554): JXcore engine is ready
,D/dalvikvm( 3554): GC_CONCURRENT freed 354K, 23% free 20595K/26700K, paused 1ms+3ms, total 32ms
,D/dalvikvm( 3554): WAIT_FOR_CONCURRENT_GC blocked 29ms
,W/jxcore-log( 3554): Starting JXcore engine
,W/jxcore-log( 3554): Platform android
W/jxcore-log( 3554): 
,W/jxcore-log( 3554): Process ARCH arm
W/jxcore-log( 3554): 
,I/jxcore-log( 3554): JXcore Cordova bridge is ready!
I/jxcore-log( 3554): 
,W/jxcore-log( 3554): JXcore engine is started
,I/chromium( 3554): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3554): Toggling radios to true
I/jxcore-log( 3554): 
D/BluetoothManagerService( 1021): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1021): enable():  mBluetooth =null mBinding = false
,W/Settings( 1250): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/Settings( 1250): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/BluetoothManagerService( 1021): Message: 1
W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
D/BluetoothManagerService( 1021): MESSAGE_ENABLE: mBluetooth = null
,W/XTWiFiOS( 1268): Active network info is not available
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,I/ActivityManager( 1021): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3608 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1023}
,D/WifiService( 1021): New client listening to asynchronous messages
D/WifiService( 1021): setWifiEnabled: true pid=3554, uid=10458
,E/WifiService( 1021): Invoking mWifiStateMachine.setWifiEnabled
,W/Settings( 1250): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiStateMachine( 1021): setting operational mode to 1
D/WifiStateMachine( 1021): handleMessage: E msg.what=131083
D/WifiStateMachine( 1021): processMsg: InitialState
,W/Settings( 1250): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
I/jxcore-log( 3554): Radios toggled
I/jxcore-log( 3554): 
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1268): Active network info is not available
,D/AdapterServiceConfig( 3608): Adding HeadsetService
D/AdapterServiceConfig( 3608): Adding A2dpService
D/AdapterServiceConfig( 3608): Adding HidService
D/AdapterServiceConfig( 3608): Adding HealthService
D/AdapterServiceConfig( 3608): Adding PanService
D/AdapterServiceConfig( 3608): Adding GattService
,D/AdapterServiceConfig( 3608): Adding BluetoothMapService
,D/BluetoothAdapterService( 3608): REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothManagerService( 1021): Message: 20
,D/BluetoothManagerService( 1021): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@443a3838:true
,D/BluetoothAdapterState( 3608): make
,I/BluetoothAdapterState( 3608): Entering OffState
,I/bluedroid( 3608): init
,I/bte_conf( 3608): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bluedroid( 3608): get_profile_interface socket
,D/BluetoothManagerService( 1021): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1021): Message: 40
,D/BluetoothManagerService( 1021): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3608): config_hci_snoop_log
D/BluetoothManagerService( 1021): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService( 1021): Broadcasting onBluetoothServiceUp() to 7 receivers.
,I/GKI_LINUX( 3608): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
,I/BluetoothAdapterProperties( 3608): adapterPropertyChangedCallback with type:2 len:6
,D/BluetoothAdapterState( 3608): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 3608): Address is:F4:F1:E1:5C:3B:E2
D/BluetoothAdapterProperties( 3608): Setting state to 11
I/BluetoothAdapterState( 3608): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3608): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService( 1021): Message: 60
D/BluetoothManagerService( 1021): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService( 1021): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3608): make
,I/BluetoothAdapterProperties( 3608): adapterPropertyChangedCallback with type:1 len:6
,I/BluetoothBondStateMachine( 3608): StableState(): Entering Off State
,I/ActivityManager( 1021): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3633 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/BluetoothAdapterProperties( 3608): Name is: XT1039
D/BluetoothManagerService( 1021): Bluetooth Adapter name changed to XT1039
D/BluetoothHeadset( 1239): Proxy object connected
D/BluetoothManagerService( 1021): Stored Bluetooth name: XT1039
D/BluetoothHeadset( 1239): Proxy object connected
D/BluetoothHeadset( 1021): Proxy object connected
D/BluetoothHeadset( 1239): Proxy object connected
D/HeadsetService( 3608): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3608): classInitNative: succeeds
D/HeadsetStateMachine( 3608): Version 1.6
D/HeadsetStateMachine( 3608): make
,I/bluedroid( 3608): get_profile_interface handsfree
,I/BluetoothAdapterState( 3608): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothA2dp( 1021): Proxy object connected
D/A2dpService( 3608): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3608): classInitNative: succeeds
V/Avrcp   ( 3608): make
I/bluedroid( 3608): get_profile_interface avrcp
,I/BluetoothA2dpServiceJni( 3608): classInitNative: succeeds
,D/A2dpStateMachine( 3608): make
,I/bluedroid( 3608): get_profile_interface a2dp
,I/GKI_LINUX( 3608): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 3608): warning : no command pending, ignore ack
,D/A2dpStateMachine( 3608): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3608): classInitNative: succeeds
,D/HidService( 3608): Received start request. Starting profile...
,I/bluedroid( 3608): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 3608): classInitNative: succeeds
,D/HealthService( 3608): Received start request. Starting profile...
,I/bluedroid( 3608): get_profile_interface health
,I/BluetoothPanServiceJni( 3608): classInitNative(L105): succeeds
,D/BluetoothPan( 1021): BluetoothPAN Proxy object connected
D/PanService( 3608): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3608): initializeNative(L110): pan
,I/bluedroid( 3608): get_profile_interface pan
,D/BluetoothTethering( 1021): got CMD_CHANNEL_HALF_CONNECTED
,D/BluetoothTethering( 1021): CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@44186760
,I/BtGatt.JNI( 3608): classInitNative(L684): classInitNative: Success!
,D/BtGatt.DebugUtils( 3608): handleDebugAction() action=null
D/BtGatt.GattService( 3608): Received start request. Starting profile...
D/BtGatt.GattService( 3608): start()
,I/bluedroid( 3608): get_profile_interface gatt
,D/BluetoothMapService( 3608): Received start request. Starting profile...
,D/BluetoothMapService( 3608): start()
,D/HeadsetPhoneState( 3608): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetPhoneState( 3608): onSignalStrengthsChanged..for signal  prevSignal=0
D/BluetoothAdapterService( 3608): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/HeadsetPhoneState( 3608): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterService( 3608): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3608): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 3608): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 3608): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3608): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterState( 3608): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3608): enable
,I/ActivityManager( 1021): Killing 3287:com.android.calendar/u0a7 (adj 15): empty #9
I/bt_hci_bdroid( 3608): init
I/bt_vendor( 3608): bt-vendor : init
I/bt_hci_bdroid( 3608): ro.qualcomm.hci_transport set to smd
D/bt_userial_mct( 3608): userial_init
I/bt_hwcfg( 3608): Starting hciattach daemon
I/bt_hwcfg( 3608): try to set false
,I/bt_hci_bdroid( 3608): bt_hc_worker_thread started
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/bt_hwcfg( 3608): Starting hciattach daemon
I/bt_hwcfg( 3608): try to set true
,I/qcom-bluetooth( 3669): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,D/WifiService( 1021): New client listening to asynchronous messages
I/MDMCTBK (  276): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  276): NetlinkHandler, interfaceAdded
I/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
E/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  276): , Wifi = 0
I/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/Tethering( 1021): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/Tethering( 1021): sendTetherStateChangedBroadcast 1, 0, 0
D/TCMD    (  447): NL - Read 1004 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
D/TCMD    (  447): Listening for incoming client connection request
D/Tethering( 1021): InitialState.processMessage what=4
D/Tethering( 1021): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/Tethering( 1021): sendTetherStateChangedBroadcast 0, 0, 0
I/MDMCTBK (  276): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  276): NetlinkHandler, interfaceAdded
I/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
E/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  276): , Wifi = 0
I/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/TCMD    (  447): NL - Read 1004 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
D/TCMD    (  447): Listening for incoming client connection request
,I/qcom-bluetooth( 3678): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 3679): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
D/QsoftapCmd(  274): Got softap fwreload command we are passing on
,D/SoftapController(  274): Softap fwReload - Ok
,I/qcom-bluetooth( 3682): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 3683): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
D/CommandListener(  274): Setting iface cfg
D/CommandListener(  274): Trying to bring down wlan0
,I/qcom-bluetooth( 3684): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,V/BluetoothFtpReceiver( 3608): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,D/AuthorizationBluetoothService( 2013): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/WifiHW  ( 1021): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
,E/WifiHW  ( 1021): ctrl_interface != /data/misc/wifi/sockets
E/Diag_Lib( 3686): qmi_init:  Not initialized, calling process init sequence
E/Diag_Lib( 3686): Setting internal use port to rmnet0
E/Diag_Lib( 3686):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,E/Diag_Lib( 3686): Failed on DIAG init
E/Diag_Lib( 3686): linux_qmi_qmux_if_client_get_proc_name: pid=3686, proc_name=hci_qcomm_init
E/Diag_Lib( 3686): linux_qmi_qmux_if_client_get_socket_paths: num_grps=2
E/Diag_Lib( 3686): linux_qmi_qmux_if_client_get_proc_group_name: gid=1002, grp_name=bluetooth
E/Diag_Lib( 3686): using socket paths bind=/dev/socket/qmux_bluetooth/qmux_client_socket, connect=/dev/socket/qmux_bluetooth/qmux_connect_socket
E/Diag_Lib( 3686): qmi_client [3686]: successfully connected to server, attempt=1
E/Diag_Lib( 3686): linux_qmi_qmux_if_client_get_client_id [3686]: qmux_client_id=13
E/Diag_Lib( 3686): qmi_client [3686] 13: qmux_client ID is initialized
E/Diag_Lib( 3686): qmi_client [3686] 13: pipe() system call, fd[0]=10, fd[1]=11
,E/Diag_Lib( 3686): qmi_client [3686] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3686): qmi_client [3686] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3686): Sending signal ...... to read cmd data 
E/Diag_Lib( 3686): qmi error code.........:0
E/Diag_Lib( 3686): qmi sys error code.........:0
E/Diag_Lib( 3686): qmi_qmux_if_pwr_up_init_ex:  Successfully created and added QMUX client 19
E/Diag_Lib( 3686): qmi_nas_srvc_init: NAS successfully initialized
E/Diag_Lib( 3686): qmi_qos_srvc_init: QOS successfully initialized
E/Diag_Lib( 3686): qmi_eap_srvc_init: EAP successfully initialized
E/Diag_Lib( 3686): qmi_wds_srvc_init: WDS successfully initialized
E/Diag_Lib( 3686): qmi_atcop_srvc_init: ATCOP successfully initialized
E/Diag_Lib( 3686): qmi_uim_srvc_init: UIM successfully initialized
E/Diag_Lib( 3686): qmi_cat_srvc_init: CAT successfully initialized
E/Diag_Lib( 3686): qmi_init:  Created client handle b8c93788
,E/Diag_Lib( 3686): qmi_client [3686] 13: sending 880 bytes on fd = 8
,E/Diag_Lib( 3686): qmi_client [3686] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3686): Sending signal ...... to read cmd data 
E/Diag_Lib( 3686): qmi error code.........:0
,E/Diag_Lib( 3686): qmi sys error code.........:0
E/Diag_Lib( 3686): Setting the api flag to : 1
,E/Diag_Lib( 3686): qmi_client [3686] 13: sending 54 bytes on fd = 8
,I/wpa_supplicant( 3689): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3689): rfkill: Cannot open RFKILL control device
D/TCMD    (  447): NL - Read 1000 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
,D/TCMD    (  447): Listening for incoming client connection request
D/TCMD    (  447): NL - Read 1000 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
,D/TCMD    (  447): Listening for incoming client connection request
,D/WifiStateMachine( 1021): setWifiState: enabling
D/WifiStateMachine( 1021): Supplicant start successful
,D/WifiMonitor( 1021): startMonitoring(wlan0) with mConnected = false
I/rmt_storage(  407): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8de01d0
I/rmt_storage(  407): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  407): wakelock acquired: 1, error no: 42
,I/rmt_storage(  407): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1193409992)
E/Diag_Lib( 3686): qmi_client [3686] 13: Received 54 bytes on fd = 8
E/Diag_Lib( 3686):  API Flag .............. 1 
,E/Diag_Lib( 3686):  Message ID ............... 92 
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1084): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1268): Active network info is not available
,E/Diag_Lib( 3689): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 3689): Setting internal use port to rmnet0
,E/wpa_supplicant( 3689): baseband property is set to [msm]
,E/wpa_supplicant( 3689):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3689): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3689): card_info[i].card_state: 0x2
E/wpa_supplicant( 3689): card_info[i].error_code: 0x3
E/wpa_supplicant( 3689): SIM/USIM not ready
,E/wpa_supplicant( 3689): Error while reading SIM card status
,E/wpa_supplicant( 3689): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3689): card_info[i].card_state: 0x2
E/wpa_supplicant( 3689): card_info[i].error_code: 0x3
E/wpa_supplicant( 3689): SIM/USIM not ready
,I/wpa_supplicant( 3689): eap_proxy: Card not ready
E/Diag_Lib( 3686): qmi_service_release called, user_handle=30200
E/Diag_Lib( 3686): qmi_free_srvc_data : ENTRY
E/Diag_Lib( 3686): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib( 3686): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib( 3686): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib( 3686): qmi_service_delete_client_txns : ENTRY - conn_id=0, service=2, client=3
E/Diag_Lib( 3686): qmi_service_delete_client_txns : EXIT
E/Diag_Lib( 3686): qmi_free_srvc_data : EXIT
,E/Diag_Lib( 3686): qmi_client [3686] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3686): qmi_client [3686] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3686): Sending signal ...... to read cmd data 
E/Diag_Lib( 3686): qmi error code.........:0
E/Diag_Lib( 3686): qmi sys error code.........:0
E/Diag_Lib( 3686): qmi_release: Released client handle ff
E/Diag_Lib( 3686): qmi_release: Last client releases, performing library de-init
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=0
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=1
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=2
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=3
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=4
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=5
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=6
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=7
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=8
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=9
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=10
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=11
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=12
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=13
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=14
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=15
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=16
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=17
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=18
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=19
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=20
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=21
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=22
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=23
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=24
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=25
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=26
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=27
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=28
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=29
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=30
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=31
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=32
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=33
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=34
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=35
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=36
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=37
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=38
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=39
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=40
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=41
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=42
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=43
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=44
E/Diag_Lib( 3686): Call,ed qmi_service_reset_all, release on modem=1, conn_id=45
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=46
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=47
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=48
E/Diag_Lib( 3686): Called qmi_service_reset_all, release on modem=1, conn_id=49
E/Diag_Lib( 3686): qmi_nas_srvc_release: NAS successfully released
E/Diag_Lib( 3686): qmi_qos_srvc_release: QOS successfully released
E/Diag_Lib( 3686): qmi_eap_srvc_release: EAP successfully released
E/Diag_Lib( 3686): qmi_wds_srvc_release: WDS successfully released
E/Diag_Lib( 3686): qmi_atcop_srvc_release: ATCOP successfully released
E/Diag_Lib( 3686): qmi_nas_srvc_release: UIM successfully released
E/Diag_Lib( 3686): qmi_cat_srvc_release: CAT successfully released
E/Diag_Lib( 3686): qmi_client [3686] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3686): qmi_client [3686] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3686): Sending signal ...... to read cmd data 
E/Diag_Lib( 3686): qmi error code.........:0
E/Diag_Lib( 3686): qmi sys error code.........:0
E/Diag_Lib( 3686): qmi_qmux_if_pwr_down_release: Released QMUX client handle [3686] 13
E/Diag_Lib( 3686): qmi_client [3686] 13: Client release, writing pipe to kill read thread, fd = 11
E/Diag_Lib( 3686): qmi_client [3686] 13: failed to locate client data
E/Diag_Lib( 3686): qmi_client [3686] 13: calling release of fd=8
,E/Diag_Lib( 3686): qmi_qmux_if_pwr_down_release: Last client releases, performing de-init
,I/rmt_storage(  407): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  407): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  407): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1193409992) wakelock released: 1, error no: 0
I/rmt_storage(  407): 
,I/rmt_storage(  407): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb8de01d0
,D/Checkin ( 2153): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2153): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/wpa_supplicant( 3689): Long line in configuration file truncated
,I/wpa_supplicant( 3689): rfkill: Cannot open RFKILL control device
D/TCMD    (  447): NL - Read 1000 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
,D/TCMD    (  447): Listening for incoming client connection request
,I/qcom-bluetooth( 3692): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 f4:f1:e1:5c:3b:e2 
,I/qcom-bluetooth( 3693): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/bt_hwcfg( 3608): bluetooth satus is on
I/GKI_LINUX( 3608): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3608): btu_task pending for preload complete event
,D/bt_userial_mct( 3608): userial_open(port:0)
I/bt_userial_vendor( 3608): Done intiailizing UART
I/bt_userial_vendor( 3608): Done intiailizing UART
,I/bt_userial_mct( 3608): CMD=72, EVT=72, ACL_Out=73, ACL_In=73
I/bt_vendor( 3608): Bluetooth Firmware and smd is initialized
D/bt_userial_mct( 3608): Entering userial_read_thread()
,I/bt-btu  ( 3608): btu_task received preload complete event
I/        ( 3608): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3608): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3608): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3608): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3608): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3608): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3608): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3608): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3608): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3608): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3608): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3608): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3608): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3608): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 3608): BTE_InitTraceLevels -- TRC_BTIF
,E/wpa_supplicant( 3689): COUNTRY Code Recived
,E/wpa_supplicant( 3689): COUNTRY Code Recived -COUNTRY PL
,E/wpa_supplicant( 3689): baseband property is set to [msm]
,E/bt-btm  ( 3608): BTM_SecRegister:p_cb_info->p_le_callback == 0x5f106049 
,E/bt-btm  ( 3608): BTM_SecRegister: btm_cb.api.p_le_callback = 0x5f106049 
,E/wpa_supplicant( 3689):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3689): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3689): card_info[i].card_state: 0x2
E/wpa_supplicant( 3689): card_info[i].error_code: 0x3
E/wpa_supplicant( 3689): SIM/USIM not ready
,E/wpa_supplicant( 3689): Error while reading SIM card status
,E/bt-btif ( 3608): Calling BTA_HhEnable
E/bt-btif ( 3608): btif_storage_get_adapter_property service_mask:0x140040
I/BluetoothAdapterProperties( 3608): adapterPropertyChangedCallback with type:2 len:6
E/wpa_supplicant( 3689): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3689): card_info[i].card_state: 0x2
E/wpa_supplicant( 3689): card_info[i].error_code: 0x3
E/wpa_supplicant( 3689): SIM/USIM not ready
,I/wpa_supplicant( 3689): eap_proxy: Card not ready
D/BluetoothAdapterProperties( 3608): Address is:F4:F1:E1:5C:3B:E2
,I/BluetoothAdapterProperties( 3608): adapterPropertyChangedCallback with type:1 len:6
D/BluetoothAdapterProperties( 3608): Name is: XT1039
I/BluetoothAdapterProperties( 3608): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothManagerService( 1021): Bluetooth Adapter name changed to XT1039
,D/BluetoothManagerService( 1021): Stored Bluetooth name: XT1039
D/BluetoothAdapterProperties( 3608): Scan Mode:21
I/BluetoothAdapterProperties( 3608): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3608): Discoverable Timeout:120
I/BluetoothAdapterProperties( 3608): adapterPropertyChangedCallback with type:8 len:0
,I/BluetoothAdapterProperties( 3608): adapterPropertyChangedCallback with type:3 len:48
,I/bte_conf( 3608): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 3608): [1] primary_record=1 vendor_id=0x001D vendor_id_source=0x0001 product_id=0x1200 version=0x1436
E/bt_mct  ( 3608): hci lib postload completed
,I/bte_conf( 3608): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 3608): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothAdapterState( 3608): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothPanServiceJni( 3608): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
D/BluetoothAdapterProperties( 3608): ScanMode =  21
D/BluetoothAdapterProperties( 3608): State =  11
D/BluetoothAdapterProperties( 3608): Setting state to 12
I/BluetoothAdapterState( 3608): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterService( 3608): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1021): Message: 60
D/BluetoothManagerService( 1021): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,I/BluetoothAdapterState( 3608): Entering On State
D/BluetoothManagerService( 1021): Broadcasting onBluetoothStateChange(true) to 6 receivers.
,D/BluetoothHeadset( 1239): onBluetoothStateChange: up=true
,D/BluetoothAdapterService(1114351040)( 3608): Get Bonded Devices being called
D/BluetoothHeadset( 1239): onBluetoothStateChange: up=true
D/BluetoothPan( 1021): onBluetoothStateChange on: true
D/BluetoothHeadset( 1239): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1021): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1021): onBluetoothStateChange: up=true
I/BluetoothAdapterProperties( 3608): adapterPropertyChangedCallback with type:9 len:4
,D/BluetoothAdapterProperties( 3608): Discoverable Timeout:120
,D/BluetoothAdapterService(1114351040)( 3608): Get Bonded Devices being called
,D/BluetoothManagerService( 1021): Bluetooth State Change Intent: 11 -> 12
,D/WifiStateMachine( 1021): transitionTo: destState=SupplicantStartingState
,D/BluetoothManagerService( 1021): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothMapService( 3608): onReceive
D/BluetoothMapService( 3608): STATE_ON
D/BluetoothManagerService( 1021): Message: 40
,D/BluetoothManagerService( 1021): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapService( 3608): Map Service startRfcommSocketListener
,D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/BluetoothAdapterService(1114351040)( 3608): Get Bonded Devices being called
D/WifiStateMachine( 1021): invokeExitMethods: InitialState
,D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine( 1021): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=131144
D/WifiStateMachine( 1021): processMsg: SupplicantStartingState
D/WifiStateMachine( 1021): deferMessage: msg=131144
D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=131085
D/WifiStateMachine( 1021): processMsg: SupplicantStartingState
D/WifiStateMachine( 1021): deferMessage: msg=131085
D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=131149
D/WifiStateMachine( 1021): processMsg: SupplicantStartingState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): setSuspendOptimizations: 2 true
D/WifiStateMachine( 1021): mSuspendOptNeedsDisabled 0
,D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=131145
D/WifiStateMachine( 1021): processMsg: SupplicantStartingState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=131146
D/WifiStateMachine( 1021): processMsg: SupplicantStartingState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131101
D/WifiStateMachine( 1021): processMsg: SupplicantStartingState
,D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131101
D/WifiStateMachine( 1021): processMsg: SupplicantStartingState
D/WifiStateMachine( 1021): processMsg: DefaultState
,D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147457
D/WifiStateMachine( 1021): processMsg: SupplicantStartingState
,D/WifiStateMachine( 1021): Supplicant connection established
,D/BluetoothMapService( 3608): Map Service initSocket
D/WifiStateMachine( 1021): setWifiState: enabled
,D/WifiConfigStore( 1021): Loading config and enabling all networks
,I/qcom-bt-wlan-coex( 3707): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,D/BluetoothManagerService( 1021): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/SBar.NetworkController( 1084): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1268): Active network info is not available
,E/WifiConfigStore( 1021): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
E/wpa_supplicant( 3689): COUNTRY Code Recived -COUNTRY PL
,W/BluetoothAdapter( 3608): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3608): SOCK FLAG = 1 ***********************
I/BluetoothAdapterProperties( 3608): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothMapService( 3608): Accepting socket connection...
,D/BluetoothAdapterProperties( 3608): Scan Mode:21
,I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1084): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1084): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,W/ContextImpl( 3633): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/WifiStateMachine( 1021): transitionTo: destState=DriverStartedState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1021): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=1,j=1
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
D/WifiStateMachine( 1021): invokeEnterMethods: SupplicantStartedState
D/WifiStateMachine( 1021): invokeEnterMethods: DriverStartedState
D/WifiStateMachine( 1021): setDetailed state, old =IDLE and new state=DISCONNECTED
E/wpa_supplicant( 3689): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 3689): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1021): Attempting to reconnect to wifi network ..
D/BluetoothPbapService( 3608): action: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothPbapService( 3608): Handler(): got msg=1
D/WifiStateMachine( 1021): transitionTo: destState=DisconnectedState
D/BluetoothManagerService( 1021): Message: 20
D/BluetoothManagerService( 1021): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43f73cc0:true
,D/BluetoothManagerService( 1021): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/WifiP2pService( 1021): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine( 1021): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=1,j=3
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
D/WifiStateMachine( 1021): invokeEnterMethods: ConnectModeState
D/WifiStateMachine( 1021): invokeEnterMethods: DisconnectedState
W/BluetoothAdapter( 3608): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3608): SOCK FLAG = 1 ***********************
D/CommandListener(  274): Setting iface cfg
D/CommandListener(  274): Trying to bring up p2p0
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131144
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131085
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiMonitor( 1021): startMonitoring(p2p0) with mConnected = true
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131152
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
,D/WifiP2pService( 1021): P2pEnablingState
D/WifiStateMachine( 1021): set country code PL
D/WifiP2pService( 1021): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): P2p socket connection successful
,D/WifiP2pService( 1021): P2pEnabledState
E/wpa_supplicant( 3689): COUNTRY Code Recived
E/wpa_supplicant( 3689): COUNTRY Code Recived
,D/WifiP2pService( 1021): sending p2p connection changed broadcast
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131162
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): set frequency band 2
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131167
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
E/SharedPreferencesImpl( 1021): Couldn't create directory for SharedPreferences file shared_prefs/wifi_sm_shared_prefs.xml
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=143371
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/LocalBluetoothProfileManager( 3633): Adding local A2DP profile
D/BluetoothManagerService( 1021): Message: 30
,D/WifiP2pService( 1021): DeviceAddress: f4:f1:e1:5c:43:c8
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
D/WifiP2pService( 1021): MCC mode enabled 0
D/WifiP2pService( 1021): mP2pAutoConnectSupport = 0
W/ContextImpl( 3633): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
,D/LocalBluetoothProfileManager( 3633): Adding local HEADSET profile
D/WifiP2pService( 1021): sending p2p persistent groups changed broadcast
D/WifiP2pService( 1021): InactiveState
D/WifiP2pService( 1021): InactiveState{ when=-20ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): P2pEnabledState{ when=-20ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): InactiveState{ when=-21ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/BluetoothManagerService( 1021): Message: 30
,D/WifiP2pService( 1021): P2pEnabledState{ when=-21ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 3689): COUNTRY Code Recived
,E/wpa_supplicant( 3689): COUNTRY Code Recived
D/WifiP2pService( 1021): InactiveState{ when=-8ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): P2pEnabledState{ when=-8ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl( 3633): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
,D/BluetoothManagerService( 1021): Message: 30
,W/ContextImpl( 3633): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
,D/BluetoothManagerService( 1021): Message: 30
,W/ContextImpl( 3633): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 3633): Adding local MAP profile
D/BluetoothMap( 3633): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1021): Message: 30
,W/ContextImpl( 3633): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/BluetoothManagerService( 1021): Message: 30
,W/ContextImpl( 3633): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 3633): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 3633): finishStartingService: stopping service
,D/BluetoothAdapterService(1114351040)( 3608): Get Bonded Devices being called
,D/BluetoothA2dp( 3633): Proxy object connected
,D/A2dpProfile( 3633): Bluetooth service connected
,D/BluetoothHeadset( 3633): Proxy object connected
,D/HeadsetProfile( 3633): Bluetooth service connected
,D/BluetoothInputDevice( 3633): Proxy object connected
,D/HidProfile( 3633): Bluetooth service connected
,D/BluetoothPan( 3633): BluetoothPAN Proxy object connected
D/PanProfile( 3633): Bluetooth service connected
D/BluetoothMap( 3633): Proxy object connected
,D/MapProfile( 3633): Bluetooth service connected
,D/BluetoothMap( 3633): getConnectedDevices()
,D/BluetoothPbap( 3633): Proxy object connected
,D/PbapServerProfile( 3633): Bluetooth service connected
,V/BluetoothFtpReceiver( 3608): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 3608): BluetoothFtpReceiver Start Service
D/AuthorizationBluetoothService( 2013): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 2013): Proximity feature is not enabled.
,D/BluetoothManagerService( 1021): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3608): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3608): SOCK FLAG = 0 ***********************
,I/BtOppRfcommListener( 3608): Accept thread started.
V/BluetoothFtpService( 3608): Ftp Service onCreate
I/BluetoothFtpService( 3608): FFFFFtp Service onCreate
,V/BluetoothFtpService( 3608): Starting FTP service
V/BluetoothFtpService( 3608): Ftp Service onStartCommand
,V/BluetoothFtpService( 3608): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 3608): Handler(): got msg=1
V/BluetoothFtpService( 3608): Ftp Service startRfcommSocketListener
,V/BluetoothFtpService( 3608): Ftp Service initSocket
,D/BluetoothManagerService( 1021): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3608): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3608): SOCK FLAG = 3 ***********************
,V/BluetoothFtpService( 3608): Succeed to create listening socket on channel 20
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3608): Run Accept thread
,D/Checkin ( 2153): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2153): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/dalvikvm( 1021): GC_EXPLICIT freed 22607K, 65% free 17866K/50256K, paused 4ms+10ms, total 157ms
,D/TCMD    (  447): NL - Read 1000 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
,D/TCMD    (  447): Listening for incoming client connection request
,I/MDMCTBK (  276): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  276): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
,I/MDMCTBK (  276): wifi_connect_to_supplicant, current pid is = 276
D/MDMCTBK (  276): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  276): wifi_close_sockets: Exit
,E/MDMCTBK (  276): Attach monitor thread
I/MDMCTBK (  276): createWifiMonitorThread: Started the wifi monitor thread -1221608624
,D/MDMCTBK (  276): wifi_wait_on_socket: Enter monitor thread
,D/Checkin ( 2153): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2153): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiP2pService( 1021): InactiveState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledState{ when=-2ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledStateupdate channel list
,V/AlarmManager( 1021): sending alarm Alarm{438b6db0 type 3 android}
,D/MDMCTBK (  276): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c2:ff:d4:d3:aa:48
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 0 c2:ff:d4:d3:aa:48
D/MDMCTBK (  276): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 c0:ff:d4:d3:aa:48
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 1 c0:ff:d4:d3:aa:48
D/MDMCTBK (  276): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 06:7c:34:12:7f:81
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 2 06:7c:34:12:7f:81
D/MDMCTBK (  276): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 38:f8:89:11:e9:11
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 3 38:f8:89:11:e9:11
D/MDMCTBK (  276): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 64:7c:34:12:7f:81
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 4 64:7c:34:12:7f:81
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
I/wpa_supplicant( 3689): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  276): Event received = Trying to associate with
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3688): fatal error opening "/sys/power/wake_lock"
I/wpa_supplicant( 3688): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
D/TCMD    (  447): NL - Read 56 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
,D/TCMD    (  447): Listening for incoming client connection request
D/WifiStateMachine( 1021): handleMessage: E msg.what=147461
D/WifiStateMachine( 1021): processMsg: DisconnectedState
,E/wpa_supplicant( 3689): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
,D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
,I/wpa_supplicant( 3689): WEXT: Custom wireless event: 'BEACONIEs='
,I/wpa_supplicant( 3689): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  447): NL - Read 312 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
D/TCMD    (  447): Listening for incoming client connection request
D/TCMD    (  447): NL - Read 192 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
D/TCMD    (  447): Listening for incoming client connection request
D/TCMD    (  447): NL - Read 68 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
D/TCMD    (  447): Listening for incoming client connection request
D/TCMD    (  447): NL - Read 1000 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
,D/TCMD    (  447): Listening for incoming client connection request
D/TCMD    (  447): NL - Read 80 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
D/TCMD    (  447): Listening for incoming client connection request
D/TCMD    (  447): NL - Read 80 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
D/TCMD    (  447): Listening for incoming client connection request
D/TCMD    (  447): NL - Read 68 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
I/wpa_supplicant( 3689): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/TCMD    (  447): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  276): Event received = Associated with c0:ff:d4
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1021): processMsg: DisconnectedState
,D/WifiStateMachine( 1021): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3689): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3689): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  276): Event received = WPA: Key negotiation com
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  276): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  276):  STA Connected !!
D/TCMD    (  447): NL - Read 1000 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
,D/TCMD    (  447): Listening for incoming client connection request
E/MDMCTBK (  276): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  276): get_freq !!, resp=0
I/MDMCTBK (  276): get_freq !!, Strip data
I/MDMCTBK (  276): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): get_property_value, Enter
I/MDMCTBK (  276): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  276): get_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler,UpdateWifiBand band=2, current_band=0
I/MDMCTBK (  276): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  276): set_property_value, Enter
,I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=0, p2p0 = 1, wlan0 = 1, data=0
E/MDMCTBK (  276): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  276): get_freq !!, resp=0
I/MDMCTBK (  276): get_freq !!, Strip data
I/MDMCTBK (  276): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  276): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  276): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): get_property_value, Enter
I/MDMCTBK (  276): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  276): get_property_value, Exit
I/MDMCTBK (  276): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1221457408
I/MDMCTBK (  276): return from set_get_from_wpa_supplicant
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
,I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  276): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  276): , reply_len: 3, ret: 0
E/MDMCTBK (  276): MdmCutbackHndler, resp=OK
E/MDMCTBK (  276): 
D/MDMCTBK (  276): wifi_set_tx_pwr: Exit
,D/Tethering( 1021): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1021): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147459
,D/WifiStateMachine( 1021): processMsg: DisconnectedState
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): Network connection established
,D/WifiStateMachine( 1021): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1021): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1021): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1021): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1021): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1021): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-44ms what=147462 obj=android.net.wifi.StateChangeResult@42804ea0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131101
D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-42ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@42b5a5e0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
,D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=196612
D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1021): processMsg: L2ConnectedState
,D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1021): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1021): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43055ad0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43055ad0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 06
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 2 06
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 38
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 3 38
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE i
D/TCMD    (  447): NL - Read 56 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
,D/TCMD    (  447): Listening for incoming client connection request
D/WifiStateMachine( 1021): ObtainingIpState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
,D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiP2pService( 1021): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): InactiveState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@427a9d80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): P2pEnabledState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@427a9d80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): DefaultState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@427a9d80 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1021): handleMessage: X
,D/TCMD    (  447): NL - Read 60 bytes from update socket.
D/TCMD    (  447): NL - ignore NL message, type = 20
,D/TCMD    (  447): Listening for incoming client connection request
,D/WifiStateMachine( 1021): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1021): handleMessage: E msg.what=131215
D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-2ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1021): processMsg: DefaultState
,D/WifiStateMachine( 1021): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1021): processMsg: ObtainingIpState
,D/WifiStateMachine( 1021): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
,D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1021): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1021): DHCP successful
,D/WifiStateMachine( 1021): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1021): Calling ARP set with IP = 192.168.1.127
,D/WifiStateMachine( 1021): transitionTo: destState=VerifyingLinkState
,D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1021): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1021): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1021): VerifyingLinkState enter
,D/WifiStateMachine( 1021): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=151572
D/WifiStateMachine( 1021): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1021): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1021): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1084): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=135190
D/WifiStateMachine( 1021): processMsg: VerifyingLinkState
D/WifiStateMachine( 1021): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 1021): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1021): invokeExitMethods: VerifyingLinkState
,D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1021): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine( 1021): CaptivePortalCheckState enter
,D/WifiStateMachine( 1021): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1021): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1021): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1021): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService( 1021): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131092
D/WifiStateMachine( 1021): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1021): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1021): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1021): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,V/ConnectivityService( 1021): WiFi NOT Tethered!
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
E/ConnectivityService( 1021): Unexpected mtu value: android.net.wifi.WifiStateTracker@42795fa0
,I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/WifiStateMachine( 1021): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1021): invokeExitMethods: CaptivePortalCheckState
,D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1021): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=131092
D/WifiStateMachine( 1021): processMsg: ConnectedState
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1021): processMsg: DefaultState
,D/WifiStateMachine( 1021): handleMessage: X
,D/Checkin ( 1021): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.NetworkController( 1084): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1286): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1286): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1286): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1021): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1021): WiFi NOT Tethered!
E/ConnectivityService( 1021): Unexpected mtu value: android.net.wifi.WifiStateTracker@42795fa0
,D/ConnectivityService( 1021): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1286): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1286): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1286): onReceive() - done, currentInetCondition=0
,D/PollingManager( 1539): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/Tethering( 1021): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/CaptivePortalTracker( 1021): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/        ( 1021): Unable to set rtc to 1449748865: Invalid argument
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,D/        ( 1021): Setting time of day to sec=1449748865
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/ActivityManager( 1021): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=3771 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/TelephonyProvider( 1239): Column apn id key is 'apn_id'
D/PollingManager( 1539): now: 314114 ,futureTime: 9359182
D/PollingManager( 1539): Polling alarm set to expire at: 9359182 Current Time: 314114
W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,E/ActivityThread( 1539): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1539): registerApp(): CCE
I/CCE     ( 1539): _configureNotificationMechanism(): successfully turned off push and starting polling at interval 1440
D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/CCE     ( 1539): Registering with Alarm Manager to restart CCE
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/PollingManager( 1539): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/Tethering( 1021): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1021): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/PollingManager( 1539): now: 314211 ,futureTime: 9359182
,D/TelephonyProvider( 1239): Column apn id key is 'apn_id'
,D/PollingManager( 1539): Polling alarm set to expire at: 9359182 Current Time: 314213
,E/ActivityThread( 1539): Failed to find provider info for com.motorola.blur.setupprovider
D/MMApiWebService( 1539): Received data connectivity intent from PollingManager .. retry the waiting requests: 2
D/CCE     ( 1539): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1539): isRequestAllowed(): already have outstanding request ... ignoring request
D/CCE     ( 1539): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1539): isRequestAllowed(): already have outstanding request ... ignoring request
D/OtaApp  ( 1539): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1539): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1539): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/MMApiWebService( 1539): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1539): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/OtaApp  ( 1539): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1539): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1539): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
D/MMApiWebService( 1539): generating token using payload instead of using session token
D/OtaApp  ( 1539): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1539): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1539): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/dalvikvm( 1357): GC_CONCURRENT freed 1956K, 32% free 11809K/17224K, paused 10ms+18ms, total 100ms
,D/dalvikvm( 1357): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/dalvikvm( 1357): WAIT_FOR_CONCURRENT_GC blocked 43ms
,D/OtaApp  ( 1539): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1539): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1539): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1539): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1539): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1539): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,I/MMApiWSBase( 1539): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager( 1021): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=3805 uid=10056 gids={50056, 3003, 1028, 1015}
D/TelephonyProvider( 1239): Column apn id key is 'apn_id'
D/OtaApp  ( 1539): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/MMApiWSBase( 1539): doRequest(): url: https://api.svcmot.com:443/v1/dp/devices.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,D/dalvikvm( 3771): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x426b3200, skipping init
I/openssl ( 3771): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3771): Crypto mode 0 already enabled
,I/ActivityManager( 1021): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=3830 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 3401:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 2013): GC_EXPLICIT freed 2465K, 41% free 10264K/17224K, paused 2ms+6ms, total 69ms
,I/dalvikvm( 1357): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1357): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1357): VFY: replacing opcode 0x6e at 0x003d
,D/TelephonyProvider( 1239): Column apn id key is 'apn_id'
,V/MmsConfig( 3830): mnc/mcc: 
V/MmsConfig( 3830): tag: bool value: enabledMMS - true
,V/MmsConfig( 3830): tag: int value: maxMessageSize - 307200
,V/MmsConfig( 3830): tag: int value: maxImageHeight - 1944
V/MmsConfig( 3830): tag: int value: maxImageWidth - 2592
,V/MmsConfig( 3830): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 3830): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 3830): tag: int value: minMessageCountPerThread - 10
,V/MmsConfig( 3830): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 3830): tag: int value: recipientLimit - 20
,V/MmsConfig( 3830): tag: bool value: enableMultipartSMS - true
,D/GpsLocationProvider( 1021): NTP server returned: 1449748862076 (Thu Dec 10 13:01:02 CET 2015) reference: 311131 certainty: 12 system time offset: -3455
,V/MmsConfig( 3830): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 3830): tag: bool value: enableSlideDuration - true
V/MmsConfig( 3830): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 3830): tag: int value: maxSubjectLength - 80
,V/MmsConfig( 3830): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 3830): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 3830): tag: bool value: enableGroupMms - false
,E/MmsConfig( 3830): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,E/LocSvc_ApiV02( 1021): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
E/ActivityThread( 1357): Failed to find provider info for com.android.contacts.metadata
,D/DelayedSyncController( 3805): Delaying sync.
,I/ActivityManager( 1021): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3855 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1021): Killing 3047:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,E/Auth.Api.Credentials( 1357): [CredentialSyncAdapter] Unknown sync event.
,D/dalvikvm( 1239): GC_EXPLICIT freed 1459K, 45% free 9518K/17224K, paused 2ms+6ms, total 66ms
,D/SyncManager( 1021): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 314696, reason: UserStart
,D/MobileConnectivityChangeReceiver( 3855): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3855): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager( 1021): Killing 3431:com.google.android.partnersetup/u0a25 (adj 15): empty #9
E/PhoneMonitor( 3855): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3855): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1021): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3870 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 3068:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1357): Checkin interval check for package: unspecified last checkin: 1449746490574 min interval config: 0 actual interval: 2375102
,D/WifiStateMachine( 1021): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1021): handleMessage: E msg.what=131215
D/WifiStateMachine( 1021): processMsg: ConnectedState
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1021): processMsg: DefaultState
,D/WifiStateMachine( 1021): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1021): handleMessage: X
,D/ConnectivityService( 1021): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1021):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1021): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
I/CheckinService( 1357): Checking schedule, now: 1449748865706 next: 1449746520497
I/CheckinService( 1357): active receiver: enabled
,I/CheckinService( 1357): Preparing to send checkin request
,I/EventLogService( 1357): Accumulating logs since 1449748322851
,V/WebViewChromiumFactoryProvider( 3870): Binding Chromium to main looper Looper (main, tid 1) {426aff50}
,I/LibraryLoader( 3870): Expected native library version number "",actual native library version number ""
,I/chromium( 3870): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3870): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 3870): BLUETOOTH permission is missing!
,I/Adreno-EGL( 3870): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3870): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3870): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3870): Local Branch: 
I/Adreno-EGL( 3870): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3870): Local Patches: NONE
I/Adreno-EGL( 3870): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3870): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 3870): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  265): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  265): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3870): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/CheckinRequestBuilder( 1357): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1357): Failed to find provider info for com.google.android.wearable.settings
,D/WifiService( 1021): New client listening to asynchronous messages
,D/dalvikvm( 1021): GC_EXPLICIT freed 1800K, 65% free 17900K/50256K, paused 5ms+10ms, total 104ms
,D/DelayedSyncController( 3805): Delaying sync.
,I/PhenotypeConfigurator( 1210): Scheduling Phenotype for one-off execution 5903 seconds from now (1449748866183)
,I/NSApplication( 3870): Starting up...
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ImageResourceManager( 3100): ImageResourceManager: uninitalized
,D/MMApiWSBase( 1539): doRequest(): v1/ns/list/messages resp length: 1465
,D/GetConfigurationSnapshotOperation( 1210): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/CCE     ( 1539): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,I/iu.Environment( 3100): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.SyncManager( 3100): SYNC; picasa accounts
,D/CCE     ( 1539): AppWSProxy - sendAIDLWSResponse() sending reponse
I/ActivityManager( 1021): Killing 3457:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.UploadsManager( 3100): num queued entries: 0
,I/iu.UploadsManager( 3100): num updated entries: 0
,I/iu.SyncManager( 3100): NEXT; no task
,D/dalvikvm( 1539): GC_CONCURRENT freed 2201K, 38% free 10782K/17224K, paused 3ms+18ms, total 51ms
,D/MMApiProvisionService( 1539): ProvisionWS.Response: processing response data: {"sessionToken":"0-62d6271415ae24024c051b549cbffe5b3369896958","error":"OK","sessionExpiration":"95402","deviceId":"1135300315450105856"}
,D/MMApiProvisionService( 1539): ProvisionWS.Response: Completed parsing response.. no settings sent by server
,D/MMApiWSBase( 1539): doRequest(): /v1/dp/devices.json resp length: 137
,I/iu.SyncManager( 1357): SYNC; picasa accounts
,D/NetworkLogImpl( 1357): Loaded NetworkSpeedPredictor
,D/MMApiProvisionService( 1539): MMApiProvisionService.handleResponse (update_device) : true (None)
,D/Checkin ( 1539): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1539): handleGetNotificationsResponse(): got 0; more=false
,I/iu.Environment( 1357): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/MMApiProvisionService( 1539): handleResponse(): Session Expiration alarm set to expire at: Fri Dec 11 15:31:08 CET 2015
,D/MMApiProvisionService( 1539): _setMMApiCredInfo: storing credential info 
,I/iu.UploadsManager( 1357): num queued entries: 0
,I/iu.UploadsManager( 1357): num updated entries: 0
,I/iu.SyncManager( 1357): NEXT; no task
,E/MMApiProvisionService( 1539): handleResponse(): no settings sent by the server:
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1539): MMApiWebService told us to retry waiting request since device is successfully provisioned: 0
,I/PhenotypeFlagCommitter( 1210): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
I/openssl ( 3771): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3771): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 3855): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3855): onReceive CONNECTIVITY_CHANGE networkType=1
,W/dalvikvm( 1210): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1210): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1210): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1210): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1210): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1210): VFY: replacing opcode 0x6e at 0x00bb
,I/ActivityManager( 1021): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3929 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
I/GoogleURLConnFactory( 1210): Using platform SSLCertificateSocketFactory
,I/iu.Environment( 3100): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/ActivityManager( 1021): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=3941 uid=10007 gids={50007, 3003}
,W/dalvikvm( 3929): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 3929): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 3929): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 3929): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 3929): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 3929): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 3929): install
,D/dalvikvm( 3100): GC_CONCURRENT freed 615K, 5% free 16454K/17224K, paused 2ms+3ms, total 48ms
,I/MultiDex( 3929): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 3929): loading existing secondary dex files
,I/MultiDex( 3929): load found 3 secondary dex files
,I/MultiDex( 3929): install done
,D/ExtensionsFactory( 3941): No custom extensions.
,I/ActivityManager( 1021): Start proc com.android.deskclock for broadcast com.android.deskclock/.AlarmInitReceiver: pid=3960 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1021): Killing 3123:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  278): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 21ms
,I/GCM     ( 2013): GCM config loaded
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
,I/ActivityManager( 1021): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3977 uid=10008 gids={50008, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 3633:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiService( 1021): Client connection lost with reason: 4
D/dalvikvm( 3929): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3929): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 3929): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 3929): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 3929): VFY: unable to resolve instance field 36
D/dalvikvm( 3929): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 3929): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3929): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 3929): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 1210): GC_CONCURRENT freed 1514K, 34% free 11394K/17224K, paused 3ms+18ms, total 76ms
,D/dalvikvm( 3929): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 3929): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 3929): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x426b5d10
D/dalvikvm( 3929): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x426b5d10
,D/dalvikvm( 3929): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x426b5d10, skipping init
,D/dalvikvm( 3929): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x426b5d10
D/dalvikvm( 3929): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x426b5d10
,V/JNIHelp ( 3929): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,V/AlarmClock( 3960): AlarmInitReceiver android.intent.action.TIME_SET
,I/CalendarProvider2( 3977): Created com.android.providers.calendar.CalendarAlarmManager@426c21c8(com.android.providers.calendar.CalendarProvider2@426b9d80)
,I/AlarmClock( 3960): Displaying next alarm time: ''
,V/AlarmClock( 3960): AlarmInitReceiver finished
,I/ActivityManager( 1021): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3994 uid=10098 gids={50098}
,D/dalvikvm( 3929): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x426b5d10
,D/dalvikvm( 3929): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x426b5d10
D/dalvikvm( 3929): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x426b5d10
,D/dalvikvm( 3929): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x426b5d10
,D/dalvikvm( 3994): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x426a3d68, skipping init
D/TimeService( 3994): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449748866741
D/        ( 3994): TimeServiceNative: User Time to be set is 1449748866741
D/QC-time-services( 3994): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3994): Lib:time_genoff_operation: pargs->operation = 0
,D/QC-time-services( 3994): Lib:time_genoff_operation: pargs->ts_val = 1449748866741
D/QC-time-services(  374): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 3994): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  374): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449748866741
D/QC-time-services(  374): Daemon:genoff_opr: Base = 2, val = 1449748866741, operation = 0
D/QC-time-services(  374): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS11/10/115 11:55:12
D/QC-time-services(  374): Daemon:Value read from RTC seconds = 1449748512000
D/QC-time-services(  374): Daemon:new time 1449748866741 
D/QC-time-services(  374): Daemon: delta 354741 genoff 354741 
D/QC-time-services(  374): Daemon:genoff_persistent_update: Writing genoff = 354741 to memory
D/QC-time-services(  374): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  374): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  374): Updating the TOD offset
D/QC-time-services(  374): Daemon:genoff_persistent_update: Writing genoff = 354741 to memory
D/QC-time-services(  374): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  374): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  374): Daemon:Update to modem bit set
D/QC-time-services(  374): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  374): Daemon: Base = 2, Value being sent to MODEM = 18446743757745106357
,E/QC-time-services( 3994): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/ActivityManager( 1021): Killing 3771:android.process.media/u0a18 (adj 15): empty #9
E/QC-time-services(  374): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  374): Daemon: Time-services: Waiting to acceptconnection
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1357): Checkin interval check for package: unspecified last checkin: 1449746490574 min interval config: 0 actual interval: 2376199
,D/DEBUG   ( 1539): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1539): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1539): ServiceHandler.handleMessage: mWaitCount=1
,D/EmailService.MarketingOptInSetter( 1539): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/DEBUG   ( 1539): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1539): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1539): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1539): ServiceHandler.handleMessage: mWaitCount=1
,D/OtaApp  ( 1539): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1539): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1021): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1539
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1539): [info] > Updatetime from metadata: 10
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1539): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1539): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1539): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1539): [info] > Updatetime from metadata: 10
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,I/ProviderInstaller( 3929): Installed default security provider GmsCore_OpenSSL
,D/OtaApp  ( 1539): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1539): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1539): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1539): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1021): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1539
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1539): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1539): [info] > Updatetime from metadata: 10
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,I/dalvikvm( 3929): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 3929): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 3929): VFY: replacing opcode 0x6e at 0x00ce
,D/OtaApp  ( 1539): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1539): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
I/dalvikvm( 3929): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 3929): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 3929): VFY: replacing opcode 0x6e at 0x000d
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1539): [info] > Updatetime from metadata: 10
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1539): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1539): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,I/LaunchCheckinHandler( 1021): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,133
D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1539): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1539): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1021): Activity reported stop, but no longer stopping: ActivityRecord{427f1130 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/dalvikvm( 3929): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 3929): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 3929): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 3929): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 3929): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 3929): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 3929): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 3929): VFY: replacing opcode 0x6e at 0x0036
,D/DEBUG   ( 1539): Received intent : com.motorola.ccc.notification.action.NOTIFY
I/SundryService( 1539): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1539): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1539): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1539): ServiceHandler.handleMessage: mWaitCount=0
I/dalvikvm( 3929): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 3929): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 3929): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/DEBUG   ( 1539): Received intent : com.motorola.notification.RETREIVE_NOTIFICATIONS
,D/GetNotificationsWS( 1539): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1539): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1539): bindWebServices(): registering our AIDL callback...
,D/GetNotificationsWS( 1539): onServiceConnected()
D/GetNotificationsWS( 1539): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1539): onHandleIntent(): action=com.motorola.notification.RETREIVE_NOTIFICATIONS
,I/SundryService( 1539): Received shoulder tap
,D/WaitableIntentService( 1539): setWaitEnabled(): mWaitCount=1 isWaitEnabled=true
,D/GetNotificationsWS( 1539): GetNotificationsWS.Request: message={"request":{"appendDeviceId":true,"baseUrl":"v1\/ns\/list\/messages","queryParams":{"appid":"MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ"},"httpMethod":"post","requestFormat":"json","wsReqId":"com.motorola.ccc.notification.GetNotificationsWS.Request","isSecure":true,"payload":{"data":"{\"appidNotifStoreMessageidPageSizeList\":[{\"appid\":\"LX6TJJI6F2MILF1NPZW6A3HBAKK8W44Z\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SULIGJDMXLSL7T1DOVYSTVG2KCBHZ5GH\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"6U5KK17SNFB416J4SYG7LC6HYFNOPYM8\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"68OUD4VKG23F7BUH6M2QBRXPLIC7IMCO\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SZZTNOGZA6O6PRFZH2V3FF14N1J8W3HC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"D9DF2F5BB1FA45B0BA459B7FE6942DCD\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"RCEAZODHQBX3UTIE62BUQ6T6TXXI6JSR\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"L71KGK4CCWOW658MGESIRYO2428ODW11\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"OCVKVSQ5Q1EYVBX76813UOPTCKGAH4VS\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"B642GFV24HEMEDQNCF3ZED8BIUMPCBOM\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"5LWTCLJBZO4OUDU5BY7ANJI4Y2MHY8OY\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"TESULHNZGDWZ5T3EMNZRTVE51RR7EUXC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"QZYSBKU4MGE71O1PLTE8HAT11SWL5M6E\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"XX274VEJBOVSSPHDKHSPURVRQ1YT5VEM\",\"pageSize\":100,\"notifStoreMessageid\":0}]}","type":"json"},"retries":"-1","useOAuth":true}}
D/GetNotificationsWS( 1539): sendAidlRequest(): was sent by CCE successfully!
,D/WaitableIntentService( 1539): ServiceHandler.handleMessage: mWaitCount=1
,D/MMApiWebService( 1539): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,I/MMApiWSBase( 1539): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,D/WVCdm   (  282): Instantiating CDM.
,I/WVCdm   (  282): Level3 Library Nov 20 2013 18:09:31
,D/AuthorizationBluetoothService( 2013): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 2013): Proximity feature is not enabled.
D/DrmWidevineDash(  282): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
,D/QSEECOMAPI: (  282): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  282): App is not loaded in QSEE
E/QSEECOMAPI: (  282): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  282): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  282): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  282): App is not loaded in QSEE
E/QSEECOMAPI: (  282): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  282): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  282): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  282): App is not loaded in QSEE
,D/LocationInitializer( 1357): Restart initialization of location
D/ConnectivityService( 1021): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1286): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1286): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1286): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1286): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1084): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,D/QSEECOMAPI: (  282): Loaded image: APP id = 3
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/DrmWidevineDash(  282): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb528b000
,E/DrmWidevineDash(  282): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb528b000
,D/WearableService( 1210): callingUid 10022, callindPid: 1210
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/DrmWidevineDash(  282): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_APIVersion...
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DrmWidevineDash(  282): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  282): calling OEMCrypto_IsKeyboxValid...
,E/MDM     ( 1210): [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/DrmWidevineDash(  282): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  282): OEMCrypto_Initialize Level 1 success. I will use level 1.
,I/WVCdm   (  282): CdmEngine::OpenSession
,D/DrmWidevineDash(  282): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  282): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  282): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  282): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  282): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  282): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  282): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  282): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  282): PrepareKeyRequest: nonce=2313908058
,D/DrmWidevineDash(  282): calling OEMCrypto_GenerateRSASignature. SID = 1
,W/GCoreFlp( 1210): No location to return for getLastLocation()
,W/FusedLocationProvider( 1210): location=null
,D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  282): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 3929): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42875698
,I/dalvikvm( 1210): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
D/dalvikvm( 3929): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42875698
,D/dalvikvm( 3929): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42875698, skipping init
W/dalvikvm( 1210): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1210): VFY: replacing opcode 0x6e at 0x003d
,D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  282): CdmEngine::CloseSession
,D/DrmWidevineDash(  282): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  282): OEMCrypto_CloseSession returns 0
,D/NativeLibraryUtils( 3929): Install completed successfully. count=14 extracted=0
,W/Settings( 3929): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/WVCdm   (  282): CdmEngine::OpenSession
,D/DrmWidevineDash(  282): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  282): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  282): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  282): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  282): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  282): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  282): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  282): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  282): PrepareKeyRequest: nonce=1749284731
,D/DrmWidevineDash(  282): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  282): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/MMApiWSBase( 1539): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1539): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1539): AppWSProxy - sendAIDLWSResponse() sending reponse
,D/Checkin ( 1539): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1539): handleGetNotificationsResponse(): got 0; more=false
,D/DEBUG   ( 1539): Received intent : com.motorola.ccc.notification.action.NOTIFY
I/SundryService( 1539): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1539): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1539): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1539): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1539): unbindWebServices(): un-registering our AIDL callback...
,I/CalendarProvider2( 3977): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3977): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 3941): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 3941): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  282): CdmEngine::CloseSession
,D/DrmWidevineDash(  282): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  282): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 3929): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4035): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 3929): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 3929): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 76ms
,I/Adreno-EGL( 3929): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3929): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3929): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3929): Local Branch: 
I/Adreno-EGL( 3929): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3929): Local Patches: NONE
I/Adreno-EGL( 3929): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 3929): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3929): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3929): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3929): Local Branch: 
I/Adreno-EGL( 3929): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3929): Local Patches: NONE
I/Adreno-EGL( 3929): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 3929): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3929): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3929): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3929): Local Branch: 
I/Adreno-EGL( 3929): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3929): Local Patches: NONE
I/Adreno-EGL( 3929): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 3929): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3929): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3929): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3929): Local Branch: 
I/Adreno-EGL( 3929): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3929): Local Patches: NONE
I/Adreno-EGL( 3929): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1357): Classify the device as Phone.
,D/dalvikvm( 1357): GC_CONCURRENT freed 1690K, 30% free 12075K/17224K, paused 4ms+11ms, total 47ms
,I/CheckinTask( 1357): Sending checkin request (11713 bytes)
,I/CheckinRequestBuilder( 1357): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1357): Failed to find provider info for com.google.android.wearable.settings
,I/jxcore-log( 3554): Test app app.js loaded
I/jxcore-log( 3554): 
,W/IInputConnectionWrapper( 3554): showStatusIcon on inactive InputConnection
,D/dalvikvm( 1021): GC_EXPLICIT freed 645K, 65% free 17849K/50256K, paused 4ms+10ms, total 98ms
,I/chromium( 3554): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/dalvikvm( 2013): GC_EXPLICIT freed 626K, 41% free 10291K/17224K, paused 2ms+4ms, total 32ms
,I/CheckinRequestBuilder( 1357): Classify the device as Phone.
,I/CheckinTask( 1357): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1357): Checking schedule, now: 1449748869673 next: 1450341939668
,I/CheckinService( 1357): active receiver: disabled
,D/CheckinService( 1357): Recording last checkin time for package unspecified as 1449748869684
,D/GCM     ( 2013): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/ProcessCpuTracker( 1021): Skipping unknown process pid 4071
,I/GAV2    ( 3870): Thread[GAThread,5,main]: No campaign data found.
,I/GlobalDismissManager( 3941): no sender configured
,D/AlertService( 3941): Beginning updateAlertNotification
,D/AlertService( 3941): No fired or scheduled alerts
,D/AlertService( 3941): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 3941): No events found starting within 1 week.
I/ActivityManager( 1021): Killing 3830:com.android.mms/u0a30 (adj 15): empty #9
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1021): Killing 3855:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/CaptivePortalTracker( 1021): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1021): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1021): Checking http://216.58.209.46/generate_204
W/ActivityThread( 1021): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/dalvikvm( 1021): Jit: resizing JitTable from 8192 to 16384
,D/CaptivePortalTracker( 1021): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1021): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 1021): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1021): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1021): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1021): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4093 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
I/Launcher( 1298): Deferring update until onResume
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
,I/Launcher( 1298): Deferring update until onResume
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
,I/GCoreNlp( 1210): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4093): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4093): MmsConfig.loadMmsSettings
,I/Babel   ( 4093): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4093): MmsConfig.loadFromDatabase
,E/Babel   ( 4093): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4093): MmsConfig.loadFromResources
,E/Babel   ( 4093): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4093): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4093): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1021): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4131 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1021): Killing 3805:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1021): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4149 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 3870:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2185): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1021): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4167 uid=10038 gids={50038, 3003, 1028, 1015}
,D/dalvikvm( 3100): GC_FOR_ALLOC freed 47K, 5% free 16418K/17224K, paused 11ms, total 11ms
,I/dalvikvm-heap( 3100): Grow heap (frag case) to 19.802MB for 1821008-byte allocation
I/ActivityManager( 1021): Killing 3977:com.android.providers.calendar/u0a8 (adj 15): empty #9
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 3100): GC_FOR_ALLOC freed 1K, 5% free 18196K/19004K, paused 17ms, total 17ms
,I/ContactLocale( 4131): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4167): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4167): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 4167): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4167): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/dalvikvm( 1357): GC_CONCURRENT freed 2077K, 31% free 11949K/17224K, paused 4ms+4ms, total 43ms
,W/SQLiteConnectionPool( 1357): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/InternalIcingCorporaPro( 2185): UpdateCorporaTask done [took 220 ms] updated apps [took 220 ms] 
,I/dalvikvm( 4167): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
,W/dalvikvm( 4167): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4167): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4167): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4167): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4167): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4167): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4167): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4167): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4167): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4167): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4167): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4167): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4167): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4167): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 4167): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4167): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4167): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4167): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4167): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4167): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1021): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4201 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4167): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4167): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4167): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4167): Skipping gmscore version check
,D/Finsky  ( 4167): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4167): [1] Libraries$2.run: Finished loading 1 libraries.
,I/dalvikvm( 4167): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
,W/dalvikvm( 4167): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4167): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1021): Killing 3994:com.qualcomm.timeservice/u0a98 (adj 15): empty #9
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1357): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1357): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1357): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4201): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x426b5190, skipping init
I/openssl ( 4201): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4201): Crypto mode 0 already enabled
,D/Finsky  ( 4167): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4167): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1021): Killing 3960:com.android.deskclock/u0a15 (adj 15): empty #9
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Icing   ( 1357): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1357): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1186): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449748877
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 3689): wlan0: WPA: Group rekeying completed with c0:ff:d4:d3:aa:48 [GTK=CCMP]
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Group rekeying comp
,D/MDMCTBK (  276): Event received = WPA: Group rekeying comp
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1021): processMsg: ConnectedState
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1021): processMsg: ConnectedState
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
,V/AlarmManager( 1021): sending alarm Alarm{42ed8478 type 2 android}
,I/jxcore-log( 3554): Toggling radios to false
I/jxcore-log( 3554): 
,D/BluetoothManagerService( 1021): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1021): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@4439f650 mBinding = false
,W/Settings( 1250): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,W/Settings( 1250): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BluetoothManagerService( 1021): Message: 2
,D/BluetoothManagerService( 1021): Sending off request.
,D/BluetoothAdapterState( 3608): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3608): Setting state to 13
I/BluetoothAdapterState( 3608): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 3608): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterProperties( 3608): onBluetoothDisable()
I/BluetoothAdapterState( 3608): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,I/BluetoothAdapterProperties( 3608): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothAdapterProperties( 3608): Scan Mode:21
D/BluetoothAdapterState( 3608): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 3608): bta_jv_rfcomm_stop_server
,E/BtOppRfcommListener( 3608): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btif ( 3608): bta_jv_rfcomm_stop_server
E/bt-btif ( 3608): bta_jv_rfcomm_stop_server
,E/bt-btif ( 3608): bta_jv_rfcomm_stop_server
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3608): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 3608): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 3608): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 3608): L2CAP - PSM: 0x0017 not found for deregistration
,D/btif_config_util( 3608): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/WifiService( 1021): setWifiEnabled: false pid=3554, uid=10458
,E/WifiService( 1021): Invoking mWifiStateMachine.setWifiEnabled
,D/BluetoothManagerService( 1021): Message: 60
,D/BluetoothManagerService( 1021): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,D/BluetoothManagerService( 1021): Bluetooth State Change Intent: 12 -> 13
D/WifiStateMachine( 1021): handleMessage: E msg.what=131084
D/WifiStateMachine( 1021): processMsg: ConnectedState
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): transitionTo: destState=WaitForP2pDisableState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
,D/WifiStateMachine( 1021): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1021): invokeExitMethods: L2ConnectedState
D/BluetoothMapService( 3608): onReceive
D/BluetoothMapService( 3608): STATE_TURNING_OFF removeTimeoutMsg:false
D/BluetoothMapService( 3608): MAP Service closeService in
D/WifiStateMachine( 1021): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 true
,W/Settings( 1250): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiP2pService( 1021): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 3554): Radios toggled
I/jxcore-log( 3554): 
,I/ActivityManager( 1021): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=4258 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,W/Settings( 1250): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/CommandListener(  274): Clearing all IP addresses on wlan0
D/TCMD    (  447): NL - Read 60 bytes from update socket.
D/TCMD    (  447): NL - ignore NL message, type = 21
,D/TCMD    (  447): Listening for incoming client connection request
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,D/WifiStateMachine( 1021): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1021): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1021): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1021): connected time updated 55620
D/ConnectivityService( 1021): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1021): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1021): Attempting to switch to mobile
D/ConnectivityService( 1021): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1021): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/WifiStateMachine( 1021): invokeExitMethods: ConnectModeState
D/WifiStateMachine( 1021): invokeExitMethods: DriverStartedState
D/Checkin ( 1021): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/ConnectivityService( 1021): resetConnections(wlan0, 3)
D/NetUtils( 1021): android_net_utils_resetConnections in env=0x611db420 clazz=0x67200001 iface=wlan0 mask=0x3
E/WifiStateMachine( 1021): Unexpected BatchedScanResults :OK
I/BtOppRfcommListener( 3608): stopping Accept Thread
I/BtOppRfcommListener( 3608): BluetoothSocket listen thread finished
V/NativeCrypto( 2013): Read error: ssl=0x618f2f18: I/O error during system call, Connection timed out
V/NativeCrypto( 2013): SSL shutdown failed: ssl=0x618f2f18: I/O error during system call, Broken pipe
,D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
D/WifiStateMachine( 1021): invokeEnterMethods: WaitForP2pDisableState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131216
D/WifiStateMachine( 1021): processMsg: WaitForP2pDisableState
,D/WifiP2pService( 1021): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131216
D/WifiP2pService( 1021): P2pDisablingState
D/WifiStateMachine( 1021): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiP2pService( 1021): P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): p2p socket connection lost
,D/WifiP2pService( 1021): P2pDisabledState
D/WifiStateMachine( 1021): handleMessage: E msg.what=131205
D/WifiStateMachine( 1021): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1021): transitionTo: destState=SupplicantStoppingState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1021): invokeExitMethods: WaitForP2pDisableState
D/WifiStateMachine( 1021): invokeExitMethods: SupplicantStartedState
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/WifiStateMachine( 1021): invokeEnterMethods: SupplicantStoppingState
D/WifiStateMachine( 1021): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1021): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  274): Clearing all IP addresses on wlan0
,D/WifiStateMachine( 1021): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1021): stopping supplicant
,D/Checkin ( 1021): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiStateMachine( 1021): setWifiState: disabling
,D/WifiStateMachine( 1021): handleMessage: X
,I/SBar.NetworkController( 1084): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1268): Active network info is not available
E/XTCC-3.0.0.2(  603): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  603): [WwanPosMgr] handleConnectivtyStatusChange failed
D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1021): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=false Wifi=(none) Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/ConnectivityService( 1021): Attempting to switch to mobile
D/ConnectivityService( 1021): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1021): Attempting to switch to ETHERNET
I/ModemStatsDSDetect( 1286): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1286): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1286): onReceive() - done, currentInetCondition=0
D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
I/wpa_supplicant( 3689): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  276): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  276):  STA Disconnected !!
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): get_property_value, Enter
I/MDMCTBK (  276): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  276): get_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  276): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
E/XTCC-3.0.0.2(  603): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  603): [CSMgr] handleConnectivtyStatusChange failed
D/TCMD    (  447): NL - Read 1000 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
D/TCMD    (  447): Listening for incoming client connection request
D/TCMD    (  447): NL - Read 1000 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
D/TCMD    (  447): Listening for incoming client connection request
D/TCMD    (  447): NL - Read 68 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
D/TCMD    (  447): Listening for incoming client connection request
D/TCMD    (  447): NL - Read 68 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
D/TCMD    (  447): Listening for incoming client connection request
D/WifiStateMachine( 1021): handleMessage: E msg.what=147460
D/WifiStateMachine( 1021): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/Tethering( 1021): InitialState.processMessage what=4
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
I/ModemStatsDSDetect( 1286): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1286): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1286): onReceive() - done, currentInetCondition=0
D/Tethering( 1021): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,W/ContextImpl( 4258): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/Tethering( 1021): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1021): handleMessage: E msg.what=131101
D/WifiStateMachine( 1021): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/BluetoothPbapService( 3608): action: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothManagerService( 1021): Message: 20
D/BluetoothManagerService( 1021): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44485d10:true
W/bt-btif ( 3608): ag scb idx 1 not allocated
E/bt-btif ( 3608): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3608): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3608): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3608): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3608): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3608): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3608): L2CAP - PSM: 0x0017 not found for deregistration
I/bt_hwcfg( 3608): hw_epilog_process
D/BluetoothManagerService( 1021): Message: 30
,W/ContextImpl( 4258): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
I/wpa_supplicant( 3689): eap_proxy Deinitialzed
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 4
,D/BluetoothManagerService( 1021): Message: 30
,W/ContextImpl( 4258): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 4258): Adding local MAP profile
D/BluetoothMap( 4258): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1021): Message: 30
,W/ContextImpl( 4258): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/BluetoothManagerService( 1021): Message: 30
,W/ContextImpl( 4258): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 4258): LocalBluetoothProfileManager construction complete
I/bt_hwcfg( 3608): hw_epilog_cback Opcode:0x0C03 Status: 0
I/bt_hci_bdroid( 3608): bt_hc_worker_thread exiting
D/bt_userial_mct( 3608): userial_close
I/bt_userial_mct( 3608): exiting userial_read_thread
D/bt_userial_mct( 3608): Leaving userial_evt_read_thread()
D/DockEventReceiver( 4258): finishStartingService: stopping service
,D/TCMD    (  447): NL - Read 1000 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
,D/TCMD    (  447): Listening for incoming client connection request
,I/wpa_supplicant( 3689): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  276): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  276):  Wpa Supplicant Exiting !!
D/MDMCTBK (  276): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  276): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  276): wifi_close_sockets: Exit
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147458
D/WifiStateMachine( 1021): processMsg: SupplicantStoppingState
,D/WifiStateMachine( 1021): Supplicant connection lost
,D/dalvikvm( 1021): GC_CONCURRENT freed 2012K, 65% free 17982K/50256K, paused 4ms+11ms, total 89ms
,D/dalvikvm( 1021): WAIT_FOR_CONCURRENT_GC blocked 61ms
,D/dalvikvm( 1021): GC_EXPLICIT freed 117K, 65% free 17865K/50256K, paused 4ms+9ms, total 87ms
,D/BTSNOOP-DISP( 3608): btsnoop_close
I/bt_vendor( 3608): cleanup
I/bt_hwcfg( 3608): Starting hciattach daemon
,I/bt_hwcfg( 3608): try to set false
I/GKI_LINUX( 3608): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3608): GKI_exit_task: GKI_exit_task 0 done
,I/GKI_LINUX( 3608): GKI_destroy_task: GKI_shutdown(): task [BTU] terminated
,D/WifiService( 1021): New client listening to asynchronous messages
D/WifiStateMachine( 1021): setWifiState: disabled
W/Settings( 4093): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine( 1021): transitionTo: destState=InitialState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1021): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
D/WifiStateMachine( 1021): invokeEnterMethods: InitialState
W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1084): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1268): Active network info is not available
E/XTCC-3.0.0.2(  603): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  603): [WwanPosMgr] handleConnectivtyStatusChange failed
W/Settings( 1210): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BluetoothAdapterState( 3608): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
E/XTCC-3.0.0.2(  603): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  603): [CSMgr] handleConnectivtyStatusChange failed
D/HeadsetService( 3608): Received stop request...Stopping profile...
D/BluetoothHeadset( 1021): Proxy object disconnected
D/BluetoothHeadset( 1239): Proxy object disconnected
D/BluetoothHeadset( 1239): Proxy object disconnected
D/BluetoothHeadset( 1239): Proxy object disconnected
D/A2dpService( 3608): Received stop request...Stopping profile...
D/A2dpStateMachine( 3608): Exit Disconnected: -1
D/BluetoothA2dp( 1021): Proxy object disconnected
D/BluetoothInputDevice( 4258): Proxy object connected
D/BluetoothAdapterService( 3608): Profile still running: com.android.bluetooth.hdp.HealthService
D/HidService( 3608): Received stop request...Stopping profile...
D/BluetoothAdapterState( 3608): Stopping profile services that were post enabled
D/HidProfile( 4258): Bluetooth service connected
W/BluetoothHeadsetServiceJni( 3608): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3608): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3608): Profile still running: com.android.bluetooth.hdp.HealthService
D/HealthService( 3608): Received stop request...Stopping profile...
D/BluetoothPan( 4258): BluetoothPAN Proxy object connected
D/PanProfile( 4258): Bluetooth service connected
D/PanService( 3608): Received stop request...Stopping profile...
D/BluetoothMap( 4258): Proxy object connected
D/BluetoothTethering( 1021): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering( 1021): attempted to stop reverse tether with nothing tethered
D/MapProfile( 4258): Bluetooth service connected
D/BluetoothTethering( 1021): Disconnect CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@44186760
D/BluetoothPan( 1021): BluetoothPAN Proxy object disconnected
D/BluetoothTethering( 1021): got CMD_CHANNEL_DISCONNECTED
D/BluetoothMap( 4258): getConnectedDevices()
I/GKI_LINUX( 3608): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
D/BluetoothMap( 4258): Bluetooth is Not enabled
I/GKI_LINUX( 3608): GKI_exit_task: GKI_exit_task 2 done
I/GKI_LINUX( 3608): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BluetoothInputDevice( 4258): Proxy object disconnected
D/HidProfile( 4258): Bluetooth service disconnected
D/BluetoothPan( 4258): BluetoothPAN Proxy object disconnected
D/PanPr,ofile( 4258): Bluetooth service disconnected
I/ActivityManager( 1021): Killing 3941:com.android.calendar/u0a7 (adj 15): empty #9
D/BtGatt.DebugUtils( 3608): handleDebugAction() action=null
D/BtGatt.GattService( 3608): Received stop request...Stopping profile...
D/BtGatt.GattService( 3608): stop()
D/BluetoothAdapterService( 3608): Profile still running: com.android.bluetooth.hdp.HealthService
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/BluetoothMapService( 3608): Received stop request...Stopping profile...
D/BluetoothMapService( 3608): stop()
D/BluetoothMapService( 3608): MAP Service closeService in
W/BluetoothHidServiceJni( 3608): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3608): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3608): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 3608): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 3608): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3608): Cleaning up Bluetooth Health object
D/BluetoothAdapterService( 3608): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 3608): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3608): Cleaning up Bluetooth PAN callback object
D/BluetoothMap( 4258): Proxy object disconnected
D/MapProfile( 4258): Bluetooth service disconnected
D/BluetoothAdapterService( 3608): Profile still running: com.android.bluetooth.map.BluetoothMapService
V/BluetoothFtpReceiver( 3608): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 3608): cleanup()
D/BluetoothMapService( 3608): MAP Service closeService in
D/AuthorizationBluetoothService( 2013): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothAdapterState( 3608): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3608): Setting state to 10
I/BluetoothAdapterState( 3608): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 3608): Broadcasting updateAdapterState() to 1 receivers.
I/BluetoothAdapterState( 3608): Entering OffState
D/BluetoothManagerService( 1021): Message: 60
D/BluetoothManagerService( 1021): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1021): Broadcasting onBluetoothStateChange(false) to 10 receivers.
D/BluetoothHeadset( 1239): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1239): onBluetoothStateChange: up=false
D/BluetoothPan( 1021): onBluetoothStateChange on: false
D/BluetoothHeadset( 1239): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1021): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1021): onBluetoothStateChange: up=false
D/BluetoothPan( 4258): onBluetoothStateChange on: false
D/BluetoothInputDevice( 4258): onBluetoothStateChange: up=false
D/BluetoothMap( 4258): onBluetoothStateChange: up=false
D/BluetoothPbap( 4258): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1021): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1021): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothManagerService( 1021): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@4439f650 mBinding = false
D/BluetoothManagerService( 1021): Sending unbind request.
D/BluetoothManagerService( 1021): Bluetooth State Change Intent: 13 -> 10
D/BluetoothAdapterService( 3608): Cleaning up adapter native....
I/GKI_LINUX( 3608): gki_task_entry: gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 3608): GKI_exit_task: GKI_exit_task 1 done
I/GKI_LINUX( 3608): GKI_destroy_task: GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3608): cleanupNative: return from cleanup
D/BluetoothAdapterService( 3608): Done cleaning up adapter native....
D/BluetoothAdapterService(111435,1040)( 3608): ****onDestroy()********
D/BtGatt.GattService( 3608): cleanup()
W/bt-btif ( 3608): GATTC Module not enabled/already disabled
W/bt-btif ( 3608): GATTS Module not enabled/already disabled
D/BluetoothAdapter( 1084): 1115821848: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1210): 1117727488: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1210): 1117727488: getState() :  mService = null. Returning STATE_OFF
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.sendDeviceAttachIntent:820 com.motorola.authentication.MotAuthenticationService.access$1300:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:575 
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.handleKeepDeviceUnlockRequest:732 com.motorola.authentication.MotAuthenticationService.access$1500:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:563 
W/ContextImpl( 4258): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/DockEventReceiver( 4258): finishStartingService: stopping service
D/BluetoothAdapter( 4258): 1114393040: getState() :  mService = null. Returning STATE_OFF
V/BluetoothFtpReceiver( 3608): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 3608): BluetoothFtpReceiver Stop Service
V/BluetoothFtpService( 3608): Ftp Service onDestroy
V/BluetoothFtpService( 3608): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3608): Shutdown
I/ActivityManager( 1021): Killing 3929:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
D/AuthorizationBluetoothService( 2013): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1021): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.ConnectedUnlockReceiver: pid=4288 uid=10016 gids={50016, 3002}
,D/Checkin ( 4288): publish the event [tag = DEVICE_AUTH_STATS_L2 event name = DEVAUTH_CONNECT]
I/ActivityManager( 1021): Killing 4093:com.google.android.talk/u0a70 (adj 15): empty #9
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/NetlinkEvent(  274): Unexpected netlink message. type=0x11
W/Netd    (  274): No subsystem found in netlink event
D/TCMD    (  447): NL - Read 444 bytes from update socket.
D/TCMD    (  447): NL - ignore NL message, type = 17
D/TCMD    (  447): Listening for incoming client connection request
I/MDMCTBK (  276): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  276): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  276): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  276): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  276): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Checkin ( 2153): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2153): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
D/TCMD    (  447): NL - Read 1000 bytes from update socket.
D/TCMD    (  447): NL - message type is RTM_NEWLINK
,D/TCMD    (  447): Listening for incoming client connection request
,D/NetlinkEvent(  274): Unexpected netlink message. type=0x11
W/Netd    (  274): No subsystem found in netlink event
D/TCMD    (  447): NL - Read 444 bytes from update socket.
D/TCMD    (  447): NL - ignore NL message, type = 17
D/TCMD    (  447): Listening for incoming client connection request
I/MDMCTBK (  276): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  276): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  276): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  276): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  276): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  276): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/MDMCTBK (  276): NetlinkHandler, wifiStateChanged 0
I/MDMCTBK (  276): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
,I/MDMCTBK (  276): checkDefaultInst, pid match
,D/Checkin ( 2153): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2153): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/Checkin ( 2153): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=196614
D/WifiStateMachine( 1021): processMsg: InitialState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=131208
D/WifiStateMachine( 1021): processMsg: InitialState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131208
,D/WifiStateMachine( 1021): processMsg: InitialState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131208
D/WifiStateMachine( 1021): processMsg: InitialState
,D/WifiStateMachine( 1021): processMsg: DefaultState
,D/WifiStateMachine( 1021): handleMessage: X
,D/Checkin ( 2153): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,V/AlarmManager( 1021): sending alarm Alarm{42f2dea8 type 3 android}
,D/Tethering( 1021): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1021): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1021): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: null, inetCondition= 0
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1268): Active network info is not available
,D/PollingManager( 1539): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1239): Column apn id key is 'apn_id'
,E/ActivityThread( 1539): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1539): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 1539): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1539): [debug] > CusSM.onRadioDown
,D/Tethering( 1021): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: null, inetCondition= 0
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/CaptivePortalTracker( 1021): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,D/TelephonyProvider( 1239): Column apn id key is 'apn_id'
,D/PollingManager( 1539): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1539): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1539): Failed to find provider info for com.motorola.blur.setupprovider
W/XTWiFiOS( 1268): Active network info is not available
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1239): Column apn id key is 'apn_id'
,I/ActivityManager( 1021): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4318 uid=10030 gids={50030, 3003, 1028, 1015}
D/TelephonyProvider( 1239): Column apn id key is 'apn_id'
,V/MmsConfig( 4318): mnc/mcc: 
V/MmsConfig( 4318): tag: bool value: enabledMMS - true
,V/MmsConfig( 4318): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4318): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4318): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4318): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4318): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4318): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4318): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4318): tag: int value: recipientLimit - 20
V/MmsConfig( 4318): tag: bool value: enableMultipartSMS - true
,V/MmsConfig( 4318): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4318): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4318): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4318): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4318): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4318): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 4318): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4318): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1021): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4341 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1021): Killing 4131:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  278): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 24ms
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 19ms
,D/MobileConnectivityChangeReceiver( 4341): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4341): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4341): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4341): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
,I/ActivityManager( 1021): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4355 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 4149:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1021): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4368 uid=10076 gids={50076, 3003, 1028, 1015}
I/ActivityManager( 1021): Killing 3100:com.google.android.apps.plus/u0a90 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4368): Binding Chromium to main looper Looper (main, tid 1) {426aa0e0}
,I/LibraryLoader( 4368): Expected native library version number "",actual native library version number ""
,I/chromium( 4368): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4368): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4368): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4368): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4368): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4368): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4368): Local Branch: 
I/Adreno-EGL( 4368): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4368): Local Patches: NONE
I/Adreno-EGL( 4368): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4368): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4368): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  265): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  265): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4368): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 4368): Starting up...
,I/ActivityManager( 1021): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4409 uid=10090 gids={50090, 3003, 3002, 1028, 1015}
,I/ActivityManager( 1021): Killing 4167:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 4409): WAIT_FOR_CONCURRENT_GC blocked 1ms
,I/ActivityManager( 1021): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=4426 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ImageResourceManager( 4409): ImageResourceManager: uninitalized
,I/iu.Environment( 4409): update battery state; isPlugged? true*
,I/iu.Environment( 4409): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,I/iu.Environment( 4409): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
I/ActivityManager( 1021): Killing 3608:com.android.bluetooth/1002 (adj 15): empty #9
I/ActivityManager( 1021): Killing 4258:com.android.settings/1000 (adj 15): empty #10
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.Environment( 1357): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1357): num queued entries: 0
,D/WifiService( 1021): Client connection lost with reason: 4
I/iu.UploadsManager( 1357): num updated entries: 0
D/DEBUG   ( 1539): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/iu.SyncManager( 1357): NEXT; no task
W/ContextImpl( 1539): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
D/GetNotificationsWS( 1539): bindWebServices(): registering our AIDL callback...
D/EmailService.MarketingOptInSetter( 1539): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1539): onServiceConnected()
D/GetNotificationsWS( 1539): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1539): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1539): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1539): unbindWebServices(): un-registering our AIDL callback...
,D/MobileConnectivityChangeReceiver( 4341): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4341): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 4409): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,I/iu.UploadsManager( 4409): #reloadSettings(); account: null; pageID: none; IU: disabled; IS: disabled; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,I/iu.FingerprintManager( 4409): Start processing all media
,D/dalvikvm( 4409): GC_FOR_ALLOC freed 391K, 5% free 16422K/17224K, paused 15ms, total 15ms
,I/dalvikvm-heap( 4409): Grow heap (frag case) to 19.806MB for 1821008-byte allocation
,I/iu.FingerprintManager( 4409): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 4409): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 4409): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 4409): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 4409): Finished generating fingerprints; 0.032 seconds
,I/iu.FingerprintManager( 4409):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/ContactLocale( 4426): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/dalvikvm( 4409): GC_FOR_ALLOC freed 21K, 5% free 18191K/19004K, paused 11ms, total 11ms
,I/iu.UploadsManager( 4409): End new media; added: 0, uploading: 0, time: 93 ms
,D/WifiP2pService( 1021): P2pDisabledState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): DefaultState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1021): handleMessage: E msg.what=131089
,D/WifiStateMachine( 1021): processMsg: InitialState
D/WifiStateMachine( 1021): processMsg: DefaultState
,D/WifiStateMachine( 1021): handleMessage: X
,V/AlarmManager( 1021): sending alarm Alarm{42fb8b60 type 2 com.android.keyguard}
,V/AlarmManager( 1021): sending alarm Alarm{42fb2918 type 2 android}
,I/GAV2    ( 4368): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService( 1021): NetTransition Wakelock for ConnectedState released by timeout
,V/AlarmManager( 1021): sending alarm Alarm{42f482c8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{44505590 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42ba8128 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{4307acf0 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42ac23f8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{44449878 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42fceae0 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42f44668 type 2 android}
,D/ConnectivityService( 1021): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1021): Done.
,D/ConnectivityService( 1021): Setting timer for 720seconds
,V/AlarmManager( 1021): sending alarm Alarm{42cdcff0 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42ef4d80 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{42f14b40 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{428ebd30 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{441cf5b0 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42ee8fa8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42f44528 type 1 com.android.deskclock}
,I/ActivityManager( 1021): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4491 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1021): Killing 4288:com.motorola.deviceauthenticator/u0a16 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager( 1021): sending alarm Alarm{42f2fef8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{44505e30 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42ef0e20 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{430514d8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{429cbce8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42ec0b68 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{44e54c00 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{44421f50 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{4436da60 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{427600d8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{441a9c88 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{43c7b908 type 3 android}
,I/ProcessStatsService( 1021): Prepared write state in 38ms
,I/ProcessStatsService( 1021): Prepared write state in 18ms
,I/ProcessStatsService( 1021): Pruning old procstats: /data/system/procstats/state-2015-12-09-18-11-09.bin
,V/AlarmManager( 1021): sending alarm Alarm{429d95e8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{426a3308 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{430449a8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42cae1f0 type 2 android}
,D/ConnectivityService( 1021): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1021): sending alarm Alarm{42fc9c98 type 1 com.android.deskclock}
,D/ConnectivityService( 1021): Done.
,D/ConnectivityService( 1021): Setting timer for 720seconds
,V/AlarmManager( 1021): sending alarm Alarm{44d18390 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms)
```
