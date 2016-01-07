#### Test 55311151a2306df_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
D/Finsky  ( 3465): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1549666, pollInterval: 10000
,D/AndroidRuntime( 3988): 
D/AndroidRuntime( 3988): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3988): CheckJNI is OFF
D/dalvikvm( 3988): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3988): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3988): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3988): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3988): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3988): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3988): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3988): failed to load memtrack module: -2
D/AndroidRuntime( 3988): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1014): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3988
W/WindowManager( 1014): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1014): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4005 uid=10519 gids={50519, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3988): Shutting down VM
D/dalvikvm( 3988): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1267): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1267): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4005): Binding Chromium to main looper Looper (main, tid 1) {42669e08}
I/LibraryLoader( 4005): Expected native library version number "",actual native library version number ""
I/chromium( 4005): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4005): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1014): Message: 20
D/BluetoothManagerService( 1014): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@440ea498:true
I/Adreno-EGL( 4005): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4005): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4005): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4005): Local Branch: 
I/Adreno-EGL( 4005): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4005): Local Patches: NONE
I/Adreno-EGL( 4005): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4005): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4005): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4005): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4005): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4005): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4005): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4005): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4005): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4005): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4005): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4005): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4005): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4005): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4005): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4005): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4005): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4005): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4005): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4005): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4005): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4005): Enabling debug mode 0
,W/AwContents( 4005): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1014): Displayed com.test.thalitest/.MainActivity,cp,ca,394
I/ActivityManager( 1014): Displayed com.test.thalitest/.MainActivity: +366ms (total +394ms)
W/AwContents( 4005): nativeOnDraw failed; clearing to background color.
W/IInputConnectionWrapper( 4005): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 4005): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4005): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4266e0d8
,D/dalvikvm( 4005): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4266e0d8
,D/jxcore_app_log( 4005): JniHelper::setJavaVM(0x41d86f78), pthread_self() = 1614024784
,D/JX-Cordova( 4005): jxcore cordova android initializing
,D/dalvikvm( 4005): GC_CONCURRENT freed 2734K, 17% free 14422K/17224K, paused 3ms+5ms, total 45ms
,D/dalvikvm( 4005): GC_FOR_ALLOC freed 220K, 17% free 14450K/17224K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4005): Grow heap (frag case) to 16.205MB for 64402-byte allocation
,D/dalvikvm( 4005): GC_FOR_ALLOC freed 138K, 17% free 14458K/17288K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4005): Grow heap (frag case) to 16.244MB for 96598-byte allocation
,D/dalvikvm( 4005): GC_FOR_ALLOC freed 180K, 17% free 14493K/17384K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4005): Grow heap (frag case) to 16.324MB for 144892-byte allocation
,D/dalvikvm( 4005): GC_FOR_ALLOC freed 254K, 18% free 14540K/17528K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4005): Grow heap (frag case) to 16.439MB for 217334-byte allocation
,D/dalvikvm( 4005): GC_FOR_ALLOC freed 371K, 18% free 14615K/17744K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4005): Grow heap (frag case) to 16.616MB for 325996-byte allocation
,D/dalvikvm( 4005): GC_FOR_ALLOC freed 572K, 19% free 14737K/18064K, paused 26ms, total 26ms
,D/dalvikvm( 4005): GC_FOR_ALLOC freed 872K, 18% free 14914K/18064K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4005): Grow heap (frag case) to 17.295MB for 733480-byte allocation
,D/dalvikvm( 4005): GC_FOR_ALLOC freed 1293K, 20% free 15171K/18784K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4005): Grow heap (frag case) to 17.897MB for 1100216-byte allocation
,D/dalvikvm( 4005): GC_CONCURRENT freed 1761K, 22% free 15553K/19860K, paused 2ms+3ms, total 41ms
,D/dalvikvm( 4005): GC_FOR_ALLOC freed 306K, 22% free 15491K/19860K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4005): Grow heap (frag case) to 18.734MB for 1650320-byte allocation
,D/dalvikvm( 4005): GC_CONCURRENT freed 1805K, 26% free 16097K/21472K, paused 1ms+6ms, total 48ms
,D/dalvikvm( 4005): GC_FOR_ALLOC freed 1238K, 25% free 16126K/21472K, paused 30ms, total 30ms
I/dalvikvm-heap( 4005): Grow heap (frag case) to 20.141MB for 2475476-byte allocation
D/dalvikvm( 4005): GC_CONCURRENT freed 266K, 23% free 18466K/23892K, paused 5ms+3ms, total 47ms
D/dalvikvm( 4005): GC_CONCURRENT freed 4383K, 29% free 17133K/23892K, paused 1ms+7ms, total 56ms
D/dalvikvm( 4005): WAIT_FOR_CONCURRENT_GC blocked 52ms
I/dalvikvm-heap( 4005): Grow heap (frag case) to 22.305MB for 3713210-byte allocation
D/dalvikvm( 4005): GC_CONCURRENT freed 2704K, 35% free 18156K/27520K, paused 2ms+5ms, total 53ms
D/dalvikvm( 4005): GC_FOR_ALLOC freed 963K, 35% free 18102K/27520K, paused 29ms, total 29ms
W/jxcore-log( 4005): Initializing JXcore engine
W/jxcore-log( 4005): JXcore engine is ready
D/dalvikvm( 4005): GC_CONCURRENT freed 349K, 25% free 20775K/27520K, paused 3ms+2ms, total 34ms
D/dalvikvm( 4005): WAIT_FOR_CONCURRENT_GC blocked 25ms
W/jxcore-log( 4005): Starting JXcore engine
W/jxcore-log( 4005): Platform android
W/jxcore-log( 4005): 
W/jxcore-log( 4005): Process ARCH arm
W/jxcore-log( 4005): 
,I/jxcore-log( 4005): JXcore Cordova bridge is ready!
I/jxcore-log( 4005): 
,W/jxcore-log( 4005): JXcore engine is started
,I/chromium( 4005): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4005): Toggling radios to true
I/jxcore-log( 4005): 
,D/BluetoothAdapter( 4005): enable(): BT is already enabled..!
D/WifiService( 1014): New client listening to asynchronous messages
D/WifiService( 1014): setWifiEnabled: true pid=4005, uid=10519
,E/WifiService( 1014): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1014): handleMessage: E msg.what=131145
D/WifiStateMachine( 1014): processMsg: ConnectedState
D/WifiStateMachine( 1014): processMsg: L2ConnectedState
I/jxcore-log( 4005): Radios toggled
I/jxcore-log( 4005): 
D/BluetoothManagerService( 1014): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1014): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4005): Received device characteristics:
I/jxcore-log( 4005): Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4005): Bluetooth name: XT1039
I/jxcore-log( 4005): Device name: motorola-XT1039
I/jxcore-log( 4005): 
I/jxcore-log( 4005): Perf Test app loaded loaded
I/jxcore-log( 4005): 
,I/jxcore-log( 4005): check test folder
I/jxcore-log( 4005): 
,I/jxcore-log( 4005): found test : ./testFindPeers.js
I/jxcore-log( 4005): 
,I/wpa_supplicant( 1156): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/TCMD    (  539): NL - Read 1000 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
D/TCMD    (  539): Listening for incoming client connection request
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
D/TCMD    (  539): NL - Read 1000 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
D/TCMD    (  539): Listening for incoming client connection request
D/TCMD    (  539): NL - Read 68 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
D/TCMD    (  539): Listening for incoming client connection request
D/TCMD    (  539): NL - Read 68 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
D/TCMD    (  539): Listening for incoming client connection request
D/Tethering( 1014): InitialState.processMessage what=4
,D/Tethering( 1014): sendTetherStateChangedBroadcast 0, 0, 0
,V/ConnectivityService( 1014): WiFi NOT Tethered!
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  276): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
D/WifiStateMachine( 1014): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1014): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1014): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1014): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1014): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1014): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1014): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1014): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1014): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1156): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1156): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  272): Clearing all IP addresses on wlan0
D/TCMD    (  539): NL - Read 60 bytes from update socket.
D/TCMD    (  539): NL - ignore NL message, type = 21
,D/TCMD    (  539): Listening for incoming client connection request
,D/WifiStateMachine( 1014): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1014): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1014): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1014): connected time updated 307534
D/ConnectivityService( 1014): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1014): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/jxcore-log( 4005): found test : ./testSendData.js
I/jxcore-log( 4005): 
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/ConnectivityService( 1014): Attempting to switch to mobile
,D/ConnectivityService( 1014): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1014): Attempting to switch to ETHERNET
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/ConnectivityService( 1014): resetConnections(wlan0, 3)
D/WifiStateMachine( 1014): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1014): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1014): invokeEnterMethods: DisconnectingState
D/WifiStateMachine( 1014): DisconnectingState
D/NetUtils( 1014): android_net_utils_resetConnections in env=0x61174198 clazz=0x64900001 iface=wlan0 mask=0x3
E/wpa_supplicant( 1156): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1156): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1014): handleMessage: X
D/WifiStateMachine( 1014): handleMessage: E msg.what=131146
D/WifiStateMachine( 1014): processMsg: DisconnectingState
D/WifiStateMachine( 1014): processMsg: ConnectModeState
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
D/WifiStateMachine( 1014): handleMessage: X
D/WifiStateMachine( 1014): handleMessage: E msg.what=131101
D/WifiStateMachine( 1014): processMsg: DisconnectingState
D/WifiStateMachine( 1014): processMsg: ConnectModeState
D/WifiStateMachine( 1014): processMsg: DriverStartedState
D/WifiStateMachine( 1014): processMsg: SupplicantStartedState
D/Checkin ( 1014): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1014): processMsg: DefaultState
D/WifiStateMachine( 1014): handleMessage: X
D/WifiStateMachine( 1014): handleMessage: E msg.what=147460
D/WifiStateMachine( 1014): processMsg: DisconnectingState
D/WifiStateMachine( 1014): processMsg: ConnectModeState
D/WifiStateMachine( 1014): Network connection lost
D/WifiStateMachine( 1014): Stopping DHCP and clearing IP
D/WifiStateMachine( 1014): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1366): Read error: ssl=0x6304fc90: I/O error during system call, Connection timed out
,V/NativeCrypto( 1366): SSL shutdown failed: ssl=0x6304fc90: I/O error during system call, Broken pipe
,D/WifiP2pService( 1014): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1014): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1156): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1156): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  272): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1014): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1014): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1014): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1014): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1014): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1014): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1014): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1014): invokeEnterMethods: DisconnectedState
D/Checkin ( 1014): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1014): handleMessage: X
D/WifiStateMachine( 1014): handleMessage: E msg.what=147462
D/WifiStateMachine( 1014): processMsg: DisconnectedState
D/WifiStateMachine( 1014): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1014): processMsg: ConnectModeState
D/WifiStateMachine( 1014): handleMessage: X
D/WifiStateMachine( 1014): handleMessage: E msg.what=131216
D/WifiStateMachine( 1014): processMsg: DisconnectedState
D/WifiStateMachine( 1014): processMsg: ConnectModeState
D/WifiStateMachine( 1014): processMsg: DriverStartedState
D/WifiStateMachine( 1014): processMsg: SupplicantStartedState
D/WifiStateMachine( 1014): processMsg: DefaultState
D/WifiStateMachine( 1014): handleMessage: X
D/WifiStateMachine( 1014): handleMessage: E msg.what=131216
D/WifiStateMachine( 1014): processMsg: DisconnectedState
D/WifiStateMachine( 1014): processMsg: ConnectModeState
D/WifiStateMachine( 1014): processMsg: DriverStartedState
D/WifiStateMachine( 1014): processMsg: SupplicantStartedState
D/WifiStateMachine( 1014): processMsg: DefaultState
D/WifiStateMachine( 1014): handleMessage: X
D/WifiStateMachine( 1014): handleMessage: E msg.what=147462
D/WifiStateMachine( 1014): processMsg: DisconnectedState
D/WifiStateMachine( 1014): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1014): processMsg: ConnectModeState
D/WifiStateMachine( 1014): handleMessage: X
,D/Nat464Xlat( 1014): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityService( 1014): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1198): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1198): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1198): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1014): Attempting to switch to mobile
D/ConnectivityService( 1014): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1014): Attempting to switch to ETHERNET
D/Nat464Xlat( 1014): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityService( 1014): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1198): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1198): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1198): onReceive() - done, currentInetCondition=0
,I/chromium( 4005): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 1156): wlan0: Trying to associate with SSID 'NG700'
,D/WifiStateMachine( 1014): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1014): processMsg: DisconnectedState
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  276): Event received = Trying to associate with
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  539): NL - Read 56 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
,D/TCMD    (  539): Listening for incoming client connection request
,D/WifiStateMachine( 1014): processMsg: ConnectModeState
,D/WifiStateMachine( 1014): processMsg: DriverStartedState
,D/WifiStateMachine( 1014): processMsg: SupplicantStartedState
,E/wpa_supplicant( 1156): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1014): handleMessage: X
,D/WifiStateMachine( 1014): handleMessage: E msg.what=147462
D/WifiStateMachine( 1014): processMsg: DisconnectedState
D/WifiStateMachine( 1014): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1014): processMsg: ConnectModeState
,D/WifiStateMachine( 1014): handleMessage: X
,I/wpa_supplicant( 1156): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1156): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  539): NL - Read 312 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
D/TCMD    (  539): Listening for incoming client connection request
D/TCMD    (  539): NL - Read 192 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
D/TCMD    (  539): Listening for incoming client connection request
D/TCMD    (  539): NL - Read 68 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
D/TCMD    (  539): Listening for incoming client connection request
D/TCMD    (  539): NL - Read 1000 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
D/TCMD    (  539): Listening for incoming client connection request
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1156): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  276): Event received = Associated with c0:ff:d4
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  539): NL - Read 80 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
D/TCMD    (  539): Listening for incoming client connection request
D/TCMD    (  539): NL - Read 80 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
D/TCMD    (  539): Listening for incoming client connection request
D/TCMD    (  539): NL - Read 68 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
,D/TCMD    (  539): Listening for incoming client connection request,
D/WifiStateMachine( 1014): handleMessage: E msg.what=147462
D/WifiStateMachine( 1014): processMsg: DisconnectedState
D/WifiStateMachine( 1014): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1014): processMsg: ConnectModeState
,D/WifiStateMachine( 1014): handleMessage: X,
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1156): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  276): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1156): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  276): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  276):  STA Connected !!
D/TCMD    (  539): NL - Read 1000 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
,D/TCMD    (  539): Listening for incoming client connection request
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
I/MDMCTBK (  276): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1217402032
I/MDMCTBK (  276): return from set_get_from_wpa_supplicant
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
,I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  276): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  276): , reply_len: 3, ret: 0
E/MDMCTBK (  276): MdmCutbackHndler, resp=OK
E/MDMCTBK (  276): 
,D/MDMCTBK (  276): wifi_set_tx_pwr: Exit
,D/Tethering( 1014): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/WifiStateMachine( 1014): handleMessage: E msg.what=147462
,D/Tethering( 1014): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1014): processMsg: DisconnectedState
,D/WifiStateMachine( 1014): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1014): processMsg: ConnectModeState
D/WifiStateMachine( 1014): handleMessage: X
D/WifiStateMachine( 1014): handleMessage: E msg.what=147462
D/WifiStateMachine( 1014): processMsg: DisconnectedState
,D/WifiStateMachine( 1014): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1014): processMsg: ConnectModeState
,D/WifiStateMachine( 1014): handleMessage: X
,D/WifiStateMachine( 1014): handleMessage: E msg.what=147459
D/WifiStateMachine( 1014): processMsg: DisconnectedState
,D/WifiStateMachine( 1014): processMsg: ConnectModeState
D/WifiStateMachine( 1014): Network connection established
,D/WifiStateMachine( 1014): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1014): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1014): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1014): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1014): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1014): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1014): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1014): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1014): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1014): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1014): handleMessage: X
D/WifiStateMachine( 1014): handleMessage: E msg.what=147462
D/WifiStateMachine( 1014): processMsg: ObtainingIpState
D/WifiStateMachine( 1014): ObtainingIpState{ when=-51ms what=147462 obj=android.net.wifi.StateChangeResult@43b065f8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1014): processMsg: L2ConnectedState
D/WifiStateMachine( 1014): processMsg: ConnectModeState
D/WifiStateMachine( 1014): handleMessage: X
D/WifiStateMachine( 1014): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1014): processMsg: ObtainingIpState
D/WifiStateMachine( 1014): ObtainingIpState{ when=-48ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@43adc3d8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1014): processMsg: L2ConnectedState
D/WifiStateMachine( 1014): processMsg: ConnectModeState
D/WifiStateMachine( 1014): processMsg: DriverStartedState
D/WifiStateMachine( 1014): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1014): processMsg: DefaultState
,D/WifiStateMachine( 1014): handleMessage: X
D/WifiStateMachine( 1014): handleMessage: E msg.what=196612
D/WifiStateMachine( 1014): processMsg: ObtainingIpState
D/WifiStateMachine( 1014): ObtainingIpState{ when=-5ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1014): processMsg: L2ConnectedState
,D/WifiStateMachine( 1014): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1014): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1014): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42e60248 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1014): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42e60248 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1014): handleMessage: X
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 c
,D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 2 c
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 3
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 3 3
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 0
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 4 0
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 6
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 5 6
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 1
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 6 1
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  539): NL - Read 56 bytes from update socket.
D/TCMD    (  539): NL - message type is RTM_NEWLINK
D/TCMD    (  539): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 10
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 5 10
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiP2pService( 1014): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1014): handleMessage: E msg.what=147461
D/WifiStateMachine( 1014): processMsg: ObtainingIpState
D/WifiStateMachine( 1014): ObtainingIpState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1014): processMsg: L2ConnectedState
D/WifiStateMachine( 1014): processMsg: ConnectModeState
D/WifiP2pService( 1014): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1014): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1014): processMsg: DriverStartedState
D/WifiP2pService( 1014): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@44221310 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1014): processMsg: SupplicantStartedState
D/WifiP2pService( 1014): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@44221310 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1014): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@44221310 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1014): handleMessage: X
,D/TCMD    (  539): NL - Read 60 bytes from update socket.
D/TCMD    (  539): NL - ignore NL message, type = 20
,D/TCMD    (  539): Listening for incoming client connection request
,D/WifiStateMachine( 1014): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1014): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1014): processMsg: ObtainingIpState
,D/WifiStateMachine( 1014): ObtainingIpState{ when=-2ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1014): processMsg: L2ConnectedState
,D/WifiStateMachine( 1014): processMsg: ConnectModeState
D/WifiStateMachine( 1014): processMsg: DriverStartedState
,D/WifiStateMachine( 1014): processMsg: SupplicantStartedState
D/WifiStateMachine( 1014): processMsg: DefaultState
,D/WifiStateMachine( 1014): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1014): handleMessage: X
,D/WifiStateMachine( 1014): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1014): processMsg: ObtainingIpState
,D/WifiStateMachine( 1014): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1014): processMsg: L2ConnectedState
,D/WifiStateMachine( 1014): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1014): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1014): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1014): DHCP successful
D/WifiStateMachine( 1014): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1014): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1014): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1014): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1014): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1014): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1014): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1014): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1014): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1014): VerifyingLinkState enter
D/WifiStateMachine( 1014): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1014): handleMessage: X
D/WifiStateMachine( 1014): handleMessage: E msg.what=151572
D/WifiStateMachine( 1014): processMsg: VerifyingLinkState
D/WifiStateMachine( 1014): VerifyingLinkState what=151572 NOT_HANDLED
D/WifiStateMachine( 1014): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1014): handleMessage: X
,D/WifiStateMachine( 1014): handleMessage: E msg.what=135190
D/WifiStateMachine( 1014): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1014): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1014): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine( 1014): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1014): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1014): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1014): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1014): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1014): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine( 1014): CaptivePortalCheckState enter
,D/WifiStateMachine( 1014): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1014): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1014): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1014): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/ConnectivityService( 1014): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine( 1014): handleMessage: X
D/WifiStateMachine( 1014): handleMessage: E msg.what=131092
D/WifiStateMachine( 1014): processMsg: CaptivePortalCheckState
,D/WifiStateMachine( 1014): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiStateMachine( 1014): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1014): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService( 1014): WiFi NOT Tethered!
,E/ConnectivityService( 1014): Unexpected mtu value: android.net.wifi.WifiStateTracker@4274a8c0
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1014): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1198): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1198): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1198): onReceive() - done, currentInetCondition=0
D/WifiStateMachine( 1014): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1014): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1014): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1014): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1014): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1014): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1014): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1014): handleMessage: X
D/WifiStateMachine( 1014): handleMessage: E msg.what=131092
D/WifiStateMachine( 1014): processMsg: ConnectedState
D/WifiStateMachine( 1014): processMsg: L2ConnectedState
D/WifiStateMachine( 1014): processMsg: ConnectModeState
D/WifiStateMachine( 1014): processMsg: DriverStartedState
D/WifiStateMachine( 1014): processMsg: SupplicantStartedState
D/WifiStateMachine( 1014): processMsg: DefaultState
D/WifiStateMachine( 1014): handleMessage: X
D/Checkin ( 1014): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService( 1014): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1014): WiFi NOT Tethered!
E/ConnectivityService( 1014): Unexpected mtu value: android.net.wifi.WifiStateTracker@4274a8c0
,D/ConnectivityService( 1014): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1014): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1198): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1198): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1198): onReceive() - done, currentInetCondition=0
,D/Tethering( 1014): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/CaptivePortalTracker( 1014): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1014): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
W/XTWiFiOS( 1293): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1081): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/PollingManager( 1568): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1259): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1293): No entry in secure settings for enhanced location services: false
,E/ActivityThread( 1568): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1568): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1568): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
I/openssl ( 3895): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3895): Crypto mode 0 already enabled
,D/Finsky  ( 3465): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1539625, pollInterval: 10000
,E/ActivityThread( 1568): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1568): Registering with Alarm Manager to restart CCE
D/TelephonyProvider( 1259): Column apn id key is 'apn_id'
,D/OtaApp  ( 1568): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1568): [debug] > CusSM.onRadioDown
,I/ActivityManager( 1014): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4151 uid=10030 gids={50030, 3003, 1028, 1015}
,D/dalvikvm( 1014): GC_EXPLICIT freed 23945K, 65% free 18112K/50996K, paused 6ms+10ms, total 152ms
,V/MmsConfig( 4151): mnc/mcc: 
V/MmsConfig( 4151): tag: bool value: enabledMMS - true
V/MmsConfig( 4151): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4151): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4151): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4151): tag: int value: defaultSMSMessagesPerThread - 500
,V/MmsConfig( 4151): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4151): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4151): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4151): tag: int value: recipientLimit - 20
V/MmsConfig( 4151): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4151): tag: int value: smsToMmsTextThreshold - 6
,V/MmsConfig( 4151): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4151): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4151): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4151): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4151): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4151): tag: bool value: enableGroupMms - false
D/Tethering( 1014): MasterInitialState.processMessage what=3
,E/MmsConfig( 4151): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,D/CaptivePortalTracker( 1014): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1259): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1259): Column apn id key is 'apn_id'
,I/ActivityManager( 1014): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4170 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1014): Killing 3755:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1267): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4170): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4170): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4170): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4170): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1014): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4184 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1014): Killing 3816:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1267): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1418): Checkin interval check for package: unspecified last checkin: 1452155815988 min interval config: 0 actual interval: 295641
,I/CheckinService( 1418): Checking schedule, now: 1452156111638 next: 1452155845945
,I/CheckinService( 1418): active receiver: enabled
,I/CheckinService( 1418): Preparing to send checkin request
,I/EventLogService( 1418): Accumulating logs since 1452155812538
,I/CheckinRequestBuilder( 1418): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1418): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1014): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4198 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1014): Killing 3830:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1267): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  278): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 23ms
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WebViewChromiumFactoryProvider( 4198): Binding Chromium to main looper Looper (main, tid 1) {4266dac0}
,I/LibraryLoader( 4198): Expected native library version number "",actual native library version number ""
I/chromium( 4198): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4198): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4198): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4198): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4198): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4198): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4198): Local Branch: 
I/Adreno-EGL( 4198): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4198): Local Patches: NONE
I/Adreno-EGL( 4198): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
I/ActivityManager( 1014): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4221 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4221): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4221): VFY: replacing opcode 0x60 at 0x000b
,W/chromium( 4198): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 4221): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4221): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4221): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4221): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4221): install
,I/MultiDex( 4221): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4221): loading existing secondary dex files
,I/MultiDex( 4221): load found 3 secondary dex files
,I/MultiDex( 4221): install done
,W/GAV2    ( 4198): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4198): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/dalvikvm( 4221): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4221): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4221): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4221): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,D/ConnectivityService( 1014): NetTransition Wakelock for ConnectedState released by timeout
W/dalvikvm( 4221): VFY: unable to resolve instance field 36
D/dalvikvm( 4221): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4221): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4221): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4221): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4221): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 4221): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 4221): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x426689c0
D/dalvikvm( 4221): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x426689c0
D/dalvikvm( 4221): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x426689c0, skipping init
D/dalvikvm( 4221): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x426689c0
D/dalvikvm( 4221): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x426689c0
V/JNIHelp ( 4221): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4221): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x426689c0
,D/dalvikvm( 4221): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x426689c0
D/dalvikvm( 4221): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x426689c0
,D/dalvikvm( 4221): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x426689c0
,I/NSApplication( 4198): Starting up...
,I/ProviderInstaller( 4221): Installed default security provider GmsCore_OpenSSL
,I/ImageResourceManager( 3875): ImageResourceManager: uninitalized
,I/iu.Environment( 3875): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1014): Killing 3847:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1267): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/openssl ( 3895): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3895): Crypto mode 0 already enabled
I/dalvikvm( 4221): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4221): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
D/dalvikvm( 4221): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4221): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
D/MobileConnectivityChangeReceiver( 4170): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4170): onReceive CONNECTIVITY_CHANGE networkType=1
W/dalvikvm( 4221): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 4221): VFY: replacing opcode 0x6e at 0x000d
,I/iu.Environment( 3875): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/dalvikvm( 4221): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4221): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4221): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4221): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 4221): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4221): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4221): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4221): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 4221): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4221): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4221): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/DEBUG   ( 1568): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1568): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1568): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1568): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1568): onServiceConnected()
,D/GetNotificationsWS( 1568): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1568): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1568): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1568): unbindWebServices(): un-registering our AIDL callback...
,D/WVCdm   (  280): Instantiating CDM.
,I/WVCdm   (  280): Level3 Library Nov 20 2013 18:09:31
,D/WearableService( 1232): callingUid 10022, callindPid: 1232
,E/MDM     ( 1232): [129] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/DrmWidevineDash(  280): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  280): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  280): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb529e000
,E/DrmWidevineDash(  280): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb529e000
D/DrmWidevineDash(  280): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  280): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  280): calling OEMCrypto_IsKeyboxValid...
,D/LocationInitializer( 1418): Restart initialization of location
,D/AuthorizationBluetoothService( 1366): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1366): Proximity feature is not enabled.
,D/DrmWidevineDash(  280): OEMCrypto_IsKeyboxValid returns 0
D/WVCdm   (  280): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  280): CdmEngine::OpenSession
,D/DrmWidevineDash(  280): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  280): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  280): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetRandom...
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DrmWidevineDash(  280): OEMCrypto_GetRandom returns 0
I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  280): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetDeviceID...
,W/GCoreFlp( 1232): No location to return for getLastLocation()
D/DrmWidevineDash(  280): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateNonce. SID = 1
,W/FusedLocationProvider( 1232): location=null
D/DrmWidevineDash(  280): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  280): PrepareKeyRequest: nonce=528966496
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4221): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4221): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4286b1a8
D/dalvikvm( 4221): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4286b1a8
,D/dalvikvm( 4221): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4286b1a8, skipping init
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  280): CdmEngine::CloseSession
,D/DrmWidevineDash(  280): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4221): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4274): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4221): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4221): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 72ms
,I/Adreno-EGL( 4221): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4221): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4221): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4221): Local Branch: 
I/Adreno-EGL( 4221): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4221): Local Patches: NONE
I/Adreno-EGL( 4221): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4221): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4221): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4221): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4221): Local Branch: 
I/Adreno-EGL( 4221): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4221): Local Patches: NONE
I/Adreno-EGL( 4221): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/dalvikvm( 4005): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4005): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4005): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 4005): Shutting down VM
,W/dalvikvm( 4005): threadid=1: thread exiting with uncaught exception (group=0x41d98d40)
E/AndroidRuntime( 4005): FATAL EXCEPTION: main
E/AndroidRuntime( 4005): Process: com.test.thalitest, PID: 4005
E/AndroidRuntime( 4005): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4005): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4005): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4005): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4005): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4005): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4005): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 4005): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4005): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4005): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4005): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4005): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4005): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4005): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4005): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4005): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4005): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4005): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4005): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 1014):   Force finishing activity com.test.thalitest/.MainActivity
,I/ActivityManager( 1014): Killing 3792:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1267): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/Process ( 4005): Sending signal. PID: 4005 SIG: 9
,W/ContextImpl( 1267): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WindowState( 1014): WIN DEATH: Window{44b8f068 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1014): Client connection lost with reason: 4
,W/ContextImpl( 1267): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager( 1014): Process com.test.thalitest (pid 4005) has died.
,I/OtaApp  ( 1568): [info] > Updatetime from metadata: 10
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1568): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1568): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1568): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1568): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/InputMethodManagerService( 1014): Got RemoteException sending setActive(false) notification to pid 4005 uid 10519
W/Binder  ( 1208): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1208): java.lang.NullPointerException
W/Binder  ( 1208): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1208): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1208): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1208): 	at dalvik.system.NativeStart.run(Native Method)
I/WVCdm   (  280): CdmEngine::OpenSession
D/DrmWidevineDash(  280): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  280): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  280): OEMCrypto_OpenSession returns 0
D/DrmWidevineDash(  280): calling OEMCrypto_GetRandom...
D/DrmWidevineDash(  280): OEMCrypto_GetRandom returns 0
I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  280): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  280): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  280): PrepareKeyRequest: nonce=1747633236
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  280): CdmEngine::CloseSession
,D/DrmWidevineDash(  280): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_CloseSession returns 0
,W/Settings( 4221): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4221): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4221): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4221): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4221): Local Branch: 
I/Adreno-EGL( 4221): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4221): Local Patches: NONE
I/Adreno-EGL( 4221): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4221): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4221): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4221): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4221): Local Branch: 
I/Adreno-EGL( 4221): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4221): Local Patches: NONE
I/Adreno-EGL( 4221): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1418): Classify the device as Phone.
,D/Tethering( 1014): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/CaptivePortalTracker( 1014): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1293): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/PollingManager( 1568): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TelephonyProvider( 1259): Column apn id key is 'apn_id'
,D/PollingManager( 1568): now: 338290 ,futureTime: 48596557
,D/PollingManager( 1568): Polling alarm set to expire at: 48596557 Current Time: 338290
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/Tethering( 1014): MasterInitialState.processMessage what=3
,E/ActivityThread( 1568): Failed to find provider info for com.motorola.blur.setupprovider
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
D/PollingManager( 1568): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/OtaApp  ( 1568): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/CaptivePortalTracker( 1014): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/OtaApp  ( 1568): [debug] > CusSM.onRadioUp
I/openssl ( 3895): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3895): Crypto mode 0 already enabled
D/TelephonyProvider( 1259): Column apn id key is 'apn_id'
W/XTWiFiOS( 1293): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
D/PollingManager( 1568): now: 338311 ,futureTime: 48596557
D/PollingManager( 1568): Polling alarm set to expire at: 48596557 Current Time: 338313
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/OtaApp  ( 1568): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1568): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,E/ActivityThread( 1568): Failed to find provider info for com.motorola.blur.setupprovider
D/TelephonyProvider( 1259): Column apn id key is 'apn_id'
I/OtaApp  ( 1568): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1568): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1568): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1568): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1568): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MobileConnectivityChangeReceiver( 4170): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4170): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1568): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1568): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/TelephonyProvider( 1259): Column apn id key is 'apn_id'
,D/OtaApp  ( 1568): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1568): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1568): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1568): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1568): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1568): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/dalvikvm( 3875): GC_FOR_ALLOC freed 596K, 5% free 16434K/17224K, paused 21ms, total 22ms
,I/dalvikvm-heap( 3875): Grow heap (frag case) to 19.817MB for 1821008-byte allocation
,I/iu.Environment( 3875): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1418): Checkin interval check for package: unspecified last checkin: 1452155815988 min interval config: 0 actual interval: 298117
,D/dalvikvm( 3875): GC_FOR_ALLOC freed 30K, 5% free 18186K/19004K, paused 12ms, total 13ms
,I/CheckinTask( 1418): Sending checkin request (11811 bytes)
,D/DEBUG   ( 1568): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1568): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1568): bindWebServices(): registering our AIDL callback...
I/SundryService( 1568): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1568): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1568): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1568): onServiceConnected()
D/GetNotificationsWS( 1568): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1568): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 3895): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3895): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4170): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4170): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3875): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1418): Checkin interval check for package: unspecified last checkin: 1452155815988 min interval config: 0 actual interval: 298170
,D/DEBUG   ( 1568): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1568): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1568): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1568): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1568): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1568): onServiceConnected()
,D/GetNotificationsWS( 1568): onServiceConnected(): Registered for remote service callbacks...
D/WaitableIntentService( 1568): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1568): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1568): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1014): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1568
W/ContextImpl( 1267): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1568): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1267): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
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
,D/OtaApp  ( 1568): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1568): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1014): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1568
,W/ContextImpl( 1267): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1568): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/ContextImpl( 1267): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
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
I/ActivityManager( 1014): Activity reported stop, but no longer stopping: ActivityRecord{42f161d0 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/CheckinRequestBuilder( 1418): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1418): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1014): GC_EXPLICIT freed 828K, 65% free 17997K/50996K, paused 4ms+8ms, total 97ms
,D/WifiStateMachine( 1014): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1014): handleMessage: E msg.what=131215
D/WifiStateMachine( 1014): processMsg: ConnectedState
D/WifiStateMachine( 1014): processMsg: L2ConnectedState
D/WifiStateMachine( 1014): processMsg: ConnectModeState
,D/WifiStateMachine( 1014): processMsg: DriverStartedState
D/WifiStateMachine( 1014): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1014): processMsg: DefaultState
,D/WifiStateMachine( 1014): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1014): handleMessage: X
D/ConnectivityService( 1014): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1014):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat( 1014): requiresClat: netType=1, hasIPv4Address=true
D/ConnectivityService( 1014): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
D/Nat464Xlat( 1014): requiresClat: netType=1, hasIPv4Address=true
,I/CheckinRequestBuilder( 1418): Classify the device as Phone.
,I/CheckinTask( 1418): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1418): Checking schedule, now: 1452156115120 next: 1452749185116
,I/CheckinService( 1418): active receiver: disabled
,I/CheckinService( 1418): Checking schedule, now: 1452156115135 next: 1452749185116
,I/CheckinService( 1418): active receiver: disabled
,D/CheckinService( 1418): Recording last checkin time for package unspecified as 1452156115140
,D/GCM     ( 1366): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService( 1014): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/ModemStatsDSDetect( 1198): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1081): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1198): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1198): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1198): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/GAV2    ( 4198): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 1014): sending alarm Alarm{42a45dd0 type 3 android}
,D/Finsky  ( 3465): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1529591, pollInterval: 10000
,I/InputReader( 1014): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager( 1014): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4348 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1014): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :,
I/PackageManager( 1014):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1014):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1014):   Scheme: "sms"
,I/PackageManager( 1014): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1014):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1014):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1014):   Scheme: "smsto"
,I/PackageManager( 1014): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1014):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1014):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1014):   Scheme: "mms"
,I/PackageManager( 1014): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1014):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1014):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1014):   Scheme: "mmsto"
,I/Launcher( 1305): Deferring update until onResume
,I/PackageManager( 1014): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1014):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1014):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1014):   Scheme: "sms"
I/Launcher( 1305): Deferring update until onResume
,I/PackageManager( 1014): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager( 1014):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1014):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1014):   Scheme: "smsto"
,I/PackageManager( 1014): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1014):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1014):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1014):   Scheme: "mms"
,I/PackageManager( 1014): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1014):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1014):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1014):   Scheme: "mmsto"
,I/GCoreNlp( 1232): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4348): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4348): MmsConfig.loadMmsSettings
I/Babel   ( 4348): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4348): MmsConfig.loadFromDatabase
,E/Babel   ( 4348): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4348): MmsConfig.loadFromResources
,E/Babel   ( 4348): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4348): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4348): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1014): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4387 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,D/dalvikvm( 1232): GC_CONCURRENT freed 1702K, 33% free 11564K/17224K, paused 7ms+7ms, total 44ms
,I/ActivityManager( 1014): Killing 3465:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1267): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1014): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4406 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1014): Killing 3895:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1267): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2315): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1014): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4423 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1014): Killing 4151:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1267): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 4423): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4423): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4423): VFY: replacing opcode 0x6e at 0x000e
,I/ContactLocale( 4387): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/Finsky  ( 4423): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 4423): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4423): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4423): VFY: replacing opcode 0x6e at 0x01d3
,I/InternalIcingCorporaPro( 2315): UpdateCorporaTask done [took 206 ms] updated apps [took 206 ms] 
,I/dalvikvm( 4423): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4423): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4423): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4423): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/dalvikvm( 4423): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4423): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4423): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4423): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4423): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4423): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4423): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4423): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 4423): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4423): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4423): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4423): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4423): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4423): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1014): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4458 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4423): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4423): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4423): VFY: replacing opcode 0x6e at 0x0019
,D/dalvikvm( 1366): GC_EXPLICIT freed 1152K, 41% free 10309K/17224K, paused 2ms+4ms, total 30ms
,D/Finsky  ( 4423): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4423): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 4423): Skipping gmscore version check
,I/dalvikvm( 4423): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4423): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4423): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1014): Killing 4170:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,D/dalvikvm( 4458): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x4266f310, skipping init
I/openssl ( 4458): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4458): Crypto mode 0 already enabled
,W/ContextImpl( 1267): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/PackageBroadcastService( 1418): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 1418): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1418): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 4423): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4423): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1014): Killing 4184:com.android.chrome/u0a56 (adj 15): empty #9
W/ContextImpl( 1267): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1418): GC_CONCURRENT freed 2138K, 31% free 12045K/17224K, paused 4ms+5ms, total 40ms
,I/Icing   ( 1418): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1418): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1208): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452156123
,D/CaptivePortalTracker( 1014): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1014): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1014): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1014): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1014): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1014): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1014): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1014): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/AlarmManager( 1014): sending alarm Alarm{427fa570 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{4442a4a8 type 3 android}
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
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
,D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 6
,V/AlarmManager( 1014): sending alarm Alarm{44c2a130 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{42a36ed0 type 1 com.android.deskclock}
,I/LaunchCheckinHandler( 1014): cleanup(): cleared. Last call was 178649 ms ago
,I/ActivityManager( 1014): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4501 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1014): Killing 4198:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1267): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager( 1014): sending alarm Alarm{4440ee90 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{42ea43d0 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{43cf5998 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{42a36000 type 2 android}
,V/AlarmManager( 1014): sending alarm Alarm{444dfd20 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{42a351b8 type 2 android}
,D/ConnectivityService( 1014): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1014): Done.
,D/ConnectivityService( 1014): Setting timer for 720seconds
,V/AlarmManager( 1014): sending alarm Alarm{443fcf20 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{445d28b0 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{44512d48 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{43c688d0 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{447f0d30 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{42f22f88 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{43d50620 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1014): sending alarm Alarm{427fdf58 type 2 com.google.android.gms}
,I/GoogleURLConnFactory( 1232): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1232): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,D/ConnectivityService( 1014): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/ModemStatsDSDetect( 1198): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1198): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1198): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/PhenotypeConfigurator( 1232): Server returned 404
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
,V/AlarmManager( 1014): sending alarm Alarm{43091be8 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{42f0cfa0 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{441491f0 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{43b33e30 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{43091cc0 type 0 com.google.android.gms}
,V/AlarmManager( 1014): sending alarm Alarm{43bd7f58 type 1 com.android.deskclock}
,D/dalvikvm( 1014): GC_EXPLICIT freed 1736K, 65% free 18106K/50996K, paused 4ms+10ms, total 99ms
,I/EventLogService( 1418): Aggregate from 1452156111660 (log), 1452155309757 (data)
,V/AlarmManager( 1014): sending alarm Alarm{44c474e8 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{44c39c38 type 2 android}
,D/ConnectivityService( 1014): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1014): Done.
,D/ConnectivityService( 1014): Setting timer for 720seconds
,V/AlarmManager( 1014): sending alarm Alarm{42edb5b8 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{42ed2c00 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{42ec1458 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{42ebca88 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{42eb7850 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{42eb1070 type 3 android}
,I/ProcessStatsService( 1014): Prepared write state in 26ms
,I/ProcessStatsService( 1014): Prepared write state in 25ms
,V/AlarmManager( 1014): sending alarm Alarm{42e947d0 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{42e7a638 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{42e79ba8 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{42e6ada0 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms),V/AlarmManager( 1014): sending alarm Alarm{44c2c0b0 type 3 android}
V/AlarmManager( 1014): sending alarm Alarm{44c2bef0 type 3 com.google.android.gms}
V/AlarmManager( 1014): sending alarm Alarm{44c12680 type 2 com.motorola.ccc.cce}
V/AlarmManager( 1014): sending alarm Alarm{44ba9740 type 2 com.google.android.gms}
D/CCE     ( 1568): Registering with Alarm Manager to restart CCE
V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 4585): 
D/AndroidRuntime( 4585): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4585): CheckJNI is OFF
D/dalvikvm( 4585): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4585): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4585): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4585): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4585): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4585): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
W/dalvikvm( 1366): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 1366): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 1366): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
D/dalvikvm( 1366): VFY: replacing opcode 0x1f at 0x0011
I/dalvikvm( 1366): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1366): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/dalvikvm( 1366): VFY: replacing opcode 0x6e at 0x003d
E/memtrack( 4585): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4585): failed to load memtrack module: -2
D/AndroidRuntime( 4585): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1014): Force stopping com.test.thalitest appid=10519 user=-1: uninstall pkg
W/PackageSettings( 1014): Skipping PackageSetting{4292b6a8 com.example.hello/10509} due to missing metadata
I/ActivityManager( 1014): Force stopping com.test.thalitest appid=10519 user=0: pkg removed
D/dalvikvm( 2285): GC_EXPLICIT freed 5279K, 44% free 9649K/17224K, paused 12ms+5ms, total 54ms
I/InputReader( 1014): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1014): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1014):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1014):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1014):   Scheme: "sms"
I/LatinIME:LogUtils( 1208): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1208): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/dalvikvm( 1014): GC_EXPLICIT freed 1125K, 65% free 17972K/50996K, paused 3ms+14ms, total 106ms
W/GeofencerStateMachine( 1232): Ignoring removeGeofence because network location is disabled.
D/dalvikvm( 1305): GC_EXPLICIT freed 3237K, 33% free 11595K/17224K, paused 2ms+5ms, total 117ms
D/dalvikvm( 2315): GC_EXPLICIT freed 2757K, 43% free 9818K/17224K, paused 2ms+3ms, total 81ms
I/Launcher( 1305): Deferring update until onResume
I/PackageManager( 1014): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1014):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1014):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1014):   Scheme: "smsto"
I/PackageManager( 1014): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1014):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1014):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1014):   Scheme: "mms"
D/VoicemailCleanupService( 4387): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1014): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1014):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1014):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1014):   Scheme: "mmsto"
D/dalvikvm( 1418): GC_EXPLICIT freed 830K, 31% free 11929K/17224K, paused 63ms+12ms, total 170ms
W/SQLiteConnectionPool( 1418): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/PackageManager( 1014): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1014):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1014):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1014):   Scheme: "sms"
I/Launcher( 1305): Deferring update until onResume
I/PackageManager( 1014): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1014):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1014):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1014):   Scheme: "smsto"
I/PackageManager( 1014): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1014):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1014):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1014):   Scheme: "mms"
I/InternalIcingCorporaPro( 2315): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1014): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1014):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1014):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1014):   Scheme: "mmsto"
I/ActivityManager( 1014): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4619 uid=10059 gids={50059, 3003, 1028, 1015}
I/LatinIME:LogUtils( 1208): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452157916
D/BackupManagerService( 1014): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1014): removePackageParticipantsLocked: uid=10519 #1
D/ConnectivityService( 1014): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/ModemStatsDSDetect( 1198): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1198): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1198): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/LatinIME:LogUtils( 1208): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452157916
D/dalvikvm( 1014): GC_EXPLICIT freed 601K, 65% free 18086K/50996K, paused 13ms+17ms, total 207ms
I/InternalIcingCorporaPro( 2315): UpdateCorporaTask done [took 158 ms] updated apps [took 158 ms] 
D/AndroidRuntime( 4585): Shutting down VM
D/dalvikvm( 4585): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
W/ActiveOrDefaultContextProvider( 4619): Missing scope.enter somewhere. Returning default context
I/ActivityManager( 1014): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4645 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/ActivityManager( 1014): Killing 4221:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
W/ContextImpl( 1267): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/GAV2    ( 4619): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 4645): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 4423): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4423): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4423): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1418): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1418): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1418): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1418): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1418): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1418): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1418): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1366): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1366): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager( 1014): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4676 uid=10058 gids={50058}
I/Icing   ( 1418): doRemovePackageData com.test.thalitest
E/SQLiteLog( 1418): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 1418): threadid=53: thread exiting with uncaught exception (group=0x41d98d40)
W/FileUtils( 4645): Failed to chmod(/data/data/com.android.keychain/databases/grants.db): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
E/SQLiteDatabase( 1418): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1418): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1418): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1418): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1418): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1418): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1418): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1418): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1418): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1418): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1418): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1418): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1418): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1418): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1418): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1418): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1418): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1418): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1418): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1418): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1418): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 1418): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 1418): Process: com.google.android.gms, PID: 1418
E/AndroidRuntime( 1418): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1418): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1418): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1418): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1418): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1418): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1418): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1418): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 1418): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3166)
E/AndroidRuntime( 1418): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 1418): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 1418): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1418): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1418): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1418): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/FileUtils( 1418): Failed to chmod(/data/data/com.google.android.gms/files): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
E/SQLiteLog( 4645): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 4645): threadid=10: thread exiting with uncaught exception (group=0x41d98d40)
E/SQLiteOpenHelper( 1418): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1418): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1418): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1418): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1418): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1418): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1418): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 1418): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 1418): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1418): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 1418): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1418): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1418): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1418): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1418): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1418): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1418): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1418): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1418): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1418): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 1418): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1418): Opened metrics.db in read-only mode
E/AndroidRuntime( 4645): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4645): Process: com.android.keychain, PID: 4645
E/AndroidRuntime( 4645): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4645): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4645): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 4645): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4645): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4645): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 4645): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 4645): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:288)
E/AndroidRuntime( 4645): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4645): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4645): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4645): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4645): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 1418): Sending signal. PID: 1418 SIG: 9
D/gH_CompatibleDatabase( 1418): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
E/DropBoxManagerService( 1014): Can't write: system_app_crash
E/DropBoxManagerService( 1014): java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1014): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1014): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1014): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1014): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1014): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1014): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1014): 	... 5 more
I/Process ( 4645): Sending signal. PID: 4645 SIG: 9
E/DropBoxManagerService( 1014): Can't write: system_app_crash
E/DropBoxManagerService( 1014): java.io.FileNotFoundException: /data/system/dropbox/drop103.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1014): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1014): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1014): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1014): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1014): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1014): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1014): 	... 5 more
I/ActivityManager( 1014): Process com.android.keychain (pid 4645) has died.
W/ActivityManager( 1014): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/ActivityManager( 1014): Process com.google.android.gms (pid 1418) has died.
D/WifiService( 1014): Client connection lost with reason: 4
W/ActivityManager( 1014): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager( 1014): Service ServiceRecord{4446f328 u0 com.google.android.gms/.usagereporting.service.UsageReportingService} in process ProcessRecord{42743c08 1418:com.google.android.gms/u0a22} not same as in map: null
W/ActivityManager( 1014): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager( 1014): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager( 1014): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
W/ActivityManager( 1014): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager( 1014): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1000ms
W/ActivityManager( 1014): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 11000ms
D/Documents( 4676): Loading roots for com.android.providers.downloads.documents
E/SQLiteDatabase( 4676): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4676): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4676): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4676): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4676): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4676): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4676): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4676): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4676): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4676): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4676): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4676): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4676): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4676): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4676): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4676): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4676): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4676): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 4676): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/SQLiteDatabase( 4676): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4676): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/SQLiteDatabase( 4676): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/SQLiteDatabase( 4676): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/SQLiteDatabase( 4676): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4676): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4676): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4676): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4676): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4676): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4676): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4676): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 4676): Shutting down VM
W/dalvikvm( 4676): threadid=1: thread exiting with uncaught exception (group=0x41d98d40)
E/AndroidRuntime( 4676): FATAL EXCEPTION: main
E/AndroidRuntime( 4676): Process: com.android.documentsui, PID: 4676
E/AndroidRuntime( 4676): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4676): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 4676): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 4676): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 4676): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4676): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4676): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4676): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4676): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4676): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4676): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4676): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4676): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4676): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4676): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4676): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4676): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4676): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4676): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4676): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4676): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4676): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4676): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4676): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4676): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4676): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4676): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4676): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4676): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 4676): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/AndroidRuntime( 4676): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4676): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 4676): 	... 10 more
D/Documents( 4676): Loading roots for com.android.externalstorage.documents
I/ActivityManager( 1014): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=4698 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
D/dalvikvm(  278): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 4ms+3ms, total 21ms

```
