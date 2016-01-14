#### Test 55613145b105d0b_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4391): 
D/AndroidRuntime( 4391): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4391): CheckJNI is OFF
D/dalvikvm( 4391): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4391): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4391): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4391): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4391): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4391): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4391): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4391): failed to load memtrack module: -2
D/AndroidRuntime( 4391): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1021): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4391
W/WindowManager( 1021): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1021): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4408 uid=10109 gids={50109, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4391): Shutting down VM
D/dalvikvm( 4391): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1270): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1270): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4408): Binding Chromium to main looper Looper (main, tid 1) {424749d8}
I/LibraryLoader( 4408): Expected native library version number "",actual native library version number ""
I/chromium( 4408): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4408): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1021): Message: 20
D/BluetoothManagerService( 1021): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43caab78:true
I/Adreno-EGL( 4408): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4408): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4408): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4408): Local Branch: 
I/Adreno-EGL( 4408): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4408): Local Patches: NONE
I/Adreno-EGL( 4408): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4408): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 4408): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 4408): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4408): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4408): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4408): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 4408): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 4408): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 4408): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4408): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4408): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 4408): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 4408): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4408): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4408): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 4408): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4408): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4408): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 4408): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4408): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4408): Enabling debug mode 0
,W/AwContents( 4408): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1210): onFinishInput()
,W/IInputConnectionWrapper( 4408): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1021): Displayed com.test.thalitest/.MainActivity,cp,ca,455
I/ActivityManager( 1021): Displayed com.test.thalitest/.MainActivity: +427ms (total +455ms)
,D/JsMessageQueue( 4408): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4408): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4247b168
,D/dalvikvm( 4408): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4247b168
,D/jxcore_app_log( 4408): JniHelper::setJavaVM(0x41b92f78), pthread_self() = 1614064448
,D/JX-Cordova( 4408): jxcore cordova android initializing
,D/dalvikvm( 4408): GC_CONCURRENT freed 2770K, 17% free 14397K/17224K, paused 2ms+2ms, total 66ms
,D/dalvikvm( 4408): WAIT_FOR_CONCURRENT_GC blocked 34ms
,D/dalvikvm( 4408): GC_FOR_ALLOC freed 178K, 17% free 14404K/17224K, paused 25ms, total 25ms
,D/dalvikvm( 4408): GC_FOR_ALLOC freed 117K, 17% free 14433K/17224K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4408): Grow heap (frag case) to 16.218MB for 95956-byte allocation
,D/dalvikvm( 4408): GC_FOR_ALLOC freed 194K, 17% free 14453K/17320K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4408): Grow heap (frag case) to 16.284MB for 143930-byte allocation
,D/dalvikvm( 4408): GC_FOR_ALLOC freed 254K, 17% free 14500K/17464K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4408): Grow heap (frag case) to 16.398MB for 215890-byte allocation
,D/dalvikvm( 4408): GC_FOR_ALLOC freed 368K, 18% free 14574K/17676K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4408): Grow heap (frag case) to 16.574MB for 323830-byte allocation
,D/dalvikvm( 4408): GC_FOR_ALLOC freed 567K, 19% free 14695K/17996K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4408): Grow heap (frag case) to 16.846MB for 485740-byte allocation
,D/dalvikvm( 4408): GC_FOR_ALLOC freed 865K, 20% free 14871K/18472K, paused 26ms, total 27ms
,D/dalvikvm( 4408): GC_FOR_ALLOC freed 1282K, 19% free 15126K/18472K, paused 27ms, total 28ms
,I/dalvikvm-heap( 4408): Grow heap (frag case) to 17.846MB for 1092904-byte allocation
,D/dalvikvm( 4408): GC_CONCURRENT freed 1852K, 21% free 15527K/19540K, paused 3ms+8ms, total 53ms
,D/dalvikvm( 4408): GC_FOR_ALLOC freed 215K, 22% free 15430K/19540K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4408): Grow heap (frag case) to 18.665MB for 1639352-byte allocation
,D/dalvikvm( 4408): GC_CONCURRENT freed 1600K, 25% free 16022K/21144K, paused 2ms+3ms, total 36ms
,D/dalvikvm( 4408): GC_FOR_ALLOC freed 1393K, 24% free 16090K/21144K, paused 31ms, total 31ms
,I/dalvikvm-heap( 4408): Grow heap (frag case) to 20.090MB for 2459024-byte allocation
,D/dalvikvm( 4408): GC_CONCURRENT freed 381K, 22% free 18407K/23548K, paused 5ms+7ms, total 62ms
,V/AlarmManager( 1021): sending alarm Alarm{446b83a0 type 3 android}
,D/dalvikvm( 4408): GC_FOR_ALLOC freed 4276K, 28% free 17070K/23548K, paused 36ms, total 36ms
,I/dalvikvm-heap( 4408): Grow heap (frag case) to 22.219MB for 3688532-byte allocation
,D/dalvikvm( 4408): GC_CONCURRENT freed 511K, 25% free 20621K/27152K, paused 5ms+8ms, total 98ms
,D/dalvikvm( 4408): GC_FOR_ALLOC freed 3127K, 34% free 18005K/27152K, paused 29ms, total 29ms
,W/jxcore-log( 4408): Initializing JXcore engine
,W/jxcore-log( 4408): JXcore engine is ready
,D/dalvikvm( 4408): GC_CONCURRENT freed 354K, 24% free 20646K/27152K, paused 1ms+2ms, total 30ms
,D/dalvikvm( 4408): WAIT_FOR_CONCURRENT_GC blocked 27ms
,W/jxcore-log( 4408): Starting JXcore engine
,W/jxcore-log( 4408): Platform android
W/jxcore-log( 4408): 
,W/jxcore-log( 4408): Process ARCH arm
W/jxcore-log( 4408): 
,I/jxcore-log( 4408): JXcore Cordova bridge is ready!
I/jxcore-log( 4408): 
,W/jxcore-log( 4408): JXcore engine is started
,I/chromium( 4408): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4408): Toggling radios to true
I/jxcore-log( 4408): 
,D/BluetoothAdapter( 4408): enable(): BT is already enabled..!
D/WifiService( 1021): New client listening to asynchronous messages
D/WifiService( 1021): setWifiEnabled: true pid=4408, uid=10109
,E/WifiService( 1021): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1021): handleMessage: E msg.what=131145
D/WifiStateMachine( 1021): processMsg: ConnectedState
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
I/jxcore-log( 4408): Radios toggled
I/jxcore-log( 4408): 
I/jxcore-log( 4408): My device name is: motorola-XT1039
I/jxcore-log( 4408): 
,D/TCMD    (  472): NL - Read 1000 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
I/wpa_supplicant( 1163): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  275): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  275):  STA Disconnected !!
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,0,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  275): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
D/Tethering( 1021): InitialState.processMessage what=4
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
I/MDMCTBK (  275): send SAR ctrl over QMI
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,V/ConnectivityService( 1021): WiFi NOT Tethered!
D/Tethering( 1021): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiStateMachine( 1021): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1021): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1021): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1021): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1021): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  273): Clearing all IP addresses on wlan0
D/TCMD    (  472): NL - Read 60 bytes from update socket.
D/TCMD    (  472): NL - ignore NL message, type = 21
,D/TCMD    (  472): Listening for incoming client connection request
,D/WifiStateMachine( 1021): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1021): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1021): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1021): connected time updated 295318
D/ConnectivityService( 1021): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1021): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1095): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1095): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=4
D/ConnectivityService( 1021): Attempting to switch to mobile
D/ConnectivityService( 1021): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1021): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1095): refreshSignalCluster: mobile: Signal=zz_moto_stat_sys_signal_emergency_only_wide Roaming=(none) mSimIconId=zz_moto_stat_sys_no_sim_wide Accessibility="Emergency calls only.","","No SIM card."
I/SBar.NetworkController( 1095): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1021): invokeEnterMethods: DisconnectingState
D/WifiStateMachine( 1021): DisconnectingState
E/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/Checkin ( 1021): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131146
D/WifiStateMachine( 1021): processMsg: DisconnectingState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131101
D/WifiStateMachine( 1021): processMsg: DisconnectingState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147460
D/WifiStateMachine( 1021): processMsg: DisconnectingState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): Network connection lost
D/WifiStateMachine( 1021): Stopping DHCP and clearing IP
D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1021): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 1021): resetConnections(wlan0, 3)
D/NetUtils( 1021): android_net_utils_resetConnections in env=0x615cc3d0 clazz=0x64700001 iface=wlan0 mask=0x3
,V/NativeCrypto( 2162): Read error: ssl=0x63116ff0: I/O error during system call, Connection timed out
,V/NativeCrypto( 2162): SSL shutdown failed: ssl=0x63116ff0: I/O error during system call, Broken pipe
,E/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  273): Clearing all IP addresses on wlan0
,D/WifiStateMachine( 1021): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/SBar.NetworkController( 1095): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1021): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1021): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine( 1021): invokeEnterMethods: DisconnectedState
,D/Checkin ( 1021): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131216
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131216
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=false
I/ModemStatsDSDetect( 1301): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1301): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1301): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1021): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1021): Attempting to switch to mobile
D/ConnectivityService( 1021): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1021): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=false
I/ModemStatsDSDetect( 1301): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1301): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1301): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 38
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 4 38
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 b8
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 5 b8
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 10
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 6 10
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
,D/TCMD    (  472): Listening for incoming client connection request
D/WifiStateMachine( 1021): handleMessage: E msg.what=147461
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
,D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiP2pService( 1021): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): handleMessage: X
,W/ProcessCpuTracker( 1021): Skipping unknown process pid 4472
,W/ProcessCpuTracker( 1021): Skipping unknown process pid 4473
,W/ProcessCpuTracker( 1021): Skipping unknown process pid 4485
,D/CaptivePortalTracker( 1021): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1021): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
W/XTWiFiOS( 1280): No entry in secure settings for enhanced location services: false
D/Tethering( 1021): MasterInitialState.processMessage what=3
I/SBar.NetworkController( 1095): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
D/PollingManager( 1602): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1095): updateConnectivity: NetworkInfo: null, inetCondition= 0
W/XTWiFiOS( 1280): Active network info is not available
,I/ActivityManager( 1021): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4488 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,D/Tethering( 1021): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1095): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/CaptivePortalTracker( 1021): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1280): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1095): updateConnectivity: NetworkInfo: null, inetCondition= 0
,W/XTWiFiOS( 1280): Active network info is not available
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,E/ActivityThread( 1602): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1602): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1602): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1602): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1602): Registering with Alarm Manager to restart CCE
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,D/OtaApp  ( 1602): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1602): [debug] > CusSM.onRadioDown
,D/dalvikvm( 4488): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x4247ec08, skipping init
I/openssl ( 4488): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4488): Crypto mode 0 already enabled
I/ActivityManager( 1021): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4513 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 4089:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1270): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4513): mnc/mcc: 
V/MmsConfig( 4513): tag: bool value: enabledMMS - true
V/MmsConfig( 4513): tag: int value: maxMessageSize - 307200
,V/MmsConfig( 4513): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4513): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4513): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4513): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4513): tag: int value: minMessageCountPerThread - 10
,V/MmsConfig( 4513): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4513): tag: int value: recipientLimit - 20
V/MmsConfig( 4513): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4513): tag: int value: smsToMmsTextThreshold - 6
,V/MmsConfig( 4513): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4513): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4513): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4513): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4513): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 4513): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4513): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1021): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4532 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1021): Killing 4213:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1270): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  278): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 23ms
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 19ms
,D/MobileConnectivityChangeReceiver( 4532): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4532): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4532): onOtaspChanged old =0, new =3
D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 19ms
,V/PhoneMonitor( 4532): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1021): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4547 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 4260:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1270): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4547): Binding Chromium to main looper Looper (main, tid 1) {4246fb10}
,I/LibraryLoader( 4547): Expected native library version number "",actual native library version number ""
,I/chromium( 4547): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4547): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4547): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4547): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4547): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4547): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4547): Local Branch: 
I/Adreno-EGL( 4547): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4547): Local Patches: NONE
I/Adreno-EGL( 4547): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4547): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4547): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  264): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  264): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4547): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 4547): Starting up...
,I/ActivityManager( 1021): Killing 3944:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1270): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.Environment( 1705): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1705): num queued entries: 0
,I/iu.UploadsManager( 1705): num updated entries: 0
,I/iu.SyncManager( 1705): NEXT; no task
,I/ActivityManager( 1021): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=4593 uid=10056 gids={50056, 3003, 1028, 1015}
,D/dalvikvm( 1021): GC_EXPLICIT freed 22965K, 65% free 18324K/51372K, paused 4ms+19ms, total 189ms
,D/dalvikvm( 4593): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,W/dalvikvm( 4593): VFY: unable to resolve instance field 68
D/dalvikvm( 4593): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 4593): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4593): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/dalvikvm( 4593): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 4593): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/dalvikvm( 4593): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 4593): VFY: unable to resolve instance field 68
,D/dalvikvm( 4593): VFY: replacing opcode 0x54 at 0x0011
I/ActivityManager( 1021): Killing 4300:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1270): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm( 4593): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4593): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4593): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4593): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4593): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 4593): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,D/MobileConnectivityChangeReceiver( 4532): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4532): onReceive CONNECTIVITY_CHANGE networkType=1
,D/DEBUG   ( 1602): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1602): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1602): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1602): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1602): onServiceConnected()
D/GetNotificationsWS( 1602): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1602): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1602): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1602): unbindWebServices(): un-registering our AIDL callback...
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 4
,V/AlarmManager( 1021): sending alarm Alarm{4436f420 type 2 com.google.android.gms}
,D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1021): sending alarm Alarm{4436ee28 type 2 android}
,I/GAV2    ( 4547): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4408): Test app app.js loaded
I/jxcore-log( 4408): 
,I/chromium( 4408): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 c
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 6 c
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 3
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 7 3
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 b
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 8 b
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 1
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 9 1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 c2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 7 c2
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
,D/TCMD    (  472): Listening for incoming client connection request
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1021): processMsg: DisconnectedState
,D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): processMsg: DriverStartedState
,D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
,D/WifiP2pService( 1021): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler },
,D/WifiP2pService( 1021): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1021): handleMessage: X
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{442de848 type 2 com.google.android.gms}
,D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 1163): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
,D/TCMD    (  472): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  275): Event received = Trying to associate with,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE ,
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147461
,E/wpa_supplicant( 1163): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
,D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: DisconnectedState
,D/WifiStateMachine( 1021): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
,I/wpa_supplicant( 1163): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 1163): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  472): NL - Read 312 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 88 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 1000 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1163): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  275): Event received = Associated with c0:ff:d4
D/TCMD    (  472): NL - Read 80 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 80 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
,D/TCMD    (  472): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1021): processMsg: DisconnectedState
,D/WifiStateMachine( 1021): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1163): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  275): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1163): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  275): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  275):  STA Connected !!
D/TCMD    (  472): NL - Read 1000 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
,D/TCMD    (  472): Listening for incoming client connection request
E/MDMCTBK (  275): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  275): get_freq !!, resp=0
I/MDMCTBK (  275): get_freq !!, Strip data
I/MDMCTBK (  275): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,0,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  275): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  275): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  275): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,0,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1199860512
I/MDMCTBK (  275): return from set_get_from_wpa_supplicant
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
,I/MDMCTBK (  275): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
D/WifiStateMachine( 1021): processMsg: ConnectModeState
I/MDMCTBK (  275): send SAR ctrl over QMI
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1021): handleMessage: X
,D/MDMCTBK (  275): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  275): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  275): , reply_len: 3, ret: 0
E/MDMCTBK (  275): MdmCutbackHndler, resp=OK
E/MDMCTBK (  275): 
,D/MDMCTBK (  275): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=147459
,D/WifiStateMachine( 1021): processMsg: DisconnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): Network connection established
,D/Tethering( 1021): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1021): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1021): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1095): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1021): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1021): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1021): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1021): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine( 1021): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=147462
D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-81ms what=147462 obj=android.net.wifi.StateChangeResult@44a37590 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
,D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=131101
D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-77ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@4264f908 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
,D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=196612
D/WifiStateMachine( 1021): processMsg: ObtainingIpState
,D/WifiStateMachine( 1021): ObtainingIpState{ when=-6ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1021): processMsg: L2ConnectedState
,D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1021): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1021): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42d924b8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42d924b8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 11 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 11 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 12 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 12 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 8 c0
D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 8 c0
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 9 06
D/TCMD    (  472): Listening for incoming client connection request
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 9 06
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 10 6
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 10 6
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
,D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
,D/WifiP2pService( 1021): InactiveState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1021): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): handleMessage: E msg.what=147461
D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): handleMessage: X
,D/TCMD    (  472): NL - Read 60 bytes from update socket.
D/TCMD    (  472): NL - ignore NL message, type = 20
,D/TCMD    (  472): Listening for incoming client connection request
,D/WifiStateMachine( 1021): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1021): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-7ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
,D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1021): processMsg: ObtainingIpState
D/WifiStateMachine( 1021): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
,D/WifiStateMachine( 1021): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1021): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1021): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1021): DHCP successful
,D/WifiStateMachine( 1021): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1021): Calling ARP set with IP = 192.168.1.127
,D/WifiStateMachine( 1021): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1021): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1021): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1021): VerifyingLinkState enter
,D/WifiStateMachine( 1021): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1095): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=151572
D/WifiStateMachine( 1021): processMsg: VerifyingLinkState
D/WifiStateMachine( 1021): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1021): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1095): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/WifiStateMachine( 1021): handleMessage: X
,D/WifiStateMachine( 1021): handleMessage: E msg.what=135190
D/WifiStateMachine( 1021): processMsg: VerifyingLinkState
D/WifiStateMachine( 1021): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1021): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1021): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1021): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1021): CaptivePortalCheckState enter
,D/WifiStateMachine( 1021): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,I/SBar.NetworkController( 1095): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1021): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1021): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1021): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1021): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131092
D/WifiStateMachine( 1021): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1021): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiStateMachine( 1021): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,I/SBar.NetworkController( 1095): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1021): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1021): WiFi NOT Tethered!
,E/ConnectivityService( 1021): Unexpected mtu value: android.net.wifi.WifiStateTracker@42541f28
I/SBar.NetworkController( 1095): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1301): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1301): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1301): onReceive() - done, currentInetCondition=0
D/WifiStateMachine( 1021): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1021): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1021): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1021): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1021): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1021): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1021): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1021): handleMessage: X
D/WifiStateMachine( 1021): handleMessage: E msg.what=131092
D/WifiStateMachine( 1021): processMsg: ConnectedState
D/WifiStateMachine( 1021): processMsg: L2ConnectedState
D/WifiStateMachine( 1021): processMsg: ConnectModeState
D/WifiStateMachine( 1021): processMsg: DriverStartedState
D/WifiStateMachine( 1021): processMsg: SupplicantStartedState
D/WifiStateMachine( 1021): processMsg: DefaultState
D/WifiStateMachine( 1021): handleMessage: X
D/Checkin ( 1021): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.NetworkController( 1095): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1095): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService( 1021): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1021): WiFi NOT Tethered!
,I/CheckinService( 1705): Checkin interval check for package: unspecified last checkin: 1452763875525 min interval config: 0 actual interval: 319759
E/ConnectivityService( 1021): Unexpected mtu value: android.net.wifi.WifiStateTracker@42541f28
,I/CheckinService( 1705): Checking schedule, now: 1452764195294 next: 1452763905477
,I/CheckinService( 1705): active receiver: enabled
,D/ConnectivityService( 1021): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1021): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1301): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1301): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1301): onReceive() - done, currentInetCondition=0
,I/CheckinService( 1705): Preparing to send checkin request
,I/EventLogService( 1705): Accumulating logs since 1452763870438
,I/CheckinRequestBuilder( 1705): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1705): Failed to find provider info for com.google.android.wearable.settings
,I/jxcore-log( 4408): --= Surplus to requirements =--
I/jxcore-log( 4408): 
I/jxcore-log( 4408): ****TEST TOOK:  ms ****
I/jxcore-log( 4408): 
,I/jxcore-log( 4408): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4408): 
,V/GLSActivity( 2162): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2162): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1021): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4700 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4700): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4700): VFY: replacing opcode 0x60 at 0x000b
I/dalvikvm( 4700): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4700): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4700): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 4700): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4700): install
,I/MultiDex( 4700): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4700): loading existing secondary dex files
,I/MultiDex( 4700): load found 3 secondary dex files
,I/MultiDex( 4700): install done
,D/dalvikvm( 4700): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4700): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4700): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4700): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 4700): VFY: unable to resolve instance field 36
,D/dalvikvm( 4700): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 4700): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4700): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4700): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4700): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4700): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4700): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42476d48
,D/dalvikvm( 4700): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42476d48
,D/dalvikvm( 4700): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42476d48, skipping init
,D/dalvikvm( 4700): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42476d48
,D/dalvikvm( 4700): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42476d48
,V/JNIHelp ( 4700): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4700): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42476d48
,D/dalvikvm( 4700): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42476d48
D/dalvikvm( 4700): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42476d48
,D/dalvikvm( 4700): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42476d48
,I/ProviderInstaller( 4700): Installed default security provider GmsCore_OpenSSL
,D/AndroidRuntime( 4698): 
D/AndroidRuntime( 4698): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4698): CheckJNI is OFF
,D/LocationInitializer( 1705): Restart initialization of location
,D/WearableService( 1224): callingUid 10022, callindPid: 1224
,D/AuthorizationBluetoothService( 2162): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 2162): Proximity feature is not enabled.
,E/MDM     ( 1224): [69] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 2162): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 4698): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4698): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4698): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4698): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4698): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,I/dalvikvm( 4700): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 4700): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4700): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4700): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4700): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4700): VFY: replacing opcode 0x6e at 0x000d
,W/GCoreFlp( 1224): No location to return for getLastLocation()
,W/FusedLocationProvider( 1224): location=null
,D/dalvikvm( 4698): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,I/dalvikvm( 4700): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4700): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4700): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4700): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4700): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4700): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4700): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
D/dalvikvm( 4700): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4700): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4700): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4700): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/WVCdm   (  280): Instantiating CDM.
,I/WVCdm   (  280): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  280): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  280): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  280): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5270000
,E/DrmWidevineDash(  280): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5270000
D/DrmWidevineDash(  280): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  280): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  280): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  280): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  280): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  280): CdmEngine::OpenSession
,D/DrmWidevineDash(  280): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  280): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  280): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  280): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  280): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  280): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  280): PrepareKeyRequest: nonce=2255555188
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,E/memtrack( 4698): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4698): failed to load memtrack module: -2
,D/NativeLibraryUtils( 4700): Install completed successfully. count=14 extracted=0
,D/AndroidRuntime( 4698): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
,I/ActivityManager( 1021): Killing 4408:com.test.thalitest/u0a109 (adj 0): stop com.test.thalitest
,W/ContextImpl( 1270): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1021):   Force finishing activity ActivityRecord{42e3cac8 u0 com.test.thalitest/.MainActivity t2}
,I/WindowState( 1021): WIN DEATH: Window{43a952a0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1021): Client connection lost with reason: 4
,I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10109 user=0: pkg removed
,D/dalvikvm( 4700): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x426c61a0
,D/dalvikvm( 4700): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x426c61a0
,D/dalvikvm( 4700): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x426c61a0, skipping init
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  280): CdmEngine::CloseSession
,D/DrmWidevineDash(  280): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 1312): GC_EXPLICIT freed 3430K, 33% free 11597K/17224K, paused 2ms+4ms, total 45ms
,D/dalvikvm( 1705): GC_EXPLICIT freed 1405K, 30% free 12068K/17224K, paused 3ms+9ms, total 75ms
D/ConnectivityService( 1021): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 2331): GC_EXPLICIT freed 3349K, 42% free 10072K/17224K, paused 2ms+4ms, total 78ms
,I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
,I/Launcher( 1312): Deferring update until onResume
,I/Keyboard.Facilitator( 1210): resetDictionaries() : en_GB
,I/Keyboard.Facilitator.DecoderInitializer( 1210): run()
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
,I/Decoder ( 1210): createOrResetDecoder
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
,W/GeofencerStateMachine( 1224): Ignoring removeGeofence because network location is disabled.
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
,D/VoicemailCleanupService( 1193): Cleaning up data for package: com.test.thalitest
,D/dalvikvm( 2299): GC_EXPLICIT freed 6163K, 44% free 9759K/17224K, paused 2ms+7ms, total 61ms
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
,D/dalvikvm( 1021): GC_EXPLICIT freed 1573K, 65% free 18309K/51372K, paused 9ms+11ms, total 147ms
,D/dalvikvm( 1021): WAIT_FOR_CONCURRENT_GC blocked 74ms
,I/ActivityManager( 1021): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4745 uid=10033 gids={50033, 3003, 1028, 1015}
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
,I/ConfigService( 1224): onCreate
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/Launcher( 1312): Deferring update until onResume
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1210): run()
,D/BackupManagerService( 1021): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 1021): removePackageParticipantsLocked: uid=10109 #1
,W/InputMethodManagerService( 1021): Got RemoteException sending setActive(false) notification to pid 4408 uid 10109
W/Binder  ( 1210): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1210): java.lang.NullPointerException
W/Binder  ( 1210): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1210): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1210): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1210): 	at dalvik.system.NativeStart.run(Native Method)
I/Keyboard.Facilitator( 1210): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1210): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1.apk (offset=5018356, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Loaded File = UserHistory.en_GB.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1210): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1210): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1210): run()
I/StatsUtilsManager( 1210): startPeriodStatsRecorder() : Success
,I/PeriodicStatsRecorder( 1210): shouldRecordStats() = Too Soon
,I/ActivityManager( 1021): Killing 4334:com.quickoffice.android/u0a95 (adj 15): empty #9
,W/ContextImpl( 1270): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2331): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/dalvikvm( 1021): GC_EXPLICIT freed 429K, 65% free 18290K/51372K, paused 5ms+15ms, total 190ms
,I/ActivityManager( 1021): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4765 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,W/ContextImpl( 4765): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,I/dalvikvm( 3882): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3882): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3882): VFY: replacing opcode 0x6e at 0x0013
,D/PackageBroadcastService( 1705): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1705): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1705): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1705): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1705): Removing dialog suppression flag for package com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 2162): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 2162): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/ChimeraCfgMgr( 1705): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1705): Module APK com.google.android.play.games already loaded
,D/gH_CompatibleDatabase( 1705): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1705): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1705): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 1705): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1705): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1705): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1705): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1705): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1705): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1705): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1705): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1705): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1705): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/Icing   ( 1705): doRemovePackageData com.test.thalitest
,I/ActivityManager( 1021): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4791 uid=10059 gids={50059, 1028, 3003, 1015}
,I/WVCdm   (  280): CdmEngine::OpenSession
,D/DrmWidevineDash(  280): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  280): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  280): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  280): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  280): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetDeviceID...
I/ActivityManager( 1021): Killing 4488:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1270): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/DrmWidevineDash(  280): OEMCrypto_GetDeviceID returns 0
D/DrmWidevineDash(  280): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  280): PrepareKeyRequest: nonce=2884627865
D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 7
D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
D/AndroidRuntime( 4698): Shutting down VM
D/dalvikvm( 4698): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+1ms, total 3ms
,I/InternalIcingCorporaPro( 2331): UpdateCorporaTask done [took 229 ms] updated apps [took 229 ms] 
,I/dalvikvm( 4791): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method gqa.a
,W/dalvikvm( 4791): VFY: unable to resolve virtual method 1798: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4791): VFY: replacing opcode 0x6e at 0x000f
,I/GAv4    ( 4791): Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4791):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4791):   adb logcat -s GAv4
,W/GAv4    ( 4791): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/dalvikvm( 4791): Could not find method android.content.Context.checkSelfPermission, referenced from method asa.a
W/dalvikvm( 4791): VFY: unable to resolve virtual method 1616: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4791): VFY: replacing opcode 0x6e at 0x001b
,W/GAv4    ( 4791): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4791): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 4791): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.474.23.34, sample rate 1.0
,I/dalvikvm( 4791): Could not find method android.provider.DocumentsContract.getTreeDocumentId, referenced from method edw.a
,W/dalvikvm( 4791): VFY: unable to resolve static method 2986: Landroid/provider/DocumentsContract;.getTreeDocumentId (Landroid/net/Uri;)Ljava/lang/String;
,D/dalvikvm( 4791): VFY: replacing opcode 0x71 at 0x0075
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  280): CdmEngine::CloseSession
,D/DrmWidevineDash(  280): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4700): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,E/dalvikvm( 4820): unable to mmap DEX cache: Permission denied
,E/dalvikvm( 4820): Optimization failed
W/dalvikvm( 4700): DexOpt: --- END 'f.apk' --- status=0xff00, process failed
,E/dalvikvm( 4700): Unable to extract+optimize DEX from '/data/data/com.google.android.gms/app_fb/f.apk'
I/ActivityManager( 1021): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=4826 uid=10095 gids={50095, 3003, 1028, 1015}
I/ActivityManager( 1021): Killing 4513:com.android.mms/u0a30 (adj 15): empty #9
W/ContextImpl( 1270): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,E/SQLiteLog( 2299): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
,E/SQLiteDatabase( 2299): Error inserting state=event=am_kill pid=4513 process=com.android.mms reason=empty+%239 selectadj=15 timestamp=1452764197078 timezone=3600 name=ProcessKillTrigger
E/SQLiteDatabase( 2299): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2299): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2299): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2299): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2299): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2299): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2299): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2299): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2299): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2299): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2299): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2299): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2299): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2299): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2299): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2299): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SharedPreferencesImpl( 4791): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml.bak
,E/cutils  (  264): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  264): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4791): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,D/dalvikvm( 4791): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4791): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4791): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4791): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4791): VFY: unable to resolve instance field 36
,D/dalvikvm( 4791): VFY: replacing opcode 0x54 at 0x005f
,E/SQLiteDatabase( 4826): Failed to open database '/data/data/com.quickoffice.android/databases/keyvaluedb.db'.
E/SQLiteDatabase( 4826): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4826): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4826): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4826): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4826): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4826): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4826): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4826): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4826): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4826): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4826): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4826): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4826): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4826): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4826): 	at com.qo.android.quickcommon.keyvalueprovider.KeyValueProvider.onCreate(KeyValueProvider.java:42)
E/SQLiteDatabase( 4826): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4826): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4826): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4855)
E/SQLiteDatabase( 4826): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4450)
E/SQLiteDatabase( 4826): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4390)
E/SQLiteDatabase( 4826): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4826): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteDatabase( 4826): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4826): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4826): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4826): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4826): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4826): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4826): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4826): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 4826): Shutting down VM
W/dalvikvm( 4826): threadid=1: thread exiting with uncaught exception (group=0x41ba4d40)
D/dalvikvm( 4791): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4791): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4791): VFY: replacing opcode 0x62 at 0x0047
E/AndroidRuntime( 4826): FATAL EXCEPTION: main
E/AndroidRuntime( 4826): Process: com.quickoffice.android, PID: 4826
E/AndroidRuntime( 4826): java.lang.RuntimeException: Unable to get provider com.qo.android.quickcommon.keyvalueprovider.KeyValueProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4826): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4858)
E/AndroidRuntime( 4826): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4450)
E/AndroidRuntime( 4826): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4390)
E/AndroidRuntime( 4826): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/AndroidRuntime( 4826): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/AndroidRuntime( 4826): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4826): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4826): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4826): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4826): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4826): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4826): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4826): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4826): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4826): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4826): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4826): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4826): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4826): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4826): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4826): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4826): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4826): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4826): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4826): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4826): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4826): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4826): 	at com.qo.android.quickcommon.keyvalueprovider.KeyValueProvider.onCreate(KeyValueProvider.java:42)
E/AndroidRuntime( 4826): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 4826): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 4826): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4855)
E/AndroidRuntime( 4826): 	... 12 more
D/dalvikvm( 4791): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 4791): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 4791): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427d2ad8
D/dalvikvm( 4791): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427d2ad8
D/dalvikvm( 4791): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427d2ad8, skipping init
I/Process ( 4826): Sending signal. PID: 4826 SIG: 9
E/DropBoxManagerService( 1021): Can't write: system_app_crash
E/DropBoxManagerService( 1021): java.io.FileNotFoundException: /data/system/dropbox/drop104.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1021): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1021): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1021): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1021): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1021): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1021): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1021): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1021): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1021): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1021): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1021): 	... 5 more
I/ActivityManager( 1021): Process com.quickoffice.android (pid 4826) has died.
D/dalvikvm( 4791): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427d2ad8
D/dalvikvm( 4791): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427d2ad8
V/JNIHelp ( 4791): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...

```
