#### Test 55902202f27eba5_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4462): 
D/AndroidRuntime( 4462): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4462): CheckJNI is OFF
D/dalvikvm( 4462): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4462): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4462): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4462): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4462): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4462): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4462): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4462): failed to load memtrack module: -2
D/AndroidRuntime( 4462): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1024): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4462
W/WindowManager( 1024): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1024): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4478 uid=10108 gids={50108, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4462): Shutting down VM
D/dalvikvm( 4462): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4478): Binding Chromium to main looper Looper (main, tid 1) {41f24b70}
I/LibraryLoader( 4478): Expected native library version number "",actual native library version number ""
I/chromium( 4478): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4478): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1024): Message: 20
D/BluetoothManagerService( 1024): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43346348:true
I/Adreno-EGL( 4478): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4478): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4478): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4478): Local Branch: 
I/Adreno-EGL( 4478): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4478): Local Patches: NONE
I/Adreno-EGL( 4478): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4478): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4478): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4478): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4478): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4478): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4478): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4478): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4478): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4478): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4478): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4478): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4478): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4478): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4478): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4478): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4478): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4478): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4478): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4478): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4478): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4478): Enabling debug mode 0
,W/AwContents( 4478): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1214): onFinishInput()
,I/dalvikvm( 1024): Jit: resizing JitTable from 8192 to 16384
,W/IInputConnectionWrapper( 4478): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1024): Displayed com.test.thalitest/.MainActivity,cp,ca,367
I/ActivityManager( 1024): Displayed com.test.thalitest/.MainActivity: +339ms (total +367ms)
,D/JsMessageQueue( 4478): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4478): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f29280
,D/dalvikvm( 4478): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f29280
,D/jxcore_app_log( 4478): JniHelper::setJavaVM(0x41577fa8), pthread_self() = 1615318360
,D/JX-Cordova( 4478): jxcore cordova android initializing
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 4478): GC_CONCURRENT freed 2800K, 17% free 14390K/17224K, paused 3ms+2ms, total 66ms
,D/dalvikvm( 4478): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 4478): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 4478): GC_FOR_ALLOC freed 127K, 17% free 14394K/17224K, paused 26ms, total 27ms
,D/dalvikvm( 4478): GC_FOR_ALLOC freed 128K, 17% free 14411K/17224K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4478): Grow heap (frag case) to 16.197MB for 95956-byte allocation
,D/dalvikvm( 4478): GC_FOR_ALLOC freed 179K, 17% free 14446K/17320K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4478): Grow heap (frag case) to 16.276MB for 143930-byte allocation
,D/dalvikvm( 4478): GC_FOR_ALLOC freed 254K, 18% free 14493K/17464K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4478): Grow heap (frag case) to 16.391MB for 215890-byte allocation
,D/dalvikvm( 4478): GC_FOR_ALLOC freed 368K, 18% free 14567K/17676K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4478): Grow heap (frag case) to 16.566MB for 323830-byte allocation
,D/dalvikvm( 4478): GC_FOR_ALLOC freed 568K, 19% free 14688K/17996K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4478): Grow heap (frag case) to 16.838MB for 485740-byte allocation
,D/dalvikvm( 4478): GC_FOR_ALLOC freed 865K, 20% free 14863K/18472K, paused 26ms, total 26ms
,D/dalvikvm( 4478): GC_FOR_ALLOC freed 1284K, 19% free 15119K/18472K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4478): Grow heap (frag case) to 17.838MB for 1092904-byte allocation
,D/dalvikvm( 4478): GC_CONCURRENT freed 1792K, 21% free 15516K/19540K, paused 2ms+7ms, total 47ms
,D/dalvikvm( 4478): GC_FOR_ALLOC freed 269K, 22% free 15433K/19540K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4478): Grow heap (frag case) to 18.666MB for 1639352-byte allocation
,D/dalvikvm( 4478): GC_CONCURRENT freed 1727K, 25% free 16021K/21144K, paused 1ms+4ms, total 41ms
,D/dalvikvm( 4478): GC_FOR_ALLOC freed 1283K, 24% free 16075K/21144K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4478): Grow heap (frag case) to 20.075MB for 2459024-byte allocation
,D/dalvikvm( 4478): GC_CONCURRENT freed 180K, 23% free 18358K/23548K, paused 4ms+3ms, total 34ms
,D/dalvikvm( 4478): GC_CONCURRENT freed 4397K, 28% free 17080K/23548K, paused 2ms+7ms, total 51ms
,D/dalvikvm( 4478): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/dalvikvm( 4478): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/dalvikvm( 4478): GC_FOR_ALLOC freed 111K, 28% free 17026K/23548K, paused 33ms, total 33ms
,I/dalvikvm-heap( 4478): Grow heap (frag case) to 22.176MB for 3688532-byte allocation
,D/dalvikvm( 4478): GC_CONCURRENT freed 420K, 25% free 20442K/27152K, paused 5ms+6ms, total 57ms
,D/dalvikvm( 4478): GC_FOR_ALLOC freed 3138K, 34% free 18020K/27152K, paused 27ms, total 29ms
,W/jxcore-log( 4478): Initializing JXcore engine
,W/jxcore-log( 4478): JXcore engine is ready
,D/dalvikvm( 4478): GC_CONCURRENT freed 355K, 24% free 20658K/27152K, paused 2ms+2ms, total 30ms
,D/dalvikvm( 4478): WAIT_FOR_CONCURRENT_GC blocked 23ms
,W/jxcore-log( 4478): Starting JXcore engine
,W/jxcore-log( 4478): Platform android
W/jxcore-log( 4478): 
,W/jxcore-log( 4478): Process ARCH arm
W/jxcore-log( 4478): 
,I/jxcore-log( 4478): JXcore Cordova bridge is ready!
I/jxcore-log( 4478): 
,W/jxcore-log( 4478): JXcore engine is started
,I/chromium( 4478): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4478): Toggling radios to true
I/jxcore-log( 4478): 
,D/BluetoothAdapter( 4478): enable(): BT is already enabled..!
D/WifiService( 1024): New client listening to asynchronous messages
D/WifiService( 1024): setWifiEnabled: true pid=4478, uid=10108
,E/WifiService( 1024): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1024): handleMessage: E msg.what=131145
D/WifiStateMachine( 1024): processMsg: ConnectedState
D/WifiStateMachine( 1024): processMsg: L2ConnectedState
I/jxcore-log( 4478): Radios toggled
I/jxcore-log( 4478): 
I/jxcore-log( 4478): My device name is: motorola-XT1039
I/jxcore-log( 4478): 
,I/wpa_supplicant( 1180): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  274): Event received = CTRL-EVENT-DISCONNECTED bssid=c0:
D/MDMCTBK (  274):  STA Disconnected !!
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,0,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
,I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
D/TCMD    (  448): NL - Read 1000 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
,D/TCMD    (  448): Listening for incoming client connection request
D/TCMD    (  448): NL - Read 1000 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
D/TCMD    (  448): Listening for incoming client connection request
D/TCMD    (  448): NL - Read 68 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
D/TCMD    (  448): Listening for incoming client connection request
D/TCMD    (  448): NL - Read 68 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
,D/TCMD    (  448): Listening for incoming client connection request
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
,I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
,I/MDMCTBK (  274): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
I/MDMCTBK (  274): send SAR ctrl over QMI
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
,D/Tethering( 1024): InitialState.processMessage what=4
,D/Tethering( 1024): sendTetherStateChangedBroadcast 0, 0, 0
V/ConnectivityService( 1024): WiFi NOT Tethered!
,D/WifiStateMachine( 1024): transitionTo: destState=DisconnectingState
,D/WifiStateMachine( 1024): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1024): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1024): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1024): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1024): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1024): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1024): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1024): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  272): Clearing all IP addresses on wlan0
D/TCMD    (  448): NL - Read 60 bytes from update socket.
D/TCMD    (  448): NL - ignore NL message, type = 21
,D/TCMD    (  448): Listening for incoming client connection request
,D/WifiStateMachine( 1024): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1024): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1024): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/WifiMetrics( 1024): connected time updated 328766
,D/ConnectivityService( 1024): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/SBar.NetworkController( 1096): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1024): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService( 1024): Attempting to switch to mobile
D/ConnectivityService( 1024): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1024): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1096): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1096): refreshSignalCluster: mobile: Signal=zz_moto_stat_sys_signal_emergency_only_wide Roaming=(none) mSimIconId=zz_moto_stat_sys_no_sim_wide Accessibility="Emergency calls only.","","No SIM card."
I/SBar.NetworkController( 1096): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/WifiStateMachine( 1024): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1024): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState,
D/WifiStateMachine( 1024): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine( 1024): DisconnectingState
E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=131146
D/WifiStateMachine( 1024): processMsg: DisconnectingState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=147460
,D/Checkin ( 1024): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1024): processMsg: DisconnectingState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): Network connection lost
D/WifiStateMachine( 1024): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1024): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1024): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1024): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 1024): resetConnections(wlan0, 3)
D/NetUtils( 1024): android_net_utils_resetConnections in env=0x615c6460 clazz=0x62700001 iface=wlan0 mask=0x3
,V/NativeCrypto( 1357): Read error: ssl=0x6307d720: I/O error during system call, Connection timed out
E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,V/NativeCrypto( 1357): SSL shutdown failed: ssl=0x6307d720: I/O error during system call, Broken pipe
,D/CommandListener(  272): Clearing all IP addresses on wlan0
,D/WifiStateMachine( 1024): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1096): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1024): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1024): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1024): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1024): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1024): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1024): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine( 1024): invokeEnterMethods: DisconnectedState
,D/Checkin ( 1024): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=147462
D/WifiStateMachine( 1024): processMsg: DisconnectedState
D/WifiStateMachine( 1024): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=131101
D/WifiStateMachine( 1024): processMsg: DisconnectedState
,D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): processMsg: DriverStartedState
D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
D/WifiStateMachine( 1024): processMsg: DefaultState
,D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=131216
D/WifiStateMachine( 1024): processMsg: DisconnectedState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): processMsg: DriverStartedState
,D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
D/WifiStateMachine( 1024): processMsg: DefaultState
D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=131216
D/WifiStateMachine( 1024): processMsg: DisconnectedState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): processMsg: DriverStartedState
,D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
D/WifiStateMachine( 1024): processMsg: DefaultState
D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=147462
D/WifiStateMachine( 1024): processMsg: DisconnectedState
,D/WifiStateMachine( 1024): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1024): processMsg: ConnectModeState
,D/WifiStateMachine( 1024): handleMessage: X
,D/Nat464Xlat( 1024): requiresClat: netType=1, hasIPv4Address=false
,I/ModemStatsDSDetect( 1303): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1024): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1303): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1303): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1024): Attempting to switch to mobile
D/ConnectivityService( 1024): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1024): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1024): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1024): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1303): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1303): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1303): onReceive() - done, currentInetCondition=0
,I/wpa_supplicant( 1180): wlan0: Trying to associate with SSID 'NG700'
,D/WifiStateMachine( 1024): handleMessage: E msg.what=147461
D/WifiStateMachine( 1024): processMsg: DisconnectedState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
,E/wpa_supplicant( 1180): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/TCMD    (  448): NL - Read 56 bytes from update socket.
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  448): NL - message type is RTM_NEWLINK
D/TCMD    (  448): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  274): Event received = Trying to associate with
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1024): processMsg: DriverStartedState
,D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=147462
D/WifiStateMachine( 1024): processMsg: DisconnectedState
D/WifiStateMachine( 1024): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1024): processMsg: ConnectModeState
,D/WifiStateMachine( 1024): handleMessage: X
,D/TCMD    (  448): NL - Read 312 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
D/TCMD    (  448): Listening for incoming client connection request
D/TCMD    (  448): NL - Read 192 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
D/TCMD    (  448): Listening for incoming client connection request
D/TCMD    (  448): NL - Read 68 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
,D/TCMD    (  448): Listening for incoming client connection request
I/wpa_supplicant( 1180): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  448): NL - Read 1000 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
D/TCMD    (  448): Listening for incoming client connection request
,I/wpa_supplicant( 1180): WEXT: Custom wireless event: 'BEACONIEs='
,I/wpa_supplicant( 1180): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  274): Event received = Associated with c0:ff:d4
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  448): NL - Read 80 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
D/TCMD    (  448): Listening for incoming client connection request
D/TCMD    (  448): NL - Read 80 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
D/TCMD    (  448): Listening for incoming client connection request
D/TCMD    (  448): NL - Read 68 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
,D/TCMD    (  448): Listening for incoming client connection request
,D/WifiStateMachine( 1024): handleMessage: E msg.what=147462
D/WifiStateMachine( 1024): processMsg: DisconnectedState
,D/WifiStateMachine( 1024): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1180): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1180): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  274): Event received = WPA: Key negotiation com
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  274): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  274):  STA Connected !!
D/TCMD    (  448): NL - Read 1000 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
,D/TCMD    (  448): Listening for incoming client connection request
E/MDMCTBK (  274): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  274): get_freq !!, resp=0
I/MDMCTBK (  274): get_freq !!, Strip data
I/MDMCTBK (  274): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,0,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  274): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  274): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  274): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,0,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1196000432
I/MDMCTBK (  274): return from set_get_from_wpa_supplicant
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
,I/MDMCTBK (  274): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
D/WifiStateMachine( 1024): handleMessage: X
,D/MDMCTBK (  274): wifi_set_tx_pwr: SETTXPOWER = 19
,I/MDMCTBK (  274): send SAR ctrl over QMI
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
E/MDMCTBK (  274): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  274): , reply_len: 3, ret: 0
E/MDMCTBK (  274): MdmCutbackHndler, resp=OK,
E/MDMCTBK (  274): 
,D/MDMCTBK (  274): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1024): handleMessage: E msg.what=147462
D/WifiStateMachine( 1024): processMsg: DisconnectedState
,D/WifiStateMachine( 1024): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1024): processMsg: ConnectModeState
,D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=147462
D/WifiStateMachine( 1024): processMsg: DisconnectedState
,D/WifiStateMachine( 1024): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=147459
,D/WifiStateMachine( 1024): processMsg: DisconnectedState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
,D/WifiStateMachine( 1024): Network connection established
,D/Tethering( 1024): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1024): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1024): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/WifiStateMachine( 1024): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1024): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1024): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1024): invokeExitMethods: DisconnectedState
,I/SBar.NetworkController( 1096): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1024): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1024): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1024): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
,D/WifiStateMachine( 1024): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1024): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1024): handleMessage: X
,D/WifiStateMachine( 1024): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1024): processMsg: ObtainingIpState
D/WifiStateMachine( 1024): ObtainingIpState{ when=-44ms what=147462 obj=android.net.wifi.StateChangeResult@4441c088 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1024): processMsg: L2ConnectedState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
,D/WifiStateMachine( 1024): handleMessage: X
,D/WifiStateMachine( 1024): handleMessage: E msg.what=131101
D/WifiStateMachine( 1024): processMsg: ObtainingIpState
,D/WifiStateMachine( 1024): ObtainingIpState{ when=-36ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@4441e220 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1024): processMsg: L2ConnectedState
,D/WifiStateMachine( 1024): processMsg: ConnectModeState
,D/WifiStateMachine( 1024): processMsg: DriverStartedState
D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
D/WifiStateMachine( 1024): processMsg: DefaultState
,D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=196612
,D/WifiStateMachine( 1024): processMsg: ObtainingIpState
D/WifiStateMachine( 1024): ObtainingIpState{ when=-13ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1024): processMsg: L2ConnectedState
,D/WifiStateMachine( 1024): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1024): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1024): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42754348 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1024): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42754348 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1024): handleMessage: X
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 3
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 5 3
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 9
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 6 9
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 6
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 7 6
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 9e
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 9e
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE-AUTH 
D/WifiStateMachine( 1024): handleMessage: E msg.what=147461
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiStateMachine( 1024): processMsg: ObtainingIpState
D/TCMD    (  448): NL - Read 56 bytes from update socket.
D/TCMD    (  448): NL - message type is RTM_NEWLINK
,D/TCMD    (  448): Listening for incoming client connection request
D/WifiStateMachine( 1024): ObtainingIpState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1024): processMsg: L2ConnectedState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): processMsg: DriverStartedState
,D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
D/WifiP2pService( 1024): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1024): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1024): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1024): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@44429e88 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1024): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@44429e88 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1024): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@44429e88 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1024): handleMessage: X
,D/TCMD    (  448): NL - Read 60 bytes from update socket.
D/TCMD    (  448): NL - ignore NL message, type = 20
,D/TCMD    (  448): Listening for incoming client connection request
,D/WifiStateMachine( 1024): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1024): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1024): processMsg: ObtainingIpState
D/WifiStateMachine( 1024): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1024): processMsg: L2ConnectedState
D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): processMsg: DriverStartedState
,D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1024): processMsg: DefaultState
D/WifiStateMachine( 1024): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1024): handleMessage: X
,D/WifiStateMachine( 1024): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1024): processMsg: ObtainingIpState
,D/WifiStateMachine( 1024): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1024): processMsg: L2ConnectedState
,D/WifiStateMachine( 1024): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1024): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1024): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1024): DHCP successful
D/WifiStateMachine( 1024): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1024): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1024): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1024): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1024): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1024): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1024): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1024): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1024): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1024): VerifyingLinkState enter
D/WifiStateMachine( 1024): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1096): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1024): handleMessage: X
,D/WifiStateMachine( 1024): handleMessage: E msg.what=151572
D/WifiStateMachine( 1024): processMsg: VerifyingLinkState
D/WifiStateMachine( 1024): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1024): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1096): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/WifiStateMachine( 1024): handleMessage: X
,D/WifiStateMachine( 1024): handleMessage: E msg.what=135190
D/WifiStateMachine( 1024): processMsg: VerifyingLinkState
D/WifiStateMachine( 1024): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 1024): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1024): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1024): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1024): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1024): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1024): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
,D/WifiStateMachine( 1024): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1024): CaptivePortalCheckState enter
,D/WifiStateMachine( 1024): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1024): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1096): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1024): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1024): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1024): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine( 1024): handleMessage: X
D/WifiStateMachine( 1024): handleMessage: E msg.what=131092
D/WifiStateMachine( 1024): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1024): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1024): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1024): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1096): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService( 1024): WiFi NOT Tethered!
,E/ConnectivityService( 1024): Unexpected mtu value: android.net.wifi.WifiStateTracker@41ff6168
I/SBar.NetworkController( 1096): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1024): requiresClat: netType=1, hasIPv4Address=true
D/Checkin ( 1024): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ModemStatsDSDetect( 1303): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1096): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/ModemStatsDSDetect( 1303): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1303): onReceive() - done, currentInetCondition=0
,I/SBar.NetworkController( 1096): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/WifiStateMachine( 1024): transitionTo: destState=ConnectedState
,D/WifiStateMachine( 1024): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1024): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1024): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1024): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1024): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1024): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1024): handleMessage: X
,D/WifiStateMachine( 1024): handleMessage: E msg.what=131092
,D/WifiStateMachine( 1024): processMsg: ConnectedState
D/WifiStateMachine( 1024): processMsg: L2ConnectedState
,D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): processMsg: DriverStartedState
D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1024): processMsg: DefaultState
,D/WifiStateMachine( 1024): handleMessage: X
,D/ConnectivityService( 1024): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1024): WiFi NOT Tethered!
,E/ConnectivityService( 1024): Unexpected mtu value: android.net.wifi.WifiStateTracker@41ff6168
,D/ConnectivityService( 1024): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1024): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1303): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1303): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1303): onReceive() - done, currentInetCondition=0
,D/ConnectivityService( 1024): NetTransition Wakelock for ConnectedState released by timeout
,D/Tethering( 1024): MasterInitialState.processMessage what=3
,D/PollingManager( 1619): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1024): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1024): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1096): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
W/XTWiFiOS( 1283): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1096): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
I/SBar.NetworkController( 1096): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/ActivityManager( 1024): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4607 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1096): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1096): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,W/XTWiFiOS( 1283): No entry in secure settings for enhanced location services: false
,D/Tethering( 1024): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1024): NoActiveNetworkState{ when=-5ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
,E/ActivityThread( 1619): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1619): Registering with Alarm Manager to restart CCE
,D/PollingManager( 1619): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1619): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
E/ActivityThread( 1619): Failed to find provider info for com.motorola.blur.setupprovider
,D/OtaApp  ( 1619): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
,D/OtaApp  ( 1619): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
,D/dalvikvm( 4607): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f2ce10, skipping init
I/openssl ( 4607): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4607): Crypto mode 0 already enabled
,I/ActivityManager( 1024): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4641 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1024): Killing 4195:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4641): mnc/mcc: 
V/MmsConfig( 4641): tag: bool value: enabledMMS - true
,V/MmsConfig( 4641): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4641): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4641): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4641): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4641): tag: int value: defaultMMSMessagesPerThread - 50
,V/MmsConfig( 4641): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4641): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4641): tag: int value: recipientLimit - 20
V/MmsConfig( 4641): tag: bool value: enableMultipartSMS - true
,V/MmsConfig( 4641): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4641): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4641): tag: int value: maxMessageTextSize - -1
,V/MmsConfig( 4641): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4641): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4641): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 4641): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4641): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1024): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4660 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1024): Killing 4302:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4660): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4660): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4660): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4660): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1024): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4673 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1024): Killing 4338:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1780): Checkin interval check for package: unspecified last checkin: 1452699281583 min interval config: 0 actual interval: 313913
,I/CheckinService( 1780): Checking schedule, now: 1452699595502 next: 1452699311560
,I/CheckinService( 1780): active receiver: enabled
,I/CheckinService( 1780): Preparing to send checkin request
,I/EventLogService( 1780): Accumulating logs since 1452699277356
,D/dalvikvm( 1024): GC_EXPLICIT freed 23696K, 65% free 18395K/51412K, paused 4ms+11ms, total 148ms
,V/WebViewChromiumFactoryProvider( 4673): Binding Chromium to main looper Looper (main, tid 1) {41f28b58}
,I/LibraryLoader( 4673): Expected native library version number "",actual native library version number ""
,I/chromium( 4673): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4673): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4673): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4673): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4673): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4673): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4673): Local Branch: 
I/Adreno-EGL( 4673): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4673): Local Patches: NONE
I/Adreno-EGL( 4673): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1780): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1780): Failed to find provider info for com.google.android.wearable.settings
,W/chromium( 4673): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4673): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4673): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1024): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4708 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4708): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4708): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4708): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
,W/dalvikvm( 4708): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4708): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 4708): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4708): install
,I/MultiDex( 4708): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4708): loading existing secondary dex files
,I/MultiDex( 4708): load found 3 secondary dex files
,I/MultiDex( 4708): install done
,D/dalvikvm( 4708): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4708): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4708): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4708): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4708): VFY: unable to resolve instance field 36
,D/dalvikvm( 4708): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 4708): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4708): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4708): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4708): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4708): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4708): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f2e908
,D/dalvikvm( 4708): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f2e908
,D/dalvikvm( 4708): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f2e908, skipping init
,D/dalvikvm( 4708): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f2e908
D/dalvikvm( 4708): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f2e908
,V/JNIHelp ( 4708): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4708): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f2e908
,D/dalvikvm( 4708): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f2e908
D/dalvikvm( 4708): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f2e908
,D/dalvikvm( 4708): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f2e908
,I/NSApplication( 4673): Starting up...
,I/ActivityManager( 1024): Killing 4061:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1024): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=4728 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ProviderInstaller( 4708): Installed default security provider GmsCore_OpenSSL
,D/dalvikvm( 4728): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 4728): VFY: unable to resolve instance field 68
D/dalvikvm( 4728): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 4728): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4728): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 4728): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 4728): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/DEBUG   ( 1619): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1619): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1619): bindWebServices(): registering our AIDL callback...
I/SundryService( 1619): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1619): ServiceHandler.handleMessage: mWaitCount=0
I/dalvikvm( 4708): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4708): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4708): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4708): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4708): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4708): VFY: replacing opcode 0x6e at 0x000d
,I/ActivityManager( 1024): Killing 4376:com.google.android.apps.docs/u0a59 (adj 15): empty #9
D/EmailService.MarketingOptInSetter( 1619): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1619): onServiceConnected()
D/GetNotificationsWS( 1619): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1619): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/openssl ( 4607): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4607): Crypto mode 0 already enabled
,D/dalvikvm( 4728): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 4728): VFY: unable to resolve instance field 68
,D/dalvikvm( 4728): VFY: replacing opcode 0x54 at 0x0011
,D/MobileConnectivityChangeReceiver( 4660): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4660): onReceive CONNECTIVITY_CHANGE networkType=1
,I/dalvikvm( 4708): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4708): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4708): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4708): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 4708): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4708): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4708): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4708): VFY: replacing opcode 0x6e at 0x0036
D/dalvikvm( 4728): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4728): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4728): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4728): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4728): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4728): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
I/dalvikvm( 4708): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4708): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4708): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  279): Instantiating CDM.
,I/WVCdm   (  279): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  279): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  279): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  279): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb50ab000
,E/DrmWidevineDash(  279): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb50ab000
,D/WearableService( 1228): callingUid 10022, callindPid: 1228
,E/MDM     ( 1228): [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/DrmWidevineDash(  279): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_APIVersion...
,D/LocationInitializer( 1780): Restart initialization of location
D/DrmWidevineDash(  279): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  279): calling OEMCrypto_IsKeyboxValid...
,D/AuthorizationBluetoothService( 1357): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1357): Proximity feature is not enabled.
D/DrmWidevineDash(  279): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  279): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  279): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetRandom...
,V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DrmWidevineDash(  279): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  279): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetDeviceID...
,W/GCoreFlp( 1228): No location to return for getLastLocation()
,W/FusedLocationProvider( 1228): location=null
,D/DrmWidevineDash(  279): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=2417278528
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4708): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4708): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4210a180
D/dalvikvm( 4708): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4210a180
,D/dalvikvm( 4708): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4210a180, skipping init
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,D/Tethering( 1024): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1096): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/CaptivePortalTracker( 1024): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1283): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1096): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/PollingManager( 1619): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1619): now: 361625 ,futureTime: 59645909
D/PollingManager( 1619): Polling alarm set to expire at: 59645909 Current Time: 361626
,D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
E/ActivityThread( 1619): Failed to find provider info for com.motorola.blur.setupprovider
I/openssl ( 4607): Crypto mode not selected, openssl will run on its regular mode.
,D/OtaApp  ( 1619): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/openssl ( 4607): Crypto mode 0 already enabled
D/OtaApp  ( 1619): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1619): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/Tethering( 1024): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1096): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1096): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/PollingManager( 1619): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1024): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/PollingManager( 1619): now: 361652 ,futureTime: 59645909
,D/PollingManager( 1619): Polling alarm set to expire at: 59645909 Current Time: 361652
,D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
,W/XTWiFiOS( 1283): No entry in secure settings for enhanced location services: false
,D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
,D/OtaApp  ( 1619): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1619): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (Notified)
,D/Checkin ( 1619): publish the event [tag = MOT_OTA event name = LOG]
,E/ActivityThread( 1619): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1619): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/MobileConnectivityChangeReceiver( 4660): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4660): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1619): [debug] > CusSM.runStateMachine: server told to :continue
,D/dalvikvm( 1619): GC_CONCURRENT freed 6401K, 38% free 10781K/17224K, paused 7ms+7ms, total 77ms
,I/CheckinService( 1780): Checkin interval check for package: unspecified last checkin: 1452699281583 min interval config: 0 actual interval: 315151
,D/OtaApp  ( 1619): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1619): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/dalvikvm( 4708): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/OtaApp  ( 1619): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1619): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (Notified)
,D/Checkin ( 1619): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1619): [debug] > CusSM.runStateMachine: server told to :continue
,D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
,D/DEBUG   ( 1619): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1619): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1619): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1619): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1619): onServiceConnected()
I/SundryService( 1619): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 1619): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1619): ServiceHandler.handleMessage: mWaitCount=0
I/openssl ( 4607): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4607): Crypto mode 0 already enabled
D/GetNotificationsWS( 1619): unbindWebServices(): un-registering our AIDL callback...
,D/MobileConnectivityChangeReceiver( 4660): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4660): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 1780): Checkin interval check for package: unspecified last checkin: 1452699281583 min interval config: 0 actual interval: 315241
,D/dalvikvm( 4762): DexOpt: load 4ms, verify+opt 11ms, 128132 bytes
,D/dalvikvm( 4708): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4708): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 95ms
,D/DEBUG   ( 1619): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1619): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1619): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1619): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1619): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1619): onServiceConnected()
,D/GetNotificationsWS( 1619): onServiceConnected(): Registered for remote service callbacks...
,I/Adreno-EGL( 4708): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4708): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4708): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4708): Local Branch: 
I/Adreno-EGL( 4708): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4708): Local Patches: NONE
I/Adreno-EGL( 4708): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/WaitableIntentService( 1619): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1619): [debug] > Receive intent: com.motorola.ccc.ota.UPGRADE_UPDATE_NOTIFICATION_AVAILABLE
,D/GetNotificationsWS( 1619): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 1619): [debug] > Received start id 2: Intent { cmp=com.motorola.ccc.ota/.ui.NotificationService (has extras) }
,D/OtaApp  ( 1619): [debug] > handle intent : null
,D/OtaApp  ( 1619): [debug] > supress duplicated intent, nextPompt: 1452785684272 and mNotificationInStatusBar: true
,D/OtaApp  ( 1619): [debug] > Receive intent: com.motorola.ccc.ota.UPGRADE_UPDATE_NOTIFICATION_AVAILABLE
,D/OtaApp  ( 1619): [debug] > Received start id 3: Intent { cmp=com.motorola.ccc.ota/.ui.NotificationService (has extras) }
,D/OtaApp  ( 1619): [debug] > handle intent : null
,D/OtaApp  ( 1619): [debug] > supress duplicated intent, nextPompt: 1452785684272 and mNotificationInStatusBar: true
,I/Adreno-EGL( 4708): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4708): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4708): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4708): Local Branch: 
I/Adreno-EGL( 4708): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4708): Local Patches: NONE
I/Adreno-EGL( 4708): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 4708): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4708): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4708): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4708): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4708): Local Branch: 
I/Adreno-EGL( 4708): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4708): Local Patches: NONE
I/Adreno-EGL( 4708): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4708): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4708): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4708): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4708): Local Branch: 
I/Adreno-EGL( 4708): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4708): Local Patches: NONE
I/Adreno-EGL( 4708): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/WifiStateMachine( 1024): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1024): handleMessage: E msg.what=131215
D/WifiStateMachine( 1024): processMsg: ConnectedState
D/WifiStateMachine( 1024): processMsg: L2ConnectedState
,D/WifiStateMachine( 1024): processMsg: ConnectModeState
D/WifiStateMachine( 1024): processMsg: DriverStartedState
D/WifiStateMachine( 1024): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1024): processMsg: DefaultState
,D/WifiStateMachine( 1024): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1024): handleMessage: X
,D/ConnectivityService( 1024): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1024):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1024): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1024): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1024): requiresClat: netType=1, hasIPv4Address=true
,I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  279): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  279): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  279): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  279): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=3834107029
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1780): Classify the device as Phone.
,V/NativeCrypto( 1780): SSL shutdown failed: ssl=0x6c2d6ea8: I/O error during system call, Connection timed out
,D/dalvikvm( 1780): GC_CONCURRENT freed 1764K, 30% free 12110K/17224K, paused 4ms+5ms, total 50ms
,I/CheckinTask( 1780): Sending checkin request (11893 bytes)
,V/AlarmManager( 1024): sending alarm Alarm{444996b8 type 2 com.google.android.gms}
,V/AlarmManager( 1024): sending alarm Alarm{44499790 type 0 com.google.android.gms}
,I/EventLogService( 1780): Aggregate from 1452699595677 (log), 1452697649446 (data)
,I/CheckinRequestBuilder( 1780): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1780): Failed to find provider info for com.google.android.wearable.settings
,I/PhenotypeConfigurator( 1228): Scheduling Phenotype for one-off execution 5291 seconds from now (1452699598707)
,D/GetConfigurationSnapshotOperation( 1228): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/dalvikvm( 1024): GC_EXPLICIT freed 891K, 65% free 18214K/51412K, paused 4ms+10ms, total 109ms
,I/PhenotypeFlagCommitter( 1228): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1228): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1228): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1228): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1228): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1228): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1228): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1228): Using platform SSLCertificateSocketFactory
,I/CheckinRequestBuilder( 1780): Classify the device as Phone.
,I/CheckinTask( 1780): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1780): Checking schedule, now: 1452699598920 next: 1452741652913
,I/CheckinService( 1780): active receiver: disabled
,I/dalvikvm( 1228): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1228): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1228): VFY: replacing opcode 0x6e at 0x003d
,I/CheckinService( 1780): Checking schedule, now: 1452699598938 next: 1452741652913
,I/CheckinService( 1780): active receiver: disabled
,D/CheckinService( 1780): Recording last checkin time for package unspecified as 1452699598944
,D/GCM     ( 1357): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService( 1024): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/SBar.NetworkController( 1096): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1303): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1096): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1096): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1303): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1303): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1303): onReceive() - done, currentInetCondition=100
,D/dalvikvm( 1228): GC_CONCURRENT freed 1673K, 35% free 11333K/17224K, paused 4ms+4ms, total 34ms
,V/AlarmManager( 1024): sending alarm Alarm{42085ab0 type 3 android}
,I/GAV2    ( 4673): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1024): Killing 4410:com.quickoffice.android/u0a95 (adj 15): empty #9
,W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 4478): Test app app.js loaded
I/jxcore-log( 4478): 
,I/chromium( 4478): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 4478): --= Surplus to requirements =--
I/jxcore-log( 4478): 
,I/jxcore-log( 4478): ****TEST TOOK:  ms ****
I/jxcore-log( 4478): 
,I/jxcore-log( 4478): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4478): 
,D/AndroidRuntime( 4838): 
D/AndroidRuntime( 4838): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4838): CheckJNI is OFF
,D/dalvikvm( 4838): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4838): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4838): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4838): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4838): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4838): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,E/memtrack( 4838): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4838): failed to load memtrack module: -2
,D/AndroidRuntime( 4838): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1024): Force stopping com.test.thalitest appid=10108 user=-1: uninstall pkg
,I/ActivityManager( 1024): Killing 4478:com.test.thalitest/u0a108 (adj 0): stop com.test.thalitest
,W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1024):   Force finishing activity ActivityRecord{43837290 u0 com.test.thalitest/.MainActivity t2}
,I/WindowState( 1024): WIN DEATH: Window{43835f30 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1024): Client connection lost with reason: 4
,I/ActivityManager( 1024): Force stopping com.test.thalitest appid=10108 user=0: pkg removed
,D/dalvikvm( 1317): GC_EXPLICIT freed 3427K, 33% free 11597K/17224K, paused 2ms+4ms, total 50ms
,W/GeofencerStateMachine( 1228): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1214): resetDictionaries() : en_GB
,I/Launcher( 1317): Deferring update until onResume
,I/Keyboard.Facilitator.DecoderInitializer( 1214): run()
,I/Decoder ( 1214): createOrResetDecoder
,I/InputReader( 1024): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "sms"
D/VoicemailCleanupService( 1193): Cleaning up data for package: com.test.thalitest
,D/dalvikvm( 1780): GC_EXPLICIT freed 938K, 31% free 11905K/17224K, paused 4ms+6ms, total 142ms
,W/SQLiteConnectionPool( 1780): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/dalvikvm( 1024): GC_EXPLICIT freed 702K, 65% free 18204K/51412K, paused 5ms+23ms, total 148ms
,D/dalvikvm( 2349): GC_EXPLICIT freed 5176K, 44% free 9650K/17224K, paused 19ms+8ms, total 58ms
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 1024):   Scheme: "smsto"
I/ActivityManager( 1024): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4860 uid=10033 gids={50033, 3003, 1028, 1015}
,D/dalvikvm( 2382): GC_EXPLICIT freed 5025K, 40% free 10482K/17224K, paused 2ms+41ms, total 140ms
,D/dalvikvm(  277): GC_EXPLICIT freed 42K, 48% free 9013K/17224K, paused 2ms+3ms, total 26ms
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "mms"
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9013K/17224K, paused 1ms+2ms, total 21ms
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9013K/17224K, paused 2ms+2ms, total 24ms
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "mmsto"
,D/BackupManagerService( 1024): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 1024): removePackageParticipantsLocked: uid=10108 #1
I/ConfigService( 1228): onCreate
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "sms"
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "smsto"
,I/Launcher( 1317): Deferring update until onResume
W/InputMethodManagerService( 1024): Got RemoteException sending setActive(false) notification to pid 4478 uid 10108
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "mms"
W/Binder  ( 1214): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1214): java.lang.NullPointerException
W/Binder  ( 1214): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1214): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1214): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1214): 	at dalvik.system.NativeStart.run(Native Method)
I/Keyboard.Facilitator( 1214): onFinishInput()
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "mmsto"
,I/InternalIcingCorporaPro( 2382): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1214): run()
,I/ActivityManager( 1024): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4880 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/ActivityManager( 1024): Killing 3975:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 4880): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/Keyboard.Facilitator.MainLanguageModelLoader( 1214): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1.apk (offset=5018356, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Loaded File = UserHistory.en_GB.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1214): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1214): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1214): run()
I/ActivityManager( 1024): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4893 uid=10038 gids={50038, 3003, 1028, 1015}
I/StatsUtilsManager( 1214): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1214): shouldRecordStats() = Too Soon
,D/dalvikvm( 1024): GC_EXPLICIT freed 625K, 65% free 18297K/51412K, paused 6ms+14ms, total 227ms
,I/ActivityManager( 1024): Killing 4607:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2382): UpdateCorporaTask done [took 130 ms] updated apps [took 130 ms] 
,I/dalvikvm( 4893): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4893): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4893): VFY: replacing opcode 0x6e at 0x000e
,D/AndroidRuntime( 4838): Shutting down VM
,D/dalvikvm( 4838): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+1ms, total 2ms
,D/dalvikvm( 1357): GC_EXPLICIT freed 1266K, 40% free 10364K/17224K, paused 2ms+4ms, total 30ms
,D/Finsky  ( 4893): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 4893): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4893): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4893): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4893): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4893): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4893): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4893): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4893): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4893): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4893): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4893): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4893): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4893): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4893): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4893): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 4893): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4893): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4893): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4893): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4893): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4893): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1024): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4928 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4893): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4893): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4893): VFY: replacing opcode 0x6e at 0x0019
,I/ActivityManager( 1024): Killing 4641:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1273): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Ads     ( 4893): Skipping gmscore version check
D/PackageBroadcastService( 1780): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1780): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1780): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1780): Module APK com.google.android.play.games already loaded
D/Finsky  ( 4893): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4893): [1] Libraries$2.run: Finished loading 1 libraries.
I/LocationSettingsChecker( 1780): Removing dialog suppression flag for package com.test.thalitest
I/dalvikvm( 4893): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4893): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4893): VFY: replacing opcode 0x6e at 0x0013
,D/ChimeraCfgMgr( 1780): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1780): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1357): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1357): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,E/SQLiteDatabase( 2349): Error inserting state=event=am_kill pid=4641 process=com.android.mms reason=empty+%239 selectadj=15 timestamp=1452699605360 timezone=3600 name=ProcessKillTrigger
E/SQLiteDatabase( 2349): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 2349): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2349): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2349): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2349): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2349): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2349): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2349): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2349): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2349): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2349): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2349): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2349): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2349): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2349): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2349): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/FileUtils( 1780): Failed to chmod(/data/data/com.google.android.gms/databases/phenotype.db): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/SQLiteLog( 1780): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/ActivityManager( 1024): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4956 uid=10059 gids={50059, 1028, 3003, 1015}
E/SQLiteDatabase( 1780): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1780): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1780): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1780): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1780): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1780): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1780): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1780): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1780): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1780): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1780): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1780): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1780): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1780): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1780): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1780): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1780): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1780): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1780): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1780): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1780): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1780): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1780): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1780): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 1780): threadid=52: thread exiting with uncaught exception (group=0x41656d40)
E/SharedPreferencesImpl( 4893): Couldn't rename file /data/data/com.android.vending/shared_prefs/finsky.xml to backup file /data/data/com.android.vending/shared_prefs/finsky.xml.bak
E/SQLiteLog( 1780): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 1780): threadid=56: thread exiting with uncaught exception (group=0x41656d40)
I/Process ( 1780): Sending signal. PID: 1780 SIG: 9
,W/FileUtils( 4928): Failed to chmod(/data/data/com.android.providers.media/databases/external.db): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
E/MediaProvider( 4928): failed to open database external.db
E/MediaProvider( 4928): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/MediaProvider( 4928): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/MediaProvider( 4928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/MediaProvider( 4928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/MediaProvider( 4928): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/MediaProvider( 4928): 	at android.database.sqlite.SQLiteConnectionPool.tryAcquireNonPrimaryConnectionLocked(SQLiteConnectionPool.java:899)
E/MediaProvider( 4928): 	at android.database.sqlite.SQLiteConnectionPool.waitForConnection(SQLiteConnectionPool.java:609)
E/MediaProvider( 4928): 	at android.database.sqlite.SQLiteConnectionPool.acquireConnection(SQLiteConnectionPool.java:348)
E/MediaProvider( 4928): 	at android.database.sqlite.SQLiteSession.acquireConnection(SQLiteSession.java:894)
E/MediaProvider( 4928): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:650)
E/MediaProvider( 4928): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
E/MediaProvider( 4928): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
E/MediaProvider( 4928): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
E/MediaProvider( 4928): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:862)
E/MediaProvider( 4928): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:242)
E/MediaProvider( 4928): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/MediaProvider( 4928): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:441)
E/MediaProvider( 4928): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:5400)
E/MediaProvider( 4928): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:645)
E/MediaProvider( 4928): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/MediaProvider( 4928): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/MediaProvider( 4928): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4855)
E/MediaProvider( 4928): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4450)
E/MediaProvider( 4928): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4390)
E/MediaProvider( 4928): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/MediaProvider( 4928): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/MediaProvider( 4928): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/MediaProvider( 4928): 	at android.os.Looper.loop(Looper.java:136)
E/MediaProvider( 4928): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/MediaProvider( 4928): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/MediaProvider( 4928): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/MediaProvider( 4928): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/MediaProvider( 4928): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/MediaProvider( 4928): 	at dalvik.system.NativeStart.main(Native Method)
D/WifiService( 1024): Client connection lost with reason: 4
I/ActivityManager( 1024): Process com.google.android.gms (pid 1780) has died.
E/SQLiteDatabase( 4928): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4928): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4928): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4928): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2337)
E/SQLiteDatabase( 4928): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:5409)
E/SQLiteDatabase( 4928): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:645)
E/SQLiteDatabase( 4928): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4928): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4928): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4855)
E/SQLiteDatabase( 4928): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4450)
E/SQLiteDatabase( 4928): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4390)
E/SQLiteDatabase( 4928): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4928): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteDatabase( 4928): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4928): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4928): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4928): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4928): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4928): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4928): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4928): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager( 1024): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
W/ActivityManager( 1024): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager( 1024): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
E/SQLiteOpenHelper( 4928): Couldn't open external.db for writing (will try read-only):
E/SQLiteOpenHelper( 4928): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4928): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4928): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4928): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 4928): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 4928): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4928): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 4928): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4928): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4928): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2337)
E/SQLiteOpenHelper( 4928): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:5409)
E/SQLiteOpenHelper( 4928): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:645)
E/SQLiteOpenHelper( 4928): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteOpenHelper( 4928): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteOpenHelper( 4928): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4855)
E/SQLiteOpenHelper( 4928): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4450)
E/SQLiteOpenHelper( 4928): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4390)
E/SQLiteOpenHelper( 4928): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 4928): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteOpenHelper( 4928): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4928): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 4928): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteOpenHelper( 4928): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4928): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4928): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteOpenHelper( 4928): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteOpenHelper( 4928): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager( 1024): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager( 1024): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager( 1024): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager( 1024): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1000ms
W/ActivityManager( 1024): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.AppsMonitorIntentService in 11000ms
W/ActivityManager( 1024): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 21000ms
W/ActivityManager( 1024): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 31000ms
E/SQLiteLog( 4928): (14) cannot open file at line 28970 of [00bb9c9ce4]
E/SQLiteLog( 4928): (14) os_unix.c:28970: (30) open(/data/data/com.android.providers.media/databases/external.db-shm) - 
E/SQLiteLog( 4928): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
D/AndroidRuntime( 4928): Shutting down VM
W/dalvikvm( 4928): threadid=1: thread exiting with uncaught exception (group=0x41656d40)
E/AndroidRuntime( 4928): FATAL EXCEPTION: main
E/AndroidRuntime( 4928): Process: android.process.media, PID: 4928
E/AndroidRuntime( 4928): java.lang.RuntimeException: Unable to get provider com.android.providers.media.MediaProvider: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
E/AndroidRuntime( 4928): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4858)
E/AndroidRuntime( 4928): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4450)
E/AndroidRuntime( 4928): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4390)
E/AndroidRuntime( 4928): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/AndroidRuntime( 4928): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/AndroidRuntime( 4928): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4928): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4928): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4928): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4928): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4928): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4928): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4928): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4928): Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLong(Native Method)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteConnection.executeForLong(SQLiteConnection.java:598)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:652)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
E/AndroidRuntime( 4928): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
E/AndroidRuntime( 4928): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:862)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:242)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 4928): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2337)
E/AndroidRuntime( 4928): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:5409)
E/AndroidRuntime( 4928): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:645)
E/AndroidRuntime( 4928): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 4928): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 4928): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4855)
E/AndroidRuntime( 4928): 	... 12 more
I/Process ( 4928): Sending signal. PID: 4928 SIG: 9
E/DropBoxManagerService( 1024): Can't write: system_app_crash
E/DropBoxManagerService( 1024): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1024): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1024): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1024): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1024): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1024): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1024): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1024): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1024): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1024): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1024): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1024): 	... 5 more
I/ActivityManager( 1024): Process android.process.media (pid 4928) has died.
W/ActivityManager( 1024): Scheduling restart of crashed service com.android.providers.downloads/.DownloadService in 40982ms

```
