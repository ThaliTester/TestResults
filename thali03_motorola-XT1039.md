#### Test 503880196dc97cd_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4059): 
D/AndroidRuntime( 4059): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4059): CheckJNI is OFF
D/dalvikvm( 4059): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4059): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4059): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4059): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4059): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4059): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4059): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4059): failed to load memtrack module: -2
D/AndroidRuntime( 4059): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1020): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 4059
W/WindowManager( 1020): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1020): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4075 uid=10412 gids={50412, 3003, 3001, 3002}
D/AndroidRuntime( 4059): Shutting down VM
D/dalvikvm( 4059): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4075): Binding Chromium to main looper Looper (main, tid 1) {41fd89f8}
I/LibraryLoader( 4075): Expected native library version number "",actual native library version number ""
I/chromium( 4075): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4075): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1020): Message: 20
D/BluetoothManagerService( 1020): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42332998:true
I/Adreno-EGL( 4075): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4075): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4075): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4075): Local Branch: 
I/Adreno-EGL( 4075): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4075): Local Patches: NONE
I/Adreno-EGL( 4075): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4075): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4075): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4075): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4075): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4075): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4075): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4075): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4075): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4075): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4075): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4075): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4075): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4075): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4075): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4075): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4075): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4075): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4075): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4075): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4075): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4075): Enabling debug mode 0
,W/AwContents( 4075): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4075): showStatusIcon on inactive InputConnection,
,I/LaunchCheckinHandler( 1020): Displayed com.example.hello/.MainActivity,cp,ca,354
I/ActivityManager( 1020): Displayed com.example.hello/.MainActivity: +328ms (total +354ms)
,I/chromium( 4075): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 4075): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 4075): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4075): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41fdce80
,D/dalvikvm( 4075): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41fdce80
,D/jxcore_app_log( 4075): JniHelper::setJavaVM(0x41625fa8), pthread_self() = 1610752392
,D/JX-Cordova( 4075): jxcore cordova android initializing
,W/jxcore-log( 4075): Initializing JXcore engine
,W/jxcore-log( 4075): JXcore engine is ready
,W/jxcore-log( 4075): Starting JXcore engine
,W/jxcore-log( 4075): Platform android
W/jxcore-log( 4075): 
,W/jxcore-log( 4075): Process ARCH arm
W/jxcore-log( 4075): 
,I/jxcore-log( 4075): JXcore Cordova bridge is ready!
I/jxcore-log( 4075): 
,W/jxcore-log( 4075): JXcore engine is started
,E/jxcore-log( 4075): >> motorola-XT1039
E/jxcore-log( 4075): 
,I/jxcore-log( 4075): Total memory 893136896
I/jxcore-log( 4075): 
I/jxcore-log( 4075): Free memory 45940736
I/jxcore-log( 4075): 
I/jxcore-log( 4075): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4075): ,
,I/jxcore-log( 4075): userPath [ 'www' ]
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): Size 720 1184
I/jxcore-log( 4075): 
,I/jxcore-log( 4075): Screen Brightness 10
I/jxcore-log( 4075): 
,E/jxcore-log( 4075): Dummy Error Log.
E/jxcore-log( 4075): 
,I/jxcore-log( 4075): getBuffer is called!!!!
I/jxcore-log( 4075): 
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
,D/BluetoothManagerService( 1020): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1020): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@4233e600 mBinding = false
,W/Settings( 1296): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/XTWiFiOS( 1305): No entry in secure settings for enhanced location services: false
,D/BluetoothManagerService( 1020): Message: 2
,D/BluetoothManagerService( 1020): Sending off request.
,D/BluetoothAdapterState( 1756): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1756): Setting state to 13
I/BluetoothAdapterState( 1756): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 1756): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterProperties( 1756): onBluetoothDisable()
,I/BluetoothAdapterProperties( 1756): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothAdapterProperties( 1756): Scan Mode:21
,I/BluetoothAdapterState( 1756): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterState( 1756): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,D/BluetoothManagerService( 1020): Message: 60
,E/bt-btif ( 1756): bta_jv_rfcomm_stop_server
,E/BtOppRfcommListener( 1756): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,V/BluetoothFtpService:RfcommSocketAcceptThread( 1756): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/BluetoothManagerService( 1020): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,E/bt-btif ( 1756): bta_jv_rfcomm_stop_server
E/bt-btif ( 1756): bta_jv_rfcomm_stop_server
,E/bt-btif ( 1756): bta_jv_rfcomm_stop_server
,D/BluetoothManagerService( 1020): Bluetooth State Change Intent: 12 -> 13
,W/bt-btif ( 1756): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,D/btif_config_util( 1756): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
W/bt-l2cap( 1756): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1756): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothMapService( 1756): onReceive
,D/BluetoothMapService( 1756): STATE_TURNING_OFF removeTimeoutMsg:false
,D/BluetoothMapService( 1756): MAP Service closeService in
,I/ActivityManager( 1020): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=4133 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1296): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm(  276): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 22ms
W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 23ms
,D/WifiService( 1020): setWifiEnabled: false pid=4075, uid=10412
,E/WifiService( 1020): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService( 1020): New client listening to asynchronous messages
I/BtOppRfcommListener( 1756): stopping Accept Thread
I/BtOppRfcommListener( 1756): BluetoothSocket listen thread finished
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 19ms
,W/Settings( 1296): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiStateMachine( 1020): handleMessage: E msg.what=131084
D/WifiStateMachine( 1020): processMsg: ConnectedState
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): transitionTo: destState=WaitForP2pDisableState
,D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
,I/jxcore-log( 4075): ****TEST TOOK:  5218  ms ****
I/jxcore-log( 4075): 
I/jxcore-log( 4075): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4075): 
,D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
D/WifiStateMachine( 1020): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1020): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1020): Stopping DHCP and clearing IP
D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
W/XTWiFiOS( 1305): No entry in secure settings for enhanced location services: false
W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiP2pService( 1020): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings( 1296): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/CommandListener(  272): Clearing all IP addresses on wlan0
D/TCMD    (  484): NL - Read 60 bytes from update socket.
D/TCMD    (  484): NL - ignore NL message, type = 21
D/TCMD    (  484): Listening for incoming client connection request
D/WifiStateMachine( 1020): addressRemoved: 192.168.1.123/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1020): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1020): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/WifiMetrics( 1020): connected time updated 113067
D/WifiStateMachine( 1020): invokeExitMethods: ConnectModeState
D/WifiStateMachine( 1020): invokeExitMethods: DriverStartedState
,D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/ConnectivityService( 1020): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1020): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/WifiStateMachine( 1020): Unexpected BatchedScanResults :OK
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1020): Attempting to switch to mobile
D/ConnectivityService( 1020): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1020): Attempting to switch to ETHERNET
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
D/WifiStateMachine( 1020): invokeEnterMethods: WaitForP2pDisableState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131216
,D/WifiP2pService( 1020): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131216
D/WifiStateMachine( 1020): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): handleMessage: X
D/WifiP2pService( 1020): P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2pDisablingState
D/WifiP2pService( 1020): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): p2p socket connection lost
,D/WifiP2pService( 1020): P2pDisabledState
I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/WifiStateMachine( 1020): handleMessage: E msg.what=131205
,D/ConnectivityService( 1020): resetConnections(wlan0, 3)
D/NetUtils( 1020): android_net_utils_resetConnections in env=0x61214418 clazz=0x61800001 iface=wlan0 mask=0x3
D/WifiStateMachine( 1020): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1020): transitionTo: destState=SupplicantStoppingState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1020): invokeExitMethods: WaitForP2pDisableState
D/WifiStateMachine( 1020): invokeExitMethods: SupplicantStartedState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/WifiStateMachine( 1020): invokeEnterMethods: SupplicantStoppingState
D/WifiStateMachine( 1020): Stopping DHCP and clearing IP
D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1352): Read error: ssl=0x6326f940: I/O error during system call, Connection timed out
,V/NativeCrypto( 1352): SSL shutdown failed: ssl=0x6326f940: I/O error during system call, Broken pipe
W/ContextImpl( 4133): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothPbapService( 1756): action: android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothManagerService( 1020): Message: 20
,D/BluetoothManagerService( 1020): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42129c60:true
D/WifiP2pService( 1020): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/BluetoothManagerService( 1020): Message: 30
,W/ContextImpl( 4133): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
D/BluetoothManagerService( 1020): Message: 30
D/CommandListener(  272): Clearing all IP addresses on wlan0
,D/WifiStateMachine( 1020): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,W/ContextImpl( 4133): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/LocalBluetoothProfileManager( 4133): Adding local MAP profile
D/WifiStateMachine( 1020): stopping supplicant
,D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1020): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/WifiStateMachine( 1020): setWifiState: disabling
D/WifiStateMachine( 1020): handleMessage: X
W/bt-btif ( 1756): ag scb idx 1 not allocated
E/bt-btif ( 1756): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1756): L2CAP - PSM: 0x0019 not found for deregistration
I/bt_hwcfg( 1756): hw_epilog_process
W/bt-l2cap( 1756): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1756): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1756): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1756): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1756): L2CAP - PSM: 0x0017 not found for deregistration
D/BluetoothMap( 4133): Create BluetoothMap proxy object
D/BluetoothManagerService( 1020): Message: 30
I/SBar.NetworkController( 1082): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
W/XTWiFiOS( 1305): No entry in secure settings for enhanced location services: false
W/XTWiFiOS( 1305): Active network info is not available
E/XTCC-3.0.0.2(  485): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  485): [WwanPosMgr] handleConnectivtyStatusChange failed
E/XTCC-3.0.0.2(  485): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  485): [CSMgr] handleConnectivtyStatusChange failed
I/ModemStatsDSDetect( 1206): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1206): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1206): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1020): Attempting to switch to mobile
D/ConnectivityService( 1020): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1020): Attempting to switch to ETHERNET
,I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=false Wifi=(none) Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,W/ContextImpl( 4133): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
I/ModemStatsDSDetect( 1206): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1206): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1206): onReceive() - done, currentInetCondition=0
,D/BluetoothManagerService( 1020): Message: 30
,W/ContextImpl( 4133): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 4133): LocalBluetoothProfileManager construction complete
I/bt_hwcfg( 1756): hw_epilog_cback Opcode:0x0C03 Status: 0
I/bt_hci_bdroid( 1756): bt_hc_worker_thread exiting
D/bt_userial_mct( 1756): userial_close
I/bt_userial_mct( 1756): exiting userial_read_thread
D/bt_userial_mct( 1756): Leaving userial_evt_read_thread()
D/DockEventReceiver( 4133): finishStartingService: stopping service
,D/WifiService( 1020): New client listening to asynchronous messages
,D/BluetoothInputDevice( 4133): Proxy object connected
,D/HidProfile( 4133): Bluetooth service connected
,D/BluetoothPan( 4133): BluetoothPAN Proxy object connected
,D/PanProfile( 4133): Bluetooth service connected
V/BluetoothFtpReceiver( 1756): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
D/TCMD    (  484): NL - Read 1000 bytes from update socket.
D/TCMD    (  484): NL - message type is RTM_NEWLINK
D/TCMD    (  484): Listening for incoming client connection request
D/TCMD    (  484): NL - Read 68 bytes from update socket.
D/TCMD    (  484): NL - message type is RTM_NEWLINK
D/TCMD    (  484): Listening for incoming client connection request
D/TCMD    (  484): NL - Read 68 bytes from update socket.
D/TCMD    (  484): NL - message type is RTM_NEWLINK
D/TCMD    (  484): Listening for incoming client connection request
,D/BluetoothMap( 4133): Proxy object connected
D/MapProfile( 4133): Bluetooth service connected
,D/BluetoothMap( 4133): getConnectedDevices()
I/wpa_supplicant( 1152): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/Tethering( 1020): InitialState.processMessage what=4
D/WifiStateMachine( 1020): handleMessage: E msg.what=147460
D/WifiStateMachine( 1020): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  274): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  274):  STA Disconnected !!
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
,I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/Tethering( 1020): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/AuthorizationBluetoothService( 1352): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/Tethering( 1020): sendTetherStateChangedBroadcast 0, 0, 0
,D/BluetoothMap( 4133): Bluetooth is Not enabled
,I/ActivityManager( 1020): Killing 3829:com.android.calendar/u0a7 (adj 15): empty #9
D/WifiStateMachine( 1020): handleMessage: E msg.what=131101
D/WifiStateMachine( 1020): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): handleMessage: X
W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/wpa_supplicant( 1152): eap_proxy Deinitialzed
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1 38:f8:89
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 1 38:f8:89
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2 64:7c:34
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 2 64:7c:34
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3 06:7c:34
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 3 06:7c:34
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4 fc:94:e3
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 4 fc:94:e3
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5 f4:dc:f9
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 5 f4:dc:f9
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6 fe:94:e3
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 6 fe:94:e3
,D/WifiStateMachine( 1020): handleMessage: E msg.what=196614
D/WifiStateMachine( 1020): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): handleMessage: X
,D/TCMD    (  484): NL - Read 1000 bytes from update socket.
D/TCMD    (  484): NL - message type is RTM_NEWLINK
,D/TCMD    (  484): Listening for incoming client connection request
I/wpa_supplicant( 1152): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  274): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  274):  Wpa Supplicant Exiting !!
D/MDMCTBK (  274): wifi_wait_on_socket: Exiting monitor thread
,D/MDMCTBK (  274): wifi_close_sockets: Close Wifi socket
D/WifiStateMachine( 1020): handleMessage: E msg.what=147458
D/WifiStateMachine( 1020): processMsg: SupplicantStoppingState
,D/WifiStateMachine( 1020): Supplicant connection lost
,D/MDMCTBK (  274): wifi_close_sockets: Exit
,D/BTSNOOP-DISP( 1756): btsnoop_close
I/bt_vendor( 1756): cleanup
I/bt_hwcfg( 1756): Starting hciattach daemon
,I/bt_hwcfg( 1756): try to set false
I/GKI_LINUX( 1756): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 1756): GKI_exit_task: GKI_exit_task 0 done
,I/GKI_LINUX( 1756): GKI_destroy_task: GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 1756): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 1756): Received stop request...Stopping profile...
D/BluetoothHeadset( 1280): Proxy object disconnected
D/BluetoothHeadset( 1280): Proxy object disconnected
D/BluetoothHeadset( 1020): Proxy object disconnected
,D/BluetoothHeadset( 1280): Proxy object disconnected
,D/A2dpService( 1756): Received stop request...Stopping profile...
,D/A2dpStateMachine( 1756): Exit Disconnected: -1
,D/BluetoothA2dp( 1020): Proxy object disconnected
,D/BluetoothAdapterService( 1756): Profile still running: com.android.bluetooth.hdp.HealthService
,D/HidService( 1756): Received stop request...Stopping profile...
D/BluetoothInputDevice( 4133): Proxy object disconnected
,D/HidProfile( 4133): Bluetooth service disconnected
,W/BluetoothHeadsetServiceJni( 1756): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 1756): Cleaning up Bluetooth Handsfree callback object
,D/BluetoothAdapterService( 1756): Profile still running: com.android.bluetooth.hdp.HealthService
,I/GKI_LINUX( 1756): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
,D/BluetoothAdapterState( 1756): Stopping profile services that were post enabled
I/GKI_LINUX( 1756): GKI_exit_task: GKI_exit_task 2 done
I/GKI_LINUX( 1756): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BluetoothAdapterService( 1756): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 1756): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 1756): cleanup: HH disabling or disabled already, status = 0
,W/BluetoothHidServiceJni( 1756): Cleaning up Bluetooth GID callback object
,D/HealthService( 1756): Received stop request...Stopping profile...
,D/PanService( 1756): Received stop request...Stopping profile...
D/BluetoothTethering( 1020): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering( 1020): attempted to stop reverse tether with nothing tethered
D/BluetoothTethering( 1020): Disconnect CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@4287d718
,D/BluetoothTethering( 1020): got CMD_CHANNEL_DISCONNECTED
,D/BluetoothPan( 1020): BluetoothPAN Proxy object disconnected
D/BluetoothPan( 4133): BluetoothPAN Proxy object disconnected
,D/PanProfile( 4133): Bluetooth service disconnected
D/BtGatt.DebugUtils( 1756): handleDebugAction() action=null
D/BtGatt.GattService( 1756): Received stop request...Stopping profile...
,D/BtGatt.GattService( 1756): stop()
D/BluetoothMapService( 1756): Received stop request...Stopping profile...
,D/BluetoothMapService( 1756): stop()
,D/BluetoothMapService( 1756): MAP Service closeService in
,D/WifiStateMachine( 1020): setWifiState: disabled
D/BluetoothMap( 4133): Proxy object disconnected
D/MapProfile( 4133): Bluetooth service disconnected
D/BluetoothAdapterService( 1756): Profile still running: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothHealthServiceJni( 1756): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 1756): Cleaning up Bluetooth Health object
D/BluetoothAdapterService( 1756): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 1756): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 1756): Cleaning up Bluetooth PAN callback object
D/WifiStateMachine( 1020): transitionTo: destState=InitialState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1020): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
D/WifiStateMachine( 1020): invokeEnterMethods: InitialState
D/BluetoothAdapterService( 1756): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/BluetoothMapService( 1756): cleanup()
,D/BluetoothMapService( 1756): MAP Service closeService in
,W/XTWiFiOS( 1305): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1082): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
D/BluetoothAdapterState( 1756): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1756): Setting state to 10
I/BluetoothAdapterState( 1756): Bluetooth adapter state changed: 13-> 10
,D/BluetoothAdapterService( 1756): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1020): Message: 60
D/BluetoothManagerService( 1020): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1020): Broadcasting onBluetoothStateChange(false) to 10 receivers.
,D/BluetoothHeadset( 1280): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 1756): Entering OffState
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1305): Active network info is not available
E/XTCC-3.0.0.2(  485): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  485): [WwanPosMgr] handleConnectivtyStatusChange failed
,D/BluetoothHeadset( 1280): onBluetoothStateChange: up=false
,D/BluetoothPan( 1020): onBluetoothStateChange on: false
,D/BluetoothHeadset( 1280): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1020): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1020): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 4133): onBluetoothStateChange: up=false
,D/BluetoothPan( 4133): onBluetoothStateChange on: false
,D/BluetoothMap( 4133): onBluetoothStateChange: up=false
,W/Settings( 1248): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BluetoothPbap( 4133): onBluetoothStateChange: up=false
,D/BluetoothManagerService( 1020): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService( 1020): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/BluetoothManagerService( 1020): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@4233e600 mBinding = false
,D/BluetoothManagerService( 1020): Sending unbind request.
,D/BluetoothManagerService( 1020): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter( 1082): 1108642296: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapterService( 1756): Cleaning up adapter native....
,I/GKI_LINUX( 1756): gki_task_entry: gki_task task_id=1 [BTIF] terminating
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.sendDeviceAttachIntent:820 com.motorola.authentication.MotAuthenticationService.access$1300:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:575 
I/GKI_LINUX( 1756): GKI_exit_task: GKI_exit_task 1 done
I/GKI_LINUX( 1756): GKI_destroy_task: GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 1756): cleanupNative: return from cleanup
D/BluetoothAdapterService( 1756): Done cleaning up adapter native....
D/AndroidRuntime( 4167): 
D/AndroidRuntime( 4167): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/BluetoothAdapterService(1107170712)( 1756): ****onDestroy()********
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.handleKeepDeviceUnlockRequest:732 com.motorola.authentication.MotAuthenticationService.access$1500:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:563 
D/BtGatt.GattService( 1756): cleanup()
W/bt-btif ( 1756): GATTC Module not enabled/already disabled
W/bt-btif ( 1756): GATTS Module not enabled/already disabled
D/AndroidRuntime( 4167): CheckJNI is OFF
D/BluetoothAdapter( 1248): 1111250536: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1248): 1111250536: getState() :  mService = null. Returning STATE_OFF
E/XTCC-3.0.0.2(  485): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  485): [CSMgr] handleConnectivtyStatusChange failed
,W/ContextImpl( 4133): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/dalvikvm( 4167): Trying to load lib libjavacore.so 0x0
D/DockEventReceiver( 4133): finishStartingService: stopping service
D/Checkin ( 2278): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
D/Checkin ( 2278): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
D/dalvikvm( 4167): Added shared lib libjavacore.so 0x0
D/BluetoothAdapter( 4133): 1107224248: getState() :  mService = null. Returning STATE_OFF
D/dalvikvm( 4167): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4167): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4167): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
V/BluetoothFtpReceiver( 1756): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 1756): BluetoothFtpReceiver Stop Service
V/BluetoothFtpService( 1756): Ftp Service onDestroy
V/BluetoothFtpService( 1756): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 1756): Shutdown
,D/AuthorizationBluetoothService( 1352): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager( 1020): Killing 3513:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1020): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.ConnectedUnlockReceiver: pid=4179 uid=10016 gids={50016, 3002}
,D/dalvikvm( 4167): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,D/Checkin ( 4179): publish the event [tag = DEVICE_AUTH_STATS_L2 event name = DEVAUTH_CONNECT]
I/ActivityManager( 1020): Killing 3926:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/rmt_storage(  363): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6ff01d0
I/rmt_storage(  363): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  363): wakelock acquired: 1, error no: 42
,I/rmt_storage(  363): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1224802584)
,I/rmt_storage(  363): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  363): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  363): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1224802584) wakelock released: 1, error no: 0
I/rmt_storage(  363): 
,I/rmt_storage(  363): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6ff01d0
,E/memtrack( 4167): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4167): failed to load memtrack module: -2
,D/Checkin ( 2278): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2278): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/AndroidRuntime( 4167): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1020): Force stopping com.example.hello appid=10412 user=-1: uninstall pkg
,I/ActivityManager( 1020): Killing 4075:com.example.hello/u0a412 (adj 0): stop com.example.hello
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1020):   Force finishing activity ActivityRecord{42887028 u0 com.example.hello/.MainActivity t3}
,I/WindowState( 1020): WIN DEATH: Window{421be998 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1020): Client connection lost with reason: 4
,W/PackageSettings( 1020): Skipping PackageSetting{42299b98 com.test.thalitest/10411} due to missing metadata
,D/TCMD    (  484): NL - Read 444 bytes from update socket.
D/TCMD    (  484): NL - ignore NL message, type = 17
D/TCMD    (  484): Listening for incoming client connection request
,D/NetlinkEvent(  272): Unexpected netlink message. type=0x11
W/Netd    (  272): No subsystem found in netlink event
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
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
,E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/ActivityManager( 1020): Force stopping com.example.hello appid=10412 user=0: pkg removed
W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/TCMD    (  484): NL - Read 1000 bytes from update socket.
D/TCMD    (  484): NL - message type is RTM_NEWLINK
,D/TCMD    (  484): Listening for incoming client connection request
,D/dalvikvm( 2312): GC_EXPLICIT freed 2677K, 44% free 9777K/17224K, paused 5ms+3ms, total 38ms
,D/dalvikvm( 1323): GC_EXPLICIT freed 3241K, 33% free 11594K/17224K, paused 2ms+4ms, total 38ms
,I/OtaApp  ( 1568): [info] > Updatetime from metadata: 10
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,I/Launcher( 1323): Deferring update until onResume
,I/LatinIME:LogUtils( 1222): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/LatinIME:LogUtils( 1222): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 1020):   Scheme: "sms"
,I/ActivityManager( 1020): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4204 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
W/GeofencerStateMachine( 1248): Ignoring removeGeofence because network location is disabled.
D/OtaApp  ( 1568): [debug] > cancelling the previous pending intent set for install later
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
I/OtaApp  ( 1568): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
D/dalvikvm( 2278): GC_EXPLICIT freed 5181K, 44% free 9663K/17224K, paused 2ms+17ms, total 52ms
,I/LatinIME:LogUtils( 1222): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1448460763
,D/NetlinkEvent(  272): Unexpected netlink message. type=0x11
W/Netd    (  272): No subsystem found in netlink event
D/TCMD    (  484): NL - Read 444 bytes from update socket.
D/TCMD    (  484): NL - ignore NL message, type = 17
D/TCMD    (  484): Listening for incoming client connection request
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
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
D/OtaApp  ( 1568): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/Checkin ( 2278): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
I/dalvikvm( 1020): Jit: resizing JitTable from 8192 to 16384
,D/dalvikvm( 1020): GC_EXPLICIT freed 2859K, 14% free 18129K/21076K, paused 6ms+11ms, total 142ms
,D/dalvikvm( 1020): WAIT_FOR_CONCURRENT_GC blocked 109ms
,I/Launcher( 1323): Deferring update until onResume
,D/OtaApp  ( 1568): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
,D/dalvikvm( 1352): GC_EXPLICIT freed 1438K, 39% free 10581K/17224K, paused 2ms+5ms, total 36ms
,W/InputMethodManagerService( 1020): Got RemoteException sending setActive(false) notification to pid 4075 uid 10412
,W/Binder  ( 1222): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1222): java.lang.NullPointerException
W/Binder  ( 1222): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1222): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1222): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1222): 	at dalvik.system.NativeStart.run(Native Method)
,I/LatinIME:LogUtils( 1222): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1448460763
D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/BackupManagerService( 1020): removePackageParticipantsLocked: uid=10412 #1
,D/VoicemailCleanupService( 4204): Cleaning up data for package: com.example.hello
,I/InternalIcingCorporaPro( 2312): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/ActivityManager( 1020): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4225 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,W/ContextImpl( 4225): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,D/PackageBroadcastService( 1420): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1420): Clearing selected account for com.example.hello
,I/LocationSettingsChecker( 1420): Removing dialog suppression flag for package com.example.hello
,D/ChimeraCfgMgr( 1420): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1420): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1420): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1420): Module APK com.google.android.play.games already loaded
,D/Checkin ( 2278): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,E/NetworkScheduler.SchedulerReceiver( 1352): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1352): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1420): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1420): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1420): 0 metrics were deleted when clearing package com.example.hello.
,D/gH_CompatibleDatabase( 1420): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/PeopleContactsSync( 1420): CP2 sync disabled
,I/Icing   ( 1420): doRemovePackageData com.example.hello
,D/gH_CompatibleDatabase( 1420): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1420): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
I/dalvikvm( 3588): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3588): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3588): VFY: replacing opcode 0x6e at 0x0013
,D/gH_CompatibleDatabase( 1420): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1420): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1420): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1420): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1420): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1420): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1420): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager( 1020): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4247 uid=10058 gids={50058}
,I/ActivityManager( 1020): Killing 3897:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm( 1020): GC_EXPLICIT freed 752K, 15% free 18010K/21076K, paused 8ms+17ms, total 329ms
I/InternalIcingCorporaPro( 2312): UpdateCorporaTask done [took 152 ms] updated apps [took 151 ms] 
,I/ActivityManager( 1020): Killing 4133:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiService( 1020): Client connection lost with reason: 4
,D/Documents( 4247): Loading roots for com.android.providers.downloads.documents
,I/ActivityManager( 1020): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4261 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/AndroidRuntime( 4167): Shutting down VM
,I/ActivityManager( 1020): Killing 1756:com.android.bluetooth/1002 (adj 15): empty #9
,D/dalvikvm( 4167): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1020): Killing 4179:com.motorola.deviceauthenticator/u0a16 (adj 15): empty #9
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4204): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/dalvikvm( 4261): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fda588, skipping init
I/openssl ( 4261): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4261): Crypto mode 0 already enabled
D/Documents( 4247): Loading roots for com.android.externalstorage.documents
,I/ActivityManager( 1020): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4277 uid=10020 gids={50020, 1028, 1015, 1023}
,I/ActivityManager( 1020): Killing 4204:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ExternalStorage( 4277): After updating volumes, found 1 active roots
,D/Documents( 4247): Updating roots due to change at content://com.android.externalstorage.documents/root
,D/Documents( 4247): Loading roots for com.android.providers.media.documents
,D/Documents( 4247): Loading roots for com.google.android.apps.docs.storage
,D/Documents( 4247): Update found 7 roots in 186ms
,D/Documents( 4247): Used cached roots for com.android.providers.downloads.documents
,D/Documents( 4247): Loading roots for com.android.externalstorage.documents
,D/Documents( 4247): Used cached roots for com.android.providers.media.documents
D/Documents( 4247): Used cached roots for com.google.android.apps.docs.storage
,D/Documents( 4247): Update found 7 roots in 6ms
,I/MDMCTBK (  274): NetlinkHandler, wifiStateChanged 0
I/MDMCTBK (  274): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
,I/MDMCTBK (  274): checkDefaultInst, pid match
,D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131208
D/WifiStateMachine( 1020): processMsg: InitialState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131208
D/WifiStateMachine( 1020): processMsg: InitialState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131208
D/WifiStateMachine( 1020): processMsg: InitialState
D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): handleMessage: X
,E/SQLiteLog( 1020): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error

```
