#### Test 51517283e387105_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4240): 
D/AndroidRuntime( 4240): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4240): CheckJNI is OFF
D/dalvikvm( 4240): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4240): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4240): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4240): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4240): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4240): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4240): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4240): failed to load memtrack module: -2
D/AndroidRuntime( 4240): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1017): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4240
W/WindowManager( 1017): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1017): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4256 uid=10398 gids={50398, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4240): Shutting down VM
D/dalvikvm( 4240): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 2ms
W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4256): Binding Chromium to main looper Looper (main, tid 1) {41fd5c38}
I/LibraryLoader( 4256): Expected native library version number "",actual native library version number ""
I/chromium( 4256): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4256): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1017): Message: 20
D/BluetoothManagerService( 1017): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@422fe248:true
I/Adreno-EGL( 4256): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4256): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4256): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4256): Local Branch: 
I/Adreno-EGL( 4256): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4256): Local Patches: NONE
I/Adreno-EGL( 4256): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4256): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4256): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4256): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4256): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4256): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4256): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4256): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4256): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4256): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4256): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4256): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4256): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4256): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4256): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4256): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4256): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4256): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4256): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4256): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4256): CordovaWebView is running on device made by: motorola
,V/AlarmManager( 1017): sending alarm Alarm{42875e60 type 3 android}
,D/OpenGLRenderer( 4256): Enabling debug mode 0
,W/AwContents( 4256): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4256): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1017): Displayed com.test.thalitest/.MainActivity,cp,ca,370
I/ActivityManager( 1017): Displayed com.test.thalitest/.MainActivity: +343ms (total +371ms)
,D/JsMessageQueue( 4256): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4256): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fdb2f0
,D/dalvikvm( 4256): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fdb2f0
D/jxcore_app_log( 4256): JniHelper::setJavaVM(0x4162afa8), pthread_self() = 1615057904
,D/JX-Cordova( 4256): jxcore cordova android initializing
,I/dalvikvm( 4256): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 4256): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4256): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 4256): GC_CONCURRENT freed 2880K, 18% free 14287K/17224K, paused 2ms+2ms, total 39ms
,D/dalvikvm( 4256): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/dalvikvm-heap( 4256): Grow heap (frag case) to 16.079MB for 98002-byte allocation
,D/dalvikvm( 4256): GC_FOR_ALLOC freed 216K, 18% free 14286K/17320K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4256): Grow heap (frag case) to 16.124MB for 146998-byte allocation
,D/dalvikvm( 4256): GC_FOR_ALLOC freed 256K, 18% free 14335K/17464K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4256): Grow heap (frag case) to 16.242MB for 220492-byte allocation
,D/dalvikvm( 4256): GC_FOR_ALLOC freed 373K, 19% free 14410K/17680K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4256): Grow heap (frag case) to 16.420MB for 330734-byte allocation
,D/dalvikvm( 4256): GC_FOR_ALLOC freed 579K, 20% free 14535K/18004K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4256): Grow heap (frag case) to 16.700MB for 496096-byte allocation
,D/dalvikvm( 4256): GC_FOR_ALLOC freed 879K, 21% free 14713K/18492K, paused 25ms, total 26ms
,D/dalvikvm( 4256): GC_FOR_ALLOC freed 1301K, 20% free 14973K/18492K, paused 27ms, total 28ms
,I/dalvikvm-heap( 4256): Grow heap (frag case) to 17.719MB for 1116206-byte allocation
,D/dalvikvm( 4256): GC_CONCURRENT freed 1736K, 22% free 15358K/19584K, paused 2ms+3ms, total 34ms
,D/dalvikvm( 4256): GC_FOR_ALLOC freed 351K, 22% free 15305K/19584K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4256): Grow heap (frag case) to 18.576MB for 1674304-byte allocation
,D/dalvikvm( 4256): GC_CONCURRENT freed 1650K, 26% free 15879K/21220K, paused 1ms+5ms, total 31ms
,D/dalvikvm( 4256): GC_FOR_ALLOC freed 1438K, 25% free 15980K/21220K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4256): Grow heap (frag case) to 20.033MB for 2511452-byte allocation
,D/dalvikvm( 4256): GC_CONCURRENT freed 1889K, 30% free 16749K/23676K, paused 4ms+4ms, total 54ms
,D/dalvikvm( 4256): GC_CONCURRENT freed 2420K, 29% free 16911K/23676K, paused 2ms+7ms, total 39ms
,D/dalvikvm( 4256): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 4256): GC_FOR_ALLOC freed 487K, 29% free 16825K/23676K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4256): Grow heap (frag case) to 22.056MB for 3767174-byte allocation
,D/dalvikvm( 4256): GC_CONCURRENT freed 2715K, 34% free 18056K/27356K, paused 5ms+5ms, total 57ms
,W/jxcore-log( 4256): Initializing JXcore engine
,W/jxcore-log( 4256): JXcore engine is ready
,D/dalvikvm( 4256): GC_CONCURRENT freed 548K, 25% free 20522K/27356K, paused 2ms+3ms, total 40ms
,D/dalvikvm( 4256): WAIT_FOR_CONCURRENT_GC blocked 34ms
,W/jxcore-log( 4256): Starting JXcore engine
,W/jxcore-log( 4256): Platform android
W/jxcore-log( 4256): 
,W/jxcore-log( 4256): Process ARCH arm
W/jxcore-log( 4256): 
,I/jxcore-log( 4256): JXcore Cordova bridge is ready!
I/jxcore-log( 4256): 
,W/jxcore-log( 4256): JXcore engine is started
,I/chromium( 4256): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4256): Turning radios to true
I/jxcore-log( 4256): 
,D/BluetoothAdapter( 4256): enable(): BT is already enabled..!
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): New client listening to asynchronous messages
D/WifiService( 1017): setWifiEnabled: true pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1017): handleMessage: E msg.what=131145
D/WifiStateMachine( 1017): processMsg: ConnectedState
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
,I/wpa_supplicant( 1155): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  273): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  273): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:
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
D/TCMD    (  463): NL - Read 1000 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
,D/TCMD    (  463): Listening for incoming client connection request
,D/Tethering( 1017): InitialState.processMessage what=4
D/TCMD    (  463): NL - Read 1000 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/TCMD    (  463): NL - Read 68 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/TCMD    (  463): NL - Read 68 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  273): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  273): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
,V/ConnectivityService( 1017): WiFi NOT Tethered!
D/Tethering( 1017): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1017): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1017): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1017): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1017): Stopping DHCP and clearing IP
D/WifiStateMachine( 1017): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1017): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  271): Clearing all IP addresses on wlan0
D/TCMD    (  463): NL - Read 60 bytes from update socket.
D/TCMD    (  463): NL - ignore NL message, type = 21
,D/TCMD    (  463): Listening for incoming client connection request
,D/WifiStateMachine( 1017): addressRemoved: 192.168.1.123/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1017): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1017): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1017): connected time updated 292425
,I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1017): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1017): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService( 1017): Attempting to switch to mobile
,D/ConnectivityService( 1017): Attempting to switch to BLUETOOTH_TETHER
,I/SBar.NetworkController( 1080): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/ConnectivityService( 1017): Attempting to switch to ETHERNET
,I/SBar.NetworkController( 1080): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1080): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/ConnectivityService( 1017): resetConnections(wlan0, 3)
D/NetUtils( 1017): android_net_utils_resetConnections in env=0x6121e218 clazz=0x60000001 iface=wlan0 mask=0x3
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1017): invokeEnterMethods: DisconnectingState
D/WifiStateMachine( 1017): DisconnectingState
E/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131146
D/WifiStateMachine( 1017): processMsg: DisconnectingState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/MDMCTBK (  273): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=131101
D/WifiStateMachine( 1017): processMsg: DisconnectingState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiStateMachine( 1017): processMsg: DefaultState
D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=147460
D/WifiStateMachine( 1017): processMsg: DisconnectingState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): Network connection lost
D/WifiStateMachine( 1017): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1017): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1351): Read error: ssl=0x62a51a90: I/O error during system call, Connection timed out
,V/NativeCrypto( 1351): SSL shutdown failed: ssl=0x62a51a90: I/O error during system call, Broken pipe
,D/Checkin ( 1017): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiP2pService( 1017): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  271): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1017): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1017): transitionTo: destState=DisconnectedState
,D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1017): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/Checkin ( 1017): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiStateMachine( 1017): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=131216
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiStateMachine( 1017): processMsg: DefaultState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131216
D/WifiStateMachine( 1017): processMsg: DisconnectedState
,D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiStateMachine( 1017): processMsg: DefaultState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): handleMessage: X
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1017): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/ModemStatsDSDetect( 1295): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityService( 1017): Attempting to switch to mobile
D/ConnectivityService( 1017): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1017): Attempting to switch to ETHERNET
I/ModemStatsDSDetect( 1295): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1295): onReceive() - done, currentInetCondition=0
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=false
,I/ModemStatsDSDetect( 1295): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1017): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1295): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1295): onReceive() - done, currentInetCondition=0
,I/wpa_supplicant( 1155): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  273): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  273): Event received = Trying to associate with
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1017): handleMessage: E msg.what=147461
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,E/wpa_supplicant( 1155): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): handleMessage: X
,I/wpa_supplicant( 1155): WEXT: Custom wireless event: 'BEACONIEs='
,I/wpa_supplicant( 1155): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  463): NL - Read 312 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/TCMD    (  463): NL - Read 88 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/TCMD    (  463): NL - Read 68 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/TCMD    (  463): NL - Read 1000 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
,D/TCMD    (  463): Listening for incoming client connection request
I/wpa_supplicant( 1155): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  273): Event received = Associated with c0:ff:d4
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/TCMD    (  463): NL - Read 80 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/TCMD    (  463): NL - Read 80 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/TCMD    (  463): NL - Read 68 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1017): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): handleMessage: X
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1155): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1155): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  273): Event received = WPA: Key negotiation com
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  273): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  273):  STA Connected !!
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): handleMessage: X
D/TCMD    (  463): NL - Read 1000 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
,D/TCMD    (  463): Listening for incoming client connection request
D/WifiStateMachine( 1017): handleMessage: E msg.what=147459
E/MDMCTBK (  273): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  273): get_freq !!, resp=0
I/MDMCTBK (  273): get_freq !!, Strip data
I/MDMCTBK (  273): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): get_property_value, Enter
I/MDMCTBK (  273): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  273): get_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  273): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  273): set_property_value, Enter
,I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  273): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  273): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): get_property_value, Enter
I/MDMCTBK (  273): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  273): get_property_value, Exit
I/MDMCTBK (  273): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1193784496
I/MDMCTBK (  273): return from set_get_from_wpa_supplicant
I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): Network connection established
,D/WifiStateMachine( 1017): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/MDMCTBK (  273): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  273): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  273): , reply_len: 3, ret: 0
E/MDMCTBK (  273): MdmCutbackHndler, resp=OK
E/MDMCTBK (  273): 
,D/MDMCTBK (  273): wifi_set_tx_pwr: Exit
,I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/Tethering( 1017): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1017): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiStateMachine( 1017): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1017): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1017): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1017): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1017): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1017): processMsg: ObtainingIpState
,D/WifiStateMachine( 1017): ObtainingIpState{ when=-24ms what=147462 obj=android.net.wifi.StateChangeResult@43a63d50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=131101
D/WifiStateMachine( 1017): processMsg: ObtainingIpState
D/WifiStateMachine( 1017): ObtainingIpState{ when=-14ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@43abef88 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiStateMachine( 1017): processMsg: DefaultState
,D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=196612
,D/WifiStateMachine( 1017): processMsg: ObtainingIpState
D/WifiStateMachine( 1017): ObtainingIpState{ when=-5ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,D/WifiStateMachine( 1017): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1017): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1017): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@421b5c08 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@421b5c08 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): handleMessage: X
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 8 c
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 3
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 9 3
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 11 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 11 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 12 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 12 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 13 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 13 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 14 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 14 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 9e
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 3 9e
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 34
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 5 34
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 fc
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 6 fc
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 a0
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 7 a0
D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  273): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiP2pService( 1017): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@4217d4f8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@4217d4f8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): DefaultState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@4217d4f8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): handleMessage: E msg.what=147461
D/WifiStateMachine( 1017): processMsg: ObtainingIpState
D/WifiStateMachine( 1017): ObtainingIpState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1017): handleMessage: X
,D/TCMD    (  463): NL - Read 60 bytes from update socket.
D/WifiStateMachine( 1017): addressUpdated: 192.168.1.123/24 on wlan0 flags 128 scope 0
D/TCMD    (  463): NL - ignore NL message, type = 20
,D/TCMD    (  463): Listening for incoming client connection request
D/WifiStateMachine( 1017): handleMessage: E msg.what=131215
D/WifiStateMachine( 1017): processMsg: ObtainingIpState
D/WifiStateMachine( 1017): ObtainingIpState{ when=0 what=131215 obj=192.168.1.123/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1017): processMsg: DefaultState
,D/WifiStateMachine( 1017): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1017): handleMessage: X
,I/SBar.NetworkController( 1080): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
,D/Tethering( 1017): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1017): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1017): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1080): updateConnectivity: NetworkInfo: null, inetCondition= 0
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1269): Active network info is not available
,D/PollingManager( 1559): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,I/ActivityManager( 1017): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4347 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1269): Active network info is not available
,I/SBar.NetworkController( 1080): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1080): updateConnectivity: NetworkInfo: null, inetCondition= 0
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1559): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1559): Registering with Alarm Manager to restart CCE
,D/Tethering( 1017): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1017): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1243): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
D/PollingManager( 1559): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1559): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1559): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1559): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1559): [debug] > CusSM.onRadioDown
D/TelephonyProvider( 1243): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1243): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1243): Column apn id key is 'apn_id'
,D/WifiStateMachine( 1017): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1017): processMsg: ObtainingIpState
D/WifiStateMachine( 1017): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,D/WifiStateMachine( 1017): setSuspendOptimizationsNative: 1 true
,D/dalvikvm( 4347): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fdefc8, skipping init
I/openssl ( 4347): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4347): Crypto mode 0 already enabled
D/WifiP2pService( 1017): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): DHCP successful
D/WifiStateMachine( 1017): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1017): Calling ARP set with IP = 192.168.1.123
,I/ActivityManager( 1017): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4382 uid=10030 gids={50030, 3003, 1028, 1015}
D/WifiStateMachine( 1017): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1017): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1017): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1017): VerifyingLinkState enter
D/WifiStateMachine( 1017): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=151572
D/WifiStateMachine( 1017): processMsg: VerifyingLinkState
D/WifiStateMachine( 1017): VerifyingLinkState what=151572 NOT_HANDLED
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,I/ActivityManager( 1017): Killing 3946:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4382): mnc/mcc: 
,V/MmsConfig( 4382): tag: bool value: enabledMMS - true
V/MmsConfig( 4382): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4382): tag: int value: maxImageHeight - 1944
,V/MmsConfig( 4382): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4382): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4382): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4382): tag: int value: minMessageCountPerThread - 10
,V/MmsConfig( 4382): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4382): tag: int value: recipientLimit - 20
V/MmsConfig( 4382): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4382): tag: int value: smsToMmsTextThreshold - 6
,V/MmsConfig( 4382): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4382): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4382): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4382): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4382): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 4382): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4382): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1017): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4400 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1017): Killing 4078:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/SBar.NetworkController( 1080): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=135190
D/WifiStateMachine( 1017): processMsg: VerifyingLinkState
D/WifiStateMachine( 1017): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1017): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1017): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1017): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1017): CaptivePortalCheckState enter
,D/WifiStateMachine( 1017): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1017): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1017): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1017): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1017): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131092
D/WifiStateMachine( 1017): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1017): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiStateMachine( 1017): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1017): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1017): WiFi NOT Tethered!
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,E/ConnectivityService( 1017): Unexpected mtu value: android.net.wifi.WifiStateTracker@420b5468
I/SBar.NetworkController( 1080): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/Checkin ( 1017): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/WifiStateMachine( 1017): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1017): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1017): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131092
D/WifiStateMachine( 1017): processMsg: ConnectedState
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiStateMachine( 1017): processMsg: DefaultState
,D/WifiStateMachine( 1017): handleMessage: X
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=true
,I/ModemStatsDSDetect( 1295): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityService( 1017): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1017): WiFi NOT Tethered!
,E/ConnectivityService( 1017): Unexpected mtu value: android.net.wifi.WifiStateTracker@420b5468
I/ModemStatsDSDetect( 1295): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1080): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/ModemStatsDSDetect( 1295): onReceive() - done, currentInetCondition=0
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1080): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/MobileConnectivityChangeReceiver( 4400): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/ConnectivityService( 1017): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/MobileConnectivityChangeReceiver( 4400): onReceive CONNECTIVITY_CHANGE networkType=1
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=true
E/PhoneMonitor( 4400): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4400): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1017): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4415 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1017): Killing 3645:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ModemStatsDSDetect( 1295): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1295): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1295): onReceive() - done, currentInetCondition=0
,I/CheckinService( 1392): Checkin interval check for package: unspecified last checkin: 1448282726355 min interval config: 0 actual interval: 281486
,I/CheckinService( 1392): Checking schedule, now: 1448283007847 next: 1448282756329
,I/CheckinService( 1392): active receiver: enabled
,I/CheckinService( 1392): Preparing to send checkin request
,I/EventLogService( 1392): Accumulating logs since 1448282722708
,I/CheckinRequestBuilder( 1392): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1392): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1017): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4430 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1017): Killing 4120:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1017): GC_EXPLICIT freed 1744K, 65% free 17994K/50356K, paused 3ms+10ms, total 96ms
,V/WebViewChromiumFactoryProvider( 4430): Binding Chromium to main looper Looper (main, tid 1) {41fdbd68}
,I/LibraryLoader( 4430): Expected native library version number "",actual native library version number ""
,I/chromium( 4430): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4430): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4430): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4430): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4430): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4430): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4430): Local Branch: 
I/Adreno-EGL( 4430): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4430): Local Patches: NONE
I/Adreno-EGL( 4430): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium( 4430): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/ActivityManager( 1017): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4460 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/GAV2    ( 4430): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  261): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  261): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4430): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/dalvikvm( 4460): VFY: unable to resolve static field 529 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4460): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4460): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4460): VFY: unable to resolve virtual method 10979: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
D/dalvikvm( 4460): VFY: replacing opcode 0x6e at 0x00ca
I/MultiDex( 4460): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4460): install
,I/MultiDex( 4460): MultiDexExtractor.load(/data/app/com.google.android.gms-2.apk, false)
,I/MultiDex( 4460): loading existing secondary dex files
,I/MultiDex( 4460): load found 3 secondary dex files
,I/MultiDex( 4460): install done
,D/dalvikvm( 4460): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4460): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4460): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4460): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4460): VFY: unable to resolve instance field 46
,D/dalvikvm( 4460): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4460): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4460): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4460): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4460): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4460): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 4460): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41fe1948
D/dalvikvm( 4460): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41fe1948
,D/dalvikvm( 4460): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41fe1948, skipping init
,D/dalvikvm( 4460): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41fe1948
D/dalvikvm( 4460): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41fe1948
,V/JNIHelp ( 4460): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/dalvikvm( 4460): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41fe1948
,D/dalvikvm( 4460): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x41fe1948
D/dalvikvm( 4460): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41fe1948
,D/dalvikvm( 4460): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41fe1948
,I/NSApplication( 4430): Starting up...
,I/ImageResourceManager( 3677): ImageResourceManager: uninitalized
,I/iu.Environment( 3677): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1017): Killing 3661:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/DEBUG   ( 1559): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1559): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1559): bindWebServices(): registering our AIDL callback...
I/SundryService( 1559): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1559): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1559): onServiceConnected()
,D/GetNotificationsWS( 1559): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1559): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1559): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4347): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4347): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4400): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4400): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ProviderInstaller( 4460): Installed default security provider GmsCore_OpenSSL
,I/iu.Environment( 3677): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/WearableService( 1213): callingUid 10022, callindPid: 1213
,I/dalvikvm( 4460): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
,W/dalvikvm( 4460): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 4460): VFY: replacing opcode 0x6e at 0x000d
,E/MDM     ( 1213): [79] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/dalvikvm( 4460): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 4460): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4460): VFY: replacing opcode 0x6e at 0x0220
,D/GCM     ( 1351): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/LocationInitializer( 1392): Restart initialization of location
,D/AuthorizationBluetoothService( 1351): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1351): Proximity feature is not enabled.
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1392): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/dalvikvm( 4460): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4460): Link of class 'Lcom/google/android/gms/common/h/c;' failed
E/dalvikvm( 4460): Could not find class 'com.google.android.gms.common.h.c', referenced from method com.google.android.gms.common.h.b.a
W/dalvikvm( 4460): VFY: unable to resolve new-instance 2668 (Lcom/google/android/gms/common/h/c;) in Lcom/google/android/gms/common/h/b;
D/dalvikvm( 4460): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4460): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.h.b.b
W/dalvikvm( 4460): VFY: unable to resolve virtual method 328: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4460): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 4460): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4460): Link of class 'Lcom/google/android/gms/common/h/c;' failed
,D/dalvikvm( 4460): DexOpt: unable to opt direct call 0x2d44 at 0x02 in Lcom/google/android/gms/common/h/b;.a
,I/jxcore-log( 4256): Attempting to connect to the test coordinator server
I/jxcore-log( 4256): 
,W/GCoreFlp( 1213): No location to return for getLastLocation()
,W/FusedLocationProvider( 1351): location=null
,D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  278): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  278): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  278): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5398000
,E/DrmWidevineDash(  278): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5398000
D/DrmWidevineDash(  278): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  278): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  278): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  278): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  278): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  278): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=1733305907
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4460): Install completed successfully. count=13 extracted=0
,D/ConnectivityService( 1017): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 4460): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421b35e0
,D/dalvikvm( 4460): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421b35e0
,D/dalvikvm( 4460): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421b35e0, skipping init
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4460): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4498): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4460): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4460): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 68ms
,I/Adreno-EGL( 4460): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4460): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4460): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4460): Local Branch: 
I/Adreno-EGL( 4460): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4460): Local Patches: NONE
I/Adreno-EGL( 4460): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4460): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4460): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4460): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4460): Local Branch: 
I/Adreno-EGL( 4460): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4460): Local Patches: NONE
I/Adreno-EGL( 4460): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
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
D/WVCdm   (  278): PrepareKeyRequest: nonce=1301249161
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,I/Adreno-EGL( 4460): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4460): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4460): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4460): Local Branch: 
I/Adreno-EGL( 4460): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4460): Local Patches: NONE
I/Adreno-EGL( 4460): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4460): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4460): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4460): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4460): Local Branch: 
I/Adreno-EGL( 4460): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4460): Local Patches: NONE
I/Adreno-EGL( 4460): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 4460): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1392): Classify the device as Phone.
,I/CheckinTask( 1392): Sending checkin request (11719 bytes)
,W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
D/PollingManager( 1559): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1080): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1080): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/Tethering( 1017): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/CaptivePortalTracker( 1017): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/PollingManager( 1559): now: 326196 ,futureTime: 78091397
,D/PollingManager( 1559): Polling alarm set to expire at: 78091397 Current Time: 326197
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1080): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1080): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1243): Column apn id key is 'apn_id'
,D/Tethering( 1017): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1017): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1243): Column apn id key is 'apn_id'
,E/ActivityThread( 1559): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1559): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/OtaApp  ( 1559): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1559): [debug] > CusSM.onRadioUp
D/PollingManager( 1559): now: 326244 ,futureTime: 78091397
D/PollingManager( 1559): Polling alarm set to expire at: 78091397 Current Time: 326247
D/OtaApp  ( 1559): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/CheckinRequestBuilder( 1392): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1392): Failed to find provider info for com.google.android.wearable.settings
E/ActivityThread( 1559): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1559): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1559): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1559): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
I/openssl ( 4347): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4347): Crypto mode 0 already enabled
D/Checkin ( 1559): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1559): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1559): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/OtaApp  ( 1559): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/TelephonyProvider( 1243): Column apn id key is 'apn_id'
D/OtaApp  ( 1559): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1559): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/TelephonyProvider( 1243): Column apn id key is 'apn_id'
D/MobileConnectivityChangeReceiver( 4400): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4400): onReceive CONNECTIVITY_CHANGE networkType=1
D/OtaApp  ( 1559): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1559): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1559): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1559): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1559): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/OtaApp  ( 1559): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/dalvikvm( 1559): GC_CONCURRENT freed 2011K, 38% free 10733K/17224K, paused 3ms+3ms, total 34ms
D/dalvikvm( 1559): WAIT_FOR_CONCURRENT_GC blocked 10ms
D/dalvikvm( 3677): GC_FOR_ALLOC freed 620K, 5% free 16441K/17224K, paused 21ms, total 22ms
I/dalvikvm-heap( 3677): Grow heap (frag case) to 19.825MB for 1821008-byte allocation
,I/iu.Environment( 3677): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/dalvikvm( 3677): GC_FOR_ALLOC freed 40K, 5% free 18183K/19004K, paused 16ms, total 16ms
,I/CheckinService( 1392): Checkin interval check for package: unspecified last checkin: 1448282726355 min interval config: 0 actual interval: 284651
,D/DEBUG   ( 1559): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1559): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1559): bindWebServices(): registering our AIDL callback...
I/SundryService( 1559): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1559): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1559): onServiceConnected()
D/GetNotificationsWS( 1559): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1559): ServiceHandler.handleMessage: mWaitCount=0
I/openssl ( 4347): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4347): Crypto mode 0 already enabled
D/GetNotificationsWS( 1559): unbindWebServices(): un-registering our AIDL callback...
,D/MobileConnectivityChangeReceiver( 4400): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4400): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3677): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1392): Checkin interval check for package: unspecified last checkin: 1448282726355 min interval config: 0 actual interval: 284733
,D/DEBUG   ( 1559): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1559): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1559): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1559): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/EmailService.MarketingOptInSetter( 1559): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1559): onServiceConnected()
,D/GetNotificationsWS( 1559): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1559): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1559): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1559): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1017): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1559
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/CheckinRequestBuilder( 1392): Classify the device as Phone.
,D/GetNotificationsWS( 1559): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1559): [info] > Updatetime from metadata: 10
,D/Checkin ( 1559): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1559): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1559): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1559): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1559): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1559): [info] > Updatetime from metadata: 10
,D/Checkin ( 1559): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1559): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1559): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1559): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1559): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,I/CheckinTask( 1392): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,D/OtaApp  ( 1559): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1017): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1559
W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/CheckinService( 1392): Checking schedule, now: 1448283011153 next: 1448876081149
I/CheckinService( 1392): active receiver: disabled
D/OtaApp  ( 1559): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/SFPerfTracer(  274):      triggers: (rate: 1:26) (compose: 0:4) (post: 0:1) (render: 0:5) (0:105 frames) (1:543)
,D/SFPerfTracer(  274):        layers: (0:12) (FocusedStackFrame: 1:10)* (StatusBar: 0:211)* (NavigationBar: 0:38)* (com.android.systemui.ImageWallpaper: 0:6)* (Starting com.motorola.ccc.ota: 0:33)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:17)* (ElectronBeam: 0:26)* (com.test.thalitest/com.test.thalitest.MainActivity: 1:5)* 
I/OtaApp  ( 1559): [info] > Updatetime from metadata: 10
D/Checkin ( 1559): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1559): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1559): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1559): publish the event [tag = MOT_OTA event name = LOG]
I/CheckinService( 1392): Checking schedule, now: 1448283011182 next: 1448876081149
I/CheckinService( 1392): active receiver: disabled
,D/CheckinService( 1392): Recording last checkin time for package unspecified as 1448283011187
,I/OtaApp  ( 1559): [info] > Updatetime from metadata: 10
,D/Checkin ( 1559): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1559): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1559): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1559): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1559): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1559): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1017): Activity reported stop, but no longer stopping: ActivityRecord{420138e8 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/LaunchCheckinHandler( 1017): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,132
D/GCM     ( 1351): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/dalvikvm( 1351): GC_CONCURRENT freed 1891K, 39% free 10637K/17224K, paused 3ms+4ms, total 38ms
,D/GetConfigurationSnapshotOperation( 1351): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1351): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1351): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1351): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/dalvikvm( 1351): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1351): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1351): VFY: replacing opcode 0x6e at 0x0033
,D/ConnectivityService( 1017): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/SBar.NetworkController( 1080): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1295): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1080): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1080): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1295): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1295): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1295): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/GetCommittedConfigurationOperation( 1351): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1351):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1351): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1351): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1351): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/GAV2    ( 4430): Thread[GAThread,5,main]: No campaign data found.
,D/WifiStateMachine( 1017): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1017): handleMessage: E msg.what=131215
D/WifiStateMachine( 1017): processMsg: ConnectedState
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1017): processMsg: DefaultState
D/WifiStateMachine( 1017): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1017): handleMessage: X
D/ConnectivityService( 1017): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1017):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1017): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=true
,I/ActivityManager( 1017): Killing 4145:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Launcher( 1309): Deferring update until onResume
,I/ActivityManager( 1017): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4566 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "sms"
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mms"
,I/Launcher( 1309): Deferring update until onResume
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mmsto"
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "sms"
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mms"
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mmsto"
,V/GmsNetworkLocationProvi( 1213): DISABLE
,I/GCoreNlp( 1213): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4566): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4566): MmsConfig.loadMmsSettings
,I/Babel   ( 4566): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4566): MmsConfig.loadFromDatabase
,E/Babel   ( 4566): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4566): MmsConfig.loadFromResources
,E/Babel   ( 4566): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4566): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,D/dalvikvm( 1017): GC_EXPLICIT freed 1690K, 65% free 18005K/50356K, paused 6ms+10ms, total 95ms
,W/Settings( 4566): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1017): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4598 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,D/dalvikvm(  276): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+2ms, total 21ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 18ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 18ms
,I/ActivityManager( 1017): Killing 3708:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1017): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4617 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1017): Killing 4347:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2336): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 1392): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager( 1017): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4636 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1017): Killing 4382:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/PackageBroadcastService( 1392): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1392): updateResources: need to parse f{com.google.android.gms}
,I/dalvikvm( 4636): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4636): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4636): VFY: replacing opcode 0x6e at 0x000e
,I/ContactLocale( 4598): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/Finsky  ( 4636): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/dalvikvm( 1392): GC_CONCURRENT freed 1948K, 32% free 11728K/17224K, paused 4ms+5ms, total 38ms
,I/dalvikvm( 4636): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4636): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4636): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4636): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4636): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4636): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4636): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4636): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4636): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4636): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4636): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4636): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4636): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4636): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4636): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4636): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4636): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4636): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4636): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4636): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4636): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1017): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4672 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/InternalIcingCorporaPro( 2336): UpdateCorporaTask done [took 325 ms] updated apps [took 325 ms] 
,I/dalvikvm( 4636): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4636): VFY: unable to resolve virtual method 9030: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4636): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4636): Skipping gmscore version check
,D/Finsky  ( 4636): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4636): [1] Libraries$2.run: Finished loading 1 libraries.
I/dalvikvm( 4636): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4636): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4636): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1017): Killing 4400:com.google.android.setupwizard/u0a41 (adj 15): empty #9
W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 4672): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fdd3e0, skipping init
I/openssl ( 4672): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4672): Crypto mode 0 already enabled
,I/ActivityManager( 1017): Killing 4415:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Finsky  ( 4636): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4636): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/CaptivePortalTracker( 1017): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1017): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1017): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1017): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1017): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1017): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1017): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1017): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/jxcore-log( 4256): Attempting to connect to the test coordinator server
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Attempting to connect to the test coordinator server
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Attempting to connect to the test coordinator server
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Attempting to connect to the test coordinator server
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Attempting to connect to the test coordinator server
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Attempting to connect to the test coordinator server
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Attempting to connect to the test coordinator server
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Attempting to connect to the test coordinator server
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Test app app.js loaded
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"setup","id":0}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): LogCallback not set !!!!
I/jxcore-log( 4256): 
,I/Choreographer( 4256): Skipped 1227 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4256): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/IInputConnectionWrapper( 4256): showStatusIcon on inactive InputConnection
,I/jxcore-log( 4256): DBG, CoordinatorConnector connect called
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): DBG, CoordinatorConnector connect called
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): DBG, CoordinatorConnector connect called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector connect called
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): DBG, CoordinatorConnector connect called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector connect called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector connect called
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): DBG, CoordinatorConnector connect called
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): DBG, CoordinatorConnector connect called
I/jxcore-log( 4256): 
,V/AlarmManager( 1017): sending alarm Alarm{4292de70 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{424c5f38 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{425dcd30 type 3 android}
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 9,
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1,
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1,
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1,
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1,
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{424faa28 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4256): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"end","test":0}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"test connectionTable table building and cleanup","id":1}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): DB value for ThaliReplicationManager is: "bogus"
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":50,"expected":50,"test":1,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":1,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":40,"expected":40,"test":1,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":60,"expected":60,"test":1,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":1,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":1,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":8,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":{"muxPort":60,"time":1448283290056},"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":9,"ok":true,"name":"Cleanup was called, this table is no longer live.","operator":"throws","actual":{"message":"Cleanup was called, this table is no longer live."},"test":1,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"end","test":1}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"teardown","id":2}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 1 isOK: undefined : test connectionTable table building and cleanup", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : Cleanup was called, this table is no longer live.", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 2 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":2}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"setup","id":3}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 3 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":3}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"test connectionTable emitting events for peerIds","id":4}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): DB value for ThaliReplicationManager is: "bogus"
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":30,"expected":30,"test":4,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":1,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":40,"expected":40,"test":4,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":50,"expected":50,"test":4,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":60,"expected":60,"test":4,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":7,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"end","test":4}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"teardown","id":5}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 4 isOK: undefined : test connectionTable emitting events for peerIds", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 5 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":5}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"setup","id":6}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 6 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":6}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"test","name":"start with bad friendly names","id":7}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":0,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":1,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":2,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":3,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"end","test":7}
I/jxcore-log( 4256): 
,V/AlarmManager( 1017): sending alarm Alarm{428cf308 type 3 android}
I/jxcore-log( 4256): {"type":"test","name":"teardown","id":8}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 7 isOK: undefined : start with bad friendly names", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 8 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":8}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"setup","id":9}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 9 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":9}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"test","name":"make sure startIdentityExchange sets things up properly","id":10}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 10 isOK: undefined : make sure startIdentityExchange sets things up properly", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: 1OJS8gwjLkKJAqMg6PQe4w==;Matt
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":46377,"expected":46377,"test":10,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":10,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"1OJS8gwjLkKJAqMg6PQe4w==;Matt","expected":"1OJS8gwjLkKJAqMg6PQe4w==;Matt","test":10,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":4,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":"123","expected":"123","test":10,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":8,"ok":true,"name":"should be equal","operator":"equal","actual":"bar1","expected":"bar1","test":10,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":9,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":"456","expected":"456","test":10,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":11,"ok":true,"name":"should be equal","operator":"equal","actual":"bar2","expected":"bar2","test":10,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":"started","expected":"started","test":10,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"end","test":10}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"teardown","id":11}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 11 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":11}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"setup","id":12}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 12 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":12}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"test","name":"make sure we get an error if we call start and then immediately call stop","id":13}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state startIdentityExchangeCalledCB","test":13,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"end","test":13}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"teardown","id":14}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: LOvFzvZCWmtXlM0nf6f5bw==;Toby
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":43597,"expected":43597,"test":13,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":13,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"LOvFzvZCWmtXlM0nf6f5bw==;Toby","expected":"LOvFzvZCWmtXlM0nf6f5bw==;Toby","test":13,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":13,"type":"assert"}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 13 isOK: undefined : make sure we get an error if we call start and then immediately call stop", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 14 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":14}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"setup","id":15}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 15 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":15}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"test","name":"Make sure stop is clean from start","id":16}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: UacaviIoS95xmDalm8L2nA==;Luke
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":33798,"expected":33798,"test":16,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":16,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"UacaviIoS95xmDalm8L2nA==;Luke","expected":"UacaviIoS95xmDalm8L2nA==;Luke","test":16,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":3,"ok":true,"name":"Should not have gotten error on startIdentityExchange","operator":"notOk","actual":null,"expected":false,"test":16,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":4,"ok":true,"name":"Should not have gotten error on stopIdentityExchange","operator":"notOk","expected":false,"test":16,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":5,"ok":true,"name":"State should be Stopped","operator":"equal","actual":"stopped","expected":"stopped","test":16,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"end","test":16}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 16 isOK: undefined : Make sure stop is clean from start", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"test","name":"teardown","id":17}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : Should not have gotten error on startIdentityExchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : Should not have gotten error on stopIdentityExchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : State should be Stopped", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 17 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":17}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"setup","id":18}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 18 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":18}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"test","name":"Make sure stop is clean from stop execute identity exchange","id":19}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: Tfdj4jRomlxHMAHyPTI7XQ==;Jukka
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":34926,"expected":34926,"test":19,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":19,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"Tfdj4jRomlxHMAHyPTI7XQ==;Jukka","expected":"Tfdj4jRomlxHMAHyPTI7XQ==;Jukka","test":19,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":19,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":4,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":19,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"stopped","expected":"stopped","test":19,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"end","test":19}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 19 isOK: undefined : Make sure stop is clean from stop execute identity exchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"test","name":"teardown","id":20}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 20 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":20}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"setup","id":21}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 21 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":21}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"test","name":"make sure we do not have a race condition between startIdentityExchange and executeIdentityExchange","id":22}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: F+XyLRJApIOrhJD5MwcmqA==;Doug
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":32849,"expected":32849,"test":22,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":22,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"F+XyLRJApIOrhJD5MwcmqA==;Doug","expected":"F+XyLRJApIOrhJD5MwcmqA==;Doug","test":22,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":22,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":4,"ok":true,"name":"should not throw","operator":"throws","test":22,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":22,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":22,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"end","test":22}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 22 isOK: undefined : make sure we do not have a race condition between startIdentityExchange and executeIdentityExchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"test","name":"teardown","id":23}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should not throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 23 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":23}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"setup","id":24}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 24 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":24}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"test","name":"illegal method combinations","id":25}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): {"id":1,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":2,"ok":true,"name":"should throw","operator":"throws","actual":"event stopIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: ClRQC0xyfAnO0kDXBM7TLg==;David
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":46130,"expected":46130,"test":25,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":25,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"ClRQC0xyfAnO0kDXBM7TLg==;David","expected":"ClRQC0xyfAnO0kDXBM7TLg==;David","test":25,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":25,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":7,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":8,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":9,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":25,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":10,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":11,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: ClRQC0xyfAnO0kDXBM7TLg==;David
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":46130,"expected":46130,"test":25,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":13,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":25,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":14,"ok":true,"name":"should be equal","operator":"equal","actual":"ClRQC0xyfAnO0kDXBM7TLg==;David","expected":"ClRQC0xyfAnO0kDXBM7TLg==;David","test":25,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":15,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":25,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":16,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":17,"ok":true,"name":"should throw","operator":"throws","actual":"event stopIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":18,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":19,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":20,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"end","test":25}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 25 isOK: undefined : illegal method combinations", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"test","name":"teardown","id":26}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 13 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 14 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 15 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 16 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 17 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 18 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 19 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 20 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 26 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":26}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"setup","id":27}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 27 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":27}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"test","name":"do an identity exchange and get code multiple times to make sure we do not hork state","id":28}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: Pk0XYadCI4vGLfTG5Z1i7g==;John
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":46726,"expected":46726,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"Pk0XYadCI4vGLfTG5Z1i7g==;John","expected":"Pk0XYadCI4vGLfTG5Z1i7g==;John","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: 4SypTkjLsuG3szgzFcRP4Q==;Srikanth
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":48256,"expected":48256,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":"4SypTkjLsuG3szgzFcRP4Q==;Srikanth","expected":"4SypTkjLsuG3szgzFcRP4Q==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":7,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO smallerHash Making /identity/cb request to pkOther value 4SypTkjLsuG3szgzFcRP4Q==
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 28 isOK: undefined : do an identity exchange and get code multiple times to make sure we do not hork state", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO smallerHash Making /identity/rnmine request to pkOther value 4SypTkjLsuG3szgzFcRP4Q==
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":8,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":9,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":10,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":11,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":173952,"expected":173952,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":13,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":14,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: Pk0XYadCI4vGLfTG5Z1i7g==;John
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":15,"ok":true,"name":"should be equal","operator":"equal","actual":46726,"expected":46726,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): {"id":16,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":17,"ok":true,"name":"should be equal","operator":"equal","actual":"Pk0XYadCI4vGLfTG5Z1i7g==;John","expected":"Pk0XYadCI4vGLfTG5Z1i7g==;John","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":18,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: 4SypTkjLsuG3szgzFcRP4Q==;Srikanth
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":19,"ok":true,"name":"should be equal","operator":"equal","actual":48256,"expected":48256,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":20,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":21,"ok":true,"name":"should be equal","operator":"equal","actual":"4SypTkjLsuG3szgzFcRP4Q==;Srikanth","expected":"4SypTkjLsuG3szgzFcRP4Q==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":22,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO smallerHash Making /identity/cb request to pkOther value 4SypTkjLsuG3szgzFcRP4Q==
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 13 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 14 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 15 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 16 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 17 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 18 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 19 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO smallerHash Making /identity/rnmine request to pkOther value 4SypTkjLsuG3szgzFcRP4Q==
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 20 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 21 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 22 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":23,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":24,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 23 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":25,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":26,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":27,"ok":true,"name":"should be equal","operator":"equal","actual":400832,"expected":400832,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":28,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":29,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: Pk0XYadCI4vGLfTG5Z1i7g==;John
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":30,"ok":true,"name":"should be equal","operator":"equal","actual":46726,"expected":46726,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":31,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":32,"ok":true,"name":"should be equal","operator":"equal","actual":"Pk0XYadCI4vGLfTG5Z1i7g==;John","expected":"Pk0XYadCI4vGLfTG5Z1i7g==;John","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":33,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: 4SypTkjLsuG3szgzFcRP4Q==;Srikanth
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":34,"ok":true,"name":"should be equal","operator":"equal","actual":48256,"expected":48256,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":35,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":36,"ok":true,"name":"should be equal","operator":"equal","actual":"4SypTkjLsuG3szgzFcRP4Q==;Srikanth","expected":"4SypTkjLsuG3szgzFcRP4Q==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":37,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO smallerHash Making /identity/cb request to pkOther value 4SypTkjLsuG3szgzFcRP4Q==
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 24 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 25 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 26 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 27 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 28 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 29 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 30 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 31 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 32 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 33 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO smallerHash Making /identity/rnmine request to pkOther value 4SypTkjLsuG3szgzFcRP4Q==
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 34 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 35 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 36 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":38,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":39,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 37 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":40,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":41,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":42,"ok":true,"name":"should be equal","operator":"equal","actual":911680,"expected":911680,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":43,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":44,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: Pk0XYadCI4vGLfTG5Z1i7g==;John
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":45,"ok":true,"name":"should be equal","operator":"equal","actual":46726,"expected":46726,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":46,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":47,"ok":true,"name":"should be equal","operator":"equal","actual":"Pk0XYadCI4vGLfTG5Z1i7g==;John","expected":"Pk0XYadCI4vGLfTG5Z1i7g==;John","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":48,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: 4SypTkjLsuG3szgzFcRP4Q==;Srikanth
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":49,"ok":true,"name":"should be equal","operator":"equal","actual":48256,"expected":48256,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":50,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":51,"ok":true,"name":"should be equal","operator":"equal","actual":"4SypTkjLsuG3szgzFcRP4Q==;Srikanth","expected":"4SypTkjLsuG3szgzFcRP4Q==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":52,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO smallerHash Making /identity/cb request to pkOther value 4SypTkjLsuG3szgzFcRP4Q==
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 38 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 39 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 40 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 41 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 42 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 43 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 44 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 45 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO smallerHash Making /identity/rnmine request to pkOther value 4SypTkjLsuG3szgzFcRP4Q==
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 46 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 47 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 48 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 49 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 50 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 51 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":53,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":54,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 52 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":55,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":56,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":57,"ok":true,"name":"should be equal","operator":"equal","actual":775168,"expected":775168,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":58,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":59,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: Pk0XYadCI4vGLfTG5Z1i7g==;John
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":60,"ok":true,"name":"should be equal","operator":"equal","actual":46726,"expected":46726,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":61,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":62,"ok":true,"name":"should be equal","operator":"equal","actual":"Pk0XYadCI4vGLfTG5Z1i7g==;John","expected":"Pk0XYadCI4vGLfTG5Z1i7g==;John","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":63,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: 4SypTkjLsuG3szgzFcRP4Q==;Srikanth
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":64,"ok":true,"name":"should be equal","operator":"equal","actual":48256,"expected":48256,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":65,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":66,"ok":true,"name":"should be equal","operator":"equal","actual":"4SypTkjLsuG3szgzFcRP4Q==;Srikanth","expected":"4SypTkjLsuG3szgzFcRP4Q==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":67,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO smallerHash Making /identity/cb request to pkOther value 4SypTkjLsuG3szgzFcRP4Q==
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 53 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 54 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 55 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 56 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 57 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 58 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 59 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 60 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 61 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO smallerHash Making /identity/rnmine request to pkOther value 4SypTkjLsuG3szgzFcRP4Q==
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 62 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 63 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 64 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 65 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 66 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 67 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":68,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":69,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 68 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":70,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":71,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":72,"ok":true,"name":"should be equal","operator":"equal","actual":451072,"expected":451072,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":73,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":74,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: Pk0XYadCI4vGLfTG5Z1i7g==;John
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":75,"ok":true,"name":"should be equal","operator":"equal","actual":46726,"expected":46726,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":76,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":77,"ok":true,"name":"should be equal","operator":"equal","actual":"Pk0XYadCI4vGLfTG5Z1i7g==;John","expected":"Pk0XYadCI4vGLfTG5Z1i7g==;John","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":78,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: 4SypTkjLsuG3szgzFcRP4Q==;Srikanth
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":79,"ok":true,"name":"should be equal","operator":"equal","actual":48256,"expected":48256,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":80,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":81,"ok":true,"name":"should be equal","operator":"equal","actual":"4SypTkjLsuG3szgzFcRP4Q==;Srikanth","expected":"4SypTkjLsuG3szgzFcRP4Q==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":82,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO smallerHash Making /identity/cb request to pkOther value 4SypTkjLsuG3szgzFcRP4Q==
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 69 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 70 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 71 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 72 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 73 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 74 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO smallerHash Making /identity/rnmine request to pkOther value 4SypTkjLsuG3szgzFcRP4Q==
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 75 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 76 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 77 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 78 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 79 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 80 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":83,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":84,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 81 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 82 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":85,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":86,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":87,"ok":true,"name":"should be equal","operator":"equal","actual":779712,"expected":779712,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":88,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":89,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: Pk0XYadCI4vGLfTG5Z1i7g==;John
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":90,"ok":true,"name":"should be equal","operator":"equal","actual":46726,"expected":46726,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":91,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":92,"ok":true,"name":"should be equal","operator":"equal","actual":"Pk0XYadCI4vGLfTG5Z1i7g==;John","expected":"Pk0XYadCI4vGLfTG5Z1i7g==;John","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":93,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: 4SypTkjLsuG3szgzFcRP4Q==;Srikanth
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":94,"ok":true,"name":"should be equal","operator":"equal","actual":48256,"expected":48256,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): {"id":95,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): {"id":96,"ok":true,"name":"should be equal","operator":"equal","actual":"4SypTkjLsuG3szgzFcRP4Q==;Srikanth","expected":"4SypTkjLsuG3szgzFcRP4Q==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): {"id":97,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO smallerHash Making /identity/cb request to pkOther value 4SypTkjLsuG3szgzFcRP4Q==
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 83 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 84 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 85 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 86 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 87 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO smallerHash Making /identity/rnmine request to pkOther value 4SypTkjLsuG3szgzFcRP4Q==
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 88 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 89 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":98,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":99,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 90 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 91 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 92 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 93 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":100,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":101,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":102,"ok":true,"name":"should be equal","operator":"equal","actual":486016,"expected":486016,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":103,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":104,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: Pk0XYadCI4vGLfTG5Z1i7g==;John
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":105,"ok":true,"name":"should be equal","operator":"equal","actual":46726,"expected":46726,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":106,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":107,"ok":true,"name":"should be equal","operator":"equal","actual":"Pk0XYadCI4vGLfTG5Z1i7g==;John","expected":"Pk0XYadCI4vGLfTG5Z1i7g==;John","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":108,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: 4SypTkjLsuG3szgzFcRP4Q==;Srikanth
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":109,"ok":true,"name":"should be equal","operator":"equal","actual":48256,"expected":48256,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":110,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":111,"ok":true,"name":"should be equal","operator":"equal","actual":"4SypTkjLsuG3szgzFcRP4Q==;Srikanth","expected":"4SypTkjLsuG3szgzFcRP4Q==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":112,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO smallerHash Making /identity/cb request to pkOther value 4SypTkjLsuG3szgzFcRP4Q==
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 94 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 95 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 96 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 97 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 98 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 99 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 100 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 101 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 102 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 103 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 104 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 105 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO smallerHash Making /identity/rnmine request to pkOther value 4SypTkjLsuG3szgzFcRP4Q==
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 106 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 107 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 108 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 109 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 110 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 111 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":113,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":114,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 112 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":115,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":116,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":117,"ok":true,"name":"should be equal","operator":"equal","actual":631872,"expected":631872,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":118,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":119,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: Pk0XYadCI4vGLfTG5Z1i7g==;John
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":120,"ok":true,"name":"should be equal","operator":"equal","actual":46726,"expected":46726,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":121,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":122,"ok":true,"name":"should be equal","operator":"equal","actual":"Pk0XYadCI4vGLfTG5Z1i7g==;John","expected":"Pk0XYadCI4vGLfTG5Z1i7g==;John","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":123,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: 4SypTkjLsuG3szgzFcRP4Q==;Srikanth
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":124,"ok":true,"name":"should be equal","operator":"equal","actual":48256,"expected":48256,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":125,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":126,"ok":true,"name":"should be equal","operator":"equal","actual":"4SypTkjLsuG3szgzFcRP4Q==;Srikanth","expected":"4SypTkjLsuG3szgzFcRP4Q==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":127,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO smallerHash Making /identity/cb request to pkOther value 4SypTkjLsuG3szgzFcRP4Q==
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 113 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 114 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 115 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 116 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 117 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 118 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO smallerHash Making /identity/rnmine request to pkOther value 4SypTkjLsuG3szgzFcRP4Q==
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 119 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 120 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 121 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":128,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":129,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 122 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 123 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 124 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":130,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":131,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":132,"ok":true,"name":"should be equal","operator":"equal","actual":709248,"expected":709248,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":133,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":134,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: Pk0XYadCI4vGLfTG5Z1i7g==;John
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":135,"ok":true,"name":"should be equal","operator":"equal","actual":46726,"expected":46726,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":136,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":137,"ok":true,"name":"should be equal","operator":"equal","actual":"Pk0XYadCI4vGLfTG5Z1i7g==;John","expected":"Pk0XYadCI4vGLfTG5Z1i7g==;John","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":138,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: 4SypTkjLsuG3szgzFcRP4Q==;Srikanth
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":139,"ok":true,"name":"should be equal","operator":"equal","actual":48256,"expected":48256,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":140,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":141,"ok":true,"name":"should be equal","operator":"equal","actual":"4SypTkjLsuG3szgzFcRP4Q==;Srikanth","expected":"4SypTkjLsuG3szgzFcRP4Q==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":142,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO smallerHash Making /identity/cb request to pkOther value 4SypTkjLsuG3szgzFcRP4Q==
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 125 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 126 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 127 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 128 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 129 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 130 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 131 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 132 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO smallerHash Making /identity/rnmine request to pkOther value 4SypTkjLsuG3szgzFcRP4Q==
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 133 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 134 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 135 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 136 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":143,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":144,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 137 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 138 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 139 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 140 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":145,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":146,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":147,"ok":true,"name":"should be equal","operator":"equal","actual":814912,"expected":814912,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":148,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":149,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: Pk0XYadCI4vGLfTG5Z1i7g==;John
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":150,"ok":true,"name":"should be equal","operator":"equal","actual":46726,"expected":46726,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":151,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":152,"ok":true,"name":"should be equal","operator":"equal","actual":"Pk0XYadCI4vGLfTG5Z1i7g==;John","expected":"Pk0XYadCI4vGLfTG5Z1i7g==;John","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":153,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO identityExchange We will advertise the following device name as we start: 4SypTkjLsuG3szgzFcRP4Q==;Srikanth
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":154,"ok":true,"name":"should be equal","operator":"equal","actual":48256,"expected":48256,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":155,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":156,"ok":true,"name":"should be equal","operator":"equal","actual":"4SypTkjLsuG3szgzFcRP4Q==;Srikanth","expected":"4SypTkjLsuG3szgzFcRP4Q==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":157,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO smallerHash Making /identity/cb request to pkOther value 4SypTkjLsuG3szgzFcRP4Q==
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 141 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 142 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 143 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 144 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 145 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 146 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO smallerHash Making /identity/rnmine request to pkOther value 4SypTkjLsuG3szgzFcRP4Q==
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 147 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 148 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 149 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":158,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":159,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 150 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 151 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 152 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":160,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":161,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":162,"ok":true,"name":"should be equal","operator":"equal","actual":575424,"expected":575424,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":163,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":164,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"end","test":28}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"teardown","id":29}
I/jxcore-log( 4256): 
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 153 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 154 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 155 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 156 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 157 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 158 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 159 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 160 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 161 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 162 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 163 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 164 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 29 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":29}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"setup","id":30}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 30 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,V/AlarmManager( 1017): sending alarm Alarm{42013b48 type 3 android}
,I/jxcore-log( 4256): {"type":"end","test":30}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"test compareEqualSizeBuffers","id":31}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":1,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":2,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":3,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":4,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"Buffers must be of the same size."},"test":31,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":8,"ok":true,"name":"should be equal","operator":"equal","actual":0,"expected":0,"test":31,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":9,"ok":true,"name":"should be equal","operator":"equal","actual":0,"expected":0,"test":31,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":1,"expected":1,"test":31,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":11,"ok":true,"name":"should be equal","operator":"equal","actual":1,"expected":1,"test":31,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"end","test":31}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"teardown","id":32}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 31 isOK: undefined : test compareEqualSizeBuffers", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 32 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4256): {"type":"end","test":32}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"setup","id":33}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 33 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":33}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"test","name":"Make sure we return 404 before hitting start","id":34}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":34,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"end","test":34}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"teardown","id":35}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 34 isOK: undefined : Make sure we return 404 before hitting start", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 35 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":35}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"setup","id":36}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 36 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":36}
I/jxcore-log( 4256): 
,E/jxcore-log( 4256): (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
E/jxcore-log( 4256): 
,E/jxcore-log( 4256): Trace: 
E/jxcore-log( 4256):     at Console.prototype.trace@console.js:169:13
E/jxcore-log( 4256):     at addListener@events.js:140:7
E/jxcore-log( 4256):     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/pouchdb-all-dbs/index.js:61:3
E/jxcore-log( 4256):     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:138:9
E/jxcore-log( 4256):     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/util.js:26:16
E/jxcore-log( 4256):     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:507:13
E/jxcore-log( 4256):     at module.exports/Promise.prototype._settlePromiseAt@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:581:13
E/jxcore-log( 4256):     at module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/
,E/jxcore-log( 4256): (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
E/jxcore-log( 4256): 
,E/jxcore-log( 4256): Trace: 
E/jxcore-log( 4256):     at Console.prototype.trace@console.js:169:13
E/jxcore-log( 4256):     at addListener@events.js:140:7
E/jxcore-log( 4256):     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/pouchdb-all-dbs/index.js:85:3
E/jxcore-log( 4256):     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:138:9
E/jxcore-log( 4256):     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/util.js:26:16
E/jxcore-log( 4256):     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:507:13
E/jxcore-log( 4256):     at module.exports/Promise.prototype._settlePromiseAt@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:581:13
E/jxcore-log( 4256):     at module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"test","name":"Random path after start, need 404","id":37}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":37,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"end","test":37}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"teardown","id":38}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 37 isOK: undefined : Random path after start, need 404", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 38 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":38}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"setup","id":39}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 39 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":39}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"test","name":"Confirm we go to wrongPeer if our hash is smaller","id":40}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"WrongPeer","expected":"WrongPeer","test":40,"type":"assert"}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 40 isOK: undefined : Confirm we go to wrongPeer if our hash is smaller", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"wrongPeer","expected":"wrongPeer","test":40,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"EVaI/H9Czcc4cEvUv0MRPg==","expected":"EVaI/H9Czcc4cEvUv0MRPg==","test":40,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":40,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"end","test":40}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"teardown","id":41}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 41 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":41}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"setup","id":42}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 42 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":42}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"test","name":"Confirm we go to wrongPeer if our hash is smaller","id":43}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"WrongPeer","expected":"WrongPeer","test":43,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"wrongPeer","expected":"wrongPeer","test":43,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"FPNQxiMHk+GhbdPHJaEn2A==","expected":"FPNQxiMHk+GhbdPHJaEn2A==","test":43,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":43,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"end","test":43}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"teardown","id":44}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 43 isOK: undefined : Confirm we go to wrongPeer if our hash is smaller", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 44 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":44}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"setup","id":45}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 45 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4256): {"type":"end","test":45}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"test","name":"Confirm we get wrongPeer on cb if we give hash other than expected","id":46}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"wrongPeer","expected":"wrongPeer","test":46,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"cx3q+46HHKKGsZcld7h1tw==","expected":"cx3q+46HHKKGsZcld7h1tw==","test":46,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":46,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"end","test":46}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"teardown","id":47}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 46 isOK: undefined : Confirm we get wrongPeer on cb if we give hash other than expected", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 47 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4256): {"type":"end","test":47}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"setup","id":48}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 48 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":48}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"test","name":"Confirm we get Skip Ahead even with a wrong peer on a rnMine request (and we can argue if this is a good choice)","id":49}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"skippedAhead","expected":"skippedAhead","test":49,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"wJwctg6CmLOVCgqubezicQ==","expected":"wJwctg6CmLOVCgqubezicQ==","test":49,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":49,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"end","test":49}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"teardown","id":50}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 49 isOK: undefined : Confirm we get Skip Ahead even with a wrong peer on a rnMine request (and we can argue if this is a good choice)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 50 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,V/AlarmManager( 1017): sending alarm Alarm{4219f150 type 3 android}
,I/jxcore-log( 4256): {"type":"end","test":50}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"setup","id":51}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 51 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":51}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"test","name":"NoIdentityExchange after start & stop","id":52}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"0PN9IUWE/WKp5WgXOdOjhQ==","expected":"0PN9IUWE/WKp5WgXOdOjhQ==","test":52,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":2,"ok":true,"name":{"req":{"method":"post","url":"http://127.0.0.1:47418/identity/cb","data":{"cbValue":"UwacJXlQ+ehNigBz4Pd0OFrdgJNoL9IdSxFI0XYhgEs=","pkMine":"N7J050N719cq0oFUesuuig=="}},"header":{"x-powered-by":"Express","content-type":"application/json; charset=utf-8","content-length":"77","etag":"W/\"4d-DWFxEdlmqfFj0frOeXXdWQ\"","date":"Mon, 23 Nov 2015 12:57:22 GMT","connection":"close"},"status":400,"text":"{\"errorCode\":\"notDoingIdentityExchange\",\"pkOther\":\"0PN9IUWE/WKp5WgXOdOjhQ==\"}"},"operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"0PN9IUWE/WKp5WgXOdOjhQ==","expected":"0PN9IUWE/WKp5WgXOdOjhQ==","test":52,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":5,"ok":true,"name":{"req":{"method":"post","url":"http://127.0.0.1:35823/identity/rnmine","data":{"rnMine":"u2kB5tCOo5K3vexgYS9ddw==","pkOther":"JMr8x7YtzDLVwtel5tkOHQ=="}},"header":{"x-powered-by":"Express","content-type":"application/json; charset=utf-8","content-length":"77","etag":"W/\"4d-DWFxEdlmqfFj0frOeXXdWQ\"","date":"Mon, 23 Nov 2015 12:57:22 GMT","connection":"close"},"status":400,"text":"{\"errorCode\":\"notDoingIdentityExchange\",\"pkOther\":\"0PN9IUWE/WKp5WgXOdOjhQ==\"}"},"operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":"0PN9IUWE/WKp5WgXOdOjhQ==","expected":"0PN9IUWE/WKp5WgXOdOjhQ==","test":52,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":8,"ok":true,"name":{"req":{"method":"post","url":"http://127.0.0.1:52994/identity/cb","data":{"cbValue":"gJUbS3lLC1r9/xaRqzhLqgZWu+zpsMicP9NpmhBSuUQ=","pkMine":"zMDsBMbpHP+wgjBAf0NQkg=="}},"header":{"x-powered-by":"Express","content-type":"application/json; charset=utf-8","content-length":"77","etag":"W/\"4d-DWFxEdlmqfFj0frOeXXdWQ\"","date":"Mon, 23 Nov 2015 12:57:22 GMT","connection":"close"},"status":400,"text":"{\"errorCode\":\"notDoingIdentityExchange\",\"pkOther\":\"0PN9IUWE/WKp5WgXOdOjhQ==\"}"},"operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":9,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":"0PN9IUWE/WKp5WgXOdOjhQ==","expected":"0PN9IUWE/WKp5WgXOdOjhQ==","test":52,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":11,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"end","test":52}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"teardown","id":53}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 52 isOK: undefined : NoIdentityExchange after start & stop", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : [object Object]", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : [object Object]", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : [object Object]", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 53 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":53}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"setup","id":54}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 54 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":54}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"test","name":"cbRequest - bad request bodies","id":55}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 55 isOK: undefined : cbRequest - bad request bodies", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":" ","pkMine":"6cC0HfpBjy2REyNcPHJTZg=="}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":"{@#{$@#{$","pkMine":"TI3rn6oM7aaUKsk2xdrbWw=="}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":"C/1BHdIdcZ6MWe7/v0tW26ru+gbtHI5VYCgytZF+sqSD","pkMine":"j3qYrBXB3i4MSjHHcwEYXA=="}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":"Eg9UrIZdLD/nfFfFkpGRsqutYYUqiVw+zo7ftPqzOQ==","pkMine":"RQ3M793HERubQ1+HsQuyNQ=="}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"xgTW8+v7I003fuI9y38pb4HKv676lef0Ei25pepmY9o=","pkMine":" "}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"JvidXl6D2vixvN8OdUhF5UkRprxQEoAuEraOVnj9oxo=","pkMine":"{@#{$@#{$"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"D4qeynW4GHDC3diqQgcbKMhGxYYBNCOnSyg6GtLkMgg=","pkMine":"NIBYRFReeN7i5T3uXp6I+78="}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"UCOADugFpN2Rf5RwS7NjFb39cH/u7Mwzfl5g9vZX0tM=","pkMine":"1Aw0+6A2Psfp6jaAFaCf"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":" "}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":"{@#{$@#{$"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":"NIBYRFReeN7i5T3uXp6I+78="}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":"1Aw0+6A2Psfp6jaAFaCf"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":" "}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":"{@#{$@#{$"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":"NIBYRFReeN7i5T3uXp6I+78="}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":"1Aw0+6A2Psfp6jaAFaCf"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"C/1BHdIdcZ6MWe7/v0tW26ru+gbtHI5VYCgytZF+sqSD","pkMine":" "}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"C/1BHdIdcZ6MWe7/v0tW26ru+gbtHI5VYCgytZF+sqSD","pkMine":"{@#{$@#{$"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"C/1BHdIdcZ6MWe7/v0tW26ru+gbtHI5VYCgytZF+sqSD","pkMine":"NIBYRFReeN7i5T3uXp6I+78="}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"C/1BHdIdcZ6MWe7/v0tW26ru+gbtHI5VYCgytZF+sqSD","pkMine":"1Aw0+6A2Psfp6jaAFaCf"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"Eg9UrIZdLD/nfFfFkpGRsqutYYUqiVw+zo7ftPqzOQ==","pkMine":" "}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"Eg9UrIZdLD/nfFfFkpGRsqutYYUqiVw+zo7ftPqzOQ==","pkMine":"{@#{$@#{$"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"Eg9UrIZdLD/nfFfFkpGRsqutYYUqiVw+zo7ftPqzOQ==","pkMine":"NIBYRFReeN7i5T3uXp6I+78="}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"Eg9UrIZdLD/nfFfFkpGRsqutYYUqiVw+zo7ftPqzOQ==","pkMine":"1Aw0+6A2Psfp6jaAFaCf"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): INFO largerHash Got a /identity/cb request with a bum pkMine - {}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"OdipwBJjTUTN8vyi3lZ3qw==","expected":"OdipwBJjTUTN8vyi3lZ3qw==","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"OdipwBJjTUTN8vyi3lZ3qw==","expected":"OdipwBJjTUTN8vyi3lZ3qw==","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":"OdipwBJjTUTN8vyi3lZ3qw==","expected":"OdipwBJjTUTN8vyi3lZ3qw==","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":8,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":9,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":"OdipwBJjTUTN8vyi3lZ3qw==","expected":"OdipwBJjTUTN8vyi3lZ3qw==","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":11,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":13,"ok":true,"name":"should be equal","operator":"equal","actual":"OdipwBJjTUTN8vyi3lZ3qw==","expected":"OdipwBJjTUTN8vyi3lZ3qw==","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":14,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":15,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":16,"ok":true,"name":"should be equal","operator":"equal","actual":"OdipwBJjTUTN8vyi3lZ3qw==","expected":"OdipwBJjTUTN8vyi3lZ3qw==","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":17,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":18,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":19,"ok":true,"name":"should be equal","operator":"equal","actual":"OdipwBJjTUTN8vyi3lZ3qw==","expected":"OdipwBJjTUTN8vyi3lZ3qw==","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":20,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":21,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":22,"ok":true,"name":"should be equal","operator":"equal","actual":"OdipwBJjTUTN8vyi3lZ3qw==","expected":"OdipwBJjTUTN8vyi3lZ3qw==","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":23,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":24,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":25,"ok":true,"name":"should be equal","operator":"equal","actual":"OdipwBJjTUTN8vyi3lZ3qw==","expected":"OdipwBJjTUTN8vyi3lZ3qw==","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":26,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":27,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":28,"ok":true,"name":"should be equal","operator":"equal","actual":"OdipwBJjTUTN8vyi3lZ3qw==","expected":"OdipwBJjTUTN8vyi3lZ3qw==","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":29,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":30,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":31,"ok":true,"name":"should be equal","operator":"equal","actual":"OdipwBJjTUTN8vyi3lZ3qw==","expected":"OdipwBJjTUTN8vyi3lZ3qw==","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":32,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":33,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":34,"ok":true,"name":"should be equal","operator":"equal","actual":"OdipwBJjTUTN8vyi3lZ3qw==","expected":"OdipwBJjTUTN8vyi3lZ3qw==","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":35,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":36,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":37,"ok":true,"name":"should be equal","operator":"equal","actual":"OdipwBJjTUTN8vyi3lZ3qw==","expected":"OdipwBJjTUTN8vyi3lZ3qw==","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":38,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":39,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":40,"ok":true,"name":"should be equal","operator":"equal","actual":"OdipwBJjTUTN8vyi3lZ3qw==","expected":"OdipwBJjTUTN8vyi3lZ3qw==","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":41,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":42,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":43,"ok":true,"name":"should be equal","operator":"equal","actual":"OdipwBJjTUTN8vyi3lZ3qw==","expected":"OdipwBJjTUTN8vyi3lZ3qw==","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":44,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":45,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":46,"ok":true,"name":"should be equal","operator":"equal","actual":"OdipwBJjTUTN8vyi3lZ3qw==","expected":"OdipwBJjTUTN8vyi3lZ3qw==","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":47,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":48,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":49,"ok":true,"name":"should be equal","operator":"equal","actual":"OdipwBJjTUTN8vyi3lZ3qw==","expected":"OdipwBJjTUTN8vyi3lZ3qw==","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":50,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":51,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":52,"ok":true,"name":"should be equal","operator":"equal","actual":"OdipwBJjTUTN8vyi3lZ3qw==","expected":"OdipwBJjTUTN8vyi3lZ3qw==","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":53,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":54,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":55,"ok":true,"name":"should be equal","operator":"equal","actual":"OdipwBJjTUTN8vyi3lZ3qw==","expected":"OdipwBJjTUTN8vyi3lZ3qw==","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":56,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":57,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":58,"ok":true,"name":"should be equal","operator":"equal","actual":"OdipwBJjTUTN8vyi3lZ3qw==","expected":"OdipwBJjTUTN8vyi3lZ3qw==","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":59,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":60,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":61,"ok":true,"name":"should be equal","operator":"equal","actual":"OdipwBJjTUTN8vyi3lZ3qw==","expected":"OdipwBJjTUTN8vyi3lZ3qw==","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":62,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":63,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":64,"ok":true,"name":"should be equal","operator":"equal","actual":"OdipwBJjTUTN8vyi3lZ3qw==","expected":"OdipwBJjTUTN8vyi3lZ3qw==","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":65,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":66,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":67,"ok":true,"name":"should be equal","operator":"equal","actual":"OdipwBJjTUTN8vyi3lZ3qw==","expected":"OdipwBJjTUTN8vyi3lZ3qw==","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":68,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":69,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":70,"ok":true,"name":"should be equal","operator":"equal","actual":"OdipwBJjTUTN8vyi3lZ3qw==","expected":"OdipwBJjTUTN8vyi3lZ3qw==","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":71,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":72,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":73,"ok":true,"name":"should be equal","operator":"equal","actual":"OdipwBJjTUTN8vyi3lZ3qw==","expected":"OdipwBJjTUTN8vyi3lZ3qw==","test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":74,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"end","test":55}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"teardown","id":56}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 13 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 14 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 15 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 16 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 17 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 18 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 19 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 20 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 21 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 22 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 23 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 24 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 25 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 26 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 27 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 28 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 29 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 30 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 31 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 32 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 33 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 34 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 35 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 36 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 37 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 38 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 39 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 40 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 41 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 42 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 43 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 44 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 45 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 46 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 47 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 48 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 49 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 50 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 51 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 52 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 53 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 54 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 55 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 56 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 57 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 58 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 59 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 60 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 61 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 62 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 63 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 64 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 65 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 66 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 67 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 68 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 69 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 70 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 71 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 72 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 73 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 74 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 56 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":56}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"setup","id":57}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 57 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4256): {"type":"end","test":57}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"test","name":"re-do cb (to check we can reset) and make sure rnOther changes","id":58}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":"L4bbHt3VAD+WOFxI4jtQSw==","expected":true,"test":58,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"6km6+bGMOXyjFh5fH8GuIA==","expected":"6km6+bGMOXyjFh5fH8GuIA==","test":58,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":2,"ok":true,"name":"should not be equal","operator":"notEqual","actual":"L4bbHt3VAD+WOFxI4jtQSw==","test":58,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"6km6+bGMOXyjFh5fH8GuIA==","expected":"6km6+bGMOXyjFh5fH8GuIA==","test":58,"type":"assert"}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 58 isOK: undefined : re-do cb (to check we can reset) and make sure rnOther changes", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"6km6+bGMOXyjFh5fH8GuIA==","expected":"6km6+bGMOXyjFh5fH8GuIA==","test":58,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"end","test":58}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"teardown","id":59}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 59 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":59}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"setup","id":60}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 60 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4256): {"type":"end","test":60}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"test","name":"good cb followed by good rnmine then repeat cb and finish up, make sure we have new rnOther","id":61}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":"GTqxRULhHLqgtdgDFMFT6w==","expected":true,"test":61,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":1,"ok":true,"name":"should not be equal","operator":"notEqual","actual":"DnlCtv8ntBDW3oEGw9C7uA==","test":61,"type":"assert"}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 61 isOK: undefined : good cb followed by good rnmine then repeat cb and finish up, make sure we have new rnOther", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":[14,121,66,182,255,39,180,16,214,222,129,6,195,208,187,184],"expected":true,"test":61,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":158720,"expected":158720,"test":61,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"end","test":61}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"teardown","id":62}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 62 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":62}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"setup","id":63}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 63 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":63}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"test","name":"do a successful cb and successful rnmine and then repeat the rnmine","id":64}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":"rQKBo/yJiCozQICiUe2aJA==","expected":true,"test":64,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":1,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":[173,2,129,163,252,137,136,42,51,64,128,162,81,237,154,36],"expected":true,"test":64,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":380096,"expected":380096,"test":64,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"end","test":64}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"teardown","id":65}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 64 isOK: undefined : do a successful cb and successful rnmine and then repeat the rnmine", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 65 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"end","test":65}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"setup","id":66}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 66 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,V/AlarmManager( 1017): sending alarm Alarm{420d5fd0 type 3 android}
,I/jxcore-log( 4256): {"type":"end","test":66}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4256): {"type":"test","name":"do a rnmine without a cb","id":67}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"skippedAhead","expected":"skippedAhead","test":67,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"4TX/C2Kkn7iIV6Av4/VZgw==","expected":"4TX/C2Kkn7iIV6Av4/VZgw==","test":67,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":67,"type":"assert"}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"end","test":67}
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): {"type":"test","name":"teardown","id":68}
I/jxcore-log( 4256): 
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 67 isOK: undefined : do a rnmine without a cb", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 68 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,V/AlarmManager( 1017): sending alarm Alarm{428050a0 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{443c9648 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{4292df48 type 2 android}
,D/ConnectivityService( 1017): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1017): sending alarm Alarm{4292e020 type 1 com.android.deskclock}
,D/ConnectivityService( 1017): Done.
,D/ConnectivityService( 1017): Setting timer for 720seconds
,I/ActivityManager( 1017): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4931 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1017): Killing 4430:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager( 1017): sending alarm Alarm{427d35b8 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{4244c560 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42855c68 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{43e1e988 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{428d42b0 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42190b20 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{4291d598 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{421801f0 type 2 com.google.android.gms}
,D/UdcCache:FPQuery( 1392): Bootstrapping UDC settings cache for all accounts
D/dalvikvm( 1351): GC_CONCURRENT freed 1617K, 36% free 11068K/17224K, paused 4ms+7ms, total 77ms
,D/dalvikvm( 1351): WAIT_FOR_CONCURRENT_GC blocked 22ms
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService( 1017): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/ModemStatsDSDetect( 1295): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1080): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1295): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1295): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1080): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,V/AlarmManager( 1017): sending alarm Alarm{429284f8 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{43a66f70 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42864d30 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{42167bc8 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{42dc7170 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{43d87448 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42262058 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42833348 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{429aa720 type 2 android}
,D/ConnectivityService( 1017): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1017): sending alarm Alarm{429aa7f8 type 0 com.google.android.gms}
,D/ConnectivityService( 1017): Done.
,D/ConnectivityService( 1017): Setting timer for 720seconds
,I/ProcessStatsService( 1017): Prepared write state in 17ms
,V/AlarmManager( 1017): sending alarm Alarm{429add28 type 1 com.android.deskclock}
,I/ProcessStatsService( 1017): Prepared write state in 17ms
,I/EventLogService( 1392): Aggregate from 1448283007867 (log), 1448282211081 (data)
I/ProcessStatsService( 1017): Pruning old procstats: /data/system/procstats/state-2015-11-22-20-29-00.bin
,V/AlarmManager( 1017): sending alarm Alarm{42800e08 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42800ee0 type 3 com.google.android.gms}
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1017): sending alarm Alarm{42800d30 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{443cdd20 type 3 android}
,I/jxcore-log( 4256): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
,D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1017): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@4218bef0 mBinding = false
,W/Settings( 1254): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/BluetoothManagerService( 1017): Message: 2
,D/BluetoothManagerService( 1017): Sending off request.
,D/BluetoothAdapterState( 1805): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1805): Setting state to 13
I/BluetoothAdapterState( 1805): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 1805): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterProperties( 1805): onBluetoothDisable()
,I/BluetoothAdapterState( 1805): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,I/BluetoothAdapterProperties( 1805): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothAdapterProperties( 1805): Scan Mode:21
,D/BluetoothAdapterState( 1805): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 1805): bta_jv_rfcomm_stop_server
,E/BtOppRfcommListener( 1805): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 1805): bta_jv_rfcomm_stop_server
E/bt-btif ( 1805): bta_jv_rfcomm_stop_server
,E/bt-btif ( 1805): bta_jv_rfcomm_stop_server
,V/BluetoothFtpService:RfcommSocketAcceptThread( 1805): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 1805): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,W/Settings( 1254): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/bt-l2cap( 1805): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1805): L2CAP - PSM: 0x0017 not found for deregistration
,D/btif_config_util( 1805): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
,D/BluetoothManagerService( 1017): Message: 60
,D/BluetoothManagerService( 1017): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,D/BluetoothManagerService( 1017): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 1805): onReceive
D/BluetoothMapService( 1805): STATE_TURNING_OFF removeTimeoutMsg:false
,D/BluetoothMapService( 1805): MAP Service closeService in
,I/ActivityManager( 1017): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=5008 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/WifiStateMachine( 1017): handleMessage: E msg.what=131084
D/WifiStateMachine( 1017): processMsg: ConnectedState
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
W/Settings( 1254): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiStateMachine( 1017): transitionTo: destState=WaitForP2pDisableState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
D/WifiStateMachine( 1017): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1017): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1017): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1017): setSuspendOptimizationsNative: 1 true
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/Settings( 1254): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiP2pService( 1017): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
D/CommandListener(  271): Clearing all IP addresses on wlan0
D/TCMD    (  463): NL - Read 60 bytes from update socket.
D/TCMD    (  463): NL - ignore NL message, type = 21
D/TCMD    (  463): Listening for incoming client connection request
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/WifiStateMachine( 1017): addressRemoved: 192.168.1.123/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1017): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1017): connected time updated 1942747
,D/WifiStateMachine( 1017): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1017): invokeExitMethods: ConnectModeState
,D/WifiStateMachine( 1017): invokeExitMethods: DriverStartedState
,I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Checkin ( 1017): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/ConnectivityService( 1017): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1017): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
E/WifiStateMachine( 1017): Unexpected BatchedScanResults :OK
,D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/ConnectivityService( 1017): Attempting to switch to mobile
D/ConnectivityService( 1017): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1017): Attempting to switch to ETHERNET
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
D/WifiStateMachine( 1017): invokeEnterMethods: WaitForP2pDisableState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131216
D/WifiStateMachine( 1017): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiStateMachine( 1017): processMsg: DefaultState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131216
D/WifiStateMachine( 1017): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiStateMachine( 1017): processMsg: DefaultState
D/WifiP2pService( 1017): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1017): handleMessage: X
D/WifiP2pService( 1017): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiP2pService( 1017): P2pDisablingState
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
D/WifiP2pService( 1017): P2pDisablingState{ when=-3ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): p2p socket connection lost
,D/WifiP2pService( 1017): P2pDisabledState
D/WifiStateMachine( 1017): handleMessage: E msg.what=131205
D/WifiStateMachine( 1017): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1017): transitionTo: destState=SupplicantStoppingState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1017): invokeExitMethods: WaitForP2pDisableState
D/WifiStateMachine( 1017): invokeExitMethods: SupplicantStartedState
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/WifiStateMachine( 1017): invokeEnterMethods: SupplicantStoppingState
D/WifiStateMachine( 1017): Stopping DHCP and clearing IP
D/WifiStateMachine( 1017): setSuspendOptimizationsNative: 1 true
I/SBar.NetworkController( 1080): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1080): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1080): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
I/BtOppRfcommListener( 1805): stopping Accept Thread
I/BtOppRfcommListener( 1805): BluetoothSocket listen thread finished
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/WifiP2pService( 1017): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): {"id":0,"ok":false,"name":"Coordinator server got disconnected","operator":"fail","error":{},"test":68,"type":"assert"}
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/ConnectivityService( 1017): resetConnections(wlan0, 3)
D/NetUtils( 1017): android_net_utils_resetConnections in env=0x6121e218 clazz=0xb6200001 iface=wlan0 mask=0x3
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
V/NativeCrypto( 1351): Read error: ssl=0x62a2b290: I/O error during system call, Connection timed out
V/NativeCrypto( 1351): SSL shutdown failed: ssl=0x62a2b290: I/O error during system call, Broken pipe
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/CommandListener(  271): Clearing all IP addresses on wlan0
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiStateMachine( 1017): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/WifiStateMachine( 1017): stopping supplicant
D/Checkin ( 1017): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
D/WifiStateMachine( 1017): setWifiState: disabling
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiStateMachine( 1017): handleMessage: X
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/SBar.NetworkController( 1080): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/bt_hwcfg( 1805): hw_epilog_process
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
W/bt-btif ( 1805): ag scb idx 1 not allocated
E/bt-btif ( 1805): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1805): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1805): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1805): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1805): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1805): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1805): L2CAP - PSM: 0x0017 not found for deregistration
W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
W/XTWiFiOS( 1269): Active network info is not available
E/XTCC-3.0.0.2(  598): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  598): [WwanPosMgr] handleConnectivtyStatusChange failed
I/SBar.NetworkController( 1080): refreshSignalCluster: wifi: mWifiConnected=false Wifi=(none) Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=false
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
,D/ConnectivityService( 1017): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
E/XTCC-3.0.0.2(  598): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  598): [CSMgr] handleConnectivtyStatusChange failed
I/bt_hwcfg( 1805): hw_epilog_cback Opcode:0x0C03 Status: 0
I/bt_hci_bdroid( 1805): bt_hc_worker_thread exiting
D/bt_userial_mct( 1805): userial_close
I/bt_userial_mct( 1805): exiting userial_read_thread
,D/bt_userial_mct( 1805): Leaving userial_evt_read_thread()
D/ConnectivityService( 1017): Attempting to switch to mobile
I/ModemStatsDSDetect( 1295): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityService( 1017): Attempting to switch to BLUETOOTH_TETHER
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,D/ConnectivityService( 1017): Attempting to switch to ETHERNET
I/ModemStatsDSDetect( 1295): INET_CONDITION=0 ,activeNet=null
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
,I/ModemStatsDSDetect( 1295): onReceive() - done, currentInetCondition=0
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
W/ContextImpl( 5008): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): Message: 20
D/BluetoothPbapService( 1805): action: android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothManagerService( 1017): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@421e66e0:true
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/wpa_supplicant( 1155): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
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
D/TCMD    (  463): NL - Read 1000 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/TCMD    (  463): NL - Read 68 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/TCMD    (  463): NL - Read 68 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  273): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/jxcore-log( 4256): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 4256): 
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/Tethering( 1017): InitialState.processMessage what=4
D/WifiStateMachine( 1017): handleMessage: E msg.what=147460
D/WifiStateMachine( 1017): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1017): processMsg: DefaultState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiStateMachine( 1017): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1017): processMsg: DefaultState
D/Tethering( 1017): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/WifiStateMachine( 1017): handleMessage: X
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
D/Tethering( 1017): sendTetherStateChangedBroadcast 0, 0, 0
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiStateMachine( 1017): handleMessage: E msg.what=131101
D/WifiStateMachine( 1017): processMsg: SupplicantStoppingState
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
D/WifiStateMachine( 1017): processMsg: DefaultState
D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=false
D/WifiStateMachine( 1017): handleMessage: X
,D/ConnectivityService( 1017): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1295): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1295): INET_CONDITION=0 ,activeNet=null
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/ModemStatsDSDetect( 1295): onReceive() - done, currentInetCondition=0
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): Message: 30
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
W/ContextImpl( 5008): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): Message: 30
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
W/ContextImpl( 5008): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
D/LocalBluetoothProfileManager( 5008): Adding local MAP profile
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
D/BluetoothMap( 5008): Create BluetoothMap proxy object
D/BluetoothManagerService( 1017): Message: 30
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
W/ContextImpl( 5008): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
D/BluetoothManagerService( 1017): Message: 30
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
W/ContextImpl( 5008): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 5008): LocalBluetoothProfileManager construction complete
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/wpa_supplicant( 1155): eap_proxy Deinitialzed
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 0
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
D/DockEventReceiver( 5008): finishStartingService: stopping service
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BTSNOOP-DISP( 1805): btsnoop_close
I/bt_vendor( 1805): cleanup
I/bt_hwcfg( 1805): Starting hciattach daemon
I/bt_hwcfg( 1805): try to set false
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
I/GKI_LINUX( 1805): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 1805): GKI_exit_task: GKI_exit_task 0 done
,I/GKI_LINUX( 1805): GKI_destroy_task: GKI_shutdown(): task [BTU] terminated
D/WifiService( 1017): New client listening to asynchronous messages
D/BluetoothAdapterState( 1805): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
D/HeadsetService( 1805): Received stop request...Stopping profile...
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/TCMD    (  463): NL - Read 1000 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/wpa_supplicant( 1155): wlan0: CTRL-EVENT-TERMINATING 
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
D/BluetoothHeadset( 1243): Proxy object disconnected
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  273): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  273):  Wpa Supplicant Exiting !!
D/MDMCTBK (  273): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  273): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  273): wifi_close_sockets: Exit
D/BluetoothHeadset( 1017): Proxy object disconnected
D/A2dpService( 1805): Received stop request...Stopping profile...
D/WifiStateMachine( 1017): handleMessage: E msg.what=147458
D/WifiStateMachine( 1017): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1017): Supplicant connection lost
D/A2dpStateMachine( 1805): Exit Disconnected: -1
D/BluetoothHeadset( 1243): Proxy object disconnected
D/BluetoothHeadset( 1243): Proxy object disconnected
D/BluetoothA2dp( 1017): Proxy object disconnected
D/BluetoothAdapterService( 1805): Profile still running: com.android.bluetooth.hdp.HealthService
D/HidService( 1805): Received stop request...Stopping profile...
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
W/BluetoothHeadsetServiceJni( 1805): Cleaning up Bluetooth Handsfree Interface...
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
W/BluetoothHeadsetServiceJni( 1805): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 1805): Profile still running: com.android.bluetooth.hdp.HealthService
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
D/HealthService( 1805): Received stop request...Stopping profile...
D/BluetoothAdapterState( 1805): Stopping profile services that were post enabled
I/jxcore-log( 4256): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/GKI_LINUX( 1805): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 1805): GKI_exit_task: GKI_exit_task 2 done
I/GKI_LINUX( 1805): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
D/PanService( 1805): Received stop request...Stopping profile...
D/BluetoothTethering( 1017): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering( 1017): attempted to stop reverse tether with nothing tethered
D/BluetoothTethering( 1017): Disconnect CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@4227c7a8
D/BluetoothTethering( 1017): got CMD_CHANNEL_DISCONNECTED
D/BluetoothPan( 1017): BluetoothPAN Proxy object disconnected
D/BluetoothAdapterService( 1805): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 1805): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 1805): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 1805): Cleaning up Bluetooth GID callback object
D/BtGatt.DebugUtils( 1805): handleDebugAction() action=null
D/BtGatt.GattService( 1805): Received stop request...Stopping profile...
D/BtGatt.GattService( 1805): stop()
D/BluetoothAdapterService( 1805): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/BluetoothMapService( 1805): Received stop request...Stopping profile...
D/BluetoothMapService( 1805): stop()
D/BluetoothMapService( 1805): MAP Service closeService in
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
W/BluetoothHealthServiceJni( 1805): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 1805): Cleaning up Bluetooth Health object
D/BluetoothAdapterService( 1805): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 1805): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 1805): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService( 1805): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/BluetoothMapService( 1805): cleanup()
D/BluetoothMapService( 1805): MAP Service closeService in
D/BluetoothAdapterState( 1805): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1805): Setting state to 10
I/BluetoothAdapterState( 1805): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 1805): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1017): Message: 60
D/BluetoothManagerService( 1017): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1017): Broadcasting onBluetoothStateChange(false) to 10 receivers.
I/BluetoothAdapterState( 1805): Entering OffState
D/BluetoothHeadset( 1243): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
D/BluetoothHeadset( 1243): onBluetoothStateChange: up=false
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/BluetoothPan( 1017): onBluetoothStateChange on: false
D/BluetoothHeadset( 1243): onBluetoothStateChange: up=false
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothInputDevice( 5008): Proxy object connected
D/HidProfile( 5008): Bluetooth service connected
D/BluetoothHeadset( 1017): onBluetoothStateChange: up=false
D/BluetoothPan( 5008): BluetoothPAN Proxy object connected
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
D/PanProfile( 5008): Bluetooth service connected
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothMap( 5008): Proxy object connected
D/MapProfile( 5008): Bluetooth service connected
D/BluetoothMap( 5008): getConnectedDevices()
D/BluetoothA2dp( 1017): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
D/BluetoothPbap( 5008): onBluetoothStateChange: up=false
D/BluetoothMap( 5008): Bluetooth is Not enabled
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/BluetoothInputDevice( 5008): onBluetoothStateChange: up=false
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothMap( 5008): onBluetoothStateChange: up=false
D/BluetoothPan( 5008): BluetoothPAN Proxy object disconnected
V/BluetoothFtpReceiver( 1805): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
D/PanProfile( 5008): Bluetooth service disconnected
I/ActivityManager( 1017): Killing 4460:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothPan( 5008): onBluetoothStateChange on: false
W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/AuthorizationBluetoothService( 1351): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
D/BluetoothManagerService( 1017): Calling onBluetoothServiceDown callbacks
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): Broadcasting onBluetoothServiceDown() to 9 receivers.
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@4218bef0 mBinding = false
D/BluetoothManagerService( 1017): Sending unbind request.
D/BluetoothAdapterService( 1805): Cleaning up adapter native....
I/GKI_LINUX( 1805): gki_task_entry: gki_task task_id=1 [BTIF] terminating
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/GKI_LINUX( 1805): GKI_exit_task: GKI_exit_task 1 done
I/GKI_LINUX( 1805): GKI_destroy_task: GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 1805): cleanupNative: return from cleanup
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
D/BluetoothAdapterService( 1805): Done cleaning up adapter native....
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
D/BluetoothAdapterService(1107195200)( 1805): ****onDestroy()********
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): Bluetooth State Change Intent: 13 -> 10
D/BtGatt.GattService( 1805): cleanup()
W/bt-btif ( 1805): GATTC Module not enabled/already disabled
W/bt-btif ( 1805): GATTS Module not enabled/already disabled
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
D/BluetoothAdapter( 1213): 1111261848: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1213): 1111261848: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1080): 1108662040: getState() :  mService = null. Returning STATE_OFF
W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.sendDeviceAttachIntent:820 com.motorola.authentication.MotAuthenticationService.access$1300:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:575 
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.handleKeepDeviceUnlockRequest:732 com.motorola.authentication.MotAuthenticationService.access$1500:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:563 
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
,W/ContextImpl( 5008): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/DockEventReceiver( 5008): finishStartingService: stopping service
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapter( 5008): 1107218576: getState() :  mService = null. Returning STATE_OFF
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
V/BluetoothFtpReceiver( 1805): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 1805): BluetoothFtpReceiver Stop Service
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
D/AuthorizationBluetoothService( 1351): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/BluetoothFtpService( 1805): Ftp Service onDestroy
V/BluetoothFtpService( 1805): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 1805): Shutdown
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
,I/ActivityManager( 1017): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.ConnectedUnlockReceiver: pid=5044 uid=10016 gids={50016, 3002}
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/ActivityManager( 1017): Killing 4566:com.google.android.talk/u0a70 (adj 15): empty #9
,D/WifiStateMachine( 1017): setWifiState: disabled
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/WifiStateMachine( 1017): transitionTo: destState=InitialState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1017): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
D/WifiStateMachine( 1017): invokeEnterMethods: InitialState
W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
W/XTWiFiOS( 1269): Active network info is not available
E/XTCC-3.0.0.2(  598): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  598): [WwanPosMgr] handleConnectivtyStatusChange failed
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
W/Settings( 1213): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
E/XTCC-3.0.0.2(  598): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  598): [CSMgr] handleConnectivtyStatusChange failed
I/rmt_storage(  436): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8acb1d0
I/rmt_storage(  436): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/rmt_storage(  436): wakelock acquired: 1, error no: 42
I/rmt_storage(  436): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1196642584)
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
,D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
,D/dalvikvm( 1017): GC_EXPLICIT freed 1990K, 65% free 18030K/50356K, paused 4ms+13ms, total 133ms
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/SBar.NetworkController( 1080): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
D/BluetoothAdapter( 5008): 1107218576: getState() :  mService = null. Returning STATE_OFF
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/Checkin ( 5044): publish the event [tag = DEVICE_AUTH_STATS_L2 event name = DEVAUTH_CONNECT]
,D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
,I/ActivityManager( 1017): Killing 4598:android.process.acore/u0a10 (adj 15): empty #9
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/rmt_storage(  436): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  436): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  436): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1196642584) wakelock released: 1, error no: 0
I/rmt_storage(  436): 
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
,D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,I/rmt_storage(  436): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb8acb1d0
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/jxcore-log( 4256): The client has disconnected!
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Turning radios to false
I/jxcore-log( 4256): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 4256): toggleBluetooth - 
I/jxcore-log( 4256): 
D/WifiService( 1017): setWifiEnabled: false pid=4256, uid=10398
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4256): toggleWiFi
I/jxcore-log( 4256): 
I/chromium( 4256): [INFO:CONSOLE(63)] "logCallback 0 isOK: false : Coordinator server got disconnected", source: file:///android_asset/www/js/thali_main.js (63)
,D/Checkin ( 2303): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2303): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/TCMD    (  463): NL - Read 444 bytes from update socket.
D/TCMD    (  463): NL - ignore NL message, type = 17
D/TCMD    (  463): Listening for incoming client connection request
,D/NetlinkEvent(  271): Unexpected netlink message. type=0x11
W/Netd    (  271): No subsystem found in netlink event
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
,D/TCMD    (  463): NL - Read 1000 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
,D/TCMD    (  463): Listening for incoming client connection request
,D/NetlinkEvent(  271): Unexpected netlink message. type=0x11
W/Netd    (  271): No subsystem found in netlink event
D/TCMD    (  463): NL - Read 444 bytes from update socket.
D/TCMD    (  463): NL - ignore NL message, type = 17
D/TCMD    (  463): Listening for incoming client connection request
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
,D/Checkin ( 2303): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2303): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/Checkin ( 2303): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=196614
D/WifiStateMachine( 1017): processMsg: InitialState
D/WifiStateMachine( 1017): processMsg: DefaultState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131208
,D/WifiStateMachine( 1017): processMsg: InitialState
D/WifiStateMachine( 1017): processMsg: DefaultState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131208
D/WifiStateMachine( 1017): processMsg: InitialState
,D/WifiStateMachine( 1017): processMsg: DefaultState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131208
D/WifiStateMachine( 1017): processMsg: InitialState
,D/WifiStateMachine( 1017): processMsg: DefaultState
,D/WifiStateMachine( 1017): handleMessage: X
,D/Checkin ( 2303): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/MDMCTBK (  273): NetlinkHandler, wifiStateChanged 0
I/MDMCTBK (  273): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
,I/MDMCTBK (  273): checkDefaultInst, pid match
,I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,D/Tethering( 1017): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1017): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1080): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/ConnectivityService( 1017): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1080): updateConnectivity: NetworkInfo: null, inetCondition= 0
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1269): Active network info is not available
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/PollingManager( 1559): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TelephonyProvider( 1243): Column apn id key is 'apn_id'
,D/Tethering( 1017): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1080): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1080): updateConnectivity: NetworkInfo: null, inetCondition= 0
,D/CaptivePortalTracker( 1017): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1269): Active network info is not available
,E/ActivityThread( 1559): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1559): Registering with Alarm Manager to restart CCE
D/TelephonyProvider( 1243): Column apn id key is 'apn_id'
D/PollingManager( 1559): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/OtaApp  ( 1559): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1559): [debug] > CusSM.onRadioDown
,D/PollingManager( 1559): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1559): Failed to find provider info for com.motorola.blur.setupprovider
I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1243): Column apn id key is 'apn_id'
,I/ActivityManager( 1017): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=5085 uid=10030 gids={50030, 3003, 1028, 1015}
,D/TelephonyProvider( 1243): Column apn id key is 'apn_id'
,V/MmsConfig( 5085): mnc/mcc: 
V/MmsConfig( 5085): tag: bool value: enabledMMS - true
V/MmsConfig( 5085): tag: int value: maxMessageSize - 307200
,V/MmsConfig( 5085): tag: int value: maxImageHeight - 1944
V/MmsConfig( 5085): tag: int value: maxImageWidth - 2592
V/MmsConfig( 5085): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 5085): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 5085): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 5085): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 5085): tag: int value: recipientLimit - 20
,V/MmsConfig( 5085): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 5085): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 5085): tag: bool value: enableSlideDuration - true
V/MmsConfig( 5085): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 5085): tag: int value: maxSubjectLength - 80
V/MmsConfig( 5085): tag: bool value: smsForceShowEncodingMenu - true
,V/MmsConfig( 5085): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 5085): tag: bool value: enableGroupMms - false
,E/MmsConfig( 5085): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1017): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5104 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1017): Killing 4617:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 5104): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5104): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 5104): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 5104): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1017): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5117 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1017): Killing 3677:com.google.android.apps.plus/u0a90 (adj 15): empty #9
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1017): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5131 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1017): Killing 4636:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 5131): Binding Chromium to main looper Looper (main, tid 1) {41fdddc8}
,I/LibraryLoader( 5131): Expected native library version number "",actual native library version number ""
,I/chromium( 5131): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5131): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 5131): BLUETOOTH permission is missing!
,I/Adreno-EGL( 5131): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5131): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5131): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5131): Local Branch: 
I/Adreno-EGL( 5131): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5131): Local Patches: NONE
I/Adreno-EGL( 5131): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 5131): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
W/GAV2    ( 5131): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
E/cutils  (  261): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
W/Vold    (  261): Returning OperationFailed - no handler for errno 30
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
W/ContextImpl( 5131): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): ,
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
,I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/NSApplication( 5131): Starting up...
,I/ActivityManager( 1017): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5170 uid=10090 gids={50090, 3003, 3002, 1028, 1015}
,I/ActivityManager( 1017): Killing 4931:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  276): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 23ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
,I/ImageResourceManager( 5170): ImageResourceManager: uninitalized
I/ActivityManager( 1017): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=5188 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/iu.Environment( 5170): update battery state; isPlugged? true*
,I/iu.Environment( 5170): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,I/iu.Environment( 5170): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
I/ActivityManager( 1017): Killing 5044:com.motorola.deviceauthenticator/u0a16 (adj 15): empty #9
I/ActivityManager( 1017): Killing 1805:com.android.bluetooth/1002 (adj 15): empty #10
W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.Environment( 1392): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1392): num queued entries: 0
,I/iu.UploadsManager( 1392): num updated entries: 0
,I/iu.SyncManager( 1392): NEXT; no task
,D/DEBUG   ( 1559): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1559): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1559): bindWebServices(): registering our AIDL callback...
D/EmailService.MarketingOptInSetter( 1559): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1559): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1559): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1559): onServiceConnected()
D/GetNotificationsWS( 1559): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1559): unbindWebServices(): un-registering our AIDL callback...
,D/MobileConnectivityChangeReceiver( 5104): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5104): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 5170): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,D/dalvikvm( 5170): GC_FOR_ALLOC freed 410K, 5% free 16405K/17224K, paused 14ms, total 14ms
,I/dalvikvm-heap( 5170): Grow heap (frag case) to 19.790MB for 1821008-byte allocation
,I/iu.UploadsManager( 5170): #reloadSettings(); account: null; pageID: none; IU: disabled; IS: disabled; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,I/iu.UploadsManager( 5170): End new media; added: 0, uploading: 0, time: 30 ms
,I/iu.FingerprintManager( 5170): Start processing all media
,I/iu.FingerprintManager( 5170): Start processing media store URI: content://media/external/images/media
,D/dalvikvm( 5170): GC_FOR_ALLOC freed 23K, 5% free 18193K/19004K, paused 11ms, total 11ms
,I/iu.FingerprintManager( 5170): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 5170): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 5170): Start processing media store URI: content://media/phoneStorage/video/media
I/iu.FingerprintManager( 5170): Finished generating fingerprints; 0.031 seconds
,I/iu.FingerprintManager( 5170):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/ContactLocale( 5188): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/WifiP2pService( 1017): P2pDisabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): DefaultState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1017): handleMessage: E msg.what=131089
,D/WifiStateMachine( 1017): processMsg: InitialState
D/WifiStateMachine( 1017): processMsg: DefaultState
,D/WifiStateMachine( 1017): handleMessage: X
,V/AlarmManager( 1017): sending alarm Alarm{428ce9a0 type 2 com.android.keyguard}
,I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
,I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 
I/jxcore-log( 4256): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4256): 

```
