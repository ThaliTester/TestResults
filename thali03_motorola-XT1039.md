#### Test 5038801913f4183_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 3964): 
D/AndroidRuntime( 3964): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3964): CheckJNI is OFF
D/dalvikvm( 3964): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3964): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3964): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3964): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3964): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3964): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3964): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3964): failed to load memtrack module: -2
D/AndroidRuntime( 3964): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3964
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3980 uid=10479 gids={50479, 3003, 3001, 3002}
D/AndroidRuntime( 3964): Shutting down VM
D/dalvikvm( 3964): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+0ms, total 4ms
W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3980): Binding Chromium to main looper Looper (main, tid 1) {41f75b38}
I/LibraryLoader( 3980): Expected native library version number "",actual native library version number ""
I/chromium( 3980): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3980): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41fbb668:true
I/Adreno-EGL( 3980): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3980): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3980): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3980): Local Branch: 
I/Adreno-EGL( 3980): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3980): Local Patches: NONE
I/Adreno-EGL( 3980): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3980): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3980): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3980): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3980): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3980): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3980): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3980): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3980): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3980): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3980): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3980): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3980): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3980): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3980): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3980): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3980): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3980): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3980): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3980): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3980): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3980): Enabling debug mode 0
,W/AwContents( 3980): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3980): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1019): Displayed com.example.hello/.MainActivity,cp,ca,299
,I/ActivityManager( 1019): Displayed com.example.hello/.MainActivity: +273ms (total +299ms)
I/SFPerfTracer(  273):      triggers: (rate: 3:36) (compose: 0:4) (post: 0:1) (render: 0:5) (0:122 frames) (1:553)
D/SFPerfTracer(  273):        layers: (0:12) (FocusedStackFrame: 0:10)* (StatusBar: 0:211)* (NavigationBar: 0:39)* (com.android.systemui.ImageWallpaper: 0:7)* (Starting com.motorola.ccc.ota: 0:34)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:19)* (ElectronBeam: 0:27)* (com.example.hello/com.example.hello.MainActivity: 1:3)* 
,I/chromium( 3980): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 3980): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 3980): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3980): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41f7a268
,D/dalvikvm( 3980): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41f7a268
D/jxcore_app_log( 3980): JniHelper::setJavaVM(0x415c9fa8), pthread_self() = 1609600856
,D/JX-Cordova( 3980): jxcore cordova android initializing
,W/jxcore-log( 3980): Initializing JXcore engine
,W/jxcore-log( 3980): JXcore engine is ready
,W/jxcore-log( 3980): Starting JXcore engine
,W/jxcore-log( 3980): Platform android
W/jxcore-log( 3980): 
,W/jxcore-log( 3980): Process ARCH arm
W/jxcore-log( 3980): 
,I/jxcore-log( 3980): JXcore Cordova bridge is ready!
I/jxcore-log( 3980): 
,W/jxcore-log( 3980): JXcore engine is started
,E/jxcore-log( 3980): >> motorola-XT1039
E/jxcore-log( 3980): 
,I/jxcore-log( 3980): Total memory 893136896
I/jxcore-log( 3980): 
I/jxcore-log( 3980): Free memory 46727168
I/jxcore-log( 3980): 
,I/jxcore-log( 3980): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3980): 
,I/jxcore-log( 3980): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3980): 
,I/jxcore-log( 3980): userPath [ 'www' ]
I/jxcore-log( 3980): 
,I/jxcore-log( 3980): Size 720 1184
I/jxcore-log( 3980): 
,I/jxcore-log( 3980): Screen Brightness 10
I/jxcore-log( 3980): 
,E/jxcore-log( 3980): Dummy Error Log.
E/jxcore-log( 3980): 
,I/jxcore-log( 3980): getBuffer is called!!!!
I/jxcore-log( 3980): 
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1019): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@424ff470 mBinding = false
,W/Settings( 1284): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/XTWiFiOS( 1301): No entry in secure settings for enhanced location services: false
,W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1284): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BluetoothManagerService( 1019): Message: 2
,D/BluetoothManagerService( 1019): Sending off request.
,D/BluetoothAdapterState( 1804): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
,D/BluetoothAdapterProperties( 1804): Setting state to 13
I/BluetoothAdapterState( 1804): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 1804): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterProperties( 1804): onBluetoothDisable()
,I/BluetoothAdapterState( 1804): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,I/BluetoothAdapterProperties( 1804): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothAdapterProperties( 1804): Scan Mode:21
,D/BluetoothAdapterState( 1804): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,D/BluetoothManagerService( 1019): Message: 60
,E/BtOppRfcommListener( 1804): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,V/BluetoothFtpService:RfcommSocketAcceptThread( 1804): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 1804): bta_jv_rfcomm_stop_server
,D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 12 -> 13
E/bt-btif ( 1804): bta_jv_rfcomm_stop_server
E/bt-btif ( 1804): bta_jv_rfcomm_stop_server
,E/bt-btif ( 1804): bta_jv_rfcomm_stop_server
,W/bt-btif ( 1804): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,W/bt-l2cap( 1804): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1804): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothMapService( 1804): onReceive
D/BluetoothMapService( 1804): STATE_TURNING_OFF removeTimeoutMsg:false
,D/BluetoothMapService( 1804): MAP Service closeService in
,I/ActivityManager( 1019): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=4045 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/btif_config_util( 1804): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/WifiService( 1019): New client listening to asynchronous messages
D/WifiService( 1019): setWifiEnabled: false pid=3980, uid=10479
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
,I/BtOppRfcommListener( 1804): stopping Accept Thread
,I/BtOppRfcommListener( 1804): BluetoothSocket listen thread finished
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131084
D/WifiStateMachine( 1019): processMsg: ConnectedState
,W/Settings( 1284): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
I/jxcore-log( 3980): ****TEST TOOK:  5215  ms ****
I/jxcore-log( 3980): 
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): transitionTo: destState=WaitForP2pDisableState
,I/jxcore-log( 3980): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3980): 
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
,D/WifiStateMachine( 1019): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1019): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1301): No entry in secure settings for enhanced location services: false
W/Settings( 1284): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/CommandListener(  269): Clearing all IP addresses on wlan0
D/TCMD    (  471): NL - Read 60 bytes from update socket.
D/TCMD    (  471): NL - ignore NL message, type = 21
D/TCMD    (  471): Listening for incoming client connection request
D/WifiStateMachine( 1019): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1019): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/WifiMetrics( 1019): connected time updated 100527
D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1019): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService( 1019): Attempting to switch to mobile
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1019): Attempting to switch to ETHERNET
,D/WifiStateMachine( 1019): invokeExitMethods: ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: DriverStartedState
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=2
,D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
D/WifiStateMachine( 1019): invokeEnterMethods: WaitForP2pDisableState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiP2pService( 1019): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: E msg.what=131216
D/WifiStateMachine( 1019): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiP2pService( 1019): P2pDisablingState
D/WifiP2pService( 1019): P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): p2p socket connection lost
,D/WifiP2pService( 1019): P2pDisabledState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131216
D/WifiStateMachine( 1019): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131205
D/WifiStateMachine( 1019): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1019): transitionTo: destState=SupplicantStoppingState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: WaitForP2pDisableState
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStartedState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
,D/ConnectivityService( 1019): resetConnections(wlan0, 3)
D/NetUtils( 1019): android_net_utils_resetConnections in env=0x5fdd6940 clazz=0x60b00001 iface=wlan0 mask=0x3
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStoppingState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,W/ContextImpl( 4045): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/BluetoothPbapService( 1804): action: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42a617c0:true
,D/WifiP2pService( 1019): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService( 1019): Message: 30
V/NativeCrypto( 1361): Read error: ssl=0x63262d58: I/O error during system call, Connection timed out
V/NativeCrypto( 1361): SSL shutdown failed: ssl=0x63262d58: I/O error during system call, Broken pipe
D/CommandListener(  269): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): stopping supplicant
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiStateMachine( 1019): setWifiState: disabling
,W/ContextImpl( 4045): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
W/XTWiFiOS( 1301): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1082): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
W/XTWiFiOS( 1301): Active network info is not available
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
E/XTCC-3.0.0.2(  586): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  586): [WwanPosMgr] handleConnectivtyStatusChange failed
I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=false Wifi=(none) Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
E/XTCC-3.0.0.2(  586): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  586): [CSMgr] handleConnectivtyStatusChange failed
D/WifiStateMachine( 1019): handleMessage: X
D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 4045): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
I/bt_hwcfg( 1804): hw_epilog_process
W/bt-btif ( 1804): ag scb idx 1 not allocated
E/bt-btif ( 1804): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1804): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1804): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1804): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1804): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1804): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1804): L2CAP - PSM: 0x0017 not found for deregistration
D/LocalBluetoothProfileManager( 4045): Adding local MAP profile
D/BluetoothMap( 4045): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 4045): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/BluetoothManagerService( 1019): Message: 30
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
I/ModemStatsDSDetect( 1311): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,W/ContextImpl( 4045): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
I/ModemStatsDSDetect( 1311): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1311): onReceive() - done, currentInetCondition=0
,D/LocalBluetoothProfileManager( 4045): LocalBluetoothProfileManager construction complete
D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1019): Attempting to switch to ETHERNET
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1311): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1311): INET_CONDITION=0 ,activeNet=null
I/bt_hwcfg( 1804): hw_epilog_cback Opcode:0x0C03 Status: 0
I/ModemStatsDSDetect( 1311): onReceive() - done, currentInetCondition=0
I/bt_hci_bdroid( 1804): bt_hc_worker_thread exiting
D/bt_userial_mct( 1804): userial_close
I/bt_userial_mct( 1804): exiting userial_read_thread
D/bt_userial_mct( 1804): Leaving userial_evt_read_thread()
D/DockEventReceiver( 4045): finishStartingService: stopping service
,D/WifiService( 1019): New client listening to asynchronous messages
D/TCMD    (  471): NL - Read 1000 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
D/TCMD    (  471): NL - Read 68 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
D/TCMD    (  471): NL - Read 68 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
I/wpa_supplicant( 1160): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  272): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  272): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:
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
D/MDMCTBK (  272): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
D/WifiStateMachine( 1019): handleMessage: E msg.what=147460
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/Tethering( 1019): InitialState.processMessage what=4
D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/BluetoothInputDevice( 4045): Proxy object connected
D/HidProfile( 4045): Bluetooth service connected
D/BluetoothPan( 4045): BluetoothPAN Proxy object connected
D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/PanProfile( 4045): Bluetooth service connected
D/BluetoothMap( 4045): Proxy object connected
D/MapProfile( 4045): Bluetooth service connected
D/BluetoothMap( 4045): getConnectedDevices()
V/BluetoothFtpReceiver( 1804): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMap( 4045): Bluetooth is Not enabled
,D/AuthorizationBluetoothService( 1361): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager( 1019): Killing 3722:com.android.calendar/u0a7 (adj 15): empty #9
W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/wpa_supplicant( 1160): eap_proxy Deinitialzed
D/MDMCTBK (  272): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4
D/MDMCTBK (  272): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1 64:7c:34
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 1 64:7c:34
D/MDMCTBK (  272): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2 06:7c:34
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 2 06:7c:34
D/MDMCTBK (  272): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3 38:f8:89
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 3 38:f8:89
D/MDMCTBK (  272): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4 9e:93:4e
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 4 9e:93:4e
D/MDMCTBK (  272): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5 64:7c:34
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 5 64:7c:34
D/MDMCTBK (  272): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6 0c:bd:51
,D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 6 0c:bd:51
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196614
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,D/TCMD    (  471): NL - Read 1000 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
,D/TCMD    (  471): Listening for incoming client connection request
I/wpa_supplicant( 1160): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  272): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  272):  Wpa Supplicant Exiting !!
D/MDMCTBK (  272): wifi_wait_on_socket: Exiting monitor thread
,D/MDMCTBK (  272): wifi_close_sockets: Close Wifi socket
D/WifiStateMachine( 1019): handleMessage: E msg.what=147458
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
,D/WifiStateMachine( 1019): Supplicant connection lost
,D/MDMCTBK (  272): wifi_close_sockets: Exit
,D/BTSNOOP-DISP( 1804): btsnoop_close
,I/bt_vendor( 1804): cleanup
I/bt_hwcfg( 1804): Starting hciattach daemon
I/bt_hwcfg( 1804): try to set false
I/GKI_LINUX( 1804): gki_task_entry: gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 1804): GKI_exit_task: GKI_exit_task 0 done
,I/GKI_LINUX( 1804): GKI_destroy_task: GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 1804): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 1804): Received stop request...Stopping profile...
,D/BluetoothHeadset( 1019): Proxy object disconnected
D/BluetoothHeadset( 1267): Proxy object disconnected
D/BluetoothHeadset( 1267): Proxy object disconnected
,D/BluetoothHeadset( 1267): Proxy object disconnected
,D/A2dpService( 1804): Received stop request...Stopping profile...
D/A2dpStateMachine( 1804): Exit Disconnected: -1
,D/BluetoothA2dp( 1019): Proxy object disconnected
,D/BluetoothAdapterService( 1804): Profile still running: com.android.bluetooth.hdp.HealthService
,D/HidService( 1804): Received stop request...Stopping profile...
,D/BluetoothAdapterState( 1804): Stopping profile services that were post enabled
W/BluetoothHeadsetServiceJni( 1804): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 1804): Cleaning up Bluetooth Handsfree callback object
D/BluetoothInputDevice( 4045): Proxy object disconnected
D/HidProfile( 4045): Bluetooth service disconnected
,D/HealthService( 1804): Received stop request...Stopping profile...
,D/PanService( 1804): Received stop request...Stopping profile...
,D/BluetoothTethering( 1019): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering( 1019): attempted to stop reverse tether with nothing tethered
D/BluetoothTethering( 1019): Disconnect CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@420a42f0
,D/BluetoothPan( 1019): BluetoothPAN Proxy object disconnected
D/BtGatt.DebugUtils( 1804): handleDebugAction() action=null
D/BluetoothTethering( 1019): got CMD_CHANNEL_DISCONNECTED
D/BluetoothPan( 4045): BluetoothPAN Proxy object disconnected
,D/PanProfile( 4045): Bluetooth service disconnected
D/BtGatt.GattService( 1804): Received stop request...Stopping profile...
,D/BtGatt.GattService( 1804): stop()
,D/BluetoothAdapterService( 1804): Profile still running: com.android.bluetooth.hdp.HealthService
I/GKI_LINUX( 1804): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 1804): GKI_exit_task: GKI_exit_task 2 done
,I/GKI_LINUX( 1804): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
,D/BluetoothAdapterService( 1804): Profile still running: com.android.bluetooth.hdp.HealthService
D/BluetoothMapService( 1804): Received stop request...Stopping profile...
,D/BluetoothMapService( 1804): stop()
,D/BluetoothMapService( 1804): MAP Service closeService in
W/BluetoothHidServiceJni( 1804): Cleaning up Bluetooth HID Interface...
D/BluetoothMap( 4045): Proxy object disconnected
W/bt-btif ( 1804): cleanup: HH disabling or disabled already, status = 0
D/MapProfile( 4045): Bluetooth service disconnected
,W/BluetoothHidServiceJni( 1804): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 1804): Profile still running: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothHealthServiceJni( 1804): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 1804): Cleaning up Bluetooth Health object
,D/BluetoothAdapterService( 1804): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 1804): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 1804): Cleaning up Bluetooth PAN callback object
,D/BluetoothAdapterService( 1804): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/BluetoothMapService( 1804): cleanup()
D/BluetoothMapService( 1804): MAP Service closeService in
D/BluetoothAdapterState( 1804): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1804): Setting state to 10
I/BluetoothAdapterState( 1804): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 1804): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1019): Message: 60
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
,D/BluetoothManagerService( 1019): Broadcasting onBluetoothStateChange(false) to 10 receivers.
I/BluetoothAdapterState( 1804): Entering OffState
D/BluetoothHeadset( 1267): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 1019): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1267): onBluetoothStateChange: up=false
,D/BluetoothPan( 1019): onBluetoothStateChange on: false
D/BluetoothHeadset( 1267): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1019): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 4045): onBluetoothStateChange: up=false
,D/BluetoothPan( 4045): onBluetoothStateChange on: false
,D/BluetoothMap( 4045): onBluetoothStateChange: up=false
,D/BluetoothPbap( 4045): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1019): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService( 1019): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService( 1019): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@424ff470 mBinding = false
,D/BluetoothManagerService( 1019): Sending unbind request.
,D/BluetoothAdapterService( 1804): Cleaning up adapter native....
I/GKI_LINUX( 1804): gki_task_entry: gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 1804): GKI_exit_task: GKI_exit_task 1 done
,I/GKI_LINUX( 1804): GKI_destroy_task: GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 1804): cleanupNative: return from cleanup
D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapterService( 1804): Done cleaning up adapter native....
,D/BluetoothAdapter( 1082): 1108264728: getState() :  mService = null. Returning STATE_OFF
W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.sendDeviceAttachIntent:820 com.motorola.authentication.MotAuthenticationService.access$1300:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:575 
,W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.handleKeepDeviceUnlockRequest:732 com.motorola.authentication.MotAuthenticationService.access$1500:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:563 
D/BluetoothAdapter( 1217): 1111185824: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1217): 1111185824: getState() :  mService = null. Returning STATE_OFF
D/WifiStateMachine( 1019): setWifiState: disabled
D/WifiStateMachine( 1019): transitionTo: destState=InitialState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
D/WifiStateMachine( 1019): invokeEnterMethods: InitialState
W/XTWiFiOS( 1301): No entry in secure settings for enhanced location services: false
W/XTWiFiOS( 1301): Active network info is not available
D/BluetoothAdapterService(1106798064)( 1804): ****onDestroy()********
E/XTCC-3.0.0.2(  586): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  586): [WwanPosMgr] handleConnectivtyStatusChange failed
I/SBar.NetworkController( 1082): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/BtGatt.GattService( 1804): cleanup()
W/bt-btif ( 1804): GATTC Module not enabled/already disabled
W/bt-btif ( 1804): GATTS Module not enabled/already disabled
,E/XTCC-3.0.0.2(  586): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  586): [CSMgr] handleConnectivtyStatusChange failed
,D/AndroidRuntime( 4077): 
D/AndroidRuntime( 4077): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4077): CheckJNI is OFF
,D/dalvikvm( 4077): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4077): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4077): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4077): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4077): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4077): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,D/dalvikvm( 1019): GC_EXPLICIT freed 2464K, 15% free 18093K/21152K, paused 4ms+9ms, total 96ms
,W/ContextImpl( 4045): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
W/Settings( 1217): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/DockEventReceiver( 4045): finishStartingService: stopping service
,D/BluetoothAdapter( 4045): 1106819736: getState() :  mService = null. Returning STATE_OFF
,V/BluetoothFtpReceiver( 1804): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 1804): BluetoothFtpReceiver Stop Service
,V/BluetoothFtpService( 1804): Ftp Service onDestroy
V/BluetoothFtpService( 1804): Ftp Service closeService
,E/BluetoothFtpService:RfcommSocketAcceptThread( 1804): Shutdown
,D/AuthorizationBluetoothService( 1361): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager( 1019): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.ConnectedUnlockReceiver: pid=4097 uid=10016 gids={50016, 3002}
,I/ActivityManager( 1019): Killing 3430:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/rmt_storage(  446): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7f531d0
I/rmt_storage(  446): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  446): wakelock acquired: 1, error no: 42
I/rmt_storage(  446): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1208667592)
,D/BluetoothAdapter( 4045): 1106819736: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager( 1019): Killing 3814:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Checkin ( 4097): publish the event [tag = DEVICE_AUTH_STATS_L2 event name = DEVAUTH_CONNECT]
,E/memtrack( 4077): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4077): failed to load memtrack module: -2
,I/rmt_storage(  446): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  446): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  446): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1208667592) wakelock released: 1, error no: 0
I/rmt_storage(  446): 
,I/rmt_storage(  446): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb7f531d0
,D/Checkin ( 2326): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2326): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/AndroidRuntime( 4077): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10479 user=-1: uninstall pkg
,I/ActivityManager( 1019): Killing 3980:com.example.hello/u0a479 (adj 0): stop com.example.hello
,W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019):   Force finishing activity ActivityRecord{42a28da8 u0 com.example.hello/.MainActivity t3}
,I/WindowState( 1019): WIN DEATH: Window{42a30978 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1019): Client connection lost with reason: 4
,W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10479 user=0: pkg removed
,D/TCMD    (  471): NL - Read 444 bytes from update socket.
D/TCMD    (  471): NL - ignore NL message, type = 17
D/TCMD    (  471): Listening for incoming client connection request
,D/NetlinkEvent(  269): Unexpected netlink message. type=0x11
W/Netd    (  269): No subsystem found in netlink event
I/MDMCTBK (  272): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  272): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  272): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  272): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
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
,D/dalvikvm( 2326): GC_EXPLICIT freed 5169K, 44% free 9655K/17224K, paused 2ms+6ms, total 37ms
,D/dalvikvm( 1412): GC_EXPLICIT freed 763K, 31% free 11939K/17224K, paused 4ms+5ms, total 52ms
,W/SQLiteConnectionPool( 1412): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/TCMD    (  471): NL - Read 1000 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
,D/TCMD    (  471): Listening for incoming client connection request
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/OtaApp  ( 1565): [info] > Updatetime from metadata: 10
,D/Checkin ( 1565): publish the event [tag = MOT_OTA event name = LOG]
I/ActivityManager( 1019): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4114 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
,W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,D/TCMD    (  471): NL - Read 444 bytes from update socket.
,D/NetlinkEvent(  269): Unexpected netlink message. type=0x11
W/Netd    (  269): No subsystem found in netlink event
D/TCMD    (  471): NL - ignore NL message, type = 17
D/TCMD    (  471): Listening for incoming client connection request
D/OtaApp  ( 1565): [debug] > cancelling the previous pending intent set for install later
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
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
I/MDMCTBK (  272): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  272): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  272): set_property_value, Enter
I/MDMCTBK (  272): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
E/MDMCTBK (  272): MdmCutbackHndler,Airplane Mode Enabled !! =1
I/LatinIME:LogUtils( 1203): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/OtaApp  ( 1565): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1565): publish the event [tag = MOT_OTA event name = LOG]
I/LatinIME:LogUtils( 1203): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,D/dalvikvm( 2361): GC_EXPLICIT freed 2753K, 43% free 9818K/17224K, paused 7ms+4ms, total 111ms
,D/dalvikvm( 1325): GC_EXPLICIT freed 3240K, 33% free 11594K/17224K, paused 2ms+6ms, total 120ms
,I/dalvikvm( 1019): Jit: resizing JitTable from 8192 to 16384
,I/Launcher( 1325): Deferring update until onResume
,W/GeofencerStateMachine( 1217): Ignoring removeGeofence because network location is disabled.
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
D/OtaApp  ( 1565): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,D/OtaApp  ( 1565): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,D/dalvikvm( 1019): GC_EXPLICIT freed 775K, 15% free 18149K/21152K, paused 11ms+81ms, total 207ms
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/Launcher( 1325): Deferring update until onResume
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10479 #1
,W/InputMethodManagerService( 1019): Got RemoteException sending setActive(false) notification to pid 3980 uid 10479
W/Binder  ( 1203): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1203): java.lang.NullPointerException
W/Binder  ( 1203): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1203): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1203): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1203): 	at dalvik.system.NativeStart.run(Native Method)
,D/AndroidRuntime( 4077): Shutting down VM
,D/dalvikvm( 4077): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 3ms
,D/Checkin ( 2326): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2326): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/LatinIME:LogUtils( 1203): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450199059
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/LatinIME:LogUtils( 1203): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450199059
,D/VoicemailCleanupService( 4114): Cleaning up data for package: com.example.hello
,I/InternalIcingCorporaPro( 2361): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4137 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,W/ContextImpl( 4137): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,I/dalvikvm( 3482): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3482): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3482): VFY: replacing opcode 0x6e at 0x0013
,D/PackageBroadcastService( 1412): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1412): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 1412): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1412): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1412): Removing dialog suppression flag for package com.example.hello
,D/ChimeraCfgMgr( 1412): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1412): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1361): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1361): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1412): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1412): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1412): 0 metrics were deleted when clearing package com.example.hello.
,D/gH_CompatibleDatabase( 1412): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1412): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1412): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1412): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/InternalIcingCorporaPro( 2361): UpdateCorporaTask done [took 125 ms] updated apps [took 125 ms] 
,D/gH_CompatibleDatabase( 1412): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1412): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1412): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1412): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1412): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1412): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager( 1019): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4158 uid=10058 gids={50058}
,I/ActivityManager( 1019): Killing 3791:com.android.defcontainer/u0a13 (adj 15): empty #9
I/Icing   ( 1412): doRemovePackageData com.example.hello
,W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Killing 1804:com.android.bluetooth/1002 (adj 15): empty #9
,W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Documents( 4158): Loading roots for com.android.providers.downloads.documents
,E/SQLiteDatabase( 4158): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4158): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4158): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4158): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4158): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4158): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4158): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4158): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4158): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4158): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4158): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4158): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4158): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4158): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4158): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4158): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4158): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4158): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 4158): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/SQLiteDatabase( 4158): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4158): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/SQLiteDatabase( 4158): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/SQLiteDatabase( 4158): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/SQLiteDatabase( 4158): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4158): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4158): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4158): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4158): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4158): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4158): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4158): 	at dalvik.system.NativeStart.main(Native Method)
,I/ActivityManager( 1019): Killing 4097:com.motorola.deviceauthenticator/u0a16 (adj 15): empty #9
D/AndroidRuntime( 4158): Shutting down VM
,W/dalvikvm( 4158): threadid=1: thread exiting with uncaught exception (group=0x416a8d40)
W/ContextImpl( 1284): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
E/AndroidRuntime( 4158): FATAL EXCEPTION: main
E/AndroidRuntime( 4158): Process: com.android.documentsui, PID: 4158
E/AndroidRuntime( 4158): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4158): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 4158): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 4158): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 4158): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4158): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4158): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4158): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4158): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4158): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4158): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4158): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4158): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4158): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4158): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4158): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4158): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4158): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4158): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4158): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4158): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4158): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4158): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4158): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4158): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4158): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4158): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4158): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4158): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 4158): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/AndroidRuntime( 4158): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4158): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 4158): 	... 10 more
,I/Process ( 4158): Sending signal. PID: 4158 SIG: 9
E/DropBoxManagerService( 1019): Can't write: system_app_crash
E/DropBoxManagerService( 1019): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager( 1019): Process com.android.documentsui (pid 4158) has died.
I/ContactLocale( 4114): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
E/SQLiteDatabase( 4114): Failed to open database '/data/data/com.android.providers.contacts/databases/profile.db'.
E/SQLiteDatabase( 4114): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4114): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4114): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4114): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4114): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4114): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4114): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4114): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4114): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4114): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4114): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4114): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4114): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4114): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4114): 	at com.android.providers.contacts.aggregation.ContactAggregator.<init>(ContactAggregator.java:276)
E/SQLiteDatabase( 4114): 	at com.android.providers.contacts.aggregation.ProfileAggregator.<init>(ProfileAggregator.java:43)
E/SQLiteDatabase( 4114): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1518)
E/SQLiteDatabase( 4114): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1588)
E/SQLiteDatabase( 4114): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1470)
E/SQLiteDatabase( 4114): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4114): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4114): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 4114): Couldn't open profile.db for writing (will try read-only):
E/SQLiteOpenHelper( 4114): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4114): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4114): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4114): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4114): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4114): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4114): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4114): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 4114): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 4114): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4114): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 4114): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 4114): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4114): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4114): 	at com.android.providers.contacts.aggregation.ContactAggregator.<init>(ContactAggregator.java:276)
E/SQLiteOpenHelper( 4114): 	at com.android.providers.contacts.aggregation.ProfileAggregator.<init>(ProfileAggregator.java:43)
E/SQLiteOpenHelper( 4114): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1518)
E/SQLiteOpenHelper( 4114): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1588)
E/SQLiteOpenHelper( 4114): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1470)
E/SQLiteOpenHelper( 4114): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4114): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 4114): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 4114): (8) statement aborts at 49: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
W/dalvikvm( 4114): threadid=10: thread exiting with uncaught exception (group=0x416a8d40)
E/AndroidRuntime( 4114): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 4114): Process: android.process.acore, PID: 4114
E/AndroidRuntime( 4114): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 4114): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4114): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4114): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4114): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4114): 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1674)
E/AndroidRuntime( 4114): 	at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1603)
E/AndroidRuntime( 4114): 	at com.android.providers.contacts.ContactsDatabaseHelper.onOpen(ContactsDatabaseHelper.java:875)
E/AndroidRuntime( 4114): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:267)
E/AndroidRuntime( 4114): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 4114): 	at com.android.providers.contacts.aggregation.ContactAggregator.<init>(ContactAggregator.java:276)
E/AndroidRuntime( 4114): 	at com.android.providers.contacts.aggregation.ProfileAggregator.<init>(ProfileAggregator.java:43)
E/AndroidRuntime( 4114): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1518)
E/AndroidRuntime( 4114): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1588)
E/AndroidRuntime( 4114): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1470)
E/AndroidRuntime( 4114): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4114): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4114): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 4114): Sending signal. PID: 4114 SIG: 9
E/DropBoxManagerService( 1019): Can't write: system_app_crash
E/DropBoxManagerService( 1019): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager( 1019): Process android.process.acore (pid 4114) has died.

```
