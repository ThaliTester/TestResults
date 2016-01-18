#### Test 5635717154d1b6f_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4309): 
D/AndroidRuntime( 4309): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4309): CheckJNI is OFF
D/dalvikvm( 4309): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4309): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4309): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4309): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4309): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4309): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4309): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4309): failed to load memtrack module: -2
D/AndroidRuntime( 4309): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1017): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4309
W/WindowManager( 1017): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1017): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4325 uid=10123 gids={50123, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4309): Shutting down VM
D/dalvikvm( 4309): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+1ms, total 2ms
W/ContextImpl( 1268): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1268): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4325): Binding Chromium to main looper Looper (main, tid 1) {41f78fa0}
I/LibraryLoader( 4325): Expected native library version number "",actual native library version number ""
I/chromium( 4325): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4325): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1017): Message: 20
D/BluetoothManagerService( 1017): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@440fba10:true
I/Adreno-EGL( 4325): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4325): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4325): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4325): Local Branch: 
I/Adreno-EGL( 4325): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4325): Local Patches: NONE
I/Adreno-EGL( 4325): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4325): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 4325): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 4325): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4325): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4325): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
,W/dalvikvm( 4325): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 4325): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 4325): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 4325): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4325): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4325): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 4325): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 4325): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
,I/dalvikvm( 4325): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4325): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 4325): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4325): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4325): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 4325): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4325): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4325): Enabling debug mode 0
,W/AwContents( 4325): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1206): onFinishInput()
,W/IInputConnectionWrapper( 4325): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1017): Displayed com.test.thalitest/.MainActivity,cp,ca,456
I/ActivityManager( 1017): Displayed com.test.thalitest/.MainActivity: +418ms (total +456ms)
,D/JsMessageQueue( 4325): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4325): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f7d270
,D/dalvikvm( 4325): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f7d270
D/jxcore_app_log( 4325): JniHelper::setJavaVM(0x41695f78), pthread_self() = 1614715232
,D/JX-Cordova( 4325): jxcore cordova android initializing
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
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 4325): GC_CONCURRENT freed 2689K, 16% free 14500K/17224K, paused 3ms+3ms, total 39ms
,D/dalvikvm( 4325): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 4325): GC_FOR_ALLOC freed 419K, 14% free 14913K/17224K, paused 27ms, total 28ms
,I/dalvikvm-heap( 4325): Grow heap (frag case) to 16.658MB for 63974-byte allocation
,D/dalvikvm( 4325): GC_FOR_ALLOC freed 142K, 14% free 14917K/17288K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4325): Grow heap (frag case) to 16.691MB for 95956-byte allocation
,D/dalvikvm( 4325): GC_FOR_ALLOC freed 178K, 14% free 14951K/17384K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4325): Grow heap (frag case) to 16.770MB for 143930-byte allocation
,D/dalvikvm( 4325): GC_FOR_ALLOC freed 251K, 15% free 14998K/17528K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4325): Grow heap (frag case) to 16.885MB for 215890-byte allocation
,D/dalvikvm( 4325): GC_FOR_ALLOC freed 366K, 16% free 15072K/17740K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4325): Grow heap (frag case) to 17.060MB for 323830-byte allocation
,D/dalvikvm( 4325): GC_FOR_ALLOC freed 565K, 16% free 15193K/18060K, paused 27ms, total 28ms
,D/dalvikvm( 4325): GC_FOR_ALLOC freed 858K, 15% free 15369K/18060K, paused 28ms, total 29ms
,I/dalvikvm-heap( 4325): Grow heap (frag case) to 17.736MB for 728606-byte allocation
,D/dalvikvm( 4325): GC_FOR_ALLOC freed 1275K, 17% free 15625K/18772K, paused 28ms, total 29ms
,I/dalvikvm-heap( 4325): Grow heap (frag case) to 18.333MB for 1092904-byte allocation
,D/dalvikvm( 4325): GC_CONCURRENT freed 1878K, 20% free 16026K/19840K, paused 1ms+4ms, total 36ms
,D/dalvikvm( 4325): GC_FOR_ALLOC freed 89K, 20% free 16012K/19840K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4325): Grow heap (frag case) to 19.233MB for 1639352-byte allocation
,D/dalvikvm( 4325): GC_CONCURRENT freed 1948K, 23% free 16541K/21444K, paused 1ms+4ms, total 38ms
,D/dalvikvm( 4325): GC_FOR_ALLOC freed 1026K, 23% free 16518K/21444K, paused 29ms, total 30ms
,I/dalvikvm-heap( 4325): Grow heap (frag case) to 20.508MB for 2459024-byte allocation
,D/dalvikvm( 4325): GC_CONCURRENT freed 350K, 21% free 18875K/23848K, paused 5ms+3ms, total 37ms
,D/dalvikvm( 4325): GC_FOR_ALLOC freed 4129K, 27% free 17552K/23848K, paused 37ms, total 40ms
,I/dalvikvm-heap( 4325): Grow heap (frag case) to 22.691MB for 3688532-byte allocation
,D/dalvikvm( 4325): GC_CONCURRENT freed 265K, 23% free 21200K/27452K, paused 4ms+7ms, total 57ms
,D/dalvikvm( 4325): GC_FOR_ALLOC freed 4479K, 33% free 18666K/27452K, paused 34ms, total 34ms
,W/jxcore-log( 4325): Initializing JXcore engine
,W/jxcore-log( 4325): JXcore engine is ready
,D/dalvikvm( 4325): GC_CONCURRENT freed 404K, 22% free 21483K/27452K, paused 2ms+2ms, total 32ms
,D/dalvikvm( 4325): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/jxcore-log( 4325): Starting JXcore engine
,W/jxcore-log( 4325): Platform android
W/jxcore-log( 4325): 
,W/jxcore-log( 4325): Process ARCH arm
W/jxcore-log( 4325): 
,I/jxcore-log( 4325): JXcore Cordova bridge is ready!
I/jxcore-log( 4325): 
,W/jxcore-log( 4325): JXcore engine is started
,I/chromium( 4325): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4325): Toggling radios to true
I/jxcore-log( 4325): 
,D/BluetoothAdapter( 4325): enable(): BT is already enabled..!
D/WifiService( 1017): New client listening to asynchronous messages
D/WifiService( 1017): setWifiEnabled: true pid=4325, uid=10123
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1017): handleMessage: E msg.what=131145
D/WifiStateMachine( 1017): processMsg: ConnectedState
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
I/jxcore-log( 4325): Radios toggled
I/jxcore-log( 4325): 
I/jxcore-log( 4325): My device name is: motorola-XT1039
I/jxcore-log( 4325): 
,I/wpa_supplicant( 1184): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  274): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  274):  STA Disconnected !!
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,0,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
D/TCMD    (  485): NL - Read 1000 bytes from update socket.
D/TCMD    (  485): NL - message type is RTM_NEWLINK
D/TCMD    (  485): Listening for incoming client connection request
D/TCMD    (  485): NL - Read 1000 bytes from update socket.
D/TCMD    (  485): NL - message type is RTM_NEWLINK
D/TCMD    (  485): Listening for incoming client connection request
D/TCMD    (  485): NL - Read 68 bytes from update socket.
D/TCMD    (  485): NL - message type is RTM_NEWLINK
D/TCMD    (  485): Listening for incoming client connection request
D/TCMD    (  485): NL - Read 68 bytes from update socket.
D/TCMD    (  485): NL - message type is RTM_NEWLINK
D/TCMD    (  485): Listening for incoming client connection request
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
,I/MDMCTBK (  274): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
D/WifiStateMachine( 1017): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1017): invokeExitMethods: ConnectedState
,I/MDMCTBK (  274): send SAR ctrl over QMI
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1017): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1017): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1017): setSuspendOptimizationsNative: 1 true
,D/Tethering( 1017): InitialState.processMessage what=4
V/ConnectivityService( 1017): WiFi NOT Tethered!
,D/Tethering( 1017): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiP2pService( 1017): InactiveState{ when=-12ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): P2pEnabledState{ when=-12ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  271): Clearing all IP addresses on wlan0
D/TCMD    (  485): NL - Read 60 bytes from update socket.
D/TCMD    (  485): NL - ignore NL message, type = 21
,D/TCMD    (  485): Listening for incoming client connection request
,D/WifiStateMachine( 1017): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1017): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1017): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1017): connected time updated 291669
,D/ConnectivityService( 1017): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/SBar.NetworkController( 1091): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1017): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService( 1017): Attempting to switch to mobile
D/ConnectivityService( 1017): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1017): Attempting to switch to ETHERNET
,I/SBar.NetworkController( 1091): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,I/SBar.NetworkController( 1091): refreshSignalCluster: mobile: Signal=zz_moto_stat_sys_signal_emergency_only_wide Roaming=(none) mSimIconId=zz_moto_stat_sys_no_sim_wide Accessibility="Emergency calls only.","","No SIM card."
,I/SBar.NetworkController( 1091): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/ConnectivityService( 1017): resetConnections(wlan0, 3)
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1017): invokeEnterMethods: DisconnectingState
D/Checkin ( 1017): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1017): DisconnectingState
D/NetUtils( 1017): android_net_utils_resetConnections in env=0x6160bf70 clazz=0x64e00001 iface=wlan0 mask=0x3
,E/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=131146
D/WifiStateMachine( 1017): processMsg: DisconnectingState
,D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147460
D/WifiStateMachine( 1017): processMsg: DisconnectingState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): Network connection lost
D/WifiStateMachine( 1017): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1017): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 2143): Read error: ssl=0x62e290f8: I/O error during system call, Connection timed out
,V/NativeCrypto( 2143): SSL shutdown failed: ssl=0x62e290f8: I/O error during system call, Broken pipe
D/WifiP2pService( 1017): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  271): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1017): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1091): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1017): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1017): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1017): invokeEnterMethods: DisconnectedState
D/Checkin ( 1017): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131101
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiStateMachine( 1017): processMsg: DefaultState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131216
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiStateMachine( 1017): processMsg: DefaultState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131216
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiStateMachine( 1017): processMsg: DefaultState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): handleMessage: X
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=false
,I/ModemStatsDSDetect( 1300): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1017): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1300): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1300): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1017): Attempting to switch to mobile
D/ConnectivityService( 1017): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1017): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1017): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1300): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1300): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1300): onReceive() - done, currentInetCondition=0
,I/wpa_supplicant( 1184): wlan0: Trying to associate with SSID 'NG700'
,D/WifiStateMachine( 1017): handleMessage: E msg.what=147461
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  274): Event received = Trying to associate with
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1184): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/TCMD    (  485): NL - Read 56 bytes from update socket.
D/TCMD    (  485): NL - message type is RTM_NEWLINK
,D/TCMD    (  485): Listening for incoming client connection request
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): handleMessage: X
,I/wpa_supplicant( 1184): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1184): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  485): NL - Read 312 bytes from update socket.
D/TCMD    (  485): NL - message type is RTM_NEWLINK
D/TCMD    (  485): Listening for incoming client connection request
D/TCMD    (  485): NL - Read 192 bytes from update socket.
D/TCMD    (  485): NL - message type is RTM_NEWLINK
D/TCMD    (  485): Listening for incoming client connection request
D/TCMD    (  485): NL - Read 68 bytes from update socket.
D/TCMD    (  485): NL - message type is RTM_NEWLINK
D/TCMD    (  485): Listening for incoming client connection request
D/TCMD    (  485): NL - Read 1000 bytes from update socket.
D/TCMD    (  485): NL - message type is RTM_NEWLINK
D/TCMD    (  485): Listening for incoming client connection request
I/wpa_supplicant( 1184): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): handleMessage: X
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  274): Event received = Associated with c0:ff:d4
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): handleMessage: X
D/TCMD    (  485): NL - Read 80 bytes from update socket.
D/TCMD    (  485): NL - message type is RTM_NEWLINK
D/TCMD    (  485): Listening for incoming client connection request
D/TCMD    (  485): NL - Read 80 bytes from update socket.
D/TCMD    (  485): NL - message type is RTM_NEWLINK
D/TCMD    (  485): Listening for incoming client connection request
D/TCMD    (  485): NL - Read 68 bytes from update socket.
D/TCMD    (  485): NL - message type is RTM_NEWLINK
,D/TCMD    (  485): Listening for incoming client connection request
,D/Tethering( 1017): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1017): sendTetherStateChangedBroadcast 1, 0, 0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
I/wpa_supplicant( 1184): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1184): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  274): Event received = WPA: Key negotiation com
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  274): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  274):  STA Connected !!
D/TCMD    (  485): NL - Read 1000 bytes from update socket.
D/TCMD    (  485): NL - message type is RTM_NEWLINK
D/TCMD    (  485): Listening for incoming client connection request
D/WifiStateMachine( 1017): processMsg: ConnectModeState
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
,I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
D/WifiStateMachine( 1017): handleMessage: X
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
I/MDMCTBK (  274): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1208014000
I/MDMCTBK (  274): return from set_get_from_wpa_supplicant
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
,I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
D/WifiStateMachine( 1017): handleMessage: E msg.what=147459
,D/WifiStateMachine( 1017): processMsg: DisconnectedState
I/MDMCTBK (  274): send SAR ctrl over QMI
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/MDMCTBK (  274): wifi_set_tx_pwr: SETTXPOWER = 19
D/WifiStateMachine( 1017): Network connection established
,D/WifiStateMachine( 1017): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
E/MDMCTBK (  274): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  274): , reply_len: 3, ret: 0
E/MDMCTBK (  274): MdmCutbackHndler, resp=OK
E/MDMCTBK (  274): 
,D/MDMCTBK (  274): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1017): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1017): invokeExitMethods: DisconnectedState
,I/SBar.NetworkController( 1091): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1017): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
,D/WifiStateMachine( 1017): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1017): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1017): processMsg: ObtainingIpState
D/WifiStateMachine( 1017): ObtainingIpState{ when=-35ms what=147462 obj=android.net.wifi.StateChangeResult@437de1e8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=131101
D/WifiStateMachine( 1017): processMsg: ObtainingIpState
D/WifiStateMachine( 1017): ObtainingIpState{ when=-30ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@44801988 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiStateMachine( 1017): processMsg: DefaultState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=196612
D/WifiStateMachine( 1017): processMsg: ObtainingIpState
D/WifiStateMachine( 1017): ObtainingIpState{ when=-6ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,D/WifiStateMachine( 1017): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1017): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1017): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42925018 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42925018 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): handleMessage: X
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 c
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 c
D/WifiStateMachine( 1017): handleMessage: E msg.what=147461
D/WifiStateMachine( 1017): processMsg: ObtainingIpState
D/WifiStateMachine( 1017): ObtainingIpState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 3
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 3
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 c2
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 c2
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 38
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 38
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
,D/WifiP2pService( 1017): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/TCMD    (  485): NL - Read 56 bytes from update socket.
D/TCMD    (  485): NL - message type is RTM_NEWLINK
D/TCMD    (  485): Listening for incoming client connection request
,D/WifiStateMachine( 1017): handleMessage: X
D/WifiP2pService( 1017): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  485): NL - Read 60 bytes from update socket.
D/TCMD    (  485): NL - ignore NL message, type = 20
,D/TCMD    (  485): Listening for incoming client connection request
,D/WifiStateMachine( 1017): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1017): handleMessage: E msg.what=131215
D/WifiStateMachine( 1017): processMsg: ObtainingIpState
D/WifiStateMachine( 1017): ObtainingIpState{ when=-4ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiStateMachine( 1017): processMsg: DefaultState
,D/WifiStateMachine( 1017): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1017): processMsg: ObtainingIpState
D/WifiStateMachine( 1017): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,D/WifiStateMachine( 1017): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1017): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): DHCP successful
D/WifiStateMachine( 1017): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1017): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1017): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1017): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1017): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1017): VerifyingLinkState enter
D/WifiStateMachine( 1017): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1091): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=151572
D/WifiStateMachine( 1017): processMsg: VerifyingLinkState
D/WifiStateMachine( 1017): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,D/Tethering( 1017): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1017): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1595): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1017): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
W/XTWiFiOS( 1279): No entry in secure settings for enhanced location services: false
W/XTWiFiOS( 1279): Active network info is not available
I/SBar.NetworkController( 1091): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1091): updateConnectivity: NetworkInfo: null, inetCondition= 0
,I/ActivityManager( 1017): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4441 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1091): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1091): updateConnectivity: NetworkInfo: null, inetCondition= 0
,E/ActivityThread( 1595): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1595): Registering with Alarm Manager to restart CCE
I/SBar.NetworkController( 1091): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
D/PollingManager( 1595): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1595): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1595): Failed to find provider info for com.motorola.blur.setupprovider
W/XTWiFiOS( 1279): No entry in secure settings for enhanced location services: false
D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=135190
D/WifiStateMachine( 1017): processMsg: VerifyingLinkState
D/WifiStateMachine( 1017): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1017): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
W/XTWiFiOS( 1279): Active network info is not available
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1017): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1017): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1017): CaptivePortalCheckState enter
D/WifiStateMachine( 1017): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
I/SBar.NetworkController( 1091): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/OtaApp  ( 1595): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WifiStateMachine( 1017): handleMessage: X
D/OtaApp  ( 1595): [debug] > CusSM.onRadioDown
D/Tethering( 1017): MasterInitialState.processMessage what=3
,D/ConnectivityService( 1017): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/CaptivePortalTracker( 1017): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1017): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1017): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine( 1017): handleMessage: E msg.what=131092
D/WifiStateMachine( 1017): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1017): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,D/ConnectivityService( 1017): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine( 1017): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
I/SBar.NetworkController( 1091): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1091): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/ConnectivityService( 1017): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1017): WiFi NOT Tethered!
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
D/WifiStateMachine( 1017): handleMessage: X
,D/Checkin ( 1017): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/ConnectivityService( 1017): Unexpected mtu value: android.net.wifi.WifiStateTracker@4205b1b8
D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=true
,I/ModemStatsDSDetect( 1300): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityService( 1017): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1017): WiFi NOT Tethered!
I/ModemStatsDSDetect( 1300): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1300): onReceive() - done, currentInetCondition=0
,E/ConnectivityService( 1017): Unexpected mtu value: android.net.wifi.WifiStateTracker@4205b1b8
I/SBar.NetworkController( 1091): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1091): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService( 1017): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1300): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1300): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1300): onReceive() - done, currentInetCondition=0
,D/dalvikvm( 4441): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f80d10, skipping init
I/openssl ( 4441): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4441): Crypto mode 0 already enabled
,I/ActivityManager( 1017): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4472 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1017): Killing 3105:com.android.providers.calendar/u0a8 (adj 15): empty #9
,W/ContextImpl( 1268): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4472): mnc/mcc: 
V/MmsConfig( 4472): tag: bool value: enabledMMS - true
,V/MmsConfig( 4472): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4472): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4472): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4472): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4472): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4472): tag: int value: minMessageCountPerThread - 10
,V/MmsConfig( 4472): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4472): tag: int value: recipientLimit - 20
V/MmsConfig( 4472): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4472): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4472): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4472): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4472): tag: int value: maxSubjectLength - 80
,V/MmsConfig( 4472): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4472): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4472): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4472): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1017): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4490 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1017): Killing 4138:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1268): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4490): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4490): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4490): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4490): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1017): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4503 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1017): Killing 4180:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1268): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  276): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 22ms
,I/CheckinService( 1689): Checkin interval check for package: unspecified last checkin: 1453132476831 min interval config: 0 actual interval: 287072
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 21ms
,I/CheckinService( 1689): Checking schedule, now: 1453132763919 next: 1453132506811
,I/CheckinService( 1689): active receiver: enabled
,I/CheckinService( 1689): Preparing to send checkin request
,I/EventLogService( 1689): Accumulating logs since 1453132472364
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 18ms
,V/WebViewChromiumFactoryProvider( 4503): Binding Chromium to main looper Looper (main, tid 1) {41f7ccd8}
,I/LibraryLoader( 4503): Expected native library version number "",actual native library version number ""
,I/chromium( 4503): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4503): Initializing chromium process, renderers=0
,I/CheckinRequestBuilder( 1689): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1689): Failed to find provider info for com.google.android.wearable.settings
,E/AudioManagerAndroid( 4503): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4503): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4503): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4503): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4503): Local Branch: 
I/Adreno-EGL( 4503): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4503): Local Patches: NONE
I/Adreno-EGL( 4503): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4503): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4503): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/dalvikvm( 1017): GC_EXPLICIT freed 25339K, 65% free 18836K/53800K, paused 5ms+12ms, total 178ms
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
W/Vold    (  262): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4503): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/dalvikvm( 2143): GC_EXPLICIT freed 1580K, 39% free 10601K/17224K, paused 2ms+5ms, total 47ms
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1017): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4545 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
I/NSApplication( 4503): Starting up...
,I/ActivityManager( 1017): Killing 3936:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1268): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1017): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=4558 uid=10056 gids={50056, 3003, 1028, 1015}
W/dalvikvm( 4545): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
D/dalvikvm( 4545): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4545): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4545): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4545): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4545): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4545): install
I/MultiDex( 4545): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
I/MultiDex( 4545): loading existing secondary dex files
,I/MultiDex( 4545): load found 3 secondary dex files
,I/MultiDex( 4545): install done
,D/dalvikvm( 4545): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4545): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4545): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4545): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4545): VFY: unable to resolve instance field 36
,D/dalvikvm( 4545): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 4545): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4545): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4545): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4545): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4545): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4545): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f77550
,D/dalvikvm( 4545): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f77550
,D/dalvikvm( 4545): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f77550, skipping init
,D/dalvikvm( 4545): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f77550
D/dalvikvm( 4545): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f77550
,V/JNIHelp ( 4545): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4558): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 4558): VFY: unable to resolve instance field 68
,D/dalvikvm( 4558): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 4558): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4558): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 4558): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 4558): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/dalvikvm( 4558): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 4558): VFY: unable to resolve instance field 68
,D/dalvikvm( 4558): VFY: replacing opcode 0x54 at 0x0011
,D/DEBUG   ( 1595): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/dalvikvm( 4558): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4558): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4558): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4558): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4558): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4558): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,W/ContextImpl( 1595): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
I/ActivityManager( 1017): Killing 4218:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1268): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/GetNotificationsWS( 1595): bindWebServices(): registering our AIDL callback...
D/EmailService.MarketingOptInSetter( 1595): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1595): onServiceConnected()
D/GetNotificationsWS( 1595): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1595): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1595): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1595): unbindWebServices(): un-registering our AIDL callback...
,I/openssl ( 4441): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4441): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4490): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4490): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 4545): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f77550
,D/dalvikvm( 4545): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f77550
D/dalvikvm( 4545): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f77550
,D/dalvikvm( 4545): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f77550
,I/ProviderInstaller( 4545): Installed default security provider GmsCore_OpenSSL
,D/ConnectivityService( 1017): NetTransition Wakelock for ConnectedState released by timeout
,D/WearableService( 1224): callingUid 10022, callindPid: 1224
,E/MDM     ( 1224): [70] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1689): Restart initialization of location
D/AuthorizationBluetoothService( 2143): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 2143): Proximity feature is not enabled.
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1224): No location to return for getLastLocation()
,W/FusedLocationProvider( 1224): location=null
I/dalvikvm( 4545): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4545): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
D/dalvikvm( 4545): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4545): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4545): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4545): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4545): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4545): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4545): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4545): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4545): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4545): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4545): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4545): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4545): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4545): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4545): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,I/jxcore-log( 4325): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4325): 
,D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  278): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
,D/DrmWidevineDash(  278): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  278): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5212000
,E/DrmWidevineDash(  278): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5212000
,D/DrmWidevineDash(  278): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  278): OEMCrypto_APIVersion = 8
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
,I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=3089900840
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4545): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 4545): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421c7700
D/dalvikvm( 4545): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421c7700
,D/dalvikvm( 4545): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x421c7700, skipping init
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4545): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4590): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4545): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4545): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 80ms
,I/Adreno-EGL( 4545): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4545): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4545): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4545): Local Branch: 
I/Adreno-EGL( 4545): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4545): Local Patches: NONE
I/Adreno-EGL( 4545): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4545): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4545): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4545): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4545): Local Branch: 
I/Adreno-EGL( 4545): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4545): Local Patches: NONE
I/Adreno-EGL( 4545): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/jxcore-log( 4325): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4325): 
,I/jxcore-log( 4325): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4325): 
,V/AlarmManager( 1017): sending alarm Alarm{43f3faf0 type 2 com.google.android.gms}
,I/jxcore-log( 4325): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4325): 
,I/jxcore-log( 4325): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4325): 
,I/jxcore-log( 4325): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4325): 
,I/jxcore-log( 4325): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4325): 
,W/Settings( 4545): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
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
D/WVCdm   (  278): PrepareKeyRequest: nonce=3560689684
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,I/Adreno-EGL( 4545): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4545): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4545): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4545): Local Branch: 
I/Adreno-EGL( 4545): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4545): Local Patches: NONE
I/Adreno-EGL( 4545): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4545): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4545): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4545): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4545): Local Branch: 
I/Adreno-EGL( 4545): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4545): Local Patches: NONE
I/Adreno-EGL( 4545): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/jxcore-log( 4325): Test app app.js loaded
I/jxcore-log( 4325): 
,D/ConnectivityService( 1017): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1300): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1300): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1091): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1300): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1300): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1091): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1091): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/dalvikvm( 4325): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4325): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 4325): VFY: replacing opcode 0x6e at 0x0002
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4325): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 4325): BLE advertisement is supported
I/jxcore-log( 4325): 
I/Choreographer( 4325): Skipped 361 frames!  The application may be doing too much work on its main thread.
I/chromium( 4325): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/CheckinRequestBuilder( 1689): Classify the device as Phone.
,W/ProcessCpuTracker( 1017): Skipping unknown process pid 4446
,W/ProcessCpuTracker( 1017): Skipping unknown process pid 4447
,W/ProcessCpuTracker( 1017): Skipping unknown process pid 4457
,W/ProcessCpuTracker( 1017): Skipping unknown process pid 4471
,W/ProcessCpuTracker( 1017): Skipping unknown process pid 4606
,W/ProcessCpuTracker( 1017): Skipping unknown process pid 4609
,D/Tethering( 1017): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1091): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1091): the netConditon of netType 1 is updated as 0 by android.net.conn.CONNECTIVITY_CHANGE,icon color should be white.
,I/SBar.NetworkController( 1091): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/CaptivePortalTracker( 1017): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1279): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1595): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,W/XTWiFiOS( 1279): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1091): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1091): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,D/PollingManager( 1595): now: 343018 ,futureTime: 40566481
,D/PollingManager( 1595): Polling alarm set to expire at: 40566481 Current Time: 343020
,E/ActivityThread( 1595): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1595): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,D/CaptivePortalTracker( 1017): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering( 1017): MasterInitialState.processMessage what=3
,D/PollingManager( 1595): now: 343040 ,futureTime: 40566481
,D/PollingManager( 1595): Polling alarm set to expire at: 40566481 Current Time: 343042
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,I/openssl ( 4441): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4441): Crypto mode 0 already enabled
,E/ActivityThread( 1595): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1595): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1595): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1595): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/OtaApp  ( 1595): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/MobileConnectivityChangeReceiver( 4490): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4490): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1595): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1595): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 1595): publish the event [tag = MOT_OTA event name = LOG]
,I/CheckinService( 1689): Checkin interval check for package: unspecified last checkin: 1453132476831 min interval config: 0 actual interval: 289929
,D/OtaApp  ( 1595): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1595): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,D/OtaApp  ( 1595): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
I/jxcore-log( 4325): --= Surplus to requirements =--
I/jxcore-log( 4325): 
,I/jxcore-log( 4325): ****TEST TOOK:  ms ****
I/jxcore-log( 4325): 
,I/jxcore-log( 4325): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4325): 
,D/OtaApp  ( 1595): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1595): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1595): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/openssl ( 4441): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4441): Crypto mode 0 already enabled
,D/OtaApp  ( 1595): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1595): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 1595): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1595): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1595): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,D/OtaApp  ( 1595): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/MobileConnectivityChangeReceiver( 4490): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4490): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1595): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/CheckinService( 1689): Checkin interval check for package: unspecified last checkin: 1453132476831 min interval config: 0 actual interval: 289995
,D/dalvikvm( 1689): GC_CONCURRENT freed 1902K, 29% free 12327K/17224K, paused 4ms+5ms, total 73ms
,D/dalvikvm( 1689): WAIT_FOR_CONCURRENT_GC blocked 16ms
D/dalvikvm( 1689): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/CheckinTask( 1689): Sending checkin request (11753 bytes)
,D/DEBUG   ( 1595): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1595): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1595): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1595): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/EmailService.MarketingOptInSetter( 1595): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1595): onServiceConnected()
,D/GetNotificationsWS( 1595): onServiceConnected(): Registered for remote service callbacks...
,D/DEBUG   ( 1595): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1595): ServiceHandler.handleMessage: mWaitCount=0
D/EmailService.MarketingOptInSetter( 1595): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1595): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1595): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1595): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 1595): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1017): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from pid 1595
,W/ContextImpl( 1268): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1595): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1268): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1595): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1595): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1595): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm( 1595): GC_CONCURRENT freed 2102K, 38% free 10680K/17224K, paused 6ms+6ms, total 50ms
,D/OtaApp  ( 1595): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1595): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1595): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1595): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1595): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1595): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1595): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1595): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1595): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1595): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1595): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1595): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 1595): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1017): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from pid 1595
W/ContextImpl( 1268): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1268): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1595): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 1595): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 1595): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1595): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 1595): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 1595): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1595): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1595): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1595): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1595): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1595): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1595): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1595): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1595): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/Keyboard.Facilitator( 1206): onFinishInput()
,W/IInputConnectionWrapper( 4325): showStatusIcon on inactive InputConnection
,I/ActivityManager( 1017): Activity reported stop, but no longer stopping: ActivityRecord{429981b0 u0 com.motorola.ccc.ota/.ui.DownloadActivity t2}
,I/LaunchCheckinHandler( 1017): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,183
,D/AndroidRuntime( 4639): 
D/AndroidRuntime( 4639): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4639): CheckJNI is OFF
,D/dalvikvm( 4639): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4639): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4639): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4639): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4639): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4639): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,D/ConnectivityService( 1017): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/ModemStatsDSDetect( 1300): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1091): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1091): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/ModemStatsDSDetect( 1300): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1091): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1300): onReceive() - done, currentInetCondition=100
,E/memtrack( 4639): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4639): failed to load memtrack module: -2
,D/AndroidRuntime( 4639): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10123 user=-1: uninstall pkg
,I/ActivityManager( 1017): Killing 4325:com.test.thalitest/u0a123 (adj 9): stop com.test.thalitest
W/ContextImpl( 1268): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1017):   Force finishing activity ActivityRecord{447d5b88 u0 com.test.thalitest/.MainActivity t3}
,I/WindowState( 1017): WIN DEATH: Window{447c5e00 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1017): Client connection lost with reason: 4
,I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10123 user=0: pkg removed
I/CheckinRequestBuilder( 1689): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1689): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 2297): GC_EXPLICIT freed 6152K, 44% free 9758K/17224K, paused 2ms+5ms, total 42ms
,D/dalvikvm( 2330): GC_EXPLICIT freed 3033K, 42% free 10050K/17224K, paused 10ms+4ms, total 78ms
,W/GeofencerStateMachine( 1224): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1206): resetDictionaries() : en_GB
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1206): run()
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "sms"
I/Decoder ( 1206): createOrResetDecoder
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
D/dalvikvm( 1309): GC_EXPLICIT freed 3252K, 33% free 11596K/17224K, paused 4ms+6ms, total 125ms
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mms"
,I/Launcher( 1309): Deferring update until onResume
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mmsto"
,D/VoicemailCleanupService( 1189): Cleaning up data for package: com.test.thalitest
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "sms"
,I/ActivityManager( 1017): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4676 uid=10033 gids={50033, 3003, 1028, 1015}
,D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 1017): removePackageParticipantsLocked: uid=10123 #1
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mms"
,I/ConfigService( 1224): onCreate
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mmsto"
,I/Launcher( 1309): Deferring update until onResume
,I/InternalIcingCorporaPro( 2330): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/dalvikvm( 1017): GC_EXPLICIT freed 1675K, 65% free 18856K/53800K, paused 71ms+14ms, total 293ms
I/ActivityManager( 1017): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4694 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/ActivityManager( 1017): Killing 4250:com.quickoffice.android/u0a95 (adj 15): empty #9
W/ContextImpl( 1268): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1206): run()
,D/AndroidRuntime( 4639): Shutting down VM
,D/dalvikvm( 4639): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+1ms, total 3ms
,W/ContextImpl( 4694): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,I/dalvikvm( 3841): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3841): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3841): VFY: replacing opcode 0x6e at 0x0013
,D/PackageBroadcastService( 1689): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1689): Clearing selected account for com.test.thalitest
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1206): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1.apk (offset=5018356, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/LocationSettingsChecker( 1689): Removing dialog suppression flag for package com.test.thalitest
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1206): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1206): run() : Loading LM = contacts
,D/ChimeraCfgMgr( 1689): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1689): Module APK com.google.android.play.games already loaded
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1206): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1206): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1206): run() : Loaded File = UserHistory.en_GB.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1206): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1206): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1206): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1206): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1206): run()
I/StatsUtilsManager( 1206): startPeriodStatsRecorder() : Success
,I/PeriodicStatsRecorder( 1206): shouldRecordStats() = Too Soon
,D/ChimeraCfgMgr( 1689): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1689): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 2143): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 2143): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager( 1017): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4718 uid=10059 gids={50059, 1028, 3003, 1015}
,D/gH_CompatibleDatabase( 1689): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1689): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1689): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 1689): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1689): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1689): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1689): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1689): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1689): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1689): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1689): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1689): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1689): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,D/WifiStateMachine( 1017): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1017): handleMessage: E msg.what=131215
D/WifiStateMachine( 1017): processMsg: ConnectedState
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
,D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1017): processMsg: DefaultState
,D/WifiStateMachine( 1017): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,I/CheckinRequestBuilder( 1689): Classify the device as Phone.
,D/WifiStateMachine( 1017): handleMessage: X
D/ConnectivityService( 1017): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1017):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=true
D/ConnectivityService( 1017): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=true
I/Icing   ( 1689): doRemovePackageData com.test.thalitest
I/InternalIcingCorporaPro( 2330): UpdateCorporaTask done [took 198 ms] updated apps [took 198 ms] 
,I/CheckinTask( 1689): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1689): Checking schedule, now: 1453132768064 next: 1453682422056
,I/CheckinService( 1689): active receiver: disabled
I/ActivityManager( 1017): Killing 4441:android.process.media/u0a18 (adj 15): empty #9
W/ContextImpl( 1268): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1689): Checking schedule, now: 1453132768082 next: 1453682422056
,I/CheckinService( 1689): active receiver: disabled
,D/CheckinService( 1689): Recording last checkin time for package unspecified as 1453132768086
,I/dalvikvm( 4718): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method gqa.a
W/dalvikvm( 4718): VFY: unable to resolve virtual method 1798: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4718): VFY: replacing opcode 0x6e at 0x000f
,I/GAv4    ( 4718): Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4718):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4718):   adb logcat -s GAv4
,W/GAv4    ( 4718): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/dalvikvm( 4718): Could not find method android.content.Context.checkSelfPermission, referenced from method asa.a
W/dalvikvm( 4718): VFY: unable to resolve virtual method 1616: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4718): VFY: replacing opcode 0x6e at 0x001b
,E/SQLiteDatabase( 4718): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4718): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4718): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4718): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4718): 	at avm.getWritableDatabase(PG:244)
E/SQLiteDatabase( 4718): 	at avc.a(PG:1573)
E/SQLiteDatabase( 4718): 	at jep$b.a(PG:131)
E/SQLiteDatabase( 4718): 	at ave.run(PG:588)
,W/dalvikvm( 4718): threadid=11: thread exiting with uncaught exception (group=0x416a7d40)
I/dalvikvm( 4718): Could not find method android.app.Activity.finishAfterTransition, referenced from method ce.onBackPressed
W/dalvikvm( 4718): VFY: unable to resolve virtual method 1245: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 4718): VFY: replacing opcode 0x6e at 0x0012
E/SharedPreferencesImpl( 4718): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4718): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4718): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4718): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4718): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 4718): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4718): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4718): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4718): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4718): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4718): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4718): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4718): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/CAKEMIX_CRASHED( 4718): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/CAKEMIX_CRASHED( 4718): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4718): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/CAKEMIX_CRASHED( 4718): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/CAKEMIX_CRASHED( 4718): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/CAKEMIX_CRASHED( 4718): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/CAKEMIX_CRASHED( 4718): 	at avm.getWritableDatabase(PG:244)
E/CAKEMIX_CRASHED( 4718): 	at avc.a(PG:1573)
E/CAKEMIX_CRASHED( 4718): 	at jep$b.a(PG:131)
E/CAKEMIX_CRASHED( 4718): 	at ave.run(PG:588)
E/SQLiteDatabase( 4718): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4718): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4718): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4718): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4718): 	at gjj$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4718): 	at gjj.l(Unknown Source)
E/SQLiteDatabase( 4718): 	at gjj.a(Unknown Source)
E/SQLiteDatabase( 4718): 	at gjj.e(Unknown Source)
E/SQLiteDatabase( 4718): 	at gjl.b(Unknown Source)
E/SQLiteDatabase( 4718): 	at gjo.run(Unknown Source)
E/SQLiteDatabase( 4718): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4718): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4718): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4718): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4718): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 4718): 	at hzg$c.run(Unknown Source)
E/GAv4    ( 4718): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4718): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4718): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4718): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4718): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4718): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4718): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4718): 	at gjj$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4718): 	at gjj.l(Unknown Source)
E/SQLiteDatabase( 4718): 	at gjj.a(Unknown Source)
E/SQLiteDatabase( 4718): 	at gjj.e(Unknown Source)
E/SQLiteDatabase( 4718): 	at gjl.b(Unknown Source)
E/SQLiteDatabase( 4718): 	at gjo.run(Unknown Source)
E/SQLiteDatabase( 4718): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4718): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4718): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4718): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4718): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 4718): 	at hzg$c.run(Unknown Source)
E/GAv4    ( 4718): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/GAv4    ( 4718): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4718): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4718): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4718): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4718): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4718): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.474.23.34, sample rate 1.0
I/dalvikvm( 4718): Could not find method android.provider.DocumentsContract.getTreeDocumentId, referenced from method edw.a
W/dalvikvm( 4718): VFY: unable to resolve static method 2986: Landroid/provider/DocumentsContract;.getTreeDocumentId (Landroid/net/Uri;)Ljava/lang/String;
,D/dalvikvm( 4718): VFY: replacing opcode 0x71 at 0x0075
W/FileUtils( 4718): Failed to chmod(/data/data/com.google.android.apps.docs/app_filecache2): libcore.io.ErrnoException: chmod failed: ENOENT (No such file or directory)
I/ActivityManager( 1017): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from pid 4718
W/WindowManager( 1017): Not okToDisplay, so not showing Starting Window
W/ContextImpl( 1268): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/Process ( 4718): Sending signal. PID: 4718 SIG: 9
W/ContextImpl( 1268): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
E/SQLiteLog( 2297): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
E/SQLiteDatabase( 2297): Error inserting state=component=com.google.android.apps.docs/.app.ErrorNotificationActivity event=am_restart_activity timestamp=1453132768277 timezone=3600 name=PauseResumeTrigger
E/SQLiteDatabase( 2297): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2297): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2297): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2297): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2297): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2297): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2297): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2297): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2297): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2297): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2297): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2297): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2297): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2297): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2297): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2297): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 2297): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
E/SQLiteDatabase( 2297): Error inserting state=component=com.google.android.apps.docs/.app.ErrorNotificationActivity event=am_pause_activity timestamp=1453132768279 timezone=3600 name=PauseResumeTrigger
E/SQLiteDatabase( 2297): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2297): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2297): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2297): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2297): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2297): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2297): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2297): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2297): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2297): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2297): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2297): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2297): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2297): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2297): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2297): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager( 1017): Process com.google.android.apps.docs (pid 4718) has died.
W/WindowManager( 1017): Not okToDisplay, so not showing Starting Window
,I/ActivityManager( 1017): Start proc com.google.android.apps.docs for activity com.google.android.apps.docs/.app.ErrorNotificationActivity: pid=4755 uid=10059 gids={50059, 1028, 3003, 1015}

```
