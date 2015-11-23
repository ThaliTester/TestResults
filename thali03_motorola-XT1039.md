#### Test 503880197c51433_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,D/AndroidRuntime( 3973): 
D/AndroidRuntime( 3973): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3973): CheckJNI is OFF
D/dalvikvm( 3973): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3973): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3973): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3973): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3973): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3973): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3973): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3973): failed to load memtrack module: -2
D/AndroidRuntime( 3973): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1004): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3973
W/WindowManager( 1004): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1004): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3989 uid=10404 gids={50404, 3003, 3001, 3002}
D/AndroidRuntime( 3973): Shutting down VM
D/dalvikvm( 3973): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 2ms
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3989): Binding Chromium to main looper Looper (main, tid 1) {41ff7ca8}
I/LibraryLoader( 3989): Expected native library version number "",actual native library version number ""
I/chromium( 3989): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3989): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1004): Message: 20
D/BluetoothManagerService( 1004): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42848730:true
I/Adreno-EGL( 3989): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3989): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3989): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3989): Local Branch: 
I/Adreno-EGL( 3989): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3989): Local Patches: NONE
I/Adreno-EGL( 3989): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3989): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3989): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3989): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3989): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3989): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3989): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3989): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3989): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3989): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3989): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3989): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3989): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3989): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3989): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3989): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3989): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3989): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3989): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3989): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3989): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3989): Enabling debug mode 0
,W/AwContents( 3989): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3989): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1004): Displayed com.example.hello/.MainActivity,cp,ca,305
I/ActivityManager( 1004): Displayed com.example.hello/.MainActivity: +283ms (total +305ms)
,I/chromium( 3989): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 3989): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 3989): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3989): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41ffcff0,
,D/dalvikvm( 3989): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41ffcff0
,D/jxcore_app_log( 3989): JniHelper::setJavaVM(0x41649fa8), pthread_self() = 1610869752
,D/JX-Cordova( 3989): jxcore cordova android initializing
,W/jxcore-log( 3989): Initializing JXcore engine
,W/jxcore-log( 3989): JXcore engine is ready
,W/jxcore-log( 3989): Starting JXcore engine
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
,W/jxcore-log( 3989): Platform android
W/jxcore-log( 3989): 
,W/jxcore-log( 3989): Process ARCH arm
W/jxcore-log( 3989): 
,I/jxcore-log( 3989): JXcore Cordova bridge is ready!
I/jxcore-log( 3989): 
,W/jxcore-log( 3989): JXcore engine is started
,E/jxcore-log( 3989): >> motorola-XT1039
E/jxcore-log( 3989): 
,I/jxcore-log( 3989): Total memory 893136896
I/jxcore-log( 3989): 
I/jxcore-log( 3989): Free memory 50647040
I/jxcore-log( 3989): 
I/jxcore-log( 3989): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3989): 
,I/jxcore-log( 3989): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3989): 
,I/jxcore-log( 3989): userPath [ 'www' ]
I/jxcore-log( 3989): 
,I/jxcore-log( 3989): Size 720 1184
I/jxcore-log( 3989): 
,I/jxcore-log( 3989): Screen Brightness 10
I/jxcore-log( 3989): 
,E/jxcore-log( 3989): Dummy Error Log.
E/jxcore-log( 3989): 
,I/jxcore-log( 3989): getBuffer is called!!!!
I/jxcore-log( 3989): 
,V/AlarmManager( 1004): sending alarm Alarm{428cd400 type 3 android}
,D/BluetoothManagerService( 1004): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1004): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@42492c10 mBinding = false
,W/Settings( 1243): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1279): No entry in secure settings for enhanced location services: false
,D/BluetoothManagerService( 1004): Message: 2
,D/BluetoothManagerService( 1004): Sending off request.
,D/BluetoothAdapterState( 1788): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1788): Setting state to 13
,I/BluetoothAdapterState( 1788): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 1788): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterProperties( 1788): onBluetoothDisable()
,I/BluetoothAdapterState( 1788): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,I/BluetoothAdapterProperties( 1788): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothAdapterProperties( 1788): Scan Mode:21
,D/BluetoothAdapterState( 1788): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,D/BluetoothManagerService( 1004): Message: 60
,E/bt-btif ( 1788): bta_jv_rfcomm_stop_server
,E/BtOppRfcommListener( 1788): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,V/BluetoothFtpService:RfcommSocketAcceptThread( 1788): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 1788): bta_jv_rfcomm_stop_server
,E/bt-btif ( 1788): bta_jv_rfcomm_stop_server
,E/bt-btif ( 1788): bta_jv_rfcomm_stop_server
,D/BluetoothManagerService( 1004): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,W/bt-btif ( 1788): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,D/BluetoothManagerService( 1004): Bluetooth State Change Intent: 12 -> 13
,W/bt-l2cap( 1788): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1788): L2CAP - PSM: 0x0017 not found for deregistration
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/BluetoothMapService( 1788): onReceive
,D/BluetoothMapService( 1788): STATE_TURNING_OFF removeTimeoutMsg:false
,D/BluetoothMapService( 1788): MAP Service closeService in
,I/ActivityManager( 1004): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=4055 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,W/Settings( 1243): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiService( 1004): New client listening to asynchronous messages
D/WifiService( 1004): setWifiEnabled: false pid=3989, uid=10404
E/WifiService( 1004): Invoking mWifiStateMachine.setWifiEnabled
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,I/BtOppRfcommListener( 1788): stopping Accept Thread
,I/BtOppRfcommListener( 1788): BluetoothSocket listen thread finished
D/WifiStateMachine( 1004): handleMessage: E msg.what=131084
D/WifiStateMachine( 1004): processMsg: ConnectedState
D/WifiStateMachine( 1004): processMsg: L2ConnectedState
D/WifiStateMachine( 1004): processMsg: ConnectModeState
D/WifiStateMachine( 1004): processMsg: DriverStartedState
D/WifiStateMachine( 1004): processMsg: SupplicantStartedState
D/WifiStateMachine( 1004): transitionTo: destState=WaitForP2pDisableState
D/WifiStateMachine( 1004): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1004): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
,W/Settings( 1243): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiStateMachine( 1004): invokeExitMethods: ConnectedState
,I/jxcore-log( 3989): ****TEST TOOK:  5181  ms ****
I/jxcore-log( 3989): 
,I/jxcore-log( 3989): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3989): 
,D/WifiStateMachine( 1004): invokeExitMethods: L2ConnectedState
W/XTWiFiOS( 1279): No entry in secure settings for enhanced location services: false
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiStateMachine( 1004): Stopping DHCP and clearing IP
D/WifiStateMachine( 1004): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1004): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1004): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/Settings( 1243): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/CommandListener(  272): Clearing all IP addresses on wlan0
D/TCMD    (  462): NL - Read 60 bytes from update socket.
D/TCMD    (  462): NL - ignore NL message, type = 21
D/TCMD    (  462): Listening for incoming client connection request
D/WifiStateMachine( 1004): addressRemoved: 192.168.1.123/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1004): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/WifiMetrics( 1004): connected time updated 99456
,D/WifiStateMachine( 1004): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/ConnectivityService( 1004): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1004): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1004): invokeExitMethods: ConnectModeState
,D/WifiStateMachine( 1004): invokeExitMethods: DriverStartedState
D/ConnectivityService( 1004): Attempting to switch to mobile
,D/ConnectivityService( 1004): Attempting to switch to BLUETOOTH_TETHER
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/ConnectivityService( 1004): Attempting to switch to ETHERNET
E/WifiStateMachine( 1004): Unexpected BatchedScanResults :OK
D/WifiStateMachine( 1004): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1004): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
D/WifiStateMachine( 1004): invokeEnterMethods: WaitForP2pDisableState
D/WifiStateMachine( 1004): handleMessage: X
D/WifiStateMachine( 1004): handleMessage: E msg.what=131216
D/WifiStateMachine( 1004): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1004): processMsg: SupplicantStartedState
,D/WifiP2pService( 1004): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1004): processMsg: DefaultState
,D/WifiP2pService( 1004): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1004): handleMessage: X
D/WifiStateMachine( 1004): handleMessage: E msg.what=131216
D/WifiStateMachine( 1004): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1004): processMsg: SupplicantStartedState
D/Checkin ( 1004): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1004): processMsg: DefaultState
,D/WifiStateMachine( 1004): handleMessage: X
D/WifiP2pService( 1004): P2pDisablingState
D/WifiP2pService( 1004): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1004): p2p socket connection lost
,D/WifiP2pService( 1004): P2pDisabledState
D/WifiStateMachine( 1004): handleMessage: E msg.what=131205
D/WifiStateMachine( 1004): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1004): transitionTo: destState=SupplicantStoppingState
D/WifiStateMachine( 1004): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1004): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1004): invokeExitMethods: WaitForP2pDisableState
D/WifiStateMachine( 1004): invokeExitMethods: SupplicantStartedState
D/WifiStateMachine( 1004): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1004): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/WifiStateMachine( 1004): invokeEnterMethods: SupplicantStoppingState
D/WifiStateMachine( 1004): Stopping DHCP and clearing IP
D/WifiStateMachine( 1004): setSuspendOptimizationsNative: 1 true
,I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/WifiP2pService( 1004): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1004): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 1004): resetConnections(wlan0, 3)
D/NetUtils( 1004): android_net_utils_resetConnections in env=0x60057bf8 clazz=0x63200001 iface=wlan0 mask=0x3
V/NativeCrypto( 1342): Read error: ssl=0x62a35dc8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1342): SSL shutdown failed: ssl=0x62a35dc8: I/O error during system call, Broken pipe
,W/ContextImpl( 4055): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothPbapService( 1788): action: android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothManagerService( 1004): Message: 20
,D/BluetoothManagerService( 1004): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42570dd8:true
,D/CommandListener(  272): Clearing all IP addresses on wlan0
,D/WifiStateMachine( 1004): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/BluetoothManagerService( 1004): Message: 30
,D/WifiStateMachine( 1004): stopping supplicant
,W/ContextImpl( 4055): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
D/WifiStateMachine( 1004): setWifiState: disabling
D/BluetoothManagerService( 1004): Message: 30
I/SBar.NetworkController( 1084): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
W/XTWiFiOS( 1279): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1004): handleMessage: X
W/XTWiFiOS( 1279): Active network info is not available
D/Checkin ( 1004): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/XTCC-3.0.0.2(  467): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  467): [WwanPosMgr] handleConnectivtyStatusChange failed
,I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=false Wifi=(none) Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,W/ContextImpl( 4055): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 4055): Adding local MAP profile
D/BluetoothMap( 4055): Create BluetoothMap proxy object
D/BluetoothManagerService( 1004): Message: 30
I/bt_hwcfg( 1788): hw_epilog_process
W/bt-btif ( 1788): ag scb idx 1 not allocated
E/bt-btif ( 1788): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1788): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1788): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1788): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1788): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1788): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1788): L2CAP - PSM: 0x0017 not found for deregistration
W/ContextImpl( 4055): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/Nat464Xlat( 1004): requiresClat: netType=1, hasIPv4Address=false
E/XTCC-3.0.0.2(  467): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  467): [CSMgr] handleConnectivtyStatusChange failed
,D/ConnectivityService( 1004): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/BluetoothManagerService( 1004): Message: 30
D/ConnectivityService( 1004): Attempting to switch to mobile
D/ConnectivityService( 1004): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1004): Attempting to switch to ETHERNET
I/ModemStatsDSDetect( 1301): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1301): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1301): onReceive() - done, currentInetCondition=0
D/Nat464Xlat( 1004): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1004): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1301): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1301): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1301): onReceive() - done, currentInetCondition=0
,W/ContextImpl( 4055): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 4055): LocalBluetoothProfileManager construction complete
I/bt_hwcfg( 1788): hw_epilog_cback Opcode:0x0C03 Status: 0
I/bt_hci_bdroid( 1788): bt_hc_worker_thread exiting
D/bt_userial_mct( 1788): userial_close
I/bt_userial_mct( 1788): exiting userial_read_thread
D/bt_userial_mct( 1788): Leaving userial_evt_read_thread()
D/TCMD    (  462): NL - Read 1000 bytes from update socket.
D/TCMD    (  462): NL - message type is RTM_NEWLINK
D/TCMD    (  462): Listening for incoming client connection request
D/TCMD    (  462): NL - Read 68 bytes from update socket.
D/TCMD    (  462): NL - message type is RTM_NEWLINK
D/TCMD    (  462): Listening for incoming client connection request
D/TCMD    (  462): NL - Read 68 bytes from update socket.
D/TCMD    (  462): NL - message type is RTM_NEWLINK
D/TCMD    (  462): Listening for incoming client connection request
D/DockEventReceiver( 4055): finishStartingService: stopping service
I/wpa_supplicant( 1161): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
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
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
D/WifiStateMachine( 1004): handleMessage: E msg.what=147460
D/WifiStateMachine( 1004): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1004): processMsg: DefaultState
D/WifiStateMachine( 1004): handleMessage: X
D/WifiStateMachine( 1004): handleMessage: E msg.what=147462
D/WifiStateMachine( 1004): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1004): processMsg: DefaultState
D/WifiStateMachine( 1004): handleMessage: X
D/Tethering( 1004): InitialState.processMessage what=4
D/Tethering( 1004): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/Tethering( 1004): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1004): handleMessage: E msg.what=131101
D/WifiStateMachine( 1004): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1004): processMsg: DefaultState
,D/WifiStateMachine( 1004): handleMessage: X
D/WifiService( 1004): New client listening to asynchronous messages
,D/BluetoothInputDevice( 4055): Proxy object connected
,D/HidProfile( 4055): Bluetooth service connected
D/BluetoothPan( 4055): BluetoothPAN Proxy object connected
,D/PanProfile( 4055): Bluetooth service connected
D/BluetoothMap( 4055): Proxy object connected
,D/MapProfile( 4055): Bluetooth service connected
,D/BluetoothMap( 4055): getConnectedDevices()
,D/BluetoothMap( 4055): Bluetooth is Not enabled
,V/BluetoothFtpReceiver( 1788): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,I/ActivityManager( 1004): Killing 3783:com.android.calendar/u0a7 (adj 15): empty #9
,D/AuthorizationBluetoothService( 1342): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/wpa_supplicant( 1161): eap_proxy Deinitialzed
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1 38:f8:89
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 1 38:f8:89
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2 06:7c:34
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 2 06:7c:34
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3 64:7c:34
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 3 64:7c:34
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4 10:9a:dd
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 4 10:9a:dd
,D/WifiStateMachine( 1004): handleMessage: E msg.what=196614
D/WifiStateMachine( 1004): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1004): processMsg: DefaultState
,D/WifiStateMachine( 1004): handleMessage: X
,D/TCMD    (  462): NL - Read 1000 bytes from update socket.
D/TCMD    (  462): NL - message type is RTM_NEWLINK
D/TCMD    (  462): Listening for incoming client connection request
I/wpa_supplicant( 1161): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  274): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  274):  Wpa Supplicant Exiting !!
D/MDMCTBK (  274): wifi_wait_on_socket: Exiting monitor thread
,D/MDMCTBK (  274): wifi_close_sockets: Close Wifi socket
D/WifiStateMachine( 1004): handleMessage: E msg.what=147458
D/WifiStateMachine( 1004): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1004): Supplicant connection lost
,D/MDMCTBK (  274): wifi_close_sockets: Exit
,D/AndroidRuntime( 4085): 
D/AndroidRuntime( 4085): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4085): CheckJNI is OFF
,D/dalvikvm( 4085): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4085): Added shared lib libjavacore.so 0x0
D/BTSNOOP-DISP( 1788): btsnoop_close
I/bt_vendor( 1788): cleanup
I/bt_hwcfg( 1788): Starting hciattach daemon
I/bt_hwcfg( 1788): try to set false
I/GKI_LINUX( 1788): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 1788): GKI_exit_task: GKI_exit_task 0 done
,I/GKI_LINUX( 1788): GKI_destroy_task: GKI_shutdown(): task [BTU] terminated
D/dalvikvm( 4085): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4085): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4085): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/BluetoothAdapterState( 1788): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 1788): Received stop request...Stopping profile...
,D/BluetoothHeadset( 1004): Proxy object disconnected
D/BluetoothHeadset( 1268): Proxy object disconnected
,D/BluetoothHeadset( 1268): Proxy object disconnected
D/BluetoothHeadset( 1268): Proxy object disconnected
,D/A2dpService( 1788): Received stop request...Stopping profile...
D/A2dpStateMachine( 1788): Exit Disconnected: -1
D/BluetoothA2dp( 1004): Proxy object disconnected
D/BluetoothAdapterService( 1788): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHeadsetServiceJni( 1788): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 1788): Cleaning up Bluetooth Handsfree callback object
D/HidService( 1788): Received stop request...Stopping profile...
D/BluetoothInputDevice( 4055): Proxy object disconnected
D/HidProfile( 4055): Bluetooth service disconnected
D/BluetoothAdapterState( 1788): Stopping profile services that were post enabled
D/HealthService( 1788): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1788): Profile still running: com.android.bluetooth.hdp.HealthService
I/GKI_LINUX( 1788): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 1788): GKI_exit_task: GKI_exit_task 2 done
I/GKI_LINUX( 1788): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
D/PanService( 1788): Received stop request...Stopping profile...
D/BluetoothTethering( 1004): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering( 1004): attempted to stop reverse tether with nothing tethered
,D/BluetoothTethering( 1004): Disconnect CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@428c3648
,D/BluetoothTethering( 1004): got CMD_CHANNEL_DISCONNECTED
D/BluetoothPan( 1004): BluetoothPAN Proxy object disconnected
D/BluetoothPan( 4055): BluetoothPAN Proxy object disconnected
,D/PanProfile( 4055): Bluetooth service disconnected
,D/BtGatt.DebugUtils( 1788): handleDebugAction() action=null
D/BtGatt.GattService( 1788): Received stop request...Stopping profile...
,D/BtGatt.GattService( 1788): stop()
,D/BluetoothAdapterService( 1788): Profile still running: com.android.bluetooth.hdp.HealthService
D/BluetoothMapService( 1788): Received stop request...Stopping profile...
,D/BluetoothMapService( 1788): stop()
,D/BluetoothMapService( 1788): MAP Service closeService in
D/BluetoothMap( 4055): Proxy object disconnected
,D/MapProfile( 4055): Bluetooth service disconnected
W/BluetoothHidServiceJni( 1788): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 1788): cleanup: HH disabling or disabled already, status = 0
,W/BluetoothHidServiceJni( 1788): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 1788): Profile still running: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothHealthServiceJni( 1788): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 1788): Cleaning up Bluetooth Health object
,D/BluetoothAdapterService( 1788): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 1788): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 1788): Cleaning up Bluetooth PAN callback object
,D/BluetoothAdapterService( 1788): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/BluetoothMapService( 1788): cleanup()
,D/BluetoothMapService( 1788): MAP Service closeService in
D/BluetoothAdapterState( 1788): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1788): Setting state to 10
I/BluetoothAdapterState( 1788): Bluetooth adapter state changed: 13-> 10
,D/BluetoothAdapterService( 1788): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1004): Message: 60
D/BluetoothManagerService( 1004): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
,D/BluetoothManagerService( 1004): Broadcasting onBluetoothStateChange(false) to 10 receivers.
D/BluetoothHeadset( 1268): onBluetoothStateChange: up=false
,I/BluetoothAdapterState( 1788): Entering OffState
D/BluetoothPan( 1004): onBluetoothStateChange on: false
D/BluetoothHeadset( 1004): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1268): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1268): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1004): onBluetoothStateChange: up=false
,D/BluetoothPbap( 4055): onBluetoothStateChange: up=false
D/dalvikvm( 4085): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,D/BluetoothPan( 4055): onBluetoothStateChange on: false
,D/BluetoothInputDevice( 4055): onBluetoothStateChange: up=false
,D/BluetoothMap( 4055): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1004): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService( 1004): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/BluetoothManagerService( 1004): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@42492c10 mBinding = false
,D/BluetoothManagerService( 1004): Sending unbind request.
,D/BluetoothAdapterService( 1788): Cleaning up adapter native....
I/GKI_LINUX( 1788): gki_task_entry: gki_task task_id=1 [BTIF] terminating
D/BluetoothManagerService( 1004): Bluetooth State Change Intent: 13 -> 10
I/GKI_LINUX( 1788): GKI_exit_task: GKI_exit_task 1 done
,I/GKI_LINUX( 1788): GKI_destroy_task: GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 1788): cleanupNative: return from cleanup
,D/BluetoothAdapterService( 1788): Done cleaning up adapter native....
,D/BluetoothAdapterService(1107318160)( 1788): ****onDestroy()********
D/BtGatt.GattService( 1788): cleanup()
W/bt-btif ( 1788): GATTC Module not enabled/already disabled
,W/bt-btif ( 1788): GATTS Module not enabled/already disabled
,D/BluetoothAdapter( 1084): 1108789168: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1220): 1111348952: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1220): 1111348952: getState() :  mService = null. Returning STATE_OFF
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.sendDeviceAttachIntent:820 com.motorola.authentication.MotAuthenticationService.access$1300:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:575 
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.handleKeepDeviceUnlockRequest:732 com.motorola.authentication.MotAuthenticationService.access$1500:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:563 
W/ContextImpl( 4055): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 4055): finishStartingService: stopping service
,D/BluetoothAdapter( 4055): 1107355760: getState() :  mService = null. Returning STATE_OFF
,V/BluetoothFtpReceiver( 1788): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 1788): BluetoothFtpReceiver Stop Service
V/BluetoothFtpService( 1788): Ftp Service onDestroy
V/BluetoothFtpService( 1788): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 1788): Shutdown
,D/AuthorizationBluetoothService( 1342): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager( 1004): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.ConnectedUnlockReceiver: pid=4106 uid=10016 gids={50016, 3002}
,D/WifiStateMachine( 1004): setWifiState: disabled
,I/ActivityManager( 1004): Killing 3470:android.process.acore/u0a10 (adj 15): empty #9
D/WifiStateMachine( 1004): transitionTo: destState=InitialState
D/WifiStateMachine( 1004): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1004): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1004): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine( 1004): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1004): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
D/WifiStateMachine( 1004): invokeEnterMethods: InitialState
I/SBar.NetworkController( 1084): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
W/XTWiFiOS( 1279): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1279): Active network info is not available
E/XTCC-3.0.0.2(  467): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  467): [WwanPosMgr] handleConnectivtyStatusChange failed
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/Settings( 1220): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/XTCC-3.0.0.2(  467): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  467): [CSMgr] handleConnectivtyStatusChange failed
,D/BluetoothAdapter( 4055): 1107355760: getState() :  mService = null. Returning STATE_OFF
I/rmt_storage(  351): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8d091d0
I/rmt_storage(  351): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  351): wakelock acquired: 1, error no: 42
,I/rmt_storage(  351): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1194290632)
,I/ActivityManager( 1004): Killing 3848:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Checkin ( 4106): publish the event [tag = DEVICE_AUTH_STATS_L2 event name = DEVAUTH_CONNECT]
,E/memtrack( 4085): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4085): failed to load memtrack module: -2
,I/rmt_storage(  351): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  351): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  351): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1194290632) wakelock released: 1, error no: 0
I/rmt_storage(  351): 
,I/rmt_storage(  351): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb8d091d0
,D/Checkin ( 2296): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2296): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/AndroidRuntime( 4085): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1004): Force stopping com.example.hello appid=10404 user=-1: uninstall pkg
,I/ActivityManager( 1004): Killing 3989:com.example.hello/u0a404 (adj 0): stop com.example.hello
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1004):   Force finishing activity ActivityRecord{429fe8e0 u0 com.example.hello/.MainActivity t3}
,I/WindowState( 1004): WIN DEATH: Window{4283bb08 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1004): Client connection lost with reason: 4
,W/PackageSettings( 1004): Skipping PackageSetting{422bce68 com.test.thalitest/10403} due to missing metadata
,I/ActivityManager( 1004): Force stopping com.example.hello appid=10404 user=0: pkg removed
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager( 1004):   Force finishing activity ActivityRecord{429fe8e0 u0 com.example.hello/.MainActivity t3 f}
,W/ActivityManager( 1004): Duplicate finish request for ActivityRecord{429fe8e0 u0 com.example.hello/.MainActivity t3 f}
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1484): [info] > Updatetime from metadata: 10
,D/Checkin ( 1484): publish the event [tag = MOT_OTA event name = LOG]
,I/InputReader( 1004): Reconfiguring input devices.  changes=0x00000010
,D/dalvikvm( 2296): GC_EXPLICIT freed 5162K, 44% free 9656K/17224K, paused 3ms+7ms, total 61ms
,I/LatinIME:LogUtils( 1205): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/LatinIME:LogUtils( 1205): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,D/dalvikvm( 2328): GC_EXPLICIT freed 2673K, 44% free 9777K/17224K, paused 4ms+3ms, total 67ms
,D/dalvikvm( 1314): GC_EXPLICIT freed 3236K, 33% free 11594K/17224K, paused 2ms+5ms, total 83ms
,I/Launcher( 1314): Deferring update until onResume
,I/ActivityManager( 1004): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4124 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
D/OtaApp  ( 1484): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1484): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1484): publish the event [tag = MOT_OTA event name = LOG]
W/GeofencerStateMachine( 1220): Ignoring removeGeofence because network location is disabled.
,D/dalvikvm( 1004): GC_EXPLICIT freed 2031K, 15% free 18054K/21008K, paused 4ms+12ms, total 119ms
,D/dalvikvm( 1004): WAIT_FOR_CONCURRENT_GC blocked 14ms
,I/PackageManager( 1004): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1004):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1004):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1004):   Scheme: "sms"
,I/Launcher( 1314): Deferring update until onResume
,D/OtaApp  ( 1484): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/PackageManager( 1004): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1004):   Action: "android.intent.action.SENDTO"
D/TCMD    (  462): NL - Read 444 bytes from update socket.
D/TCMD    (  462): NL - ignore NL message, type = 17
D/TCMD    (  462): Listening for incoming client connection request
,D/NetlinkEvent(  272): Unexpected netlink message. type=0x11
W/Netd    (  272): No subsystem found in netlink event
I/PackageManager( 1004):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1004):   Scheme: "smsto"
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
,D/OtaApp  ( 1484): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/PackageManager( 1004): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1004):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1004):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1004):   Scheme: "mms"
,I/PackageManager( 1004): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1004):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1004):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1004):   Scheme: "mmsto"
,I/PackageManager( 1004): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1004):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1004):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1004):   Scheme: "sms"
,D/TCMD    (  462): NL - Read 1000 bytes from update socket.
D/TCMD    (  462): NL - message type is RTM_NEWLINK
,D/TCMD    (  462): Listening for incoming client connection request
,I/PackageManager( 1004): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1004):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1004):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1004):   Scheme: "smsto"
,I/PackageManager( 1004): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1004):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1004):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1004):   Scheme: "mms"
,I/PackageManager( 1004): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1004):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1004):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1004):   Scheme: "mmsto"
,W/InputMethodManagerService( 1004): Got RemoteException sending setActive(false) notification to pid 3989 uid 10404
W/Binder  ( 1205): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1205): java.lang.NullPointerException
W/Binder  ( 1205): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1205): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1205): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1205): 	at dalvik.system.NativeStart.run(Native Method)
,D/NetlinkEvent(  272): Unexpected netlink message. type=0x11
D/TCMD    (  462): NL - Read 444 bytes from update socket.
W/Netd    (  272): No subsystem found in netlink event
D/TCMD    (  462): NL - ignore NL message, type = 17
D/TCMD    (  462): Listening for incoming client connection request
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
I/LatinIME:LogUtils( 1205): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1448299023
,I/SFPerfTracer(  276):      triggers: (rate: 3:33) (compose: 0:4) (post: 0:1) (render: 0:5) (1:117 frames) (2:561)
,D/BackupManagerService( 1004): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/BackupManagerService( 1004): removePackageParticipantsLocked: uid=10404 #1
,D/SFPerfTracer(  276):        layers: (0:13) (FocusedStackFrame: 0:10)* (StatusBar: 0:211)* (NavigationBar: 0:40)* (com.android.systemui.ImageWallpaper: 0:6)* (Starting com.motorola.ccc.ota: 0:35)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:19)* (ElectronBeam: 0:26)* (com.example.hello/com.example.hello.MainActivity: 0:4)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 2:2)* 
D/VoicemailCleanupService( 4124): Cleaning up data for package: com.example.hello
,I/InternalIcingCorporaPro( 2328): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/ActivityManager( 1004): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4142 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,D/Checkin ( 2296): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2296): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,W/ContextImpl( 4142): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,I/LatinIME:LogUtils( 1205): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1448299023
,D/PackageBroadcastService( 1391): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1391): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1391): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1391): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1391): Removing dialog suppression flag for package com.example.hello
,D/dalvikvm( 1004): GC_EXPLICIT freed 812K, 15% free 18016K/21008K, paused 5ms+23ms, total 284ms
,E/NetworkScheduler.SchedulerReceiver( 1342): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1342): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/dalvikvm( 3541): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3541): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3541): VFY: replacing opcode 0x6e at 0x0013
,D/ChimeraCfgMgr( 1391): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1391): Module APK com.google.android.play.games already loaded
I/ActivityManager( 1004): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4164 uid=10058 gids={50058}
I/ActivityManager( 1004): Killing 3834:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/gH_CompatibleDatabase( 1391): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1391): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1391): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1391): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/dalvikvm(  277): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+2ms, total 22ms
,I/PeopleContactsSync( 1391): CP2 sync disabled
,D/gH_CompatibleDatabase( 1391): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1391): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1391): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 19ms
,D/dalvikvm(  277): WAIT_FOR_CONCURRENT_GC blocked 1ms
,D/gH_CompatibleDatabase( 1391): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1391): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1391): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1391): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1391): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1391): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 20ms
,D/AndroidRuntime( 4085): Shutting down VM
,D/dalvikvm( 4085): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 3ms
,I/Icing   ( 1391): doRemovePackageData com.example.hello
,I/InternalIcingCorporaPro( 2328): UpdateCorporaTask done [took 215 ms] updated apps [took 215 ms] 
I/ActivityManager( 1004): Killing 1788:com.android.bluetooth/1002 (adj 15): empty #9
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Documents( 4164): Loading roots for com.android.providers.downloads.documents
,I/ActivityManager( 1004): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4182 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/ActivityManager( 1004): Killing 4106:com.motorola.deviceauthenticator/u0a16 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1004): Killing 4055:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiService( 1004): Client connection lost with reason: 4
,I/ContactLocale( 4124): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/dalvikvm( 4182): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41ffa548, skipping init
I/openssl ( 4182): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4182): Crypto mode 0 already enabled
,D/Documents( 4164): Loading roots for com.android.externalstorage.documents
,I/ActivityManager( 1004): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4198 uid=10020 gids={50020, 1028, 1015, 1023}
,I/ActivityManager( 1004): Killing 4124:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ExternalStorage( 4198): After updating volumes, found 1 active roots
,D/Documents( 4164): Updating roots due to change at content://com.android.externalstorage.documents/root
,D/Documents( 4164): Loading roots for com.android.providers.media.documents
,D/Documents( 4164): Loading roots for com.google.android.apps.docs.storage
,D/Documents( 4164): Update found 7 roots in 192ms
D/Documents( 4164): Used cached roots for com.android.providers.downloads.documents
,D/Documents( 4164): Loading roots for com.android.externalstorage.documents
D/Documents( 4164): Used cached roots for com.android.providers.media.documents
D/Documents( 4164): Used cached roots for com.google.android.apps.docs.storage
,D/Documents( 4164): Update found 7 roots in 5ms
,D/Checkin ( 2296): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]

```
