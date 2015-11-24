#### Test 50388019b17f598_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1015): sending alarm Alarm{42806158 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 3937): 
D/AndroidRuntime( 3937): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3937): CheckJNI is OFF
D/dalvikvm( 3937): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3937): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3937): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3937): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3937): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3937): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3937): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3937): failed to load memtrack module: -2
D/AndroidRuntime( 3937): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1015): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3937
W/WindowManager( 1015): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1015): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3953 uid=10407 gids={50407, 3003, 3001, 3002}
D/AndroidRuntime( 3937): Shutting down VM
D/dalvikvm( 3937): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+0ms, total 3ms
W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3953): Binding Chromium to main looper Looper (main, tid 1) {41fa8a50}
I/LibraryLoader( 3953): Expected native library version number "",actual native library version number ""
I/chromium( 3953): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3953): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1015): Message: 20
D/BluetoothManagerService( 1015): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@428963a0:true
I/Adreno-EGL( 3953): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3953): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3953): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3953): Local Branch: 
I/Adreno-EGL( 3953): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3953): Local Patches: NONE
I/Adreno-EGL( 3953): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3953): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3953): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3953): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3953): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3953): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3953): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3953): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3953): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3953): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3953): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3953): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3953): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3953): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3953): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3953): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3953): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3953): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3953): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3953): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3953): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3953): Enabling debug mode 0
,W/AwContents( 3953): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3953): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1015): Displayed com.example.hello/.MainActivity,cp,ca,355
I/ActivityManager( 1015): Displayed com.example.hello/.MainActivity: +330ms (total +356ms)
,I/chromium( 3953): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 3953): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 3953): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3953): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41fad1f0
,D/dalvikvm( 3953): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41fad1f0
D/jxcore_app_log( 3953): JniHelper::setJavaVM(0x415fbfa8), pthread_self() = 1610572232
,D/JX-Cordova( 3953): jxcore cordova android initializing
,W/jxcore-log( 3953): Initializing JXcore engine
,W/jxcore-log( 3953): JXcore engine is ready
,W/jxcore-log( 3953): Starting JXcore engine
,W/jxcore-log( 3953): Platform android
W/jxcore-log( 3953): 
,W/jxcore-log( 3953): Process ARCH arm
W/jxcore-log( 3953): 
,I/jxcore-log( 3953): JXcore Cordova bridge is ready!
I/jxcore-log( 3953): 
,W/jxcore-log( 3953): JXcore engine is started
,E/jxcore-log( 3953): >> motorola-XT1039
E/jxcore-log( 3953): 
,I/jxcore-log( 3953): Total memory 893136896
I/jxcore-log( 3953): 
I/jxcore-log( 3953): Free memory 38825984
I/jxcore-log( 3953): 
,I/jxcore-log( 3953): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3953): 
,I/jxcore-log( 3953): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3953): 
,I/jxcore-log( 3953): userPath [ 'www' ]
I/jxcore-log( 3953): 
,I/jxcore-log( 3953): Size 720 1184
I/jxcore-log( 3953): 
,I/jxcore-log( 3953): Screen Brightness 10
I/jxcore-log( 3953): 
,E/jxcore-log( 3953): Dummy Error Log.
E/jxcore-log( 3953): 
,I/jxcore-log( 3953): getBuffer is called!!!!
I/jxcore-log( 3953): 
,D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1015): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@4279d970 mBinding = false
,W/Settings( 1292): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/XTWiFiOS( 1300): No entry in secure settings for enhanced location services: false
W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1292): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/BluetoothManagerService( 1015): Message: 2
D/BluetoothManagerService( 1015): Sending off request.
D/BluetoothAdapterState( 1790): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1790): Setting state to 13
I/BluetoothAdapterState( 1790): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 1790): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterProperties( 1790): onBluetoothDisable()
I/BluetoothAdapterState( 1790): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/BluetoothAdapterProperties( 1790): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 1790): Scan Mode:21
D/BluetoothAdapterState( 1790): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/BluetoothManagerService( 1015): Message: 60
E/bt-btif ( 1790): bta_jv_rfcomm_stop_server
E/BtOppRfcommListener( 1790): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 1790): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/BluetoothManagerService( 1015): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1015): Bluetooth State Change Intent: 12 -> 13
E/bt-btif ( 1790): bta_jv_rfcomm_stop_server
E/bt-btif ( 1790): bta_jv_rfcomm_stop_server
E/bt-btif ( 1790): bta_jv_rfcomm_stop_server
D/btif_config_util( 1790): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
W/bt-btif ( 1790): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 1790): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1790): L2CAP - PSM: 0x0017 not found for deregistration
D/BluetoothMapService( 1790): onReceive
D/BluetoothMapService( 1790): STATE_TURNING_OFF removeTimeoutMsg:false
D/BluetoothMapService( 1790): MAP Service closeService in
,I/ActivityManager( 1015): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=4008 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,D/WifiService( 1015): New client listening to asynchronous messages
,D/WifiService( 1015): setWifiEnabled: false pid=3953, uid=10407
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
,I/BtOppRfcommListener( 1790): stopping Accept Thread
,I/BtOppRfcommListener( 1790): BluetoothSocket listen thread finished
,W/Settings( 1292): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/jxcore-log( 3953): ****TEST TOOK:  5171  ms ****
I/jxcore-log( 3953): 
D/WifiStateMachine( 1015): handleMessage: E msg.what=131084
,D/WifiStateMachine( 1015): processMsg: ConnectedState
,D/WifiStateMachine( 1015): processMsg: L2ConnectedState
,D/WifiStateMachine( 1015): processMsg: ConnectModeState
,I/jxcore-log( 3953): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3953): 
,D/WifiStateMachine( 1015): processMsg: DriverStartedState
D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
D/WifiStateMachine( 1015): transitionTo: destState=WaitForP2pDisableState
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
W/XTWiFiOS( 1300): No entry in secure settings for enhanced location services: false
W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1292): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
D/WifiStateMachine( 1015): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1015): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1015): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1015): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1015): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  271): Clearing all IP addresses on wlan0
D/TCMD    (  581): NL - Read 60 bytes from update socket.
D/TCMD    (  581): NL - ignore NL message, type = 21
,D/TCMD    (  581): Listening for incoming client connection request
,D/WifiStateMachine( 1015): addressRemoved: 192.168.1.123/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1015): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1015): connected time updated 92476
,D/WifiStateMachine( 1015): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/ConnectivityService( 1015): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1015): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1078): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1078): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1015): invokeExitMethods: ConnectModeState
,D/WifiStateMachine( 1015): invokeExitMethods: DriverStartedState
D/ConnectivityService( 1015): Attempting to switch to mobile
D/ConnectivityService( 1015): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1015): Attempting to switch to ETHERNET
D/Checkin ( 1015): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.NetworkController( 1078): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,E/WifiStateMachine( 1015): Unexpected BatchedScanResults :OK
W/ContextImpl( 4008): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=2
,D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
D/WifiStateMachine( 1015): invokeEnterMethods: WaitForP2pDisableState
D/WifiStateMachine( 1015): handleMessage: X
,D/WifiP2pService( 1015): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1015): handleMessage: E msg.what=131216
D/WifiStateMachine( 1015): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
D/WifiP2pService( 1015): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiP2pService( 1015): P2pDisablingState
D/WifiP2pService( 1015): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): p2p socket connection lost
,D/WifiP2pService( 1015): P2pDisabledState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131216
D/WifiStateMachine( 1015): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
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
,D/WifiStateMachine( 1015): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1015): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): DefaultState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 1015): resetConnections(wlan0, 3)
D/NetUtils( 1015): android_net_utils_resetConnections in env=0x611f4528 clazz=0x63500001 iface=wlan0 mask=0x3
D/BluetoothPbapService( 1790): action: android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothManagerService( 1015): Message: 20
,D/BluetoothManagerService( 1015): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@428ac790:true
,V/NativeCrypto( 1353): Read error: ssl=0x5c00ca00: I/O error during system call, Connection timed out
,D/BluetoothManagerService( 1015): Message: 30
,W/ContextImpl( 4008): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
D/BluetoothManagerService( 1015): Message: 30
V/NativeCrypto( 1353): SSL shutdown failed: ssl=0x5c00ca00: I/O error during system call, Broken pipe
,D/CommandListener(  271): Clearing all IP addresses on wlan0
,W/ContextImpl( 4008): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/WifiStateMachine( 1015): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1015): stopping supplicant
D/Checkin ( 1015): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1015): setWifiState: disabling
I/SBar.NetworkController( 1078): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1078): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1300): No entry in secure settings for enhanced location services: false
D/WifiStateMachine( 1015): handleMessage: X
W/XTWiFiOS( 1300): Active network info is not available
I/SBar.NetworkController( 1078): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1078): updateTelephonySignalStrength:  No service
E/XTCC-3.0.0.2(  585): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  585): [WwanPosMgr] handleConnectivtyStatusChange failed
D/LocalBluetoothProfileManager( 4008): Adding local MAP profile
W/bt-btif ( 1790): ag scb idx 1 not allocated
E/bt-btif ( 1790): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1790): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1790): L2CAP - PSM: 0x0017 not found for deregistration
I/bt_hwcfg( 1790): hw_epilog_process
W/bt-l2cap( 1790): L2CAP - PSM: 0x0019 not found for deregistration
D/BluetoothMap( 4008): Create BluetoothMap proxy object
W/bt-l2cap( 1790): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1790): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1790): L2CAP - PSM: 0x0017 not found for deregistration
D/BluetoothManagerService( 1015): Message: 30
,I/SBar.NetworkController( 1078): refreshSignalCluster: wifi: mWifiConnected=false Wifi=(none) Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,W/ContextImpl( 4008): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/BluetoothManagerService( 1015): Message: 30
,W/ContextImpl( 4008): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 4008): LocalBluetoothProfileManager construction complete
,D/Nat464Xlat( 1015): requiresClat: netType=1, hasIPv4Address=false
E/XTCC-3.0.0.2(  585): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  585): [CSMgr] handleConnectivtyStatusChange failed
,D/DockEventReceiver( 4008): finishStartingService: stopping service
D/ConnectivityService( 1015): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1015): Attempting to switch to mobile
D/ConnectivityService( 1015): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1015): Attempting to switch to ETHERNET
I/ModemStatsDSDetect( 1196): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1196): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1196): onReceive() - done, currentInetCondition=0
I/bt_hwcfg( 1790): hw_epilog_cback Opcode:0x0C03 Status: 0
I/bt_hci_bdroid( 1790): bt_hc_worker_thread exiting
D/bt_userial_mct( 1790): userial_close
I/bt_userial_mct( 1790): exiting userial_read_thread
,D/bt_userial_mct( 1790): Leaving userial_evt_read_thread()
D/Nat464Xlat( 1015): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1015): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1196): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1196): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1196): onReceive() - done, currentInetCondition=0
,D/WifiService( 1015): New client listening to asynchronous messages
,D/Tethering( 1015): InitialState.processMessage what=4
I/wpa_supplicant( 1148): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  274): reply_len: 92 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  274): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  274):  STA Disconnected !!
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=0
,D/Tethering( 1015): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/MDMCTBK (  274): reply_len: 87 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine( 1015): handleMessage: E msg.what=147460
D/WifiStateMachine( 1015): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
D/WifiStateMachine( 1015): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
D/TCMD    (  581): NL - Read 1000 bytes from update socket.
D/TCMD    (  581): NL - message type is RTM_NEWLINK
D/TCMD    (  581): Listening for incoming client connection request
D/TCMD    (  581): NL - Read 68 bytes from update socket.
D/TCMD    (  581): NL - message type is RTM_NEWLINK
D/TCMD    (  581): Listening for incoming client connection request
D/TCMD    (  581): NL - Read 68 bytes from update socket.
D/TCMD    (  581): NL - message type is RTM_NEWLINK
,D/TCMD    (  581): Listening for incoming client connection request
D/BluetoothInputDevice( 4008): Proxy object connected
,D/HidProfile( 4008): Bluetooth service connected
,D/Tethering( 1015): sendTetherStateChangedBroadcast 0, 0, 0
,V/BluetoothFtpReceiver( 1790): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
D/WifiStateMachine( 1015): handleMessage: E msg.what=131101
D/WifiStateMachine( 1015): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1015): processMsg: DefaultState
,D/WifiStateMachine( 1015): handleMessage: X
,D/BluetoothPan( 4008): BluetoothPAN Proxy object connected
D/PanProfile( 4008): Bluetooth service connected
,D/BluetoothMap( 4008): Proxy object connected
D/MapProfile( 4008): Bluetooth service connected
,D/BluetoothMap( 4008): getConnectedDevices()
D/BluetoothMap( 4008): Bluetooth is Not enabled
,D/AuthorizationBluetoothService( 1353): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager( 1015): Killing 3695:com.android.calendar/u0a7 (adj 15): empty #9
W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/wpa_supplicant( 1148): eap_proxy Deinitialzed
D/MDMCTBK (  274): reply_len: 58 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:48
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:48
D/MDMCTBK (  274): reply_len: 58 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1 38:f8:89:11:e9:11
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 1 38:f8:89:11:e9:11
D/MDMCTBK (  274): reply_len: 58 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2 06:7c:34:12:7f:81
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 2 06:7c:34:12:7f:81
D/MDMCTBK (  274): reply_len: 58 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3 64:7c:34:12:7f:81
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 3 64:7c:34:12:7f:81
D/MDMCTBK (  274): reply_len: 58 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4 fc:94:e3:11:35:3a
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 4 fc:94:e3:11:35:3a
,D/WifiStateMachine( 1015): handleMessage: E msg.what=196614
D/WifiStateMachine( 1015): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1015): processMsg: DefaultState
,D/WifiStateMachine( 1015): handleMessage: X
,D/TCMD    (  581): NL - Read 1000 bytes from update socket.
D/TCMD    (  581): NL - message type is RTM_NEWLINK
,D/TCMD    (  581): Listening for incoming client connection request
I/wpa_supplicant( 1148): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  274): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  274):  Wpa Supplicant Exiting !!
D/MDMCTBK (  274): wifi_wait_on_socket: Exiting monitor thread
,D/MDMCTBK (  274): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  274): wifi_close_sockets: Exit
D/WifiStateMachine( 1015): handleMessage: E msg.what=147458
D/WifiStateMachine( 1015): processMsg: SupplicantStoppingState
,D/WifiStateMachine( 1015): Supplicant connection lost
,D/AndroidRuntime( 4040): 
D/AndroidRuntime( 4040): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4040): CheckJNI is OFF
,D/dalvikvm( 4040): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4040): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 4040): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4040): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4040): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/BTSNOOP-DISP( 1790): btsnoop_close
I/bt_vendor( 1790): cleanup
I/bt_hwcfg( 1790): Starting hciattach daemon
,I/bt_hwcfg( 1790): try to set false
I/GKI_LINUX( 1790): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 1790): GKI_exit_task: GKI_exit_task 0 done
,I/GKI_LINUX( 1790): GKI_destroy_task: GKI_shutdown(): task [BTU] terminated
,D/WifiStateMachine( 1015): setWifiState: disabled
,I/SBar.NetworkController( 1078): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1300): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1300): Active network info is not available
I/SBar.NetworkController( 1078): updateTelephonySignalStrength:  No service
E/XTCC-3.0.0.2(  585): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  585): [WwanPosMgr] handleConnectivtyStatusChange failed
,D/dalvikvm( 4040): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/XTCC-3.0.0.2(  585): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  585): [CSMgr] handleConnectivtyStatusChange failed
D/WifiStateMachine( 1015): transitionTo: destState=InitialState
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1015): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
,D/WifiStateMachine( 1015): invokeEnterMethods: InitialState
,D/BluetoothAdapterState( 1790): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 1790): Received stop request...Stopping profile...
,D/BluetoothHeadset( 1015): Proxy object disconnected
D/BluetoothHeadset( 1272): Proxy object disconnected
D/BluetoothHeadset( 1272): Proxy object disconnected
,D/BluetoothHeadset( 1272): Proxy object disconnected
,D/BluetoothAdapterState( 1790): Stopping profile services that were post enabled
,D/A2dpService( 1790): Received stop request...Stopping profile...
,D/A2dpStateMachine( 1790): Exit Disconnected: -1
,D/BluetoothA2dp( 1015): Proxy object disconnected
,D/HidService( 1790): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 1790): Profile still running: com.android.bluetooth.hdp.HealthService
,D/HealthService( 1790): Received stop request...Stopping profile...
W/BluetoothHeadsetServiceJni( 1790): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 1790): Cleaning up Bluetooth Handsfree callback object
,D/PanService( 1790): Received stop request...Stopping profile...
D/BluetoothTethering( 1015): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering( 1015): attempted to stop reverse tether with nothing tethered
,D/BluetoothTethering( 1015): Disconnect CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@420fcdd8
,D/BluetoothPan( 1015): BluetoothPAN Proxy object disconnected
,D/BluetoothTethering( 1015): got CMD_CHANNEL_DISCONNECTED
,D/BtGatt.DebugUtils( 1790): handleDebugAction() action=null
D/BtGatt.GattService( 1790): Received stop request...Stopping profile...
,D/BtGatt.GattService( 1790): stop()
D/BluetoothMapService( 1790): Received stop request...Stopping profile...
,D/BluetoothMapService( 1790): stop()
,D/BluetoothMapService( 1790): MAP Service closeService in
,D/BluetoothAdapterService( 1790): Profile still running: com.android.bluetooth.hdp.HealthService
,I/GKI_LINUX( 1790): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 1790): GKI_exit_task: GKI_exit_task 2 done
,I/GKI_LINUX( 1790): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BluetoothAdapterService( 1790): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 1790): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 1790): cleanup: HH disabling or disabled already, status = 0
,W/BluetoothHidServiceJni( 1790): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 1790): Profile still running: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothHealthServiceJni( 1790): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 1790): Cleaning up Bluetooth Health object
,D/BluetoothAdapterService( 1790): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 1790): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 1790): Cleaning up Bluetooth PAN callback object
,D/BluetoothAdapterService( 1790): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/BluetoothMapService( 1790): cleanup()
,D/BluetoothMapService( 1790): MAP Service closeService in
,W/Settings( 1237): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BluetoothAdapterState( 1790): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1790): Setting state to 10
I/BluetoothAdapterState( 1790): Bluetooth adapter state changed: 13-> 10
,D/BluetoothAdapterService( 1790): Broadcasting updateAdapterState() to 1 receivers.
I/BluetoothAdapterState( 1790): Entering OffState
D/BluetoothManagerService( 1015): Message: 60
,D/BluetoothManagerService( 1015): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1015): Broadcasting onBluetoothStateChange(false) to 10 receivers.
,D/BluetoothHeadset( 1272): onBluetoothStateChange: up=false
,D/BluetoothPan( 1015): onBluetoothStateChange on: false
,D/BluetoothHeadset( 1272): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1272): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 1015): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1015): onBluetoothStateChange: up=false
,D/BluetoothMap( 4008): onBluetoothStateChange: up=false
,D/BluetoothPan( 4008): onBluetoothStateChange on: false
,D/BluetoothInputDevice( 4008): onBluetoothStateChange: up=false
,D/BluetoothPbap( 4008): onBluetoothStateChange: up=false
,D/BluetoothManagerService( 1015): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService( 1015): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/BluetoothManagerService( 1015): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@4279d970 mBinding = false
,D/BluetoothManagerService( 1015): Sending unbind request.
,D/BluetoothAdapterService( 1790): Cleaning up adapter native....
,I/GKI_LINUX( 1790): gki_task_entry: gki_task task_id=1 [BTIF] terminating
,D/BluetoothManagerService( 1015): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter( 1078): 1108469528: getState() :  mService = null. Returning STATE_OFF
W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.sendDeviceAttachIntent:820 com.motorola.authentication.MotAuthenticationService.access$1300:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:575 
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.handleKeepDeviceUnlockRequest:732 com.motorola.authentication.MotAuthenticationService.access$1500:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:563 
I/GKI_LINUX( 1790): GKI_exit_task: GKI_exit_task 1 done
I/GKI_LINUX( 1790): GKI_destroy_task: GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 1790): cleanupNative: return from cleanup
D/BluetoothAdapterService( 1790): Done cleaning up adapter native....
D/BluetoothAdapterService(1107002872)( 1790): ****onDestroy()********
D/BtGatt.GattService( 1790): cleanup()
W/bt-btif ( 1790): GATTC Module not enabled/already disabled
,W/bt-btif ( 1790): GATTS Module not enabled/already disabled
,W/ContextImpl( 4008): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/BluetoothAdapter( 1237): 1110944184: getState() :  mService = null. Returning STATE_OFF
D/DockEventReceiver( 4008): finishStartingService: stopping service
D/BluetoothAdapter( 1237): 1110944184: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4008): 1107028520: getState() :  mService = null. Returning STATE_OFF
V/BluetoothFtpReceiver( 1790): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 1790): BluetoothFtpReceiver Stop Service
V/BluetoothFtpService( 1790): Ftp Service onDestroy
V/BluetoothFtpService( 1790): Ftp Service closeService
,E/BluetoothFtpService:RfcommSocketAcceptThread( 1790): Shutdown
,D/AuthorizationBluetoothService( 1353): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager( 1015): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.ConnectedUnlockReceiver: pid=4060 uid=10016 gids={50016, 3002}
,I/ActivityManager( 1015): Killing 3413:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/rmt_storage(  361): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb85b21d0
I/rmt_storage(  361): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  361): wakelock acquired: 1, error no: 42
I/rmt_storage(  361): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1201987864)
,I/ActivityManager( 1015): Killing 3801:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Checkin ( 4060): publish the event [tag = DEVICE_AUTH_STATS_L2 event name = DEVAUTH_CONNECT]
,E/memtrack( 4040): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4040): failed to load memtrack module: -2
,I/rmt_storage(  361): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  361): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  361): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1201987864) wakelock released: 1, error no: 0
I/rmt_storage(  361): 
,I/rmt_storage(  361): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb85b21d0
,D/Checkin ( 2290): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2290): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/AndroidRuntime( 4040): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1015): Force stopping com.example.hello appid=10407 user=-1: uninstall pkg
,I/ActivityManager( 1015): Killing 3953:com.example.hello/u0a407 (adj 0): stop com.example.hello
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1015):   Force finishing activity ActivityRecord{42948890 u0 com.example.hello/.MainActivity t3}
,I/WindowState( 1015): WIN DEATH: Window{429d49f8 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1015): Client connection lost with reason: 4
I/SFPerfTracer(  275):      triggers: (rate: 3:37) (compose: 0:4) (post: 0:1) (render: 0:6) (0:112 frames) (1:545)
,D/SFPerfTracer(  275):        layers: (0:13) (FocusedStackFrame: 0:8)* (StatusBar: 0:204)* (NavigationBar: 0:38)* (com.android.systemui.ImageWallpaper: 0:7)* (com.android.launcher/com.android.launcher2.Launcher: 0:11)* (Starting com.motorola.ccc.ota: 0:32)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:16)* (ElectronBeam: 0:26)* (com.example.hello/com.example.hello.MainActivity: 1:4)* 
,W/PackageSettings( 1015): Skipping PackageSetting{4226eb28 com.test.thalitest/10104} due to missing metadata
,I/ActivityManager( 1015): Force stopping com.example.hello appid=10407 user=0: pkg removed
W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager( 1015):   Force finishing activity ActivityRecord{42948890 u0 com.example.hello/.MainActivity t3 f}
,W/ActivityManager( 1015): Duplicate finish request for ActivityRecord{42948890 u0 com.example.hello/.MainActivity t3 f}
,I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
,I/OtaApp  ( 1533): [info] > Updatetime from metadata: 10
,D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "sms"
,D/dalvikvm( 2290): GC_EXPLICIT freed 5139K, 44% free 9656K/17224K, paused 2ms+21ms, total 54ms
I/ActivityManager( 1015): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4077 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "smsto"
,I/LatinIME:LogUtils( 1208): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/LatinIME:LogUtils( 1208): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mms"
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mmsto"
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/TCMD    (  581): NL - Read 444 bytes from update socket.
D/TCMD    (  581): NL - ignore NL message, type = 17
D/TCMD    (  581): Listening for incoming client connection request
,D/NetlinkEvent(  271): Unexpected netlink message. type=0x11
W/Netd    (  271): No subsystem found in netlink event
D/OtaApp  ( 1533): [debug] > cancelling the previous pending intent set for install later
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "sms"
I/OtaApp  ( 1533): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
I/MDMCTBK (  274): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  274): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  274): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  274): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  274): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/dalvikvm( 1317): GC_EXPLICIT freed 3241K, 33% free 11594K/17224K, paused 2ms+5ms, total 106ms
,D/dalvikvm( 2339): GC_EXPLICIT freed 4074K, 42% free 10092K/17224K, paused 2ms+4ms, total 118ms
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "smsto"
,D/dalvikvm( 1015): GC_EXPLICIT freed 2053K, 15% free 18085K/21076K, paused 3ms+20ms, total 134ms
,I/Launcher( 1317): Deferring update until onResume
,D/dalvikvm( 1015): WAIT_FOR_CONCURRENT_GC blocked 68ms
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mms"
D/TCMD    (  581): NL - Read 1000 bytes from update socket.
D/TCMD    (  581): NL - message type is RTM_NEWLINK
D/TCMD    (  581): Listening for incoming client connection request
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mmsto"
,D/NetlinkEvent(  271): Unexpected netlink message. type=0x11
D/TCMD    (  581): NL - Read 444 bytes from update socket.
W/Netd    (  271): No subsystem found in netlink event
D/TCMD    (  581): NL - ignore NL message, type = 17
D/TCMD    (  581): Listening for incoming client connection request
I/Launcher( 1317): Deferring update until onResume
I/MDMCTBK (  274): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  274): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  274): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  274): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  274): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  274): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
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
,D/dalvikvm( 1015): GC_EXPLICIT freed 467K, 16% free 17905K/21076K, paused 5ms+11ms, total 123ms
,D/dalvikvm( 1015): WAIT_FOR_CONCURRENT_GC blocked 186ms
,W/GeofencerStateMachine( 1237): Ignoring removeGeofence because network location is disabled.
,D/BackupManagerService( 1015): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService( 1015): removePackageParticipantsLocked: uid=10407 #1
D/OtaApp  ( 1533): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/LatinIME:LogUtils( 1208): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1448386028
,D/OtaApp  ( 1533): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/InputMethodManagerService( 1015): Got RemoteException sending setActive(false) notification to pid 3953 uid 10407
W/Binder  ( 1208): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1208): java.lang.NullPointerException
W/Binder  ( 1208): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1208): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1208): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1208): 	at dalvik.system.NativeStart.run(Native Method)
,I/LatinIME:LogUtils( 1208): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1448386028
,D/Checkin ( 2290): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2290): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/VoicemailCleanupService( 4077): Cleaning up data for package: com.example.hello
,I/InternalIcingCorporaPro( 2339): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/ActivityManager( 1015): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4098 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,D/dalvikvm( 1015): GC_EXPLICIT freed 231K, 16% free 17898K/21076K, paused 5ms+27ms, total 191ms
,I/ActivityManager( 1015): Killing 3450:com.google.android.apps.plus/u0a90 (adj 15): empty #9
,W/ContextImpl( 4098): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/AndroidRuntime( 4040): Shutting down VM
,D/dalvikvm( 4040): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 3ms
,I/ActivityManager( 1015): Killing 3772:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1412): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1412): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 1412): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1412): Module APK com.google.android.play.games already loaded
,I/InternalIcingCorporaPro( 2339): UpdateCorporaTask done [took 125 ms] updated apps [took 125 ms] 
D/ChimeraCfgMgr( 1412): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1412): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1412): Removing dialog suppression flag for package com.example.hello
,E/NetworkScheduler.SchedulerReceiver( 1353): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1353): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1412): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1412): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,I/PeopleContactsSync( 1412): CP2 sync disabled
D/gH_MetricsDatabase( 1412): 0 metrics were deleted when clearing package com.example.hello.
,D/gH_CompatibleDatabase( 1412): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/Icing   ( 1412): doRemovePackageData com.example.hello
,D/gH_CompatibleDatabase( 1412): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
I/dalvikvm( 3470): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3470): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3470): VFY: replacing opcode 0x6e at 0x0013
,D/gH_CompatibleDatabase( 1412): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1412): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1412): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1412): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1412): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1412): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1412): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1412): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager( 1015): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4120 uid=10058 gids={50058}
,I/ContactLocale( 4077): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/Documents( 4120): Loading roots for com.android.providers.downloads.documents
,I/ActivityManager( 1015): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4133 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/ActivityManager( 1015): Killing 4008:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiService( 1015): Client connection lost with reason: 4
,I/ActivityManager( 1015): Killing 1790:com.android.bluetooth/1002 (adj 15): empty #9
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 4133): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fb5640, skipping init
I/openssl ( 4133): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4133): Crypto mode 0 already enabled
D/Documents( 4120): Loading roots for com.android.externalstorage.documents
,I/ActivityManager( 1015): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4150 uid=10020 gids={50020, 1028, 1015, 1023}
,D/dalvikvm(  277): GC_EXPLICIT freed 44K, 48% free 9012K/17224K, paused 1ms+2ms, total 19ms
,I/ActivityManager( 1015): Killing 4060:com.motorola.deviceauthenticator/u0a16 (adj 15): empty #9
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms
D/ExternalStorage( 4150): After updating volumes, found 1 active roots
D/Documents( 4120): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 4120): Loading roots for com.android.providers.media.documents
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 18ms
,D/Documents( 4120): Loading roots for com.google.android.apps.docs.storage
,D/Checkin ( 2290): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,E/SQLiteLog( 2290): (778) statement aborts at 25: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] 
,E/SQLiteDatabase( 2290): Error inserting state=event=am_kill pid=3450 process=com.google.android.apps.plus reason=empty+%239 selectadj=15 timestamp=1448386028488 timezone=3600 name=ProcessKillTrigger
E/SQLiteDatabase( 2290): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 2290): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2290): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2290): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2290): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2290): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2290): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2290): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2290): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2290): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2290): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2290): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2290): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2290): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2290): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2290): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Documents( 4120): Update found 7 roots in 202ms
,D/Documents( 4120): Used cached roots for com.android.providers.downloads.documents
,D/Documents( 4120): Loading roots for com.android.externalstorage.documents
,D/Documents( 4120): Used cached roots for com.android.providers.media.documents
D/Documents( 4120): Used cached roots for com.google.android.apps.docs.storage
,D/Documents( 4120): Update found 7 roots in 7ms

```
