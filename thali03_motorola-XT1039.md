#### Test 5497026186051be_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1020): sending alarm Alarm{42906850 type 3 android}
--------- beginning of /dev/log/main
D/AndroidRuntime( 4152): 
D/AndroidRuntime( 4152): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4152): CheckJNI is OFF
D/dalvikvm( 4152): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4152): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4152): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4152): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4152): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4152): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4152): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4152): failed to load memtrack module: -2
D/AndroidRuntime( 4152): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1020): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4152
W/WindowManager( 1020): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1020): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4168 uid=10536 gids={50536, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4152): Shutting down VM
D/dalvikvm( 4152): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 2ms
W/ContextImpl( 1238): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1238): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4168): Binding Chromium to main looper Looper (main, tid 1) {420d0d68}
I/LibraryLoader( 4168): Expected native library version number "",actual native library version number ""
I/chromium( 4168): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4168): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1020): Message: 20
D/BluetoothManagerService( 1020): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42a10920:true
I/Adreno-EGL( 4168): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4168): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4168): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4168): Local Branch: 
I/Adreno-EGL( 4168): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4168): Local Patches: NONE
I/Adreno-EGL( 4168): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4168): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4168): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4168): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4168): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4168): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4168): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4168): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4168): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4168): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4168): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4168): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4168): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4168): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4168): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4168): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4168): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4168): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4168): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4168): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4168): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4168): Enabling debug mode 0
,W/AwContents( 4168): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1020): Displayed com.test.thalitest/.MainActivity,cp,ca,343
I/ActivityManager( 1020): Displayed com.test.thalitest/.MainActivity: +319ms (total +343ms)
W/AwContents( 4168): nativeOnDraw failed; clearing to background color.
W/IInputConnectionWrapper( 4168): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 4168): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4168): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x420d5038
,D/dalvikvm( 4168): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x420d5038
,D/jxcore_app_log( 4168): JniHelper::setJavaVM(0x417ecf78), pthread_self() = 1614607536
,D/JX-Cordova( 4168): jxcore cordova android initializing
,D/dalvikvm( 4168): GC_CONCURRENT freed 2770K, 17% free 14419K/17224K, paused 2ms+3ms, total 47ms
,D/dalvikvm( 4168): GC_FOR_ALLOC freed 133K, 17% free 14396K/17224K, paused 27ms, total 27ms
,D/dalvikvm( 4168): GC_FOR_ALLOC freed 119K, 17% free 14422K/17224K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4168): Grow heap (frag case) to 16.208MB for 95956-byte allocation
,D/dalvikvm( 4168): GC_FOR_ALLOC freed 184K, 17% free 14450K/17320K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4168): Grow heap (frag case) to 16.281MB for 143930-byte allocation
,D/dalvikvm( 4168): GC_FOR_ALLOC freed 252K, 17% free 14497K/17464K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4168): Grow heap (frag case) to 16.396MB for 215890-byte allocation
,D/dalvikvm( 4168): GC_FOR_ALLOC freed 366K, 18% free 14571K/17676K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4168): Grow heap (frag case) to 16.571MB for 323830-byte allocation
,D/dalvikvm( 4168): GC_FOR_ALLOC freed 564K, 19% free 14692K/17996K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4168): Grow heap (frag case) to 16.843MB for 485740-byte allocation
,D/dalvikvm( 4168): GC_FOR_ALLOC freed 860K, 20% free 14868K/18472K, paused 27ms, total 27ms
,D/dalvikvm( 4168): GC_FOR_ALLOC freed 1275K, 19% free 15124K/18472K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4168): Grow heap (frag case) to 17.844MB for 1092904-byte allocation
,D/dalvikvm( 4168): GC_CONCURRENT freed 1772K, 21% free 15509K/19540K, paused 1ms+3ms, total 35ms
,D/dalvikvm( 4168): GC_FOR_ALLOC freed 253K, 21% free 15456K/19540K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4168): Grow heap (frag case) to 18.690MB for 1639352-byte allocation
,D/dalvikvm( 4168): GC_CONCURRENT freed 1732K, 25% free 16022K/21144K, paused 1ms+4ms, total 33ms
,D/dalvikvm( 4168): GC_FOR_ALLOC freed 1264K, 24% free 16077K/21144K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4168): Grow heap (frag case) to 20.078MB for 2459024-byte allocation
,D/dalvikvm( 4168): GC_CONCURRENT freed 1715K, 29% free 16860K/23548K, paused 5ms+4ms, total 40ms
,D/dalvikvm( 4168): GC_CONCURRENT freed 2448K, 28% free 17031K/23548K, paused 1ms+6ms, total 41ms
,D/dalvikvm( 4168): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 4168): GC_FOR_ALLOC freed 716K, 29% free 16804K/23548K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4168): Grow heap (frag case) to 21.959MB for 3688532-byte allocation
,D/dalvikvm( 4168): GC_CONCURRENT freed 2638K, 34% free 17998K/27152K, paused 4ms+4ms, total 40ms
,D/dalvikvm( 4168): GC_FOR_ALLOC freed 702K, 34% free 18021K/27152K, paused 28ms, total 28ms
,W/jxcore-log( 4168): Initializing JXcore engine
,W/jxcore-log( 4168): JXcore engine is ready
,D/dalvikvm( 4168): GC_CONCURRENT freed 368K, 24% free 20644K/27152K, paused 2ms+2ms, total 33ms
,D/dalvikvm( 4168): WAIT_FOR_CONCURRENT_GC blocked 25ms
W/jxcore-log( 4168): Starting JXcore engine
,W/jxcore-log( 4168): Platform android
W/jxcore-log( 4168): 
,W/jxcore-log( 4168): Process ARCH arm
W/jxcore-log( 4168): 
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4168): JXcore Cordova bridge is ready!
I/jxcore-log( 4168): 
,W/jxcore-log( 4168): JXcore engine is started
,I/chromium( 4168): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4168): Toggling radios to true
I/jxcore-log( 4168): 
,D/BluetoothAdapter( 4168): enable(): BT is already enabled..!
D/WifiService( 1020): New client listening to asynchronous messages
D/WifiService( 1020): setWifiEnabled: true pid=4168, uid=10536
,E/WifiService( 1020): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1020): handleMessage: E msg.what=131145
D/WifiStateMachine( 1020): processMsg: ConnectedState
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
I/jxcore-log( 4168): Radios toggled
I/jxcore-log( 4168): 
I/jxcore-log( 4168): My device name is: motorola-XT1039
I/jxcore-log( 4168): 
,D/TCMD    (  487): NL - Read 1000 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
D/TCMD    (  487): NL - Read 68 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
D/TCMD    (  487): NL - Read 68 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
,D/TCMD    (  487): Listening for incoming client connection request
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
,I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
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
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
,D/Tethering( 1020): InitialState.processMessage what=4
,V/ConnectivityService( 1020): WiFi NOT Tethered!
D/WifiStateMachine( 1020): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1020): invokeExitMethods: ConnectedState
D/Tethering( 1020): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1020): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1020): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1020): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  272): Clearing all IP addresses on wlan0
D/TCMD    (  487): NL - Read 60 bytes from update socket.
D/TCMD    (  487): NL - ignore NL message, type = 21
,D/TCMD    (  487): Listening for incoming client connection request
,D/WifiStateMachine( 1020): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1020): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1020): connected time updated 328690
,D/WifiStateMachine( 1020): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/ConnectivityService( 1020): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1020): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/ConnectivityService( 1020): Attempting to switch to mobile
D/ConnectivityService( 1020): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1020): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1083): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1083): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/ConnectivityService( 1020): resetConnections(wlan0, 3)
D/NetUtils( 1020): android_net_utils_resetConnections in env=0x6002e330 clazz=0x62700001 iface=wlan0 mask=0x3
,D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1020): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine( 1020): DisconnectingState
E/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=131146
D/WifiStateMachine( 1020): processMsg: DisconnectingState
,D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
,V/NativeCrypto( 1361): Read error: ssl=0x631ff698: I/O error during system call, Connection timed out
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147460
D/WifiStateMachine( 1020): processMsg: DisconnectingState
,D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): Network connection lost
D/WifiStateMachine( 1020): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1020): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  272): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1020): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
V/NativeCrypto( 1361): SSL shutdown failed: ssl=0x631ff698: I/O error during system call, Broken pipe
D/WifiStateMachine( 1020): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1020): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1020): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131101
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131216
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131216
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityService( 1020): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1020): Attempting to switch to mobile
D/ConnectivityService( 1020): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1020): Attempting to switch to ETHERNET
D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,I/ModemStatsDSDetect( 1297): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1297): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1297): onReceive() - done, currentInetCondition=0
,I/ModemStatsDSDetect( 1297): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1297): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1297): onReceive() - done, currentInetCondition=0
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
I/wpa_supplicant( 1161): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  274): Event received = Trying to associate with
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147461
D/TCMD    (  487): NL - Read 56 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
,D/TCMD    (  487): Listening for incoming client connection request
,E/wpa_supplicant( 1161): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
,D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
,D/WifiStateMachine( 1020): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
,I/wpa_supplicant( 1161): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  487): NL - Read 312 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
,D/TCMD    (  487): Listening for incoming client connection request
D/TCMD    (  487): NL - Read 192 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
,D/TCMD    (  487): Listening for incoming client connection request
,I/wpa_supplicant( 1161): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  487): NL - Read 68 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
,D/TCMD    (  487): Listening for incoming client connection request
D/TCMD    (  487): NL - Read 1000 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1161): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  274): Event received = Associated with c0:ff:d4
D/TCMD    (  487): NL - Read 80 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
D/TCMD    (  487): NL - Read 80 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
D/TCMD    (  487): NL - Read 68 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
,D/TCMD    (  487): Listening for incoming client connection request
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1020): processMsg: DisconnectedState
,D/WifiStateMachine( 1020): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
,D/Tethering( 1020): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1020): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiStateMachine( 1020): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
,D/WifiStateMachine( 1020): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
I/wpa_supplicant( 1161): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  274): Event received = WPA: Key negotiation com
,I/wpa_supplicant( 1161): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  274): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  274):  STA Connected !!
D/TCMD    (  487): NL - Read 1000 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
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
I/MDMCTBK (  274): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1202967728
I/MDMCTBK (  274): return from set_get_from_wpa_supplicant
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  274): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  274): , reply_len: 3, ret: 0
E/MDMCTBK (  274): MdmCutbackHndler, resp=OK
E/MDMCTBK (  274): 
,D/MDMCTBK (  274): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147459
,D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): Network connection established
,D/WifiStateMachine( 1020): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/WifiStateMachine( 1020): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1020): invokeExitMethods: DisconnectedState
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1020): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1020): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1020): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
,D/WifiStateMachine( 1020): ObtainingIpState{ when=-24ms what=147462 obj=android.net.wifi.StateChangeResult@4423ab78 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=196612
,D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-2ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1020): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1020): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@422332e0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@422332e0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): handleMessage: X
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 c
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 6 c
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 3
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 7 3
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 8 0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 8
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 9 8
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/TCMD    (  487): NL - Read 56 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 80
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 80
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 64
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 5 64
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiP2pService( 1020): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): InactiveState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@43ac7950 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2pEnabledState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@43ac7950 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): DefaultState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@43ac7950 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): handleMessage: E msg.what=147461
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1020): handleMessage: X
,D/TCMD    (  487): NL - Read 60 bytes from update socket.
D/TCMD    (  487): NL - ignore NL message, type = 20
,D/TCMD    (  487): Listening for incoming client connection request
,D/WifiStateMachine( 1020): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1020): handleMessage: E msg.what=131215
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
,D/WifiStateMachine( 1020): ObtainingIpState{ when=0 what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1020): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1020): DHCP successful
,D/WifiStateMachine( 1020): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1020): Calling ARP set with IP = 192.168.1.127
,D/WifiStateMachine( 1020): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1020): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1020): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1020): VerifyingLinkState enter
,D/WifiStateMachine( 1020): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=151572
D/WifiStateMachine( 1020): processMsg: VerifyingLinkState
D/WifiStateMachine( 1020): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1083): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=135190
D/WifiStateMachine( 1020): processMsg: VerifyingLinkState
D/WifiStateMachine( 1020): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1020): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1020): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1020): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine( 1020): CaptivePortalCheckState enter
,D/WifiStateMachine( 1020): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1020): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1020): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1020): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1020): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131092
D/WifiStateMachine( 1020): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1020): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiStateMachine( 1020): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1020): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService( 1020): WiFi NOT Tethered!
,E/ConnectivityService( 1020): Unexpected mtu value: android.net.wifi.WifiStateTracker@421cefe0
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1297): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1297): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1297): onReceive() - done, currentInetCondition=0
,D/ConnectivityService( 1020): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/WifiStateMachine( 1020): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1020): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1020): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131092
D/WifiStateMachine( 1020): processMsg: ConnectedState
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
I/SBar.NetworkController( 1083): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,V/ConnectivityService( 1020): WiFi NOT Tethered!
,I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
E/ConnectivityService( 1020): Unexpected mtu value: android.net.wifi.WifiStateTracker@421cefe0
,D/ConnectivityService( 1020): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
,I/ModemStatsDSDetect( 1297): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1297): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1297): onReceive() - done, currentInetCondition=0
,D/ConnectivityService( 1020): NetTransition Wakelock for ConnectedState released by timeout
,D/CaptivePortalTracker( 1020): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1020): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/Tethering( 1020): MasterInitialState.processMessage what=3
D/TelephonyProvider( 1268): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1280): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1578): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1083): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1280): No entry in secure settings for enhanced location services: false
,E/ActivityThread( 1578): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1578): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1578): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1578): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1578): Registering with Alarm Manager to restart CCE
D/OtaApp  ( 1578): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1578): [debug] > CusSM.onRadioDown
D/Tethering( 1020): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1020): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/openssl ( 4049): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4049): Crypto mode 0 already enabled
D/TelephonyProvider( 1268): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1268): Column apn id key is 'apn_id'
,D/dalvikvm( 1020): GC_EXPLICIT freed 1714K, 65% free 18093K/50916K, paused 4ms+10ms, total 93ms
,I/ActivityManager( 1020): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4300 uid=10030 gids={50030, 3003, 1028, 1015}
D/TelephonyProvider( 1268): Column apn id key is 'apn_id'
,V/MmsConfig( 4300): mnc/mcc: 
,V/MmsConfig( 4300): tag: bool value: enabledMMS - true
V/MmsConfig( 4300): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4300): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4300): tag: int value: maxImageWidth - 2592
,V/MmsConfig( 4300): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4300): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4300): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4300): tag: int value: maxMessageCountPerThread - 5000
,V/MmsConfig( 4300): tag: int value: recipientLimit - 20
V/MmsConfig( 4300): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4300): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4300): tag: bool value: enableSlideDuration - true
,V/MmsConfig( 4300): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4300): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4300): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4300): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 4300): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4300): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1020): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4318 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1020): Killing 3968:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1238): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4318): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4318): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4318): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4318): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1020): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4332 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 3982:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1238): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  276): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 21ms
,I/CheckinService( 1391): Checkin interval check for package: unspecified last checkin: 1452511669711 min interval config: 0 actual interval: 318642
,I/CheckinService( 1391): Checking schedule, now: 1452511988362 next: 1452511699657
,I/CheckinService( 1391): active receiver: enabled
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,I/CheckinService( 1391): Preparing to send checkin request
,I/EventLogService( 1391): Accumulating logs since 1452511666288
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 18ms
,I/CheckinRequestBuilder( 1391): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1391): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1020): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4346 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 4002:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1238): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4346): Binding Chromium to main looper Looper (main, tid 1) {420c9510}
,I/LibraryLoader( 4346): Expected native library version number "",actual native library version number ""
,I/chromium( 4346): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4346): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4346): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4346): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4346): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4346): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4346): Local Branch: 
I/Adreno-EGL( 4346): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4346): Local Patches: NONE
I/Adreno-EGL( 4346): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium( 4346): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/ActivityManager( 1020): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4375 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/GAV2    ( 4346): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  261): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  261): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4346): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/dalvikvm( 4375): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4375): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4375): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
,W/dalvikvm( 4375): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4375): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 4375): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4375): install
,I/MultiDex( 4375): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4375): loading existing secondary dex files
,I/MultiDex( 4375): load found 3 secondary dex files
,I/MultiDex( 4375): install done
,D/dalvikvm( 4375): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4375): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4375): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4375): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4375): VFY: unable to resolve instance field 36
,D/dalvikvm( 4375): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4375): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4375): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4375): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4375): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4375): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4375): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x420cfe18
D/dalvikvm( 4375): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x420cfe18
,D/dalvikvm( 4375): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x420cfe18, skipping init
,D/dalvikvm( 4375): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x420cfe18
D/dalvikvm( 4375): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x420cfe18
,V/JNIHelp ( 4375): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4375): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x420cfe18
,D/dalvikvm( 4375): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x420cfe18
D/dalvikvm( 4375): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x420cfe18
,D/dalvikvm( 4375): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x420cfe18
,I/NSApplication( 4346): Starting up...
,I/ImageResourceManager( 4029): ImageResourceManager: uninitalized
,I/iu.Environment( 4029): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1020): Killing 3949:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1238): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/openssl ( 4049): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4049): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4318): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4318): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 4029): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/DEBUG   ( 1578): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1578): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1578): bindWebServices(): registering our AIDL callback...
,I/ProviderInstaller( 4375): Installed default security provider GmsCore_OpenSSL
,I/SundryService( 1578): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1578): ServiceHandler.handleMessage: mWaitCount=0
D/EmailService.MarketingOptInSetter( 1578): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1578): onServiceConnected()
,D/GetNotificationsWS( 1578): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1578): unbindWebServices(): un-registering our AIDL callback...
,D/WearableService( 1222): callingUid 10022, callindPid: 1222
,D/LocationInitializer( 1391): Restart initialization of location
D/AuthorizationBluetoothService( 1361): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1361): Proximity feature is not enabled.
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1222): [126] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/dalvikvm( 4375): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4375): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4375): VFY: replacing opcode 0x6e at 0x00ce
,W/GCoreFlp( 1222): No location to return for getLastLocation()
,W/FusedLocationProvider( 1222): location=null
I/dalvikvm( 4375): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4375): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4375): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4375): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4375): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4375): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4375): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4375): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4375): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4375): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4375): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4375): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4375): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4375): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  279): Instantiating CDM.
,I/WVCdm   (  279): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  279): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  279): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  279): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5355000
,E/DrmWidevineDash(  279): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5355000
D/DrmWidevineDash(  279): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  279): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  279): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  279): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  279): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
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
D/WVCdm   (  279): PrepareKeyRequest: nonce=1134862688
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4375): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4375): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x422c8cc0
D/dalvikvm( 4375): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x422c8cc0
,D/dalvikvm( 4375): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x422c8cc0, skipping init
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4375): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4414): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4375): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4375): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 65ms
,D/CaptivePortalTracker( 1020): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering( 1020): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1280): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/PollingManager( 1578): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/PollingManager( 1578): now: 360026 ,futureTime: 35225570
,D/PollingManager( 1578): Polling alarm set to expire at: 35225570 Current Time: 360026
,E/ActivityThread( 1578): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1578): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/Adreno-EGL( 4375): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4375): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4375): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4375): Local Branch: 
I/Adreno-EGL( 4375): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4375): Local Patches: NONE
I/Adreno-EGL( 4375): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
D/OtaApp  ( 1578): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1578): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1578): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1578): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1578): publish the event [tag = MOT_OTA event name = LOG]
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/OtaApp  ( 1578): [debug] > CusSM.runStateMachine: server told to :continue
,D/PollingManager( 1578): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1578): now: 360063 ,futureTime: 35225570
,D/PollingManager( 1578): Polling alarm set to expire at: 35225570 Current Time: 360063
,D/OtaApp  ( 1578): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1280): No entry in secure settings for enhanced location services: false
,E/ActivityThread( 1578): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1578): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1578): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1578): [debug] > CusSM.onRadioUp
I/openssl ( 4049): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4049): Crypto mode 0 already enabled
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/OtaApp  ( 1578): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/CaptivePortalTracker( 1020): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering( 1020): MasterInitialState.processMessage what=3
D/OtaApp  ( 1578): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1578): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1578): publish the event [tag = MOT_OTA event name = LOG]
D/TelephonyProvider( 1268): Column apn id key is 'apn_id'
D/OtaApp  ( 1578): [debug] > CusSM.runStateMachine: server told to :continue
D/TelephonyProvider( 1268): Column apn id key is 'apn_id'
D/OtaApp  ( 1578): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1578): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MobileConnectivityChangeReceiver( 4318): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4318): onReceive CONNECTIVITY_CHANGE networkType=1
,D/TelephonyProvider( 1268): Column apn id key is 'apn_id'
,I/iu.Environment( 4029): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/TelephonyProvider( 1268): Column apn id key is 'apn_id'
,I/Adreno-EGL( 4375): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4375): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4375): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4375): Local Branch: 
I/Adreno-EGL( 4375): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4375): Local Patches: NONE
I/Adreno-EGL( 4375): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinService( 1391): Checkin interval check for package: unspecified last checkin: 1452511669711 min interval config: 0 actual interval: 319959
,D/DEBUG   ( 1578): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1578): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1578): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1578): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/EmailService.MarketingOptInSetter( 1578): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1578): onServiceConnected()
,D/GetNotificationsWS( 1578): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1578): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1578): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4049): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4049): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4318): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4318): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 4029): GC_FOR_ALLOC freed 605K, 5% free 16434K/17224K, paused 17ms, total 17ms
,I/dalvikvm-heap( 4029): Grow heap (frag case) to 19.818MB for 1821008-byte allocation
,I/iu.Environment( 4029): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1391): Checkin interval check for package: unspecified last checkin: 1452511669711 min interval config: 0 actual interval: 320054
,D/DEBUG   ( 1578): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/dalvikvm( 4029): GC_FOR_ALLOC freed 30K, 5% free 18186K/19004K, paused 21ms, total 22ms
,W/ContextImpl( 1578): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1578): bindWebServices(): registering our AIDL callback...
D/EmailService.MarketingOptInSetter( 1578): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1578): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1578): onServiceConnected()
,D/GetNotificationsWS( 1578): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1578): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1578): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1578): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1020): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1578
,W/ContextImpl( 1238): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1238): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/GetNotificationsWS( 1578): unbindWebServices(): un-registering our AIDL callback...
,I/OtaApp  ( 1578): [info] > Updatetime from metadata: 10
,D/Checkin ( 1578): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1578): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1578): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1578): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1578): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1578): [info] > Updatetime from metadata: 10
,D/Checkin ( 1578): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1578): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1578): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1578): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1578): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1578): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1020): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1578
W/ContextImpl( 1238): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1238): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1578): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1578): [info] > Updatetime from metadata: 10
,D/Checkin ( 1578): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1578): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1578): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1578): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1578): [info] > Updatetime from metadata: 10
,D/Checkin ( 1578): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1578): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1578): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1578): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1578): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1578): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1020): Activity reported stop, but no longer stopping: ActivityRecord{42a676a8 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/LaunchCheckinHandler( 1020): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,119
,I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  279): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  279): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  279): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  279): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=803204190
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,W/Settings( 4375): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4375): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4375): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4375): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4375): Local Branch: 
I/Adreno-EGL( 4375): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4375): Local Patches: NONE
I/Adreno-EGL( 4375): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4375): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4375): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4375): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4375): Local Branch: 
I/Adreno-EGL( 4375): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4375): Local Patches: NONE
I/Adreno-EGL( 4375): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1391): Classify the device as Phone.
,D/WifiStateMachine( 1020): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1020): handleMessage: E msg.what=131215
D/WifiStateMachine( 1020): processMsg: ConnectedState
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
,D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/dalvikvm( 1020): GC_EXPLICIT freed 731K, 65% free 18013K/50916K, paused 3ms+9ms, total 92ms
,D/WifiStateMachine( 1020): handleMessage: X
D/ConnectivityService( 1020): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1020):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1020): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
V/NativeCrypto( 1391): SSL shutdown failed: ssl=0x6bfe9760: I/O error during system call, Connection timed out
,I/CheckinTask( 1391): Sending checkin request (11758 bytes)
,I/CheckinRequestBuilder( 1391): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1391): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1391): Classify the device as Phone.
,I/CheckinTask( 1391): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1391): Checking schedule, now: 1452511991572 next: 1453105061561
,I/CheckinService( 1391): active receiver: disabled
,I/CheckinService( 1391): Checking schedule, now: 1452511991595 next: 1453105061561
,I/CheckinService( 1391): active receiver: disabled
,D/CheckinService( 1391): Recording last checkin time for package unspecified as 1452511991601
,D/GCM     ( 1361): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService( 1020): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1297): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1083): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1297): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1297): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1297): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/GAV2    ( 4346): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1020): Killing 3517:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1238): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 4168): Test app app.js loaded
I/jxcore-log( 4168): 
,I/Choreographer( 4168): Skipped 707 frames!  The application may be doing too much work on its main thread.
,W/IInputConnectionWrapper( 4168): showStatusIcon on inactive InputConnection
,I/chromium( 4168): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 4168): --= Surplus to requirements =--
I/jxcore-log( 4168): 
I/jxcore-log( 4168): ****TEST TOOK:  ms ****
I/jxcore-log( 4168): 
,I/jxcore-log( 4168): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4168): 
,D/AndroidRuntime( 4458): 
D/AndroidRuntime( 4458): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4458): CheckJNI is OFF
,D/dalvikvm( 4458): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4458): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4458): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4458): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4458): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4458): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,E/memtrack( 4458): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4458): failed to load memtrack module: -2
,D/AndroidRuntime( 4458): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10536 user=-1: uninstall pkg
,I/ActivityManager( 1020): Killing 4168:com.test.thalitest/u0a536 (adj 9): stop com.test.thalitest
,I/ActivityManager( 1020):   Force finishing activity ActivityRecord{42a100c0 u0 com.test.thalitest/.MainActivity t3}
,W/ContextImpl( 1238): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/WindowState( 1020): WIN DEATH: Window{42ab3ba0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1020): Client connection lost with reason: 4
,W/PackageSettings( 1020): Skipping PackageSetting{42399218 com.example.hello/10529} due to missing metadata
,I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10536 user=0: pkg removed
,D/dalvikvm( 2280): GC_EXPLICIT freed 5213K, 44% free 9648K/17224K, paused 2ms+5ms, total 44ms
,I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
,I/ActivityManager( 1020): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4477 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
D/dalvikvm( 1391): GC_EXPLICIT freed 1417K, 31% free 11977K/17224K, paused 3ms+57ms, total 107ms
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
I/LatinIME:LogUtils( 1202): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1202): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
W/GeofencerStateMachine( 1222): Ignoring removeGeofence because network location is disabled.
D/dalvikvm( 2312): GC_EXPLICIT freed 2486K, 44% free 9813K/17224K, paused 2ms+8ms, total 106ms
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
,D/dalvikvm( 1020): GC_EXPLICIT freed 801K, 65% free 18082K/50916K, paused 3ms+10ms, total 112ms
,D/dalvikvm( 1020): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/dalvikvm( 1311): GC_EXPLICIT freed 3136K, 33% free 11593K/17224K, paused 17ms+11ms, total 86ms
,I/Launcher( 1311): Deferring update until onResume
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
,I/LatinIME:LogUtils( 1202): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452511997
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
I/Launcher( 1311): Deferring update until onResume
,I/LatinIME:LogUtils( 1202): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452511997
,D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 1020): removePackageParticipantsLocked: uid=10536 #1
,I/ActivityManager( 1020): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4495 uid=10033 gids={50033, 3003, 1028, 1015}
D/VoicemailCleanupService( 4477): Cleaning up data for package: com.test.thalitest
,D/dalvikvm( 1020): GC_EXPLICIT freed 447K, 65% free 18072K/50916K, paused 4ms+15ms, total 170ms
,I/InternalIcingCorporaPro( 2312): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager( 1020): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4512 uid=10059 gids={50059, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 4135:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1238): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1020): Killing 4049:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1238): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/AndroidRuntime( 4458): Shutting down VM
,D/dalvikvm( 4458): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 3ms
,I/ContactLocale( 4477): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/InternalIcingCorporaPro( 2312): UpdateCorporaTask done [took 159 ms] updated apps [took 159 ms] 
,W/ActiveOrDefaultContextProvider( 4512): Missing scope.enter somewhere. Returning default context
,I/ActivityManager( 1020): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4532 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/GAV2    ( 4512): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ContextImpl( 4532): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,I/ActivityManager( 1020): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4551 uid=10038 gids={50038, 3003, 1028, 1015}
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
F/PackageManager( 1020): Unable to backup user packages state file, current changes will be lost at reboot
I/Launcher( 1311): Deferring update until onResume
I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
E/SQLiteLog( 1311): (3850) statement aborts at 30: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
E/SQLiteDatabase( 4532): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4532): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4532): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4532): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4532): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4532): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4532): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4532): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4532): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4532): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4532): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4532): threadid=10: thread exiting with uncaught exception (group=0x417fed40)
E/AndroidRuntime( 4532): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4532): Process: com.android.keychain, PID: 4532
E/AndroidRuntime( 4532): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4532): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4532): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4532): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4532): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4532): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4532): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4532): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4532): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4532): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 1020): Can't write: system_server_wtf
E/DropBoxManagerService( 1020): java.io.FileNotFoundException: /data/system/dropbox/drop64.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1020): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1020): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1020): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1020): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10230)
E/DropBoxManagerService( 1020): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10135)
E/DropBoxManagerService( 1020): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10022)
E/DropBoxManagerService( 1020): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService( 1020): 	at android.util.Log$1.onTerribleFailure(Log.java:111)
E/DropBoxManagerService( 1020): 	at android.util.Log.wtf(Log.java:477)
E/DropBoxManagerService( 1020): 	at android.util.Log.wtf(Log.java:440)
E/DropBoxManagerService( 1020): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1046)
E/DropBoxManagerService( 1020): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:10124)
E/DropBoxManagerService( 1020): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:10180)
E/DropBoxManagerService( 1020): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:974)
E/DropBoxManagerService( 1020): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1538)
E/DropBoxManagerService( 1020): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 1020): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 1020): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1020): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1020): 	... 19 more
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
F/PackageManager( 1020): Unable to backup user packages state file, current changes will be lost at reboot
E/DropBoxManagerService( 1020): Can't write: system_app_crash
E/DropBoxManagerService( 1020): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1020): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1020): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1020): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1020): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1020): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1020): 	... 5 more
I/Launcher( 1311): Deferring update until onResume
E/DropBoxManagerService( 1020): Can't write: system_server_wtf
E/DropBoxManagerService( 1020): java.io.FileNotFoundException: /data/system/dropbox/drop65.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1020): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1020): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1020): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1020): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10230)
E/DropBoxManagerService( 1020): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10135)
E/DropBoxManagerService( 1020): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10022)
E/DropBoxManagerService( 1020): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService( 1020): 	at android.util.Log$1.onTerribleFailure(Log.java:111)
E/DropBoxManagerService( 1020): 	at android.util.Log.wtf(Log.java:477)
E/DropBoxManagerService( 1020): 	at android.util.Log.wtf(Log.java:440)
E/DropBoxManagerService( 1020): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1046)
E/DropBoxManagerService( 1020): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:10124)
E/DropBoxManagerService( 1020): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:10180)
E/DropBoxManagerService( 1020): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:974)
E/DropBoxManagerService( 1020): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1538)
E/DropBoxManagerService( 1020): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 1020): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 1020): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1020): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1020): 	... 19 more
I/Process ( 4532): Sending signal. PID: 4532 SIG: 9
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
F/PackageManager( 1020): Unable to backup user packages state file, current changes will be lost at reboot
E/DropBoxManagerService( 1020): Can't write: system_server_wtf
E/DropBoxManagerService( 1020): java.io.FileNotFoundException: /data/system/dropbox/drop68.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1020): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1020): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1020): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1020): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10230)
E/DropBoxManagerService( 1020): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10135)
E/DropBoxManagerService( 1020): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10022)
E/DropBoxManagerService( 1020): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService( 1020): 	at android.util.Log$1.onTerribleFailure(Log.java:111)
E/DropBoxManagerService( 1020): 	at android.util.Log.wtf(Log.java:477)
E/DropBoxManagerService( 1020): 	at android.util.Log.wtf(Log.java:440)
E/DropBoxManagerService( 1020): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1046)
E/DropBoxManagerService( 1020): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:10124)
E/DropBoxManagerService( 1020): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:10180)
E/DropBoxManagerService( 1020): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:974)
E/DropBoxManagerService( 1020): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1538)
E/DropBoxManagerService( 1020): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 1020): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 1020): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1020): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1020): 	... 19 more

```
