#### Test 539786633aa3ea0_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1018): sending alarm Alarm{446f2ce8 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 4048): 
D/AndroidRuntime( 4048): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4048): CheckJNI is OFF
D/dalvikvm( 4048): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4048): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4048): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4048): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4048): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4048): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4048): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4048): failed to load memtrack module: -2
D/AndroidRuntime( 4048): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1018): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4048
W/WindowManager( 1018): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4064 uid=10493 gids={50493, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4048): Shutting down VM
D/dalvikvm( 4048): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 2ms
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4064): Binding Chromium to main looper Looper (main, tid 1) {42826af0}
I/LibraryLoader( 4064): Expected native library version number "",actual native library version number ""
I/chromium( 4064): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4064): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1018): Message: 20
D/BluetoothManagerService( 1018): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@440d0008:true
I/Adreno-EGL( 4064): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4064): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4064): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4064): Local Branch: 
I/Adreno-EGL( 4064): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4064): Local Patches: NONE
I/Adreno-EGL( 4064): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4064): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4064): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4064): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4064): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4064): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4064): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4064): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4064): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 4064): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4064): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4064): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 4064): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 4064): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4064): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
,W/dalvikvm( 4064): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 4064): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4064): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
,W/dalvikvm( 4064): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 4064): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4064): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4064): Enabling debug mode 0
,W/AwContents( 4064): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4064): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1018): Displayed com.test.thalitest/.MainActivity,cp,ca,452
I/ActivityManager( 1018): Displayed com.test.thalitest/.MainActivity: +426ms (total +452ms)
,D/JsMessageQueue( 4064): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4064): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4282b090
,D/dalvikvm( 4064): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4282b090
,D/jxcore_app_log( 4064): JniHelper::setJavaVM(0x41f42f78), pthread_self() = 1615807160
,D/JX-Cordova( 4064): jxcore cordova android initializing
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 4064): GC_CONCURRENT freed 2800K, 17% free 14389K/17224K, paused 3ms+2ms, total 52ms
,D/dalvikvm( 4064): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 4064): GC_FOR_ALLOC freed 180K, 17% free 14390K/17224K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4064): Grow heap (frag case) to 16.179MB for 98002-byte allocation
,D/dalvikvm( 4064): GC_FOR_ALLOC freed 211K, 17% free 14395K/17320K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4064): Grow heap (frag case) to 16.230MB for 146998-byte allocation
,D/dalvikvm( 4064): GC_FOR_ALLOC freed 257K, 18% free 14443K/17464K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4064): Grow heap (frag case) to 16.347MB for 220492-byte allocation
,D/dalvikvm( 4064): GC_FOR_ALLOC freed 373K, 18% free 14519K/17680K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4064): Grow heap (frag case) to 16.527MB for 330734-byte allocation
,D/dalvikvm( 4064): GC_FOR_ALLOC freed 579K, 19% free 14643K/18004K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4064): Grow heap (frag case) to 16.805MB for 496096-byte allocation
,D/dalvikvm( 4064): GC_FOR_ALLOC freed 879K, 20% free 14821K/18492K, paused 28ms, total 31ms
,D/dalvikvm( 4064): GC_FOR_ALLOC freed 1301K, 19% free 15082K/18492K, paused 27ms, total 28ms
,I/dalvikvm-heap( 4064): Grow heap (frag case) to 17.826MB for 1116206-byte allocation
,D/dalvikvm( 4064): GC_CONCURRENT freed 1737K, 22% free 15468K/19584K, paused 1ms+3ms, total 34ms
,D/dalvikvm( 4064): GC_FOR_ALLOC freed 344K, 22% free 15412K/19584K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4064): Grow heap (frag case) to 18.680MB for 1674304-byte allocation
,D/dalvikvm( 4064): GC_CONCURRENT freed 1677K, 25% free 15991K/21220K, paused 3ms+3ms, total 34ms
,D/dalvikvm( 4064): GC_FOR_ALLOC freed 1411K, 25% free 16084K/21220K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4064): Grow heap (frag case) to 20.134MB for 2511452-byte allocation
,D/dalvikvm( 4064): GC_CONCURRENT freed 1908K, 29% free 16905K/23676K, paused 4ms+5ms, total 58ms
,D/dalvikvm( 4064): GC_CONCURRENT freed 2510K, 29% free 17029K/23676K, paused 3ms+7ms, total 52ms
,D/dalvikvm( 4064): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 4064): GC_FOR_ALLOC freed 334K, 29% free 16980K/23676K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4064): Grow heap (frag case) to 22.208MB for 3767174-byte allocation
,D/dalvikvm( 4064): GC_CONCURRENT freed 2679K, 34% free 18132K/27356K, paused 4ms+3ms, total 47ms
,D/dalvikvm( 4064): GC_FOR_ALLOC freed 617K, 35% free 18021K/27356K, paused 26ms, total 26ms
,W/jxcore-log( 4064): Initializing JXcore engine
,W/jxcore-log( 4064): JXcore engine is ready
,D/dalvikvm( 4064): GC_CONCURRENT freed 311K, 25% free 20698K/27356K, paused 2ms+2ms, total 30ms
,D/dalvikvm( 4064): WAIT_FOR_CONCURRENT_GC blocked 21ms
,W/jxcore-log( 4064): Starting JXcore engine
,W/jxcore-log( 4064): Platform android
W/jxcore-log( 4064): 
,W/jxcore-log( 4064): Process ARCH arm
W/jxcore-log( 4064): 
,I/jxcore-log( 4064): JXcore Cordova bridge is ready!
I/jxcore-log( 4064): 
,W/jxcore-log( 4064): JXcore engine is started
,I/chromium( 4064): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4064): Toggling radios to true
I/jxcore-log( 4064): 
,D/BluetoothAdapter( 4064): enable(): BT is already enabled..!
D/WifiService( 1018): New client listening to asynchronous messages
D/WifiService( 1018): setWifiEnabled: true pid=4064, uid=10493
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1018): handleMessage: E msg.what=131145
D/WifiStateMachine( 1018): processMsg: ConnectedState
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
I/jxcore-log( 4064): Radios toggled
I/jxcore-log( 4064): 
,I/wpa_supplicant( 1173): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  271): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  271):  STA Disconnected !!
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): get_property_value, Enter
I/MDMCTBK (  271): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  271): get_property_value, Exit
I/MDMCTBK (  271): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  271): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  271): set_property_value, Enter
I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  449): NL - Read 1000 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
D/TCMD    (  449): NL - Read 1000 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
D/TCMD    (  449): NL - Read 68 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
D/TCMD    (  449): NL - Read 68 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
I/MDMCTBK (  271): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  271): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  271): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  271): set_property_value, Enter
I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit,
E/MDMCTBK (  271): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1018): transitionTo: destState=DisconnectingState
,D/Tethering( 1018): InitialState.processMessage what=4
,D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
,V/ConnectivityService( 1018): WiFi NOT Tethered!
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1018): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1018): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1018): Stopping DHCP and clearing IP
D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1018): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  269): Clearing all IP addresses on wlan0
D/TCMD    (  449): NL - Read 60 bytes from update socket.
D/TCMD    (  449): NL - ignore NL message, type = 21
,D/TCMD    (  449): Listening for incoming client connection request
,D/WifiStateMachine( 1018): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1018): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1018): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1018): connected time updated 648597
D/ConnectivityService( 1018): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1018): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1083): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1083): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/ConnectivityService( 1018): Attempting to switch to mobile
D/ConnectivityService( 1018): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1018): Attempting to switch to ETHERNET
,D/ConnectivityService( 1018): resetConnections(wlan0, 3)
D/NetUtils( 1018): android_net_utils_resetConnections in env=0x5fe5eaa8 clazz=0x62500001 iface=wlan0 mask=0x3
,D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1018): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine( 1018): DisconnectingState
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/Checkin ( 1018): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131146
D/WifiStateMachine( 1018): processMsg: DisconnectingState
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147460
D/WifiStateMachine( 1018): processMsg: DisconnectingState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): Network connection lost
D/WifiStateMachine( 1018): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1370): Read error: ssl=0x631174f0: I/O error during system call, Connection timed out
,D/WifiP2pService( 1018): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  269): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1018): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1018): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1018): invokeExitMethods: DisconnectingState
,D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine( 1018): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine( 1018): handleMessage: X
D/Checkin ( 1018): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131101
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131216
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131216
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiStateMachine( 1018): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=false
I/ModemStatsDSDetect( 1299): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1299): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1299): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1018): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1018): Attempting to switch to mobile
D/ConnectivityService( 1018): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1018): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=false
I/ModemStatsDSDetect( 1299): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1299): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1299): onReceive() - done, currentInetCondition=0
,D/dalvikvm( 1018): GC_EXPLICIT freed 23023K, 65% free 18105K/50776K, paused 4ms+12ms, total 157ms
,V/NativeCrypto( 1370): SSL shutdown failed: ssl=0x631174f0: I/O error during system call, Broken pipe
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
,D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-SCAN-RESULTS 
I/wpa_supplicant( 1173): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  271): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  271): Event received = Trying to associate with
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  449): NL - Read 56 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
,E/wpa_supplicant( 1173): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine( 1018): handleMessage: E msg.what=147461
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,I/wpa_supplicant( 1173): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  449): NL - Read 312 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
D/TCMD    (  449): NL - Read 88 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
,I/wpa_supplicant( 1173): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  449): NL - Read 68 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
D/TCMD    (  449): NL - Read 1000 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
I/wpa_supplicant( 1173): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  271): Event received = Associated with c0:ff:d4
D/TCMD    (  449): NL - Read 80 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
D/TCMD    (  449): NL - Read 80 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
D/TCMD    (  449): NL - Read 68 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1173): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1173): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  271): Event received = WPA: Key negotiation com
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  271): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  271):  STA Connected !!
D/TCMD    (  449): NL - Read 1000 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
E/MDMCTBK (  271): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  271): get_freq !!, resp=0
I/MDMCTBK (  271): get_freq !!, Strip data
I/MDMCTBK (  271): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): get_property_value, Enter
I/MDMCTBK (  271): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  271): get_property_value, Exit
I/MDMCTBK (  271): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  271): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  271): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  271): set_property_value, Enter
I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
I/MDMCTBK (  271): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  271): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  271): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): get_property_value, Enter
I/MDMCTBK (  271): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  271): get_property_value, Exit
I/MDMCTBK (  271): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1221919920
I/MDMCTBK (  271): return from set_get_from_wpa_supplicant
I/MDMCTBK (  271): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  271): set_property_value, Enter
I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
E/MDMCTBK (  271): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE ,
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiStateMachine( 1018): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/MDMCTBK (  271): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  271): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  271): , reply_len: 3, ret: 0
E/MDMCTBK (  271): MdmCutbackHndler, resp=OK
E/MDMCTBK (  271): 
,D/MDMCTBK (  271): wifi_set_tx_pwr: Exit
D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiStateMachine( 1018): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147459
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): Network connection established
,D/WifiStateMachine( 1018): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/Tethering( 1018): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1018): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1018): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1018): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1018): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1018): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
,D/WifiStateMachine( 1018): ObtainingIpState{ when=-31ms what=147462 obj=android.net.wifi.StateChangeResult@42e101c0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131101
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-13ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@43085388 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=196612
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-6ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1018): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1018): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4285e920 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4285e920 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): handleMessage: X
,D/TCMD    (  449): NL - Read 56 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 c
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 6 c
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 3
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 7 3
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 0
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 8 0
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 6
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 9 6
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 11 
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 11 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 12 
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 12 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 9e
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 5 9e
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 64
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 6 64
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 06
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 7 06
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  271): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiStateMachine( 1018): handleMessage: E msg.what=147461
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiP2pService( 1018): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@429b4b08 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@429b4b08 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): DefaultState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@429b4b08 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): handleMessage: X
,D/TCMD    (  449): NL - Read 60 bytes from update socket.
D/TCMD    (  449): NL - ignore NL message, type = 20
,D/TCMD    (  449): Listening for incoming client connection request
,D/WifiStateMachine( 1018): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1018): handleMessage: E msg.what=131215
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=0 what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1018): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
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
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=151572
D/WifiStateMachine( 1018): processMsg: VerifyingLinkState
D/WifiStateMachine( 1018): VerifyingLinkState what=151572 NOT_HANDLED
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1083): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=135190
D/WifiStateMachine( 1018): processMsg: VerifyingLinkState
D/WifiStateMachine( 1018): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1018): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1018): invokeExitMethods: VerifyingLinkState
,D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1018): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1018): CaptivePortalCheckState enter
,D/WifiStateMachine( 1018): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1018): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1018): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1018): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1018): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131092
D/WifiStateMachine( 1018): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1018): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1018): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/ConnectivityService( 1018): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1018): WiFi NOT Tethered!
,E/ConnectivityService( 1018): Unexpected mtu value: android.net.wifi.WifiStateTracker@42918bb0
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1299): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1299): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1299): onReceive() - done, currentInetCondition=0
D/WifiStateMachine( 1018): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1018): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1018): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131092
D/WifiStateMachine( 1018): processMsg: ConnectedState
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
I/SBar.NetworkController( 1083): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/Checkin ( 1018): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/ConnectivityService( 1018): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1018): WiFi NOT Tethered!
,I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
E/ConnectivityService( 1018): Unexpected mtu value: android.net.wifi.WifiStateTracker@42918bb0
,D/ConnectivityService( 1018): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1299): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1299): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1299): onReceive() - done, currentInetCondition=0
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1283): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1083): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1018): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1018): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/PollingManager( 1569): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/TelephonyProvider( 1253): Column apn id key is 'apn_id'
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1283): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,E/ActivityThread( 1569): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1569): Registering with Alarm Manager to restart CCE
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/jxcore-log( 4064): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4064): 
I/jxcore-log( 4064): my name is : motorola-XT1039_PT7033
I/jxcore-log( 4064): 
D/TelephonyProvider( 1253): Column apn id key is 'apn_id'
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/Tethering( 1018): MasterInitialState.processMessage what=3
D/TelephonyProvider( 1253): Column apn id key is 'apn_id'
D/CaptivePortalTracker( 1018): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/OtaApp  ( 1569): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/openssl ( 3957): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3957): Crypto mode 0 already enabled
D/PollingManager( 1569): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1569): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 1569): [debug] > CusSM.onRadioDown
,E/ActivityThread( 1569): Failed to find provider info for com.motorola.blur.setupprovider
,D/TelephonyProvider( 1253): Column apn id key is 'apn_id'
,I/ActivityManager( 1018): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4204 uid=10030 gids={50030, 3003, 1028, 1015}
,I/jxcore-log( 4064): attempting to connect to test coordinator
I/jxcore-log( 4064): 
,I/jxcore-log( 4064): check test folder
I/jxcore-log( 4064): 
V/MmsConfig( 4204): mnc/mcc: 
,V/MmsConfig( 4204): tag: bool value: enabledMMS - true
V/MmsConfig( 4204): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4204): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4204): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4204): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4204): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4204): tag: int value: minMessageCountPerThread - 10
,V/MmsConfig( 4204): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4204): tag: int value: recipientLimit - 20
V/MmsConfig( 4204): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4204): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4204): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4204): tag: int value: maxMessageTextSize - -1
I/jxcore-log( 4064): found test : ./testFindPeers.js
I/jxcore-log( 4064): 
,V/MmsConfig( 4204): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4204): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4204): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4204): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4204): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/jxcore-log( 4064): found test : ./testReConnect.js
I/jxcore-log( 4064): 
I/ActivityManager( 1018): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4222 uid=10041 gids={50041, 3003}
I/ActivityManager( 1018): Killing 3872:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 4064): found test : ./testSendData.js
I/jxcore-log( 4064): 
,D/MobileConnectivityChangeReceiver( 4222): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4222): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4222): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4222): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/dalvikvm(  274): WAIT_FOR_CONCURRENT_GC blocked 1ms
I/ActivityManager( 1018): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4236 uid=10056 gids={50056, 3003, 1028, 1015}
I/ActivityManager( 1018): Killing 3890:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1408): Checkin interval check for package: unspecified last checkin: 1450445251674 min interval config: 0 actual interval: 636777
,D/dalvikvm(  274): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+2ms, total 20ms
,I/CheckinService( 1408): Checking schedule, now: 1450445888464 next: 1450445281630
,I/CheckinService( 1408): active receiver: enabled
,I/jxcore-log( 4064): Test app app.js loaded
I/jxcore-log( 4064): 
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 19ms
,I/Choreographer( 4064): Skipped 210 frames!  The application may be doing too much work on its main thread.
,I/CheckinService( 1408): Preparing to send checkin request
,I/EventLogService( 1408): Accumulating logs since 1450445525635
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 18ms
,I/chromium( 4064): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/CheckinRequestBuilder( 1408): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1408): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4258 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1018): Killing 3905:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 4064): DBG, CoordinatorConnector connect called
I/jxcore-log( 4064): 
,I/jxcore-log( 4064): Coordinator is now connected to the server!
I/jxcore-log( 4064): 
,I/chromium( 4064): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,V/WebViewChromiumFactoryProvider( 4258): Binding Chromium to main looper Looper (main, tid 1) {4281fc98}
,I/LibraryLoader( 4258): Expected native library version number "",actual native library version number ""
,I/chromium( 4258): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4258): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4258): BLUETOOTH permission is missing!
,D/dalvikvm( 1370): GC_EXPLICIT freed 1697K, 41% free 10312K/17224K, paused 2ms+5ms, total 42ms
,I/Adreno-EGL( 4258): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4258): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4258): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4258): Local Branch: 
I/Adreno-EGL( 4258): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4258): Local Patches: NONE
I/Adreno-EGL( 4258): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4258): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 4258): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  260): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  260): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4258): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/ActivityManager( 1018): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4297 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4297): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4297): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4297): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
,W/dalvikvm( 4297): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4297): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 4297): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4297): install
,I/MultiDex( 4297): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4297): loading existing secondary dex files
,I/MultiDex( 4297): load found 3 secondary dex files
,I/MultiDex( 4297): install done
,D/dalvikvm( 4297): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4297): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4297): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4297): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4297): VFY: unable to resolve instance field 36
,D/dalvikvm( 4297): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4297): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4297): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4297): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4297): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4297): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4297): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42825d78
D/dalvikvm( 4297): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42825d78
,D/dalvikvm( 4297): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42825d78, skipping init
,D/dalvikvm( 4297): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42825d78
D/dalvikvm( 4297): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42825d78
,V/JNIHelp ( 4297): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4297): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42825d78
,D/dalvikvm( 4297): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42825d78
D/dalvikvm( 4297): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42825d78
,D/dalvikvm( 4297): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42825d78
,I/NSApplication( 4258): Starting up...
,I/ImageResourceManager( 3936): ImageResourceManager: uninitalized
,I/iu.Environment( 3936): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1018): Killing 3848:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/DEBUG   ( 1569): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1569): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1569): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1569): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1569): ServiceHandler.handleMessage: mWaitCount=0
D/EmailService.MarketingOptInSetter( 1569): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1569): onServiceConnected()
D/GetNotificationsWS( 1569): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1569): unbindWebServices(): un-registering our AIDL callback...
,I/openssl ( 3957): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3957): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4222): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4222): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3936): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/ProviderInstaller( 4297): Installed default security provider GmsCore_OpenSSL
,D/ConnectivityService( 1018): NetTransition Wakelock for ConnectedState released by timeout
D/WearableService( 1220): callingUid 10022, callindPid: 1220
D/LocationInitializer( 1408): Restart initialization of location
,D/WifiStateMachine( 1018): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1018): handleMessage: E msg.what=131215
D/WifiStateMachine( 1018): processMsg: ConnectedState
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): processMsg: DefaultState
D/AuthorizationBluetoothService( 1370): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1370): Proximity feature is not enabled.
,D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1018): handleMessage: X
,D/ConnectivityService( 1018): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1018):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1018): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/MDM     ( 1220): [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/dalvikvm( 4297): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/GCoreFlp( 1220): No location to return for getLastLocation()
W/dalvikvm( 4297): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4297): VFY: replacing opcode 0x6e at 0x00ce
W/FusedLocationProvider( 1220): location=null
I/dalvikvm( 4297): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4297): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4297): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4297): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4297): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4297): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4297): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4297): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4297): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4297): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4297): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4297): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4297): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4297): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  276): Instantiating CDM.
,I/WVCdm   (  276): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  276): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  276): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  276): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb533a000
,E/DrmWidevineDash(  276): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb533a000
D/DrmWidevineDash(  276): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  276): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  276): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  276): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  276): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  276): CdmEngine::OpenSession
,D/DrmWidevineDash(  276): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  276): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  276): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  276): OEMCrypto_GetRandom returns 0
I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  276): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  276): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  276): PrepareKeyRequest: nonce=2446844378
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4297): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4297): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a28ae8
D/dalvikvm( 4297): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a28ae8
,D/dalvikvm( 4297): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a28ae8, skipping init
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,W/Settings( 4297): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4297): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4340): DexOpt: load 3ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4297): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4297): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 89ms
,I/Adreno-EGL( 4297): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4297): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4297): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4297): Local Branch: 
I/Adreno-EGL( 4297): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4297): Local Patches: NONE
I/Adreno-EGL( 4297): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4297): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4297): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4297): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4297): Local Branch: 
I/Adreno-EGL( 4297): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4297): Local Patches: NONE
I/Adreno-EGL( 4297): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4297): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4297): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4297): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4297): Local Branch: 
I/Adreno-EGL( 4297): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4297): Local Patches: NONE
I/Adreno-EGL( 4297): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4297): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4297): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4297): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4297): Local Branch: 
I/Adreno-EGL( 4297): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4297): Local Patches: NONE
I/Adreno-EGL( 4297): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/WVCdm   (  276): CdmEngine::OpenSession
,D/DrmWidevineDash(  276): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  276): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  276): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  276): calling OEMCrypto_LoadDeviceRSAKey. SID = 1,
D/DrmWidevineDash(  276): OEMCrypto_LoadDeviceRSAKey returns 0
D/DrmWidevineDash(  276): calling OEMCrypto_GetDeviceID...
D/DrmWidevineDash(  276): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  276): PrepareKeyRequest: nonce=1275281727
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1408): Classify the device as Phone.
,V/NativeCrypto( 1408): SSL shutdown failed: ssl=0x6c06da68: I/O error during system call, Connection timed out
,I/CheckinTask( 1408): Sending checkin request (11623 bytes)
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1018): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,W/XTWiFiOS( 1283): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/PollingManager( 1569): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TelephonyProvider( 1253): Column apn id key is 'apn_id'
D/PollingManager( 1569): now: 680023 ,futureTime: 22412949
,D/PollingManager( 1569): Polling alarm set to expire at: 22412949 Current Time: 680023
,E/ActivityThread( 1569): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1569): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1569): [debug] > CusSM.onRadioUp
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/PollingManager( 1569): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/Tethering( 1018): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1018): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/PollingManager( 1569): now: 680039 ,futureTime: 22412949
D/PollingManager( 1569): Polling alarm set to expire at: 22412949 Current Time: 680039
W/XTWiFiOS( 1283): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/TelephonyProvider( 1253): Column apn id key is 'apn_id'
D/OtaApp  ( 1569): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,E/ActivityThread( 1569): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1569): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/openssl ( 3957): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3957): Crypto mode 0 already enabled
D/OtaApp  ( 1569): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1569): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1569): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1569): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/MobileConnectivityChangeReceiver( 4222): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4222): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1569): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1569): [debug] > CusSM.onRadioUp
,I/iu.Environment( 3936): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/OtaApp  ( 1569): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1569): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1569): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,I/CheckinService( 1408): Checkin interval check for package: unspecified last checkin: 1450445251674 min interval config: 0 actual interval: 639480
,D/OtaApp  ( 1569): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1569): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1569): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/DEBUG   ( 1569): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1569): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1569): bindWebServices(): registering our AIDL callback...
I/SundryService( 1569): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1569): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1569): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1569): onServiceConnected()
,D/GetNotificationsWS( 1569): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1569): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 3957): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3957): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4222): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4222): onReceive CONNECTIVITY_CHANGE networkType=1
,D/TelephonyProvider( 1253): Column apn id key is 'apn_id'
,I/iu.Environment( 3936): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1408): Checkin interval check for package: unspecified last checkin: 1450445251674 min interval config: 0 actual interval: 639540
,D/DEBUG   ( 1569): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/dalvikvm( 3936): GC_FOR_ALLOC freed 613K, 5% free 16434K/17224K, paused 21ms, total 22ms
,W/ContextImpl( 1569): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1569): bindWebServices(): registering our AIDL callback...
I/SundryService( 1569): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1569): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1569): onServiceConnected()
,D/GetNotificationsWS( 1569): onServiceConnected(): Registered for remote service callbacks...
,D/OtaApp  ( 1569): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/WaitableIntentService( 1569): ServiceHandler.handleMessage: mWaitCount=0
,I/dalvikvm-heap( 3936): Grow heap (frag case) to 19.818MB for 1821008-byte allocation
,D/OtaApp  ( 1569): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1018): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1569
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1569): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1569): [info] > Updatetime from metadata: 10
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1569): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1569): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1569): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1569): [info] > Updatetime from metadata: 10
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1569): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1569): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1569): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/dalvikvm( 1018): GC_EXPLICIT freed 1390K, 65% free 18055K/50776K, paused 5ms+9ms, total 117ms
,D/OtaApp  ( 1569): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1018): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1569
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/TelephonyProvider( 1253): Column apn id key is 'apn_id'
,D/OtaApp  ( 1569): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1569): [info] > Updatetime from metadata: 10
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1569): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1569): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1569): [info] > Updatetime from metadata: 10
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1569): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1569): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1569): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/IInputConnectionWrapper( 4064): showStatusIcon on inactive InputConnection
,D/OtaApp  ( 1569): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1018): Activity reported stop, but no longer stopping: ActivityRecord{4316b1b8 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/LaunchCheckinHandler( 1018): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,133
,I/CheckinRequestBuilder( 1408): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1408): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1408): Classify the device as Phone.
,I/CheckinTask( 1408): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1408): Checking schedule, now: 1450445891793 next: 1451038961789
,I/CheckinService( 1408): active receiver: disabled
,I/CheckinService( 1408): Checking schedule, now: 1450445891811 next: 1451038961789
,I/CheckinService( 1408): active receiver: disabled
,D/CheckinService( 1408): Recording last checkin time for package unspecified as 1450445891816
,D/GCM     ( 1370): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1220): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1220): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1220): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1220): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1220): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,D/dalvikvm( 1220): GC_EXPLICIT freed 1498K, 35% free 11274K/17224K, paused 2ms+8ms, total 42ms
,I/dalvikvm( 1220): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm( 1220): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1220): VFY: replacing opcode 0x6e at 0x003d
,I/PhenotypeConfigurator( 1220): Scheduling Phenotype for one-off execution 5420 seconds from now (1450445892427)
,D/GetConfigurationSnapshotOperation( 1220): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1220): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1220): Using platform SSLCertificateSocketFactory
,D/ConnectivityService( 1018): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1299): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1299): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1299): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1299): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1083): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/dalvikvm( 1220): GC_CONCURRENT freed 1660K, 33% free 11583K/17224K, paused 3ms+7ms, total 40ms
,W/PhenotypeConfigurator( 1220): Server returned 404
,I/dalvikvm( 4064): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4064): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4064): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 4064): Shutting down VM
,W/dalvikvm( 4064): threadid=1: thread exiting with uncaught exception (group=0x41f54d40)
,E/AndroidRuntime( 4064): FATAL EXCEPTION: main
E/AndroidRuntime( 4064): Process: com.test.thalitest, PID: 4064
E/AndroidRuntime( 4064): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4064): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4064): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4064): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4064): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4064): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4064): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4064): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4064): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4064): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4064): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4064): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4064): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4064): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4064): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4064): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4064): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4064): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4064): 	at dalvik.system.NativeStart.main(Native Method)
I/Process ( 4064): Sending signal. PID: 4064 SIG: 9
,I/ActivityManager( 1018): Process com.test.thalitest (pid 4064) has died.
,I/WindowState( 1018): WIN DEATH: Window{450cb850 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1018): Client connection lost with reason: 4
,I/GAV2    ( 4258): Thread[GAThread,5,main]: No campaign data found.
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/ActivityManager( 1018): Killing 3497:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
,I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4404 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Launcher( 1311): Deferring update until onResume
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
I/Launcher( 1311): Deferring update until onResume
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
,I/GCoreNlp( 1220): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4404): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4404): MmsConfig.loadMmsSettings
I/Babel   ( 4404): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4404): MmsConfig.loadFromDatabase
,E/Babel   ( 4404): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4404): MmsConfig.loadFromResources
,E/Babel   ( 4404): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4404): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4404): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1018): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4440 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1018): Killing 4028:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4458 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1018): Killing 3957:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2320): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1018): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4477 uid=10038 gids={50038, 3003, 1028, 1015}
,D/dalvikvm( 3936): GC_FOR_ALLOC freed 34K, 5% free 18189K/19004K, paused 20ms, total 22ms
,I/ActivityManager( 1018): Killing 4204:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4440): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4477): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4477): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4477): VFY: replacing opcode 0x6e at 0x000e
,D/dalvikvm( 1408): GC_CONCURRENT freed 1967K, 30% free 12070K/17224K, paused 3ms+5ms, total 55ms
,D/dalvikvm( 1370): GC_EXPLICIT freed 1026K, 41% free 10325K/17224K, paused 2ms+4ms, total 31ms
,D/Finsky  ( 4477): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2320): UpdateCorporaTask done [took 234 ms] updated apps [took 234 ms] 
,I/dalvikvm( 4477): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4477): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4477): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4477): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
,W/dalvikvm( 4477): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4477): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4477): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/dalvikvm( 4477): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4477): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4477): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4477): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4477): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4477): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4477): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4477): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4477): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4477): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4477): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4477): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4477): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4477): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1018): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4513 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4477): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 4477): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4477): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4477): Skipping gmscore version check
,D/Finsky  ( 4477): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4477): [1] Libraries$2.run: Finished loading 1 libraries.
I/dalvikvm( 4477): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4477): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4477): VFY: replacing opcode 0x6e at 0x0017
,I/ActivityManager( 1018): Killing 4222:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1408): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1408): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1408): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4513): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x4282c288, skipping init
I/openssl ( 4513): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4513): Crypto mode 0 already enabled
,I/ActivityManager( 1018): Killing 4236:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1018): GC_EXPLICIT freed 1412K, 65% free 18122K/50776K, paused 4ms+11ms, total 95ms
,D/Finsky  ( 4477): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4477): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 1408): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1408): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1205): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450445900
,D/CaptivePortalTracker( 1018): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1018): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1018): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1018): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1018): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1018): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1018): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1018): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{42e282e8 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,D/TCMD    (  449): NL - Read 1000 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
D/TCMD    (  449): NL - Read 68 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
I/wpa_supplicant( 1173): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  271): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  271):  STA Disconnected !!
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): get_property_value, Enter
I/MDMCTBK (  271): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  271): get_property_value, Exit
I/MDMCTBK (  271): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  271): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  271): set_property_value, Enter
I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
I/MDMCTBK (  271): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  271): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  271): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  271): set_property_value, Enter
I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
E/MDMCTBK (  271): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  449): NL - Read 68 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147460
D/WifiStateMachine( 1018): processMsg: ConnectedState
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): Network connection lost
D/WifiStateMachine( 1018): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 true
,D/Tethering( 1018): InitialState.processMessage what=4
,V/ConnectivityService( 1018): WiFi NOT Tethered!
D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiP2pService( 1018): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  269): Clearing all IP addresses on wlan0
D/TCMD    (  449): NL - Read 60 bytes from update socket.
D/TCMD    (  449): NL - ignore NL message, type = 21
,D/TCMD    (  449): Listening for incoming client connection request
,D/WifiStateMachine( 1018): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1018): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1018): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1018): connected time updated 758347
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1018): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1018): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1018): Attempting to switch to mobile
D/ConnectivityService( 1018): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1018): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/WifiStateMachine( 1018): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1018): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1018): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1018): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 true
,D/ConnectivityService( 1018): resetConnections(wlan0, 3)
D/NetUtils( 1018): android_net_utils_resetConnections in env=0x5fe5eaa8 clazz=0x89400001 iface=wlan0 mask=0x3
,D/Checkin ( 1018): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiP2pService( 1018): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,V/NativeCrypto( 1370): Read error: ssl=0x631320a0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1370): SSL shutdown failed: ssl=0x631320a0: I/O error during system call, Broken pipe
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  269): Clearing all IP addresses on wlan0
,D/WifiStateMachine( 1018): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine( 1018): invokeEnterMethods: DisconnectedState
,D/Checkin ( 1018): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
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
,D/WifiStateMachine( 1018): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1018): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1299): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1299): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1299): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1018): Attempting to switch to mobile
D/ConnectivityService( 1018): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1018): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1299): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1299): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1299): onReceive() - done, currentInetCondition=0
,I/wpa_supplicant( 1173): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  271): Event received = WPS-AP-AVAILABLE-AUTH 
D/TCMD    (  449): NL - Read 56 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
D/WifiStateMachine( 1018): handleMessage: E msg.what=147461,
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState,
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  271): Event received = Trying to associate with
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE ,
,E/wpa_supplicant( 1173): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,I/wpa_supplicant( 1173): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  449): NL - Read 312 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
D/TCMD    (  449): NL - Read 88 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
,I/wpa_supplicant( 1173): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  449): NL - Read 68 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
D/TCMD    (  449): NL - Read 1000 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1173): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  271): Event received = Associated with c0:ff:d4
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  449): NL - Read 80 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
D/TCMD    (  449): NL - Read 80 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
D/TCMD    (  449): NL - Read 68 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiStateMachine( 1018): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiStateMachine( 1018): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
I/wpa_supplicant( 1173): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  271): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1173): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  271): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  271):  STA Connected !!
,D/WifiStateMachine( 1018): handleMessage: X
D/TCMD    (  449): NL - Read 1000 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
E/MDMCTBK (  271): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  271): get_freq !!, resp=0
I/MDMCTBK (  271): get_freq !!, Strip data
I/MDMCTBK (  271): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): get_property_value, Enter
I/MDMCTBK (  271): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  271): get_property_value, Exit
I/MDMCTBK (  271): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  271): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  271): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  271): set_property_value, Enter
I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
I/MDMCTBK (  271): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  271): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  271): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): get_property_value, Enter
I/MDMCTBK (  271): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  271): get_property_value, Exit
I/MDMCTBK (  271): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1221919920
I/MDMCTBK (  271): return from set_get_from_wpa_supplicant
I/MDMCTBK (  271): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  271): set_property_value, Enter
,I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
E/MDMCTBK (  271): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  271): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  271): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  271): , reply_len: 3, ret: 0
E/MDMCTBK (  271): MdmCutbackHndler, resp=OK
E/MDMCTBK (  271): 
,D/MDMCTBK (  271): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiStateMachine( 1018): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,D/Tethering( 1018): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147459
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): Network connection established
,D/WifiStateMachine( 1018): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1018): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1018): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1018): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1018): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1018): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-43ms what=147462 obj=android.net.wifi.StateChangeResult@42a14390 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131101
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-35ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@43076f20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=196612
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
,D/WifiStateMachine( 1018): ObtainingIpState{ when=-6ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1018): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiP2pService( 1018): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4285e920 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4285e920 target=com.android.internal.util.StateMachine$SmHandler }
,V/AlarmManager( 1018): sending alarm Alarm{42a10fb0 type 3 android}
,D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 1
D/TCMD    (  449): NL - Read 56 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request,
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS ,
D/MDMCTBK (  271): Event received = CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
,D/MDMCTBK (  271): Event received = WPS-AP-AVAILABLE-AUTH 
D/WifiP2pService( 1018): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): handleMessage: E msg.what=147461
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): handleMessage: X
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1018): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,W/XTWiFiOS( 1283): No entry in secure settings for enhanced location services: false
,D/ConnectivityService( 1018): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
W/XTWiFiOS( 1283): Active network info is not available
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: null, inetCondition= 0
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/PollingManager( 1569): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1253): Column apn id key is 'apn_id'
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,W/XTWiFiOS( 1283): No entry in secure settings for enhanced location services: false
D/CaptivePortalTracker( 1018): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1283): Active network info is not available
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: null, inetCondition= 0
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1569): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1569): Registering with Alarm Manager to restart CCE
D/TelephonyProvider( 1253): Column apn id key is 'apn_id'
D/PollingManager( 1569): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/OtaApp  ( 1569): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1569): [debug] > CusSM.onRadioDown
,D/PollingManager( 1569): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1569): Failed to find provider info for com.motorola.blur.setupprovider
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1253): Column apn id key is 'apn_id'
,I/ActivityManager( 1018): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4611 uid=10030 gids={50030, 3003, 1028, 1015}
,D/TelephonyProvider( 1253): Column apn id key is 'apn_id'
,V/MmsConfig( 4611): mnc/mcc: 
V/MmsConfig( 4611): tag: bool value: enabledMMS - true
V/MmsConfig( 4611): tag: int value: maxMessageSize - 307200
,V/MmsConfig( 4611): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4611): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4611): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4611): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4611): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4611): tag: int value: maxMessageCountPerThread - 5000
,V/MmsConfig( 4611): tag: int value: recipientLimit - 20
V/MmsConfig( 4611): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4611): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4611): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4611): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4611): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4611): tag: bool value: smsForceShowEncodingMenu - true
,V/MmsConfig( 4611): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4611): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4611): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1018): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4639 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1018): Killing 4258:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4639): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4639): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4639): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4639): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1018): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4652 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1018): Killing 4297:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4666 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1018): Killing 4404:com.google.android.talk/u0a70 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  274): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 3ms+3ms, total 25ms
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 18ms
,V/WebViewChromiumFactoryProvider( 4666): Binding Chromium to main looper Looper (main, tid 1) {42829a20}
,I/LibraryLoader( 4666): Expected native library version number "",actual native library version number ""
,I/chromium( 4666): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4666): Initializing chromium process, renderers=0
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 18ms
,E/AudioManagerAndroid( 4666): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4666): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4666): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4666): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4666): Local Branch: 
I/Adreno-EGL( 4666): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4666): Local Patches: NONE
I/Adreno-EGL( 4666): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4666): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4666): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  260): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  260): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4666): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 4666): Starting up...
,I/iu.Environment( 3936): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.SyncManager( 3936): SYNC; picasa accounts
I/ActivityManager( 1018): Killing 4440:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/iu.UploadsManager( 3936): num queued entries: 0
I/iu.Environment( 1408): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/iu.UploadsManager( 1408): num queued entries: 0
I/iu.UploadsManager( 3936): num updated entries: 0
I/iu.SyncManager( 3936): NEXT; no task
I/iu.UploadsManager( 1408): num updated entries: 0
D/DEBUG   ( 1569): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/iu.SyncManager( 1408): NEXT; no task
W/ContextImpl( 1569): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
D/GetNotificationsWS( 1569): bindWebServices(): registering our AIDL callback...
I/SundryService( 1569): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1569): ServiceHandler.handleMessage: mWaitCount=0
D/EmailService.MarketingOptInSetter( 1569): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1569): onServiceConnected()
D/GetNotificationsWS( 1569): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 1569): unbindWebServices(): un-registering our AIDL callback...
,D/MobileConnectivityChangeReceiver( 4639): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4639): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3936): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,D/TCMD    (  449): NL - Read 60 bytes from update socket.
D/TCMD    (  449): NL - ignore NL message, type = 20
,D/TCMD    (  449): Listening for incoming client connection request
,D/WifiStateMachine( 1018): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1018): processMsg: ObtainingIpState
,D/WifiStateMachine( 1018): ObtainingIpState{ when=-2ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 true,
,D/WifiP2pService( 1018): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): DHCP successful
,D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1018): Calling ARP set with IP = 192.168.1.127
,D/WifiStateMachine( 1018): transitionTo: destState=VerifyingLinkState
,D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1018): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1018): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1018): VerifyingLinkState enter
,D/WifiStateMachine( 1018): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=151572
D/WifiStateMachine( 1018): processMsg: VerifyingLinkState
D/WifiStateMachine( 1018): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1083): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=135190
D/WifiStateMachine( 1018): processMsg: VerifyingLinkState
D/WifiStateMachine( 1018): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1018): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1018): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1018): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1018): CaptivePortalCheckState enter
,D/WifiStateMachine( 1018): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1018): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1018): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1018): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1018): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131092
D/WifiStateMachine( 1018): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1018): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1018): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1018): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1018): WiFi NOT Tethered!
,E/ConnectivityService( 1018): Unexpected mtu value: android.net.wifi.WifiStateTracker@42918bb0
I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1299): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1299): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1299): onReceive() - done, currentInetCondition=0
,D/WifiStateMachine( 1018): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1018): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1018): invokeEnterMethods: ConnectedState
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131092
D/WifiStateMachine( 1018): processMsg: ConnectedState
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): handleMessage: X
,D/Checkin ( 1018): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.NetworkController( 1083): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1018): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1018): WiFi NOT Tethered!
,E/ConnectivityService( 1018): Unexpected mtu value: android.net.wifi.WifiStateTracker@42918bb0
I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,D/ConnectivityService( 1018): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1299): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/CheckinService( 1408): Checkin interval check for package: unspecified last checkin: 1450445891816 min interval config: 0 actual interval: 110194
I/ModemStatsDSDetect( 1299): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1299): onReceive() - done, currentInetCondition=0
,I/CheckinService( 1408): Checking schedule, now: 1450446002016 next: 1450445921789
,I/CheckinService( 1408): active receiver: enabled
,I/CheckinService( 1408): Preparing to send checkin request
,I/EventLogService( 1408): Accumulating logs since 1450445888500
,I/CheckinRequestBuilder( 1408): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1408): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1018): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4749 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4749): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4749): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4749): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4749): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4749): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 4749): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4749): install
,I/MultiDex( 4749): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4749): loading existing secondary dex files
,I/MultiDex( 4749): load found 3 secondary dex files
,I/MultiDex( 4749): install done
,D/dalvikvm( 4749): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4749): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4749): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4749): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4749): VFY: unable to resolve instance field 36
,D/dalvikvm( 4749): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 4749): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4749): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4749): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4749): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4749): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4749): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428249c8
,D/dalvikvm( 4749): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428249c8
D/dalvikvm( 4749): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428249c8, skipping init
,D/dalvikvm( 4749): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428249c8
D/dalvikvm( 4749): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428249c8
,V/JNIHelp ( 4749): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4749): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428249c8
,D/dalvikvm( 4749): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428249c8
D/dalvikvm( 4749): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428249c8
,D/dalvikvm( 4749): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428249c8
,I/ProviderInstaller( 4749): Installed default security provider GmsCore_OpenSSL
,D/AuthorizationBluetoothService( 1370): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1370): Proximity feature is not enabled.
,D/WearableService( 1220): callingUid 10022, callindPid: 1220
,D/LocationInitializer( 1408): Restart initialization of location
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1220): [70] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1220): No location to return for getLastLocation()
,W/FusedLocationProvider( 1220): location=null
,I/dalvikvm( 4749): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4749): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4749): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4749): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4749): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4749): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4749): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4749): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4749): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4749): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4749): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4749): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4749): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4749): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4749): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4749): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4749): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  276): Instantiating CDM.
,I/WVCdm   (  276): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  276): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  276): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  276): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb533a000
,E/DrmWidevineDash(  276): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb533a000
D/DrmWidevineDash(  276): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  276): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  276): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  276): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  276): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  276): CdmEngine::OpenSession
,D/DrmWidevineDash(  276): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  276): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  276): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  276): OEMCrypto_GetRandom returns 0
I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  276): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  276): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  276): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  276): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  276): PrepareKeyRequest: nonce=558445725
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4749): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4749): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a48d70
,D/dalvikvm( 4749): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a48d70
,D/dalvikvm( 4749): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a48d70, skipping init
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,D/ConnectivityService( 1018): NetTransition Wakelock for ConnectedState released by timeout
,W/Settings( 4749): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4749): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4784): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4749): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4749): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 69ms
,I/Adreno-EGL( 4749): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4749): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4749): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4749): Local Branch: 
I/Adreno-EGL( 4749): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4749): Local Patches: NONE
I/Adreno-EGL( 4749): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4749): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4749): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4749): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4749): Local Branch: 
I/Adreno-EGL( 4749): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4749): Local Patches: NONE
I/Adreno-EGL( 4749): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4749): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4749): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4749): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4749): Local Branch: 
I/Adreno-EGL( 4749): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4749): Local Patches: NONE
I/Adreno-EGL( 4749): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4749): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4749): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4749): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4749): Local Branch: 
I/Adreno-EGL( 4749): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4749): Local Patches: NONE
I/Adreno-EGL( 4749): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/WVCdm   (  276): CdmEngine::OpenSession
,D/DrmWidevineDash(  276): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  276): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  276): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  276): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  276): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  276): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  276): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  276): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  276): PrepareKeyRequest: nonce=1337365473
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1408): Classify the device as Phone.
,I/CheckinTask( 1408): Sending checkin request (11627 bytes)
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,W/XTWiFiOS( 1283): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/CaptivePortalTracker( 1018): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/PollingManager( 1569): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1569): now: 793975 ,futureTime: 22412949
,D/PollingManager( 1569): Polling alarm set to expire at: 22412949 Current Time: 793975
,E/ActivityThread( 1569): Failed to find provider info for com.motorola.blur.setupprovider
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1253): Column apn id key is 'apn_id'
,D/PollingManager( 1569): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,W/XTWiFiOS( 1283): No entry in secure settings for enhanced location services: false
,D/OtaApp  ( 1569): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1569): [debug] > CusSM.onRadioUp
,D/PollingManager( 1569): now: 794000 ,futureTime: 22412949
,D/PollingManager( 1569): Polling alarm set to expire at: 22412949 Current Time: 794000
,D/OtaApp  ( 1569): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1569): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1569): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,E/ActivityThread( 1569): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1569): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
D/OtaApp  ( 1569): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1569): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/openssl ( 4513): Crypto mode not selected, openssl will run on its regular mode.
D/OtaApp  ( 1569): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/openssl ( 4513): Crypto mode 0 already enabled
D/Tethering( 1018): MasterInitialState.processMessage what=3
D/OtaApp  ( 1569): [debug] > CusSM.onRadioUp
D/CaptivePortalTracker( 1018): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/OtaApp  ( 1569): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/TelephonyProvider( 1253): Column apn id key is 'apn_id'
D/MobileConnectivityChangeReceiver( 4639): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4639): onReceive CONNECTIVITY_CHANGE networkType=1
D/OtaApp  ( 1569): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1569): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1569): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1569): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/TelephonyProvider( 1253): Column apn id key is 'apn_id'
D/OtaApp  ( 1569): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/iu.Environment( 3936): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 3936): num queued entries: 0
,I/iu.UploadsManager( 3936): num updated entries: 0
I/iu.SyncManager( 3936): NEXT; no task
I/CheckinService( 1408): Checkin interval check for package: unspecified last checkin: 1450445891816 min interval config: 0 actual interval: 113335
D/dalvikvm( 1569): GC_CONCURRENT freed 2012K, 39% free 10659K/17224K, paused 2ms+4ms, total 35ms
D/TelephonyProvider( 1253): Column apn id key is 'apn_id'
I/iu.Environment( 1408): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1408): num queued entries: 0
I/iu.UploadsManager( 1408): num updated entries: 0
I/iu.SyncManager( 1408): NEXT; no task
D/DEBUG   ( 1569): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/ContextImpl( 1569): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1569): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1569): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/EmailService.MarketingOptInSetter( 1569): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1569): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1569): onServiceConnected()
D/GetNotificationsWS( 1569): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1569): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4513): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4513): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4639): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4639): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 1408): GC_CONCURRENT freed 1980K, 30% free 12086K/17224K, paused 37ms+7ms, total 98ms
,I/iu.Environment( 3936): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1408): Checkin interval check for package: unspecified last checkin: 1450445891816 min interval config: 0 actual interval: 113392
,D/dalvikvm( 3936): GC_FOR_ALLOC freed 47K, 4% free 20566K/21288K, paused 13ms, total 14ms
,D/DEBUG   ( 1569): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1569): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/dalvikvm( 1018): GC_EXPLICIT freed 1839K, 65% free 18030K/50776K, paused 4ms+10ms, total 90ms
,D/GetNotificationsWS( 1569): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1569): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1569): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1569): onServiceConnected()
D/GetNotificationsWS( 1569): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1569): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1569): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1569): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1018): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1569
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1569): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1569): [info] > Updatetime from metadata: 10
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1569): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1569): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1569): [info] > Updatetime from metadata: 10
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1569): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1569): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1569): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1569): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1569): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1018): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1569
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1569): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1569): [info] > Updatetime from metadata: 10
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1569): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1569): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1569): [info] > Updatetime from metadata: 10
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1569): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1569): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1569): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1569): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1569): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1018): Activity reported stop, but no longer stopping: ActivityRecord{4316b1b8 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/GAV2    ( 4666): Thread[GAThread,5,main]: No campaign data found.
,I/CheckinRequestBuilder( 1408): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1408): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1408): Classify the device as Phone.
,I/CheckinTask( 1408): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1408): Checking schedule, now: 1450446006614 next: 1451039076607
,I/CheckinService( 1408): active receiver: disabled
,I/CheckinService( 1408): Checking schedule, now: 1450446006634 next: 1451039076607
,I/CheckinService( 1408): active receiver: disabled
,D/CheckinService( 1408): Recording last checkin time for package unspecified as 1450446006640
,D/GCM     ( 1370): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiStateMachine( 1018): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131215
D/WifiStateMachine( 1018): processMsg: ConnectedState
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityService( 1018): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1018):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine( 1018): handleMessage: X
,D/ConnectivityService( 1018): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
,I/ClearcutLoggerApiImpl( 1370): disconnect managed GoogleApiClient
,D/ConnectivityService( 1018): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1299): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1083): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
,I/ModemStatsDSDetect( 1299): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1299): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1299): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/ActivityManager( 1018): Killing 4458:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4844 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
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
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
I/Launcher( 1311): Deferring update until onResume
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
I/Launcher( 1311): Deferring update until onResume
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
,I/GCoreNlp( 1220): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4844): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4844): MmsConfig.loadMmsSettings
I/Babel   ( 4844): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4844): MmsConfig.loadFromDatabase
,E/Babel   ( 4844): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4844): MmsConfig.loadFromResources
E/Babel   ( 4844): canonicalizeMccMnc: invalid mccmnc nullnull
,W/Settings( 4844): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel   ( 4844): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/ActivityManager( 1018): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4881 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1018): Killing 4477:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Killing 4513:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4900 uid=10033 gids={50033, 3003, 1028, 1015}
,I/InternalIcingCorporaPro( 2320): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1018): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4918 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1018): Killing 4611:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4881): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4918): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4918): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4918): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4918): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2320): UpdateCorporaTask done [took 197 ms] updated apps [took 197 ms] 
,I/dalvikvm( 4918): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4918): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4918): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4918): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4918): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4918): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4918): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4918): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4918): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4918): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4918): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4918): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4918): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4918): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4918): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 4918): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4918): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4918): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4918): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4918): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4918): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1018): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4952 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4918): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4918): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4918): VFY: replacing opcode 0x6e at 0x0019
,D/Finsky  ( 4918): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4918): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 4918): Skipping gmscore version check
,I/dalvikvm( 4918): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4918): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4918): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1018): Killing 4639:com.google.android.setupwizard/u0a41 (adj 15): empty #9
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1408): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1408): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1408): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4952): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x4282b318, skipping init
I/openssl ( 4952): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4952): Crypto mode 0 already enabled
,D/Finsky  ( 4918): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager( 1018): Killing 4652:com.android.chrome/u0a56 (adj 15): empty #9
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Finsky  ( 4918): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ProcessCpuTracker( 1018): Skipping unknown process pid 4853
,W/ProcessCpuTracker( 1018): Skipping unknown process pid 4854
,W/ProcessCpuTracker( 1018): Skipping unknown process pid 4869
,W/ProcessCpuTracker( 1018): Skipping unknown process pid 4981
,I/Icing   ( 1408): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1408): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1205): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450446014
,D/CaptivePortalTracker( 1018): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1018): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1018): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1018): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1018): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 1018): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1018): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1018): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,W/bt-l2cap( 1788): l2cu_get_conn_role 1
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [44:80:eb:7b:5a:05]: 7, f, 6109
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,V/AlarmManager( 1018): sending alarm Alarm{42de5898 type 2 android}
,D/ConnectivityService( 1018): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1018): Done.
,D/ConnectivityService( 1018): Setting timer for 720seconds
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,W/bt-l2cap( 1788): l2cu_get_conn_role 1
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [44:80:eb:7b:5a:05]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [90:e7:c4:f6:69:77]: 0, 0, 0
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1788): tBTM_SEC_DEV:0x5f2d91b0 rs_disc_pending=1
,W/bt-btif ( 1788): bta_dm_check_av:0
,W/bt-btif ( 1788): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [f8:95:c7:87:3c:51]: 0, 0, 0
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1788): tBTM_SEC_DEV:0x5f2d9528 rs_disc_pending=0
,W/bt-btif ( 1788): bta_dm_check_av:0
,W/bt-btif ( 1788): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1788): l2cu_get_conn_role 0
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [f8:95:c7:87:3c:51]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1788): tBTM_SEC_DEV:0x5f2d936c rs_disc_pending=0
,W/bt-btif ( 1788): bta_dm_check_av:0
,W/bt-btif ( 1788): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,V/AlarmManager( 1018): sending alarm Alarm{42de0378 type 3 android}
,W/bt-l2cap( 1788): l2cu_get_conn_role 0
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [90:e7:c4:f6:69:77]: 7, f, 6109
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1788): tBTM_SEC_DEV:0x5f2d9528 rs_disc_pending=0
,W/bt-btif ( 1788): bta_dm_check_av:0
,W/bt-btif ( 1788): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1788): l2cu_get_conn_role 1
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 7 
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,W/bt-l2cap( 1788): l2cu_get_conn_role 1
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{42b52888 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{44643b28 type 3 android}
,D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 1 
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1788): l2cu_get_conn_role 1
,W/bt-btif ( 1788): info:x10
D/        ( 1788): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,V/AlarmManager( 1018): sending alarm Alarm{43c36800 type 3 android}
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1788): l2cu_get_conn_role 1
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1788): l2cu_get_conn_role 1
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1788): tBTM_SEC_DEV:0x5f2d96e4 rs_disc_pending=1
,W/bt-btif ( 1788): bta_dm_check_av:0
,W/bt-btif ( 1788): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1788): tBTM_SEC_DEV:0x5f2d98a0 rs_disc_pending=0
,W/bt-btif ( 1788): bta_dm_check_av:0
,W/bt-btif ( 1788): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1788): RS in progress - Set DISC Pending flag in btm_sec_send_hci_disconnect to delay disconnect
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-btm  ( 1788): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 1788): tBTM_SEC_DEV:0x5f2d98a0 rs_disc_pending=2
E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 1788): bta_dm_check_av:0
W/bt-btif ( 1788): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1788): l2cu_get_conn_role 0
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{447117a0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42dcba10 type 1 com.android.deskclock}
,I/LaunchCheckinHandler( 1018): cleanup(): cleared. Last call was 288294 ms ago
,I/ActivityManager( 1018): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=5009 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1018): Killing 4666:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/bt-l2cap( 1788): l2cu_get_conn_role 0
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [08:ec:a9:50:76:27]: 7, f, 6109
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1788): l2cu_get_conn_role 1
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [34:fc:ef:11:ae:67]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1788): tBTM_SEC_DEV:0x5f2d9a5c rs_disc_pending=1
,W/bt-btif ( 1788): bta_dm_check_av:0
,W/bt-btif ( 1788): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1788): tBTM_SEC_DEV:0x5f2d9c18 rs_disc_pending=0
,W/bt-btif ( 1788): bta_dm_check_av:0
,W/bt-btif ( 1788): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1788): tBTM_SEC_DEV:0x5f2d9c18 rs_disc_pending=0
,W/bt-btif ( 1788): bta_dm_check_av:0
,W/bt-btif ( 1788): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [08:ec:a9:50:76:27]: 7, f, 6109
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1788): tBTM_SEC_DEV:0x5f2d9c18 rs_disc_pending=1
,W/bt-btif ( 1788): bta_dm_check_av:0
,W/bt-btif ( 1788): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1788): l2cu_get_conn_role 1
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1788): l2cu_get_conn_role 1
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [58:3f:54:73:64:c0]: 7, f, 6109
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [08:ec:a9:50:76:27]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1788): tBTM_SEC_DEV:0x5f2d98a0 rs_disc_pending=0
,W/bt-btif ( 1788): bta_dm_check_av:0
,W/bt-btif ( 1788): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1788): l2cu_get_conn_role 0
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1788): l2cu_get_conn_role 0
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,V/AlarmManager( 1018): sending alarm Alarm{44526428 type 3 android}
,W/bt-l2cap( 1788): l2cu_get_conn_role 1
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,V/AlarmManager( 1018): sending alarm Alarm{43e3aac0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{449a5028 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42dc9770 type 2 android}
,D/dalvikvm( 1018): GC_CONCURRENT freed 2147K, 65% free 18141K/50776K, paused 5ms+9ms, total 90ms
,D/dalvikvm( 1018): WAIT_FOR_CONCURRENT_GC blocked 46ms
,I/PeopleSync( 1408): onPerformSync() [5005f081]
,I/PeopleSync( 1408): Setting subscription: result=true [5005f081]
,D/dalvikvm( 1370): GC_EXPLICIT freed 545K, 41% free 10313K/17224K, paused 2ms+4ms, total 30ms
,I/PeopleSync( 1408): Starting sync, feed=null [5005f081]
,D/dalvikvm( 1408): GC_CONCURRENT freed 2047K, 30% free 12061K/17224K, paused 6ms+5ms, total 46ms
,I/GoogleURLConnFactory( 1408): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 1408): Using Auth Proxy for data requests.
,W/BaseAppContext( 1408): Using Auth Proxy for data requests.
,V/NativeCrypto( 1408): SSL shutdown failed: ssl=0x6b4c0800: I/O error during system call, Connection timed out
,W/BaseAppContext( 1408): Using Auth Proxy for data requests.
,I/PeopleSync( 1408): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1370): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,E/dalvikvm( 1370): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 1370): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 1370): VFY: replacing opcode 0x1f at 0x0011
I/dalvikvm( 1370): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1370): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1370): VFY: replacing opcode 0x6e at 0x003d
,I/ActivityManager( 1018): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=5044 uid=10064 gids={50064, 3003, 1028, 1015}
,D/ActivityThread( 5044): Loading provider com.android.gmail.ui: com.google.android.gm.provider.GmailProvider
,W/GAV2    ( 5044): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/dalvikvm( 1408): Jit: resizing JitTable from 4096 to 8192
,I/Gmail   ( 5044): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5044): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5044): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5044): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5044): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 13077, normalSync: true
,I/dalvikvm( 1370): Total arena pages for JIT: 11
,D/dalvikvm( 1408): GC_CONCURRENT freed 1744K, 29% free 12272K/17224K, paused 4ms+5ms, total 44ms
,I/PeopleSync( 1408): Sync finished, successful=true, took 1821ms
,I/PeopleContactsSync( 1408): CP2 sync start [5005f081]
,I/PeopleContactsSync( 1408): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/PeopleContactsSync( 1408): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/PeopleContactsSync( 1408): CP2 cleanup done, kept= duration=34 ms
,I/PeopleContactsSync( 1408): ===CP2 sync finished, success=true, time=46,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,I/PeopleSync( 1408): ***Sync finished***, duration: 2260 [5005f081]
,I/ActivityManager( 1018): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=5095 uid=10065 gids={50065, 3003}
,W/AbstractGoogleClient( 5095): Application name is not set. Call Builder#setApplicationName.
,I/ActivityManager( 1018): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5109 uid=10008 gids={50008, 3003, 1028, 1015}
,I/CalendarProvider2( 5109): Created com.android.providers.calendar.CalendarAlarmManager@42841c88(com.android.providers.calendar.CalendarProvider2@42839840)
,D/dalvikvm( 1018): GC_EXPLICIT freed 954K, 65% free 18035K/50776K, paused 4ms+8ms, total 88ms
,I/CalendarProvider2( 5109): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5109): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager( 1018): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5130 uid=10007 gids={50007, 3003}
,D/dalvikvm(  274): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+2ms, total 35ms
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
,D/ExtensionsFactory( 5130): No custom extensions.
,D/AlertReceiver( 5130): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 18ms
,D/AlertUtils( 5130): Flushing old alerts from shared prefs table
,D/AlertService( 5130): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/dalvikvm( 5044): GC_EXPLICIT freed 5133K, 44% free 9742K/17224K, paused 4ms+4ms, total 49ms
,I/Gmail   ( 5044): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 13146, normalSync: true
,I/Gmail   ( 5044): lowestBackward conversation id 0
,I/ActivityManager( 1018): Killing 4749:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1370): GC_EXPLICIT freed 1027K, 40% free 10376K/17224K, paused 2ms+4ms, total 29ms
,D/CalendarSyncAdapter( 5095): Found 0 events marked dirty & lastSynced
,I/ActivityManager( 1018): Killing 4844:com.google.android.talk/u0a70 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for service com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.service.SyncAdapterService: pid=5193 uid=10076 gids={50076, 3003, 1028, 1015}
,V/WebViewChromiumFactoryProvider( 5193): Binding Chromium to main looper Looper (main, tid 1) {4281fd68}
,I/LibraryLoader( 5193): Expected native library version number "",actual native library version number ""
,I/chromium( 5193): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5193): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 5193): BLUETOOTH permission is missing!
,I/Adreno-EGL( 5193): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5193): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5193): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5193): Local Branch: 
I/Adreno-EGL( 5193): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5193): Local Patches: NONE
I/Adreno-EGL( 5193): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 5193): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 5193): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  260): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  260): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5193): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 5193): Starting up...
,I/ActivityManager( 1018): Killing 4900:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=5242 uid=10056 gids={50056, 3003, 1028, 1015}
,D/DelayedSyncController( 5242): Delaying sync.
I/ActivityManager( 1018): Killing 3936:com.google.android.apps.plus/u0a90 (adj 15): empty #9
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/BaseAppContext( 1408): Using Auth Proxy for data requests.
,W/BaseAppContext( 1408): Using Auth Proxy for data requests.
,W/BaseAppContext( 1408): Using Auth Proxy for data requests.
,W/BaseAppContext( 1408): Using Auth Proxy for data requests.
,W/BaseAppContext( 1408): Using Auth Proxy for data requests.
,W/BaseAppContext( 1408): Using Auth Proxy for data requests.
,W/BaseAppContext( 1408): Using Auth Proxy for data requests.
,I/ActivityManager( 1018): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=5264 uid=10059 gids={50059, 3003, 1028, 1015}
,W/ActiveOrDefaultContextProvider( 5264): Missing scope.enter somewhere. Returning default context
,W/GAV2    ( 5264): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/ActivityThread( 5264): Failed to find provider info for com.google.android.apps.docs.editors.kix.statesyncer
,E/ActivityThread( 5264): Failed to find provider info for com.google.android.apps.docs.editors.trix.statesyncer
E/ActivityThread( 5264): Failed to find provider info for com.google.android.apps.docs.editors.punch.statesyncer
,E/ActivityThread( 5264): Failed to find provider info for com.google.android.apps.docs.editors.drawings.statesyncer
,D/WifiService( 1018): acquireWifiLockLocked: WifiLock{DocsSyncAdapter type=1 binder=android.os.BinderProxy@42a03008}
,I/ActivityManager( 1018): Killing 4952:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=5308 uid=10100 gids={50100, 3003, 1028, 1015, 3002}
,D/PlayMovies( 5308): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,I/MediaRouter( 5308): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/PlayMovies( 5308): MediaRouteManager.restoreRoute:197 sessionRestore routeId: 
,D/PlayMovies( 5308): MediaRouteManager.onRouteSelected:151 routeInfo: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/PlayMovies( 5308): TransferService.onCreate:52 creating transfer service
,D/PlayMovies( 5308): MediaRouteManager.onRouteAdded:138 new route added android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE
,D/PlayMovies( 5308): MediaRouteManager.onRouteSelected:151 routeInfo: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/GAV2    ( 5044): Thread[GAThread,5,main]: No campaign data found.
,E/cutils  (  260): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  260): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5308): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.videos/files/Movies
,W/GAV2    ( 5264): DocsSyncAdapter-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/WifiService( 1018): releaseWifiLockLocked: WifiLock{DocsSyncAdapter type=1 binder=android.os.BinderProxy@42a03008}
,I/ActivityManager( 1018): Killing 4918:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Start proc com.google.android.apps.cloudprint:sync for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService: pid=5360 uid=10057 gids={50057, 3003, 1028}
,D/dalvikvm( 1018): GC_EXPLICIT freed 1232K, 65% free 18079K/50772K, paused 4ms+9ms, total 93ms
,I/PlayMovies( 5308): SyncService.syncAllPurchases:159 Starting sync for thalitester@gmail.com
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/com.google.android.apps.common.multidex.Tracer( 5360): Checking if extracted archive /data/data/com.google.android.apps.cloudprint/files/secondary0.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 5360): Extracted file last modified: Aug 24, 2015 8:20:50.0
V/com.google.android.apps.common.multidex.Tracer( 5360): Package last updated: Jul 8, 2014 5:38:19.0
,V/com.google.android.apps.common.multidex.Tracer( 5360): Checking if extracted archive /data/data/com.google.android.apps.cloudprint/files/secondary1.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 5360): Extracted file last modified: Aug 24, 2015 8:20:50.0
V/com.google.android.apps.common.multidex.Tracer( 5360): Package last updated: Jul 8, 2014 5:38:19.0
,V/com.google.android.apps.common.multidex.Tracer( 5360): Attempting to patch the classloader using the following patchers [com.google.android.apps.common.multidex.KlpClassLoaderExtender@42836520, com.google.android.apps.common.multidex.IcsClassLoaderExtender@42837290, com.google.android.apps.common.multidex.PreIcsClassLoaderExtender@428375e8]
,V/com.google.android.apps.common.multidex.Tracer( 5360): Trying com.google.android.apps.common.multidex.KlpClassLoaderExtender@42836520.
,V/com.google.android.apps.common.multidex.Tracer( 5360): Patching was successful.
,I/ActivityManager( 1018): Start proc com.google.android.apps.cloudprint for content provider com.google.android.apps.cloudprint/.printdialog.database.CloudPrintContentProvider: pid=5375 uid=10057 gids={50057, 3003, 1028}
,V/com.google.android.apps.common.multidex.Tracer( 5375): Checking if extracted archive /data/user/0/com.google.android.apps.cloudprint/files/secondary0.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 5375): Extracted file last modified: Aug 24, 2015 8:20:50.0
V/com.google.android.apps.common.multidex.Tracer( 5375): Package last updated: Jul 8, 2014 5:38:19.0
,V/com.google.android.apps.common.multidex.Tracer( 5375): Checking if extracted archive /data/user/0/com.google.android.apps.cloudprint/files/secondary1.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 5375): Extracted file last modified: Aug 24, 2015 8:20:50.0
V/com.google.android.apps.common.multidex.Tracer( 5375): Package last updated: Jul 8, 2014 5:38:19.0
,V/com.google.android.apps.common.multidex.Tracer( 5375): Attempting to patch the classloader using the following patchers [com.google.android.apps.common.multidex.KlpClassLoaderExtender@4283a6e8, com.google.android.apps.common.multidex.IcsClassLoaderExtender@4283b458, com.google.android.apps.common.multidex.PreIcsClassLoaderExtender@4283b7b0]
,V/com.google.android.apps.common.multidex.Tracer( 5375): Trying com.google.android.apps.common.multidex.KlpClassLoaderExtender@4283a6e8.
,V/com.google.android.apps.common.multidex.Tracer( 5375): Patching was successful.
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PlayMovies( 5308): SyncService$3.onResponse:164 Sync completed for thalitester@gmail.com
,I/ActivityManager( 1018): Killing 5009:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/BaseAppContext( 1220): Using Auth Proxy for data requests.
,E/BaseAppContext( 1220): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1220): GC_CONCURRENT freed 2092K, 34% free 11526K/17224K, paused 4ms+7ms, total 43ms
,I/GCoreUlr( 1220): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/GCoreUlr( 1220): DispatchingService.onCreate()
,I/ActivityManager( 1018): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.apps.youtube.app.offline.sync.OfflineSyncService: pid=5412 uid=10102 gids={50102, 3003, 1028, 1015}
,I/GlobalDismissManager( 5130): no sender configured
,D/AlertService( 5130): Beginning updateAlertNotification
,D/AlertService( 5130): No fired or scheduled alerts
,D/AlertService( 5130): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 5130): No events found starting within 1 week.
I/ActivityManager( 1018): Killing 5109:com.android.providers.calendar/u0a8 (adj 15): empty #9
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1370): GC_EXPLICIT freed 1313K, 39% free 10636K/17224K, paused 5ms+12ms, total 56ms
,I/GCoreUlr( 1220): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1220): Unbound from all location providers
,I/GCoreUlr( 1220): Place inference reporting - stopped
,D/YouTube ( 5412): apps.youtube.common.network.l.a:40 HttpClient.UserAgent: com.google.android.youtube/5.6.36(Linux; U; Android 4.4.4; en_GB; XT1039 Build/KXB21.14-L1.46)
,I/GCoreUlr( 1220): DispatchingService.onDestroy()
,I/GCoreUlr( 1220): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1220): Unbound from all location providers
,I/GCoreUlr( 1220): Place inference reporting - stopped
,I/ActivityManager( 1018): Killing 5044:com.google.android.gm/u0a64 (adj 15): empty #9
,I/ActivityManager( 1018): Killing 5130:com.android.calendar/u0a7 (adj 15): empty #10
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,E/cutils  (  260): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  260): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5412): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,E/cutils  (  260): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  260): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5412): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,D/YouTube ( 5412): apps.youtube.common.network.l.a:40 HttpClient.UserAgent: com.google.android.youtube/5.6.36(Linux; U; Android 4.4.4; en_GB; XT1039 Build/KXB21.14-L1.46)
,D/YouTube ( 5412): apps.youtube.common.network.l.a:40 HttpClient.UserAgent: com.google.android.youtube/5.6.36(Linux; U; Android 4.4.4; en_GB; XT1039 Build/KXB21.14-L1.46)
,E/Auth.Api.Credentials( 1408): [CredentialSyncAdapter] Unknown sync event.
,I/ActivityManager( 1018): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5452 uid=10008 gids={50008, 3003, 1028, 1015}
,D/YouTube ( 5412): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
,I/CalendarProvider2( 5452): Created com.android.providers.calendar.CalendarAlarmManager@4283fd68(com.android.providers.calendar.CalendarProvider2@42837920)
,D/YouTube ( 5412): apps.youtube.core.player.Director.c:360 VideoStage: NEW
,I/MediaRouter( 5412): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/YouTube ( 5412): apps.youtube.core.client.s.a:114 event [version=5.6.36-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
,I/GoogleConversionPing( 5412): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=OOR12PiaL5kcBDCoRWtvsQ&bundleid=com.google.android.youtube&appversion=5.6.36&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1450446498&data=screen_name%3D%3CAndroid_YT_Open_App%3E
,D/YouTube ( 5412): apps.youtube.app.offline.sync.OfflineSyncService.onCreate:21 PUDL creating sync service for the 1st time
,W/YouTube ( 5412): apps.youtube.app.offline.sync.OfflineSyncService.onBind:28 PUDL binding sync adapter
,D/YouTube ( 5412): apps.youtube.app.offline.sync.a.onPerformSync:60 OfflineSyncAdapter.onPerformSync() called!
,D/YouTube ( 5412): apps.youtube.common.d.d.a:25 Executing ConditionTask com.google.android.apps.youtube.datalib.offline.h
,D/YouTube ( 5412): apps.youtube.datalib.offline.h.a:34 Network change detected, dispatch offline http requests.
,D/YouTube ( 5412): apps.youtube.common.d.j.e:170 Scheduling task com.google.android.apps.youtube.datalib.offline.o with ScheduledExecutorService for repeating execution.
,V/CalendarSyncAdapter( 5095): Saving inProgress state: {calendarId=thalitester@gmail.com, maxAttendees=50, maxResults=200, timeMax=2016-12-25T00:00:00.000Z, updatedMin=2015-11-18T16:31:02.459Z}
,D/CalendarSyncAdapter( 5095): Found 0 events marked dirty & lastSynced
,I/ActivityManager( 1018): Killing 5193:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/GoogleConversionPing( 5412): Ping responded with response code 200
,I/CalendarProvider2( 5452): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5452): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager( 1018): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5501 uid=10007 gids={50007, 3003}
,I/ActivityManager( 1018): Killing 5242:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ExtensionsFactory( 5501): No custom extensions.
,D/AlertReceiver( 5501): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 5501): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/dalvikvm( 1018): GC_EXPLICIT freed 834K, 65% free 18062K/50772K, paused 3ms+9ms, total 89ms
,I/GAV2    ( 5264): Thread[GAThread,5,main]: No campaign data found.
,I/GlobalDismissManager( 5501): no sender configured
,D/AlertService( 5501): Beginning updateAlertNotification
,D/AlertService( 5501): No fired or scheduled alerts
,D/AlertService( 5501): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 5501): No events found starting within 1 week.
I/ActivityManager( 1018): Killing 4881:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
,I/ActivityManager( 1018): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5532 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
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
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
,I/Launcher( 1311): Deferring update until onResume
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
,I/Launcher( 1311): Deferring update until onResume
,I/ActivityManager( 1018): Killing 5264:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5559 uid=10033 gids={50033, 3003, 1028, 1015}
,D/dalvikvm(  274): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 21ms
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 18ms
,I/InternalIcingCorporaPro( 2320): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,I/ActivityManager( 1018): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5576 uid=10090 gids={50090, 3003, 3002, 1028, 1015}
,I/ActivityManager( 1018): Killing 5308:com.google.android.videos/u0a100 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 5532): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/InternalIcingCorporaPro( 2320): UpdateCorporaTask done [took 66 ms] updated apps [took 66 ms] 
,I/ActivityManager( 1018): Start proc android.process.media for content provider com.android.providers.media/.MediaProvider: pid=5591 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/ActivityManager( 1018): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5607 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1018): Killing 5360:com.google.android.apps.cloudprint:sync/u0a57 (adj 15): empty #9
,I/ActivityManager( 1018): Killing 5375:com.google.android.apps.cloudprint/u0a57 (adj 15): empty #10
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.UploadsManager( 5576): #reloadSettings(); account: null; pageID: none; IU: disabled; IS: disabled; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,D/dalvikvm( 5591): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x42829048, skipping init
I/openssl ( 5591): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 5591): Crypto mode 0 already enabled
I/dalvikvm( 5607): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 5607): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 5607): VFY: replacing opcode 0x6e at 0x000e
,I/iu.UploadsManager( 5576): End new media; added: 0, uploading: 0, time: 51 ms
,D/Finsky  ( 5607): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/iu.Environment( 5576): update battery state; isPlugged? true*
,I/iu.Environment( 5576): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.FingerprintManager( 5576): Start processing all media
,I/iu.FingerprintManager( 5576): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 5576): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 5576): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 5576): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 5576): Finished generating fingerprints; 0.018 seconds
,I/iu.FingerprintManager( 5576):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/dalvikvm( 5607): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
,W/dalvikvm( 5607): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5607): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 5607): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 5607): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 5607): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 5607): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 5607): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 5607): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 5607): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 5607): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5607): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 5607): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5607): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5607): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 5607): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5607): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5607): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 5607): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5607): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5607): VFY: replacing opcode 0x6e at 0x0385
,I/dalvikvm( 5607): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 5607): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5607): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 5607): Skipping gmscore version check
,D/Finsky  ( 5607): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5607): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5607): [1] Libraries$2.run: Finished loading 1 libraries.
,I/dalvikvm( 5607): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 5607): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 5607): VFY: replacing opcode 0x6e at 0x0017
,D/PackageBroadcastService( 1408): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,D/Finsky  ( 5607): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1018): Killing 5452:com.android.providers.calendar/u0a8 (adj 15): empty #9
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Icing   ( 1408): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1408): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1205): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450446507
,D/YouTube ( 5412): apps.youtube.common.d.j.e:170 Scheduling task com.google.android.apps.youtube.datalib.offline.o with ScheduledExecutorService for repeating execution.
,D/YouTube ( 5412): apps.youtube.common.d.j.e:170 Scheduling task com.google.android.apps.youtube.datalib.offline.q with ScheduledExecutorService for repeating execution.
,V/AlarmManager( 1018): sending alarm Alarm{430beb30 type 2 android}
,W/IcingInternalCorpora( 1408): getNumBytesRead when not calculated.
,D/YouTube ( 5412): apps.youtube.common.d.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.offline.o
,D/YouTube ( 5412): apps.youtube.common.d.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.offline.o
,D/YouTube ( 5412): apps.youtube.datalib.offline.o.a:55 Flushing offline queue.
,D/YouTube ( 5412): apps.youtube.datalib.offline.o.a:55 Flushing offline queue.
,V/AlarmManager( 1018): sending alarm Alarm{430bda00 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43062c28 type 2 android}
,I/ActivityManager( 1018): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=5681 uid=10059 gids={50059, 3003, 1028, 1015}
,W/ActiveOrDefaultContextProvider( 5681): Missing scope.enter somewhere. Returning default context
,W/GAV2    ( 5681): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/GAV2    ( 5681): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager( 1018): Killing 5412:com.google.android.youtube/u0a102 (adj 15): empty #9
W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 ,
,I/GAV2    ( 5681): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 1018): sending alarm Alarm{4450d1c8 type 2 android}
,V/AlarmManager( 1018): sending alarm Alarm{446f66d0 type 3 android}
,I/ClearcutLoggerApiImpl( 1408): disconnect managed GoogleApiClient
,V/AlarmManager( 1018): sending alarm Alarm{446cd1c0 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{430def70 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,W/bt-l2cap( 1788): l2cu_get_conn_role 1
,W/bt-btif ( 1788): info:x10
D/        ( 1788): remote version info [34:fc:ef:11:ae:67]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1788): l2cu_get_conn_role 1
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1788): l2cu_get_conn_role 1
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [58:3f:54:73:64:c0]: 7, f, 6109
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1788): l2cu_get_conn_role 1
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [34:fc:ef:11:ae:67]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,W/bt-l2cap( 1788): l2cu_get_conn_role 1
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [58:3f:54:73:64:c0]: 7, f, 6109
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,V/AlarmManager( 1018): sending alarm Alarm{42b3eea0 type 3 android}
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1788): l2cu_get_conn_role 1
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [34:fc:ef:11:ae:67]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1788): l2cu_get_conn_role 1
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [58:3f:54:73:64:c0]: 7, f, 6109
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [34:fc:ef:11:ae:67]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1788): tBTM_SEC_DEV:0x5f2d9c18 rs_disc_pending=1
,W/bt-btif ( 1788): bta_dm_check_av:0
,W/bt-btif ( 1788): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1788): tBTM_SEC_DEV:0x5f2d9a5c rs_disc_pending=0
,W/bt-btif ( 1788): bta_dm_check_av:0
,W/bt-btif ( 1788): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 1788): l2cu_get_conn_role 0
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1788): tBTM_SEC_DEV:0x5f2d9c18 rs_disc_pending=0
,W/bt-btif ( 1788): bta_dm_check_av:0
,W/bt-btif ( 1788): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1788): l2cu_get_conn_role 1
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,V/AlarmManager( 1018): sending alarm Alarm{431c29b8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{445b0198 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{430ba510 type 2 android}
,V/AlarmManager( 1018): sending alarm Alarm{430b6750 type 2 com.google.android.gms}
,D/ConnectivityService( 1018): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1018): Done.
,D/ConnectivityService( 1018): Setting timer for 720seconds
,D/ConnectivityService( 1018): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/ModemStatsDSDetect( 1299): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1299): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1299): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,V/AlarmManager( 1018): sending alarm Alarm{44665c30 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4507fb30 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{44665d08 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{44665de0 type 2 com.motorola.ccc.cce}
,V/AlarmManager( 1018): sending alarm Alarm{450816d8 type 3 com.google.android.gms}
,D/MMApiProvisionService( 1569): Got session expired event.. obtaining new session
,D/MMApiProvisionService( 1569): createDeviceIdOrLogin(): Got request to login .. processing now
,I/BSUtils ( 1569): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/ProcessStatsService( 1018): Prepared write state in 13ms
,D/MMApiWebService( 1569): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1569): generating token using payload instead of using session token
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MMApiWSBase( 1569): doRequest(): url: https://api.svcmot.com:443/v1/dp/devices.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1569): publish the event [tag = MOT_CCE event name = LOG]
,I/ProcessStatsService( 1018): Pruning old procstats: /data/system/procstats/state-2015-12-17-18-43-27.bin
,D/dalvikvm( 1370): GC_EXPLICIT freed 622K, 39% free 10580K/17224K, paused 3ms+5ms, total 39ms
,D/MMApiProvisionService( 1569): ProvisionWS.Response: processing response data: {"sessionToken":"0-62d6271415ae24024c051b549cbffe5b3369896958","error":"OK","sessionExpiration":"172742","deviceId":"1135300315450105856"}
,D/MMApiProvisionService( 1569): ProvisionWS.Response: Completed parsing response.. no settings sent by server
,D/MMApiWSBase( 1569): doRequest(): /v1/dp/devices.json resp length: 138
,D/MMApiProvisionService( 1569): MMApiProvisionService.handleResponse (update_device) : true (None)
,D/MMApiProvisionService( 1569): handleResponse(): Session Expiration alarm set to expire at: Sun Dec 20 14:56:29 CET 2015
,D/MMApiProvisionService( 1569): _setMMApiCredInfo: storing credential info 
,E/MMApiProvisionService( 1569): handleResponse(): no settings sent by the server:
,D/Checkin ( 1569): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1569): MMApiWebService told us to retry waiting request since device is successfully provisioned: 0
,D/DEBUG   ( 1569): Received intent : com.motorola.notification.RETREIVE_NOTIFICATIONS
,W/ContextImpl( 1569): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1569): bindWebServices(): registering our AIDL callback...
,D/GetNotificationsWS( 1569): onServiceConnected()
D/GetNotificationsWS( 1569): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1569): onHandleIntent(): action=com.motorola.notification.RETREIVE_NOTIFICATIONS
,I/SundryService( 1569): Received shoulder tap
,D/WaitableIntentService( 1569): setWaitEnabled(): mWaitCount=1 isWaitEnabled=true
,D/GetNotificationsWS( 1569): GetNotificationsWS.Request: message={"request":{"appendDeviceId":true,"baseUrl":"v1\/ns\/list\/messages","queryParams":{"appid":"MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ"},"httpMethod":"post","requestFormat":"json","wsReqId":"com.motorola.ccc.notification.GetNotificationsWS.Request","isSecure":true,"payload":{"data":"{\"appidNotifStoreMessageidPageSizeList\":[{\"appid\":\"LX6TJJI6F2MILF1NPZW6A3HBAKK8W44Z\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SULIGJDMXLSL7T1DOVYSTVG2KCBHZ5GH\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"6U5KK17SNFB416J4SYG7LC6HYFNOPYM8\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"68OUD4VKG23F7BUH6M2QBRXPLIC7IMCO\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SZZTNOGZA6O6PRFZH2V3FF14N1J8W3HC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"D9DF2F5BB1FA45B0BA459B7FE6942DCD\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"RCEAZODHQBX3UTIE62BUQ6T6TXXI6JSR\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"L71KGK4CCWOW658MGESIRYO2428ODW11\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"OCVKVSQ5Q1EYVBX76813UOPTCKGAH4VS\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"B642GFV24HEMEDQNCF3ZED8BIUMPCBOM\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"5LWTCLJBZO4OUDU5BY7ANJI4Y2MHY8OY\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"TESULHNZGDWZ5T3EMNZRTVE51RR7EUXC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"QZYSBKU4MGE71O1PLTE8HAT11SWL5M6E\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"XX274VEJBOVSSPHDKHSPURVRQ1YT5VEM\",\"pageSize\":100,\"notifStoreMessageid\":0}]}","type":"json"},"retries":"-1","useOAuth":true}}
,D/GetNotificationsWS( 1569): sendAidlRequest(): was sent by CCE successfully!
,D/WaitableIntentService( 1569): ServiceHandler.handleMessage: mWaitCount=1
,D/MMApiWebService( 1569): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,I/MMApiWSBase( 1569): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1569): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWSBase( 1569): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1569): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1569): AppWSProxy - sendAIDLWSResponse() sending reponse
,D/Checkin ( 1569): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1569): handleGetNotificationsResponse(): got 0; more=false
,D/DEBUG   ( 1569): Received intent : com.motorola.ccc.notification.action.NOTIFY
,I/SundryService( 1569): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1569): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1569): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1569): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1569): unbindWebServices(): un-registering our AIDL callback...
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{4381f850 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{430181f0 type 3 android}
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,W/bt-l2cap( 1788): l2cu_get_conn_role 1
,W/bt-btif ( 1788): info:x10
,D/        ( 1788): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,D/btif_config_util( 1788): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1788): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1788): aclStateChangeCallback: Device is NULL
,V/AlarmManager( 1018): sending alarm Alarm{4462fa40 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{45081728 type 1 com.android.deskclock}
,I/ActivityManager( 1018): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=5766 uid=10015 gids={50015, 1028}
,D/dalvikvm( 1018): GC_EXPLICIT freed 1724K, 65% free 18200K/50772K, paused 4ms+10ms, total 100ms
,I/ActivityManager( 1018): Killing 5095:com.google.android.syncadapters.calendar/u0a65 (adj 15): empty #9
,W/ContextImpl( 1266): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{4469add8 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{449f5c20 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{449f56e8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4497e150 type 3 android}

```
