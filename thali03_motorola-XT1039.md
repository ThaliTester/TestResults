#### Test 55634150e857e16_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager(  989): sending alarm Alarm{42936ce0 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 4054): 
D/AndroidRuntime( 4054): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4054): CheckJNI is OFF
D/dalvikvm( 4054): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4054): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4054): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4054): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4054): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4054): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4054): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4054): failed to load memtrack module: -2
D/AndroidRuntime( 4054): Calling main entry com.android.commands.am.Am
I/ActivityManager(  989): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 4054
W/WindowManager(  989): Not okToDisplay, so not showing Starting Window
I/ActivityManager(  989): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4069 uid=10542 gids={50542, 3003, 3001, 3002}
D/AndroidRuntime( 4054): Shutting down VM
D/dalvikvm( 4054): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4069): Binding Chromium to main looper Looper (main, tid 1) {42032730}
I/LibraryLoader( 4069): Expected native library version number "",actual native library version number ""
I/chromium( 4069): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4069): Initializing chromium process, renderers=0
D/BluetoothManagerService(  989): Message: 20
D/BluetoothManagerService(  989): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4213cce0:true
I/Adreno-EGL( 4069): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4069): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4069): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4069): Local Branch: 
I/Adreno-EGL( 4069): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4069): Local Patches: NONE
I/Adreno-EGL( 4069): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4069): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4069): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4069): VFY: unable to resolve virtual method 170: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4069): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4069): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4069): VFY: unable to resolve virtual method 165: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4069): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4069): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4069): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4069): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4069): VFY: unable to resolve virtual method 223: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4069): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4069): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4069): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4069): VFY: unable to resolve virtual method 181: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4069): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4069): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4069): VFY: unable to resolve virtual method 186: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4069): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4069): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4069): Enabling debug mode 0
,W/AwContents( 4069): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4069): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler(  989): Displayed com.example.hello/.MainActivity,cp,ca,331
I/ActivityManager(  989): Displayed com.example.hello/.MainActivity: +304ms (total +331ms)
,I/chromium( 4069): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 4069): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 4069): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4069): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x420381f8
,D/dalvikvm( 4069): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x420381f8
D/jxcore_app_log( 4069): JniHelper::setJavaVM(0x41753f78), pthread_self() = 1609170936
,D/JX-Cordova( 4069): jxcore cordova android initializing
,W/jxcore-log( 4069): Initializing JXcore engine
,W/jxcore-log( 4069): JXcore engine is ready
,W/jxcore-log( 4069): Starting JXcore engine
,W/jxcore-log( 4069): Platform android
W/jxcore-log( 4069): 
,W/jxcore-log( 4069): Process ARCH arm
W/jxcore-log( 4069): 
,I/jxcore-log( 4069): JXcore Cordova bridge is ready!
I/jxcore-log( 4069): 
,W/jxcore-log( 4069): JXcore engine is started
,E/jxcore-log( 4069): >> motorola-XT1039
E/jxcore-log( 4069): 
,I/jxcore-log( 4069): Total memory 893136896
I/jxcore-log( 4069): 
I/jxcore-log( 4069): Free memory 33402880
I/jxcore-log( 4069): 
,I/jxcore-log( 4069): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4069): 
,I/jxcore-log( 4069): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4069): 
,I/jxcore-log( 4069): userPath [ 'www', 'www' ]
I/jxcore-log( 4069): 
,I/jxcore-log( 4069): Size 720 1184
I/jxcore-log( 4069): 
,I/jxcore-log( 4069): Screen Brightness 10
I/jxcore-log( 4069): 
,E/jxcore-log( 4069): Dummy Error Log.
E/jxcore-log( 4069): 
,I/jxcore-log( 4069): getBuffer is called!!!!
I/jxcore-log( 4069): 
,D/BluetoothManagerService(  989): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  989): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@424c0350 mBinding = false
,W/Settings( 1250): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1292): No entry in secure settings for enhanced location services: false
,D/BluetoothManagerService(  989): Message: 2
,D/BluetoothManagerService(  989): Sending off request.
,D/BluetoothAdapterState( 1763): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1763): Setting state to 13
,I/BluetoothAdapterState( 1763): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 1763): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterProperties( 1763): onBluetoothDisable()
,I/BluetoothAdapterState( 1763): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,I/BluetoothAdapterProperties( 1763): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothAdapterProperties( 1763): Scan Mode:21
,D/BluetoothAdapterState( 1763): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,D/BluetoothManagerService(  989): Message: 60
,D/BluetoothManagerService(  989): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,E/BtOppRfcommListener( 1763): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 1763): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 1763): bta_jv_rfcomm_stop_server
,E/bt-btif ( 1763): bta_jv_rfcomm_stop_server
E/bt-btif ( 1763): bta_jv_rfcomm_stop_server
,E/bt-btif ( 1763): bta_jv_rfcomm_stop_server
,D/BluetoothManagerService(  989): Bluetooth State Change Intent: 12 -> 13
,D/btif_config_util( 1763): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1763): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,W/bt-l2cap( 1763): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1763): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothMapService( 1763): onReceive
,D/BluetoothMapService( 1763): STATE_TURNING_OFF removeTimeoutMsg:false
,D/BluetoothMapService( 1763): MAP Service closeService in
,I/ActivityManager(  989): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=4126 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,D/WifiService(  989): New client listening to asynchronous messages
,W/Settings( 1250): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiService(  989): setWifiEnabled: false pid=4069, uid=10542
E/WifiService(  989): Invoking mWifiStateMachine.setWifiEnabled
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,I/BtOppRfcommListener( 1763): stopping Accept Thread
,I/BtOppRfcommListener( 1763): BluetoothSocket listen thread finished
,W/Settings( 1250): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiStateMachine(  989): handleMessage: E msg.what=131084
D/WifiStateMachine(  989): processMsg: ConnectedState
D/WifiStateMachine(  989): processMsg: L2ConnectedState
D/WifiStateMachine(  989): processMsg: ConnectModeState
D/WifiStateMachine(  989): processMsg: DriverStartedState
D/WifiStateMachine(  989): processMsg: SupplicantStartedState
D/WifiStateMachine(  989): transitionTo: destState=WaitForP2pDisableState
,D/WifiStateMachine(  989): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  989): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
,W/XTWiFiOS( 1292): No entry in secure settings for enhanced location services: false
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
I/jxcore-log( 4069): ****TEST TOOK:  5219  ms ****
I/jxcore-log( 4069): 
W/Settings( 1250): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/jxcore-log( 4069): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4069): 
D/WifiStateMachine(  989): invokeExitMethods: ConnectedState
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiStateMachine(  989): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  989): Stopping DHCP and clearing IP
D/WifiStateMachine(  989): setSuspendOptimizationsNative: 1 true
D/WifiP2pService(  989): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  989): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  270): Clearing all IP addresses on wlan0
D/TCMD    (  452): NL - Read 60 bytes from update socket.
D/TCMD    (  452): NL - ignore NL message, type = 21
D/TCMD    (  452): Listening for incoming client connection request
D/WifiStateMachine(  989): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  989): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  989): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics(  989): connected time updated 100169
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService(  989): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  989): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/ConnectivityService(  989): Attempting to switch to mobile
D/ConnectivityService(  989): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService(  989): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/WifiStateMachine(  989): invokeExitMethods: ConnectModeState
D/WifiStateMachine(  989): invokeExitMethods: DriverStartedState
D/Checkin (  989): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  989): Unexpected BatchedScanResults :OK
W/ContextImpl( 4126): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothPbapService( 1763): action: android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothManagerService(  989): Message: 20
,D/BluetoothManagerService(  989): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42905720:true
D/WifiStateMachine(  989): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine(  989): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
,D/WifiStateMachine(  989): invokeEnterMethods: WaitForP2pDisableState
D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=131216
D/WifiStateMachine(  989): processMsg: WaitForP2pDisableState
D/WifiStateMachine(  989): processMsg: SupplicantStartedState
D/WifiStateMachine(  989): processMsg: DefaultState
D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=131216
D/WifiStateMachine(  989): processMsg: WaitForP2pDisableState
D/WifiStateMachine(  989): processMsg: SupplicantStartedState
D/WifiStateMachine(  989): processMsg: DefaultState
,D/WifiStateMachine(  989): handleMessage: X
D/WifiP2pService(  989): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  989): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  989): P2pDisablingState
D/WifiP2pService(  989): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  989): p2p socket connection lost
,D/WifiP2pService(  989): P2pDisabledState
D/WifiStateMachine(  989): handleMessage: E msg.what=131205
D/WifiStateMachine(  989): processMsg: WaitForP2pDisableState
D/WifiStateMachine(  989): transitionTo: destState=SupplicantStoppingState
D/WifiStateMachine(  989): handleMessage: new destination call exit/enter
D/WifiStateMachine(  989): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  989): invokeExitMethods: WaitForP2pDisableState
D/WifiStateMachine(  989): invokeExitMethods: SupplicantStartedState
D/WifiStateMachine(  989): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine(  989): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/WifiStateMachine(  989): invokeEnterMethods: SupplicantStoppingState
D/WifiStateMachine(  989): Stopping DHCP and clearing IP
D/WifiStateMachine(  989): setSuspendOptimizationsNative: 1 true
,D/BluetoothManagerService(  989): Message: 30
,W/ContextImpl( 4126): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
,D/BluetoothManagerService(  989): Message: 30
,W/ContextImpl( 4126): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 4126): Adding local MAP profile
D/WifiP2pService(  989): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  989): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothMap( 4126): Create BluetoothMap proxy object
D/BluetoothManagerService(  989): Message: 30
,D/ConnectivityService(  989): resetConnections(wlan0, 3)
D/NetUtils(  989): android_net_utils_resetConnections in env=0x61567478 clazz=0x63800001 iface=wlan0 mask=0x3
,V/NativeCrypto( 1354): Read error: ssl=0x63317df0: I/O error during system call, Connection timed out
,W/ContextImpl( 4126): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
V/NativeCrypto( 1354): SSL shutdown failed: ssl=0x63317df0: I/O error during system call, Broken pipe
,D/BluetoothManagerService(  989): Message: 30
,W/ContextImpl( 4126): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 4126): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 4126): finishStartingService: stopping service
,D/CommandListener(  270): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  989): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,W/bt-btif ( 1763): ag scb idx 1 not allocated
D/WifiStateMachine(  989): stopping supplicant
E/bt-btif ( 1763): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1763): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1763): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1763): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1763): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1763): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1763): L2CAP - PSM: 0x0017 not found for deregistration
,D/WifiStateMachine(  989): setWifiState: disabling
,I/bt_hwcfg( 1763): hw_epilog_process
,D/Checkin (  989): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1292): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1292): Active network info is not available
D/WifiStateMachine(  989): handleMessage: X
E/XTCC-3.0.0.2(  453): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  453): [WwanPosMgr] handleConnectivtyStatusChange failed
,I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=(none) Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/WifiService(  989): New client listening to asynchronous messages
,D/Nat464Xlat(  989): requiresClat: netType=1, hasIPv4Address=false
E/XTCC-3.0.0.2(  453): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  453): [CSMgr] handleConnectivtyStatusChange failed
I/bt_hwcfg( 1763): hw_epilog_cback Opcode:0x0C03 Status: 0
I/bt_hci_bdroid( 1763): bt_hc_worker_thread exiting
D/bt_userial_mct( 1763): userial_close
I/bt_userial_mct( 1763): exiting userial_read_thread
D/bt_userial_mct( 1763): Leaving userial_evt_read_thread()
I/ModemStatsDSDetect( 1215): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1215): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1215): onReceive() - done, currentInetCondition=0
D/ConnectivityService(  989): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  989): Attempting to switch to mobile
D/ConnectivityService(  989): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService(  989): Attempting to switch to ETHERNET
,D/TCMD    (  452): NL - Read 1000 bytes from update socket.
D/TCMD    (  452): NL - message type is RTM_NEWLINK
,D/TCMD    (  452): Listening for incoming client connection request
D/TCMD    (  452): NL - Read 68 bytes from update socket.
D/TCMD    (  452): NL - message type is RTM_NEWLINK
D/TCMD    (  452): Listening for incoming client connection request
D/TCMD    (  452): NL - Read 68 bytes from update socket.
D/TCMD    (  452): NL - message type is RTM_NEWLINK
,D/TCMD    (  452): Listening for incoming client connection request
,I/wpa_supplicant( 1169): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  273): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  273):  STA Disconnected !!
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): get_property_value, Enter
I/MDMCTBK (  273): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  273): get_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,D/Tethering(  989): InitialState.processMessage what=4
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  273): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/Tethering(  989): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine(  989): handleMessage: E msg.what=147460
D/WifiStateMachine(  989): processMsg: SupplicantStoppingState
D/WifiStateMachine(  989): processMsg: DefaultState
D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=147462
D/WifiStateMachine(  989): processMsg: SupplicantStoppingState
D/WifiStateMachine(  989): processMsg: DefaultState
,D/WifiStateMachine(  989): handleMessage: X
,D/Tethering(  989): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine(  989): handleMessage: E msg.what=131101
D/WifiStateMachine(  989): processMsg: SupplicantStoppingState
D/WifiStateMachine(  989): processMsg: DefaultState
,D/WifiStateMachine(  989): handleMessage: X
,I/wpa_supplicant( 1169): eap_proxy Deinitialzed
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 3
D/WifiStateMachine(  989): handleMessage: E msg.what=196614
D/WifiStateMachine(  989): processMsg: SupplicantStoppingState
D/WifiStateMachine(  989): processMsg: DefaultState
,D/WifiStateMachine(  989): handleMessage: X
,D/Nat464Xlat(  989): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  989): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1215): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1215): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1215): onReceive() - done, currentInetCondition=0
,D/dalvikvm(  989): GC_EXPLICIT freed 1457K, 15% free 18175K/21208K, paused 3ms+10ms, total 110ms
,V/BluetoothFtpReceiver( 1763): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothInputDevice( 4126): Proxy object connected
,D/HidProfile( 4126): Bluetooth service connected
,D/BluetoothPan( 4126): BluetoothPAN Proxy object connected
D/PanProfile( 4126): Bluetooth service connected
,D/BluetoothMap( 4126): Proxy object connected
D/MapProfile( 4126): Bluetooth service connected
,D/BluetoothMap( 4126): getConnectedDevices()
,D/AuthorizationBluetoothService( 1354): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/TCMD    (  452): NL - Read 1000 bytes from update socket.
D/TCMD    (  452): NL - message type is RTM_NEWLINK
,D/TCMD    (  452): Listening for incoming client connection request
I/wpa_supplicant( 1169): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  273): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  273):  Wpa Supplicant Exiting !!
D/MDMCTBK (  273): wifi_wait_on_socket: Exiting monitor thread
,D/MDMCTBK (  273): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  273): wifi_close_sockets: Exit
D/WifiStateMachine(  989): handleMessage: E msg.what=147458
D/WifiStateMachine(  989): processMsg: SupplicantStoppingState
,D/WifiStateMachine(  989): Supplicant connection lost
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/BluetoothMap( 4126): Bluetooth is Not enabled
,I/ActivityManager(  989): Killing 3813:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/BTSNOOP-DISP( 1763): btsnoop_close
,I/bt_vendor( 1763): cleanup
I/bt_hwcfg( 1763): Starting hciattach daemon
,I/bt_hwcfg( 1763): try to set false
I/GKI_LINUX( 1763): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 1763): GKI_exit_task: GKI_exit_task 0 done
,I/GKI_LINUX( 1763): GKI_destroy_task: GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 1763): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 1763): Received stop request...Stopping profile...
D/BluetoothHeadset(  989): Proxy object disconnected
D/BluetoothHeadset( 1276): Proxy object disconnected
D/A2dpService( 1763): Received stop request...Stopping profile...
,D/A2dpStateMachine( 1763): Exit Disconnected: -1
,D/BluetoothA2dp(  989): Proxy object disconnected
D/BluetoothHeadset( 1276): Proxy object disconnected
,D/BluetoothHeadset( 1276): Proxy object disconnected
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/HidService( 1763): Received stop request...Stopping profile...
,D/BluetoothAdapterState( 1763): Stopping profile services that were post enabled
D/BluetoothAdapterService( 1763): Profile still running: com.android.bluetooth.hdp.HealthService
D/BluetoothInputDevice( 4126): Proxy object disconnected
,D/HidProfile( 4126): Bluetooth service disconnected
W/BluetoothHeadsetServiceJni( 1763): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 1763): Cleaning up Bluetooth Handsfree callback object
,D/BluetoothAdapterService( 1763): Profile still running: com.android.bluetooth.hdp.HealthService
,D/HealthService( 1763): Received stop request...Stopping profile...
,I/GKI_LINUX( 1763): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 1763): GKI_exit_task: GKI_exit_task 2 done
I/GKI_LINUX( 1763): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
,D/PanService( 1763): Received stop request...Stopping profile...
D/BluetoothTethering(  989): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering(  989): attempted to stop reverse tether with nothing tethered
,D/BluetoothTethering(  989): Disconnect CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@42962bf8
D/BluetoothTethering(  989): got CMD_CHANNEL_DISCONNECTED
,D/BluetoothPan(  989): BluetoothPAN Proxy object disconnected
D/BluetoothPan( 4126): BluetoothPAN Proxy object disconnected
D/BtGatt.DebugUtils( 1763): handleDebugAction() action=null
D/BtGatt.GattService( 1763): Received stop request...Stopping profile...
,D/BtGatt.GattService( 1763): stop()
,D/PanProfile( 4126): Bluetooth service disconnected
D/BluetoothAdapterService( 1763): Profile still running: com.android.bluetooth.hdp.HealthService
D/BluetoothMapService( 1763): Received stop request...Stopping profile...
,D/BluetoothMapService( 1763): stop()
,D/BluetoothMapService( 1763): MAP Service closeService in
W/BluetoothHidServiceJni( 1763): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 1763): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 1763): Cleaning up Bluetooth GID callback object
D/BluetoothMap( 4126): Proxy object disconnected
D/MapProfile( 4126): Bluetooth service disconnected
D/BluetoothAdapterService( 1763): Profile still running: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothHealthServiceJni( 1763): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 1763): Cleaning up Bluetooth Health object
,D/BluetoothAdapterService( 1763): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 1763): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 1763): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService( 1763): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/BluetoothMapService( 1763): cleanup()
,D/BluetoothMapService( 1763): MAP Service closeService in
D/BluetoothAdapterState( 1763): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1763): Setting state to 10
I/BluetoothAdapterState( 1763): Bluetooth adapter state changed: 13-> 10
,D/BluetoothAdapterService( 1763): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  989): Message: 60
D/BluetoothManagerService(  989): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  989): Broadcasting onBluetoothStateChange(false) to 10 receivers.
D/BluetoothPan(  989): onBluetoothStateChange on: false
,D/BluetoothHeadset(  989): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 1763): Entering OffState
,D/BluetoothHeadset( 1276): onBluetoothStateChange: up=false
,D/BluetoothPan( 4126): onBluetoothStateChange on: false
,D/BluetoothMap( 4126): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1276): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1276): onBluetoothStateChange: up=false
D/BluetoothA2dp(  989): onBluetoothStateChange: up=false
,D/BluetoothPbap( 4126): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 4126): onBluetoothStateChange: up=false
D/BluetoothManagerService(  989): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService(  989): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService(  989): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@424c0350 mBinding = false
,D/BluetoothManagerService(  989): Sending unbind request.
,D/BluetoothManagerService(  989): Bluetooth State Change Intent: 13 -> 10
D/BluetoothAdapterService( 1763): Cleaning up adapter native....
,I/GKI_LINUX( 1763): gki_task_entry: gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 1763): GKI_exit_task: GKI_exit_task 1 done
I/GKI_LINUX( 1763): GKI_destroy_task: GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 1763): cleanupNative: return from cleanup
,D/BluetoothAdapterService( 1763): Done cleaning up adapter native....
,D/BluetoothAdapterService(1107568016)( 1763): ****onDestroy()********
D/BtGatt.GattService( 1763): cleanup()
W/bt-btif ( 1763): GATTC Module not enabled/already disabled
,W/bt-btif ( 1763): GATTS Module not enabled/already disabled
,D/BluetoothAdapter( 1081): 1109039096: getState() :  mService = null. Returning STATE_OFF
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.sendDeviceAttachIntent:820 com.motorola.authentication.MotAuthenticationService.access$1300:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:575 
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.handleKeepDeviceUnlockRequest:732 com.motorola.authentication.MotAuthenticationService.access$1500:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:563 
D/BluetoothAdapter( 1227): 1112053944: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1227): 1112053944: getState() :  mService = null. Returning STATE_OFF
,W/ContextImpl( 4126): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
D/DockEventReceiver( 4126): finishStartingService: stopping service
,D/BluetoothAdapter( 4126): 1107595408: getState() :  mService = null. Returning STATE_OFF
,V/BluetoothFtpReceiver( 1763): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 1763): BluetoothFtpReceiver Stop Service
V/BluetoothFtpService( 1763): Ftp Service onDestroy
V/BluetoothFtpService( 1763): Ftp Service closeService
D/AuthorizationBluetoothService( 1354): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/BluetoothFtpService:RfcommSocketAcceptThread( 1763): Shutdown
,D/WifiStateMachine(  989): setWifiState: disabled
,I/ActivityManager(  989): Killing 3435:android.process.acore/u0a10 (adj 15): empty #9
D/WifiStateMachine(  989): transitionTo: destState=InitialState
W/XTWiFiOS( 1292): No entry in secure settings for enhanced location services: false
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/XTWiFiOS( 1292): Active network info is not available
I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
E/XTCC-3.0.0.2(  453): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  453): [WwanPosMgr] handleConnectivtyStatusChange failed
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine(  989): handleMessage: new destination call exit/enter
D/WifiStateMachine(  989): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  989): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine(  989): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine(  989): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
D/WifiStateMachine(  989): invokeEnterMethods: InitialState
E/XTCC-3.0.0.2(  453): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  453): [CSMgr] handleConnectivtyStatusChange failed
D/AndroidRuntime( 4157): 
D/AndroidRuntime( 4157): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4157): CheckJNI is OFF
,W/Settings( 1227): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  989): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.ConnectedUnlockReceiver: pid=4170 uid=10016 gids={50016, 3002}
,D/dalvikvm( 4157): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4157): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4157): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4157): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4157): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/BluetoothAdapter( 4126): 1107595408: getState() :  mService = null. Returning STATE_OFF
,D/Checkin ( 4170): publish the event [tag = DEVICE_AUTH_STATS_L2 event name = DEVAUTH_CONNECT]
I/ActivityManager(  989): Killing 3921:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 4157): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
I/rmt_storage(  403): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb78ed1d0
I/rmt_storage(  403): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  403): wakelock acquired: 1, error no: 42
,I/rmt_storage(  403): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1215377688)
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/rmt_storage(  403): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  403): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  403): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1215377688) wakelock released: 1, error no: 0
I/rmt_storage(  403): 
,I/rmt_storage(  403): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb78ed1d0
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/Checkin ( 2242): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2242): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
E/memtrack( 4157): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4157): failed to load memtrack module: -2
,D/AndroidRuntime( 4157): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  989): Force stopping com.example.hello appid=10542 user=-1: uninstall pkg
,I/ActivityManager(  989): Killing 4069:com.example.hello/u0a542 (adj 0): stop com.example.hello
,I/ActivityManager(  989):   Force finishing activity ActivityRecord{42947158 u0 com.example.hello/.MainActivity t3}
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/WindowState(  989): WIN DEATH: Window{429e2988 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  989): Client connection lost with reason: 4
,I/dalvikvm(  989): Total arena pages for JIT: 15
,W/PackageSettings(  989): Skipping PackageSetting{422faec0 com.test.thalitest/10540} due to missing metadata
,D/NetlinkEvent(  270): Unexpected netlink message. type=0x11
W/Netd    (  270): No subsystem found in netlink event
D/TCMD    (  452): NL - Read 444 bytes from update socket.
D/TCMD    (  452): NL - ignore NL message, type = 17
D/TCMD    (  452): Listening for incoming client connection request
I/MDMCTBK (  273): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  273): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  273): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  273): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  273): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
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
,I/ActivityManager(  989): Force stopping com.example.hello appid=10542 user=0: pkg removed
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/ActivityManager(  989):   Force finishing activity ActivityRecord{42947158 u0 com.example.hello/.MainActivity t3 f}
W/ActivityManager(  989): Duplicate finish request for ActivityRecord{42947158 u0 com.example.hello/.MainActivity t3 f}
D/TCMD    (  452): NL - Read 1000 bytes from update socket.
D/TCMD    (  452): NL - message type is RTM_NEWLINK
D/TCMD    (  452): Listening for incoming client connection request
,D/dalvikvm( 2242): GC_EXPLICIT freed 5163K, 44% free 9659K/17224K, paused 2ms+5ms, total 43ms
,D/dalvikvm( 2286): GC_EXPLICIT freed 2673K, 44% free 9777K/17224K, paused 2ms+3ms, total 34ms
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/OtaApp  ( 1553): [info] > Updatetime from metadata: 10
D/Checkin ( 1553): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm( 1393): GC_EXPLICIT freed 213K, 31% free 11886K/17224K, paused 3ms+16ms, total 83ms
,W/SQLiteConnectionPool( 1393): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/OtaApp  ( 1553): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1553): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1553): publish the event [tag = MOT_OTA event name = LOG]
,D/NetlinkEvent(  270): Unexpected netlink message. type=0x11
W/Netd    (  270): No subsystem found in netlink event
D/TCMD    (  452): NL - Read 444 bytes from update socket.
D/TCMD    (  452): NL - ignore NL message, type = 17
D/TCMD    (  452): Listening for incoming client connection request
I/InputReader(  989): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1227): Ignoring removeGeofence because network location is disabled.
I/MDMCTBK (  273): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  273): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  273): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  273): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  273): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  273): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
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
,I/ActivityManager(  989): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4197 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "sms"
I/LatinIME:LogUtils( 1199): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1199): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "smsto"
I/LatinIME:LogUtils( 1199): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452528667
D/dalvikvm( 1304): GC_EXPLICIT freed 3236K, 33% free 11594K/17224K, paused 2ms+4ms, total 95ms
D/OtaApp  ( 1553): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "mms"
,I/Launcher( 1304): Deferring update until onResume
,I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
D/OtaApp  ( 1553): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "mmsto"
,I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "sms"
,I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "smsto"
,I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "mms"
,I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "mmsto"
,I/Launcher( 1304): Deferring update until onResume
,D/Checkin ( 2242): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2242): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/LatinIME:LogUtils( 1199): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452528668
,D/BackupManagerService(  989): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService(  989): removePackageParticipantsLocked: uid=10542 #1
,I/dalvikvm(  989): Jit: resizing JitTable from 8192 to 16384
,W/InputMethodManagerService(  989): Got RemoteException sending setActive(false) notification to pid 4069 uid 10542
W/Binder  ( 1199): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1199): java.lang.NullPointerException
W/Binder  ( 1199): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1199): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1199): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1199): 	at dalvik.system.NativeStart.run(Native Method)
D/VoicemailCleanupService( 4197): Cleaning up data for package: com.example.hello
,D/dalvikvm(  989): GC_EXPLICIT freed 1473K, 15% free 18052K/21208K, paused 4ms+27ms, total 257ms
,I/InternalIcingCorporaPro( 2286): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/ActivityManager(  989): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4217 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/AndroidRuntime( 4157): Shutting down VM
D/dalvikvm( 4157): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+1ms, total 2ms
,I/ActivityManager(  989): Killing 3476:com.google.android.apps.plus/u0a90 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 4217): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,I/ActivityManager(  989): Killing 3883:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 3494): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3494): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3494): VFY: replacing opcode 0x6e at 0x0013
,D/PackageBroadcastService( 1393): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1393): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 1393): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1393): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1393): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1393): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1393): Removing dialog suppression flag for package com.example.hello
,E/NetworkScheduler.SchedulerReceiver( 1354): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1354): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ContactLocale( 4197): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  989): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4235 uid=10058 gids={50058}
D/gH_CompatibleDatabase( 1393): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1393): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1393): 0 metrics were deleted when clearing package com.example.hello.
,D/gH_CompatibleDatabase( 1393): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1393): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1393): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1393): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1393): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1393): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1393): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1393): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1393): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1393): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/Icing   ( 1393): doRemovePackageData com.example.hello
,I/InternalIcingCorporaPro( 2286): UpdateCorporaTask done [took 213 ms] updated apps [took 209 ms] 
,D/Documents( 4235): Loading roots for com.android.providers.downloads.documents
,I/ActivityManager(  989): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4255 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/ActivityManager(  989): Killing 1763:com.android.bluetooth/1002 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager(  989): Killing 4170:com.motorola.deviceauthenticator/u0a16 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,E/SQLiteLog( 2242): (3850) statement aborts at 30: [SELECT timestamp, triggerState, timezone FROM TriggerView WHERE trigger = 'SettingsTrigger' AND triggerState IS NOT NULL AND triggerId = 137525 ORDER BY timestamp LIMIT 0,100] disk I/O
E/SQLiteQuery( 2242): exception: disk I/O error (code 3850); query: SELECT timestamp, triggerState, timezone FROM TriggerView WHERE trigger = 'SettingsTrigger' AND triggerState IS NOT NULL AND triggerId = 137525 ORDER BY timestamp LIMIT 0,100
,W/dalvikvm( 2242): threadid=12: thread exiting with uncaught exception (group=0x41765d40)
,E/SharedPreferencesImpl( 2242): Couldn't rename file /data/data/com.motorola.motocare/shared_prefs/com.motorola.motocare.xml to backup file /data/data/com.motorola.motocare/shared_prefs/com.motorola.motocare.xml.bak
,E/SQLiteDatabase( 2242): Error inserting state=component=com.motorola.ccc.ota/.ui.InstallationActivity event=am_pause_activity timestamp=1452528667928 timezone=3600 name=PauseResumeTrigger
E/SQLiteDatabase( 2242): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2242): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2242): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2242): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2242): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2242): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2242): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2242): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2242): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2242): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 2242): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
,E/SQLiteDatabase( 2242): Error inserting state=event=am_kill pid=3476 process=com.google.android.apps.plus reason=empty+%239 selectadj=15 timestamp=1452528668253 timezone=3600 name=ProcessKillTrigger
E/SQLiteDatabase( 2242): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2242): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2242): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2242): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2242): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2242): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2242): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2242): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2242): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2242): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/FileUtils( 4255): Failed to chmod(/data/data/com.android.providers.media/databases/external.db): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
E/SQLiteLog( 2242): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
E/SQLiteDatabase( 2242): Error inserting state=event=am_kill pid=3883 process=com.android.defcontainer reason=empty+%239 selectadj=15 timestamp=1452528668303 timezone=3600 name=ProcessKillTrigger
E/SQLiteDatabase( 2242): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2242): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2242): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2242): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2242): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2242): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2242): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2242): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2242): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2242): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4255): (2570) os_unix.c:30323: (30) unlink(/data/data/com.android.providers.media/databases/external.db-wal) - 
E/SQLiteLog( 2242): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
E/SQLiteDatabase( 2242): Error inserting state=event=am_kill pid=1763 process=com.android.bluetooth reason=empty+%239 selectadj=15 timestamp=1452528668473 timezone=3600 name=ProcessKillTrigger
E/SQLiteDatabase( 2242): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2242): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2242): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2242): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2242): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2242): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2242): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2242): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/,SQLiteDatabase( 2242): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2242): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 2242): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
E/MediaProvider( 4255): failed to open database external.db
E/MediaProvider( 4255): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/MediaProvider( 4255): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/MediaProvider( 4255): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/MediaProvider( 4255): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/MediaProvider( 4255): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/MediaProvider( 4255): 	at android.database.sqlite.SQLiteConnectionPool.tryAcquireNonPrimaryConnectionLocked(SQLiteConnectionPool.java:899)
E/MediaProvider( 4255): 	at android.database.sqlite.SQLiteConnectionPool.waitForConnection(SQLiteConnectionPool.java:609)
E/MediaProvider( 4255): 	at android.database.sqlite.SQLiteConnectionPool.acquireConnection(SQLiteConnectionPool.java:348)
E/MediaProvider( 4255): 	at android.database.sqlite.SQLiteSession.acquireConnection(SQLiteSession.java:894)
E/MediaProvider( 4255): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:650)
E/MediaProvider( 4255): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
E/MediaProvider( 4255): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
E/MediaProvider( 4255): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
E/MediaProvider( 4255): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:862)
E/MediaProvider( 4255): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:242)
E/MediaProvider( 4255): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/MediaProvider( 4255): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:441)
E/MediaProvider( 4255): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:5400)
E/MediaProvider( 4255): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:645)
E/MediaProvider( 4255): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/MediaProvider( 4255): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/MediaProvider( 4255): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4855)
E/MediaProvider( 4255): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4450)
E/MediaProvider( 4255): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4390)
E/MediaProvider( 4255): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/MediaProvider( 4255): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/MediaProvider( 4255): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/MediaProvider( 4255): 	at android.os.Looper.loop(Looper.java:136)
E/MediaProvider( 4255): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/MediaProvider( 4255): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/MediaProvider( 4255): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/MediaProvider( 4255): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/MediaProvider( 4255): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/MediaProvider( 4255): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 2242): Error inserting state=event=am_kill pid=4170 process=com.motorola.deviceauthenticator reason=empty+%239 selectadj=15 timestamp=1452528668484 timezone=3600 name=ProcessKillTrigger
E/SQLiteDatabase( 2242): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2242): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2242): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2242): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2242): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2242): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2242): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2242): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2242): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2242): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2242): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Checkin ( 2242): publish the event [tag = MOT_CA_STATS_L1 event name = DC_ERRORS]
W/System.err( 2242): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/System.err( 2242): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForCursorWindow(Native Method)
W/System.err( 2242): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:845)
W/System.err( 2242): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
W/System.err( 2242): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
W/System.err( 2242): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
W/System.err( 2242): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
W/System.err( 2242): 	at android.content.ContentResolver.query(ContentResolver.java:480)
W/System.err( 2242): 	at android.content.ContentResolver.query(ContentResolver.java:404)
W/System.err( 2242): 	at com.motorola.motocare.util.DbIterator$BaseIterator.readChunkFromDb(DbIterator.java:72)
W/System.err( 2242): 	at com.motorola.motocare.util.DbIterator$BaseIterator.<init>(DbIterator.java:63)
W/System.err( 2242): 	at com.motorola.motocare.util.DbIterator$TriggerIterator.<init>(DbIterator.java:40)
W/System.err( 2242): 	at com.motorola.motocare.action.report.SettingsReport.report(SettingsReport.java:86)
W/System.err( 2242): 	at com.motorola.motocare.action.SettingsAction.onReceiveImpl(SettingsAction.java:60)
W/System.err( 2242): 	at com.motorola.motocare.util.BackgroundReceiver$1.run(BackgroundReceiver.java:14)
W/System.err( 2242): 	at android.os.Handler.handleCallback(Handler.java:733)
W/System.err( 2242): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2242): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2242): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 2242): Sending signal. PID: 2242 SIG: 9
E/SQLiteDatabase( 4255): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4255): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4255): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4255): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4255): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4255): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4255): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4255): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4255): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4255): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4255): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4255): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4255): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4255): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4255): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2337)
E/SQLiteDatabase( 4255): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:5409)
E/SQLiteDatabase( 4255): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:645)
E/SQLiteDatabase( 4255): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4255): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4255): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4855)
E/SQLiteDatabase( 4255): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4450)
E/SQLiteDatabase( 4255): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4390)
E/SQLiteDatabase( 4255): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4255): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteDatabase( 4255): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4255): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4255): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4255): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4255): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4255): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4255): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4255): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4255): Couldn't open external.db for writing (will try read-only):
E/SQLiteOpenHelper( 4255): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4255): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4255): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4255): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4255): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4255): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4255): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4255): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 4255): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 4255): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4255): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 4255): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4255): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4255): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2337)
E/SQLiteOpenHelper( 4255): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:5409)
E/SQLiteOpenHelper( 4255): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:645)
E/SQLiteOpenHelper( 4255): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteOpenHelper( 4255): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteOpenHelper( 4255): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4855)
E/SQLiteOpenHelper( 4255): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4450)
E/SQLiteOpenHelper( 4255): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4390)
E/SQLiteOpenHelper( 4255): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 4255): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteOpenHelper( 4255): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4255): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 4255): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteOpenHelper( 4255): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4255): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4255): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteOpenHelper( 4255): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteOpenHelper( 4255): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteLog( 4255): (14) cannot open file at line 28970 of [00bb9c9ce4]
E/SQLiteLog( 4255): (14) os_unix.c:28970: (30) open(/data/data/com.android.providers.media/databases/external.db-shm) - 
E/SQLiteLog( 4255): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
D/AndroidRuntime( 4255): Shutting down VM
W/dalvikvm( 4255): threadid=1: thread exiting with uncaught exception (group=0x41765d40)
E/AndroidRuntime( 4255): FATAL EXCEPTION: main
E/AndroidRuntime( 4255): Process: android.process.media, PID: 4255
E/AndroidRuntime( 4255): java.lang.RuntimeException: Unable to get provider com.android.providers.media.MediaProvider: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
E/AndroidRuntime( 4255): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4858)
E/AndroidRuntime( 4255): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4450)
E/AndroidRuntime( 4255): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4390)
E/AndroidRuntime( 4255): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/AndroidRuntime( 4255): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/AndroidRuntime( 4255): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4255): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4255): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4255): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4255): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4255): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4255): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4255): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4255): Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
E/AndroidRuntime( 4255): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLong(Native Method)
E/AndroidRuntime( 4255): 	at android.database.sqlite.SQLiteConnection.executeForLong(SQLiteConnection.java:598)
E/AndroidRuntime( 4255): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:652)
E/AndroidRuntime( 4255): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
E/AndroidRuntime( 4255): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
E/AndroidRuntime( 4255): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
E/AndroidRuntime( 4255): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:862)
E/AndroidRuntime( 4255): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:242)
E/AndroidRuntime( 4255): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 4255): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2337)
E/AndroidRuntime( 4255): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:5409)
E/AndroidRuntime( 4255): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:645)
E/AndroidRuntime( 4255): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 4255): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 4255): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4855)
E/AndroidRuntime( 4255): 	... 12 more
I/Process ( 4255): Sending signal. PID: 4255 SIG: 9
I/ActivityManager(  989): Process com.motorola.motocare (pid 2242) has died.
W/ActivityManager(  989): Scheduling restart of crashed service com.motorola.motocare/.MotoCareService in 1000ms
E/DropBoxManagerService(  989): Can't write: system_app_crash
E/DropBoxManagerService(  989): java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  989): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  989): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  989): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  989): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  989): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  989): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService(  989): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  989): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  989): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  989): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  989): 	... 5 more
I/ActivityManager(  989): Process android.process.media (pid 4255) has died.
W/ActivityManager(  989): Scheduling restart of crashed service com.android.providers.downloads/.DownloadService in 10993ms
E/SQLiteLog(  989): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/CheckinProvider(  989): SQLiteDiskIOException:
E/CheckinProvider(  989): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/CheckinProvider(  989): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/CheckinProvider(  989): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/CheckinProvider(  989): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/CheckinProvider(  989): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/CheckinProvider(  989): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/CheckinProvider(  989): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/CheckinProvider(  989): 	at com.motorola.android.server.checkin.CheckinProvider.insertEvents(CheckinProvider.java:775)
E/CheckinProvider(  989): 	at com.motorola.android.server.checkin.CheckinProvider.access$000(CheckinProvider.java:67)
E/CheckinProvider(  989): 	at com.motorola.android.server.checkin.CheckinProvider$EventInsertThread.run(CheckinProvider.java:909)
E/CheckinProvider(  989): Exception:
E/CheckinProvider(  989): java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/CheckinProvider(  989): 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
E/CheckinProvider(  989): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
E/CheckinProvider(  989): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
E/CheckinProvider(  989): 	at com.motorola.android.server.checkin.CheckinProvider.insertEvents(CheckinProvider.java:798)
E/CheckinProvider(  989): 	at com.motorola.android.server.checkin.CheckinProvider.access$000(CheckinProvider.java:67)
E/CheckinProvider(  989): 	at com.motorola.android.server.checkin.CheckinProvider$EventInsertThread.run(CheckinProvider.java:909)
I/ActivityManager(  989): Start proc android.process.media for restart android.process.media: pid=4272 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/dalvikvm(  275): GC_EXPLICIT freed 44K, 48% free 9012K/17224K, paused 2ms+2ms, total 20ms
D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 16ms
D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=131208
D/WifiStateMachine(  989): processMsg: InitialState
D/WifiStateMachine(  989): processMsg: DefaultState
D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=131208
D/WifiStateMachine(  989): processMsg: InitialState
D/WifiStateMachine(  989): processMsg: DefaultState
D/WifiStateMachine(  989): handleMessage: X
D/WifiStateMachine(  989): handleMessage: E msg.what=131208
D/WifiStateMachine(  989): processMsg: InitialState
D/WifiStateMachine(  989): processMsg: DefaultState
D/WifiStateMachine(  989): handleMessage: X

```
