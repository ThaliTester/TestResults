#### Test 50388019aa1a16d_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 3896): 
D/AndroidRuntime( 3896): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3896): CheckJNI is OFF
D/dalvikvm( 3896): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3896): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3896): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3896): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3896): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3896): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3896): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3896): failed to load memtrack module: -2
D/AndroidRuntime( 3896): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1021): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3896
W/WindowManager( 1021): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1021): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3912 uid=10388 gids={50388, 3003, 3001, 3002}
D/AndroidRuntime( 3896): Shutting down VM
D/dalvikvm( 3896): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 2ms
W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3912): Binding Chromium to main looper Looper (main, tid 1) {41f045c0}
I/LibraryLoader( 3912): Expected native library version number "",actual native library version number ""
I/chromium( 3912): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3912): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1021): Message: 20
D/BluetoothManagerService( 1021): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42723010:true
I/Adreno-EGL( 3912): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3912): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3912): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3912): Local Branch: 
I/Adreno-EGL( 3912): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3912): Local Patches: NONE
I/Adreno-EGL( 3912): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3912): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3912): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3912): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3912): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3912): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3912): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3912): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3912): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3912): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3912): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3912): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3912): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3912): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3912): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3912): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3912): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3912): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3912): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3912): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3912): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3912): Enabling debug mode 0
,W/AwContents( 3912): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3912): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1021): Displayed com.example.hello/.MainActivity,cp,ca,315
I/ActivityManager( 1021): Displayed com.example.hello/.MainActivity: +293ms (total +316ms)
,I/chromium( 3912): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 3912): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 3912): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3912): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41f091c8
,D/dalvikvm( 3912): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41f091c8
D/jxcore_app_log( 3912): JniHelper::setJavaVM(0x41556fa8), pthread_self() = 1610203016
,D/JX-Cordova( 3912): jxcore cordova android initializing
,W/jxcore-log( 3912): Initializing JXcore engine
,W/jxcore-log( 3912): JXcore engine is ready
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,W/jxcore-log( 3912): Starting JXcore engine
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
,W/jxcore-log( 3912): Platform android
W/jxcore-log( 3912): 
,W/jxcore-log( 3912): Process ARCH arm
W/jxcore-log( 3912): 
,I/jxcore-log( 3912): JXcore Cordova bridge is ready!
I/jxcore-log( 3912): 
,W/jxcore-log( 3912): JXcore engine is started
,E/jxcore-log( 3912): >> motorola-XT1039
E/jxcore-log( 3912): 
,I/jxcore-log( 3912): Total memory 893136896
I/jxcore-log( 3912): 
I/jxcore-log( 3912): Free memory 43069440
I/jxcore-log( 3912): 
,I/jxcore-log( 3912): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3912): 
,I/jxcore-log( 3912): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3912): 
,I/jxcore-log( 3912): userPath [ 'www' ]
I/jxcore-log( 3912): 
,I/jxcore-log( 3912): Size 720 1184
I/jxcore-log( 3912): 
,I/jxcore-log( 3912): Screen Brightness 10
I/jxcore-log( 3912): 
,E/jxcore-log( 3912): Dummy Error Log.
E/jxcore-log( 3912): 
,I/jxcore-log( 3912): getBuffer is called!!!!
I/jxcore-log( 3912): 
,V/AlarmManager( 1021): sending alarm Alarm{421442f0 type 3 android}
,D/BluetoothManagerService( 1021): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1021): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@42273b78 mBinding = false
,W/Settings( 1265): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1275): No entry in secure settings for enhanced location services: false
,D/BluetoothManagerService( 1021): Message: 2
,D/BluetoothManagerService( 1021): Sending off request.
,D/BluetoothAdapterState( 1780): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1780): Setting state to 13
,I/BluetoothAdapterState( 1780): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 1780): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterProperties( 1780): onBluetoothDisable()
,I/BluetoothAdapterState( 1780): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,I/BluetoothAdapterProperties( 1780): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothAdapterProperties( 1780): Scan Mode:21
,D/BluetoothAdapterState( 1780): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 1780): bta_jv_rfcomm_stop_server
,V/BluetoothFtpService:RfcommSocketAcceptThread( 1780): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/BtOppRfcommListener( 1780): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/BluetoothManagerService( 1021): Message: 60
,D/BluetoothManagerService( 1021): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
E/bt-btif ( 1780): bta_jv_rfcomm_stop_server
,E/bt-btif ( 1780): bta_jv_rfcomm_stop_server
,E/bt-btif ( 1780): bta_jv_rfcomm_stop_server
,D/BluetoothManagerService( 1021): Bluetooth State Change Intent: 12 -> 13
,W/bt-btif ( 1780): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,W/bt-l2cap( 1780): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1780): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothMapService( 1780): onReceive
,D/BluetoothMapService( 1780): STATE_TURNING_OFF removeTimeoutMsg:false
,D/BluetoothMapService( 1780): MAP Service closeService in
,D/btif_config_util( 1780): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
I/ActivityManager( 1021): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3976 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,W/Settings( 1265): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/WifiService( 1021): New client listening to asynchronous messages
D/WifiService( 1021): setWifiEnabled: false pid=3912, uid=10388
,E/WifiService( 1021): Invoking mWifiStateMachine.setWifiEnabled
I/BtOppRfcommListener( 1780): stopping Accept Thread
I/BtOppRfcommListener( 1780): BluetoothSocket listen thread finished
,D/WifiStateMachine( 1021): handleMessage: E msg.what=131084
,W/Settings( 1265): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiStateMachine( 1021): processMsg: ConnectedState
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
,I/jxcore-log( 3912): ****TEST TOOK:  5189  ms ****
I/jxcore-log( 3912): 
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
,I/jxcore-log( 3912): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3912): 
D/WifiStateMachine( 1021): transitionTo: destState=WaitForP2pDisableState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiStateMachine( 1021): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1021): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1021): Stopping DHCP and clearing IP
D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 true
W/Settings( 1265): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/XTWiFiOS( 1275): No entry in secure settings for enhanced location services: false
W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiP2pService( 1021): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  271): Clearing all IP addresses on wlan0
D/TCMD    (  469): NL - Read 60 bytes from update socket.
D/TCMD    (  469): NL - ignore NL message, type = 21
D/TCMD    (  469): Listening for incoming client connection request
,W/ContextImpl( 3976): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/WifiStateMachine( 1021): addressRemoved: 192.168.1.123/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1021): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1021): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/WifiMetrics( 1021): connected time updated 100020
D/ConnectivityService( 1021): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/WifiStateMachine( 1021): invokeExitMethods: ConnectModeState
D/WifiStateMachine( 1021): invokeExitMethods: DriverStartedState
,D/ConnectivityService( 1021): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/BluetoothPbapService( 1780): action: android.bluetooth.adapter.action.STATE_CHANGED
D/ConnectivityService( 1021): Attempting to switch to mobile
D/ConnectivityService( 1021): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1021): Attempting to switch to ETHERNET
D/Checkin ( 1021): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/BluetoothManagerService( 1021): Message: 20
D/BluetoothManagerService( 1021): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@428fa3b8:true
E/WifiStateMachine( 1021): Unexpected BatchedScanResults :OK
I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/BluetoothManagerService( 1021): Message: 30
,D/ConnectivityService( 1021): resetConnections(wlan0, 3)
D/NetUtils( 1021): android_net_utils_resetConnections in env=0x5fd79288 clazz=0x61d00001 iface=wlan0 mask=0x3
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
,D/WifiStateMachine( 1021): invokeEnterMethods: WaitForP2pDisableState
D/WifiP2pService( 1021): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl( 3976): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
D/WifiP2pService( 1021): P2pDisablingState
D/WifiP2pService( 1021): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): p2p socket connection lost
,D/WifiP2pService( 1021): P2pDisabledState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131216
D/WifiStateMachine( 1021): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131216
D/WifiStateMachine( 1021): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
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
D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 true
,D/BluetoothManagerService( 1021): Message: 30
,W/ContextImpl( 3976): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 3976): Adding local MAP profile
D/BluetoothMap( 3976): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1021): Message: 30
,W/ContextImpl( 3976): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/BluetoothManagerService( 1021): Message: 30
,W/ContextImpl( 3976): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 3976): LocalBluetoothProfileManager construction complete
V/NativeCrypto( 1374): Read error: ssl=0x627b6d48: I/O error during system call, Connection timed out
V/NativeCrypto( 1374): SSL shutdown failed: ssl=0x627b6d48: I/O error during system call, Broken pipe
,D/WifiP2pService( 1021): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  271): Clearing all IP addresses on wlan0
,D/DockEventReceiver( 3976): finishStartingService: stopping service
,D/WifiStateMachine( 1021): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1021): stopping supplicant
,D/WifiStateMachine( 1021): setWifiState: disabling
D/WifiStateMachine( 1021): handleMessage: X
D/Checkin ( 1021): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.NetworkController( 1084): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
W/XTWiFiOS( 1275): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=false
W/XTWiFiOS( 1275): Active network info is not available
E/XTCC-3.0.0.2(  472): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  472): [WwanPosMgr] handleConnectivtyStatusChange failed
I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=false Wifi=(none) Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/ModemStatsDSDetect( 1296): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1296): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1296): onReceive() - done, currentInetCondition=0
,E/XTCC-3.0.0.2(  472): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  472): [CSMgr] handleConnectivtyStatusChange failed
D/ConnectivityService( 1021): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1021): Attempting to switch to mobile
D/ConnectivityService( 1021): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1021): Attempting to switch to ETHERNET
,I/wpa_supplicant( 1175): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
W/bt-btif ( 1780): ag scb idx 1 not allocated
E/bt-btif ( 1780): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1780): L2CAP - PSM: 0x0019 not found for deregistration
D/TCMD    (  469): NL - Read 1000 bytes from update socket.
D/TCMD    (  469): NL - message type is RTM_NEWLINK
D/TCMD    (  469): Listening for incoming client connection request
D/TCMD    (  469): NL - Read 68 bytes from update socket.
D/TCMD    (  469): NL - message type is RTM_NEWLINK
D/TCMD    (  469): Listening for incoming client connection request
D/TCMD    (  469): NL - Read 68 bytes from update socket.
D/TCMD    (  469): NL - message type is RTM_NEWLINK
,D/TCMD    (  469): Listening for incoming client connection request
W/bt-l2cap( 1780): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1780): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1780): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1780): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1780): L2CAP - PSM: 0x0017 not found for deregistration
,I/bt_hwcfg( 1780): hw_epilog_process
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=false
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
D/Tethering( 1021): InitialState.processMessage what=4
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
D/WifiStateMachine( 1021): handleMessage: E msg.what=147460
D/WifiStateMachine( 1021): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1021): processMsg: DefaultState
,D/Tethering( 1021): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/WifiService( 1021): New client listening to asynchronous messages
D/WifiStateMachine( 1021): handleMessage: X
D/Tethering( 1021): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1021): handleMessage: E msg.what=131101
D/WifiStateMachine( 1021): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
I/ModemStatsDSDetect( 1296): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1296): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1296): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
,I/bt_hwcfg( 1780): hw_epilog_cback Opcode:0x0C03 Status: 0
,I/bt_hci_bdroid( 1780): bt_hc_worker_thread exiting
D/bt_userial_mct( 1780): userial_close
,I/wpa_supplicant( 1175): eap_proxy Deinitialzed
I/bt_userial_mct( 1780): exiting userial_read_thread
D/bt_userial_mct( 1780): Leaving userial_evt_read_thread()
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1 64:7c:34
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 1 64:7c:34
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2 38:f8:89
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 2 38:f8:89
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3 64:7c:34
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 3 64:7c:34
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4 fc:94:e3
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 4 fc:94:e3
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5 0c:bd:51
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 5 0c:bd:51
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6 06:7c:34
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 6 06:7c:34
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7 10:9a:dd
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 7 10:9a:dd
,D/BluetoothInputDevice( 3976): Proxy object connected
,D/HidProfile( 3976): Bluetooth service connected
V/BluetoothFtpReceiver( 1780): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothPan( 3976): BluetoothPAN Proxy object connected
D/PanProfile( 3976): Bluetooth service connected
D/BluetoothMap( 3976): Proxy object connected
,D/MapProfile( 3976): Bluetooth service connected
,D/BluetoothMap( 3976): getConnectedDevices()
,D/BluetoothMap( 3976): Bluetooth is Not enabled
,I/ActivityManager( 1021): Killing 3708:com.android.calendar/u0a7 (adj 15): empty #9
,D/AuthorizationBluetoothService( 1374): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/TCMD    (  469): NL - Read 1000 bytes from update socket.
D/TCMD    (  469): NL - message type is RTM_NEWLINK
,D/TCMD    (  469): Listening for incoming client connection request
,I/wpa_supplicant( 1175): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  274): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  274):  Wpa Supplicant Exiting !!
D/MDMCTBK (  274): wifi_wait_on_socket: Exiting monitor thread
,D/MDMCTBK (  274): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  274): wifi_close_sockets: Exit
D/WifiStateMachine( 1021): handleMessage: E msg.what=147458
D/WifiStateMachine( 1021): processMsg: SupplicantStoppingState
,D/WifiStateMachine( 1021): Supplicant connection lost
,D/WifiStateMachine( 1021): setWifiState: disabled
,W/XTWiFiOS( 1275): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1275): Active network info is not available
E/XTCC-3.0.0.2(  472): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  472): [WwanPosMgr] handleConnectivtyStatusChange failed
E/XTCC-3.0.0.2(  472): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  472): [CSMgr] handleConnectivtyStatusChange failed
I/SBar.NetworkController( 1084): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1021): transitionTo: destState=InitialState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1021): invokeExitMethods: SupplicantStoppingState
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
,D/WifiStateMachine( 1021): invokeEnterMethods: InitialState
,W/Settings( 1213): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AndroidRuntime( 4011): 
D/AndroidRuntime( 4011): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4011): CheckJNI is OFF
,D/dalvikvm( 4011): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4011): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4011): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4011): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4011): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/BTSNOOP-DISP( 1780): btsnoop_close
I/bt_vendor( 1780): cleanup
I/bt_hwcfg( 1780): Starting hciattach daemon
,I/bt_hwcfg( 1780): try to set false
,I/GKI_LINUX( 1780): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 1780): GKI_exit_task: GKI_exit_task 0 done
,I/GKI_LINUX( 1780): GKI_destroy_task: GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 1780): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 1780): Received stop request...Stopping profile...
,D/BluetoothHeadset( 1021): Proxy object disconnected
D/BluetoothHeadset( 1253): Proxy object disconnected
D/BluetoothHeadset( 1253): Proxy object disconnected
D/BluetoothHeadset( 1253): Proxy object disconnected
,D/A2dpService( 1780): Received stop request...Stopping profile...
,D/A2dpStateMachine( 1780): Exit Disconnected: -1
D/BluetoothA2dp( 1021): Proxy object disconnected
,D/BluetoothAdapterService( 1780): Profile still running: com.android.bluetooth.hdp.HealthService
,D/HidService( 1780): Received stop request...Stopping profile...
,D/BluetoothInputDevice( 3976): Proxy object disconnected
,D/HidProfile( 3976): Bluetooth service disconnected
W/BluetoothHeadsetServiceJni( 1780): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 1780): Cleaning up Bluetooth Handsfree callback object
,D/BluetoothAdapterState( 1780): Stopping profile services that were post enabled
,D/HealthService( 1780): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 1780): Profile still running: com.android.bluetooth.hdp.HealthService
I/GKI_LINUX( 1780): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 1780): GKI_exit_task: GKI_exit_task 2 done
,I/GKI_LINUX( 1780): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
D/PanService( 1780): Received stop request...Stopping profile...
D/BluetoothTethering( 1021): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering( 1021): attempted to stop reverse tether with nothing tethered
D/BluetoothTethering( 1021): Disconnect CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@42747af0
,D/BluetoothTethering( 1021): got CMD_CHANNEL_DISCONNECTED
,D/BluetoothPan( 1021): BluetoothPAN Proxy object disconnected
D/BluetoothPan( 3976): BluetoothPAN Proxy object disconnected
D/BluetoothAdapterService( 1780): Profile still running: com.android.bluetooth.hdp.HealthService
D/PanProfile( 3976): Bluetooth service disconnected
,D/BtGatt.DebugUtils( 1780): handleDebugAction() action=null
D/BtGatt.GattService( 1780): Received stop request...Stopping profile...
,D/BtGatt.GattService( 1780): stop()
W/BluetoothHidServiceJni( 1780): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 1780): cleanup: HH disabling or disabled already, status = 0
,W/BluetoothHidServiceJni( 1780): Cleaning up Bluetooth GID callback object
,D/BluetoothMapService( 1780): Received stop request...Stopping profile...
D/BluetoothMapService( 1780): stop()
,D/BluetoothMapService( 1780): MAP Service closeService in
D/BluetoothMap( 3976): Proxy object disconnected
,D/MapProfile( 3976): Bluetooth service disconnected
D/dalvikvm( 4011): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,D/BluetoothAdapterService( 1780): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 1780): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 1780): Cleaning up Bluetooth Health object
D/BluetoothAdapterService( 1780): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 1780): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 1780): Cleaning up Bluetooth PAN callback object
,D/BluetoothAdapterService( 1780): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterState( 1780): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothMapService( 1780): cleanup()
D/BluetoothMapService( 1780): MAP Service closeService in
D/BluetoothAdapterProperties( 1780): Setting state to 10
I/BluetoothAdapterState( 1780): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 1780): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1021): Message: 60
D/BluetoothManagerService( 1021): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
,D/BluetoothManagerService( 1021): Broadcasting onBluetoothStateChange(false) to 10 receivers.
,D/BluetoothHeadset( 1253): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 1780): Entering OffState
D/BluetoothA2dp( 1021): onBluetoothStateChange: up=false
,D/BluetoothPan( 1021): onBluetoothStateChange on: false
,D/BluetoothHeadset( 1253): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1253): onBluetoothStateChange: up=false
,D/BluetoothPbap( 3976): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1021): onBluetoothStateChange: up=false
,D/BluetoothPan( 3976): onBluetoothStateChange on: false
D/BluetoothInputDevice( 3976): onBluetoothStateChange: up=false
,D/BluetoothMap( 3976): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1021): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService( 1021): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/BluetoothManagerService( 1021): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@42273b78 mBinding = false
,D/BluetoothManagerService( 1021): Sending unbind request.
,D/BluetoothManagerService( 1021): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapterService( 1780): Cleaning up adapter native....
,I/GKI_LINUX( 1780): gki_task_entry: gki_task task_id=1 [BTIF] terminating
,D/BluetoothAdapter( 1084): 1107793688: getState() :  mService = null. Returning STATE_OFF
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.sendDeviceAttachIntent:820 com.motorola.authentication.MotAuthenticationService.access$1300:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:575 
I/GKI_LINUX( 1780): GKI_exit_task: GKI_exit_task 1 done
,I/GKI_LINUX( 1780): GKI_destroy_task: GKI_shutdown(): task [BTIF] terminated
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.handleKeepDeviceUnlockRequest:732 com.motorola.authentication.MotAuthenticationService.access$1500:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:563 
I/BluetoothServiceJni( 1780): cleanupNative: return from cleanup
D/BluetoothAdapterService( 1780): Done cleaning up adapter native....
,D/BluetoothAdapterService(1106327080)( 1780): ****onDestroy()********
,W/ContextImpl( 3976): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/BtGatt.GattService( 1780): cleanup()
W/bt-btif ( 1780): GATTC Module not enabled/already disabled
W/bt-btif ( 1780): GATTS Module not enabled/already disabled
D/BluetoothAdapter( 1213): 1110423048: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1213): 1110423048: getState() :  mService = null. Returning STATE_OFF
D/DockEventReceiver( 3976): finishStartingService: stopping service
,D/BluetoothAdapter( 3976): 1106356688: getState() :  mService = null. Returning STATE_OFF
V/BluetoothFtpReceiver( 1780): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 1780): BluetoothFtpReceiver Stop Service
V/BluetoothFtpService( 1780): Ftp Service onDestroy
V/BluetoothFtpService( 1780): Ftp Service closeService
,E/BluetoothFtpService:RfcommSocketAcceptThread( 1780): Shutdown
,D/AuthorizationBluetoothService( 1374): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager( 1021): Killing 3395:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1021): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.ConnectedUnlockReceiver: pid=4028 uid=10016 gids={50016, 3002}
,D/Checkin ( 2283): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2283): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/ActivityManager( 1021): Killing 3786:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/rmt_storage(  360): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb879e1d0
I/rmt_storage(  360): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  360): wakelock acquired: 1, error no: 42
I/rmt_storage(  360): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1199972632)
D/Checkin ( 4028): publish the event [tag = DEVICE_AUTH_STATS_L2 event name = DEVAUTH_CONNECT]
,E/memtrack( 4011): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4011): failed to load memtrack module: -2
,I/rmt_storage(  360): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  360): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  360): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1199972632) wakelock released: 1, error no: 0
I/rmt_storage(  360): 
,I/rmt_storage(  360): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb879e1d0
,D/AndroidRuntime( 4011): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1021): Force stopping com.example.hello appid=10388 user=-1: uninstall pkg
,I/ActivityManager( 1021): Killing 3912:com.example.hello/u0a388 (adj 0): stop com.example.hello
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1021):   Force finishing activity ActivityRecord{4212d6c8 u0 com.example.hello/.MainActivity t3}
,I/WindowState( 1021): WIN DEATH: Window{41ff60f8 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1021): Client connection lost with reason: 4
,W/PackageSettings( 1021): Skipping PackageSetting{421ca1a8 com.test.thalitest/10387} due to missing metadata
,D/NetlinkEvent(  271): Unexpected netlink message. type=0x11
W/Netd    (  271): No subsystem found in netlink event
D/TCMD    (  469): NL - Read 444 bytes from update socket.
D/TCMD    (  469): NL - ignore NL message, type = 17
D/TCMD    (  469): Listening for incoming client connection request
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
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager( 1021): Force stopping com.example.hello appid=10388 user=0: pkg removed
,D/TCMD    (  469): NL - Read 1000 bytes from update socket.
D/TCMD    (  469): NL - message type is RTM_NEWLINK
,D/TCMD    (  469): Listening for incoming client connection request
,D/dalvikvm( 2283): GC_EXPLICIT freed 5182K, 44% free 9658K/17224K, paused 2ms+6ms, total 40ms
,D/NetlinkEvent(  271): Unexpected netlink message. type=0x11
W/Netd    (  271): No subsystem found in netlink event
D/TCMD    (  469): NL - Read 444 bytes from update socket.
D/TCMD    (  469): NL - ignore NL message, type = 17
D/TCMD    (  469): Listening for incoming client connection request
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
D/dalvikvm( 2315): GC_EXPLICIT freed 2753K, 43% free 9818K/17224K, paused 4ms+4ms, total 70ms
,I/LatinIME:LogUtils( 1198): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/LatinIME:LogUtils( 1198): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/ActivityManager( 1021): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4045 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/GeofencerStateMachine( 1213): Ignoring removeGeofence because network location is disabled.
D/dalvikvm( 1309): GC_EXPLICIT freed 3235K, 33% free 11594K/17224K, paused 2ms+4ms, total 104ms
I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
,I/LatinIME:LogUtils( 1198): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1448020262
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
I/OtaApp  ( 1563): [info] > Updatetime from metadata: 10
D/Checkin ( 1563): publish the event [tag = MOT_OTA event name = LOG]
,I/Launcher( 1309): Deferring update until onResume
,D/OtaApp  ( 1563): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1563): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1563): publish the event [tag = MOT_OTA event name = LOG]
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
,D/dalvikvm( 1021): GC_EXPLICIT freed 1810K, 15% free 18095K/21084K, paused 5ms+11ms, total 128ms
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
D/dalvikvm( 1021): WAIT_FOR_CONCURRENT_GC blocked 34ms
D/OtaApp  ( 1563): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/SFPerfTracer(  275):      triggers: (rate: 2:33) (compose: 0:4) (post: 0:1) (render: 0:5) (0:125 frames) (1:549)
,D/SFPerfTracer(  275):        layers: (0:12) (FocusedStackFrame: 1:10)* (StatusBar: 0:213)* (NavigationBar: 0:39)* (com.android.systemui.ImageWallpaper: 0:5)* (Starting com.motorola.ccc.ota: 0:33)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:18)* (ElectronBeam: 0:27)* (com.example.hello/com.example.hello.MainActivity: 0:4)* 
D/OtaApp  ( 1563): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/Checkin ( 2283): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2283): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
I/Launcher( 1309): Deferring update until onResume
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
,W/InputMethodManagerService( 1021): Got RemoteException sending setActive(false) notification to pid 3912 uid 10388
W/Binder  ( 1198): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1198): java.lang.NullPointerException
W/Binder  ( 1198): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1198): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1198): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1198): 	at dalvik.system.NativeStart.run(Native Method)
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
,D/BackupManagerService( 1021): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService( 1021): removePackageParticipantsLocked: uid=10388 #1
,D/VoicemailCleanupService( 4045): Cleaning up data for package: com.example.hello
,I/InternalIcingCorporaPro( 2315): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/LatinIME:LogUtils( 1198): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1448020262
,I/ActivityManager( 1021): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4065 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,W/ContextImpl( 4065): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,I/dalvikvm( 3462): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3462): VFY: unable to resolve virtual method 338: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3462): VFY: replacing opcode 0x6e at 0x0013
,D/PackageBroadcastService( 1418): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1418): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 1418): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1418): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1418): Removing dialog suppression flag for package com.example.hello
,D/ChimeraCfgMgr( 1418): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1418): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 1021): GC_EXPLICIT freed 684K, 15% free 18049K/21084K, paused 5ms+18ms, total 281ms
E/NetworkScheduler.SchedulerReceiver( 1374): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1374): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1418): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1418): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,I/ActivityManager( 1021): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4084 uid=10058 gids={50058}
D/gH_MetricsDatabase( 1418): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1418): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/ActivityManager( 1021): Killing 3763:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/gH_CompatibleDatabase( 1418): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1418): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1418): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/dalvikvm( 1418): GC_CONCURRENT freed 2036K, 32% free 11738K/17224K, paused 5ms+7ms, total 62ms
W/SQLiteConnectionPool( 1418): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/gH_CompatibleDatabase( 1418): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1418): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1418): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1418): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1418): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1418): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/PeopleContactsSync( 1418): CP2 sync disabled
,I/Icing   ( 1418): doRemovePackageData com.example.hello
,I/InternalIcingCorporaPro( 2315): UpdateCorporaTask done [took 183 ms] updated apps [took 183 ms] 
,I/ActivityManager( 1021): Killing 3976:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/AndroidRuntime( 4011): Shutting down VM
,D/dalvikvm( 4011): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
,D/WifiService( 1021): Client connection lost with reason: 4
D/Documents( 4084): Loading roots for com.android.providers.downloads.documents
,I/ActivityManager( 1021): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4101 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/dalvikvm(  276): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 3ms+3ms, total 22ms
I/ActivityManager( 1021): Killing 4028:com.motorola.deviceauthenticator/u0a16 (adj 15): empty #9
I/ActivityManager( 1021): Killing 1780:com.android.bluetooth/1002 (adj 15): empty #10
W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ContactLocale( 4045): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 18ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 18ms
,D/Checkin ( 2283): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Documents( 4084): Loading roots for com.android.externalstorage.documents
,D/dalvikvm( 4101): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f11398, skipping init
I/openssl ( 4101): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4101): Crypto mode 0 already enabled
,I/ActivityManager( 1021): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4116 uid=10020 gids={50020, 1028, 1015, 1023}
,D/ExternalStorage( 4116): After updating volumes, found 1 active roots
,D/Documents( 4084): Updating roots due to change at content://com.android.externalstorage.documents/root
I/ActivityManager( 1021): Killing 4045:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Documents( 4084): Loading roots for com.android.providers.media.documents
,D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=196614
D/WifiStateMachine( 1021): processMsg: InitialState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131208
D/WifiStateMachine( 1021): processMsg: InitialState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131208
D/WifiStateMachine( 1021): processMsg: InitialState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131208
D/WifiStateMachine( 1021): processMsg: InitialState
D/WifiStateMachine( 1021): processMsg: DefaultState
,D/WifiStateMachine( 1021): handleMessage: X
,D/Documents( 4084): Loading roots for com.google.android.apps.docs.storage
,D/Documents( 4084): Update found 7 roots in 203ms
D/Documents( 4084): Used cached roots for com.android.providers.downloads.documents
,D/Documents( 4084): Loading roots for com.android.externalstorage.documents
D/Documents( 4084): Used cached roots for com.android.providers.media.documents
D/Documents( 4084): Used cached roots for com.google.android.apps.docs.storage
,D/Documents( 4084): Update found 7 roots in 7ms

```
