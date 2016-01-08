#### Test 5497026140aeaf4_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4049): 
D/AndroidRuntime( 4049): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4049): CheckJNI is OFF
D/dalvikvm( 4049): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4049): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4049): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4049): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4049): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4049): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4049): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4049): failed to load memtrack module: -2
D/AndroidRuntime( 4049): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1022): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4049
W/WindowManager( 1022): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1022): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4065 uid=10530 gids={50530, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4049): Shutting down VM
D/dalvikvm( 4049): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+1ms, total 3ms
W/ContextImpl( 1299): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1299): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4065): Binding Chromium to main looper Looper (main, tid 1) {4236b810}
I/LibraryLoader( 4065): Expected native library version number "",actual native library version number ""
I/chromium( 4065): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4065): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1022): Message: 20
D/BluetoothManagerService( 1022): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4265b6a0:true
I/Adreno-EGL( 4065): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4065): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4065): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4065): Local Branch: 
I/Adreno-EGL( 4065): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4065): Local Patches: NONE
I/Adreno-EGL( 4065): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4065): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4065): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4065): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4065): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4065): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4065): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4065): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4065): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4065): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4065): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4065): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4065): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4065): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4065): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4065): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4065): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4065): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4065): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4065): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4065): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4065): Enabling debug mode 0
,W/AwContents( 4065): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4065): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1022): Displayed com.test.thalitest/.MainActivity,cp,ca,400
I/ActivityManager( 1022): Displayed com.test.thalitest/.MainActivity: +377ms (total +401ms)
,D/JsMessageQueue( 4065): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4065): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42370150
,D/dalvikvm( 4065): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42370150
,D/jxcore_app_log( 4065): JniHelper::setJavaVM(0x41a8af78), pthread_self() = 1614154976
,D/JX-Cordova( 4065): jxcore cordova android initializing
,D/dalvikvm( 4065): GC_CONCURRENT freed 2780K, 17% free 14397K/17224K, paused 3ms+2ms, total 53ms
,D/dalvikvm( 4065): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 4065): GC_FOR_ALLOC freed 111K, 17% free 14394K/17224K, paused 24ms, total 24ms
,D/dalvikvm( 4065): GC_FOR_ALLOC freed 125K, 17% free 14415K/17224K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4065): Grow heap (frag case) to 16.201MB for 95956-byte allocation
,D/dalvikvm( 4065): GC_FOR_ALLOC freed 178K, 17% free 14449K/17320K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4065): Grow heap (frag case) to 16.280MB for 143930-byte allocation
,D/dalvikvm( 4065): GC_FOR_ALLOC freed 251K, 17% free 14496K/17464K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4065): Grow heap (frag case) to 16.395MB for 215890-byte allocation
,D/dalvikvm( 4065): GC_FOR_ALLOC freed 366K, 18% free 14570K/17676K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4065): Grow heap (frag case) to 16.570MB for 323830-byte allocation
,D/dalvikvm( 4065): GC_FOR_ALLOC freed 564K, 19% free 14691K/17996K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4065): Grow heap (frag case) to 16.842MB for 485740-byte allocation
,D/dalvikvm( 4065): GC_FOR_ALLOC freed 860K, 20% free 14867K/18472K, paused 26ms, total 26ms
,D/dalvikvm( 4065): GC_FOR_ALLOC freed 1278K, 19% free 15122K/18472K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4065): Grow heap (frag case) to 17.841MB for 1092904-byte allocation
,V/AlarmManager( 1022): sending alarm Alarm{4255a198 type 3 android}
,D/dalvikvm( 4065): GC_CONCURRENT freed 1767K, 21% free 15506K/19540K, paused 1ms+5ms, total 34ms
,D/dalvikvm( 4065): GC_FOR_ALLOC freed 254K, 21% free 15465K/19540K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4065): Grow heap (frag case) to 18.698MB for 1639352-byte allocation
,D/dalvikvm( 4065): GC_CONCURRENT freed 1738K, 25% free 16018K/21144K, paused 3ms+3ms, total 32ms
,D/dalvikvm( 4065): GC_FOR_ALLOC freed 1269K, 24% free 16076K/21144K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4065): Grow heap (frag case) to 20.077MB for 2459024-byte allocation
,D/dalvikvm( 4065): GC_CONCURRENT freed 1764K, 29% free 16845K/23548K, paused 5ms+4ms, total 37ms
,D/dalvikvm( 4065): GC_CONCURRENT freed 2430K, 28% free 17030K/23548K, paused 3ms+6ms, total 42ms
,D/dalvikvm( 4065): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 4065): GC_FOR_ALLOC freed 626K, 29% free 16866K/23548K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4065): Grow heap (frag case) to 22.021MB for 3688532-byte allocation
,D/dalvikvm( 4065): GC_CONCURRENT freed 2569K, 34% free 18058K/27152K, paused 5ms+4ms, total 34ms
,D/dalvikvm( 4065): GC_FOR_ALLOC freed 827K, 34% free 18026K/27152K, paused 27ms, total 29ms
,W/jxcore-log( 4065): Initializing JXcore engine
,W/jxcore-log( 4065): JXcore engine is ready
,D/dalvikvm( 4065): GC_CONCURRENT freed 373K, 24% free 20643K/27152K, paused 2ms+2ms, total 32ms
,D/dalvikvm( 4065): WAIT_FOR_CONCURRENT_GC blocked 24ms
,W/jxcore-log( 4065): Starting JXcore engine
,W/jxcore-log( 4065): Platform android
W/jxcore-log( 4065): 
,W/jxcore-log( 4065): Process ARCH arm
W/jxcore-log( 4065): 
,I/jxcore-log( 4065): JXcore Cordova bridge is ready!
I/jxcore-log( 4065): 
,W/jxcore-log( 4065): JXcore engine is started
,I/chromium( 4065): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4065): Toggling radios to true
I/jxcore-log( 4065): 
,D/BluetoothAdapter( 4065): enable(): BT is already enabled..!
D/WifiService( 1022): New client listening to asynchronous messages
D/WifiService( 1022): setWifiEnabled: true pid=4065, uid=10530
,E/WifiService( 1022): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1022): handleMessage: E msg.what=131145
D/WifiStateMachine( 1022): processMsg: ConnectedState
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
I/jxcore-log( 4065): Radios toggled
I/jxcore-log( 4065): 
,D/TCMD    (  438): NL - Read 1000 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
D/TCMD    (  438): NL - Read 68 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
D/TCMD    (  438): NL - Read 68 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
,I/wpa_supplicant( 1154): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
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
,I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
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
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
D/WifiStateMachine( 1022): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1022): invokeExitMethods: ConnectedState
,D/Tethering( 1022): InitialState.processMessage what=4
,D/Tethering( 1022): sendTetherStateChangedBroadcast 0, 0, 0
,V/ConnectivityService( 1022): WiFi NOT Tethered!
D/WifiStateMachine( 1022): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1022): Stopping DHCP and clearing IP
D/WifiStateMachine( 1022): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1022): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1022): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1154): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1154): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  272): Clearing all IP addresses on wlan0
D/TCMD    (  438): NL - Read 60 bytes from update socket.
D/TCMD    (  438): NL - ignore NL message, type = 21
,D/TCMD    (  438): Listening for incoming client connection request
,D/WifiStateMachine( 1022): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1022): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1022): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1022): connected time updated 301193
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1022): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1022): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1022): Attempting to switch to mobile
D/ConnectivityService( 1022): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1022): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1083): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1083): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/ConnectivityService( 1022): resetConnections(wlan0, 3)
D/NetUtils( 1022): android_net_utils_resetConnections in env=0x5fdaff60 clazz=0x63400001 iface=wlan0 mask=0x3
,D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=4
,D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1022): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine( 1022): DisconnectingState
E/wpa_supplicant( 1154): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1154): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1022): handleMessage: X
D/Checkin ( 1022): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiStateMachine( 1022): handleMessage: E msg.what=131146
D/WifiStateMachine( 1022): processMsg: DisconnectingState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147460
D/WifiStateMachine( 1022): processMsg: DisconnectingState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): Network connection lost
D/WifiStateMachine( 1022): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1022): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1380): Read error: ssl=0x6307d9a0: I/O error during system call, Connection timed out
,D/WifiP2pService( 1022): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1022): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1154): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1154): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  272): Clearing all IP addresses on wlan0
V/NativeCrypto( 1380): SSL shutdown failed: ssl=0x6307d9a0: I/O error during system call, Broken pipe
D/WifiStateMachine( 1022): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1022): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1022): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1022): invokeEnterMethods: DisconnectedState
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/Checkin ( 1022): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131101
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131216
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131216
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): handleMessage: X
,D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=false
,I/ModemStatsDSDetect( 1213): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1022): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1213): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1213): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1022): Attempting to switch to mobile
D/ConnectivityService( 1022): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1022): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1022): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1213): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1213): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1213): onReceive() - done, currentInetCondition=0
,I/wpa_supplicant( 1154): wlan0: Trying to associate with SSID 'NG700'
E/wpa_supplicant( 1154): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  438): NL - Read 56 bytes from update socket.
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  274): Event received = Trying to associate with
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1022): handleMessage: E msg.what=147461
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
,D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): handleMessage: X
,I/wpa_supplicant( 1154): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  438): NL - Read 312 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
,D/TCMD    (  438): Listening for incoming client connection request
D/TCMD    (  438): NL - Read 192 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
I/wpa_supplicant( 1154): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  438): NL - Read 68 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
,D/TCMD    (  438): Listening for incoming client connection request
D/TCMD    (  438): NL - Read 1000 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1154): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  274): Event received = Associated with c0:ff:d4
D/TCMD    (  438): NL - Read 80 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
D/TCMD    (  438): NL - Read 80 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
D/TCMD    (  438): NL - Read 68 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1154): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1154): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  274): Event received = WPA: Key negotiation com
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  274): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  274):  STA Connected !!
D/TCMD    (  438): NL - Read 1000 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
E/MDMCTBK (  274): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  274): get_freq !!, resp=0
I/MDMCTBK (  274): get_freq !!, Strip data
I/MDMCTBK (  274): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  274): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  274): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  274): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1224615088
I/MDMCTBK (  274): return from set_get_from_wpa_supplicant
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): handleMessage: X
D/MDMCTBK (  274): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  274): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  274): , reply_len: 3, ret: 0
E/MDMCTBK (  274): MdmCutbackHndler, resp=OK
E/MDMCTBK (  274): 
,D/MDMCTBK (  274): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/Tethering( 1022): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1022): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147459
D/WifiStateMachine( 1022): processMsg: DisconnectedState
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): Network connection established
,D/WifiStateMachine( 1022): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1022): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1022): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1022): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1022): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1022): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=-36ms what=147462 obj=android.net.wifi.StateChangeResult@42967558 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=131101
D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=-28ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@43592280 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1022): processMsg: DefaultState
,D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=196612
D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=-6ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1022): processMsg: L2ConnectedState
,D/WifiStateMachine( 1022): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1022): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1022): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42b5d038 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1022): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42b5d038 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): handleMessage: X
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 c
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 c
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 3
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 3
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 6
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 5 6
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 6 0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE i
D/TCMD    (  438): NL - Read 56 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
,D/TCMD    (  438): Listening for incoming client connection request
,D/WifiP2pService( 1022): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): handleMessage: E msg.what=147461
D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiP2pService( 1022): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1022): ObtainingIpState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiP2pService( 1022): InactiveState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@4456f918 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: DriverStartedState
,D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiP2pService( 1022): P2pEnabledState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@4456f918 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1022): DefaultState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@4456f918 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): handleMessage: X
,D/TCMD    (  438): NL - Read 60 bytes from update socket.
D/TCMD    (  438): NL - ignore NL message, type = 20
,D/TCMD    (  438): Listening for incoming client connection request
,D/WifiStateMachine( 1022): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1022): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
,D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1022): processMsg: DefaultState
,D/WifiStateMachine( 1022): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1022): processMsg: L2ConnectedState
,D/WifiStateMachine( 1022): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1022): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1022): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): DHCP successful
D/WifiStateMachine( 1022): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1022): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1022): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1022): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1022): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1022): VerifyingLinkState enter
D/WifiStateMachine( 1022): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=151572
D/WifiStateMachine( 1022): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1022): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1022): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1083): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=135190
D/WifiStateMachine( 1022): processMsg: VerifyingLinkState
D/WifiStateMachine( 1022): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1022): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1022): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
,D/WifiStateMachine( 1022): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1022): CaptivePortalCheckState enter
,D/WifiStateMachine( 1022): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1022): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1022): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1022): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1022): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131092
D/WifiStateMachine( 1022): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1022): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiStateMachine( 1022): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1022): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1022): WiFi NOT Tethered!
,E/ConnectivityService( 1022): Unexpected mtu value: android.net.wifi.WifiStateTracker@424606f8
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Checkin ( 1022): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/WifiStateMachine( 1022): transitionTo: destState=ConnectedState
,D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1022): invokeExitMethods: CaptivePortalCheckState
,D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
,D/WifiStateMachine( 1022): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=131092
D/WifiStateMachine( 1022): processMsg: ConnectedState
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): processMsg: DriverStartedState
,D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
I/SBar.NetworkController( 1083): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
D/WifiStateMachine( 1022): processMsg: DefaultState
,D/WifiStateMachine( 1022): handleMessage: X
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=true
,I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,I/ModemStatsDSDetect( 1213): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1213): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1213): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1022): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1022): WiFi NOT Tethered!
E/ConnectivityService( 1022): Unexpected mtu value: android.net.wifi.WifiStateTracker@424606f8
,D/ConnectivityService( 1022): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1213): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1213): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1213): onReceive() - done, currentInetCondition=0
,D/PollingManager( 1576): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/Tethering( 1022): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1083): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/CaptivePortalTracker( 1022): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1022): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/XTWiFiOS( 1306): No entry in secure settings for enhanced location services: false
,I/ActivityManager( 1022): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4178 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/TelephonyProvider( 1282): Column apn id key is 'apn_id'
,E/ActivityThread( 1576): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1576): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1576): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1576): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1576): Registering with Alarm Manager to restart CCE
,W/XTWiFiOS( 1306): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/OtaApp  ( 1576): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1576): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1282): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/Tethering( 1022): MasterInitialState.processMessage what=3
D/TelephonyProvider( 1282): Column apn id key is 'apn_id'
,D/CaptivePortalTracker( 1022): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1282): Column apn id key is 'apn_id'
,I/ActivityManager( 1022): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4207 uid=10030 gids={50030, 3003, 1028, 1015}
,D/dalvikvm( 4178): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x42373bf0, skipping init
I/openssl ( 4178): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4178): Crypto mode 0 already enabled
,I/ActivityManager( 1022): Killing 3756:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1299): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4207): mnc/mcc: 
V/MmsConfig( 4207): tag: bool value: enabledMMS - true
,V/MmsConfig( 4207): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4207): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4207): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4207): tag: int value: defaultSMSMessagesPerThread - 500
,V/MmsConfig( 4207): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4207): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4207): tag: int value: maxMessageCountPerThread - 5000
,V/MmsConfig( 4207): tag: int value: recipientLimit - 20
V/MmsConfig( 4207): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4207): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4207): tag: bool value: enableSlideDuration - true
,V/MmsConfig( 4207): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4207): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4207): tag: bool value: smsForceShowEncodingMenu - true
,V/MmsConfig( 4207): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4207): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4207): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1022): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4227 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1022): Killing 3896:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1299): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4227): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4227): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4227): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4227): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1022): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4240 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1022): Killing 3443:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1299): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1421): Checkin interval check for package: unspecified last checkin: 1452278236330 min interval config: 0 actual interval: 289562
,I/CheckinService( 1421): Checking schedule, now: 1452278525900 next: 1452278266251
,I/CheckinService( 1421): active receiver: enabled
,I/CheckinService( 1421): Preparing to send checkin request
,I/EventLogService( 1421): Accumulating logs since 1452278232327
,I/CheckinRequestBuilder( 1421): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1421): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService( 1022): NetTransition Wakelock for ConnectedState released by timeout
,I/ActivityManager( 1022): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4255 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1022): Killing 3941:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1299): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/GLSActivity( 1380): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1380): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1022): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4267 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,D/dalvikvm(  276): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+2ms, total 20ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 18ms
,W/dalvikvm( 4267): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4267): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 1022): GC_EXPLICIT freed 1700K, 65% free 18109K/50980K, paused 4ms+11ms, total 105ms
,V/WebViewChromiumFactoryProvider( 4255): Binding Chromium to main looper Looper (main, tid 1) {42370b28}
,I/LibraryLoader( 4255): Expected native library version number "",actual native library version number ""
,I/chromium( 4255): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4255): Initializing chromium process, renderers=0
,I/dalvikvm( 4267): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4267): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4267): VFY: replacing opcode 0x6e at 0x00cd
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 21ms
I/MultiDex( 4267): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4267): install
,I/MultiDex( 4267): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,E/AudioManagerAndroid( 4255): BLUETOOTH permission is missing!
,I/MultiDex( 4267): loading existing secondary dex files
,I/MultiDex( 4267): load found 3 secondary dex files
,I/Adreno-EGL( 4255): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4255): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4255): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4255): Local Branch: 
I/Adreno-EGL( 4255): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4255): Local Patches: NONE
I/Adreno-EGL( 4255): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/MultiDex( 4267): install done
,D/dalvikvm( 4267): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4267): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4267): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 4267): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4267): VFY: unable to resolve instance field 36
,D/dalvikvm( 4267): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4267): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4267): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4267): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4267): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4267): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4267): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42376700
D/dalvikvm( 4267): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42376700
,D/dalvikvm( 4267): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42376700, skipping init
,D/dalvikvm( 4267): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42376700
,D/dalvikvm( 4267): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42376700
,V/JNIHelp ( 4267): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/chromium( 4255): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4255): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  261): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  261): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4255): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
D/dalvikvm( 4267): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42376700
D/dalvikvm( 4267): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42376700
D/dalvikvm( 4267): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42376700
D/dalvikvm( 4267): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42376700
,I/ProviderInstaller( 4267): Installed default security provider GmsCore_OpenSSL
,I/dalvikvm( 4267): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 4267): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4267): VFY: replacing opcode 0x6e at 0x00ce
,I/dalvikvm( 4267): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4267): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4267): VFY: replacing opcode 0x6e at 0x000d
,I/NSApplication( 4255): Starting up...
I/dalvikvm( 4267): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4267): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4267): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4267): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 4267): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4267): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4267): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4267): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4267): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4267): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4267): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,I/ImageResourceManager( 3478): ImageResourceManager: uninitalized
,I/iu.Environment( 3478): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1022): Killing 3461:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1299): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1251): GC_EXPLICIT freed 946K, 36% free 11065K/17224K, paused 4ms+6ms, total 47ms
,D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  278): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  278): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  278): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb522f000
,E/DrmWidevineDash(  278): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb522f000
D/DrmWidevineDash(  278): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  278): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  278): calling OEMCrypto_IsKeyboxValid...
,I/openssl ( 4178): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4178): Crypto mode 0 already enabled
D/DrmWidevineDash(  278): OEMCrypto_IsKeyboxValid returns 0
D/WVCdm   (  278): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  278): CdmEngine::OpenSession
D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
D/DrmWidevineDash(  278): calling OEMCrypto_GetRandom...
D/DrmWidevineDash(  278): OEMCrypto_GetRandom returns 0
I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/MobileConnectivityChangeReceiver( 4227): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4227): onReceive CONNECTIVITY_CHANGE networkType=1
D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,I/iu.Environment( 3478): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=801666689
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DEBUG   ( 1576): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1576): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1576): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1576): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1576): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1576): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1576): onServiceConnected()
,D/GetNotificationsWS( 1576): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1576): unbindWebServices(): un-registering our AIDL callback...
,D/WearableService( 1251): callingUid 10022, callindPid: 1251
,E/MDM     ( 1251): [130] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1380): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1380): Proximity feature is not enabled.
,D/LocationInitializer( 1421): Restart initialization of location
,V/GLSActivity( 1380): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1251): No location to return for getLastLocation()
,W/FusedLocationProvider( 1251): location=null
,D/dalvikvm( 4267): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42553560
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/dalvikvm( 4267): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42553560
,D/dalvikvm( 4267): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42553560, skipping init
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,D/NativeLibraryUtils( 4267): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4267): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4333): DexOpt: load 3ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4267): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4267): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 71ms
,I/Adreno-EGL( 4267): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4267): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4267): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4267): Local Branch: 
I/Adreno-EGL( 4267): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4267): Local Patches: NONE
I/Adreno-EGL( 4267): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4267): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4267): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4267): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4267): Local Branch: 
I/Adreno-EGL( 4267): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4267): Local Patches: NONE
I/Adreno-EGL( 4267): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 4267): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4267): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4267): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4267): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4267): Local Branch: 
I/Adreno-EGL( 4267): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4267): Local Patches: NONE
I/Adreno-EGL( 4267): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4267): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4267): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4267): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4267): Local Branch: 
I/Adreno-EGL( 4267): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4267): Local Patches: NONE
I/Adreno-EGL( 4267): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  278): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=4085603140
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/Tethering( 1022): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/CaptivePortalTracker( 1022): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1306): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1576): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1576): now: 332928 ,futureTime: 11578181
,D/PollingManager( 1576): Polling alarm set to expire at: 11578181 Current Time: 332928
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,E/ActivityThread( 1576): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1576): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/PollingManager( 1576): now: 332968 ,futureTime: 11578181
D/PollingManager( 1576): Polling alarm set to expire at: 11578181 Current Time: 332968
,W/XTWiFiOS( 1306): No entry in secure settings for enhanced location services: false
E/ActivityThread( 1576): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1576): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1576): [debug] > CusSM.onRadioUp
D/Tethering( 1022): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1022): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/OtaApp  ( 1576): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1576): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
D/OtaApp  ( 1576): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1576): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1576): publish the event [tag = MOT_OTA event name = LOG]
I/openssl ( 4178): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4178): Crypto mode 0 already enabled
D/TelephonyProvider( 1282): Column apn id key is 'apn_id'
D/TelephonyProvider( 1282): Column apn id key is 'apn_id'
D/OtaApp  ( 1576): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1576): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
I/WVCdm   (  278): CdmEngine::CloseSession
D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
D/OtaApp  ( 1576): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/TelephonyProvider( 1282): Column apn id key is 'apn_id'
D/OtaApp  ( 1576): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1576): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/MobileConnectivityChangeReceiver( 4227): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4227): onReceive CONNECTIVITY_CHANGE networkType=1
D/OtaApp  ( 1576): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1576): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1576): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1576): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1576): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/TelephonyProvider( 1282): Column apn id key is 'apn_id'
D/OtaApp  ( 1576): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/iu.Environment( 3478): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1421): Checkin interval check for package: unspecified last checkin: 1452278236330 min interval config: 0 actual interval: 291851
,I/CheckinRequestBuilder( 1421): Classify the device as Phone.
,D/dalvikvm( 3478): GC_CONCURRENT freed 631K, 5% free 16445K/17224K, paused 4ms+3ms, total 28ms
,D/dalvikvm( 3478): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/dalvikvm-heap( 3478): Grow heap (frag case) to 19.829MB for 1821008-byte allocation
,I/openssl ( 4178): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4178): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4227): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4227): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 3478): GC_FOR_ALLOC freed 42K, 5% free 18184K/19004K, paused 10ms, total 10ms
,I/iu.Environment( 3478): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1421): Checkin interval check for package: unspecified last checkin: 1452278236330 min interval config: 0 actual interval: 291933
,D/DEBUG   ( 1576): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1576): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1576): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1576): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1576): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1576): onServiceConnected()
D/WaitableIntentService( 1576): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1576): onServiceConnected(): Registered for remote service callbacks...
,D/DEBUG   ( 1576): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1576): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1576): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1576): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1576): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1576): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1576): onServiceConnected()
,D/GetNotificationsWS( 1576): onServiceConnected(): Registered for remote service callbacks...
D/OtaApp  ( 1576): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/WaitableIntentService( 1576): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1576): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1022): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1576
,W/ContextImpl( 1299): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1299): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/GetNotificationsWS( 1576): unbindWebServices(): un-registering our AIDL callback...
,I/OtaApp  ( 1576): [info] > Updatetime from metadata: 10
,D/Checkin ( 1576): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1576): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1576): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1576): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1576): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1576): [info] > Updatetime from metadata: 10
,D/Checkin ( 1576): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1576): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1576): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1576): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1576): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1576): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1022): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1576
W/ContextImpl( 1299): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1299): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1576): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/CheckinTask( 1421): Sending checkin request (11636 bytes)
I/OtaApp  ( 1576): [info] > Updatetime from metadata: 10
D/Checkin ( 1576): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1576): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1576): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1576): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1576): [info] > Updatetime from metadata: 10
,D/Checkin ( 1576): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1576): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1576): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1576): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1576): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1576): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1022): Activity reported stop, but no longer stopping: ActivityRecord{426a06a8 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,D/WifiStateMachine( 1022): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1022): handleMessage: E msg.what=131215
D/WifiStateMachine( 1022): processMsg: ConnectedState
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1022): processMsg: DefaultState
,D/WifiStateMachine( 1022): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1022): handleMessage: X
I/LaunchCheckinHandler( 1022): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,124
D/ConnectivityService( 1022): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1022):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=true
D/ConnectivityService( 1022): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=true
,I/CheckinRequestBuilder( 1421): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1421): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1421): Classify the device as Phone.
,I/CheckinTask( 1421): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1421): Checking schedule, now: 1452278529272 next: 1452871599264
,I/CheckinService( 1421): active receiver: disabled
,I/CheckinService( 1421): Checking schedule, now: 1452278529300 next: 1452871599264
,I/CheckinService( 1421): active receiver: disabled
,D/CheckinService( 1421): Recording last checkin time for package unspecified as 1452278529306
,D/GCM     ( 1380): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/PhenotypeConfigurator( 1251): Scheduling Phenotype for one-off execution 10575 seconds from now (1452278530077)
,D/GetConfigurationSnapshotOperation( 1251): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1251): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1251): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1251): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1251): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1251): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1251): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1251): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1251): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 1251): GC_CONCURRENT freed 1435K, 33% free 11634K/17224K, paused 3ms+13ms, total 50ms
,D/ConnectivityService( 1022): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1213): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1213): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1213): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1213): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1083): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/dalvikvm( 1380): GC_EXPLICIT freed 1558K, 41% free 10297K/17224K, paused 2ms+4ms, total 33ms
,I/GAV2    ( 4255): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1022): Killing 3967:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1299): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 4065): Test app app.js loaded
I/jxcore-log( 4065): 
,I/Choreographer( 4065): Skipped 713 frames!  The application may be doing too much work on its main thread.
,W/IInputConnectionWrapper( 4065): showStatusIcon on inactive InputConnection
,I/chromium( 4065): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 4065): --= Surplus to requirements =--
I/jxcore-log( 4065): 
,I/jxcore-log( 4065): ****TEST TOOK:  ms ****
I/jxcore-log( 4065): 
,I/jxcore-log( 4065): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4065): 
,D/AndroidRuntime( 4410): 
D/AndroidRuntime( 4410): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4410): CheckJNI is OFF
,D/dalvikvm( 4410): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4410): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4410): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4410): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4410): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4410): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,E/memtrack( 4410): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4410): failed to load memtrack module: -2
,D/AndroidRuntime( 4410): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1022): Force stopping com.test.thalitest appid=10530 user=-1: uninstall pkg
,I/ActivityManager( 1022): Killing 4065:com.test.thalitest/u0a530 (adj 9): stop com.test.thalitest
,W/ContextImpl( 1299): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1022):   Force finishing activity ActivityRecord{42485d10 u0 com.test.thalitest/.MainActivity t3}
,I/WindowState( 1022): WIN DEATH: Window{423a7ef8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1022): Client connection lost with reason: 4
,W/PackageSettings( 1022): Skipping PackageSetting{42630100 com.example.hello/10529} due to missing metadata
,I/ActivityManager( 1022): Force stopping com.test.thalitest appid=10530 user=0: pkg removed
,D/dalvikvm( 2302): GC_EXPLICIT freed 2751K, 43% free 9818K/17224K, paused 2ms+3ms, total 52ms
D/dalvikvm( 1421): GC_EXPLICIT freed 1449K, 31% free 12009K/17224K, paused 4ms+7ms, total 61ms
,W/SQLiteConnectionPool( 1421): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/InputReader( 1022): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "sms"
,I/ActivityManager( 1022): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4421 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/LatinIME:LogUtils( 1226): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452278535
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/LatinIME:LogUtils( 1226): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "smsto"
,I/LatinIME:LogUtils( 1226): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mms"
W/GeofencerStateMachine( 1251): Ignoring removeGeofence because network location is disabled.
,D/dalvikvm( 2272): GC_EXPLICIT freed 5201K, 44% free 9649K/17224K, paused 15ms+7ms, total 65ms
,D/dalvikvm( 1321): GC_EXPLICIT freed 3241K, 33% free 11594K/17224K, paused 2ms+4ms, total 119ms
,D/dalvikvm( 1022): GC_EXPLICIT freed 1347K, 65% free 18136K/50980K, paused 5ms+12ms, total 143ms
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mmsto"
D/dalvikvm( 1022): WAIT_FOR_CONCURRENT_GC blocked 4ms
I/Launcher( 1321): Deferring update until onResume
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "sms"
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "smsto"
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mms"
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mmsto"
,I/Launcher( 1321): Deferring update until onResume
,I/LatinIME:LogUtils( 1226): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452278535
,D/VoicemailCleanupService( 4421): Cleaning up data for package: com.test.thalitest
D/BackupManagerService( 1022): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1022): removePackageParticipantsLocked: uid=10530 #1
,I/ActivityManager( 1022): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4449 uid=10033 gids={50033, 3003, 1028, 1015}
,D/dalvikvm( 1022): GC_EXPLICIT freed 540K, 65% free 18108K/50980K, paused 4ms+19ms, total 187ms
,I/ActivityManager( 1022): Killing 3516:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1299): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2302): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager( 1022): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4465 uid=10059 gids={50059, 3003, 1028, 1015}
,I/ActivityManager( 1022): Killing 4178:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1299): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4421): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/AndroidRuntime( 4410): Shutting down VM
,D/dalvikvm( 4410): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
,I/InternalIcingCorporaPro( 2302): UpdateCorporaTask done [took 112 ms] updated apps [took 112 ms] 
,W/ActiveOrDefaultContextProvider( 4465): Missing scope.enter somewhere. Returning default context
,I/InputReader( 1022): Reconfiguring input devices.  changes=0x00000010
,I/Launcher( 1321): Deferring update until onResume
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "sms"
F/PackageManager( 1022): Unable to backup user packages state file, current changes will be lost at reboot
E/SQLiteLog( 1321): (3850) statement aborts at 30: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,E/DropBoxManagerService( 1022): Can't write: system_server_wtf
E/DropBoxManagerService( 1022): java.io.FileNotFoundException: /data/system/dropbox/drop12.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1022): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1022): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10230)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10135)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10022)
E/DropBoxManagerService( 1022): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService( 1022): 	at android.util.Log$1.onTerribleFailure(Log.java:111)
E/DropBoxManagerService( 1022): 	at android.util.Log.wtf(Log.java:477)
E/DropBoxManagerService( 1022): 	at android.util.Log.wtf(Log.java:440)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1046)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:10124)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:10180)
E/DropBoxManagerService( 1022): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:974)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1538)
E/DropBoxManagerService( 1022): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 1022): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 1022): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1022): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1022): 	... 19 more
,E/SQLiteLog( 4465): (3850) statement aborts at 59: [DELETE FROM CachedSearch101 WHERE timestamp<?] disk I/O error
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "smsto"
F/PackageManager( 1022): Unable to backup user packages state file, current changes will be lost at reboot
E/DropBoxManagerService( 1022): Can't write: system_server_wtf
E/DropBoxManagerService( 1022): java.io.FileNotFoundException: /data/system/dropbox/drop75.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1022): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1022): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10230)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10135)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10022)
E/DropBoxManagerService( 1022): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService( 1022): 	at android.util.Log$1.onTerribleFailure(Log.java:111)
E/DropBoxManagerService( 1022): 	at android.util.Log.wtf(Log.java:477)
E/DropBoxManagerService( 1022): 	at android.util.Log.wtf(Log.java:440)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1046)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:10124)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:10180)
E/DropBoxManagerService( 1022): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:974)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1538)
E/DropBoxManagerService( 1022): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 1022): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 1022): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1022): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1022): 	... 19 more
I/ActivityManager( 1022): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4488 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mms"
F/PackageManager( 1022): Unable to backup user packages state file, current changes will be lost at reboot
E/AbstractDatabaseInstance( 4465): Failed to delete from CachedSearch101
E/AbstractDatabaseInstance( 4465): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AbstractDatabaseInstance( 4465): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AbstractDatabaseInstance( 4465): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AbstractDatabaseInstance( 4465): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AbstractDatabaseInstance( 4465): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AbstractDatabaseInstance( 4465): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AbstractDatabaseInstance( 4465): 	at WQ.b(AbstractDatabaseInstance.java:292)
E/AbstractDatabaseInstance( 4465): 	at XC.a(DatabaseModelLoader.java:317)
E/AbstractDatabaseInstance( 4465): 	at Yg.a(ObsoleteDataCleanerImpl.java:122)
E/AbstractDatabaseInstance( 4465): 	at fh.run(DocsApplication.java:264)
W/dalvikvm( 4465): threadid=11: thread exiting with uncaught exception (group=0x41a9cd40)
E/AndroidRuntime( 4465): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 4465): Process: com.google.android.apps.docs, PID: 4465
E/AndroidRuntime( 4465): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4465): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4465): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4465): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4465): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4465): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 4465): 	at WQ.b(AbstractDatabaseInstance.java:292)
E/AndroidRuntime( 4465): 	at XC.a(DatabaseModelLoader.java:317)
E/AndroidRuntime( 4465): 	at Yg.a(ObsoleteDataCleanerImpl.java:122)
E/AndroidRuntime( 4465): 	at fh.run(DocsApplication.java:264)
E/DropBoxManagerService( 1022): Can't write: system_server_wtf
E/DropBoxManagerService( 1022): java.io.FileNotFoundException: /data/system/dropbox/drop12.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1022): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1022): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10230)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10135)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10022)
E/DropBoxManagerService( 1022): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService( 1022): 	at android.util.Log$1.onTerribleFailure(Log.java:111)
E/DropBoxManagerService( 1022): 	at android.util.Log.wtf(Log.java:477)
E/DropBoxManagerService( 1022): 	at android.util.Log.wtf(Log.java:440)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1046)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:10124)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:10180)
E/DropBoxManagerService( 1022): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:974)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1538)
E/DropBoxManagerService( 1022): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 1022): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 1022): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1022): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1022): 	... 19 more
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mmsto"
F/PackageManager( 1022): Unable to backup user packages state file, current changes will be lost at reboot
E/DropBoxManagerService( 1022): Can't write: system_server_wtf
E/DropBoxManagerService( 1022): java.io.FileNotFoundException: /data/system/dropbox/drop12.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1022): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1022): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10230)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10135)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10022)
E/DropBoxManagerService( 1022): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService( 1022): 	at android.util.Log$1.onTerribleFailure(Log.java:111)
E/DropBoxManagerService( 1022): 	at android.util.Log.wtf(Log.java:477)
E/DropBoxManagerService( 1022): 	at android.util.Log.wtf(Log.java:440)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1046)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:10124)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:10180)
E/DropBoxManagerService( 1022): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:974)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1538)
E/DropBoxManagerService( 1022): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 1022): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 1022): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1022): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1022): 	... 19 more
I/Launcher( 1321): Deferring update until onResume
E/DropBoxManagerService( 1022): Can't write: system_app_crash
E/DropBoxManagerService( 1022): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1022): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1022): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1022): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1022): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1022): 	... 5 more
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "sms"
F/PackageManager( 1022): Unable to backup user packages state file, current changes will be lost at reboot
E/DropBoxManagerService( 1022): Can't write: system_server_wtf
E/DropBoxManagerService( 1022): java.io.FileNotFoundException: /data/system/dropbox/drop69.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1022): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1022): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10230)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10135)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10022)
E/DropBoxManagerService( 1022): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService( 1022): 	at android.util.Log$1.onTerribleFailure(Log.java:111)
E/DropBoxManagerService( 1022): 	at android.util.Log.wtf(Log.java:477)
E/DropBoxManagerService( 1022): 	at android.util.Log.wtf(Log.java:440)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1046)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:10124)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:10180)
E/DropBoxManagerService( 1022): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:974)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1538)
E/DropBoxManagerService( 1022): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 1022): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 1022): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1022): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1022): 	... 19 more
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "smsto"
F/PackageManager( 1022): Unable to backup user packages state file, current changes will be lost at reboot
W/GAV2    ( 4465): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/DropBoxManagerService( 1022): Can't write: system_server_wtf
E/DropBoxManagerService( 1022): java.io.FileNotFoundException: /data/system/dropbox/drop91.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1022): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1022): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10230)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10135)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10022)
E/DropBoxManagerService( 1022): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService( 1022): 	at android.util.Log$1.onTerribleFailure(Log.java:111)
E/DropBoxManagerService( 1022): 	at android.util.Log.wtf(Log.java:477)
E/DropBoxManagerService( 1022): 	at android.util.Log.wtf(Log.java:440)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1046)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:10124)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:10180)
E/DropBoxManagerService( 1022): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:974)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1538)
E/DropBoxManagerService( 1022): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 1022): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 1022): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1022): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1022): 	... 19 more
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mms"
F/PackageManager( 1022): Unable to backup user packages state file, current changes will be lost at reboot
I/Process ( 4465): Sending signal. PID: 4465 SIG: 9
E/DropBoxManagerService( 1022): Can't write: system_server_wtf
E/DropBoxManagerService( 1022): java.io.FileNotFoundException: /data/system/dropbox/drop13.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1022): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1022): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10230)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10135)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10022)
E/DropBoxManagerService( 1022): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService( 1022): 	at android.util.Log$1.onTerribleFailure(Log.java:111)
E/DropBoxManagerService( 1022): 	at android.util.Log.wtf(Log.java:477)
E/DropBoxManagerService( 1022): 	at android.util.Log.wtf(Log.java:440)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1046)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:10124)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:10180)
E/DropBoxManagerService( 1022): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:974)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1538)
E/DropBoxManagerService( 1022): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 1022): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 1022): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1022): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1022): 	... 19 more
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mmsto"
F/PackageManager( 1022): Unable to backup user packages state file, current changes will be lost at reboot
I/ActivityManager( 1022): Process com.google.android.apps.docs (pid 4465) has died.
W/ActivityManager( 1022): Scheduling restart of crashed service com.google.android.apps.docs/.sync.syncadapter.ContentSyncService in 1000ms
E/DropBoxManagerService( 1022): Can't write: system_server_wtf
E/DropBoxManagerService( 1022): java.io.FileNotFoundException: /data/system/dropbox/drop68.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1022): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1022): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10230)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10135)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10022)
E/DropBoxManagerService( 1022): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService( 1022): 	at android.util.Log$1.onTerribleFailure(Log.java:111)
E/DropBoxManagerService( 1022): 	at android.util.Log.wtf(Log.java:477)
E/DropBoxManagerService( 1022): 	at android.util.Log.wtf(Log.java:440)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1046)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:10124)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:10180)
E/DropBoxManagerService( 1022): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:974)
E/DropBoxManagerService( 1022): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1538)
E/DropBoxManagerService( 1022): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 1022): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 1022): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1022): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1022): 	... 19 more

```
