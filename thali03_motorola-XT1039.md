#### Test 549702617d40def_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4019): 
D/AndroidRuntime( 4019): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4019): CheckJNI is OFF
D/dalvikvm( 4019): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4019): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4019): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4019): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4019): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4019): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4019): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4019): failed to load memtrack module: -2
D/AndroidRuntime( 4019): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4019
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4035 uid=10512 gids={50512, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4019): Shutting down VM
D/dalvikvm( 4019): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4035): Binding Chromium to main looper Looper (main, tid 1) {424c7be0}
I/LibraryLoader( 4035): Expected native library version number "",actual native library version number ""
I/chromium( 4035): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4035): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44256dc0:true
I/Adreno-EGL( 4035): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4035): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4035): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4035): Local Branch: 
I/Adreno-EGL( 4035): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4035): Local Patches: NONE
I/Adreno-EGL( 4035): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4035): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4035): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4035): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4035): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4035): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4035): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4035): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4035): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4035): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4035): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4035): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4035): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4035): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4035): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4035): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4035): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4035): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4035): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4035): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4035): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4035): Enabling debug mode 0
,W/AwContents( 4035): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4035): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1019): Displayed com.test.thalitest/.MainActivity,cp,ca,457
I/ActivityManager( 1019): Displayed com.test.thalitest/.MainActivity: +429ms (total +457ms)
,D/JsMessageQueue( 4035): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4035): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x424cc180
,D/dalvikvm( 4035): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x424cc180
,D/jxcore_app_log( 4035): JniHelper::setJavaVM(0x41be3f78), pthread_self() = 1615579576
,D/JX-Cordova( 4035): jxcore cordova android initializing
,D/dalvikvm( 4035): GC_CONCURRENT freed 2745K, 17% free 14434K/17224K, paused 3ms+2ms, total 50ms
,D/dalvikvm( 4035): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 4035): GC_FOR_ALLOC freed 171K, 17% free 14444K/17224K, paused 25ms, total 25ms
,D/dalvikvm( 4035): GC_FOR_ALLOC freed 131K, 17% free 14459K/17224K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4035): Grow heap (frag case) to 16.244MB for 95956-byte allocation
,D/dalvikvm( 4035): GC_FOR_ALLOC freed 178K, 17% free 14493K/17320K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4035): Grow heap (frag case) to 16.323MB for 143930-byte allocation
,D/dalvikvm( 4035): GC_FOR_ALLOC freed 251K, 17% free 14540K/17464K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4035): Grow heap (frag case) to 16.438MB for 215890-byte allocation
,D/dalvikvm( 4035): GC_FOR_ALLOC freed 366K, 18% free 14614K/17676K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4035): Grow heap (frag case) to 16.613MB for 323830-byte allocation
,D/dalvikvm( 4035): GC_FOR_ALLOC freed 564K, 19% free 14735K/17996K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4035): Grow heap (frag case) to 16.885MB for 485740-byte allocation
,D/dalvikvm( 4035): GC_FOR_ALLOC freed 860K, 20% free 14911K/18472K, paused 26ms, total 26ms
,D/dalvikvm( 4035): GC_FOR_ALLOC freed 1277K, 18% free 15167K/18472K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4035): Grow heap (frag case) to 17.886MB for 1092904-byte allocation
,D/dalvikvm( 4035): GC_CONCURRENT freed 1771K, 21% free 15552K/19540K, paused 3ms+4ms, total 35ms
,D/dalvikvm( 4035): GC_FOR_ALLOC freed 266K, 21% free 15493K/19540K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4035): Grow heap (frag case) to 18.726MB for 1639352-byte allocation
,D/dalvikvm( 4035): GC_CONCURRENT freed 1741K, 25% free 16066K/21144K, paused 3ms+3ms, total 33ms
,D/dalvikvm( 4035): GC_FOR_ALLOC freed 1253K, 24% free 16118K/21144K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4035): Grow heap (frag case) to 20.118MB for 2459024-byte allocation
,D/dalvikvm( 4035): GC_CONCURRENT freed 1799K, 29% free 16931K/23548K, paused 4ms+4ms, total 52ms
,D/dalvikvm( 4035): GC_CONCURRENT freed 2503K, 28% free 17072K/23548K, paused 2ms+6ms, total 40ms
,D/dalvikvm( 4035): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 4035): GC_FOR_ALLOC freed 417K, 28% free 16987K/23548K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4035): Grow heap (frag case) to 22.139MB for 3688532-byte allocation
,D/dalvikvm( 4035): GC_CONCURRENT freed 2669K, 33% free 18204K/27152K, paused 5ms+5ms, total 60ms
,D/dalvikvm( 4035): GC_FOR_ALLOC freed 920K, 34% free 18069K/27152K, paused 29ms, total 29ms
,W/jxcore-log( 4035): Initializing JXcore engine
,W/jxcore-log( 4035): JXcore engine is ready
,D/dalvikvm( 4035): GC_CONCURRENT freed 335K, 24% free 20752K/27152K, paused 3ms+2ms, total 30ms
,D/dalvikvm( 4035): WAIT_FOR_CONCURRENT_GC blocked 23ms
,W/jxcore-log( 4035): Starting JXcore engine
,W/jxcore-log( 4035): Platform android
W/jxcore-log( 4035): 
,W/jxcore-log( 4035): Process ARCH arm
W/jxcore-log( 4035): 
,I/jxcore-log( 4035): JXcore Cordova bridge is ready!
I/jxcore-log( 4035): 
,W/jxcore-log( 4035): JXcore engine is started
,I/chromium( 4035): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4035): Toggling radios to true
I/jxcore-log( 4035): 
,D/BluetoothAdapter( 4035): enable(): BT is already enabled..!
D/WifiService( 1019): New client listening to asynchronous messages
D/WifiService( 1019): setWifiEnabled: true pid=4035, uid=10512
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1019): handleMessage: E msg.what=131145
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
I/jxcore-log( 4035): Radios toggled
I/jxcore-log( 4035): 
,I/wpa_supplicant( 1169): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  276): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  276):  STA Disconnected !!
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): get_property_value, Enter
I/MDMCTBK (  276): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  276): get_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  276): set_property_value, Enter
,I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  276): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  488): NL - Read 1000 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
D/TCMD    (  488): NL - Read 1000 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
D/TCMD    (  488): NL - Read 68 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
D/TCMD    (  488): NL - Read 68 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
,D/TCMD    (  488): Listening for incoming client connection request
,D/Tethering( 1019): InitialState.processMessage what=4
,V/ConnectivityService( 1019): WiFi NOT Tethered!
D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1019): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1019): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1019): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  273): Clearing all IP addresses on wlan0
D/TCMD    (  488): NL - Read 60 bytes from update socket.
D/TCMD    (  488): NL - ignore NL message, type = 21
,D/TCMD    (  488): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1019): connected time updated 301876
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1019): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1083): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1083): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1019): Attempting to switch to ETHERNET
,D/ConnectivityService( 1019): resetConnections(wlan0, 3)
D/NetUtils( 1019): android_net_utils_resetConnections in env=0x611dd008 clazz=0x62800001 iface=wlan0 mask=0x3
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine( 1019): DisconnectingState
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131146
D/WifiStateMachine( 1019): processMsg: DisconnectingState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147460
D/WifiStateMachine( 1019): processMsg: DisconnectingState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection lost
,D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1363): Read error: ssl=0x62dfbb28: I/O error during system call, Connection timed out
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  273): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,V/NativeCrypto( 1363): SSL shutdown failed: ssl=0x62dfbb28: I/O error during system call, Broken pipe
,D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1019): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectedState
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131216
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131216
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,I/ModemStatsDSDetect( 1299): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1299): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1299): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1019): Attempting to switch to ETHERNET
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1299): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1299): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1299): onReceive() - done, currentInetCondition=0
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
,D/TCMD    (  488): Listening for incoming client connection request
I/wpa_supplicant( 1169): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  276): Event received = Trying to associate with
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,E/wpa_supplicant( 1169): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,I/wpa_supplicant( 1169): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  488): NL - Read 312 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
D/TCMD    (  488): NL - Read 88 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/wpa_supplicant( 1169): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  488): NL - Read 68 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
D/TCMD    (  488): NL - Read 1000 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
,D/TCMD    (  488): Listening for incoming client connection request
I/wpa_supplicant( 1169): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  276): Event received = Associated with c0:ff:d4
D/TCMD    (  488): NL - Read 80 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
D/TCMD    (  488): NL - Read 80 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
D/TCMD    (  488): NL - Read 68 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1169): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1169): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  276): Event received = WPA: Key negotiation com
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  276): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  276):  STA Connected !!
D/TCMD    (  488): NL - Read 1000 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
,D/TCMD    (  488): Listening for incoming client connection request
E/MDMCTBK (  276): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  276): get_freq !!, resp=0
I/MDMCTBK (  276): get_freq !!, Strip data
I/MDMCTBK (  276): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): get_property_value, Enter
I/MDMCTBK (  276): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  276): get_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  276): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  276): set_property_value, Enter
,I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  276): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  276): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): get_property_value, Enter
I/MDMCTBK (  276): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  276): get_property_value, Exit
I/MDMCTBK (  276): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1202050224
I/MDMCTBK (  276): return from set_get_from_wpa_supplicant
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
,I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147459
,D/MDMCTBK (  276): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  276): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  276): , reply_len: 3, ret: 0
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection established
D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
E/MDMCTBK (  276): MdmCutbackHndler, resp=OK
E/MDMCTBK (  276): 
,D/MDMCTBK (  276): wifi_set_tx_pwr: Exit
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1019): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1019): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-39ms what=147462 obj=android.net.wifi.StateChangeResult@43680ed8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-32ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@43643da0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196612
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-6ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@426ff868 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@426ff868 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 c
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 2 c
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 3
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 3 3
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 6
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 4 6
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 f
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 5 f
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 1
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 6 1
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 0
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 7 0
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 fc
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 4 fc
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 10
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 5 10
D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 0c
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 6 0c
D/TCMD    (  488): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiP2pService( 1019): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@44a11eb8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@44a11eb8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@44a11eb8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: X
V/AlarmManager( 1019): sending alarm Alarm{4463d228 type 3 android}
,W/XTWiFiOS( 1274): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1568): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,W/XTWiFiOS( 1274): Active network info is not available
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/TelephonyProvider( 1248): Column apn id key is 'apn_id'
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: null, inetCondition= 0
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1274): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1274): Active network info is not available
,E/ActivityThread( 1568): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1568): Registering with Alarm Manager to restart CCE
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1248): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: null, inetCondition= 0
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/PollingManager( 1568): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1568): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1568): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1568): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1568): [debug] > CusSM.onRadioDown
,I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4124 uid=10030 gids={50030, 3003, 1028, 1015}
D/TelephonyProvider( 1248): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1248): Column apn id key is 'apn_id'
,D/TCMD    (  488): NL - Read 60 bytes from update socket.
D/TCMD    (  488): NL - ignore NL message, type = 20
,D/TCMD    (  488): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/dalvikvm( 1019): GC_EXPLICIT freed 23429K, 65% free 18070K/50952K, paused 5ms+14ms, total 166ms
,V/MmsConfig( 4124): mnc/mcc: 
V/MmsConfig( 4124): tag: bool value: enabledMMS - true
,V/MmsConfig( 4124): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4124): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4124): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4124): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4124): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4124): tag: int value: minMessageCountPerThread - 10
,V/MmsConfig( 4124): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4124): tag: int value: recipientLimit - 20
,V/MmsConfig( 4124): tag: bool value: enableMultipartSMS - true
,V/MmsConfig( 4124): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4124): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4124): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4124): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4124): tag: bool value: smsForceShowEncodingMenu - true
,V/MmsConfig( 4124): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4124): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4124): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4163 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1019): Killing 3813:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4163): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4163): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4163): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4163): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1019): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4176 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3858:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  278): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 22ms
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 18ms
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4189 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3874:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): DHCP successful
D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1019): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1019): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1019): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState enter
D/WifiStateMachine( 1019): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=151572
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState what=151572 NOT_HANDLED
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,V/WebViewChromiumFactoryProvider( 4189): Binding Chromium to main looper Looper (main, tid 1) {424c0780}
,I/LibraryLoader( 4189): Expected native library version number "",actual native library version number ""
,I/chromium( 4189): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4189): Initializing chromium process, renderers=0
,I/SBar.NetworkController( 1083): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,E/AudioManagerAndroid( 4189): BLUETOOTH permission is missing!
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=135190
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1019): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1019): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1019): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState enter
,D/WifiStateMachine( 1019): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
I/Adreno-EGL( 4189): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4189): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4189): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4189): Local Branch: 
I/Adreno-EGL( 4189): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4189): Local Patches: NONE
I/Adreno-EGL( 4189): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/WifiStateMachine( 1019): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1019): WiFi NOT Tethered!
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@425b9620
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/WifiStateMachine( 1019): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1019): handleMessage: X
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1019): WiFi NOT Tethered!
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@425b9620
I/ModemStatsDSDetect( 1299): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.NetworkController( 1083): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/ModemStatsDSDetect( 1299): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1299): onReceive() - done, currentInetCondition=0
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,I/ModemStatsDSDetect( 1299): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1299): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1299): onReceive() - done, currentInetCondition=0
,I/CheckinService( 1396): Checkin interval check for package: unspecified last checkin: 1451956812338 min interval config: 0 actual interval: 290318
,I/CheckinService( 1396): Checking schedule, now: 1451957102673 next: 1451956842311
,I/CheckinService( 1396): active receiver: enabled
,I/CheckinService( 1396): Preparing to send checkin request
,I/EventLogService( 1396): Accumulating logs since 1451956808803
,W/chromium( 4189): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/CheckinRequestBuilder( 1396): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1396): Failed to find provider info for com.google.android.wearable.settings
,W/GAV2    ( 4189): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4189): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1019): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4228 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4228): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4228): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4228): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4228): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4228): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4228): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4228): install
,I/MultiDex( 4228): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4228): loading existing secondary dex files
,I/MultiDex( 4228): load found 3 secondary dex files
,I/MultiDex( 4228): install done
,I/NSApplication( 4189): Starting up...
,D/dalvikvm( 4228): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4228): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4228): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4228): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4228): VFY: unable to resolve instance field 36
,D/dalvikvm( 4228): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4228): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4228): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4228): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4228): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4228): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4228): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x424c6d80
,D/dalvikvm( 4228): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x424c6d80
D/dalvikvm( 4228): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x424c6d80, skipping init
,D/dalvikvm( 4228): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x424c6d80
D/dalvikvm( 4228): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x424c6d80
,V/JNIHelp ( 4228): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ImageResourceManager( 3911): ImageResourceManager: uninitalized
,I/iu.Environment( 3911): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1019): Killing 3890:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/DEBUG   ( 1568): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1568): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1568): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1568): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1568): onServiceConnected()
D/GetNotificationsWS( 1568): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1568): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1568): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1568): unbindWebServices(): un-registering our AIDL callback...
,I/openssl ( 3934): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3934): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4163): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4163): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3911): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
D/dalvikvm( 4228): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x424c6d80
D/dalvikvm( 4228): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x424c6d80
,D/dalvikvm( 4228): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x424c6d80
,D/dalvikvm( 4228): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x424c6d80
,I/ProviderInstaller( 4228): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1227): callingUid 10022, callindPid: 1227
,D/LocationInitializer( 1396): Restart initialization of location
,E/MDM     ( 1227): [128] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1363): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1363): Proximity feature is not enabled.
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1227): No location to return for getLastLocation()
,W/FusedLocationProvider( 1227): location=null
,I/dalvikvm( 4228): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 4228): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4228): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4228): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4228): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4228): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4228): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4228): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4228): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4228): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 4228): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4228): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4228): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4228): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4228): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4228): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4228): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  281): Instantiating CDM.
,I/WVCdm   (  281): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  281): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
,D/DrmWidevineDash(  281): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  281): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb531a000
,E/DrmWidevineDash(  281): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb531a000
,D/DrmWidevineDash(  281): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  281): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  281): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  281): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  281): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=4089386044
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4228): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4228): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42714f28
D/dalvikvm( 4228): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42714f28
,D/dalvikvm( 4228): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42714f28, skipping init
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,D/ConnectivityService( 1019): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 4228): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4266): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4228): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4228): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 88ms
,I/Adreno-EGL( 4228): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4228): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4228): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4228): Local Branch: 
I/Adreno-EGL( 4228): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4228): Local Patches: NONE
I/Adreno-EGL( 4228): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4228): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4228): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4228): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4228): Local Branch: 
I/Adreno-EGL( 4228): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4228): Local Patches: NONE
I/Adreno-EGL( 4228): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 4228): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4228): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4228): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4228): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4228): Local Branch: 
I/Adreno-EGL( 4228): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4228): Local Patches: NONE
I/Adreno-EGL( 4228): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4228): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4228): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4228): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4228): Local Branch: 
I/Adreno-EGL( 4228): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4228): Local Patches: NONE
I/Adreno-EGL( 4228): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=937475160
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1396): Classify the device as Phone.
,I/CheckinTask( 1396): Sending checkin request (11684 bytes)
,D/WifiStateMachine( 1019): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/ConnectivityService( 1019): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1019):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,I/CheckinRequestBuilder( 1396): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1396): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1396): Classify the device as Phone.
,I/CheckinTask( 1396): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1396): Checking schedule, now: 1451957105601 next: 1452550175592
,I/CheckinService( 1396): active receiver: disabled
,D/CheckinService( 1396): Recording last checkin time for package unspecified as 1451957105618
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1274): No entry in secure settings for enhanced location services: false
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/PollingManager( 1568): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/PollingManager( 1568): now: 333671 ,futureTime: 74798589
,D/PollingManager( 1568): Polling alarm set to expire at: 74798589 Current Time: 333671
,E/ActivityThread( 1568): Failed to find provider info for com.motorola.blur.setupprovider
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/OtaApp  ( 1568): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1568): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1568): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1274): No entry in secure settings for enhanced location services: false
D/PollingManager( 1568): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering( 1019): MasterInitialState.processMessage what=3
D/OtaApp  ( 1568): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1568): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
D/TelephonyProvider( 1248): Column apn id key is 'apn_id'
D/PollingManager( 1568): now: 333703 ,futureTime: 74798589
D/PollingManager( 1568): Polling alarm set to expire at: 74798589 Current Time: 333703
D/TelephonyProvider( 1248): Column apn id key is 'apn_id'
,D/OtaApp  ( 1568): [debug] > CusSM.runStateMachine: server told to :continue
,E/ActivityThread( 1568): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1568): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/OtaApp  ( 1568): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1568): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1568): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1568): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/openssl ( 3934): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3934): Crypto mode 0 already enabled
D/TelephonyProvider( 1248): Column apn id key is 'apn_id'
D/OtaApp  ( 1568): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1568): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
D/GCM     ( 1363): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/OtaApp  ( 1568): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1568): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/MobileConnectivityChangeReceiver( 4163): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4163): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1568): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/TelephonyProvider( 1248): Column apn id key is 'apn_id'
,I/iu.Environment( 3911): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/DEBUG   ( 1568): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1568): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1568): bindWebServices(): registering our AIDL callback...
,D/dalvikvm( 3911): GC_FOR_ALLOC freed 606K, 5% free 16433K/17224K, paused 22ms, total 22ms
,D/EmailService.MarketingOptInSetter( 1568): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1568): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1568): onServiceConnected()
,D/GetNotificationsWS( 1568): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1568): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1568): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 3934): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3934): Crypto mode 0 already enabled
I/dalvikvm-heap( 3911): Grow heap (frag case) to 19.818MB for 1821008-byte allocation
,D/dalvikvm( 1019): GC_EXPLICIT freed 1089K, 65% free 17944K/50952K, paused 4ms+9ms, total 96ms
,D/MobileConnectivityChangeReceiver( 4163): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4163): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 3911): GC_FOR_ALLOC freed 28K, 5% free 18186K/19004K, paused 11ms, total 11ms
,I/iu.Environment( 3911): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/DEBUG   ( 1568): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1568): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1568): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1568): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1568): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1568): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1568): onServiceConnected()
,D/GetNotificationsWS( 1568): onServiceConnected(): Registered for remote service callbacks...
,D/OtaApp  ( 1568): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1568): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1568
,D/GetNotificationsWS( 1568): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1568): [info] > Updatetime from metadata: 10
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1568): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1568): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1568): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1568): [info] > Updatetime from metadata: 10
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1568): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1568): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1568): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1568): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1568
W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1568): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1568): [info] > Updatetime from metadata: 10
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1568): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1568): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1568): [info] > Updatetime from metadata: 10
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1568): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1568): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1568): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1568): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1019): Activity reported stop, but no longer stopping: ActivityRecord{42ebc178 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/LaunchCheckinHandler( 1019): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,139
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1299): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1299): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1083): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1299): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1299): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/GAV2    ( 4189): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1019): Killing 3835:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 4035): Test app app.js loaded
I/jxcore-log( 4035): 
,I/Choreographer( 4035): Skipped 682 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4035): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/IInputConnectionWrapper( 4035): showStatusIcon on inactive InputConnection
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/Launcher( 1311): Deferring update until onResume
,I/ActivityManager( 1019): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4326 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/Launcher( 1311): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/GCoreNlp( 1227): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4326): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4326): MmsConfig.loadMmsSettings
I/Babel   ( 4326): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4326): MmsConfig.loadFromDatabase
,E/Babel   ( 4326): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4326): MmsConfig.loadFromResources
,E/Babel   ( 4326): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4326): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4326): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1019): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4363 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1019): Killing 3452:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4383 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3934:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2319): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1019): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4402 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4124:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4363): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4402): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4402): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4402): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4402): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2319): UpdateCorporaTask done [took 198 ms] updated apps [took 198 ms] 
,I/dalvikvm( 4402): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4402): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4402): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4402): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
,W/dalvikvm( 4402): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4402): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4402): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4402): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4402): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4402): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4402): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4402): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4402): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4402): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4402): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4402): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4402): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4402): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4402): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4402): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4402): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4436 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4402): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 4402): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4402): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4402): Skipping gmscore version check
,D/Finsky  ( 4402): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4402): [1] Libraries$2.run: Finished loading 1 libraries.
,I/dalvikvm( 4402): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4402): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4402): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1019): Killing 4163:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/PackageBroadcastService( 1396): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 1396): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1396): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4436): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x424cd290, skipping init
I/openssl ( 4436): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4436): Crypto mode 0 already enabled
,I/ActivityManager( 1019): Killing 4176:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Finsky  ( 4402): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4402): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/dalvikvm( 1396): GC_CONCURRENT freed 1971K, 31% free 12002K/17224K, paused 4ms+4ms, total 39ms
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/Icing   ( 1396): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1396): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1203): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1451957114
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
,I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=0 what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1019): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1019): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1019): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1019): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1019): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{448ec620 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
,I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
,I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{4403ae70 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{443d41f0 type 3 android}
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 6 
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
,D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 7
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{44236140 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42cf5020 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{448e8648 type 0 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{446c5d88 type 1 com.android.deskclock}
,I/ActivityManager( 1019): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4480 uid=10015 gids={50015, 1028}
,I/EventLogService( 1396): Aggregate from 1451957102693 (log), 1451955122790 (data)
,I/ActivityManager( 1019): Killing 4189:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{440b9a20 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
,I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{44237da8 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
,I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42cff878 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{440b9af8 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{44657d48 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
,I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{442e1860 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
,I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{4441f340 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42d22020 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{44952d18 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43efc360 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
,I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{4365e1d8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{441d67e8 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/ModemStatsDSDetect( 1299): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1299): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1299): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{44244308 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
,I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 1019): GC_CONCURRENT freed 1956K, 65% free 18113K/50952K, paused 11ms+9ms, total 106ms
,V/AlarmManager( 1019): sending alarm Alarm{42e49900 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{44a15a00 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{44967110 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{44676450 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{442443e0 type 1 com.android.deskclock}
,V/AlarmManager( 1019): sending alarm Alarm{44657290 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{44614888 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{443dc168 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{442444b8 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{44244590 type 2 android}
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,D/dalvikvm( 1363): GC_EXPLICIT freed 663K, 41% free 10321K/17224K, paused 2ms+4ms, total 35ms
,D/dalvikvm( 1227): GC_CONCURRENT freed 1681K, 33% free 11599K/17224K, paused 3ms+10ms, total 38ms
,V/AlarmManager( 1019): sending alarm Alarm{4437d558 type 2 android}
,V/AlarmManager( 1019): sending alarm Alarm{443c32e0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{430a1030 type 3 android}
,I/ProcessStatsService( 1019): Prepared write state in 24ms
,I/ProcessStatsService( 1019): Prepared write state in 34ms
,I/ProcessStatsService( 1019): Pruning old procstats: /data/system/procstats/state-2016-01-04-06-44-00.bin
,V/AlarmManager( 1019): sending alarm Alarm{42a04900 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42d41408 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42996a68 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4261e480 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42d9dfe0 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms),V/AlarmManager( 1019): sending alarm Alarm{442445e0 type 3 android}
V/AlarmManager( 1019): sending alarm Alarm{443afde0 type 3 com.google.android.gms}
V/AlarmManager( 1019): sending alarm Alarm{443afe30 type 2 com.motorola.ccc.cce}
V/AlarmManager( 1019): sending alarm Alarm{42f21cf8 type 2 com.google.android.gms}
D/CCE     ( 1568): Registering with Alarm Manager to restart CCE
V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/dalvikvm( 1363): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 1363): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 1363): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
D/dalvikvm( 1363): VFY: replacing opcode 0x1f at 0x0011
I/dalvikvm( 1363): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1363): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/dalvikvm( 1363): VFY: replacing opcode 0x6e at 0x003d
D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/ModemStatsDSDetect( 1299): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1299): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1299): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/AndroidRuntime( 4572): 
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
I/ActivityManager( 1019): Killing 4228:com.google.android.gms.unstable/u0a22 (adj 15): empty for 1801s
W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/AndroidRuntime( 4572): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10512 user=-1: uninstall pkg
I/ActivityManager( 1019): Killing 4035:com.test.thalitest/u0a512 (adj 9): stop com.test.thalitest
W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/WindowState( 1019): WIN DEATH: Window{4498cfb0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1019): Client connection lost with reason: 4
I/ActivityManager( 1019):   Force finishing activity ActivityRecord{44988608 u0 com.test.thalitest/.MainActivity t3}
W/PackageSettings( 1019): Skipping PackageSetting{4278b330 com.example.hello/10509} due to missing metadata
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10512 user=0: pkg removed
D/dalvikvm( 2319): GC_EXPLICIT freed 2678K, 44% free 9776K/17224K, paused 2ms+3ms, total 88ms
D/dalvikvm( 1019): GC_EXPLICIT freed 1272K, 65% free 17990K/50940K, paused 5ms+11ms, total 97ms
D/dalvikvm( 1311): GC_EXPLICIT freed 3236K, 33% free 11593K/17224K, paused 2ms+24ms, total 94ms
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
W/GeofencerStateMachine( 1227): Ignoring removeGeofence because network location is disabled.
I/LatinIME:LogUtils( 1203): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1203): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/Launcher( 1311): Deferring update until onResume
D/dalvikvm( 1396): GC_EXPLICIT freed 684K, 31% free 11930K/17224K, paused 4ms+19ms, total 148ms
W/SQLiteConnectionPool( 1396): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
D/dalvikvm( 2284): GC_EXPLICIT freed 5570K, 44% free 9651K/17224K, paused 3ms+5ms, total 60ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
D/VoicemailCleanupService( 4363): Cleaning up data for package: com.test.thalitest
I/LatinIME:LogUtils( 1203): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1451958911
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/Launcher( 1311): Deferring update until onResume
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/InternalIcingCorporaPro( 2319): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10512 #1
I/ActivityManager( 1019): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4605 uid=10059 gids={50059, 3003, 1028, 1015}
I/LatinIME:LogUtils( 1203): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1451958911
I/InternalIcingCorporaPro( 2319): UpdateCorporaTask done [took 88 ms] updated apps [took 88 ms] 
D/dalvikvm( 1019): GC_EXPLICIT freed 713K, 65% free 18064K/50940K, paused 21ms+13ms, total 203ms
D/AndroidRuntime( 4572): Shutting down VM
D/dalvikvm( 4572): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
W/ActiveOrDefaultContextProvider( 4605): Missing scope.enter somewhere. Returning default context
I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4629 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/GAV2    ( 4605): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 4629): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/PackageBroadcastService( 1396): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1396): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1396): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1396): Module APK com.google.android.play.games already loaded
I/dalvikvm( 4402): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4402): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4402): VFY: replacing opcode 0x6e at 0x0013
I/LocationSettingsChecker( 1396): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1396): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1396): Module APK com.google.android.play.games already loaded
D/dalvikvm( 3911): GC_FOR_ALLOC freed 22K, 4% free 20464K/21204K, paused 38ms, total 39ms
E/NetworkScheduler.SchedulerReceiver( 1363): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1363): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
W/FileUtils( 1396): Failed to chmod(/data/data/com.google.android.gms/databases/phenotype.db): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
I/ActivityManager( 1019): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4668 uid=10058 gids={50058}
E/SQLiteDatabase( 1396): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1396): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1396): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1396): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1396): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1396): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1396): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1396): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1396): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1396): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1396): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1396): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1396): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1396): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1396): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1396): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1396): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1396): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1396): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1396): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1396): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1396): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1396): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1396): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GMPM-SVC( 1396): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
E/SQLiteLog( 1396): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteOpenHelper( 1396): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1396): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1396): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1396): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1396): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1396): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1396): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1396): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1396): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 1396): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 1396): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1396): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 1396): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1396): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1396): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1396): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1396): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1396): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1396): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1396): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1396): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1396): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 1396): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SharedPreferencesImpl( 1396): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
D/dalvikvm(  278): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 22ms
E/SQLiteLog( 1396): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 1396): threadid=54: thread exiting with uncaught exception (group=0x41bf5d40)
I/Icing   ( 1396): doRemovePackageData com.test.thalitest
W/SQLiteOpenHelper( 1396): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1396): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1396): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1396): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
W/FileUtils( 1396): Failed to chmod(/data/data/com.google.android.gms/files): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
D/gH_CompatibleDatabase( 1396): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 1396): threadid=51: thread exiting with uncaught exception (group=0x41bf5d40)
I/Process ( 1396): Sending signal. PID: 1396 SIG: 9
E/AndroidRuntime( 1396): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 1396): Process: com.google.android.gms, PID: 1396
E/AndroidRuntime( 1396): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1396): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1396): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1396): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1396): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1396): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1396): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1396): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 1396): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 1396): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 1396): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 1396): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1396): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1396): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1396): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 22ms
E/SQLiteDatabase( 4629): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4629): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4629): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4629): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4629): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4629): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4629): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4629): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4629): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4629): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4629): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4629): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4629): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4629): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4629): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4629): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4629): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4629): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4629): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4629): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4629): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4629): threadid=10: thread exiting with uncaught exception (group=0x41bf5d40)
I/ActivityManager( 1019): Process com.google.android.gms (pid 1396) has died.
D/WifiService( 1019): Client connection lost with reason: 4
W/ActivityManager( 1019): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager( 1019): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager( 1019): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager( 1019): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
W/ActivityManager( 1019): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager( 1019): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1000ms
W/ActivityManager( 1019): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.UpdateIcingCorporaService in 11000ms
W/ActivityManager( 1019): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 21000ms
E/AndroidRuntime( 4629): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4629): Process: com.android.keychain, PID: 4629
E/AndroidRuntime( 4629): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4629): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4629): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4629): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4629): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4629): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4629): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4629): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4629): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4629): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4629): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4629): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4629): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4629): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4629): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4629): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4629): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4629): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4629): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4629): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 20ms
I/Process ( 4629): Sending signal. PID: 4629 SIG: 9
E/DropBoxManagerService( 1019): Can't write: system_app_crash
E/DropBoxManagerService( 1019): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager( 1019): Process com.android.keychain (pid 4629) has died.
W/ActivityManager( 1019): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 30981ms
D/Documents( 4668): Loading roots for com.android.providers.downloads.documents

```
