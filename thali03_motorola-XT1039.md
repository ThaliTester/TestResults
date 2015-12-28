#### Test 503880191ec81a5_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
,I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4000): 
D/AndroidRuntime( 4000): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4000): CheckJNI is OFF
D/dalvikvm( 4000): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4000): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4000): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4000): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4000): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4000): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4000): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4000): failed to load memtrack module: -2
D/AndroidRuntime( 4000): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1021): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 4000
W/WindowManager( 1021): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1021): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4016 uid=10508 gids={50508, 3003, 3001, 3002}
D/AndroidRuntime( 4000): Shutting down VM
D/dalvikvm( 4000): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 2ms
W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4016): Binding Chromium to main looper Looper (main, tid 1) {41fdce30}
I/LibraryLoader( 4016): Expected native library version number "",actual native library version number ""
I/chromium( 4016): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4016): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1021): Message: 20
D/BluetoothManagerService( 1021): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4285a0d0:true
I/Adreno-EGL( 4016): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4016): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4016): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4016): Local Branch: 
I/Adreno-EGL( 4016): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4016): Local Patches: NONE
I/Adreno-EGL( 4016): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4016): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4016): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4016): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4016): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4016): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4016): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4016): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4016): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4016): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4016): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4016): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4016): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4016): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4016): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4016): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4016): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4016): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4016): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4016): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4016): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4016): Enabling debug mode 0
,W/AwContents( 4016): nativeOnDraw failed; clearing to background color.
,W/AwContents( 4016): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1021): Displayed com.example.hello/.MainActivity,cp,ca,306
I/ActivityManager( 1021): Displayed com.example.hello/.MainActivity: +281ms (total +306ms)
W/IInputConnectionWrapper( 4016): showStatusIcon on inactive InputConnection
,I/chromium( 4016): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 4016): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 4016): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4016): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41fe2048
,D/dalvikvm( 4016): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41fe2048
D/jxcore_app_log( 4016): JniHelper::setJavaVM(0x4162efa8), pthread_self() = 1610776728
,D/JX-Cordova( 4016): jxcore cordova android initializing
,W/jxcore-log( 4016): Initializing JXcore engine
,W/jxcore-log( 4016): JXcore engine is ready
,W/jxcore-log( 4016): Starting JXcore engine
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,W/jxcore-log( 4016): Platform android
W/jxcore-log( 4016): 
,W/jxcore-log( 4016): Process ARCH arm
W/jxcore-log( 4016): 
,I/jxcore-log( 4016): JXcore Cordova bridge is ready!
I/jxcore-log( 4016): 
,W/jxcore-log( 4016): JXcore engine is started
,E/jxcore-log( 4016): >> motorola-XT1039
E/jxcore-log( 4016): 
,I/jxcore-log( 4016): Total memory 893136896
I/jxcore-log( 4016): 
I/jxcore-log( 4016): Free memory 40980480
I/jxcore-log( 4016): 
I/jxcore-log( 4016): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4016): 
,I/jxcore-log( 4016): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4016): 
,I/jxcore-log( 4016): userPath [ 'www' ]
I/jxcore-log( 4016): 
,I/jxcore-log( 4016): Size 720 1184
I/jxcore-log( 4016): 
,I/jxcore-log( 4016): Screen Brightness 10
I/jxcore-log( 4016): 
,E/jxcore-log( 4016): Dummy Error Log.
E/jxcore-log( 4016): 
,I/jxcore-log( 4016): getBuffer is called!!!!
I/jxcore-log( 4016): 
,D/BluetoothManagerService( 1021): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1021): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@422c11c0 mBinding = false
,W/Settings( 1296): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/XTWiFiOS( 1307): No entry in secure settings for enhanced location services: false
,W/Settings( 1296): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/BluetoothManagerService( 1021): Message: 2
D/BluetoothManagerService( 1021): Sending off request.
D/BluetoothAdapterState( 1798): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1798): Setting state to 13
I/BluetoothAdapterState( 1798): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 1798): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterProperties( 1798): onBluetoothDisable()
I/BluetoothAdapterState( 1798): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/BluetoothAdapterProperties( 1798): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 1798): Scan Mode:21
D/BluetoothAdapterState( 1798): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 1798): bta_jv_rfcomm_stop_server
E/BtOppRfcommListener( 1798): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 1798): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btif ( 1798): bta_jv_rfcomm_stop_server
E/bt-btif ( 1798): bta_jv_rfcomm_stop_server
E/bt-btif ( 1798): bta_jv_rfcomm_stop_server
D/BluetoothManagerService( 1021): Message: 60
D/BluetoothManagerService( 1021): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1021): Bluetooth State Change Intent: 12 -> 13
W/bt-btif ( 1798): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/btif_config_util( 1798): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
W/bt-l2cap( 1798): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1798): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothMapService( 1798): onReceive
,D/BluetoothMapService( 1798): STATE_TURNING_OFF removeTimeoutMsg:false
,D/BluetoothMapService( 1798): MAP Service closeService in
,I/ActivityManager( 1021): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=4079 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,D/WifiService( 1021): New client listening to asynchronous messages
,D/WifiService( 1021): setWifiEnabled: false pid=4016, uid=10508
,E/WifiService( 1021): Invoking mWifiStateMachine.setWifiEnabled
,W/Settings( 1296): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiStateMachine( 1021): handleMessage: E msg.what=131084
D/WifiStateMachine( 1021): processMsg: ConnectedState
,I/jxcore-log( 4016): ****TEST TOOK:  5194  ms ****
I/jxcore-log( 4016): 
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
I/jxcore-log( 4016): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4016): 
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): transitionTo: destState=WaitForP2pDisableState
W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
D/WifiStateMachine( 1021): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1021): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1021): Stopping DHCP and clearing IP
D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 true
W/Settings( 1296): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1307): No entry in secure settings for enhanced location services: false
D/WifiP2pService( 1021): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/BtOppRfcommListener( 1798): stopping Accept Thread
I/BtOppRfcommListener( 1798): BluetoothSocket listen thread finished
D/CommandListener(  275): Clearing all IP addresses on wlan0
D/TCMD    (  481): NL - Read 60 bytes from update socket.
D/TCMD    (  481): NL - ignore NL message, type = 21
D/TCMD    (  481): Listening for incoming client connection request
D/WifiStateMachine( 1021): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1021): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1021): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1021): connected time updated 101063
D/ConnectivityService( 1021): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1021): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1021): Attempting to switch to mobile
D/ConnectivityService( 1021): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1021): Attempting to switch to ETHERNET
D/WifiStateMachine( 1021): invokeExitMethods: ConnectModeState
I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/WifiStateMachine( 1021): invokeExitMethods: DriverStartedState
D/Checkin ( 1021): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/ConnectivityService( 1021): resetConnections(wlan0, 3)
,D/NetUtils( 1021): android_net_utils_resetConnections in env=0x6123e7f8 clazz=0x62f00001 iface=wlan0 mask=0x3
W/ContextImpl( 4079): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,V/NativeCrypto( 1386): Read error: ssl=0x62e0a230: I/O error during system call, Connection timed out
,D/BluetoothManagerService( 1021): Message: 20
D/BluetoothManagerService( 1021): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423d25e8:true
,D/BluetoothPbapService( 1798): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/NativeCrypto( 1386): SSL shutdown failed: ssl=0x62e0a230: I/O error during system call, Broken pipe
,D/BluetoothManagerService( 1021): Message: 30
,W/ContextImpl( 4079): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
,D/BluetoothManagerService( 1021): Message: 30
W/ContextImpl( 4079): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
E/WifiStateMachine( 1021): Unexpected BatchedScanResults :OK
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
,D/WifiStateMachine( 1021): invokeEnterMethods: WaitForP2pDisableState
D/WifiP2pService( 1021): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
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
D/WifiP2pService( 1021): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LocalBluetoothProfileManager( 4079): Adding local MAP profile
D/BluetoothMap( 4079): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1021): Message: 30
,W/ContextImpl( 4079): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
D/BluetoothManagerService( 1021): Message: 30
,D/CommandListener(  275): Clearing all IP addresses on wlan0
,W/ContextImpl( 4079): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 4079): LocalBluetoothProfileManager construction complete
D/WifiStateMachine( 1021): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1021): stopping supplicant
D/DockEventReceiver( 4079): finishStartingService: stopping service
D/WifiStateMachine( 1021): setWifiState: disabling
D/Checkin ( 1021): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
W/XTWiFiOS( 1307): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1084): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1307): Active network info is not available
D/WifiStateMachine( 1021): handleMessage: X
E/XTCC-3.0.0.2(  628): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  628): [WwanPosMgr] handleConnectivtyStatusChange failed
I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=false Wifi=(none) Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/bt_hwcfg( 1798): hw_epilog_process
W/bt-btif ( 1798): ag scb idx 1 not allocated
E/bt-btif ( 1798): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1798): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1798): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1798): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1798): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1798): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1798): L2CAP - PSM: 0x0017 not found for deregistration
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1021): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
E/XTCC-3.0.0.2(  628): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  628): [CSMgr] handleConnectivtyStatusChange failed
I/ModemStatsDSDetect( 1208): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1208): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1208): onReceive() - done, currentInetCondition=0
D/WifiService( 1021): New client listening to asynchronous messages
D/ConnectivityService( 1021): Attempting to switch to mobile
D/ConnectivityService( 1021): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1021): Attempting to switch to ETHERNET
D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1208): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1208): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1208): onReceive() - done, currentInetCondition=0
I/bt_hwcfg( 1798): hw_epilog_cback Opcode:0x0C03 Status: 0
I/bt_hci_bdroid( 1798): bt_hc_worker_thread exiting
D/bt_userial_mct( 1798): userial_close
I/bt_userial_mct( 1798): exiting userial_read_thread
D/bt_userial_mct( 1798): Leaving userial_evt_read_thread()
,I/wpa_supplicant( 1154): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  277): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  277): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  277):  STA Disconnected !!
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): get_property_value, Enter
I/MDMCTBK (  277): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  277): get_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
,I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
,E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  277): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
D/TCMD    (  481): NL - Read 1000 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/WifiStateMachine( 1021): handleMessage: E msg.what=147460
D/WifiStateMachine( 1021): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1021): processMsg: DefaultState
,D/WifiStateMachine( 1021): handleMessage: X
,D/Tethering( 1021): InitialState.processMessage what=4
D/Tethering( 1021): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/TCMD    (  481): NL - Read 1000 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 68 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 68 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
,D/Tethering( 1021): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1021): handleMessage: E msg.what=131101
D/WifiStateMachine( 1021): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1021): processMsg: DefaultState
,D/WifiStateMachine( 1021): handleMessage: X
,I/wpa_supplicant( 1154): eap_proxy Deinitialzed
D/MDMCTBK (  277): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4
D/MDMCTBK (  277): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1 38:f8:89
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 1 38:f8:89
D/MDMCTBK (  277): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2 fc:94:e3
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 2 fc:94:e3
,D/WifiStateMachine( 1021): handleMessage: E msg.what=196614
D/WifiStateMachine( 1021): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1021): processMsg: DefaultState
,D/WifiStateMachine( 1021): handleMessage: X
,D/dalvikvm( 1021): GC_EXPLICIT freed 1362K, 15% free 18093K/21160K, paused 3ms+12ms, total 98ms
,D/BluetoothInputDevice( 4079): Proxy object connected
,D/HidProfile( 4079): Bluetooth service connected
,V/BluetoothFtpReceiver( 1798): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothPan( 4079): BluetoothPAN Proxy object connected
D/PanProfile( 4079): Bluetooth service connected
,D/BluetoothMap( 4079): Proxy object connected
,D/MapProfile( 4079): Bluetooth service connected
,D/BluetoothMap( 4079): getConnectedDevices()
D/BluetoothMap( 4079): Bluetooth is Not enabled
,D/AuthorizationBluetoothService( 1386): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager( 1021): Killing 3765:com.android.calendar/u0a7 (adj 15): empty #9
W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/TCMD    (  481): NL - Read 1000 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
,D/TCMD    (  481): Listening for incoming client connection request
I/wpa_supplicant( 1154): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  277): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  277):  Wpa Supplicant Exiting !!
D/MDMCTBK (  277): wifi_wait_on_socket: Exiting monitor thread
,D/MDMCTBK (  277): wifi_close_sockets: Close Wifi socket
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147458
,D/WifiStateMachine( 1021): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1021): Supplicant connection lost
,D/MDMCTBK (  277): wifi_close_sockets: Exit
,D/AndroidRuntime( 4110): 
D/AndroidRuntime( 4110): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4110): CheckJNI is OFF
,D/dalvikvm( 4110): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4110): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4110): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4110): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4110): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4110): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,D/BTSNOOP-DISP( 1798): btsnoop_close
I/bt_vendor( 1798): cleanup
I/bt_hwcfg( 1798): Starting hciattach daemon
,I/bt_hwcfg( 1798): try to set false
I/GKI_LINUX( 1798): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 1798): GKI_exit_task: GKI_exit_task 0 done
,I/GKI_LINUX( 1798): GKI_destroy_task: GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 1798): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 1798): Received stop request...Stopping profile...
D/BluetoothHeadset( 1282): Proxy object disconnected
,D/BluetoothHeadset( 1021): Proxy object disconnected
D/BluetoothHeadset( 1282): Proxy object disconnected
,D/BluetoothHeadset( 1282): Proxy object disconnected
,D/A2dpService( 1798): Received stop request...Stopping profile...
,D/A2dpStateMachine( 1798): Exit Disconnected: -1
,D/BluetoothA2dp( 1021): Proxy object disconnected
,D/HidService( 1798): Received stop request...Stopping profile...
D/BluetoothInputDevice( 4079): Proxy object disconnected
D/HidProfile( 4079): Bluetooth service disconnected
,D/BluetoothAdapterService( 1798): Profile still running: com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterState( 1798): Stopping profile services that were post enabled
,D/HealthService( 1798): Received stop request...Stopping profile...
,W/BluetoothHeadsetServiceJni( 1798): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 1798): Cleaning up Bluetooth Handsfree callback object
,D/PanService( 1798): Received stop request...Stopping profile...
D/BluetoothTethering( 1021): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering( 1021): attempted to stop reverse tether with nothing tethered
,D/BluetoothTethering( 1021): Disconnect CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@428cdb98
,D/BluetoothTethering( 1021): got CMD_CHANNEL_DISCONNECTED
D/BluetoothPan( 1021): BluetoothPAN Proxy object disconnected
D/BluetoothPan( 4079): BluetoothPAN Proxy object disconnected
,D/PanProfile( 4079): Bluetooth service disconnected
,D/BtGatt.DebugUtils( 1798): handleDebugAction() action=null
D/BtGatt.GattService( 1798): Received stop request...Stopping profile...
,D/BtGatt.GattService( 1798): stop()
,D/BluetoothAdapterService( 1798): Profile still running: com.android.bluetooth.hdp.HealthService
D/BluetoothMapService( 1798): Received stop request...Stopping profile...
,D/BluetoothMapService( 1798): stop()
,D/BluetoothMapService( 1798): MAP Service closeService in
,I/GKI_LINUX( 1798): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 1798): GKI_exit_task: GKI_exit_task 2 done
I/GKI_LINUX( 1798): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
,D/BluetoothAdapterService( 1798): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 1798): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 1798): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 1798): Cleaning up Bluetooth GID callback object
,D/BluetoothMap( 4079): Proxy object disconnected
D/BluetoothAdapterService( 1798): Profile still running: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothHealthServiceJni( 1798): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 1798): Cleaning up Bluetooth Health object
,D/BluetoothAdapterService( 1798): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 1798): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 1798): Cleaning up Bluetooth PAN callback object
,D/MapProfile( 4079): Bluetooth service disconnected
,D/BluetoothAdapterService( 1798): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/BluetoothMapService( 1798): cleanup()
,D/BluetoothMapService( 1798): MAP Service closeService in
,D/BluetoothAdapterState( 1798): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1798): Setting state to 10
I/BluetoothAdapterState( 1798): Bluetooth adapter state changed: 13-> 10
,D/BluetoothAdapterService( 1798): Broadcasting updateAdapterState() to 1 receivers.
I/BluetoothAdapterState( 1798): Entering OffState
D/BluetoothManagerService( 1021): Message: 60
D/BluetoothManagerService( 1021): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
,D/BluetoothManagerService( 1021): Broadcasting onBluetoothStateChange(false) to 10 receivers.
,D/BluetoothHeadset( 1282): onBluetoothStateChange: up=false
,D/BluetoothPan( 1021): onBluetoothStateChange on: false
,D/BluetoothHeadset( 1282): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1282): onBluetoothStateChange: up=false
,D/BluetoothMap( 4079): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1021): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1021): onBluetoothStateChange: up=false
,D/BluetoothPan( 4079): onBluetoothStateChange on: false
,D/BluetoothPbap( 4079): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 4079): onBluetoothStateChange: up=false
,D/BluetoothManagerService( 1021): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService( 1021): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/WifiStateMachine( 1021): setWifiState: disabled
,D/BluetoothManagerService( 1021): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@422c11c0 mBinding = false
,D/BluetoothManagerService( 1021): Sending unbind request.
D/WifiStateMachine( 1021): transitionTo: destState=InitialState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1021): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
,D/WifiStateMachine( 1021): invokeEnterMethods: InitialState
,D/BluetoothManagerService( 1021): Bluetooth State Change Intent: 13 -> 10
,W/XTWiFiOS( 1307): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1084): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/BluetoothAdapterService( 1798): Cleaning up adapter native....
,W/XTWiFiOS( 1307): Active network info is not available
I/GKI_LINUX( 1798): gki_task_entry: gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 1798): GKI_exit_task: GKI_exit_task 1 done
,I/GKI_LINUX( 1798): GKI_destroy_task: GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 1798): cleanupNative: return from cleanup
D/BluetoothAdapterService( 1798): Done cleaning up adapter native....
,D/BluetoothAdapterService(1107212128)( 1798): ****onDestroy()********
,D/BluetoothAdapter( 1084): 1108678424: getState() :  mService = null. Returning STATE_OFF
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.sendDeviceAttachIntent:820 com.motorola.authentication.MotAuthenticationService.access$1300:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:575 
E/XTCC-3.0.0.2(  628): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  628): [WwanPosMgr] handleConnectivtyStatusChange failed
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.handleKeepDeviceUnlockRequest:732 com.motorola.authentication.MotAuthenticationService.access$1500:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:563 
D/BtGatt.GattService( 1798): cleanup()
W/bt-btif ( 1798): GATTC Module not enabled/already disabled
W/bt-btif ( 1798): GATTS Module not enabled/already disabled
W/Settings( 1252): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ContextImpl( 4079): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/BluetoothAdapter( 1252): 1110646168: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1252): 1110646168: getState() :  mService = null. Returning STATE_OFF
D/DockEventReceiver( 4079): finishStartingService: stopping service
I/dalvikvm( 1021): Jit: resizing JitTable from 8192 to 16384
E/XTCC-3.0.0.2(  628): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  628): [CSMgr] handleConnectivtyStatusChange failed
D/BluetoothAdapter( 4079): 1107243152: getState() :  mService = null. Returning STATE_OFF
,V/BluetoothFtpReceiver( 1798): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 1798): BluetoothFtpReceiver Stop Service
V/BluetoothFtpService( 1798): Ftp Service onDestroy
V/BluetoothFtpService( 1798): Ftp Service closeService
,E/BluetoothFtpService:RfcommSocketAcceptThread( 1798): Shutdown
,D/AuthorizationBluetoothService( 1386): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager( 1021): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.ConnectedUnlockReceiver: pid=4133 uid=10016 gids={50016, 3002}
,I/ActivityManager( 1021): Killing 3474:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/rmt_storage(  447): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb73261d0
I/rmt_storage(  447): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  447): wakelock acquired: 1, error no: 42
,I/rmt_storage(  447): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1221435672)
,E/memtrack( 4110): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4110): failed to load memtrack module: -2
,I/ActivityManager( 1021): Killing 3846:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Checkin ( 4133): publish the event [tag = DEVICE_AUTH_STATS_L2 event name = DEVAUTH_CONNECT]
,D/AndroidRuntime( 4110): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1021): Force stopping com.example.hello appid=10508 user=-1: uninstall pkg
,I/ActivityManager( 1021): Killing 4016:com.example.hello/u0a508 (adj 0): stop com.example.hello
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiService( 1021): Client connection lost with reason: 4
,I/WindowState( 1021): WIN DEATH: Window{428d9758 u0 com.example.hello/com.example.hello.MainActivity}
,I/ActivityManager( 1021):   Force finishing activity ActivityRecord{428176c8 u0 com.example.hello/.MainActivity t3}
I/rmt_storage(  447): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  447): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  447): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1221435672) wakelock released: 1, error no: 0
I/rmt_storage(  447): 
I/rmt_storage(  447): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb73261d0
,I/SFPerfTracer(  279):      triggers: (rate: 2:29) (compose: 0:4) (post: 0:1) (render: 0:5) (0:105 frames) (1:549)
,D/SFPerfTracer(  279):        layers: (0:12) (FocusedStackFrame: 0:9)* (StatusBar: 0:209)* (NavigationBar: 0:34)* (com.android.systemui.ImageWallpaper: 0:6)* (Starting com.motorola.ccc.ota: 0:34)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:18)* (ElectronBeam: 0:25)* (com.example.hello/com.example.hello.MainActivity: 0:4)* 
,W/PackageSettings( 1021): Skipping PackageSetting{422a42b8 com.test.thalitest/10507} due to missing metadata
,I/ActivityManager( 1021): Force stopping com.example.hello appid=10508 user=0: pkg removed
I/ActivityManager( 1021):   Force finishing activity ActivityRecord{428176c8 u0 com.example.hello/.MainActivity t3 f}
W/ActivityManager( 1021): Duplicate finish request for ActivityRecord{428176c8 u0 com.example.hello/.MainActivity t3 f}
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 1021):   Scheme: "sms"
I/ActivityManager( 1021): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4150 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
D/dalvikvm( 2292): GC_EXPLICIT freed 5283K, 44% free 9669K/17224K, paused 2ms+5ms, total 54ms
I/LatinIME:LogUtils( 1221): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1221): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/OtaApp  ( 1600): [info] > Updatetime from metadata: 10
D/Checkin ( 1600): publish the event [tag = MOT_OTA event name = LOG]
W/GeofencerStateMachine( 1252): Ignoring removeGeofence because network location is disabled.
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
D/OtaApp  ( 1600): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1600): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1600): publish the event [tag = MOT_OTA event name = LOG]
,D/Checkin ( 2292): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2292): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
D/OtaApp  ( 1600): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/dalvikvm( 1396): GC_EXPLICIT freed 1274K, 31% free 11962K/17224K, paused 44ms+9ms, total 139ms
,W/SQLiteConnectionPool( 1396): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
,D/OtaApp  ( 1600): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/dalvikvm( 1324): GC_EXPLICIT freed 3241K, 33% free 11594K/17224K, paused 75ms+34ms, total 156ms
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
,D/NetlinkEvent(  275): Unexpected netlink message. type=0x11
W/Netd    (  275): No subsystem found in netlink event
D/TCMD    (  481): NL - Read 444 bytes from update socket.
D/TCMD    (  481): NL - ignore NL message, type = 17
D/TCMD    (  481): Listening for incoming client connection request
,I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  277): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
,I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
,E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/Launcher( 1324): Deferring update until onResume
,D/dalvikvm( 2329): GC_EXPLICIT freed 5078K, 41% free 10174K/17224K, paused 75ms+12ms, total 177ms
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
,D/BackupManagerService( 1021): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService( 1021): removePackageParticipantsLocked: uid=10508 #1
,D/TCMD    (  481): NL - Read 1000 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
,D/TCMD    (  481): Listening for incoming client connection request
,W/InputMethodManagerService( 1021): Got RemoteException sending setActive(false) notification to pid 4016 uid 10508
W/Binder  ( 1221): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1221): java.lang.NullPointerException
W/Binder  ( 1221): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1221): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1221): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1221): 	at dalvik.system.NativeStart.run(Native Method)
,I/LatinIME:LogUtils( 1221): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1451341496
,I/Launcher( 1324): Deferring update until onResume
,D/NetlinkEvent(  275): Unexpected netlink message. type=0x11
W/Netd    (  275): No subsystem found in netlink event
D/TCMD    (  481): NL - Read 444 bytes from update socket.
D/TCMD    (  481): NL - ignore NL message, type = 17
D/TCMD    (  481): Listening for incoming client connection request
I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  277): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  277): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  277): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/VoicemailCleanupService( 4150): Cleaning up data for package: com.example.hello
,I/InternalIcingCorporaPro( 2329): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/LatinIME:LogUtils( 1221): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1451341496
,I/ActivityManager( 1021): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4170 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/dalvikvm( 1021): GC_EXPLICIT freed 1369K, 15% free 18116K/21160K, paused 4ms+17ms, total 343ms
,W/ContextImpl( 4170): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,I/dalvikvm( 3524): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3524): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3524): VFY: replacing opcode 0x6e at 0x0013
,I/ActivityManager( 1021): Killing 3823:com.android.defcontainer/u0a13 (adj 15): empty #9
D/PackageBroadcastService( 1396): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1396): Clearing selected account for com.example.hello
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ChimeraCfgMgr( 1396): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1396): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1396): Removing dialog suppression flag for package com.example.hello
,D/ChimeraCfgMgr( 1396): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1396): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1386): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1386): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1396): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1396): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1396): 0 metrics were deleted when clearing package com.example.hello.
,D/gH_CompatibleDatabase( 1396): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1396): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1396): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1396): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/ActivityManager( 1021): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4192 uid=10058 gids={50058}
D/gH_CompatibleDatabase( 1396): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1396): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
I/Icing   ( 1396): doRemovePackageData com.example.hello
D/gH_CompatibleDatabase( 1396): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1396): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1396): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1396): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,D/dalvikvm(  280): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+2ms, total 21ms
,D/dalvikvm(  280): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 18ms
,D/AndroidRuntime( 4110): Shutting down VM
,D/dalvikvm( 4110): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 3ms
,D/dalvikvm(  280): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,I/ActivityManager( 1021): Killing 4079:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiService( 1021): Client connection lost with reason: 4
D/Documents( 4192): Loading roots for com.android.providers.downloads.documents
,I/ActivityManager( 1021): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4209 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/ActivityManager( 1021): Killing 1798:com.android.bluetooth/1002 (adj 15): empty #9
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2329): UpdateCorporaTask done [took 261 ms] updated apps [took 261 ms] 
,I/ActivityManager( 1021): Killing 4133:com.motorola.deviceauthenticator/u0a16 (adj 15): empty #9
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4150): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/dalvikvm( 4209): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fdf568, skipping init
I/openssl ( 4209): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4209): Crypto mode 0 already enabled
D/Documents( 4192): Loading roots for com.android.externalstorage.documents
,I/ActivityManager( 1021): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4226 uid=10020 gids={50020, 1028, 1015, 1023}
,I/ActivityManager( 1021): Killing 4150:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ExternalStorage( 4226): After updating volumes, found 1 active roots
,D/Documents( 4192): Updating roots due to change at content://com.android.externalstorage.documents/root
,D/Documents( 4192): Loading roots for com.android.providers.media.documents
,D/Documents( 4192): Loading roots for com.google.android.apps.docs.storage
,D/Documents( 4192): Update found 7 roots in 198ms
,D/Documents( 4192): Used cached roots for com.android.providers.downloads.documents
,D/Documents( 4192): Loading roots for com.android.externalstorage.documents
,D/Documents( 4192): Used cached roots for com.android.providers.media.documents
D/Documents( 4192): Used cached roots for com.google.android.apps.docs.storage
,D/Documents( 4192): Update found 7 roots in 6ms
,D/Checkin ( 2292): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2292): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]

```
