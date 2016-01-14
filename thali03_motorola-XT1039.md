#### Test 55613145c131883_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
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
E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4423): 
D/AndroidRuntime( 4423): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4423): CheckJNI is OFF
D/dalvikvm( 4423): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4423): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4423): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4423): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4423): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4423): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4423): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4423): failed to load memtrack module: -2
D/AndroidRuntime( 4423): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1018): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4423
W/WindowManager( 1018): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4440 uid=10110 gids={50110, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4423): Shutting down VM
D/dalvikvm( 4423): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+1ms, total 3ms
W/ContextImpl( 1280): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1280): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4440): Binding Chromium to main looper Looper (main, tid 1) {427847d8}
I/LibraryLoader( 4440): Expected native library version number "",actual native library version number ""
I/chromium( 4440): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4440): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1018): Message: 20
D/BluetoothManagerService( 1018): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4457c6c0:true
I/Adreno-EGL( 4440): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4440): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4440): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4440): Local Branch: 
I/Adreno-EGL( 4440): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4440): Local Patches: NONE
I/Adreno-EGL( 4440): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4440): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4440): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4440): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4440): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4440): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 4440): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4440): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4440): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4440): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 4440): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 4440): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4440): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4440): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4440): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4440): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4440): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4440): Enabling debug mode 0
,W/AwContents( 4440): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1212): onFinishInput()
,W/IInputConnectionWrapper( 4440): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1018): Displayed com.test.thalitest/.MainActivity,cp,ca,436
I/ActivityManager( 1018): Displayed com.test.thalitest/.MainActivity: +406ms (total +437ms)
,D/JsMessageQueue( 4440): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4440): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42788aa8
,D/dalvikvm( 4440): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42788aa8
,D/jxcore_app_log( 4440): JniHelper::setJavaVM(0x41ea6f78), pthread_self() = 1614050096
,D/JX-Cordova( 4440): jxcore cordova android initializing
,D/dalvikvm( 4440): GC_CONCURRENT freed 2722K, 17% free 14413K/17224K, paused 3ms+3ms, total 45ms
,D/dalvikvm( 4440): GC_FOR_ALLOC freed 155K, 17% free 14402K/17224K, paused 26ms, total 26ms
,D/dalvikvm( 4440): GC_FOR_ALLOC freed 125K, 17% free 14422K/17224K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4440): Grow heap (frag case) to 16.208MB for 95956-byte allocation
,D/dalvikvm( 4440): GC_FOR_ALLOC freed 182K, 17% free 14452K/17320K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4440): Grow heap (frag case) to 16.284MB for 143930-byte allocation
,D/dalvikvm( 4440): GC_FOR_ALLOC freed 252K, 17% free 14499K/17464K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4440): Grow heap (frag case) to 16.398MB for 215890-byte allocation
,D/dalvikvm( 4440): GC_FOR_ALLOC freed 366K, 18% free 14573K/17676K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4440): Grow heap (frag case) to 16.574MB for 323830-byte allocation
,D/dalvikvm( 4440): GC_FOR_ALLOC freed 563K, 19% free 14694K/17996K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4440): Grow heap (frag case) to 16.846MB for 485740-byte allocation
,D/dalvikvm( 4440): GC_FOR_ALLOC freed 860K, 20% free 14870K/18472K, paused 26ms, total 27ms
,D/dalvikvm( 4440): GC_FOR_ALLOC freed 1276K, 19% free 15126K/18472K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4440): Grow heap (frag case) to 17.846MB for 1092904-byte allocation
,D/dalvikvm( 4440): GC_CONCURRENT freed 1736K, 21% free 15506K/19540K, paused 3ms+5ms, total 47ms
,D/dalvikvm( 4440): GC_FOR_ALLOC freed 294K, 21% free 15457K/19540K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4440): Grow heap (frag case) to 18.691MB for 1639352-byte allocation
,D/dalvikvm( 4440): GC_CONCURRENT freed 1670K, 25% free 16022K/21144K, paused 3ms+4ms, total 32ms
,D/dalvikvm( 4440): GC_FOR_ALLOC freed 1327K, 24% free 16086K/21144K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4440): Grow heap (frag case) to 20.086MB for 2459024-byte allocation
,D/dalvikvm( 4440): GC_CONCURRENT freed 300K, 22% free 18397K/23548K, paused 4ms+4ms, total 49ms
,D/dalvikvm( 4440): GC_FOR_ALLOC freed 4307K, 28% free 17076K/23548K, paused 34ms, total 35ms
,I/dalvikvm-heap( 4440): Grow heap (frag case) to 22.226MB for 3688532-byte allocation
,D/dalvikvm( 4440): GC_CONCURRENT freed 269K, 25% free 20563K/27152K, paused 5ms+6ms, total 41ms
,D/dalvikvm( 4440): GC_FOR_ALLOC freed 3334K, 34% free 18031K/27152K, paused 28ms, total 28ms
,W/jxcore-log( 4440): Initializing JXcore engine
,W/jxcore-log( 4440): JXcore engine is ready
,D/dalvikvm( 4440): GC_CONCURRENT freed 375K, 24% free 20645K/27152K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 4440): WAIT_FOR_CONCURRENT_GC blocked 22ms
,W/jxcore-log( 4440): Starting JXcore engine
,W/jxcore-log( 4440): Platform android
W/jxcore-log( 4440): 
,W/jxcore-log( 4440): Process ARCH arm
W/jxcore-log( 4440): 
,I/jxcore-log( 4440): JXcore Cordova bridge is ready!
I/jxcore-log( 4440): 
,W/jxcore-log( 4440): JXcore engine is started
,I/chromium( 4440): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4440): Toggling radios to true
I/jxcore-log( 4440): 
,D/BluetoothAdapter( 4440): enable(): BT is already enabled..!
D/WifiService( 1018): New client listening to asynchronous messages
D/WifiService( 1018): setWifiEnabled: true pid=4440, uid=10110
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1018): handleMessage: E msg.what=131145
D/WifiStateMachine( 1018): processMsg: ConnectedState
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
I/jxcore-log( 4440): Radios toggled
I/jxcore-log( 4440): 
I/jxcore-log( 4440): My device name is: motorola-XT1039
I/jxcore-log( 4440): 
,I/wpa_supplicant( 1166): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  273): reply_len: 58 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:
D/MDMCTBK (  273): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:
D/MDMCTBK (  273):  STA Disconnected !!
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): get_property_value, Enter
I/MDMCTBK (  273): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,0,1,0, length=23
I/MDMCTBK (  273): get_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
D/TCMD    (  451): NL - Read 1000 bytes from update socket.
D/TCMD    (  451): NL - message type is RTM_NEWLINK
D/TCMD    (  451): Listening for incoming client connection request
D/TCMD    (  451): NL - Read 68 bytes from update socket.
D/TCMD    (  451): NL - message type is RTM_NEWLINK
D/TCMD    (  451): Listening for incoming client connection request
D/TCMD    (  451): NL - Read 68 bytes from update socket.
D/TCMD    (  451): NL - message type is RTM_NEWLINK
D/TCMD    (  451): Listening for incoming client connection request
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  273): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
I/MDMCTBK (  273): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
I/MDMCTBK (  273): send SAR ctrl over QMI
D/MDMCTBK (  273): reply_len: 58 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID
,D/Tethering( 1018): InitialState.processMessage what=4
,V/ConnectivityService( 1018): WiFi NOT Tethered!
D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiStateMachine( 1018): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1018): invokeExitMethods: ConnectedState
,D/WifiStateMachine( 1018): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1018): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1018): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  271): Clearing all IP addresses on wlan0
D/TCMD    (  451): NL - Read 60 bytes from update socket.
D/TCMD    (  451): NL - ignore NL message, type = 21
,D/TCMD    (  451): Listening for incoming client connection request
,D/WifiStateMachine( 1018): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1018): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1018): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1018): connected time updated 317365
,D/ConnectivityService( 1018): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1018): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService( 1018): Attempting to switch to mobile
D/ConnectivityService( 1018): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1018): Attempting to switch to ETHERNET
,I/SBar.NetworkController( 1094): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,I/SBar.NetworkController( 1094): refreshSignalCluster: mobile: Signal=zz_moto_stat_sys_signal_emergency_only_wide Roaming=(none) mSimIconId=zz_moto_stat_sys_no_sim_wide Accessibility="Emergency calls only.","","No SIM card."
,I/SBar.NetworkController( 1094): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
,D/WifiStateMachine( 1018): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine( 1018): DisconnectingState
E/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/ConnectivityService( 1018): resetConnections(wlan0, 3)
D/NetUtils( 1018): android_net_utils_resetConnections in env=0x615ccf48 clazz=0x64a00001 iface=wlan0 mask=0x3
D/Checkin ( 1018): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131146
D/WifiStateMachine( 1018): processMsg: DisconnectingState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/MDMCTBK (  273): reply_len: 58 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSI
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSI
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147460
D/WifiStateMachine( 1018): processMsg: DisconnectingState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): Network connection lost
D/WifiStateMachine( 1018): Stopping DHCP and clearing IP
D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1348): Read error: ssl=0x63756ad8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1348): SSL shutdown failed: ssl=0x63756ad8: I/O error during system call, Broken pipe
,D/WifiP2pService( 1018): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  271): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1018): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1018): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1018): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/Checkin ( 1018): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1018): invokeEnterMethods: DisconnectedState
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
D/WifiStateMachine( 1018): handleMessage: X
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1018): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1018): Attempting to switch to mobile
D/ConnectivityService( 1018): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1018): Attempting to switch to ETHERNET
I/ModemStatsDSDetect( 1224): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1224): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1224): onReceive() - done, currentInetCondition=0
D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1224): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1224): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1224): onReceive() - done, currentInetCondition=0
,D/TCMD    (  451): NL - Read 56 bytes from update socket.
D/TCMD    (  451): NL - message type is RTM_NEWLINK
,D/TCMD    (  451): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  273): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 38
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 1 38
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiStateMachine( 1018): handleMessage: E msg.what=147461
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiP2pService( 1018): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@439935a0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@439935a0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@439935a0 target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: null, inetCondition= 0
,D/CaptivePortalTracker( 1018): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1018): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
W/XTWiFiOS( 1297): No entry in secure settings for enhanced location services: false
W/XTWiFiOS( 1297): Active network info is not available
,D/PollingManager( 1615): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ActivityManager( 1018): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4515 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/TelephonyProvider( 1269): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1297): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: null, inetCondition= 0
,E/ActivityThread( 1615): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1615): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
W/XTWiFiOS( 1297): Active network info is not available
D/PollingManager( 1615): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,E/ActivityThread( 1615): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1615): Registering with Alarm Manager to restart CCE
,D/CaptivePortalTracker( 1018): NoActiveNetworkState{ when=-6ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1269): Column apn id key is 'apn_id'
,D/OtaApp  ( 1615): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1615): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1269): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1269): Column apn id key is 'apn_id'
,D/dalvikvm( 4515): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x4278cea0, skipping init
I/openssl ( 4515): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4515): Crypto mode 0 already enabled
,I/ActivityManager( 1018): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4542 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1018): Killing 3862:com.android.providers.calendar/u0a8 (adj 15): empty #9
,W/ContextImpl( 1280): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4542): mnc/mcc: 
,V/MmsConfig( 4542): tag: bool value: enabledMMS - true
V/MmsConfig( 4542): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4542): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4542): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4542): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4542): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4542): tag: int value: minMessageCountPerThread - 10
,V/MmsConfig( 4542): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4542): tag: int value: recipientLimit - 20
V/MmsConfig( 4542): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4542): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4542): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4542): tag: int value: maxMessageTextSize - -1
,V/MmsConfig( 4542): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4542): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4542): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4542): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4542): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1018): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4561 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1018): Killing 4244:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1280): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4561): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4561): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4561): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4561): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4574 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1018): Killing 4298:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1280): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4574): Binding Chromium to main looper Looper (main, tid 1) {42788560}
,I/LibraryLoader( 4574): Expected native library version number "",actual native library version number ""
I/chromium( 4574): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4574): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4574): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4574): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4574): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4574): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4574): Local Branch: 
I/Adreno-EGL( 4574): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4574): Local Patches: NONE
I/Adreno-EGL( 4574): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/dalvikvm( 1018): GC_EXPLICIT freed 23181K, 65% free 18322K/51136K, paused 4ms+12ms, total 148ms
,W/chromium( 4574): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4574): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  261): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  261): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4574): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 4574): Starting up...
,I/ActivityManager( 1018): Killing 4004:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1280): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.Environment( 1743): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1743): num queued entries: 0
,I/iu.UploadsManager( 1743): num updated entries: 0
,I/iu.SyncManager( 1743): NEXT; no task
,I/ActivityManager( 1018): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=4618 uid=10056 gids={50056, 3003, 1028, 1015}
,D/dalvikvm( 4618): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,W/dalvikvm( 4618): VFY: unable to resolve instance field 68
D/dalvikvm( 4618): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 4618): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4618): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 4618): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 4618): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/dalvikvm( 4618): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,W/dalvikvm( 4618): VFY: unable to resolve instance field 68
,D/dalvikvm( 4618): VFY: replacing opcode 0x54 at 0x0011
,I/ActivityManager( 1018): Killing 4337:com.google.android.apps.docs/u0a59 (adj 15): empty #9
D/dalvikvm( 4618): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4618): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4618): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4618): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4618): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4618): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
W/ContextImpl( 1280): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4561): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4561): onReceive CONNECTIVITY_CHANGE networkType=1
,D/DEBUG   ( 1615): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1615): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1615): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1615): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1615): onServiceConnected()
D/GetNotificationsWS( 1615): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1615): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1615): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1615): unbindWebServices(): un-registering our AIDL callback...
,V/AlarmManager( 1018): sending alarm Alarm{4465c170 type 2 com.google.android.gms}
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
,I/GAV2    ( 4574): Thread[GAThread,5,main]: No campaign data found.
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 0
,I/jxcore-log( 4440): Test app app.js loaded
I/jxcore-log( 4440): 
,I/Choreographer( 4440): Skipped 681 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4440): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 1166): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 5 c
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 3
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 6 3
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  273): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  451): NL - Read 56 bytes from update socket.
D/TCMD    (  451): NL - message type is RTM_NEWLINK
,D/TCMD    (  451): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  273): Event received = Trying to associate with,
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1166): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147461
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,I/wpa_supplicant( 1166): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1166): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  451): NL - Read 312 bytes from update socket.
D/TCMD    (  451): NL - message type is RTM_NEWLINK
D/TCMD    (  451): Listening for incoming client connection request
D/TCMD    (  451): NL - Read 88 bytes from update socket.
D/TCMD    (  451): NL - message type is RTM_NEWLINK
D/TCMD    (  451): Listening for incoming client connection request
D/TCMD    (  451): NL - Read 68 bytes from update socket.
D/TCMD    (  451): NL - message type is RTM_NEWLINK
D/TCMD    (  451): Listening for incoming client connection request
D/TCMD    (  451): NL - Read 1000 bytes from update socket.
D/TCMD    (  451): NL - message type is RTM_NEWLINK
,D/TCMD    (  451): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1166): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  273): Event received = Associated with c0:ff:d4
D/TCMD    (  451): NL - Read 80 bytes from update socket.
D/TCMD    (  451): NL - message type is RTM_NEWLINK
,D/TCMD    (  451): Listening for incoming client connection request
D/TCMD    (  451): NL - Read 80 bytes from update socket.
D/TCMD    (  451): NL - message type is RTM_NEWLINK
D/TCMD    (  451): Listening for incoming client connection request
D/TCMD    (  451): NL - Read 68 bytes from update socket.
D/TCMD    (  451): NL - message type is RTM_NEWLINK
,D/TCMD    (  451): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1166): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1166): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  273): Event received = WPA: Key negotiation com
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  273): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  273):  STA Connected !!
D/TCMD    (  451): NL - Read 1000 bytes from update socket.
D/TCMD    (  451): NL - message type is RTM_NEWLINK
,D/TCMD    (  451): Listening for incoming client connection request
E/MDMCTBK (  273): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  273): get_freq !!, resp=0
I/MDMCTBK (  273): get_freq !!, Strip data
I/MDMCTBK (  273): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): get_property_value, Enter
I/MDMCTBK (  273): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,0,1,0, length=23
I/MDMCTBK (  273): get_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  273): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  273): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  273): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): get_property_value, Enter
I/MDMCTBK (  273): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,0,1,0, length=23
I/MDMCTBK (  273): get_property_value, Exit
I/MDMCTBK (  273): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1197638832
I/MDMCTBK (  273): return from set_get_from_wpa_supplicant
I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
,I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
,I/MDMCTBK (  273): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1,
I/MDMCTBK (  273): send SAR ctrl over QMI
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE ,
,D/Tethering( 1018): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/MDMCTBK (  273): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  273): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  273): , reply_len: 3, ret: 0
E/MDMCTBK (  273): MdmCutbackHndler, resp=OK
E/MDMCTBK (  273): 
,D/MDMCTBK (  273): wifi_set_tx_pwr: Exit
,D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiStateMachine( 1018): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiStateMachine( 1018): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131101
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147459
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): Network connection established
,D/WifiStateMachine( 1018): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1018): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1018): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1018): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1018): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1018): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-43ms what=147462 obj=android.net.wifi.StateChangeResult@428b0db8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=196612
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-4ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1018): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1018): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427c4b50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427c4b50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): handleMessage: X
,D/TCMD    (  451): NL - Read 56 bytes from update socket.
D/TCMD    (  451): NL - message type is RTM_NEWLINK
,D/TCMD    (  451): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
,D/MDMCTBK (  273): Event received = WPS-AP-AVAILABLE 
D/WifiStateMachine( 1018): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1018): processMsg: ObtainingIpState
,D/WifiStateMachine( 1018): ObtainingIpState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): InactiveState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): handleMessage: X
,D/TCMD    (  451): NL - Read 60 bytes from update socket.
D/TCMD    (  451): NL - ignore NL message, type = 20
,D/TCMD    (  451): Listening for incoming client connection request
,D/WifiStateMachine( 1018): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1018): processMsg: ObtainingIpState
,D/WifiStateMachine( 1018): ObtainingIpState{ when=-2ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1018): processMsg: ObtainingIpState
,D/WifiStateMachine( 1018): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
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
D/WifiStateMachine( 1018): handleMessage: X
I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1018): handleMessage: E msg.what=151572
D/WifiStateMachine( 1018): processMsg: VerifyingLinkState
D/WifiStateMachine( 1018): VerifyingLinkState what=151572 NOT_HANDLED
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1094): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=135190
D/WifiStateMachine( 1018): processMsg: VerifyingLinkState
D/WifiStateMachine( 1018): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1018): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1018): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1018): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1018): CaptivePortalCheckState enter
,D/WifiStateMachine( 1018): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/ConnectivityService( 1018): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1018): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1018): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1018): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131092
D/WifiStateMachine( 1018): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1018): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1018): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/ConnectivityService( 1018): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1018): WiFi NOT Tethered!
,E/ConnectivityService( 1018): Unexpected mtu value: android.net.wifi.WifiStateTracker@42856048
I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
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
D/Checkin ( 1018): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
I/SBar.NetworkController( 1094): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1094): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.NetworkController( 1094): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
I/ModemStatsDSDetect( 1224): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1224): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1224): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1018): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1018): WiFi NOT Tethered!
E/ConnectivityService( 1018): Unexpected mtu value: android.net.wifi.WifiStateTracker@42856048
D/ConnectivityService( 1018): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
,I/ModemStatsDSDetect( 1224): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1224): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1224): onReceive() - done, currentInetCondition=0
,I/CheckinService( 1743): Checkin interval check for package: unspecified last checkin: 1452773784588 min interval config: 0 actual interval: 317250
,I/CheckinService( 1743): Checking schedule, now: 1452774101854 next: 1452773814560
,I/CheckinService( 1743): active receiver: enabled
,I/CheckinService( 1743): Preparing to send checkin request
,I/EventLogService( 1743): Accumulating logs since 1452773780977
,I/CheckinRequestBuilder( 1743): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1743): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1018): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4700 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4700): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4700): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4700): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4700): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4700): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4700): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4700): install
,I/MultiDex( 4700): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4700): loading existing secondary dex files
,I/MultiDex( 4700): load found 3 secondary dex files
,I/MultiDex( 4700): install done
,D/dalvikvm( 4700): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4700): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4700): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4700): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4700): VFY: unable to resolve instance field 36
,D/dalvikvm( 4700): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4700): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4700): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4700): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4700): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4700): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4700): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4278fa58
D/dalvikvm( 4700): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4278fa58
,D/dalvikvm( 4700): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4278fa58, skipping init
,D/dalvikvm( 4700): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4278fa58
D/dalvikvm( 4700): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4278fa58
,V/JNIHelp ( 4700): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4700): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4278fa58
,D/dalvikvm( 4700): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4278fa58
D/dalvikvm( 4700): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4278fa58
,D/dalvikvm( 4700): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4278fa58
,I/ProviderInstaller( 4700): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1238): callingUid 10022, callindPid: 1238
,E/MDM     ( 1238): [132] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1348): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1348): Proximity feature is not enabled.
,D/LocationInitializer( 1743): Restart initialization of location
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1238): No location to return for getLastLocation()
,W/FusedLocationProvider( 1238): location=null
,I/dalvikvm( 4700): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4700): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4700): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4700): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4700): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4700): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4700): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4700): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4700): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4700): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4700): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4700): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4700): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4700): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4700): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4700): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4700): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  277): Instantiating CDM.
,I/WVCdm   (  277): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  277): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  277): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  277): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb519b000
,E/DrmWidevineDash(  277): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb519b000
D/DrmWidevineDash(  277): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  277): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  277): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  277): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  277): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  277): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  277): PrepareKeyRequest: nonce=240776521
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4700): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4700): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429deeb0
D/dalvikvm( 4700): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429deeb0
,D/dalvikvm( 4700): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429deeb0, skipping init
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,D/ConnectivityService( 1018): NetTransition Wakelock for ConnectedState released by timeout
,I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  277): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  277): PrepareKeyRequest: nonce=2002471255
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/jxcore-log( 4440): --= Surplus to requirements =--
I/jxcore-log( 4440): 
I/jxcore-log( 4440): ****TEST TOOK:  ms ****
I/jxcore-log( 4440): 
,I/jxcore-log( 4440): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4440): 
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4700): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4756): DexOpt: load 4ms, verify+opt 7ms, 128132 bytes
,D/dalvikvm( 4700): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4700): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 95ms
,I/Adreno-EGL( 4700): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4700): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4700): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4700): Local Branch: 
I/Adreno-EGL( 4700): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4700): Local Patches: NONE
I/Adreno-EGL( 4700): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/AndroidRuntime( 4754): 
D/AndroidRuntime( 4754): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4754): CheckJNI is OFF
,D/dalvikvm( 4754): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4754): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 4754): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4754): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4754): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,I/Adreno-EGL( 4700): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4700): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4700): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4700): Local Branch: 
I/Adreno-EGL( 4700): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4700): Local Patches: NONE
I/Adreno-EGL( 4700): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/dalvikvm( 4754): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,I/Adreno-EGL( 4700): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4700): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4700): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4700): Local Branch: 
I/Adreno-EGL( 4700): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4700): Local Patches: NONE
I/Adreno-EGL( 4700): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4700): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4700): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4700): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4700): Local Branch: 
I/Adreno-EGL( 4700): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4700): Local Patches: NONE
I/Adreno-EGL( 4700): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,E/memtrack( 4754): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4754): failed to load memtrack module: -2
,D/AndroidRuntime( 4754): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10110 user=-1: uninstall pkg
,I/ActivityManager( 1018): Killing 4440:com.test.thalitest/u0a110 (adj 0): stop com.test.thalitest
,W/ContextImpl( 1280): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018):   Force finishing activity ActivityRecord{44c4b298 u0 com.test.thalitest/.MainActivity t2}
,I/WindowState( 1018): WIN DEATH: Window{44c4fef8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1018): Client connection lost with reason: 4
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10110 user=0: pkg removed
,D/dalvikvm( 1311): GC_EXPLICIT freed 3427K, 33% free 11596K/17224K, paused 2ms+4ms, total 43ms
,I/Launcher( 1311): Deferring update until onResume
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1212): resetDictionaries() : en_GB
,I/Keyboard.Facilitator.DecoderInitializer( 1212): run()
,D/VoicemailCleanupService( 1194): Cleaning up data for package: com.test.thalitest
,W/GeofencerStateMachine( 1238): Ignoring removeGeofence because network location is disabled.
,I/Decoder ( 1212): createOrResetDecoder
,I/ActivityManager( 1018): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4778 uid=10033 gids={50033, 3003, 1028, 1015}
D/dalvikvm( 1743): GC_EXPLICIT freed 1055K, 31% free 11966K/17224K, paused 16ms+26ms, total 106ms
W/SQLiteConnectionPool( 1743): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
,D/dalvikvm( 2329): GC_EXPLICIT freed 5185K, 44% free 9650K/17224K, paused 2ms+18ms, total 69ms
D/dalvikvm( 2361): GC_EXPLICIT freed 4089K, 42% free 10092K/17224K, paused 64ms+4ms, total 156ms
D/dalvikvm( 1018): GC_EXPLICIT freed 1387K, 65% free 18272K/51136K, paused 5ms+20ms, total 155ms
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
,I/Launcher( 1311): Deferring update until onResume
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
,I/ConfigService( 1238): onCreate
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
,D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 1018): removePackageParticipantsLocked: uid=10110 #1
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
,W/InputMethodManagerService( 1018): Got RemoteException sending setActive(false) notification to pid 4440 uid 10110
,W/Binder  ( 1212): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1212): java.lang.NullPointerException
W/Binder  ( 1212): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1212): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1212): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1212): 	at dalvik.system.NativeStart.run(Native Method)
,I/Keyboard.Facilitator( 1212): onFinishInput()
,W/Settings( 4700): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1212): run()
,I/ActivityManager( 1018): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4801 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/ActivityManager( 1018): Killing 4369:com.quickoffice.android/u0a95 (adj 15): empty #9
,I/InternalIcingCorporaPro( 2361): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 1280): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1212): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1.apk (offset=5018356, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Loaded File = UserHistory.en_GB.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1212): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1212): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1212): run()
I/StatsUtilsManager( 1212): startPeriodStatsRecorder() : Success
,I/PeriodicStatsRecorder( 1212): shouldRecordStats() = Too Soon
,W/ContextImpl( 4801): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,I/dalvikvm( 3909): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3909): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3909): VFY: replacing opcode 0x6e at 0x0013
,D/PackageBroadcastService( 1743): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1743): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1743): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1743): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1743): Removing dialog suppression flag for package com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 1348): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1348): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/ChimeraCfgMgr( 1743): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1743): Module APK com.google.android.play.games already loaded
,D/gH_CompatibleDatabase( 1743): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1743): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1743): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 1743): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1743): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1743): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1743): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1743): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1743): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1743): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1743): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1743): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1743): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/CheckinRequestBuilder( 1743): Classify the device as Phone.
,I/ActivityManager( 1018): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4834 uid=10059 gids={50059, 1028, 3003, 1015}
D/dalvikvm(  275): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 21ms
,I/ActivityManager( 1018): Killing 4515:android.process.media/u0a18 (adj 15): empty #9
I/Icing   ( 1743): doRemovePackageData com.test.thalitest
,D/dalvikvm( 1018): GC_EXPLICIT freed 732K, 65% free 18312K/51136K, paused 6ms+20ms, total 321ms
W/ContextImpl( 1280): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 19ms
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,I/InternalIcingCorporaPro( 2361): UpdateCorporaTask done [took 205 ms] updated apps [took 204 ms] 
,V/NativeCrypto( 1743): SSL shutdown failed: ssl=0x6bad0b80: I/O error during system call, Connection timed out
,D/AndroidRuntime( 4754): Shutting down VM
,D/dalvikvm( 4754): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
,I/dalvikvm( 4834): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method gqa.a
,W/dalvikvm( 4834): VFY: unable to resolve virtual method 1798: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4834): VFY: replacing opcode 0x6e at 0x000f
,I/GAv4    ( 4834): Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4834):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4834):   adb logcat -s GAv4
,W/GAv4    ( 4834): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/dalvikvm( 4834): Could not find method android.content.Context.checkSelfPermission, referenced from method asa.a
W/dalvikvm( 4834): VFY: unable to resolve virtual method 1616: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4834): VFY: replacing opcode 0x6e at 0x001b
,W/GAv4    ( 4834): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4834): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 4834): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.474.23.34, sample rate 1.0
,I/dalvikvm( 4834): Could not find method android.provider.DocumentsContract.getTreeDocumentId, referenced from method edw.a
W/dalvikvm( 4834): VFY: unable to resolve static method 2986: Landroid/provider/DocumentsContract;.getTreeDocumentId (Landroid/net/Uri;)Ljava/lang/String;
,D/dalvikvm( 4834): VFY: replacing opcode 0x71 at 0x0075
,I/ActivityManager( 1018): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=4868 uid=10095 gids={50095, 3003, 1028, 1015}
,I/ActivityManager( 1018): Killing 4542:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1280): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,E/SQLiteLog( 2329): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
,E/SharedPreferencesImpl( 4834): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml.bak
,E/SQLiteDatabase( 2329): Error inserting state=event=am_kill pid=4542 process=com.android.mms reason=empty+%239 selectadj=15 timestamp=1452774104740 timezone=3600 name=ProcessKillTrigger
E/SQLiteDatabase( 2329): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2329): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2329): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2329): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2329): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2329): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2329): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2329): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2329): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2329): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2329): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2329): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2329): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2329): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2329): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2329): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/cutils  (  261): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
W/Vold    (  261): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4834): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1297): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1615): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1018): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,E/SharedPreferencesImpl( 1462): Couldn't rename file /data/data/com.google.android.backuptransport/shared_prefs/BackupTransport.backupScheduler.xml to backup file /data/data/com.google.android.backuptransport/shared_prefs/BackupTransport.backupScheduler.xml.bak
,I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
D/PollingManager( 1615): now: 364897 ,futureTime: 71543319
,D/PollingManager( 1615): Polling alarm set to expire at: 71543319 Current Time: 364897
,D/TelephonyProvider( 1269): Column apn id key is 'apn_id'
,E/ActivityThread( 1615): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1615): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1615): [debug] > CusSM.onRadioUp
D/dalvikvm( 4834): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4834): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4834): VFY: replacing opcode 0x62 at 0x000a
D/OtaApp  ( 1615): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/dalvikvm( 4834): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4834): VFY: unable to resolve instance field 36
D/dalvikvm( 4834): VFY: replacing opcode 0x54 at 0x005f
I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
W/XTWiFiOS( 1297): No entry in secure settings for enhanced location services: false
D/PollingManager( 1615): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/Tethering( 1018): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1018): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
D/PollingManager( 1615): now: 364912 ,futureTime: 71543319
D/PollingManager( 1615): Polling alarm set to expire at: 71543319 Current Time: 364912
D/TelephonyProvider( 1269): Column apn id key is 'apn_id'
E/SQLiteDatabase( 4868): Failed to open database '/data/data/com.quickoffice.android/databases/keyvaluedb.db'.
E/SQLiteDatabase( 4868): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4868): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4868): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4868): 	at com.qo.android.quickcommon.keyvalueprovider.KeyValueProvider.onCreate(KeyValueProvider.java:42)
E/SQLiteDatabase( 4868): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4868): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4868): 	at androi,d.app.ActivityThread.installProvider(ActivityThread.java:4855)
E/SQLiteDatabase( 4868): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4450)
E/SQLiteDatabase( 4868): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4390)
E/SQLiteDatabase( 4868): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4868): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteDatabase( 4868): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4868): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4868): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4868): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4868): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4868): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4868): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4868): 	at dalvik.system.NativeStart.main(Native Method)

```
