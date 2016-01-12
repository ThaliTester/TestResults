#### Test 55613145ac448d4_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1019): sending alarm Alarm{431a9858 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 3640): 
D/AndroidRuntime( 3640): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3640): CheckJNI is OFF
D/dalvikvm( 3640): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3640): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3640): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3640): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3640): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3640): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3640): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3640): failed to load memtrack module: -2
D/AndroidRuntime( 3640): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3640
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3657 uid=10544 gids={50544, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3640): Shutting down VM
D/dalvikvm( 3640): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 2ms
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3657): Binding Chromium to main looper Looper (main, tid 1) {41f33818}
I/LibraryLoader( 3657): Expected native library version number "",actual native library version number ""
I/chromium( 3657): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3657): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43ca8ae0:true
D/BluetoothAdapter( 3657): 1106543992: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3657): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3657): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3657): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3657): Local Branch: 
I/Adreno-EGL( 3657): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3657): Local Patches: NONE
I/Adreno-EGL( 3657): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3657): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3657): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 3657): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3657): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3657): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3657): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3657): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3657): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 3657): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3657): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3657): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3657): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3657): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3657): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3657): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3657): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3657): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3657): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3657): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3657): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3657): Enabling debug mode 0
,W/AwContents( 3657): nativeOnDraw failed; clearing to background color.
,W/AwContents( 3657): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1019): Displayed com.test.thalitest/.MainActivity,cp,ca,404
I/ActivityManager( 1019): Displayed com.test.thalitest/.MainActivity: +376ms (total +404ms)
W/IInputConnectionWrapper( 3657): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 3657): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3657): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f37ae8
,D/dalvikvm( 3657): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f37ae8
,D/jxcore_app_log( 3657): JniHelper::setJavaVM(0x41589fa8), pthread_self() = 1614078024
,D/JX-Cordova( 3657): jxcore cordova android initializing
,D/dalvikvm( 3657): GC_CONCURRENT freed 2759K, 17% free 14430K/17224K, paused 2ms+2ms, total 60ms
D/dalvikvm( 3657): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 3657): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 3657): GC_FOR_ALLOC freed 168K, 17% free 14412K/17224K, paused 27ms, total 29ms
,D/dalvikvm( 3657): GC_FOR_ALLOC freed 302K, 16% free 14471K/17224K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3657): Grow heap (frag case) to 16.301MB for 143930-byte allocation
,D/dalvikvm( 3657): GC_FOR_ALLOC freed 263K, 17% free 14509K/17368K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3657): Grow heap (frag case) to 16.408MB for 215890-byte allocation
,D/dalvikvm( 3657): GC_FOR_ALLOC freed 368K, 18% free 14583K/17580K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3657): Grow heap (frag case) to 16.583MB for 323830-byte allocation
,D/dalvikvm( 3657): GC_FOR_ALLOC freed 568K, 18% free 14704K/17900K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3657): Grow heap (frag case) to 16.855MB for 485740-byte allocation
,D/dalvikvm( 3657): GC_FOR_ALLOC freed 864K, 20% free 14879K/18376K, paused 27ms, total 28ms
,I/dalvikvm-heap( 3657): Grow heap (frag case) to 17.257MB for 728606-byte allocation
,D/dalvikvm( 3657): GC_FOR_ALLOC freed 1284K, 21% free 15136K/19088K, paused 28ms, total 29ms
,D/dalvikvm( 3657): GC_CONCURRENT freed 1678K, 19% free 15505K/19088K, paused 2ms+4ms, total 35ms
,D/dalvikvm( 3657): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 3657): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 3657): GC_FOR_ALLOC freed 368K, 19% free 15462K/19088K, paused 28ms, total 28ms
,I/dalvikvm-heap( 3657): Grow heap (frag case) to 18.696MB for 1639352-byte allocation
,D/dalvikvm( 3657): GC_CONCURRENT freed 1769K, 23% free 16040K/20692K, paused 1ms+4ms, total 54ms
,D/dalvikvm( 3657): GC_FOR_ALLOC freed 1250K, 23% free 16085K/20692K, paused 29ms, total 31ms
,I/dalvikvm-heap( 3657): Grow heap (frag case) to 20.085MB for 2459024-byte allocation
,D/dalvikvm( 3657): GC_CONCURRENT freed 345K, 21% free 18408K/23096K, paused 5ms+4ms, total 61ms
,D/dalvikvm( 3657): GC_FOR_ALLOC freed 4303K, 27% free 17080K/23096K, paused 37ms, total 37ms
,I/dalvikvm-heap( 3657): Grow heap (frag case) to 22.230MB for 3688532-byte allocation
,D/dalvikvm( 3657): GC_CONCURRENT freed 129K, 23% free 20680K/26700K, paused 4ms+6ms, total 48ms
,D/dalvikvm( 3657): GC_FOR_ALLOC freed 3498K, 33% free 18050K/26700K, paused 38ms, total 38ms
,W/jxcore-log( 3657): Initializing JXcore engine
,W/jxcore-log( 3657): JXcore engine is ready
,D/dalvikvm( 3657): GC_CONCURRENT freed 391K, 23% free 20661K/26700K, paused 1ms+3ms, total 37ms
,D/dalvikvm( 3657): WAIT_FOR_CONCURRENT_GC blocked 32ms
,W/jxcore-log( 3657): Starting JXcore engine
,W/jxcore-log( 3657): Platform android
W/jxcore-log( 3657): 
,W/jxcore-log( 3657): Process ARCH arm
W/jxcore-log( 3657): 
,I/jxcore-log( 3657): JXcore Cordova bridge is ready!
I/jxcore-log( 3657): 
,W/jxcore-log( 3657): JXcore engine is started
,I/chromium( 3657): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3657): Toggling radios to true
I/jxcore-log( 3657): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1019): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService( 1019): Message: 1
,D/BluetoothManagerService( 1019): MESSAGE_ENABLE: mBluetooth = null
,W/Settings( 1252): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/XTWiFiOS( 1266): No entry in secure settings for enhanced location services: false
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1266): Active network info is not available
,D/WifiService( 1019): New client listening to asynchronous messages
,D/WifiService( 1019): setWifiEnabled: true pid=3657, uid=10544
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
,I/ActivityManager( 1019): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3712 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1023}
,W/Settings( 1252): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1252): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiStateMachine( 1019): setting operational mode to 1
D/WifiStateMachine( 1019): handleMessage: E msg.what=131083
,D/WifiStateMachine( 1019): processMsg: InitialState
,W/XTWiFiOS( 1266): No entry in secure settings for enhanced location services: false
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1266): Active network info is not available
I/jxcore-log( 3657): Radios toggled
I/jxcore-log( 3657): 
I/jxcore-log( 3657): My device name is: motorola-XT1039
I/jxcore-log( 3657): 
,W/Settings( 1252): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/AdapterServiceConfig( 3712): Adding HeadsetService
,D/AdapterServiceConfig( 3712): Adding A2dpService
D/AdapterServiceConfig( 3712): Adding HidService
D/AdapterServiceConfig( 3712): Adding HealthService
D/AdapterServiceConfig( 3712): Adding PanService
D/AdapterServiceConfig( 3712): Adding GattService
,D/AdapterServiceConfig( 3712): Adding BluetoothMapService
,D/BluetoothAdapterService( 3712): REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothManagerService( 1019): Message: 20
,D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43a73f10:true
,D/BluetoothAdapterState( 3712): make
,I/BluetoothAdapterState( 3712): Entering OffState
,I/bluedroid( 3712): init
,I/bte_conf( 3712): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bluedroid( 3712): get_profile_interface socket
,D/BluetoothManagerService( 1019): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1019): Message: 40
,D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/GKI_LINUX( 3712): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
,I/bluedroid( 3712): config_hci_snoop_log
I/BluetoothAdapterProperties( 3712): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothManagerService( 1019): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService( 1019): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterProperties( 3712): Address is:F4:F1:E1:5C:3B:E2
D/BluetoothAdapterState( 3712): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
I/BluetoothAdapterProperties( 3712): adapterPropertyChangedCallback with type:1 len:6
D/BluetoothAdapterProperties( 3712): Setting state to 11
I/BluetoothAdapterState( 3712): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3712): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1019): Message: 60
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3712): make
,D/BluetoothAdapterProperties( 3712): Name is: XT1039
,D/BluetoothManagerService( 1019): Bluetooth Adapter name changed to XT1039
,D/BluetoothManagerService( 1019): Stored Bluetooth name: XT1039
,I/ActivityManager( 1019): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3739 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/BluetoothBondStateMachine( 3712): StableState(): Entering Off State
,D/BluetoothHeadset( 1242): Proxy object connected
,D/BluetoothHeadset( 1019): Proxy object connected
D/BluetoothHeadset( 1242): Proxy object connected
,D/BluetoothHeadset( 1242): Proxy object connected
,D/HeadsetService( 3712): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 3712): classInitNative: succeeds
D/HeadsetStateMachine( 3712): Version 1.6
,D/HeadsetStateMachine( 3712): make
,I/BluetoothAdapterState( 3712): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/bluedroid( 3712): get_profile_interface handsfree
,D/BluetoothA2dp( 1019): Proxy object connected
D/A2dpService( 3712): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3712): classInitNative: succeeds
,V/Avrcp   ( 3712): make
,I/bluedroid( 3712): get_profile_interface avrcp
,I/BluetoothA2dpServiceJni( 3712): classInitNative: succeeds
,D/A2dpStateMachine( 3712): make
,I/bluedroid( 3712): get_profile_interface a2dp
,I/GKI_LINUX( 3712): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 3712): warning : no command pending, ignore ack
,D/A2dpStateMachine( 3712): Enter Disconnected: -2
I/BluetoothHidServiceJni( 3712): classInitNative: succeeds
,D/HidService( 3712): Received start request. Starting profile...
,I/bluedroid( 3712): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 3712): classInitNative: succeeds
,D/HealthService( 3712): Received start request. Starting profile...
,I/bluedroid( 3712): get_profile_interface health
,I/BluetoothPanServiceJni( 3712): classInitNative(L105): succeeds
,D/BluetoothPan( 1019): BluetoothPAN Proxy object connected
,D/PanService( 3712): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3712): initializeNative(L110): pan
,I/bluedroid( 3712): get_profile_interface pan
,D/BluetoothTethering( 1019): got CMD_CHANNEL_HALF_CONNECTED
,D/BluetoothTethering( 1019): CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@43a25a40
,I/BtGatt.JNI( 3712): classInitNative(L684): classInitNative: Success!
,D/BtGatt.DebugUtils( 3712): handleDebugAction() action=null
,D/BtGatt.GattService( 3712): Received start request. Starting profile...
,D/BtGatt.GattService( 3712): start()
,I/bluedroid( 3712): get_profile_interface gatt
,D/BluetoothMapService( 3712): Received start request. Starting profile...
,D/BluetoothMapService( 3712): start()
,D/HeadsetPhoneState( 3712): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/BluetoothAdapterService( 3712): Profile still not running:com.android.bluetooth.hdp.HealthService
D/HeadsetPhoneState( 3712): onSignalStrengthsChanged..for signal  prevSignal=0
D/BluetoothAdapterService( 3712): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 3712): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 3712): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/HeadsetPhoneState( 3712): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterService( 3712): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3712): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterState( 3712): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3712): enable
,I/bt_hci_bdroid( 3712): init
I/bt_vendor( 3712): bt-vendor : init
I/bt_hci_bdroid( 3712): ro.qualcomm.hci_transport set to smd
D/bt_userial_mct( 3712): userial_init
I/bt_hwcfg( 3712): Starting hciattach daemon
,I/bt_hwcfg( 3712): try to set false
,I/bt_hci_bdroid( 3712): bt_hc_worker_thread started
I/bt_hwcfg( 3712): Starting hciattach daemon
,I/bt_hwcfg( 3712): try to set true
,I/qcom-bluetooth( 3772): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/qcom-bluetooth( 3778): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 3779): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/ActivityManager( 1019): Killing 3331:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
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
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/TCMD    (  505): NL - Read 1004 bytes from update socket.
D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/TCMD    (  505): NL - message type is RTM_NEWLINK
D/TCMD    (  505): Listening for incoming client connection request
D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1019): InitialState.processMessage what=4
D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
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
E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
I/qcom-bluetooth( 3781): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
D/TCMD    (  505): NL - Read 1004 bytes from update socket.
D/TCMD    (  505): NL - message type is RTM_NEWLINK
D/TCMD    (  505): Listening for incoming client connection request
I/qcom-bluetooth( 3784): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
D/QsoftapCmd(  271): Got softap fwreload command we are passing on
D/SoftapController(  271): Softap fwReload - Ok
I/qcom-bluetooth( 3785): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
D/CommandListener(  271): Setting iface cfg
D/CommandListener(  271): Trying to bring down wlan0
,E/Diag_Lib( 3787): qmi_init:  Not initialized, calling process init sequence
E/Diag_Lib( 3787): Setting internal use port to rmnet0
E/Diag_Lib( 3787):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,E/Diag_Lib( 3787): Failed on DIAG init
E/Diag_Lib( 3787): linux_qmi_qmux_if_client_get_proc_name: pid=3787, proc_name=hci_qcomm_init
E/Diag_Lib( 3787): linux_qmi_qmux_if_client_get_socket_paths: num_grps=2
E/Diag_Lib( 3787): linux_qmi_qmux_if_client_get_proc_group_name: gid=1002, grp_name=bluetooth
E/Diag_Lib( 3787): using socket paths bind=/dev/socket/qmux_bluetooth/qmux_client_socket, connect=/dev/socket/qmux_bluetooth/qmux_connect_socket
E/Diag_Lib( 3787): qmi_client [3787]: successfully connected to server, attempt=1
E/Diag_Lib( 3787): linux_qmi_qmux_if_client_get_client_id [3787]: qmux_client_id=13
E/Diag_Lib( 3787): qmi_client [3787] 13: qmux_client ID is initialized
E/Diag_Lib( 3787): qmi_client [3787] 13: pipe() system call, fd[0]=10, fd[1]=11
,E/Diag_Lib( 3787): qmi_client [3787] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3787): qmi_client [3787] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3787): Sending signal ...... to read cmd data 
E/Diag_Lib( 3787): qmi error code.........:0
E/Diag_Lib( 3787): qmi sys error code.........:0
E/Diag_Lib( 3787): qmi_qmux_if_pwr_up_init_ex:  Successfully created and added QMUX client 19
E/Diag_Lib( 3787): qmi_nas_srvc_init: NAS successfully initialized
E/Diag_Lib( 3787): qmi_qos_srvc_init: QOS successfully initialized
E/Diag_Lib( 3787): qmi_eap_srvc_init: EAP successfully initialized
E/Diag_Lib( 3787): qmi_wds_srvc_init: WDS successfully initialized
E/Diag_Lib( 3787): qmi_atcop_srvc_init: ATCOP successfully initialized
E/Diag_Lib( 3787): qmi_uim_srvc_init: UIM successfully initialized
E/Diag_Lib( 3787): qmi_cat_srvc_init: CAT successfully initialized
E/Diag_Lib( 3787): qmi_init:  Created client handle b8435788
,E/Diag_Lib( 3787): qmi_client [3787] 13: sending 880 bytes on fd = 8
,E/WifiHW  ( 1019): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
,E/WifiHW  ( 1019): ctrl_interface != /data/misc/wifi/sockets
E/Diag_Lib( 3787): qmi_client [3787] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3787): Sending signal ...... to read cmd data 
E/Diag_Lib( 3787): qmi error code.........:0
E/Diag_Lib( 3787): qmi sys error code.........:0
,D/WifiStateMachine( 1019): setWifiState: enabling
E/Diag_Lib( 3787): Setting the api flag to : 1
,E/Diag_Lib( 3787): qmi_client [3787] 13: sending 54 bytes on fd = 8
,D/WifiStateMachine( 1019): Supplicant start successful
,D/WifiMonitor( 1019): startMonitoring(wlan0) with mConnected = false
,I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
W/XTWiFiOS( 1266): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1266): Active network info is not available
,D/WifiService( 1019): New client listening to asynchronous messages
,V/BluetoothFtpReceiver( 3712): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,D/AuthorizationBluetoothService( 1348): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/wpa_supplicant( 3793): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3793): rfkill: Cannot open RFKILL control device
D/TCMD    (  505): NL - Read 1000 bytes from update socket.
D/TCMD    (  505): NL - message type is RTM_NEWLINK
,D/TCMD    (  505): Listening for incoming client connection request
D/TCMD    (  505): NL - Read 1000 bytes from update socket.
D/TCMD    (  505): NL - message type is RTM_NEWLINK
,D/TCMD    (  505): Listening for incoming client connection request
,I/rmt_storage(  431): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb79301d0
I/rmt_storage(  431): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  431): wakelock acquired: 1, error no: 42
,I/rmt_storage(  431): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1215102408)
E/Diag_Lib( 3787): qmi_client [3787] 13: Received 54 bytes on fd = 8
E/Diag_Lib( 3787):  API Flag .............. 1 
,E/Diag_Lib( 3787):  Message ID ............... 92 
E/Diag_Lib( 3793): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 3793): Setting internal use port to rmnet0
,E/wpa_supplicant( 3793): baseband property is set to [msm]
,E/wpa_supplicant( 3793):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3793): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3793): card_info[i].card_state: 0x2
E/wpa_supplicant( 3793): card_info[i].error_code: 0x3
E/wpa_supplicant( 3793): SIM/USIM not ready
,E/wpa_supplicant( 3793): Error while reading SIM card status
,E/wpa_supplicant( 3793): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3793): card_info[i].card_state: 0x2
E/wpa_supplicant( 3793): card_info[i].error_code: 0x3
E/wpa_supplicant( 3793): SIM/USIM not ready
,I/wpa_supplicant( 3793): eap_proxy: Card not ready
,E/Diag_Lib( 3787): qmi_service_release called, user_handle=30200
E/Diag_Lib( 3787): qmi_free_srvc_data : ENTRY
E/Diag_Lib( 3787): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib( 3787): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib( 3787): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib( 3787): qmi_service_delete_client_txns : ENTRY - conn_id=0, service=2, client=3
E/Diag_Lib( 3787): qmi_service_delete_client_txns : EXIT
E/Diag_Lib( 3787): qmi_free_srvc_data : EXIT
,E/Diag_Lib( 3787): qmi_client [3787] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3787): qmi_client [3787] 13: Received 880 bytes on fd = 8
,E/Diag_Lib( 3787): Sending signal ...... to read cmd data 
E/Diag_Lib( 3787): qmi error code.........:0
E/Diag_Lib( 3787): qmi sys error code.........:0
E/Diag_Lib( 3787): qmi_release: Released client handle ff
E/Diag_Lib( 3787): qmi_release: Last client releases, performing library de-init
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=0
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=1
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=2
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=3
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=4
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=5
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=6
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=7
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=8
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=9
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=10
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=11
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=12
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=13
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=14
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=15
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=16
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=17
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=18
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=19
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=20
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=21
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=22
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=23
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=24
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=25
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=26
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=27
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=28
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=29
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=30
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=31
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=32
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=33
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=34
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=35
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=36
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=37
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=38
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=39
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=40
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=41
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=42
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=43
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=44
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=45
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=46
E/,Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=47
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=48
E/Diag_Lib( 3787): Called qmi_service_reset_all, release on modem=1, conn_id=49
E/Diag_Lib( 3787): qmi_nas_srvc_release: NAS successfully released
E/Diag_Lib( 3787): qmi_qos_srvc_release: QOS successfully released
E/Diag_Lib( 3787): qmi_eap_srvc_release: EAP successfully released
E/Diag_Lib( 3787): qmi_wds_srvc_release: WDS successfully released
E/Diag_Lib( 3787): qmi_atcop_srvc_release: ATCOP successfully released
E/Diag_Lib( 3787): qmi_nas_srvc_release: UIM successfully released
E/Diag_Lib( 3787): qmi_cat_srvc_release: CAT successfully released
E/Diag_Lib( 3787): qmi_client [3787] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3787): qmi_client [3787] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3787): Sending signal ...... to read cmd data 
E/Diag_Lib( 3787): qmi error code.........:0
E/Diag_Lib( 3787): qmi sys error code.........:0
E/Diag_Lib( 3787): qmi_qmux_if_pwr_down_release: Released QMUX client handle [3787] 13
E/Diag_Lib( 3787): qmi_client [3787] 13: Client release, writing pipe to kill read thread, fd = 11
E/Diag_Lib( 3787): qmi_client [3787] 13: failed to locate client data
E/Diag_Lib( 3787): qmi_client [3787] 13: calling release of fd=8
,E/Diag_Lib( 3787): qmi_qmux_if_pwr_down_release: Last client releases, performing de-init
,D/Checkin ( 2123): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2123): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/rmt_storage(  431): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  431): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  431): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1215102408) wakelock released: 1, error no: 0
I/rmt_storage(  431): 
,I/rmt_storage(  431): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb79301d0
,I/wpa_supplicant( 3793): Long line in configuration file truncated
,I/wpa_supplicant( 3793): rfkill: Cannot open RFKILL control device
D/TCMD    (  505): NL - Read 1000 bytes from update socket.
D/TCMD    (  505): NL - message type is RTM_NEWLINK
,D/TCMD    (  505): Listening for incoming client connection request
,I/qcom-bluetooth( 3797): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 f4:f1:e1:5c:3b:e2 
,I/qcom-bluetooth( 3798): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,E/wpa_supplicant( 3793): COUNTRY Code Recived
,E/wpa_supplicant( 3793): COUNTRY Code Recived -COUNTRY PL
,E/wpa_supplicant( 3793): baseband property is set to [msm]
,I/bt_hwcfg( 3712): bluetooth satus is on
I/GKI_LINUX( 3712): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3712): btu_task pending for preload complete event
,D/bt_userial_mct( 3712): userial_open(port:0)
,I/bt_userial_vendor( 3712): Done intiailizing UART
I/bt_userial_vendor( 3712): Done intiailizing UART
I/bt_userial_mct( 3712): CMD=72, EVT=72, ACL_Out=73, ACL_In=73
I/bt_vendor( 3712): Bluetooth Firmware and smd is initialized
,D/bt_userial_mct( 3712): Entering userial_read_thread()
,I/bt-btu  ( 3712): btu_task received preload complete event
,E/wpa_supplicant( 3793):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3793): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3793): card_info[i].card_state: 0x2
E/wpa_supplicant( 3793): card_info[i].error_code: 0x3
E/wpa_supplicant( 3793): SIM/USIM not ready
,E/wpa_supplicant( 3793): Error while reading SIM card status
I/        ( 3712): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3712): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3712): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3712): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3712): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3712): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3712): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3712): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3712): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3712): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3712): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3712): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3712): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3712): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 3712): BTE_InitTraceLevels -- TRC_BTIF
E/wpa_supplicant( 3793): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3793): card_info[i].card_state: 0x2
E/wpa_supplicant( 3793): card_info[i].error_code: 0x3
E/wpa_supplicant( 3793): SIM/USIM not ready
,I/wpa_supplicant( 3793): eap_proxy: Card not ready
D/WifiStateMachine( 1019): transitionTo: destState=SupplicantStartingState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: InitialState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131144
,D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): deferMessage: msg=131144
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131085
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
,D/WifiStateMachine( 1019): deferMessage: msg=131085
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131149
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
,D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): setSuspendOptimizations: 2 true
D/WifiStateMachine( 1019): mSuspendOptNeedsDisabled 0
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131145
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131146
,D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
,D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147457
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
,D/WifiStateMachine( 1019): Supplicant connection established
,D/WifiStateMachine( 1019): setWifiState: enabled
,I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,D/WifiConfigStore( 1019): Loading config and enabling all networks
,W/XTWiFiOS( 1266): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1266): Active network info is not available
,E/WifiConfigStore( 1019): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,E/wpa_supplicant( 3793): COUNTRY Code Recived -COUNTRY PL
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/WifiStateMachine( 1019): transitionTo: destState=DriverStartedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
,D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStartedState
,E/bt-btm  ( 3712): BTM_SecRegister:p_cb_info->p_le_callback == 0x5f0cb049 
,E/bt-btm  ( 3712): BTM_SecRegister: btm_cb.api.p_le_callback = 0x5f0cb049 
,D/WifiStateMachine( 1019): invokeEnterMethods: DriverStartedState
,D/WifiStateMachine( 1019): setDetailed state, old =IDLE and new state=DISCONNECTED
,E/bt-btif ( 3712): Calling BTA_HhEnable
,E/bt-btif ( 3712): btif_storage_get_adapter_property service_mask:0x140040
E/wpa_supplicant( 3793): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 3793): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,I/BluetoothAdapterProperties( 3712): adapterPropertyChangedCallback with type:2 len:6
,D/WifiStateMachine( 1019): Attempting to reconnect to wifi network ..
D/BluetoothAdapterProperties( 3712): Address is:F4:F1:E1:5C:3B:E2
,I/BluetoothAdapterProperties( 3712): adapterPropertyChangedCallback with type:1 len:6
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
D/BluetoothAdapterProperties( 3712): Name is: XT1039
D/BluetoothManagerService( 1019): Bluetooth Adapter name changed to XT1039
I/BluetoothAdapterProperties( 3712): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothManagerService( 1019): Stored Bluetooth name: XT1039
D/BluetoothAdapterProperties( 3712): Scan Mode:21
I/BluetoothAdapterProperties( 3712): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3712): Discoverable Timeout:120
I/BluetoothAdapterProperties( 3712): adapterPropertyChangedCallback with type:8 len:0
I/BluetoothAdapterProperties( 3712): adapterPropertyChangedCallback with type:3 len:48
I/bte_conf( 3712): Attempt to load did conf from /etc/bluetooth/bt_did.conf
E/bt_mct  ( 3712): hci lib postload completed
I/bte_conf( 3712): [1] primary_record=1 vendor_id=0x001D vendor_id_source=0x0001 product_id=0x1200 version=0x1436
I/bte_conf( 3712): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 3712): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothAdapterState( 3712): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3712): ScanMode =  21
D/BluetoothAdapterProperties( 3712): State =  11
D/BluetoothPanServiceJni( 3712): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
D/BluetoothAdapterProperties( 3712): Setting state to 12
I/BluetoothAdapterState( 3712): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3712): Broadcasting updateAdapterState() to 1 receivers.
I/BluetoothAdapterProperties( 3712): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3712): Discoverable Timeout:120
D/BluetoothManagerService( 1019): Message: 60
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1019): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/CommandListener(  271): Setting iface cfg
D/BluetoothHeadset( 1242): onBluetoothStateChange: up=true
D/CommandListener(  271): Trying to bring up p2p0
D/BluetoothPan( 1019): onBluetoothStateChange on: true
D/BluetoothHeadset( 1242): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 3712): Entering On State
D/BluetoothA2dp( 1019): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1242): onBluetoothStateChange: up=true
D/WifiMonitor( 1019): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 1019): P2pEnablingState
D/WifiP2pService( 1019): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2p socket connection successful
D/BluetoothHeadset( 1019): onBluetoothStateChange: up=true
,D/WifiP2pService( 1019): P2pEnabledState
D/BluetoothAdapterService(1106531704)( 3712): Get Bonded Devices being called
D/BluetoothAdapterService(1106531704)( 3712): Get Bonded Devices being called
D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 11 -> 12
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131144
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131085
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/BluetoothManagerService( 1019): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothMapService( 3712): onReceive
D/BluetoothMapService( 3712): STATE_ON
D/BluetoothMapService( 3712): Map Service startRfcommSocketListener
D/BluetoothManagerService( 1019): Message: 40
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131152
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): set country code PL
,D/WifiP2pService( 1019): sending p2p connection changed broadcast
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothAdapterService(1106531704)( 3712): Get Bonded Devices being called
,D/BluetoothMapService( 3712): Map Service initSocket
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3712): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3712): SOCK FLAG = 1 ***********************
,I/BluetoothAdapterProperties( 3712): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothMapService( 3712): Accepting socket connection...
,D/BluetoothAdapterProperties( 3712): Scan Mode:21
D/WifiP2pService( 1019): DeviceAddress: f4:f1:e1:5c:43:c8
,W/ContextImpl( 3739): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/qcom-bt-wlan-coex( 3813): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
D/WifiP2pService( 1019): MCC mode enabled 0
D/WifiP2pService( 1019): mP2pAutoConnectSupport = 0
D/WifiP2pService( 1019): sending p2p persistent groups changed broadcast
D/WifiP2pService( 1019): InactiveState
D/WifiP2pService( 1019): InactiveState{ when=-7ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-7ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 3793): COUNTRY Code Recived
E/wpa_supplicant( 3793): COUNTRY Code Recived
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43516fa8:true
,D/BluetoothPbapService( 3712): action: android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothPbapService( 3712): Handler(): got msg=1
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3712): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3712): SOCK FLAG = 1 ***********************
,D/LocalBluetoothProfileManager( 3739): Adding local A2DP profile
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3739): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
D/LocalBluetoothProfileManager( 3739): Adding local HEADSET profile
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3739): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
E/wpa_supplicant( 3793): COUNTRY Code Recived
E/wpa_supplicant( 3793): COUNTRY Code Recived
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131162
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): set frequency band 2
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService( 1019): Message: 30
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiP2pService( 1019): InactiveState{ when=-5ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,W/ContextImpl( 3739): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiP2pService( 1019): P2pEnabledState{ when=-8ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131167
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
E/SharedPreferencesImpl( 1019): Couldn't create directory for SharedPreferences file shared_prefs/wifi_sm_shared_prefs.xml
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
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3739): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 3739): Adding local MAP profile
D/BluetoothMap( 3739): Create BluetoothMap proxy object
,D/dalvikvm( 1019): GC_EXPLICIT freed 22827K, 65% free 17871K/50428K, paused 4ms+10ms, total 142ms
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3739): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3739): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 3739): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 3739): finishStartingService: stopping service
,D/BluetoothAdapterService(1106531704)( 3712): Get Bonded Devices being called
,D/BluetoothA2dp( 3739): Proxy object connected
,D/A2dpProfile( 3739): Bluetooth service connected
,D/BluetoothHeadset( 3739): Proxy object connected
,D/HeadsetProfile( 3739): Bluetooth service connected
,D/BluetoothInputDevice( 3739): Proxy object connected
,D/HidProfile( 3739): Bluetooth service connected
,D/BluetoothPan( 3739): BluetoothPAN Proxy object connected
,D/PanProfile( 3739): Bluetooth service connected
D/BluetoothMap( 3739): Proxy object connected
,D/MapProfile( 3739): Bluetooth service connected
,D/BluetoothMap( 3739): getConnectedDevices()
,D/BluetoothPbap( 3739): Proxy object connected
,D/PbapServerProfile( 3739): Bluetooth service connected
,D/Checkin ( 2123): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2123): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,V/BluetoothFtpReceiver( 3712): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 3712): BluetoothFtpReceiver Start Service
,D/AuthorizationBluetoothService( 1348): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1348): Proximity feature is not enabled.
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothFtpService( 3712): Ftp Service onCreate
I/BluetoothFtpService( 3712): FFFFFtp Service onCreate
,V/BluetoothFtpService( 3712): Starting FTP service
V/BluetoothFtpService( 3712): Ftp Service onStartCommand
,V/BluetoothFtpService( 3712): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpService( 3712): Handler(): got msg=1
V/BluetoothFtpService( 3712): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 3712): Ftp Service initSocket
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3712): getBluetoothService() called with no BluetoothManagerCallback
,W/BluetoothAdapter( 3712): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3712): SOCK FLAG = 0 ***********************
,E/BluetoothServiceJni( 3712): SOCK FLAG = 3 ***********************
,V/BluetoothFtpService( 3712): Succeed to create listening socket on channel 20
,I/BtOppRfcommListener( 3712): Accept thread started.
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3712): Run Accept thread
,D/TCMD    (  505): NL - Read 1000 bytes from update socket.
D/TCMD    (  505): NL - message type is RTM_NEWLINK
,D/TCMD    (  505): Listening for incoming client connection request
,I/MDMCTBK (  273): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  273): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): wifi_connect_to_supplicant, current pid is = 273
D/MDMCTBK (  273): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  273): wifi_close_sockets: Exit
,E/MDMCTBK (  273): Attach monitor thread
I/MDMCTBK (  273): createWifiMonitorThread: Started the wifi monitor thread -1208084936
,D/MDMCTBK (  273): wifi_wait_on_socket: Enter monitor thread
,D/Checkin ( 2123): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2123): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledStateupdate channel list
,I/wpa_supplicant( 3793): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  273): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c2:ff:d4:d3:aa:48
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 0 c2:ff:d4:d3:aa:48
D/MDMCTBK (  273): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 c0:ff:d4:d3:aa:48
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 1 c0:ff:d4:d3:aa:48
D/MDMCTBK (  273): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 38:f8:89:11:e9:11
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 2 38:f8:89:11:e9:11
D/MDMCTBK (  273): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 10:9a:dd:8e:22:d9
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 3 10:9a:dd:8e:22:d9
D/MDMCTBK (  273): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 64:7c:34:57:51:e2
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 4 64:7c:34:57:51:e2
D/MDMCTBK (  273): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 80:c6:ab:29:84:a8
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 5 80:c6:ab:29:84:a8
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  273): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  273): Event received = Trying to associate with
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3791): fatal error opening "/sys/power/wake_lock"
,I/wpa_supplicant( 3791): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
D/TCMD    (  505): NL - Read 56 bytes from update socket.
D/TCMD    (  505): NL - message type is RTM_NEWLINK
,D/TCMD    (  505): Listening for incoming client connection request
,E/wpa_supplicant( 3793): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,I/wpa_supplicant( 3793): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  505): NL - Read 312 bytes from update socket.
D/TCMD    (  505): NL - message type is RTM_NEWLINK
D/TCMD    (  505): Listening for incoming client connection request
D/TCMD    (  505): NL - Read 192 bytes from update socket.
D/TCMD    (  505): NL - message type is RTM_NEWLINK
D/TCMD    (  505): Listening for incoming client connection request
D/TCMD    (  505): NL - Read 68 bytes from update socket.
D/TCMD    (  505): NL - message type is RTM_NEWLINK
D/TCMD    (  505): Listening for incoming client connection request
D/TCMD    (  505): NL - Read 1000 bytes from update socket.
D/TCMD    (  505): NL - message type is RTM_NEWLINK
,D/TCMD    (  505): Listening for incoming client connection request
,I/wpa_supplicant( 3793): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 3793): wlan0: Associated with c0:ff:d4:d3:aa:48
D/TCMD    (  505): NL - Read 80 bytes from update socket.
D/TCMD    (  505): NL - message type is RTM_NEWLINK
D/TCMD    (  505): Listening for incoming client connection request
D/TCMD    (  505): NL - Read 80 bytes from update socket.
D/TCMD    (  505): NL - message type is RTM_NEWLINK
D/TCMD    (  505): Listening for incoming client connection request
D/TCMD    (  505): NL - Read 68 bytes from update socket.
D/TCMD    (  505): NL - message type is RTM_NEWLINK
D/TCMD    (  505): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  273): Event received = Associated with c0:ff:d4
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3793): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3793): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  273): Event received = WPA: Key negotiation com
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  273): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  273):  STA Connected !!
D/TCMD    (  505): NL - Read 1000 bytes from update socket.
D/TCMD    (  505): NL - message type is RTM_NEWLINK
,D/TCMD    (  505): Listening for incoming client connection request
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
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=0, p2p0 = 1, wlan0 = 1, data=0
E/MDMCTBK (  273): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  273): get_freq !!, resp=0
I/MDMCTBK (  273): get_freq !!, Strip data
I/MDMCTBK (  273): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  273): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  273): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): get_property_value, Enter
I/MDMCTBK (  273): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  273): get_property_value, Exit
I/MDMCTBK (  273): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1208089040
I/MDMCTBK (  273): return from set_get_from_wpa_supplicant
I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147459
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): Network connection established
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/MDMCTBK (  273): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  273): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  273): , reply_len: 3, ret: 0
E/MDMCTBK (  273): MdmCutbackHndler, resp=OK
E/MDMCTBK (  273): 
,D/MDMCTBK (  273): wifi_set_tx_pwr: Exit
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
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
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-58ms what=147462 obj=android.net.wifi.StateChangeResult@4201f008 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-39ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@42215890 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196612
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427ae8e8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427ae8e8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 6
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 6 6
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 10
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 4 10
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 64
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 5 64
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 80
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 6 80
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  273): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/TCMD    (  505): NL - Read 56 bytes from update socket.
D/TCMD    (  505): NL - message type is RTM_NEWLINK
,D/TCMD    (  505): Listening for incoming client connection request
D/WifiStateMachine( 1019): ObtainingIpState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4201d6d8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4201d6d8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4201d6d8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
,D/TCMD    (  505): NL - Read 60 bytes from update socket.
D/TCMD    (  505): NL - ignore NL message, type = 20
D/TCMD    (  505): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): DHCP successful
D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1019): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1019): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1019): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState enter
D/WifiStateMachine( 1019): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=151572
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState what=151572 NOT_HANDLED
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=135190
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 1019): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1019): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
,D/WifiStateMachine( 1019): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState enter
,D/WifiStateMachine( 1019): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiStateMachine( 1019): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1019): WiFi NOT Tethered!
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@42032348
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/WifiStateMachine( 1019): transitionTo: destState=ConnectedState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: CaptivePortalCheckState
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ConnectedState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
,D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1019): WiFi NOT Tethered!
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@42032348
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1283): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1283): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1283): onReceive() - done, currentInetCondition=0
,I/ModemStatsDSDetect( 1283): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1283): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1283): onReceive() - done, currentInetCondition=0
,D/WifiStateMachine( 1019): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
D/ConnectivityService( 1019): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1019):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/        ( 1019): Setting time of day to sec=1452596713
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,W/        ( 1019): Unable to set rtc to 1452596713: Invalid argument
,W/XTWiFiOS( 1266): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/PollingManager( 1542): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ActivityManager( 1019): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=3890 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/TelephonyProvider( 1242): Column apn id key is 'apn_id'
D/PollingManager( 1542): now: 336949 ,futureTime: 86438804
D/PollingManager( 1542): Polling alarm set to expire at: 86438804 Current Time: 336950
,W/XTWiFiOS( 1266): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1542): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1542): registerApp(): CCE
I/CCE     ( 1542): _configureNotificationMechanism(): successfully turned off push and starting polling at interval 1440
D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1542): Registering with Alarm Manager to restart CCE
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/MMApiWebService( 1542): Received data connectivity intent from PollingManager .. retry the waiting requests: 3
,D/CCE     ( 1542): trying to auto login since I haven't yet and the radio is up now
,D/MMApiProvisionService( 1542): isRequestAllowed(): already have outstanding request ... ignoring request
,D/OtaApp  ( 1542): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY,
,D/OtaApp  ( 1542): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1542): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/PollingManager( 1542): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/PollingManager( 1542): now: 337024 ,futureTime: 86438804
,D/PollingManager( 1542): Polling alarm set to expire at: 86438804 Current Time: 337025
,D/TelephonyProvider( 1242): Column apn id key is 'apn_id'
,D/OtaApp  ( 1542): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1542): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
,D/MMApiWebService( 1542): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1542): generating token using payload instead of using session token
,D/OtaApp  ( 1542): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1542): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/MMApiWebService( 1542): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,E/ActivityThread( 1542): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1542): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1542): isRequestAllowed(): already have outstanding request ... ignoring request
D/OtaApp  ( 1542): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1542): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1542): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1542): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1542): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1542): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1542): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1542): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1542): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/MMApiWSBase( 1542): doRequest(): url: https://api.svcmot.com:443/v1/dp/devices.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,I/MMApiWSBase( 1542): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager( 1019): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=3922 uid=10056 gids={50056, 3003, 1028, 1015}
,D/TelephonyProvider( 1242): Column apn id key is 'apn_id'
,W/dalvikvm( 1207): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1207): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1207): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1207): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1207): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1207): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1207): Using platform SSLCertificateSocketFactory
,D/ChimeraCfgMgr( 1373): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1373): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 1373): GC_CONCURRENT freed 1863K, 32% free 11824K/17224K, paused 4ms+6ms, total 67ms
,I/GamesSyncServiceMain( 1373): Found unexpected GCM tag when scheduling; aborting
,W/GamesSyncServiceMain( 1373): Failed to execute periodic sync, missing client context - aborting
,D/dalvikvm( 3890): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f3e1c0, skipping init
I/openssl ( 3890): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3890): Crypto mode 0 already enabled
,I/ActivityManager( 1019): Killing 3474:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/PhenotypeConfigurator( 1207): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,I/dalvikvm( 1373): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm( 1373): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1373): VFY: replacing opcode 0x6e at 0x003d
,I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=3952 uid=10030 gids={50030, 3003, 1028, 1015}
D/TelephonyProvider( 1242): Column apn id key is 'apn_id'
,E/ActivityThread( 1373): Failed to find provider info for com.android.contacts.metadata
D/GpsLocationProvider( 1019): NTP server returned: 1452596710825 (Tue Jan 12 12:05:10 CET 2016) reference: 334011 certainty: 14 system time offset: -3431
D/DelayedSyncController( 3922): Delaying sync.
E/LocSvc_ApiV02( 1019): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,V/MmsConfig( 3952): mnc/mcc: 
,V/MmsConfig( 3952): tag: bool value: enabledMMS - true
V/MmsConfig( 3952): tag: int value: maxMessageSize - 307200
V/MmsConfig( 3952): tag: int value: maxImageHeight - 1944
V/MmsConfig( 3952): tag: int value: maxImageWidth - 2592
V/MmsConfig( 3952): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 3952): tag: int value: defaultMMSMessagesPerThread - 50
E/Auth.Api.Credentials( 1373): [CredentialSyncAdapter] Unknown sync event.
,V/MmsConfig( 3952): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 3952): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 3952): tag: int value: recipientLimit - 20
V/MmsConfig( 3952): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 3952): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 3952): tag: bool value: enableSlideDuration - true
,V/MmsConfig( 3952): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 3952): tag: int value: maxSubjectLength - 80
V/MmsConfig( 3952): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 3952): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 3952): tag: bool value: enableGroupMms - false
,E/MmsConfig( 3952): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3975 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1019): Killing 3074:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/SyncManager( 1019): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 337522, reason: UserStart
,I/ActivityManager( 1019): Killing 3507:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 1207): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1207): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1207): VFY: replacing opcode 0x6e at 0x003d
,D/MobileConnectivityChangeReceiver( 3975): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 3975): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 3975): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3975): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/dalvikvm( 1242): GC_EXPLICIT freed 1459K, 45% free 9517K/17224K, paused 20ms+14ms, total 92ms
,I/CheckinService( 1373): Checkin interval check for package: unspecified last checkin: 1452528581633 min interval config: 0 actual interval: 68132790
I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3989 uid=10076 gids={50076, 3003, 1028, 1015}
I/ActivityManager( 1019): Killing 3090:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1373): Checking schedule, now: 1452596714445 next: 1452528611559
,I/CheckinService( 1373): active receiver: enabled
,I/CheckinService( 1373): Preparing to send checkin request
,I/EventLogService( 1373): Accumulating logs since 1452595947337
,V/WebViewChromiumFactoryProvider( 3989): Binding Chromium to main looper Looper (main, tid 1) {41f3b008}
,I/LibraryLoader( 3989): Expected native library version number "",actual native library version number ""
,I/chromium( 3989): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3989): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 3989): BLUETOOTH permission is missing!
,D/dalvikvm( 1019): GC_EXPLICIT freed 1735K, 65% free 17920K/50428K, paused 5ms+11ms, total 133ms
,I/Adreno-EGL( 3989): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3989): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3989): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3989): Local Branch: 
I/Adreno-EGL( 3989): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3989): Local Patches: NONE
I/Adreno-EGL( 3989): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/dalvikvm( 1019): Jit: resizing JitTable from 8192 to 16384
,D/dalvikvm( 1542): GC_CONCURRENT freed 2178K, 38% free 10812K/17224K, paused 4ms+6ms, total 57ms
,W/chromium( 3989): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,D/DelayedSyncController( 3922): Delaying sync.
,I/CheckinRequestBuilder( 1373): Checkin reason type: 8 attempt count: 1
,D/WifiService( 1019): New client listening to asynchronous messages
,E/ActivityThread( 1373): Failed to find provider info for com.google.android.wearable.settings
,W/GAV2    ( 3989): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3989): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NSApplication( 3989): Starting up...
,I/ImageResourceManager( 3110): ImageResourceManager: uninitalized
,I/iu.Environment( 3110): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.SyncManager( 3110): SYNC; picasa accounts
,I/ActivityManager( 1019): Killing 3534:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.UploadsManager( 3110): num queued entries: 0
,I/iu.UploadsManager( 3110): num updated entries: 0
,I/iu.SyncManager( 3110): NEXT; no task
,I/iu.SyncManager( 1373): SYNC; picasa accounts
,D/NetworkLogImpl( 1373): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1373): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1373): num queued entries: 0
,I/iu.UploadsManager( 1373): num updated entries: 0
,I/iu.SyncManager( 1373): NEXT; no task
,D/DEBUG   ( 1542): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1542): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1542): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1542): ServiceHandler.handleMessage: mWaitCount=1
I/openssl ( 3890): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3890): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 3975): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3975): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3110): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/dalvikvm( 3110): GC_CONCURRENT freed 615K, 5% free 16454K/17224K, paused 3ms+2ms, total 35ms
,I/ActivityManager( 1019): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=4055 uid=10007 gids={50007, 3003}
,D/MMApiProvisionService( 1542): ProvisionWS.Response: processing response data: {"sessionToken":"0-62d6271415ae24024c051b549cbffe5b3369896958","error":"OK","sessionExpiration":"22142","deviceId":"1135300315450105856"}
,D/MMApiWSBase( 1542): doRequest(): v1/ns/list/messages resp length: 1465
,D/ExtensionsFactory( 4055): No custom extensions.
D/MMApiProvisionService( 1542): ProvisionWS.Response: Completed parsing response.. no settings sent by server
,D/MMApiWSBase( 1542): doRequest(): /v1/dp/devices.json resp length: 137
,D/MMApiProvisionService( 1542): MMApiProvisionService.handleResponse (update_device) : true (None)
,D/CCE     ( 1542): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1542): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ActivityManager( 1019): Start proc com.android.deskclock for broadcast com.android.deskclock/.AlarmInitReceiver: pid=4072 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1019): Killing 3153:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/MMApiProvisionService( 1542): handleResponse(): Session Expiration alarm set to expire at: Tue Jan 12 18:14:17 CET 2016
D/MMApiProvisionService( 1542): _setMMApiCredInfo: storing credential info 
D/dalvikvm( 1348): GC_CONCURRENT freed 1939K, 39% free 10580K/17224K, paused 3ms+5ms, total 66ms
,I/ActivityManager( 1019): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4084 uid=10008 gids={50008, 3003, 1028, 1015}
,D/dalvikvm(  276): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 1ms+2ms, total 27ms
,D/dalvikvm( 1207): GC_CONCURRENT freed 1547K, 35% free 11341K/17224K, paused 4ms+14ms, total 62ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 19ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
I/ActivityManager( 1019): Killing 3739:com.android.settings/1000 (adj 15): empty #9
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiService( 1019): Client connection lost with reason: 4
I/GCM     ( 1348): GCM config loaded
,E/MMApiProvisionService( 1542): handleResponse(): no settings sent by the server:
,D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1542): MMApiWebService told us to retry waiting request since device is successfully provisioned: 0
,V/AlarmClock( 4072): AlarmInitReceiver android.intent.action.TIME_SET
,D/MMApiWebService( 1542): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/AlarmClock( 4072): Displaying next alarm time: ''
,V/AlarmClock( 4072): AlarmInitReceiver finished
,I/MMApiWSBase( 1542): doRequest(): url: https://api.svcmot.com:443/v1/us/devices/check.json/1135300315450105856?appId=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
I/ActivityManager( 1019): Killing 3890:android.process.media/u0a18 (adj 15): empty #9
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Checkin ( 1542): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1542): handleGetNotificationsResponse(): got 0; more=false
,I/ActivityManager( 1019): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4102 uid=10098 gids={50098}
,I/CalendarProvider2( 4084): Created com.android.providers.calendar.CalendarAlarmManager@41f56ec0(com.android.providers.calendar.CalendarProvider2@41f4ea78)
,D/dalvikvm( 4102): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x41f375f8, skipping init
D/TimeService( 4102): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1452596715521
D/        ( 4102): TimeServiceNative: User Time to be set is 1452596715521
D/QC-time-services( 4102): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4102): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4102): Lib:time_genoff_operation: pargs->ts_val = 1452596715521
,D/QC-time-services(  418): Daemon: Connection accepted:time_genoff
D/QC-time-services( 4102): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  418): Daemon:Received base = 2, unit = 1, operation = 0,value = 1452596715521
D/QC-time-services(  418): Daemon:genoff_opr: Base = 2, val = 1452596715521, operation = 0
D/QC-time-services(  418): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/12/116 10:59:14
D/QC-time-services(  418): Daemon:Value read from RTC seconds = 1452596354000
D/QC-time-services(  418): Daemon:new time 1452596715521 
D/QC-time-services(  418): Daemon: delta 361521 genoff 361521 
D/QC-time-services(  418): Daemon:genoff_persistent_update: Writing genoff = 361521 to memory
D/QC-time-services(  418): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  418): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  418): Updating the TOD offset
D/QC-time-services(  418): Daemon:genoff_persistent_update: Writing genoff = 361521 to memory
D/QC-time-services(  418): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  418): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  418): Daemon:Update to modem bit set
D/QC-time-services(  418): Daemon:genoff_send_modem: Sending data to MODEM !
E/QC-time-services( 4102): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  418): Daemon: Base = 2, Value being sent to MODEM = 18446743757745113137
E/QC-time-services(  418): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  418): Daemon: Time-services: Waiting to acceptconnection
,I/CheckinService( 1373): Checkin interval check for package: unspecified last checkin: 1452528581633 min interval config: 0 actual interval: 68133903
,D/DEBUG   ( 1542): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1542): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1542): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1542): ServiceHandler.handleMessage: mWaitCount=1
,W/PhenotypeConfigurator( 1207): Server returned 404
,D/OtaApp  ( 1542): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1542): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1542
,I/OtaApp  ( 1542): [info] > Updatetime from metadata: 10
,D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1542): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1542): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1542): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1542): [info] > Updatetime from metadata: 10
,D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1542): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1542): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1542): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
I/dalvikvm( 1373): Could not find method android.content.Context.getNoBackupFilesDir, referenced from method com.google.android.gms.iid.n.<init>
W/dalvikvm( 1373): VFY: unable to resolve virtual method 378: Landroid/content/Context;.getNoBackupFilesDir ()Ljava/io/File;
,D/dalvikvm( 1373): VFY: replacing opcode 0x6e at 0x002c
,D/OtaApp  ( 1542): [debug] > UpdateReceiver: Received True from doSanityCheck.
,I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1542
I/dalvikvm( 1373): Could not find method android.content.Context.getDrawable, referenced from method android.support.v4.content.g.a
W/dalvikvm( 1373): VFY: unable to resolve virtual method 287: Landroid/content/Context;.getDrawable (I)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 1373): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1373): Could not find method android.content.Context.getColor, referenced from method android.support.v4.content.g.b
W/dalvikvm( 1373): VFY: unable to resolve virtual method 283: Landroid/content/Context;.getColor (I)I
,D/dalvikvm( 1373): VFY: replacing opcode 0x6e at 0x0006
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1542): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1542): [info] > Updatetime from metadata: 10
,D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1542): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1542): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1542): [info] > Updatetime from metadata: 10
,D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
I/LaunchCheckinHandler( 1019): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,139
,D/OtaApp  ( 1542): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1542): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1542): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/ActivityManager( 1019): Activity reported stop, but no longer stopping: ActivityRecord{4207dcc8 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
D/OtaApp  ( 1542): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/DEBUG   ( 1542): Received intent : com.motorola.notification.RETREIVE_NOTIFICATIONS
I/SundryService( 1542): onHandleIntent(): action=com.motorola.notification.RETREIVE_NOTIFICATIONS
I/SundryService( 1542): Received shoulder tap
,D/DEBUG   ( 1542): Received intent : com.motorola.ccc.notification.action.NOTIFY
,D/GCM     ( 1348): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,D/WaitableIntentService( 1542): setWaitEnabled(): mWaitCount=2 isWaitEnabled=true
,D/GetNotificationsWS( 1542): GetNotificationsWS.Request: message={"request":{"appendDeviceId":true,"baseUrl":"v1\/ns\/list\/messages","queryParams":{"appid":"MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ"},"httpMethod":"post","requestFormat":"json","wsReqId":"com.motorola.ccc.notification.GetNotificationsWS.Request","isSecure":true,"payload":{"data":"{\"appidNotifStoreMessageidPageSizeList\":[{\"appid\":\"LX6TJJI6F2MILF1NPZW6A3HBAKK8W44Z\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SULIGJDMXLSL7T1DOVYSTVG2KCBHZ5GH\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"6U5KK17SNFB416J4SYG7LC6HYFNOPYM8\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"68OUD4VKG23F7BUH6M2QBRXPLIC7IMCO\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SZZTNOGZA6O6PRFZH2V3FF14N1J8W3HC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"D9DF2F5BB1FA45B0BA459B7FE6942DCD\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"RCEAZODHQBX3UTIE62BUQ6T6TXXI6JSR\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"L71KGK4CCWOW658MGESIRYO2428ODW11\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"OCVKVSQ5Q1EYVBX76813UOPTCKGAH4VS\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"B642GFV24HEMEDQNCF3ZED8BIUMPCBOM\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"5LWTCLJBZO4OUDU5BY7ANJI4Y2MHY8OY\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"TESULHNZGDWZ5T3EMNZRTVE51RR7EUXC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"QZYSBKU4MGE71O1PLTE8HAT11SWL5M6E\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"XX274VEJBOVSSPHDKHSPURVRQ1YT5VEM\",\"pageSize\":100,\"notifStoreMessageid\":0}]}","type":"json"},"retries":"-1","useOAuth":true}}
,D/GetNotificationsWS( 1542): sendAidlRequest(): was sent by CCE successfully!
D/WaitableIntentService( 1542): ServiceHandler.handleMessage: mWaitCount=2
I/SundryService( 1542): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1542): setWaitEnabled(): mWaitCount=1 isWaitEnabled=false
D/SundryService( 1542): onHandleIntent(): isWaitEnabled=true
,D/WaitableIntentService( 1542): ServiceHandler.handleMessage: mWaitCount=1
,D/MMApiWebService( 1542): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,I/MMApiWSBase( 1542): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager( 1019): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4124 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4124): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4124): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4124): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
,W/dalvikvm( 4124): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4124): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 4124): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4124): install
,I/MultiDex( 4124): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4124): loading existing secondary dex files
,I/MultiDex( 4124): load found 3 secondary dex files
,I/MultiDex( 4124): install done
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1283): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1283): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1283): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1283): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1081): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/dalvikvm( 4124): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4124): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4124): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4124): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4124): VFY: unable to resolve instance field 36
,D/dalvikvm( 4124): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4124): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4124): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4124): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4124): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4124): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4124): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f38b38
D/dalvikvm( 4124): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f38b38
,D/dalvikvm( 4124): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f38b38, skipping init
,D/dalvikvm( 4124): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f38b38
D/dalvikvm( 4124): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f38b38
,V/JNIHelp ( 4124): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4124): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f38b38
,D/dalvikvm( 4124): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f38b38
D/dalvikvm( 4124): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f38b38
,D/dalvikvm( 4124): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f38b38
,I/ProviderInstaller( 4124): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1207): callingUid 10022, callindPid: 1207
,D/LocationInitializer( 1373): Restart initialization of location
I/dalvikvm( 4124): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4124): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4124): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4124): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4124): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4124): VFY: replacing opcode 0x6e at 0x000d
,D/AuthorizationBluetoothService( 1348): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1348): Proximity feature is not enabled.
,E/MDM     ( 1207): [123] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 4124): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4124): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4124): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4124): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4124): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4124): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4124): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4124): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 4124): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4124): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4124): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/dalvikvm( 1019): GC_EXPLICIT freed 916K, 65% free 17931K/50428K, paused 4ms+11ms, total 104ms
,W/GCoreFlp( 1207): No location to return for getLastLocation()
,W/FusedLocationProvider( 1207): location=null
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
,E/QSEECOMAPI: (  278): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  278): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  278): App is not loaded in QSEE
,D/MMApiWSBase( 1542): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1542): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1542): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/dalvikvm( 4124): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 4124): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 4124): VFY: replacing opcode 0x6e at 0x003d
,W/dalvikvm( 4124): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4124): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/QSEECOMAPI: (  278): Loaded image: APP id = 3
,W/dalvikvm( 4124): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/NativeLibraryUtils( 4124): Install completed successfully. count=14 extracted=0
D/DrmWidevineDash(  278): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb51a9000
,E/DrmWidevineDash(  278): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb51a9000
I/dalvikvm( 4124): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 4124): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 4124): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 4124): Using platform SSLCertificateSocketFactory
D/DrmWidevineDash(  278): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  278): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  278): calling OEMCrypto_IsKeyboxValid...
,D/Checkin ( 1542): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1542): handleGetNotificationsResponse(): got 0; more=false
,D/DEBUG   ( 1542): Received intent : com.motorola.ccc.notification.action.NOTIFY
I/SundryService( 1542): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1542): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1542): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1542): ServiceHandler.handleMessage: mWaitCount=0
D/DrmWidevineDash(  278): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  278): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/GetNotificationsWS( 1542): unbindWebServices(): un-registering our AIDL callback...
I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  278): OEMCrypto_GetRandom returns 0
I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,I/PhenotypeConfigurator( 1207): Scheduling Phenotype for one-off execution 84 seconds from now (1452596716434)
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,D/GetConfigurationSnapshotOperation( 1207): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=833463155
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/PhenotypeFlagCommitter( 1207): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1207): Using platform SSLCertificateSocketFactory
,I/CalendarProvider2( 4084): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 4084): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 4055): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 4055): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  278): CdmEngine::CloseSession
D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 1207): GC_CONCURRENT freed 1554K, 32% free 11728K/17224K, paused 4ms+9ms, total 37ms
,D/dalvikvm( 4124): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x422facc8
,D/dalvikvm( 4124): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x422facc8
,D/dalvikvm( 4124): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x422facc8, skipping init
,D/dalvikvm( 4124): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4164): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4124): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4124): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 79ms
,I/Adreno-EGL( 4124): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4124): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4124): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4124): Local Branch: 
I/Adreno-EGL( 4124): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4124): Local Patches: NONE
I/Adreno-EGL( 4124): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4124): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4124): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4124): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4124): Local Branch: 
I/Adreno-EGL( 4124): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4124): Local Patches: NONE
I/Adreno-EGL( 4124): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 4124): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 1348): null clazz in OP_INSTANCE_OF, single-stepping
,I/Adreno-EGL( 4124): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4124): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4124): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4124): Local Branch: 
I/Adreno-EGL( 4124): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4124): Local Patches: NONE
I/Adreno-EGL( 4124): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4124): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4124): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4124): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4124): Local Branch: 
I/Adreno-EGL( 4124): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4124): Local Patches: NONE
I/Adreno-EGL( 4124): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/MMApiWSBase( 1542): doRequest(): v1/us/devices/check resp length: 188
,D/CCE     ( 1542): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
,D/CCE     ( 1542): AppWSProxy - sendWSResponse(): sending response to com.motorola.ccc.ota.webservice.response.182339526 for reqID:  error: None
,D/OtaWebService( 1542): [debug] > WebService.checkAndInvokeRetryHandler(): invoking retry handler: com.motorola.ccc.ota.webservice.InternalRetryHandler@426d2ec8 with response com.motorola.ccc.ota.webservice.dataobjects.WebResponse@423ff6b8
,D/OtaWebService( 1542): [debug] > InternalRetryHandler:onTransact() response string from WebService{"response":{"error":"None","statusCode":200,"payload":"{\"metaDataVersion\":\"1410862052\",\"pollAfterSeconds\":86400,\"status\":\"OTA_OK\",\"status_description\":\"{\\\"code\\\":\\\"OTA_OK\\\",\\\"description\\\":\\\"No upgrade found for this device at this time.\\\"}\"}\n","errorText":""}}
,D/OtaWebService( 1542): [debug] > WebService.checkAndInvokeResponseHandler(): invoking response handler: com.motorola.ccc.ota.webservice.InternalResponseHandler@426d4568 with response com.motorola.ccc.ota.webservice.dataobjects.WebResponse@423ff6b8
,D/OtaWebService( 1542): [debug] > InternalResponseHandler:onTransact() response string from WebService{"response":{"error":"None","statusCode":200,"payload":"{\"metaDataVersion\":\"1410862052\",\"pollAfterSeconds\":86400,\"status\":\"OTA_OK\",\"status_description\":\"{\\\"code\\\":\\\"OTA_OK\\\",\\\"description\\\":\\\"No upgrade found for this device at this time.\\\"}\"}\n","errorText":""}}
,I/OtaApp  ( 1542): [info] > OTAUpgradeSource.handleMMApiCheckForUpdateResponse: check_for_update : 200 :  
,D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1542): [info] > OTAUpgradeSource.handleMMApiCheckForUpdateResponse: no upgrades found for this device at this time
,D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1542): [debug] > CusAndroidPollingManager.handleIntent: com.motorola.blur.service.blur.upgrade_poll
,I/OtaApp  ( 1542): [info] > Next Polling is scheduled at 1439 mins from now
,D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
,D/PollingManager( 1542): registerApp(): cUsPollingService
,D/OtaApp  ( 1542): [debug] > BotaFotaResolver.parse got the following check order (bota); assuming only bota is enabled
,D/OtaApp  ( 1542): [debug] > OTAUpgradeSource.handleMMApiCheckForUpdateResponse: authoritative response from BOTA ERR_NOTFOUND
,D/OtaApp  ( 1542): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1542): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1542): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1542): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1542): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1542): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1542): [debug] > UpdateReceiver: Received True from doSanityCheck.
,I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1542
,D/OtaApp  ( 1542): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1542): [info] > Updatetime from metadata: 10
D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
D/OtaWebService( 1542): [debug] > appending web service response to serviceHandler
D/OtaWebService( 1542): [debug] > Removing request :v1/us/devices/check from queue
D/OtaWebService( 1542): [debug] > No pending web request. shutdown webservice
D/OtaApp  ( 1542): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1542): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
I/OtaApp  ( 1542): [info] > Updatetime from metadata: 10
D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1542): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1542): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1542): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/OtaWebService( 1542): [info] > Stopping webservice android service
D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1542): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  278): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=3105100106
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,I/jxcore-log( 3657): Test app app.js loaded
I/jxcore-log( 3657): 
,W/IInputConnectionWrapper( 3657): showStatusIcon on inactive InputConnection
,I/chromium( 3657): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3657): --= Surplus to requirements =--
I/jxcore-log( 3657): 
,I/jxcore-log( 3657): ****TEST TOOK:  ms ****
I/jxcore-log( 3657): 
,I/jxcore-log( 3657): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3657): 
,I/CheckinRequestBuilder( 1373): Classify the device as Phone.
,D/dalvikvm( 1373): GC_CONCURRENT freed 1732K, 30% free 12089K/17224K, paused 4ms+8ms, total 47ms
,I/CheckinTask( 1373): Sending checkin request (12189 bytes)
,D/AndroidRuntime( 4182): 
D/AndroidRuntime( 4182): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4182): CheckJNI is OFF
,D/dalvikvm( 4182): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4182): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4182): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4182): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4182): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4182): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,E/memtrack( 4182): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4182): failed to load memtrack module: -2
,D/AndroidRuntime( 4182): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10544 user=-1: uninstall pkg
,I/ActivityManager( 1019): Killing 3657:com.test.thalitest/u0a544 (adj 9): stop com.test.thalitest
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019):   Force finishing activity ActivityRecord{446bef88 u0 com.test.thalitest/.MainActivity t3}
,I/WindowState( 1019): WIN DEATH: Window{44680810 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1019): Client connection lost with reason: 4
,I/dalvikvm( 1019): Total arena pages for JIT: 15
,W/PackageSettings( 1019): Skipping PackageSetting{421fab90 com.example.hello/10543} due to missing metadata
,I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10544 user=0: pkg removed
,I/CheckinResponseProcessor( 1373): From server: 4 gservices updates and 0 deletes
,D/dalvikvm( 2123): GC_EXPLICIT freed 6020K, 44% free 9744K/17224K, paused 2ms+6ms, total 39ms
,D/dalvikvm( 3110): GC_FOR_ALLOC freed 39K, 5% free 16415K/17224K, paused 30ms, total 30ms
,I/dalvikvm-heap( 3110): Grow heap (frag case) to 19.799MB for 1821008-byte allocation
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1207): Ignoring removeGeofence because network location is disabled.
I/ActivityManager( 1019): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4202 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/LatinIME:LogUtils( 1188): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/LatinIME:LogUtils( 1188): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
D/dalvikvm( 2158): GC_EXPLICIT freed 3479K, 42% free 10110K/17224K, paused 2ms+4ms, total 119ms
,I/LatinIME:LogUtils( 1188): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452596719
,D/dalvikvm( 1297): GC_EXPLICIT freed 2792K, 33% free 11591K/17224K, paused 15ms+4ms, total 137ms
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
I/Launcher( 1297): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,D/dalvikvm( 1019): GC_EXPLICIT freed 1061K, 65% free 17926K/50428K, paused 21ms+12ms, total 151ms
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/LatinIME:LogUtils( 1188): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452596719
,I/Launcher( 1297): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,D/AndroidRuntime( 4182): Shutting down VM
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
D/dalvikvm( 4182): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
,D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10544 #1
,D/VoicemailCleanupService( 4202): Cleaning up data for package: com.test.thalitest
,I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4228 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3952:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,E/UlpEngine( 1019): kvs.containsKey(ENH_LOCATION_SERVICES_ENABLED) returned false
,W/XTWiFiOS( 1266): No entry in secure settings for enhanced location services: false
,I/InternalIcingCorporaPro( 2158): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager( 1019): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4246 uid=10059 gids={50059, 3003, 1028, 1015}
,E/UlpEngine( 1019): kvs.containsKey(ENH_LOCATION_SERVICES_ENABLED) returned false
,I/ActivityManager( 1019): Killing 3975:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/XTWiFiOS( 1266): No entry in secure settings for enhanced location services: false
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/CertBlacklister( 1019): Certificate blacklist changed, updating...
I/CertBlacklister( 1019): Certificate blacklist updated
,I/ContactLocale( 4202): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/GservicesProvider( 1348): main difference update completed
,I/CheckinRequestBuilder( 1373): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1373): Failed to find provider info for com.google.android.wearable.settings
,I/InternalIcingCorporaPro( 2158): UpdateCorporaTask done [took 87 ms] updated apps [took 87 ms] 
,I/GAV2    ( 3989): Thread[GAThread,5,main]: No campaign data found.
,E/SQLiteLog( 4202): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/dalvikvm( 4202): threadid=10: thread exiting with uncaught exception (group=0x41668d40)
,I/CheckinRequestBuilder( 1373): Classify the device as Phone.
E/AndroidRuntime( 4202): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 4202): Process: android.process.acore, PID: 4202
E/AndroidRuntime( 4202): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4202): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4202): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 4202): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4202): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4202): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 4202): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 4202): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:381)
E/AndroidRuntime( 4202): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:350)
E/AndroidRuntime( 4202): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1653)
E/AndroidRuntime( 4202): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1470)
E/AndroidRuntime( 4202): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4202): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4202): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 4202): Sending signal. PID: 4202 SIG: 9
E/DropBoxManagerService( 1019): Can't write: system_app_crash
E/DropBoxManagerService( 1019): java.io.FileNotFoundException: /data/system/dropbox/drop93.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager( 1019): Process android.process.acore (pid 4202) has died.
I/CheckinTask( 1373): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
E/SharedPreferencesImpl( 1373): Couldn't rename file /data/data/com.google.android.gsf/shared_prefs/CheckinService.xml to backup file /data/data/com.google.android.gsf/shared_prefs/CheckinService.xml.bak
E/SharedPreferencesImpl( 1373): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/Checkin.xml to backup file /data/data/com.google.android.gms/shared_prefs/Checkin.xml.bak
E/SharedPreferencesImpl( 1373): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/Checkin.xml to backup file /data/data/com.google.android.gms/shared_prefs/Checkin.xml.bak
I/CheckinService( 1373): Checking schedule, now: 1452596719856 next: 1453189789849
I/CheckinService( 1373): active receiver: disabled
F/PackageManager( 1019): Unable to backup user packages state file, current changes will be lost at reboot
,E/DropBoxManagerService( 1019): Can't write: system_server_wtf
E/DropBoxManagerService( 1019): java.io.FileNotFoundException: /data/system/dropbox/drop64.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1019): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1019): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10230)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10135)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10022)
E/DropBoxManagerService( 1019): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService( 1019): 	at android.util.Log$1.onTerribleFailure(Log.java:111)
E/DropBoxManagerService( 1019): 	at android.util.Log.wtf(Log.java:477)
E/DropBoxManagerService( 1019): 	at android.util.Log.wtf(Log.java:440)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1046)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.PackageManagerService.setEnabledSetting(PackageManagerService.java:10418)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.PackageManagerService.setComponentEnabledSetting(PackageManagerService.java:10326)
E/DropBoxManagerService( 1019): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1036)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1538)
E/DropBoxManagerService( 1019): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 1019): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 1019): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1019): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1019): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1019): 	... 19 more
D/CheckinService( 1373): Recording last checkin time for package unspecified as 1452596719870
E/SharedPreferencesImpl( 1373): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/Checkin.xml to backup file /data/data/com.google.android.gms/shared_prefs/Checkin.xml.bak

```
