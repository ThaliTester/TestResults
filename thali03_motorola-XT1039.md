#### Test 543122980a88295_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 3982): 
D/AndroidRuntime( 3982): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3982): CheckJNI is OFF
D/dalvikvm( 3982): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3982): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3982): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3982): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3982): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3982): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3982): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3982): failed to load memtrack module: -2
D/AndroidRuntime( 3982): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1018): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3982
W/WindowManager( 1018): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3998 uid=10506 gids={50506, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3982): Shutting down VM
D/dalvikvm( 3982): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3998): Binding Chromium to main looper Looper (main, tid 1) {41f765a0}
I/LibraryLoader( 3998): Expected native library version number "",actual native library version number ""
I/chromium( 3998): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3998): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1018): Message: 20
D/BluetoothManagerService( 1018): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@424b3640:true
I/Adreno-EGL( 3998): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3998): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3998): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3998): Local Branch: 
I/Adreno-EGL( 3998): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3998): Local Patches: NONE
I/Adreno-EGL( 3998): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3998): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3998): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3998): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3998): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3998): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3998): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3998): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3998): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3998): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3998): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3998): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3998): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3998): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3998): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3998): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3998): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3998): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3998): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3998): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3998): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3998): Enabling debug mode 0
,W/AwContents( 3998): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3998): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1018): Displayed com.test.thalitest/.MainActivity,cp,ca,424
I/ActivityManager( 1018): Displayed com.test.thalitest/.MainActivity: +400ms (total +425ms)
,D/JsMessageQueue( 3998): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3998): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f7b2c0
,D/dalvikvm( 3998): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f7b2c0
,D/jxcore_app_log( 3998): JniHelper::setJavaVM(0x415c8fa8), pthread_self() = 1614299472
,D/JX-Cordova( 3998): jxcore cordova android initializing
,D/dalvikvm( 3998): GC_CONCURRENT freed 2797K, 17% free 14384K/17224K, paused 3ms+2ms, total 58ms
,D/dalvikvm( 3998): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 3998): GC_FOR_ALLOC freed 106K, 17% free 14388K/17224K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3998): Grow heap (frag case) to 16.144MB for 64402-byte allocation
,D/dalvikvm( 3998): GC_FOR_ALLOC freed 152K, 17% free 14383K/17288K, paused 26ms, total 26ms
,D/dalvikvm( 3998): GC_FOR_ALLOC freed 180K, 17% free 14418K/17288K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3998): Grow heap (frag case) to 16.250MB for 144892-byte allocation
,D/dalvikvm( 3998): GC_FOR_ALLOC freed 255K, 18% free 14466K/17432K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3998): Grow heap (frag case) to 16.367MB for 217334-byte allocation
,D/dalvikvm( 3998): GC_FOR_ALLOC freed 372K, 18% free 14540K/17648K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3998): Grow heap (frag case) to 16.542MB for 325996-byte allocation
,D/dalvikvm( 3998): GC_FOR_ALLOC freed 573K, 19% free 14662K/17968K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3998): Grow heap (frag case) to 16.817MB for 488990-byte allocation
,D/dalvikvm( 3998): GC_FOR_ALLOC freed 872K, 20% free 14838K/18448K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3998): Grow heap (frag case) to 17.222MB for 733480-byte allocation
,D/dalvikvm( 3998): GC_FOR_ALLOC freed 1292K, 22% free 15096K/19168K, paused 27ms, total 27ms
,D/dalvikvm( 3998): GC_CONCURRENT freed 1676K, 20% free 15467K/19168K, paused 1ms+3ms, total 37ms
,D/dalvikvm( 3998): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 3998): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 3998): GC_FOR_ALLOC freed 383K, 20% free 15426K/19168K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3998): Grow heap (frag case) to 18.670MB for 1650320-byte allocation
,D/dalvikvm( 3998): GC_CONCURRENT freed 1713K, 23% free 16011K/20780K, paused 1ms+3ms, total 43ms
,D/dalvikvm( 3998): GC_FOR_ALLOC freed 1370K, 23% free 16077K/20780K, paused 30ms, total 30ms
,I/dalvikvm-heap( 3998): Grow heap (frag case) to 20.093MB for 2475476-byte allocation
,D/dalvikvm( 3998): GC_CONCURRENT freed 186K, 21% free 18398K/23200K, paused 4ms+4ms, total 40ms
,D/dalvikvm( 3998): GC_CONCURRENT freed 4458K, 27% free 17063K/23200K, paused 1ms+8ms, total 54ms
,D/dalvikvm( 3998): WAIT_FOR_CONCURRENT_GC blocked 38ms
,I/dalvikvm-heap( 3998): Grow heap (frag case) to 22.237MB for 3713210-byte allocation
,D/dalvikvm( 3998): GC_CONCURRENT freed 2767K, 33% free 18202K/26828K, paused 5ms+6ms, total 66ms
,D/dalvikvm( 3998): GC_FOR_ALLOC freed 758K, 33% free 17995K/26828K, paused 29ms, total 29ms
,W/jxcore-log( 3998): Initializing JXcore engine
,W/jxcore-log( 3998): JXcore engine is ready
,D/dalvikvm( 3998): GC_CONCURRENT freed 355K, 24% free 20614K/26828K, paused 1ms+2ms, total 33ms
,D/dalvikvm( 3998): WAIT_FOR_CONCURRENT_GC blocked 30ms
,W/jxcore-log( 3998): Starting JXcore engine
,W/jxcore-log( 3998): Platform android
W/jxcore-log( 3998): 
,W/jxcore-log( 3998): Process ARCH arm
W/jxcore-log( 3998): 
,I/jxcore-log( 3998): JXcore Cordova bridge is ready!
I/jxcore-log( 3998): 
,W/jxcore-log( 3998): JXcore engine is started
,I/chromium( 3998): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3998): Toggling radios to true
I/jxcore-log( 3998): 
,D/BluetoothAdapter( 3998): enable(): BT is already enabled..!
D/WifiService( 1018): New client listening to asynchronous messages
D/WifiService( 1018): setWifiEnabled: true pid=3998, uid=10506
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1018): handleMessage: E msg.what=131145
D/WifiStateMachine( 1018): processMsg: ConnectedState
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
I/jxcore-log( 3998): Radios toggled
I/jxcore-log( 3998): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3998): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3998): 
I/jxcore-log( 3998): Perf Test app loaded loaded
I/jxcore-log( 3998): 
,I/jxcore-log( 3998): check test folder
I/jxcore-log( 3998): 
,I/jxcore-log( 3998): found test : ./testFindPeers.js
I/jxcore-log( 3998): 
,D/TCMD    (  462): NL - Read 1000 bytes from update socket.
D/TCMD    (  462): NL - message type is RTM_NEWLINK
D/TCMD    (  462): Listening for incoming client connection request
D/TCMD    (  462): NL - Read 68 bytes from update socket.
D/TCMD    (  462): NL - message type is RTM_NEWLINK
D/TCMD    (  462): Listening for incoming client connection request
D/TCMD    (  462): NL - Read 68 bytes from update socket.
D/TCMD    (  462): NL - message type is RTM_NEWLINK
,D/TCMD    (  462): Listening for incoming client connection request
,I/wpa_supplicant( 1158): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  275): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  275):  STA Disconnected !!
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  275): set_property_value, Enter
,I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  275): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
,D/WifiStateMachine( 1018): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1018): invokeExitMethods: ConnectedState
,D/Tethering( 1018): InitialState.processMessage what=4
,D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
,V/ConnectivityService( 1018): WiFi NOT Tethered!
D/WifiStateMachine( 1018): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1018): Stopping DHCP and clearing IP
D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1018): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
I/jxcore-log( 3998): found test : ./testSendData.js
I/jxcore-log( 3998): 
,D/CommandListener(  273): Clearing all IP addresses on wlan0
D/TCMD    (  462): NL - Read 60 bytes from update socket.
D/TCMD    (  462): NL - ignore NL message, type = 21
,D/TCMD    (  462): Listening for incoming client connection request
,D/WifiStateMachine( 1018): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1018): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1018): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1018): connected time updated 351272
,D/ConnectivityService( 1018): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService( 1018): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/ConnectivityService( 1018): Attempting to switch to mobile
D/ConnectivityService( 1018): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1018): Attempting to switch to ETHERNET
,D/ConnectivityService( 1018): resetConnections(wlan0, 3)
D/NetUtils( 1018): android_net_utils_resetConnections in env=0x611bb898 clazz=0x62d00001 iface=wlan0 mask=0x3
,I/jxcore-log( 3998): found test : ./testSendData2.js
I/jxcore-log( 3998): 
,D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1018): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine( 1018): DisconnectingState
E/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1018): handleMessage: X
,D/Checkin ( 1018): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1018): handleMessage: E msg.what=131146
D/WifiStateMachine( 1018): processMsg: DisconnectingState
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/MDMCTBK (  275): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147460
D/WifiStateMachine( 1018): processMsg: DisconnectingState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): Network connection lost
D/WifiStateMachine( 1018): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1367): Read error: ssl=0x630b56b8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1367): SSL shutdown failed: ssl=0x630b56b8: I/O error during system call, Broken pipe
D/WifiP2pService( 1018): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  273): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1018): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1018): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1018): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1018): invokeEnterMethods: DisconnectedState
D/Checkin ( 1018): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131101
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131216
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131216
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1018): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1310): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1310): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1310): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1018): Attempting to switch to mobile
D/ConnectivityService( 1018): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1018): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=false
,I/ModemStatsDSDetect( 1310): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1310): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1310): onReceive() - done, currentInetCondition=0
,I/chromium( 3998): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 1158): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1018): handleMessage: E msg.what=147461
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/MDMCTBK (  275): Event received = Trying to associate with
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  462): NL - Read 56 bytes from update socket.
D/TCMD    (  462): NL - message type is RTM_NEWLINK
,D/TCMD    (  462): Listening for incoming client connection request
,E/wpa_supplicant( 1158): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,I/wpa_supplicant( 1158): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  462): NL - Read 312 bytes from update socket.
D/TCMD    (  462): NL - message type is RTM_NEWLINK
,D/TCMD    (  462): Listening for incoming client connection request
D/TCMD    (  462): NL - Read 88 bytes from update socket.
D/TCMD    (  462): NL - message type is RTM_NEWLINK
D/TCMD    (  462): Listening for incoming client connection request
,I/wpa_supplicant( 1158): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  462): NL - Read 68 bytes from update socket.
D/TCMD    (  462): NL - message type is RTM_NEWLINK
D/TCMD    (  462): Listening for incoming client connection request
D/TCMD    (  462): NL - Read 1000 bytes from update socket.
D/TCMD    (  462): NL - message type is RTM_NEWLINK
D/TCMD    (  462): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1158): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  275): Event received = Associated with c0:ff:d4
D/TCMD    (  462): NL - Read 80 bytes from update socket.
D/TCMD    (  462): NL - message type is RTM_NEWLINK
D/TCMD    (  462): Listening for incoming client connection request
D/TCMD    (  462): NL - Read 80 bytes from update socket.
D/TCMD    (  462): NL - message type is RTM_NEWLINK
D/TCMD    (  462): Listening for incoming client connection request
D/TCMD    (  462): NL - Read 68 bytes from update socket.
D/TCMD    (  462): NL - message type is RTM_NEWLINK
,D/TCMD    (  462): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1158): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
,D/MDMCTBK (  275): Event received = WPA: Key negotiation com
,I/wpa_supplicant( 1158): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  275): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  275):  STA Connected !!
D/TCMD    (  462): NL - Read 1000 bytes from update socket.
D/TCMD    (  462): NL - message type is RTM_NEWLINK
,D/TCMD    (  462): Listening for incoming client connection request
E/MDMCTBK (  275): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  275): get_freq !!, resp=0
I/MDMCTBK (  275): get_freq !!, Strip data
I/MDMCTBK (  275): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  275): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  275): set_property_value, Enter
,I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  275): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  275): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1208108208
I/MDMCTBK (  275): return from set_get_from_wpa_supplicant
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
,I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE ,
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  275): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  275): , reply_len: 3, ret: 0
E/MDMCTBK (  275): MdmCutbackHndler, resp=OK
E/MDMCTBK (  275): 
,D/MDMCTBK (  275): wifi_set_tx_pwr: Exit
,D/Tethering( 1018): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiStateMachine( 1018): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147459
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): Network connection established
,D/WifiStateMachine( 1018): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1018): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1018): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1018): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1018): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1018): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-43ms what=147462 obj=android.net.wifi.StateChangeResult@4282c928 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131101
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-39ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@434f72a0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=196612
,D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-13ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1018): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1018): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@421bf6b8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@421bf6b8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 c
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 2 c
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 3 0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 0c
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 2 0c
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE i
D/TCMD    (  462): NL - Read 56 bytes from update socket.
D/TCMD    (  462): NL - message type is RTM_NEWLINK
,D/TCMD    (  462): Listening for incoming client connection request
D/WifiP2pService( 1018): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): InactiveState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@43e4f478 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@43e4f478 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): DefaultState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@43e4f478 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): handleMessage: E msg.what=147461
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): handleMessage: X
,V/AlarmManager( 1018): sending alarm Alarm{4413e340 type 3 android}
,D/TCMD    (  462): NL - Read 60 bytes from update socket.
D/TCMD    (  462): NL - ignore NL message, type = 20
,D/TCMD    (  462): Listening for incoming client connection request
,D/WifiStateMachine( 1018): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1018): processMsg: ObtainingIpState
,D/WifiStateMachine( 1018): ObtainingIpState{ when=-7ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1018): processMsg: ObtainingIpState
,D/WifiStateMachine( 1018): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1018): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): DHCP successful
D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1018): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1018): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1018): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1018): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1018): VerifyingLinkState enter
D/WifiStateMachine( 1018): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=151572
,D/WifiStateMachine( 1018): processMsg: VerifyingLinkState
D/WifiStateMachine( 1018): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=135190
D/WifiStateMachine( 1018): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1018): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1018): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1018): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1018): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1018): CaptivePortalCheckState enter
,D/WifiStateMachine( 1018): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1018): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1018): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1018): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1018): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131092
D/WifiStateMachine( 1018): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1018): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1018): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1018): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService( 1018): WiFi NOT Tethered!
,E/ConnectivityService( 1018): Unexpected mtu value: android.net.wifi.WifiStateTracker@4205e860
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1310): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1310): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1310): onReceive() - done, currentInetCondition=0
,D/WifiStateMachine( 1018): transitionTo: destState=ConnectedState
,D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1018): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
,D/WifiStateMachine( 1018): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131092
,D/WifiStateMachine( 1018): processMsg: ConnectedState
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): handleMessage: X
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService( 1018): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1018): WiFi NOT Tethered!
,D/Checkin ( 1018): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
E/ConnectivityService( 1018): Unexpected mtu value: android.net.wifi.WifiStateTracker@4205e860
,D/ConnectivityService( 1018): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
,I/ModemStatsDSDetect( 1310): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1310): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1310): onReceive() - done, currentInetCondition=0
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1300): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/CaptivePortalTracker( 1018): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1018): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/PollingManager( 1566): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/TelephonyProvider( 1272): Column apn id key is 'apn_id'
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
W/XTWiFiOS( 1300): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1566): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1566): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1566): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1566): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1566): Registering with Alarm Manager to restart CCE
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/Tethering( 1018): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1018): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyProvider( 1272): Column apn id key is 'apn_id'
D/OtaApp  ( 1566): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1566): [debug] > CusSM.onRadioDown
I/openssl ( 3889): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3889): Crypto mode 0 already enabled
,I/ActivityManager( 1018): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4131 uid=10030 gids={50030, 3003, 1028, 1015}
,V/MmsConfig( 4131): mnc/mcc: 
,V/MmsConfig( 4131): tag: bool value: enabledMMS - true
V/MmsConfig( 4131): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4131): tag: int value: maxImageHeight - 1944
,V/MmsConfig( 4131): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4131): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4131): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4131): tag: int value: minMessageCountPerThread - 10
,V/MmsConfig( 4131): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4131): tag: int value: recipientLimit - 20
V/MmsConfig( 4131): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4131): tag: int value: smsToMmsTextThreshold - 6
,V/MmsConfig( 4131): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4131): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4131): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4131): tag: bool value: smsForceShowEncodingMenu - true
,V/MmsConfig( 4131): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4131): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4131): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1018): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4152 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1018): Killing 3804:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1018): GC_EXPLICIT freed 1642K, 65% free 18051K/50768K, paused 5ms+13ms, total 112ms
,D/TelephonyProvider( 1272): Column apn id key is 'apn_id'
,D/MobileConnectivityChangeReceiver( 4152): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4152): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4152): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4152): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1018): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4165 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1018): Killing 3821:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/TelephonyProvider( 1272): Column apn id key is 'apn_id'
,I/CheckinService( 1405): Checkin interval check for package: unspecified last checkin: 1450833920064 min interval config: 0 actual interval: 340780
,I/CheckinService( 1405): Checking schedule, now: 1450834260850 next: 1450833950019
,I/CheckinService( 1405): active receiver: enabled
,I/CheckinService( 1405): Preparing to send checkin request
,I/EventLogService( 1405): Accumulating logs since 1450833916581
,I/CheckinRequestBuilder( 1405): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1405): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4188 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1018): Killing 3838:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,D/dalvikvm( 1405): GC_CONCURRENT freed 1877K, 31% free 12012K/17224K, paused 5ms+4ms, total 44ms
W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 3998): Connected to the server!
I/jxcore-log( 3998): 
,I/chromium( 3998): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WebViewChromiumFactoryProvider( 4188): Binding Chromium to main looper Looper (main, tid 1) {41f7ad38}
,I/LibraryLoader( 4188): Expected native library version number "",actual native library version number ""
,I/chromium( 4188): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4188): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4188): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4188): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4188): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4188): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4188): Local Branch: 
I/Adreno-EGL( 4188): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4188): Local Patches: NONE
I/Adreno-EGL( 4188): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/ActivityManager( 1018): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4209 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/chromium( 4188): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4209): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4209): VFY: replacing opcode 0x60 at 0x000b
I/dalvikvm( 4209): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4209): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4209): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4209): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4209): install
,I/MultiDex( 4209): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4209): loading existing secondary dex files
,I/MultiDex( 4209): load found 3 secondary dex files
,I/MultiDex( 4209): install done
,W/GAV2    ( 4188): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4188): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/dalvikvm( 4209): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4209): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4209): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4209): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4209): VFY: unable to resolve instance field 36
,D/dalvikvm( 4209): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4209): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4209): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4209): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4209): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4209): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4209): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f80a08
D/dalvikvm( 4209): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f80a08
,D/dalvikvm( 4209): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f80a08, skipping init
,D/dalvikvm( 4209): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f80a08
D/dalvikvm( 4209): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f80a08
,V/JNIHelp ( 4209): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4209): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f80a08
,D/dalvikvm( 4209): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f80a08
D/dalvikvm( 4209): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f80a08
,D/dalvikvm( 4209): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f80a08
,I/ProviderInstaller( 4209): Installed default security provider GmsCore_OpenSSL
,I/NSApplication( 4188): Starting up...
,I/ImageResourceManager( 3865): ImageResourceManager: uninitalized
,I/iu.Environment( 3865): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1018): Killing 3781:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 4209): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 4209): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4209): VFY: replacing opcode 0x6e at 0x00ce
,I/dalvikvm( 4209): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4209): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4209): VFY: replacing opcode 0x6e at 0x000d
I/openssl ( 3889): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3889): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4152): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4152): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3865): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/dalvikvm( 4209): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4209): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4209): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4209): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4209): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4209): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4209): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4209): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4209): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4209): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4209): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/DEBUG   ( 1566): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1566): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1566): bindWebServices(): registering our AIDL callback...
I/SundryService( 1566): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1566): ServiceHandler.handleMessage: mWaitCount=0
,D/EmailService.MarketingOptInSetter( 1566): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1566): onServiceConnected()
D/GetNotificationsWS( 1566): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1566): unbindWebServices(): un-registering our AIDL callback...
,D/WVCdm   (  279): Instantiating CDM.
,I/WVCdm   (  279): Level3 Library Nov 20 2013 18:09:31
,D/WearableService( 1242): callingUid 10022, callindPid: 1242
,D/DrmWidevineDash(  279): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  279): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  279): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5317000
,E/DrmWidevineDash(  279): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5317000
D/DrmWidevineDash(  279): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_APIVersion...
,E/MDM     ( 1242): [129] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/DrmWidevineDash(  279): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  279): calling OEMCrypto_IsKeyboxValid...
,D/AuthorizationBluetoothService( 1367): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1367): Proximity feature is not enabled.
,D/LocationInitializer( 1405): Restart initialization of location
,D/DrmWidevineDash(  279): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  279): OEMCrypto_Initialize Level 1 success. I will use level 1.
,I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  279): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetRandom...
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DrmWidevineDash(  279): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  279): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetDeviceID...
,W/GCoreFlp( 1242): No location to return for getLastLocation()
,W/FusedLocationProvider( 1242): location=null
D/DrmWidevineDash(  279): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=1872065199
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/ConnectivityService( 1018): NetTransition Wakelock for ConnectedState released by timeout
,D/NativeLibraryUtils( 4209): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4209): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42175db8
,D/dalvikvm( 4209): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42175db8
,D/dalvikvm( 4209): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42175db8, skipping init
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  279): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  279): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  279): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  279): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=656917761
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,I/dalvikvm( 3998): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 3998): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 3998): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 3998): Shutting down VM
,W/dalvikvm( 3998): threadid=1: thread exiting with uncaught exception (group=0x416a7d40)
E/AndroidRuntime( 3998): FATAL EXCEPTION: main
E/AndroidRuntime( 3998): Process: com.test.thalitest, PID: 3998
E/AndroidRuntime( 3998): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 3998): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 3998): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 3998): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 3998): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 3998): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 3998): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 3998): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 3998): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 3998): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 3998): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 3998): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 3998): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 3998): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 3998): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 3998): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 3998): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 3998): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 3998): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 1018):   Force finishing activity com.test.thalitest/.MainActivity
,I/ActivityManager( 1018): Killing 3438:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Process ( 3998): Sending signal. PID: 3998 SIG: 9
,I/ActivityManager( 1018): Process com.test.thalitest (pid 3998) has died.
,I/WindowState( 1018): WIN DEATH: Window{42043d90 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1018): Client connection lost with reason: 4
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/Settings( 4209): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/OtaApp  ( 1566): [info] > Updatetime from metadata: 10
,D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1566): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1566): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1566): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1566): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/InputMethodManagerService( 1018): Got RemoteException sending setActive(false) notification to pid 3998 uid 10506
W/Binder  ( 1206): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1206): java.lang.NullPointerException
W/Binder  ( 1206): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1206): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1206): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1206): 	at dalvik.system.NativeStart.run(Native Method)
,D/dalvikvm( 4209): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4280): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4209): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4209): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 74ms
,I/Adreno-EGL( 4209): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4209): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4209): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4209): Local Branch: 
I/Adreno-EGL( 4209): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4209): Local Patches: NONE
I/Adreno-EGL( 4209): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4209): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4209): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4209): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4209): Local Branch: 
I/Adreno-EGL( 4209): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4209): Local Patches: NONE
I/Adreno-EGL( 4209): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4209): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4209): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4209): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4209): Local Branch: 
I/Adreno-EGL( 4209): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4209): Local Patches: NONE
I/Adreno-EGL( 4209): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4209): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4209): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4209): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4209): Local Branch: 
I/Adreno-EGL( 4209): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4209): Local Patches: NONE
I/Adreno-EGL( 4209): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1405): Classify the device as Phone.
,V/NativeCrypto( 1405): SSL shutdown failed: ssl=0x6bc4ddb8: I/O error during system call, Connection timed out
,I/CheckinTask( 1405): Sending checkin request (11626 bytes)
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1018): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1300): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/PollingManager( 1566): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1566): now: 384011 ,futureTime: 65754636
,D/PollingManager( 1566): Polling alarm set to expire at: 65754636 Current Time: 384011
,D/TelephonyProvider( 1272): Column apn id key is 'apn_id'
E/ActivityThread( 1566): Failed to find provider info for com.motorola.blur.setupprovider
,D/OtaApp  ( 1566): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1566): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1566): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1300): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/PollingManager( 1566): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/Tethering( 1018): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1018): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/OtaApp  ( 1566): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1566): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/PollingManager( 1566): now: 384060 ,futureTime: 65754636
D/PollingManager( 1566): Polling alarm set to expire at: 65754636 Current Time: 384060
,D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1566): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1566): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,E/ActivityThread( 1566): Failed to find provider info for com.motorola.blur.setupprovider
,D/OtaApp  ( 1566): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/openssl ( 3889): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3889): Crypto mode 0 already enabled
D/OtaApp  ( 1566): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/TelephonyProvider( 1272): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1272): Column apn id key is 'apn_id'
,D/MobileConnectivityChangeReceiver( 4152): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4152): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1566): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1566): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/iu.Environment( 3865): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/TelephonyProvider( 1272): Column apn id key is 'apn_id'
,D/OtaApp  ( 1566): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1566): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
I/CheckinService( 1405): Checkin interval check for package: unspecified last checkin: 1450833920064 min interval config: 0 actual interval: 343673
D/OtaApp  ( 1566): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1566): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1566): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/DEBUG   ( 1566): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1566): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1566): bindWebServices(): registering our AIDL callback...
I/SundryService( 1566): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1566): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1566): onServiceConnected()
,D/GetNotificationsWS( 1566): onServiceConnected(): Registered for remote service callbacks...
D/WaitableIntentService( 1566): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1566): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 3889): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3889): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4152): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4152): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 3865): GC_FOR_ALLOC freed 593K, 5% free 16434K/17224K, paused 14ms, total 15ms
,I/dalvikvm-heap( 3865): Grow heap (frag case) to 19.818MB for 1821008-byte allocation
,I/iu.Environment( 3865): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1405): Checkin interval check for package: unspecified last checkin: 1450833920064 min interval config: 0 actual interval: 343744
,D/dalvikvm( 3865): GC_FOR_ALLOC freed 30K, 5% free 18186K/19004K, paused 17ms, total 17ms
,D/DEBUG   ( 1566): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1566): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1566): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1566): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1566): onServiceConnected()
D/GetNotificationsWS( 1566): onServiceConnected(): Registered for remote service callbacks...
,I/SundryService( 1566): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1566): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1566): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1566): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1018): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1566
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1566): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/OtaApp  ( 1566): [info] > Updatetime from metadata: 10
D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1566): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1566): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1566): [info] > Updatetime from metadata: 10
D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1566): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1566): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1566): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/OtaApp  ( 1566): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
D/OtaApp  ( 1566): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1018): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1566
W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1566): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/OtaApp  ( 1566): [info] > Updatetime from metadata: 10
D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1566): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1566): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
I/OtaApp  ( 1566): [info] > Updatetime from metadata: 10
D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1566): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1566): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1566): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/OtaApp  ( 1566): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1018): Activity reported stop, but no longer stopping: ActivityRecord{427d5870 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/CheckinRequestBuilder( 1405): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1405): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1018): GC_EXPLICIT freed 725K, 65% free 18021K/50768K, paused 5ms+9ms, total 98ms
,I/CheckinRequestBuilder( 1405): Classify the device as Phone.
,D/dalvikvm( 1367): GC_EXPLICIT freed 1368K, 40% free 10355K/17224K, paused 2ms+5ms, total 34ms
,I/CheckinTask( 1405): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1405): Checking schedule, now: 1450834264171 next: 1451427334166
,I/CheckinService( 1405): active receiver: disabled
,I/CheckinService( 1405): Checking schedule, now: 1450834264188 next: 1451427334166
,I/CheckinService( 1405): active receiver: disabled
,D/CheckinService( 1405): Recording last checkin time for package unspecified as 1450834264195
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService( 1018): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received,
,I/ModemStatsDSDetect( 1310): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1310): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1310): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1310): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1018): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131215
D/WifiStateMachine( 1018): processMsg: ConnectedState
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1018): handleMessage: X
,D/ConnectivityService( 1018): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1018):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1018): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
,I/GAV2    ( 4188): Thread[GAThread,5,main]: No campaign data found.
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4335 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
D/dalvikvm(  277): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 1ms+17ms, total 38ms
,I/Launcher( 1327): Deferring update until onResume
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 30ms
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
,I/Launcher( 1327): Deferring update until onResume
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
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
,I/Babel   ( 4335): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4335): MmsConfig.loadMmsSettings
,I/GCoreNlp( 1242): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4335): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4335): MmsConfig.loadFromDatabase
,E/Babel   ( 4335): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4335): MmsConfig.loadFromResources
,E/Babel   ( 4335): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4335): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4335): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1018): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4373 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,D/dalvikvm( 1242): GC_CONCURRENT freed 1667K, 33% free 11618K/17224K, paused 4ms+7ms, total 46ms
,I/ActivityManager( 1018): Killing 3965:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Killing 3889:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4393 uid=10033 gids={50033, 3003, 1028, 1015}
,I/InternalIcingCorporaPro( 2309): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1018): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4411 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1018): Killing 4131:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4373): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4411): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
,W/dalvikvm( 4411): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4411): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4411): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2309): UpdateCorporaTask done [took 198 ms] updated apps [took 198 ms] 
,I/dalvikvm( 4411): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4411): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4411): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4411): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4411): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4411): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4411): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4411): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4411): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4411): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4411): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4411): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4411): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4411): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4411): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4411): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4411): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4411): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4411): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4411): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4411): VFY: replacing opcode 0x6e at 0x0385
I/ActivityManager( 1018): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4445 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4411): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 4411): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4411): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4411): Skipping gmscore version check
,D/Finsky  ( 4411): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4411): [1] Libraries$2.run: Finished loading 1 libraries.
I/dalvikvm( 4411): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4411): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4411): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1018): Killing 4152:com.google.android.setupwizard/u0a41 (adj 15): empty #9
W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1405): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1405): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1405): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4445): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f7c320, skipping init
I/openssl ( 4445): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4445): Crypto mode 0 already enabled
,I/ActivityManager( 1018): Killing 4165:com.android.chrome/u0a56 (adj 15): empty #9
,D/Finsky  ( 4411): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Finsky  ( 4411): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/dalvikvm( 1405): GC_CONCURRENT freed 1972K, 31% free 11994K/17224K, paused 3ms+5ms, total 36ms
,I/Icing   ( 1405): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1405): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1206): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450834272
,D/CaptivePortalTracker( 1018): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1018): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1018): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1018): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1018): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1018): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1018): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1018): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/AlarmManager( 1018): sending alarm Alarm{422d9e30 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{43e23e28 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{43543860 type 3 android}
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 3
,V/AlarmManager( 1018): sending alarm Alarm{42119778 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{440f6fb0 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{434f9c38 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{434f8fa8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{422d8620 type 2 android}
,V/AlarmManager( 1018): sending alarm Alarm{422cadf8 type 0 com.google.android.gms}
,D/ConnectivityService( 1018): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1018): Done.
,D/ConnectivityService( 1018): Setting timer for 720seconds
,I/EventLogService( 1405): Aggregate from 1450834260870 (log), 1450832401038 (data)
,V/AlarmManager( 1018): sending alarm Alarm{43a30cb0 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{428aa618 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{42d02180 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{43931a00 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{420473d8 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{4256ff40 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{4351a018 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43a30d88 type 1 com.android.deskclock}
,I/LaunchCheckinHandler( 1018): cleanup(): cleared. Last call was 829404 ms ago
,I/ActivityManager( 1018): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4497 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1018): Killing 4188:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{440f5ac0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43a30e60 type 2 com.google.android.gms}
,D/ConnectivityService( 1018): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/ModemStatsDSDetect( 1310): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1310): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1310): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{43d68d10 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{427aca70 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43d68de8 type 2 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{43928948 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{43960c70 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43d68ec0 type 2 android}
,D/ConnectivityService( 1018): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1018): Done.
,D/ConnectivityService( 1018): Setting timer for 720seconds
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{43822738 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43639c80 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43a434a8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4203e760 type 3 android}
,D/dalvikvm( 1018): GC_CONCURRENT freed 2074K, 65% free 18145K/50768K, paused 5ms+11ms, total 118ms
,V/AlarmManager( 1018): sending alarm Alarm{43389880 type 3 android}
,I/ProcessStatsService( 1018): Prepared write state in 22ms
,I/ProcessStatsService( 1018): Prepared write state in 23ms
,I/ProcessStatsService( 1018): Prepared write state in 16ms
,I/ProcessStatsService( 1018): Pruning old procstats: /data/system/procstats/state-2015-12-22-01-49-10.bin
,V/AlarmManager( 1018): sending alarm Alarm{440a8950 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43a3b060 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43928948 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4383ebf8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43540560 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43d68f98 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43d69070 type 3 com.google.android.gms}
,V/AlarmManager( 1018): sending alarm Alarm{43d690c0 type 1 com.android.deskclock}
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NativeCrypto( 1367): SSL shutdown failed: ssl=0x63650b18: I/O error during system call, Connection timed out
,I/GoogleURLConnFactory( 1242): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1242): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,W/PhenotypeConfigurator( 1242): Server returned 404
,V/AlarmManager( 1018): sending alarm Alarm{427b1c38 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4572): 
D/AndroidRuntime( 4572): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4572): CheckJNI is OFF
D/dalvikvm( 4572): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4572): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4572): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4572): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4572): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4572): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4572): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4572): failed to load memtrack module: -2
D/AndroidRuntime( 4572): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10506 user=-1: uninstall pkg
W/PackageSettings( 1018): Skipping PackageSetting{42238d90 com.example.hello/10480} due to missing metadata
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10506 user=0: pkg removed
D/dalvikvm( 2276): GC_EXPLICIT freed 5418K, 44% free 9649K/17224K, paused 2ms+5ms, total 54ms
D/dalvikvm( 2309): GC_EXPLICIT freed 4556K, 42% free 10132K/17224K, paused 2ms+90ms, total 128ms
D/dalvikvm( 1018): GC_EXPLICIT freed 1069K, 65% free 17927K/50768K, paused 5ms+9ms, total 102ms
I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
I/LatinIME:LogUtils( 1206): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450836062
D/VoicemailCleanupService( 4373): Cleaning up data for package: com.test.thalitest
D/dalvikvm( 1327): GC_EXPLICIT freed 3240K, 33% free 11596K/17224K, paused 2ms+22ms, total 129ms
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
D/dalvikvm( 1405): GC_EXPLICIT freed 628K, 31% free 11919K/17224K, paused 6ms+6ms, total 170ms
W/SQLiteConnectionPool( 1405): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/Launcher( 1327): Deferring update until onResume
W/GeofencerStateMachine( 1242): Ignoring removeGeofence because network location is disabled.
I/LatinIME:LogUtils( 1206): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1206): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1018): removePackageParticipantsLocked: uid=10506 #1
D/dalvikvm( 1018): GC_EXPLICIT freed 170K, 65% free 18012K/50768K, paused 9ms+11ms, total 117ms
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
I/InternalIcingCorporaPro( 2309): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
I/Launcher( 1327): Deferring update until onResume
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
I/ActivityManager( 1018): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4601 uid=10059 gids={50059, 3003, 1028, 1015}
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
D/AndroidRuntime( 4572): Shutting down VM
D/dalvikvm( 4572): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+1ms, total 2ms
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
I/LatinIME:LogUtils( 1206): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450836062
I/InternalIcingCorporaPro( 2309): UpdateCorporaTask done [took 132 ms] updated apps [took 132 ms] 
W/ActiveOrDefaultContextProvider( 4601): Missing scope.enter somewhere. Returning default context
E/SQLiteDatabase( 4601): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4601): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4601): 	at vR.b(ClientFlagDatabaseImpl.java:148)
E/SQLiteDatabase( 4601): 	at wd.a(ClientFlagsModule.java:31)
E/SQLiteDatabase( 4601): 	at wd.a(ClientFlagsModule.java:22)
E/SQLiteDatabase( 4601): 	at anh.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4601): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4601): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4601): 	at iy.a(GellyInjectorStore.java:2144)
E/SQLiteDatabase( 4601): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4601): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4601): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4601): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4601): 	at fM.a(GellyInjectorStore.java:87)
E/SQLiteDatabase( 4601): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4601): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4601): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4601): 	at WB.a(GellyInjectorStore.java:73)
E/SQLiteDatabase( 4601): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4601): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4601): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4601): 	at XX.a(GellyInjectorStore.java:123)
E/SQLiteDatabase( 4601): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4601): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4601): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4601): 	at fj.b(GellyInjectorStore.java:193)
E/SQLiteDatabase( 4601): 	at fj.a(GellyInjectorStore.java:306)
E/SQLiteDatabase( 4601): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4601): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4601): 	at anh.a(GellyInjectorStoreBase.java:135)
E/SQLiteDatabase( 4601): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4601): 	at Jk.a(GellyInjectorStore.java:1093)
E/SQLiteDatabase( 4601): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4601): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4601): 	at fj.a(GellyInjectorStore.java:91)
E/SQLiteDatabase( 4601): 	at fj.a(GellyInjectorStore.java:359)
E/SQLiteDatabase( 4601): 	at anj.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4601): 	at amS.a(GellyInjector.java:117)
E/SQLiteDatabase( 4601): 	at Ma.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4601): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:198)
E/SQLiteDatabase( 4601): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1030)
E/SQLiteDatabase( 4601): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4409)
E/SQLiteDatabase( 4601): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4601): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteDatabase( 4601): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4601): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4601): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4601): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4601): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4601): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4601): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4601): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4601): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 4601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 4601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 4601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 4601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4601): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4601): 	at vR.b(ClientFlagDatabaseImpl.java:148)
E/SQLiteOpenHelper( 4601): 	at wd.a(ClientFlagsModule.java:31)
E/SQLiteOpenHelper( 4601): 	at wd.a(ClientFlagsModule.java:22)
E/SQLiteOpenHelper( 4601): 	at anh.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4601): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4601): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4601): 	at iy.a(GellyInjectorStore.java:2144)
E/SQLiteOpenHelper( 4601): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4601): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4601): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4601): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4601): 	at fM.a(GellyInjectorStore.java:87)
E/SQLiteOpenHelper( 4601): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4601): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4601): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4601): 	at WB.a(GellyInjectorStore.java:73)
E/SQLiteOpenHelper( 4601): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4601): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4601): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4601): 	at XX.a(GellyInjectorStore.java:123)
E/SQLiteOpenHelper( 4601): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4601): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4601): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4601): 	at fj.b(GellyInjectorStore.java:193)
E/SQLiteOpenHelper( 4601): 	at fj.a(GellyInjectorStore.java:306)
E/SQLiteOpenHelper( 4601): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4601): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4601): 	at anh.a(GellyInjectorStoreBase.java:135)
E/SQLiteOpenHelper( 4601): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4601): 	at Jk.a(GellyInjectorStore.java:1093)
E/SQLiteOpenHelper( 4601): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4601): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4601): 	at fj.a(GellyInjectorStore.java:91)
E/SQLiteOpenHelper( 4601): 	at fj.a(GellyInjectorStore.java:359)
E/SQLiteOpenHelper( 4601): 	at anj.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4601): 	at amS.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4601): 	at Ma.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4601): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:198)
E/SQLiteOpenHelper( 4601): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1030)
E/SQLiteOpenHelper( 4601): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4409)
E/SQLiteOpenHelper( 4601): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 4601): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteOpenHelper( 4601): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4601): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 4601): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteOpenHelper( 4601): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4601): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4601): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteOpenHelper( 4601): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteOpenHelper( 4601): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4601): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4601): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4601): 	at WW.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4601): 	at WS.a(AbstractDatabaseInstance.java:396)
E/SQLiteDatabase( 4601): 	at WS.a(AbstractDatabaseInstance.java:393)
E/SQLiteDatabase( 4601): 	at agh.a(Suppliers.java:125)
E/SQLiteDatabase( 4601): 	at WT.run(AbstractDatabaseInstance.java:411)
W/dalvikvm( 4601): threadid=11: thread exiting with uncaught exception (group=0x416a7d40)
E/AndroidRuntime( 4601): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4601): Process: com.google.android.apps.docs, PID: 4601
E/AndroidRuntime( 4601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4601): 	at WW.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4601): 	at WS.a(AbstractDatabaseInstance.java:396)
E/AndroidRuntime( 4601): 	at WS.a(AbstractDatabaseInstance.java:393)
E/AndroidRuntime( 4601): 	at agh.a(Suppliers.java:125)
E/AndroidRuntime( 4601): 	at WT.run(AbstractDatabaseInstance.java:411)
I/Process ( 4601): Sending signal. PID: 4601 SIG: 9
E/DropBoxManagerService( 1018): Can't write: system_app_crash
E/DropBoxManagerService( 1018): java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1018): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1018): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1018): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1018): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1018): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1018): 	... 5 more
I/ActivityManager( 1018): Process com.google.android.apps.docs (pid 4601) has died.

```
