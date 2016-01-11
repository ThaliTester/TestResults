#### Test 549702617cfd775_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4160): 
D/AndroidRuntime( 4160): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4160): CheckJNI is OFF
D/dalvikvm( 4160): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4160): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4160): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4160): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4160): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4160): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4160): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4160): failed to load memtrack module: -2
D/AndroidRuntime( 4160): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1020): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4160
W/WindowManager( 1020): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1020): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4176 uid=10538 gids={50538, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4160): Shutting down VM
D/dalvikvm( 4160): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
D/dalvikvm(  278): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 21ms
W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 19ms
V/WebViewChromiumFactoryProvider( 4176): Binding Chromium to main looper Looper (main, tid 1) {42695990}
I/LibraryLoader( 4176): Expected native library version number "",actual native library version number ""
I/chromium( 4176): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4176): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1020): Message: 20
D/BluetoothManagerService( 1020): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@442c91c0:true
I/Adreno-EGL( 4176): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4176): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4176): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4176): Local Branch: 
I/Adreno-EGL( 4176): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4176): Local Patches: NONE
I/Adreno-EGL( 4176): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4176): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4176): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4176): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4176): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4176): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4176): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4176): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4176): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4176): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4176): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4176): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4176): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4176): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4176): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4176): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4176): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4176): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4176): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4176): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4176): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4176): Enabling debug mode 0
,W/AwContents( 4176): nativeOnDraw failed; clearing to background color.
,W/AwContents( 4176): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1020): Displayed com.test.thalitest/.MainActivity,cp,ca,377
I/ActivityManager( 1020): Displayed com.test.thalitest/.MainActivity: +345ms (total +378ms)
,W/IInputConnectionWrapper( 4176): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 4176): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4176): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42699e40
,D/dalvikvm( 4176): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42699e40
,D/jxcore_app_log( 4176): JniHelper::setJavaVM(0x41daef78), pthread_self() = 1614142288
,D/JX-Cordova( 4176): jxcore cordova android initializing
,D/dalvikvm( 4176): GC_CONCURRENT freed 2791K, 17% free 14382K/17224K, paused 3ms+1ms, total 66ms
,D/dalvikvm( 4176): WAIT_FOR_CONCURRENT_GC blocked 37ms
,D/dalvikvm( 4176): GC_FOR_ALLOC freed 166K, 17% free 14401K/17224K, paused 28ms, total 28ms
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 4176): GC_FOR_ALLOC freed 116K, 17% free 14431K/17224K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4176): Grow heap (frag case) to 16.216MB for 95956-byte allocation
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
,D/dalvikvm( 4176): GC_FOR_ALLOC freed 195K, 17% free 14450K/17320K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4176): Grow heap (frag case) to 16.281MB for 143930-byte allocation
,D/dalvikvm( 4176): GC_FOR_ALLOC freed 253K, 17% free 14497K/17464K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4176): Grow heap (frag case) to 16.396MB for 215890-byte allocation
,D/dalvikvm( 4176): GC_FOR_ALLOC freed 368K, 18% free 14571K/17676K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4176): Grow heap (frag case) to 16.571MB for 323830-byte allocation
,D/dalvikvm( 4176): GC_FOR_ALLOC freed 570K, 19% free 14692K/17996K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4176): Grow heap (frag case) to 16.843MB for 485740-byte allocation
,D/dalvikvm( 4176): GC_FOR_ALLOC freed 865K, 20% free 14868K/18472K, paused 26ms, total 26ms
,D/dalvikvm( 4176): GC_FOR_ALLOC freed 1282K, 19% free 15123K/18472K, paused 27ms, total 28ms
,I/dalvikvm-heap( 4176): Grow heap (frag case) to 17.843MB for 1092904-byte allocation
,D/dalvikvm( 4176): GC_CONCURRENT freed 1768K, 21% free 15509K/19540K, paused 2ms+4ms, total 48ms
,D/dalvikvm( 4176): GC_FOR_ALLOC freed 287K, 21% free 15440K/19540K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4176): Grow heap (frag case) to 18.674MB for 1639352-byte allocation
,D/dalvikvm( 4176): GC_CONCURRENT freed 1745K, 25% free 16039K/21144K, paused 2ms+4ms, total 44ms
,D/dalvikvm( 4176): GC_FOR_ALLOC freed 1261K, 24% free 16075K/21144K, paused 29ms, total 30ms
,I/dalvikvm-heap( 4176): Grow heap (frag case) to 20.076MB for 2459024-byte allocation
,D/dalvikvm( 4176): GC_CONCURRENT freed 182K, 23% free 18359K/23548K, paused 5ms+4ms, total 34ms
,D/dalvikvm( 4176): GC_CONCURRENT freed 4392K, 28% free 17086K/23548K, paused 1ms+7ms, total 48ms
,D/dalvikvm( 4176): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 4176): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 4176): GC_FOR_ALLOC freed 163K, 28% free 16978K/23548K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4176): Grow heap (frag case) to 22.130MB for 3688532-byte allocation
,D/dalvikvm( 4176): GC_CONCURRENT freed 439K, 25% free 20497K/27152K, paused 4ms+6ms, total 72ms
,D/dalvikvm( 4176): GC_FOR_ALLOC freed 3094K, 34% free 18017K/27152K, paused 28ms, total 29ms
,W/jxcore-log( 4176): Initializing JXcore engine
,W/jxcore-log( 4176): JXcore engine is ready
,D/dalvikvm( 4176): GC_CONCURRENT freed 332K, 24% free 20682K/27152K, paused 2ms+3ms, total 35ms
,D/dalvikvm( 4176): WAIT_FOR_CONCURRENT_GC blocked 28ms
,W/jxcore-log( 4176): Starting JXcore engine
,W/jxcore-log( 4176): Platform android
W/jxcore-log( 4176): 
,W/jxcore-log( 4176): Process ARCH arm
W/jxcore-log( 4176): 
,I/jxcore-log( 4176): JXcore Cordova bridge is ready!
I/jxcore-log( 4176): 
,W/jxcore-log( 4176): JXcore engine is started
,I/chromium( 4176): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4176): Toggling radios to true
I/jxcore-log( 4176): 
,D/BluetoothAdapter( 4176): enable(): BT is already enabled..!
D/WifiService( 1020): New client listening to asynchronous messages
D/WifiService( 1020): setWifiEnabled: true pid=4176, uid=10538
,E/WifiService( 1020): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1020): handleMessage: E msg.what=131145
D/WifiStateMachine( 1020): processMsg: ConnectedState
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
I/jxcore-log( 4176): Radios toggled
I/jxcore-log( 4176): 
I/jxcore-log( 4176): My device name is: motorola-XT1039
I/jxcore-log( 4176): 
,I/wpa_supplicant( 1171): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
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
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  393): NL - Read 1000 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
,D/TCMD    (  393): Listening for incoming client connection request
D/TCMD    (  393): NL - Read 1000 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
D/TCMD    (  393): Listening for incoming client connection request
D/TCMD    (  393): NL - Read 68 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
D/TCMD    (  393): Listening for incoming client connection request
D/TCMD    (  393): NL - Read 68 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
D/TCMD    (  393): Listening for incoming client connection request
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  276): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
D/WifiStateMachine( 1020): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1020): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1020): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1020): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
,D/Tethering( 1020): InitialState.processMessage what=4
V/ConnectivityService( 1020): WiFi NOT Tethered!
,D/Tethering( 1020): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiP2pService( 1020): InactiveState{ when=-15ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=-15ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  273): Clearing all IP addresses on wlan0
D/TCMD    (  393): NL - Read 60 bytes from update socket.
D/TCMD    (  393): NL - ignore NL message, type = 21
,D/TCMD    (  393): Listening for incoming client connection request
,D/WifiStateMachine( 1020): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1020): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1020): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1020): connected time updated 343200
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1020): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1020): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,I/SBar.NetworkController( 1082): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
D/ConnectivityService( 1020): Attempting to switch to mobile
D/ConnectivityService( 1020): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1020): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1082): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/ConnectivityService( 1020): resetConnections(wlan0, 3)
D/NetUtils( 1020): android_net_utils_resetConnections in env=0x61189120 clazz=0x61200001 iface=wlan0 mask=0x3
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1020): invokeEnterMethods: DisconnectingState
D/WifiStateMachine( 1020): DisconnectingState
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131146
D/WifiStateMachine( 1020): processMsg: DisconnectingState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147460
D/WifiStateMachine( 1020): processMsg: DisconnectingState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): Network connection lost
D/WifiStateMachine( 1020): Stopping DHCP and clearing IP
D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
V/NativeCrypto( 1359): Read error: ssl=0x62f91a18: I/O error during system call, Connection timed out
V/NativeCrypto( 1359): SSL shutdown failed: ssl=0x62f91a18: I/O error during system call, Broken pipe
,D/WifiP2pService( 1020): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  273): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1020): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1020): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1020): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine( 1020): invokeEnterMethods: DisconnectedState
,D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1020): handleMessage: X
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
,D/WifiStateMachine( 1020): processMsg: DisconnectedState
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
,D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=false
,I/ModemStatsDSDetect( 1239): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1020): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1239): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1239): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1020): Attempting to switch to mobile
D/ConnectivityService( 1020): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1020): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=false
,I/ModemStatsDSDetect( 1239): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1239): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1239): onReceive() - done, currentInetCondition=0
,I/wpa_supplicant( 1171): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  276): Event received = Trying to associate with
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  393): NL - Read 56 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
D/TCMD    (  393): Listening for incoming client connection request
D/WifiStateMachine( 1020): handleMessage: E msg.what=147461
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
,D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,E/wpa_supplicant( 1171): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
,D/TCMD    (  393): NL - Read 312 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
D/TCMD    (  393): Listening for incoming client connection request
I/wpa_supplicant( 1171): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  393): NL - Read 192 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
D/TCMD    (  393): Listening for incoming client connection request
,I/wpa_supplicant( 1171): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  393): NL - Read 68 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
D/TCMD    (  393): Listening for incoming client connection request
D/TCMD    (  393): NL - Read 1000 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
,D/TCMD    (  393): Listening for incoming client connection request
I/wpa_supplicant( 1171): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  276): Event received = Associated with c0:ff:d4
D/TCMD    (  393): NL - Read 80 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
D/TCMD    (  393): Listening for incoming client connection request
D/TCMD    (  393): NL - Read 80 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
D/TCMD    (  393): Listening for incoming client connection request
D/TCMD    (  393): NL - Read 68 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
,D/TCMD    (  393): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/Tethering( 1020): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/WifiStateMachine( 1020): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1171): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1171): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  276): Event received = WPA: Key negotiation com
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  276): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  276):  STA Connected !!
D/TCMD    (  393): NL - Read 1000 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
,D/TCMD    (  393): Listening for incoming client connection request
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
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1020): processMsg: ConnectModeState
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
I/MDMCTBK (  276): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1221362816
I/MDMCTBK (  276): return from set_get_from_wpa_supplicant
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,D/Tethering( 1020): sendTetherStateChangedBroadcast 1, 0, 0
,D/MDMCTBK (  276): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  276): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  276): , reply_len: 3, ret: 0
E/MDMCTBK (  276): MdmCutbackHndler, resp=OK
E/MDMCTBK (  276): 
D/MDMCTBK (  276): wifi_set_tx_pwr: Exit
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147459
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): Network connection established
,D/WifiStateMachine( 1020): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine( 1020): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1020): invokeExitMethods: DisconnectedState
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1020): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1020): invokeEnterMethods: ObtainingIpState
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-13ms what=147462 obj=android.net.wifi.StateChangeResult@440fdb30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131101
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-9ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@440fe5d8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=196612
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-2ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1020): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1020): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4275acc0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4275acc0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): handleMessage: X
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 c
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 6 c
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 3
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 7 3
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 0
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 8 0
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 f
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 9 f
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 11 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 11 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  393): NL - Read 56 bytes from update socket.
D/TCMD    (  393): NL - message type is RTM_NEWLINK
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2
D/TCMD    (  393): Listening for incoming client connection request
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 0c
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 3 0c
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 fe
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 4 fe
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 64
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 5 64
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 fc
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 6 fc
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiP2pService( 1020): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@440cc320 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@440cc320 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): DefaultState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@440cc320 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): handleMessage: E msg.what=147461
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1020): handleMessage: X
,D/TCMD    (  393): NL - Read 60 bytes from update socket.
D/TCMD    (  393): NL - ignore NL message, type = 20
,D/TCMD    (  393): Listening for incoming client connection request
D/WifiStateMachine( 1020): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1020): handleMessage: E msg.what=131215
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-4ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1020): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): DHCP successful
D/WifiStateMachine( 1020): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1020): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1020): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1020): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1020): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1020): VerifyingLinkState enter
D/WifiStateMachine( 1020): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=151572
D/WifiStateMachine( 1020): processMsg: VerifyingLinkState
D/WifiStateMachine( 1020): VerifyingLinkState what=151572 NOT_HANDLED
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1082): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=135190
D/WifiStateMachine( 1020): processMsg: VerifyingLinkState
D/WifiStateMachine( 1020): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1020): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1020): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
,D/WifiStateMachine( 1020): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1020): CaptivePortalCheckState enter
,D/WifiStateMachine( 1020): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1020): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1020): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1020): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/ConnectivityService( 1020): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131092
D/WifiStateMachine( 1020): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1020): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiStateMachine( 1020): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService( 1020): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
V/ConnectivityService( 1020): WiFi NOT Tethered!
,E/ConnectivityService( 1020): Unexpected mtu value: android.net.wifi.WifiStateTracker@4278f568
I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/WifiStateMachine( 1020): transitionTo: destState=ConnectedState
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
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): handleMessage: X
,I/SBar.NetworkController( 1082): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
I/ModemStatsDSDetect( 1239): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1239): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1239): onReceive() - done, currentInetCondition=0
,I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService( 1020): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1020): WiFi NOT Tethered!
E/ConnectivityService( 1020): Unexpected mtu value: android.net.wifi.WifiStateTracker@4278f568
,D/ConnectivityService( 1020): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true,
I/ModemStatsDSDetect( 1239): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1239): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1239): onReceive() - done, currentInetCondition=0
,D/Tethering( 1020): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/CaptivePortalTracker( 1020): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1020): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/PollingManager( 1558): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
W/XTWiFiOS( 1278): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1082): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1270): Column apn id key is 'apn_id'
,W/XTWiFiOS( 1278): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/Tethering( 1020): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1020): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1270): Column apn id key is 'apn_id'
,E/ActivityThread( 1558): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1558): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1558): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1558): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1558): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 1558): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1558): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1270): Column apn id key is 'apn_id'
,I/openssl ( 4088): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4088): Crypto mode 0 already enabled
,I/ActivityManager( 1020): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4296 uid=10030 gids={50030, 3003, 1028, 1015}
,V/AlarmManager( 1020): sending alarm Alarm{448575c8 type 3 android}
,D/dalvikvm( 1020): GC_EXPLICIT freed 23389K, 62% free 18101K/47288K, paused 4ms+10ms, total 141ms
,D/TelephonyProvider( 1270): Column apn id key is 'apn_id'
,V/MmsConfig( 4296): mnc/mcc: 
V/MmsConfig( 4296): tag: bool value: enabledMMS - true
,V/MmsConfig( 4296): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4296): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4296): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4296): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4296): tag: int value: defaultMMSMessagesPerThread - 50
,V/MmsConfig( 4296): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4296): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4296): tag: int value: recipientLimit - 20
V/MmsConfig( 4296): tag: bool value: enableMultipartSMS - true
,V/MmsConfig( 4296): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4296): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4296): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4296): tag: int value: maxSubjectLength - 80
,V/MmsConfig( 4296): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4296): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4296): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4296): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1020): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4320 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1020): Killing 3933:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4320): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4320): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4320): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4320): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1020): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4333 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 3999:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1376): Checkin interval check for package: unspecified last checkin: 1452520827549 min interval config: 0 actual interval: 332724
,I/CheckinService( 1376): Checking schedule, now: 1452521160283 next: 1452520857527
,I/CheckinService( 1376): active receiver: enabled
,I/CheckinService( 1376): Preparing to send checkin request
,I/EventLogService( 1376): Accumulating logs since 1452520823977
,I/CheckinRequestBuilder( 1376): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1376): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1020): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4347 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 4015:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ConnectivityService( 1020): NetTransition Wakelock for ConnectedState released by timeout
,V/WebViewChromiumFactoryProvider( 4347): Binding Chromium to main looper Looper (main, tid 1) {4268deb8}
,I/LibraryLoader( 4347): Expected native library version number "",actual native library version number ""
,I/chromium( 4347): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4347): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4347): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4347): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4347): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4347): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4347): Local Branch: 
I/Adreno-EGL( 4347): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4347): Local Patches: NONE
I/Adreno-EGL( 4347): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1020): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4373 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/chromium( 4347): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/dalvikvm( 4373): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4373): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4373): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4373): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4373): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4373): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4373): install
,W/GAV2    ( 4347): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/MultiDex( 4373): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4373): loading existing secondary dex files
,I/MultiDex( 4373): load found 3 secondary dex files
,I/MultiDex( 4373): install done
,E/cutils  (  264): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  264): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4347): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/dalvikvm( 4373): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4373): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4373): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 4373): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4373): VFY: unable to resolve instance field 36
,D/dalvikvm( 4373): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4373): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4373): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4373): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4373): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4373): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4373): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42694ba8
,D/dalvikvm( 4373): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42694ba8
,D/dalvikvm( 4373): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42694ba8, skipping init
D/dalvikvm( 4373): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42694ba8
D/dalvikvm( 4373): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42694ba8
,V/JNIHelp ( 4373): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4373): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42694ba8
,D/dalvikvm( 4373): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42694ba8
D/dalvikvm( 4373): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42694ba8
,D/dalvikvm( 4373): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42694ba8
,I/NSApplication( 4347): Starting up...
,I/ProviderInstaller( 4373): Installed default security provider GmsCore_OpenSSL
,I/ImageResourceManager( 4060): ImageResourceManager: uninitalized
,I/iu.Environment( 4060): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1020): Killing 4034:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/openssl ( 4088): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4088): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4320): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4320): onReceive CONNECTIVITY_CHANGE networkType=1
I/dalvikvm( 4373): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4373): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4373): VFY: replacing opcode 0x6e at 0x00ce
,I/dalvikvm( 4373): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4373): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4373): VFY: replacing opcode 0x6e at 0x000d
,I/iu.Environment( 4060): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/DEBUG   ( 1558): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1558): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1558): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1558): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1558): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1558): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1558): onServiceConnected()
D/GetNotificationsWS( 1558): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1558): unbindWebServices(): un-registering our AIDL callback...
I/dalvikvm( 4373): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4373): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4373): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4373): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4373): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4373): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4373): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4373): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4373): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4373): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4373): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WearableService( 1226): callingUid 10022, callindPid: 1226
,D/LocationInitializer( 1376): Restart initialization of location
,E/MDM     ( 1226): [130] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1226): No location to return for getLastLocation()
,W/FusedLocationProvider( 1226): location=null
,D/WVCdm   (  281): Instantiating CDM.
,I/WVCdm   (  281): Level3 Library Nov 20 2013 18:09:31
D/AuthorizationBluetoothService( 1359): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1359): Proximity feature is not enabled.
,D/DrmWidevineDash(  281): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  281): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  281): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fdd000
,E/DrmWidevineDash(  281): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fdd000
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DrmWidevineDash(  281): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  281): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  281): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  281): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  281): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
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
D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=4035319599
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4373): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4373): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4287fc90
,D/dalvikvm( 4373): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4287fc90
,D/dalvikvm( 4373): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4287fc90, skipping init
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=2205967283
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,W/Settings( 4373): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4373): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4419): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4373): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4373): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 100ms
,I/Adreno-EGL( 4373): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4373): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4373): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4373): Local Branch: 
I/Adreno-EGL( 4373): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4373): Local Patches: NONE
I/Adreno-EGL( 4373): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4373): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4373): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4373): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4373): Local Branch: 
I/Adreno-EGL( 4373): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4373): Local Patches: NONE
I/Adreno-EGL( 4373): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4373): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4373): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4373): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4373): Local Branch: 
I/Adreno-EGL( 4373): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4373): Local Patches: NONE
I/Adreno-EGL( 4373): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4373): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4373): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4373): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4373): Local Branch: 
I/Adreno-EGL( 4373): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4373): Local Patches: NONE
I/Adreno-EGL( 4373): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/Tethering( 1020): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1020): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1270): Column apn id key is 'apn_id'
,W/XTWiFiOS( 1278): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1558): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/PollingManager( 1558): now: 375519 ,futureTime: 26068211
,D/PollingManager( 1558): Polling alarm set to expire at: 26068211 Current Time: 375519
,E/ActivityThread( 1558): Failed to find provider info for com.motorola.blur.setupprovider
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/OtaApp  ( 1558): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1558): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1558): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/Tethering( 1020): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1020): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1278): No entry in secure settings for enhanced location services: false
,D/TelephonyProvider( 1270): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/PollingManager( 1558): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/PollingManager( 1558): now: 375540 ,futureTime: 26068211
,D/PollingManager( 1558): Polling alarm set to expire at: 26068211 Current Time: 375541
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/OtaApp  ( 1558): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1558): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1558): publish the event [tag = MOT_OTA event name = LOG]
,I/openssl ( 4088): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4088): Crypto mode 0 already enabled
,E/ActivityThread( 1558): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1558): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1558): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1558): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1558): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1558): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1558): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1558): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1558): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1558): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm( 1558): GC_CONCURRENT freed 1941K, 38% free 10741K/17224K, paused 3ms+3ms, total 30ms
,D/OtaApp  ( 1558): [debug] > CusSM.runStateMachine: server told to :continue
,D/TelephonyProvider( 1270): Column apn id key is 'apn_id'
,D/OtaApp  ( 1558): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1558): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/CheckinRequestBuilder( 1376): Classify the device as Phone.
,D/MobileConnectivityChangeReceiver( 4320): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4320): onReceive CONNECTIVITY_CHANGE networkType=1
,D/TelephonyProvider( 1270): Column apn id key is 'apn_id'
,I/iu.Environment( 4060): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1376): Checkin interval check for package: unspecified last checkin: 1452520827549 min interval config: 0 actual interval: 335049
,V/NativeCrypto( 1376): SSL shutdown failed: ssl=0x6bf20900: I/O error during system call, Connection timed out
,D/DEBUG   ( 1558): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1558): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1558): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1558): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1558): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1558): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1558): onServiceConnected()
,D/GetNotificationsWS( 1558): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1558): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4088): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4088): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4320): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4320): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 4060): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1376): Checkin interval check for package: unspecified last checkin: 1452520827549 min interval config: 0 actual interval: 335115
,D/DEBUG   ( 1558): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1558): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1558): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1558): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1558): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/dalvikvm( 4060): GC_FOR_ALLOC freed 624K, 5% free 16434K/17224K, paused 27ms, total 33ms
D/GetNotificationsWS( 1558): onServiceConnected()
,D/GetNotificationsWS( 1558): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1558): ServiceHandler.handleMessage: mWaitCount=0
,I/dalvikvm-heap( 4060): Grow heap (frag case) to 19.818MB for 1821008-byte allocation
,D/OtaApp  ( 1558): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1558): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1020): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1558
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1558): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1558): [info] > Updatetime from metadata: 10
,D/Checkin ( 1558): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1558): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1558): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1558): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1558): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1558): [info] > Updatetime from metadata: 10
,D/Checkin ( 1558): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1558): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1558): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1558): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1558): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1558): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1020): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1558
W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1558): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/OtaApp  ( 1558): [info] > Updatetime from metadata: 10
D/Checkin ( 1558): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1558): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1558): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1558): publish the event [tag = MOT_OTA event name = LOG]
I/LaunchCheckinHandler( 1020): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,104
,I/CheckinTask( 1376): Sending checkin request (11751 bytes)
,D/dalvikvm( 1020): GC_EXPLICIT freed 724K, 62% free 18037K/47288K, paused 3ms+9ms, total 92ms
,I/OtaApp  ( 1558): [info] > Updatetime from metadata: 10
,D/Checkin ( 1558): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1558): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1558): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1558): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1558): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1558): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1020): Activity reported stop, but no longer stopping: ActivityRecord{426ccea8 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/CheckinRequestBuilder( 1376): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1376): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1359): GC_EXPLICIT freed 1422K, 41% free 10330K/17224K, paused 2ms+4ms, total 32ms
,D/WifiStateMachine( 1020): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1020): handleMessage: E msg.what=131215
D/WifiStateMachine( 1020): processMsg: ConnectedState
,D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1020): handleMessage: X
D/ConnectivityService( 1020): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1020):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
D/ConnectivityService( 1020): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
,I/CheckinRequestBuilder( 1376): Classify the device as Phone.
,I/CheckinTask( 1376): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1376): Checking schedule, now: 1452521163639 next: 1453114233615
,I/CheckinService( 1376): active receiver: disabled
,I/CheckinService( 1376): Checking schedule, now: 1452521163656 next: 1453114233615
,I/CheckinService( 1376): active receiver: disabled
,D/CheckinService( 1376): Recording last checkin time for package unspecified as 1452521163662
,D/GCM     ( 1359): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService( 1020): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1239): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1239): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1239): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1239): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1082): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/GAV2    ( 4347): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1020): Killing 3977:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 4176): Test app app.js loaded
I/jxcore-log( 4176): 
,W/IInputConnectionWrapper( 4176): showStatusIcon on inactive InputConnection
,I/chromium( 4176): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 4176): --= Surplus to requirements =--
I/jxcore-log( 4176): 
I/jxcore-log( 4176): ****TEST TOOK:  ms ****
I/jxcore-log( 4176): 
,I/jxcore-log( 4176): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4176): 
,D/AndroidRuntime( 4469): 
D/AndroidRuntime( 4469): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4469): CheckJNI is OFF
,D/dalvikvm( 4469): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4469): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4469): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4469): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4469): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4469): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,E/memtrack( 4469): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4469): failed to load memtrack module: -2
,D/AndroidRuntime( 4469): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10538 user=-1: uninstall pkg
,I/ActivityManager( 1020): Killing 4176:com.test.thalitest/u0a538 (adj 9): stop com.test.thalitest
,I/ActivityManager( 1020):   Force finishing activity ActivityRecord{44a92168 u0 com.test.thalitest/.MainActivity t3}
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/WindowState( 1020): WIN DEATH: Window{44b6d130 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1020): Client connection lost with reason: 4
,W/PackageSettings( 1020): Skipping PackageSetting{42953670 com.example.hello/10529} due to missing metadata
,I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10538 user=0: pkg removed
,D/dalvikvm( 4060): GC_FOR_ALLOC freed 26K, 5% free 18186K/19004K, paused 22ms, total 22ms
,D/dalvikvm( 2301): GC_EXPLICIT freed 3215K, 42% free 10071K/17224K, paused 2ms+3ms, total 44ms
,I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager( 1020): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4486 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
,I/LatinIME:LogUtils( 1206): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/LatinIME:LogUtils( 1206): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,W/GeofencerStateMachine( 1226): Ignoring removeGeofence because network location is disabled.
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
,D/dalvikvm( 2269): GC_EXPLICIT freed 5239K, 44% free 9651K/17224K, paused 3ms+7ms, total 63ms
,D/dalvikvm( 1299): GC_EXPLICIT freed 3132K, 33% free 11593K/17224K, paused 2ms+18ms, total 127ms
,D/dalvikvm( 1020): GC_EXPLICIT freed 716K, 62% free 18063K/47288K, paused 5ms+14ms, total 124ms
,D/dalvikvm( 1376): GC_EXPLICIT freed 1784K, 31% free 12016K/17224K, paused 3ms+16ms, total 158ms
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
,I/Launcher( 1299): Deferring update until onResume
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
,I/Launcher( 1299): Deferring update until onResume
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
,I/LatinIME:LogUtils( 1206): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452521169
,D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 1020): removePackageParticipantsLocked: uid=10538 #1
,I/LatinIME:LogUtils( 1206): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452521169
,D/VoicemailCleanupService( 4486): Cleaning up data for package: com.test.thalitest
,D/dalvikvm( 1020): GC_EXPLICIT freed 515K, 62% free 18102K/47288K, paused 7ms+14ms, total 167ms
,I/ActivityManager( 1020): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4509 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 3570:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2301): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager( 1020): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4525 uid=10059 gids={50059, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 4088:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4486): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/AndroidRuntime( 4469): Shutting down VM
,D/dalvikvm( 4469): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 3ms
,I/InternalIcingCorporaPro( 2301): UpdateCorporaTask done [took 122 ms] updated apps [took 122 ms] 
,W/ActiveOrDefaultContextProvider( 4525): Missing scope.enter somewhere. Returning default context
,W/GAV2    ( 4525): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/SQLiteLog( 4525): (3850) statement aborts at 59: [DELETE FROM CachedSearch101 WHERE timestamp<?] disk I/O error
I/ActivityManager( 1020): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4554 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,E/AbstractDatabaseInstance( 4525): Failed to delete from CachedSearch101
E/AbstractDatabaseInstance( 4525): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AbstractDatabaseInstance( 4525): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AbstractDatabaseInstance( 4525): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AbstractDatabaseInstance( 4525): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AbstractDatabaseInstance( 4525): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AbstractDatabaseInstance( 4525): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AbstractDatabaseInstance( 4525): 	at WQ.b(AbstractDatabaseInstance.java:292)
E/AbstractDatabaseInstance( 4525): 	at XC.a(DatabaseModelLoader.java:317)
E/AbstractDatabaseInstance( 4525): 	at Yg.a(ObsoleteDataCleanerImpl.java:122)
E/AbstractDatabaseInstance( 4525): 	at fh.run(DocsApplication.java:264)
,W/dalvikvm( 4525): threadid=11: thread exiting with uncaught exception (group=0x41dc0d40)
,E/AndroidRuntime( 4525): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 4525): Process: com.google.android.apps.docs, PID: 4525
E/AndroidRuntime( 4525): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4525): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4525): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4525): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4525): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4525): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 4525): 	at WQ.b(AbstractDatabaseInstance.java:292)
E/AndroidRuntime( 4525): 	at XC.a(DatabaseModelLoader.java:317)
E/AndroidRuntime( 4525): 	at Yg.a(ObsoleteDataCleanerImpl.java:122)
E/AndroidRuntime( 4525): 	at fh.run(DocsApplication.java:264)
I/Process ( 4525): Sending signal. PID: 4525 SIG: 9
,E/DropBoxManagerService( 1020): Can't write: system_app_crash
E/DropBoxManagerService( 1020): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager( 1020): Process com.google.android.apps.docs (pid 4525) has died.
,W/ActivityManager( 1020): Scheduling restart of crashed service com.google.android.apps.docs/.sync.syncadapter.ContentSyncService in 1000ms
,W/ContextImpl( 4554): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,I/ActivityManager( 1020): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4571 uid=10038 gids={50038, 3003, 1028, 1015}
,E/SQLiteDatabase( 4554): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4554): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4554): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4554): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4554): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4554): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4554): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4554): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4554): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4554): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4554): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4554): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4554): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4554): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4554): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4554): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4554): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4554): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4554): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4554): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4554): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4554): threadid=10: thread exiting with uncaught exception (group=0x41dc0d40)
E/AndroidRuntime( 4554): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4554): Process: com.android.keychain, PID: 4554
E/AndroidRuntime( 4554): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4554): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4554): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4554): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4554): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4554): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4554): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4554): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4554): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4554): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4554): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4554): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4554): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4554): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4554): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4554): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4554): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4554): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4554): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4554): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 4554): Sending signal. PID: 4554 SIG: 9
E/DropBoxManagerService( 1020): Can't write: system_app_crash
E/DropBoxManagerService( 1020): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager( 1020): Process com.android.keychain (pid 4554) has died.
W/ActivityManager( 1020): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10942ms

```
