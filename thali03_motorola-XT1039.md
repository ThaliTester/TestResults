#### Test 561510933390750_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4332): 
D/AndroidRuntime( 4332): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4332): CheckJNI is OFF
D/dalvikvm( 4332): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4332): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4332): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4332): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4332): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4332): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4332): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4332): failed to load memtrack module: -2
D/AndroidRuntime( 4332): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1022): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4332
W/WindowManager( 1022): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1022): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4348 uid=10116 gids={50116, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4332): Shutting down VM
D/dalvikvm( 4332): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+1ms, total 3ms
W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4348): Binding Chromium to main looper Looper (main, tid 1) {4293a838}
I/LibraryLoader( 4348): Expected native library version number "",actual native library version number ""
I/chromium( 4348): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4348): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1022): Message: 20
D/BluetoothManagerService( 1022): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44adb4f8:true
I/Adreno-EGL( 4348): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4348): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4348): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4348): Local Branch: 
I/Adreno-EGL( 4348): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4348): Local Patches: NONE
I/Adreno-EGL( 4348): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4348): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4348): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4348): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4348): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4348): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4348): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4348): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4348): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4348): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4348): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4348): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4348): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4348): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4348): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4348): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4348): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4348): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4348): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4348): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4348): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4348): Enabling debug mode 0
,W/AwContents( 4348): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1210): onFinishInput()
,W/IInputConnectionWrapper( 4348): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1022): Displayed com.test.thalitest/.MainActivity,cp,ca,397
I/ActivityManager( 1022): Displayed com.test.thalitest/.MainActivity: +369ms (total +397ms)
,D/JsMessageQueue( 4348): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4348): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4293eb08
,D/dalvikvm( 4348): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4293eb08
,D/jxcore_app_log( 4348): JniHelper::setJavaVM(0x4205cf78), pthread_self() = 1615530952
,D/JX-Cordova( 4348): jxcore cordova android initializing
,D/dalvikvm( 4348): GC_CONCURRENT freed 2705K, 16% free 14484K/17224K, paused 2ms+3ms, total 43ms
,D/dalvikvm( 4348): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/dalvikvm( 4348): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/dalvikvm( 4348): GC_FOR_ALLOC freed 347K, 14% free 14889K/17224K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4348): Grow heap (frag case) to 16.614MB for 42652-byte allocation
,D/dalvikvm( 4348): GC_FOR_ALLOC freed 104K, 14% free 14896K/17268K, paused 26ms, total 26ms
,D/dalvikvm( 4348): GC_FOR_ALLOC freed 126K, 14% free 14916K/17268K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4348): Grow heap (frag case) to 16.691MB for 95956-byte allocation
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
,D/dalvikvm( 4348): GC_FOR_ALLOC freed 179K, 14% free 14951K/17364K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4348): Grow heap (frag case) to 16.770MB for 143930-byte allocation
,D/dalvikvm( 4348): GC_FOR_ALLOC freed 253K, 15% free 14998K/17508K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4348): Grow heap (frag case) to 16.885MB for 215890-byte allocation
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 4348): GC_FOR_ALLOC freed 368K, 15% free 15072K/17720K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4348): Grow heap (frag case) to 17.060MB for 323830-byte allocation
,D/dalvikvm( 4348): GC_FOR_ALLOC freed 569K, 16% free 15192K/18040K, paused 28ms, total 29ms
,I/dalvikvm-heap( 4348): Grow heap (frag case) to 17.333MB for 485740-byte allocation
,D/dalvikvm( 4348): GC_FOR_ALLOC freed 863K, 17% free 15369K/18516K, paused 27ms, total 27ms
,D/dalvikvm( 4348): GC_FOR_ALLOC freed 1175K, 16% free 15614K/18516K, paused 28ms, total 28ms
,D/dalvikvm( 4348): GC_FOR_ALLOC freed 124K, 16% free 15608K/18516K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4348): Grow heap (frag case) to 18.317MB for 1092904-byte allocation
,D/dalvikvm( 4348): GC_CONCURRENT freed 1921K, 19% free 16041K/19584K, paused 1ms+7ms, total 55ms
,D/dalvikvm( 4348): GC_FOR_ALLOC freed 49K, 19% free 16007K/19584K, paused 27ms, total 28ms
,I/dalvikvm-heap( 4348): Grow heap (frag case) to 19.227MB for 1639352-byte allocation
,D/dalvikvm( 4348): GC_CONCURRENT freed 1930K, 22% free 16563K/21188K, paused 2ms+5ms, total 56ms
,D/dalvikvm( 4348): GC_FOR_ALLOC freed 1056K, 23% free 16521K/21188K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4348): Grow heap (frag case) to 20.511MB for 2459024-byte allocation
,D/dalvikvm( 4348): GC_CONCURRENT freed 1969K, 27% free 17341K/23592K, paused 5ms+4ms, total 52ms
,D/dalvikvm( 4348): GC_CONCURRENT freed 2553K, 26% free 17546K/23592K, paused 2ms+7ms, total 51ms
,D/dalvikvm( 4348): WAIT_FOR_CONCURRENT_GC blocked 34ms
,I/dalvikvm-heap( 4348): Grow heap (frag case) to 22.685MB for 3688532-byte allocation
,D/dalvikvm( 4348): GC_CONCURRENT freed 2701K, 32% free 18688K/27196K, paused 2ms+6ms, total 69ms
,D/dalvikvm( 4348): GC_FOR_ALLOC freed 2065K, 32% free 18663K/27196K, paused 35ms, total 35ms
,W/jxcore-log( 4348): Initializing JXcore engine
,W/jxcore-log( 4348): JXcore engine is ready
,D/dalvikvm( 4348): GC_CONCURRENT freed 411K, 22% free 21474K/27196K, paused 2ms+3ms, total 33ms
,D/dalvikvm( 4348): WAIT_FOR_CONCURRENT_GC blocked 20ms
D/dalvikvm( 4348): WAIT_FOR_CONCURRENT_GC blocked 24ms
,W/jxcore-log( 4348): Starting JXcore engine
,W/jxcore-log( 4348): Platform android
W/jxcore-log( 4348): 
,W/jxcore-log( 4348): Process ARCH arm
W/jxcore-log( 4348): 
,I/jxcore-log( 4348): JXcore Cordova bridge is ready!
I/jxcore-log( 4348): 
,W/jxcore-log( 4348): JXcore engine is started
,I/chromium( 4348): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4348): Toggling radios to true
I/jxcore-log( 4348): 
,D/BluetoothAdapter( 4348): enable(): BT is already enabled..!
D/WifiService( 1022): New client listening to asynchronous messages
D/WifiService( 1022): setWifiEnabled: true pid=4348, uid=10116
,E/WifiService( 1022): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1022): handleMessage: E msg.what=131145
D/WifiStateMachine( 1022): processMsg: ConnectedState
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
I/jxcore-log( 4348): Radios toggled
I/jxcore-log( 4348): 
I/jxcore-log( 4348): My device name is: motorola-XT1039
I/jxcore-log( 4348): 
,I/wpa_supplicant( 1188): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  276): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  276):  STA Disconnected !!
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): get_property_value, Enter
I/MDMCTBK (  276): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,0,1,0, length=23
I/MDMCTBK (  276): get_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  276): set_property_value, Enter
,I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  276): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
,I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,0,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
,I/MDMCTBK (  276): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
I/MDMCTBK (  276): send SAR ctrl over QMI
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1022): transitionTo: destState=DisconnectingState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1022): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1022): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1022): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1022): setSuspendOptimizationsNative: 1 true
,D/Tethering( 1022): InitialState.processMessage what=4
D/WifiP2pService( 1022): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,V/ConnectivityService( 1022): WiFi NOT Tethered!
D/TCMD    (  438): NL - Read 1000 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
D/TCMD    (  438): NL - Read 1000 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
D/TCMD    (  438): NL - Read 68 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
D/TCMD    (  438): NL - Read 68 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
D/Tethering( 1022): sendTetherStateChangedBroadcast 0, 0, 0
E/wpa_supplicant( 1188): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1188): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  274): Clearing all IP addresses on wlan0
D/TCMD    (  438): NL - Read 60 bytes from update socket.
D/TCMD    (  438): NL - ignore NL message, type = 21
,D/TCMD    (  438): Listening for incoming client connection request
,D/WifiStateMachine( 1022): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1022): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1022): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1022): connected time updated 294849
,I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1022): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1022): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,I/dalvikvm( 1022): Jit: resizing JitTable from 8192 to 16384
D/ConnectivityService( 1022): Attempting to switch to mobile
D/ConnectivityService( 1022): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1022): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1094): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1094): refreshSignalCluster: mobile: Signal=zz_moto_stat_sys_signal_emergency_only_wide Roaming=(none) mSimIconId=zz_moto_stat_sys_no_sim_wide Accessibility="Emergency calls only.","","No SIM card."
I/SBar.NetworkController( 1094): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
D/WifiStateMachine( 1022): invokeEnterMethods: DisconnectingState
,D/WifiStateMachine( 1022): DisconnectingState
,D/ConnectivityService( 1022): resetConnections(wlan0, 3)
D/NetUtils( 1022): android_net_utils_resetConnections in env=0x61a20200 clazz=0x63000001 iface=wlan0 mask=0x3
E/wpa_supplicant( 1188): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1188): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131146
D/WifiStateMachine( 1022): processMsg: DisconnectingState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
V/NativeCrypto( 1345): Read error: ssl=0x634ad8e0: I/O error during system call, Connection timed out
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147460
D/WifiStateMachine( 1022): processMsg: DisconnectingState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): Network connection lost
D/WifiStateMachine( 1022): Stopping DHCP and clearing IP
D/WifiStateMachine( 1022): setSuspendOptimizationsNative: 1 true
D/Checkin ( 1022): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
V/NativeCrypto( 1345): SSL shutdown failed: ssl=0x634ad8e0: I/O error during system call, Broken pipe
,D/WifiP2pService( 1022): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1022): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1188): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1188): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  274): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1022): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1022): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1022): invokeExitMethods: DisconnectingState
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine( 1022): invokeEnterMethods: DisconnectedState
,D/Checkin ( 1022): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131101
D/WifiStateMachine( 1022): processMsg: DisconnectedState
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
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
,D/WifiStateMachine( 1022): handleMessage: X
,D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=false
I/ModemStatsDSDetect( 1275): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1275): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1275): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1022): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1022): Attempting to switch to mobile
D/ConnectivityService( 1022): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1022): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1022): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1275): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1275): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1275): onReceive() - done, currentInetCondition=0
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
,I/wpa_supplicant( 1188): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  276): Event received = Trying to associate with
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  438): NL - Read 56 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
E/wpa_supplicant( 1188): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147461
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): processMsg: DriverStartedState
,D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
,D/WifiStateMachine( 1022): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): handleMessage: X
,I/wpa_supplicant( 1188): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  438): NL - Read 312 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
D/TCMD    (  438): NL - Read 192 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
,D/TCMD    (  438): Listening for incoming client connection request
I/wpa_supplicant( 1188): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  438): NL - Read 68 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
,D/TCMD    (  438): Listening for incoming client connection request
D/TCMD    (  438): NL - Read 1000 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
I/wpa_supplicant( 1188): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  276): Event received = Associated with c0:ff:d4
D/TCMD    (  438): NL - Read 80 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
D/TCMD    (  438): NL - Read 80 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
D/TCMD    (  438): NL - Read 68 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1022): processMsg: DisconnectedState
,D/WifiStateMachine( 1022): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1188): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1188): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  276): Event received = WPA: Key negotiation com
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  276): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  276):  STA Connected !!
D/TCMD    (  438): NL - Read 1000 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
,D/TCMD    (  438): Listening for incoming client connection request
E/MDMCTBK (  276): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  276): get_freq !!, resp=0
I/MDMCTBK (  276): get_freq !!, Strip data
I/MDMCTBK (  276): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): get_property_value, Enter
I/MDMCTBK (  276): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,0,1,0, length=23
I/MDMCTBK (  276): get_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  276): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  276): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  276): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): get_property_value, Enter
I/MDMCTBK (  276): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,0,1,0, length=23
I/MDMCTBK (  276): get_property_value, Exit
I/MDMCTBK (  276): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1203553456
I/MDMCTBK (  276): return from set_get_from_wpa_supplicant
D/MDMCTBK (  276): wifi_set_tx_pwr: SETTXPOWER = 19
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=0, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,0,1,0
E/MDMCTBK (  276): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  276): , reply_len: 3, ret: 0
E/MDMCTBK (  276): MdmCutbackHndler, resp=OK
E/MDMCTBK (  276): 
,D/MDMCTBK (  276): wifi_set_tx_pwr: Exit
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
,I/MDMCTBK (  276): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
,D/WifiStateMachine( 1022): handleMessage: X
I/MDMCTBK (  276): send SAR ctrl over QMI
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): handleMessage: X
,D/Tethering( 1022): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1022): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147459
,D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): Network connection established
,D/WifiStateMachine( 1022): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1022): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1022): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1022): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1022): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1022): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: ObtainingIpState
,D/WifiStateMachine( 1022): ObtainingIpState{ when=-41ms what=147462 obj=android.net.wifi.StateChangeResult@445dfb48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=131101
D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=-33ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@4515c388 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=196612
D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=-7ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1022): processMsg: L2ConnectedState
,D/WifiStateMachine( 1022): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1022): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1022): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42b43fa0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1022): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42b43fa0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): handleMessage: X
,D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 c
,D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 3
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 5 3
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 6
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 6 6
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 6
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 7 6
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 1
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 8 1
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 0 c2
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 10
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 5 10
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  438): NL - Read 56 bytes from update socket.
D/TCMD    (  438): NL - message type is RTM_NEWLINK
D/TCMD    (  438): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiP2pService( 1022): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@45169e80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@45169e80 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1022): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@45169e80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): handleMessage: E msg.what=147461
D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1022): handleMessage: X
,D/Tethering( 1022): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1022): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1022): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/PollingManager( 1624): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
W/XTWiFiOS( 1267): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: null, inetCondition= 0
W/XTWiFiOS( 1267): Active network info is not available
,D/TCMD    (  438): NL - Read 60 bytes from update socket.
D/TCMD    (  438): NL - ignore NL message, type = 20
,D/TCMD    (  438): Listening for incoming client connection request
,D/WifiStateMachine( 1022): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
I/ActivityManager( 1022): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4447 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/WifiStateMachine( 1022): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=0 what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
,D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1022): handleMessage: X
,I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: null, inetCondition= 0
,W/XTWiFiOS( 1267): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1267): Active network info is not available
,E/ActivityThread( 1624): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1624): Registering with Alarm Manager to restart CCE
,D/PollingManager( 1624): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1624): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 1624): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1624): [debug] > CusSM.onRadioDown
,E/ActivityThread( 1624): Failed to find provider info for com.motorola.blur.setupprovider
D/Tethering( 1022): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1022): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,D/dalvikvm( 4447): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x42942de8, skipping init
I/openssl ( 4447): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4447): Crypto mode 0 already enabled
,I/ActivityManager( 1022): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4494 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1022): Killing 4128:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4494): mnc/mcc: 
V/MmsConfig( 4494): tag: bool value: enabledMMS - true
,V/MmsConfig( 4494): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4494): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4494): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4494): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4494): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4494): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4494): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4494): tag: int value: recipientLimit - 20
,V/MmsConfig( 4494): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4494): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4494): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4494): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4494): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4494): tag: bool value: smsForceShowEncodingMenu - true
,V/MmsConfig( 4494): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4494): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4494): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1022): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4513 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1022): Killing 4189:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiStateMachine( 1022): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
,D/WifiStateMachine( 1022): setSuspendOptimizationsNative: 1 true
,D/MobileConnectivityChangeReceiver( 4513): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4513): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4513): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4513): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager( 1022): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4527 uid=10076 gids={50076, 3003, 1028, 1015}
I/ActivityManager( 1022): Killing 3877:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/WifiP2pService( 1022): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1022): DHCP successful
,D/WifiStateMachine( 1022): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1022): Calling ARP set with IP = 192.168.1.127
,D/WifiStateMachine( 1022): transitionTo: destState=VerifyingLinkState
,D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1022): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1022): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1022): VerifyingLinkState enter
,D/WifiStateMachine( 1022): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=151572
D/WifiStateMachine( 1022): processMsg: VerifyingLinkState
D/WifiStateMachine( 1022): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1022): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1094): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=135190
D/WifiStateMachine( 1022): processMsg: VerifyingLinkState
D/WifiStateMachine( 1022): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1022): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1022): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1022): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1022): CaptivePortalCheckState enter
,D/WifiStateMachine( 1022): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,V/WebViewChromiumFactoryProvider( 4527): Binding Chromium to main looper Looper (main, tid 1) {4293e3e0}
D/ConnectivityService( 1022): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1022): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1022): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1022): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/LibraryLoader( 4527): Expected native library version number "",actual native library version number ""
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131092
D/WifiStateMachine( 1022): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1022): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
I/chromium( 4527): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4527): Initializing chromium process, renderers=0
D/WifiStateMachine( 1022): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,I/SBar.NetworkController( 1094): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1022): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1022): WiFi NOT Tethered!
,E/ConnectivityService( 1022): Unexpected mtu value: android.net.wifi.WifiStateTracker@42a0a090
I/SBar.NetworkController( 1094): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,E/AudioManagerAndroid( 4527): BLUETOOTH permission is missing!
,D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine( 1022): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1022): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1022): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131092
D/WifiStateMachine( 1022): processMsg: ConnectedState
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): handleMessage: X
I/ModemStatsDSDetect( 1275): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1094): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/Checkin ( 1022): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/ConnectivityService( 1022): ConnectivityChange for WIFI: CONNECTED/CONNECTED
I/SBar.NetworkController( 1094): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,V/ConnectivityService( 1022): WiFi NOT Tethered!
I/ModemStatsDSDetect( 1275): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1275): onReceive() - done, currentInetCondition=0
E/ConnectivityService( 1022): Unexpected mtu value: android.net.wifi.WifiStateTracker@42a0a090
,D/ConnectivityService( 1022): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=true
I/CheckinService( 1729): Checkin interval check for package: unspecified last checkin: 1453032728551 min interval config: 0 actual interval: 279535
I/ModemStatsDSDetect( 1275): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1275): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1275): onReceive() - done, currentInetCondition=0
,I/CheckinService( 1729): Checking schedule, now: 1453033008097 next: 1453032758535
,I/CheckinService( 1729): active receiver: enabled
,I/CheckinService( 1729): Preparing to send checkin request
,I/EventLogService( 1729): Accumulating logs since 1453032723951
,I/CheckinRequestBuilder( 1729): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1729): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1022): GC_EXPLICIT freed 25355K, 65% free 18787K/53676K, paused 5ms+12ms, total 181ms
,I/Adreno-EGL( 4527): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4527): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4527): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4527): Local Branch: 
I/Adreno-EGL( 4527): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4527): Local Patches: NONE
I/Adreno-EGL( 4527): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4527): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,V/GLSActivity( 1345): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1345): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 4527): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4527): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/ActivityManager( 1022): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4566 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4566): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4566): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4566): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4566): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4566): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4566): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4566): install
,I/MultiDex( 4566): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4566): loading existing secondary dex files
,I/MultiDex( 4566): load found 3 secondary dex files
,I/MultiDex( 4566): install done
,D/dalvikvm( 4566): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4566): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4566): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4566): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4566): VFY: unable to resolve instance field 36
,D/dalvikvm( 4566): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4566): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4566): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4566): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4566): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4566): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4566): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x429449d0
D/dalvikvm( 4566): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x429449d0
,D/dalvikvm( 4566): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x429449d0, skipping init
,D/dalvikvm( 4566): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x429449d0
D/dalvikvm( 4566): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x429449d0
,V/JNIHelp ( 4566): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/NSApplication( 4527): Starting up...
,I/ActivityManager( 1022): Killing 3902:com.google.android.apps.plus/u0a90 (adj 15): empty #9
,W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm( 4566): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x429449d0
D/dalvikvm( 4566): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x429449d0
D/dalvikvm( 4566): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x429449d0
D/dalvikvm( 4566): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x429449d0
,I/ProviderInstaller( 4566): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager( 1022): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=4585 uid=10056 gids={50056, 3003, 1028, 1015}
,I/dalvikvm( 4566): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 4566): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4566): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4566): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4566): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4566): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4566): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4566): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4566): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4566): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4566): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4566): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4566): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4566): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 4566): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4566): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4566): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/dalvikvm( 4585): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 4585): VFY: unable to resolve instance field 68
D/dalvikvm( 4585): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 4585): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4585): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 4585): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 4585): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/DEBUG   ( 1624): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/dalvikvm( 4585): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 4585): VFY: unable to resolve instance field 68
D/dalvikvm( 4585): VFY: replacing opcode 0x54 at 0x0011
,W/ContextImpl( 1624): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1624): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1624): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1624): onServiceConnected()
,D/GetNotificationsWS( 1624): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1624): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1624): ServiceHandler.handleMessage: mWaitCount=0
D/dalvikvm( 4585): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4585): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4585): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 4585): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 4585): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4585): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,D/GetNotificationsWS( 1624): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4447): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4447): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4513): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4513): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager( 1022): Killing 4227:com.google.android.apps.docs/u0a59 (adj 15): empty #9
D/WVCdm   (  284): Instantiating CDM.
,I/WVCdm   (  284): Level3 Library Nov 20 2013 18:09:31
W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/DrmWidevineDash(  284): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  284): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  284): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb50e6000
,E/DrmWidevineDash(  284): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb50e6000
D/DrmWidevineDash(  284): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  284): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  284): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  284): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  284): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  284): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  284): CdmEngine::OpenSession
,D/DrmWidevineDash(  284): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  284): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  284): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  284): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  284): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  284): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  284): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  284): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  284): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  284): calling OEMCrypto_GetDeviceID...
,I/jxcore-log( 4348): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4348): 
,I/ActivityManager( 1022): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/com.google.android.libraries.social.autobackup.AutoBackupEnvironment$ConnectivityReceiver: pid=4606 uid=10090 gids={50090, 3003, 3002, 1028, 1015}
I/jxcore-log( 4348): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4348): 
D/DrmWidevineDash(  284): OEMCrypto_GetDeviceID returns 0
D/DrmWidevineDash(  284): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  284): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  284): PrepareKeyRequest: nonce=3460982095
D/DrmWidevineDash(  284): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  284): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  284): OEMCrypto_GenerateRSASignature returns 7
D/DrmWidevineDash(  284): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/jxcore-log( 4348): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4348): 
,E/dalvikvm( 4606): Could not find class 'android.app.Notification$Action$Builder', referenced from method efj.a
W/dalvikvm( 4606): VFY: unable to resolve new-instance 412 (Landroid/app/Notification$Action$Builder;) in Lefj;
,D/dalvikvm( 4606): VFY: replacing opcode 0x22 at 0x0000
,I/jxcore-log( 4348): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4348): 
,I/jxcore-log( 4348): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4348): 
,I/jxcore-log( 4348): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4348): 
,E/dalvikvm( 4606): Could not find class 'android.graphics.drawable.RippleDrawable', referenced from method efj.a
,W/dalvikvm( 4606): VFY: unable to resolve new-instance 575 (Landroid/graphics/drawable/RippleDrawable;) in Lefj;
,D/dalvikvm( 4606): VFY: replacing opcode 0x22 at 0x000b
,D/dalvikvm( 4566): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42b44910
D/dalvikvm( 4566): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42b44910
,D/dalvikvm( 4566): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42b44910, skipping init
,D/DrmWidevineDash(  284): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  284): CdmEngine::CloseSession
,D/DrmWidevineDash(  284): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  284): OEMCrypto_CloseSession returns 0
,D/ConnectivityService( 1022): NetTransition Wakelock for ConnectedState released by timeout
,E/dalvikvm( 4606): Could not find class 'android.app.Notification$Action$Builder', referenced from method efj.a
,D/NativeLibraryUtils( 4566): Install completed successfully. count=14 extracted=0
W/dalvikvm( 4606): VFY: unable to resolve new-instance 412 (Landroid/app/Notification$Action$Builder;) in Lefj;
,D/dalvikvm( 4606): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 4606): Unable to resolve superclass of Lcm; (800)
,W/dalvikvm( 4606): Link of class 'Lcm;' failed
E/dalvikvm( 4606): Could not find class 'cm', referenced from method efj.a
W/dalvikvm( 4606): VFY: unable to resolve new-instance 2378 (Lcm;) in Lefj;
,D/dalvikvm( 4606): VFY: replacing opcode 0x22 at 0x0006
,W/dalvikvm( 4606): Unable to resolve superclass of Lco; (800)
W/dalvikvm( 4606): Link of class 'Lco;' failed
E/dalvikvm( 4606): Could not find class 'co', referenced from method efj.a
W/dalvikvm( 4606): VFY: unable to resolve new-instance 2432 (Lco;) in Lefj;
,D/dalvikvm( 4606): VFY: replacing opcode 0x22 at 0x002c
I/dalvikvm( 4606): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method efj.a
W/dalvikvm( 4606): VFY: unable to resolve virtual method 5224: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 4606): VFY: replacing opcode 0x6e at 0x0008
,I/dalvikvm( 4606): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method efj.a
W/dalvikvm( 4606): VFY: unable to resolve virtual method 5756: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 4606): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 4606): Could not find method android.view.View.getTransitionName, referenced from method efj.a
,W/dalvikvm( 4606): VFY: unable to resolve virtual method 5560: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4606): VFY: replacing opcode 0x6e at 0x0006
,W/dalvikvm( 4606): VFY: unable to find class referenced in signature (Lx;)
,I/dalvikvm( 4606): Could not find method android.transition.Transition.getTargetNames, referenced from method efj.a
W/dalvikvm( 4606): VFY: unable to resolve virtual method 5213: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
D/dalvikvm( 4606): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 4606): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method efj.a
W/dalvikvm( 4606): VFY: unable to resolve interface method 5806: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
,D/dalvikvm( 4606): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 4606): Could not find method android.view.ViewParent.onNestedFling, referenced from method efj.a
W/dalvikvm( 4606): VFY: unable to resolve interface method 5805: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
,D/dalvikvm( 4606): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 4606): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method efj.a
W/dalvikvm( 4606): VFY: unable to resolve interface method 5807: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 4606): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 4606): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 4606): Could not find class 'android.app.RemoteInput[]', referenced from method efj.a
W/dalvikvm( 4606): VFY: unable to resolve new-array 13337 ([Landroid/app/RemoteInput;) in Lefj;
,D/dalvikvm( 4606): VFY: replacing opcode 0x23 at 0x0005
,I/dalvikvm( 4606): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method efj.b
,W/dalvikvm( 4606): VFY: unable to resolve virtual method 5224: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 4606): VFY: replacing opcode 0x6e at 0x0009
,W/dalvikvm( 4606): VFY: unable to find class referenced in signature (Lx;)
,D/dalvikvm( 4606): DexOpt: unable to opt direct call 0x09c0 at 0x0e in Lefj;.a
,D/dalvikvm( 4606): DexOpt: unable to opt direct call 0x0d49 at 0x0e in Lefj;.a
,D/dalvikvm( 4606): DexOpt: unable to opt direct call 0x09c0 at 0x0e in Lefj;.a
,W/dalvikvm( 4606): Unable to resolve superclass of Lcm; (800)
W/dalvikvm( 4606): Link of class 'Lcm;' failed
,D/dalvikvm( 4606): DexOpt: unable to opt direct call 0x39db at 0x08 in Lefj;.a
W/dalvikvm( 4606): Unable to resolve superclass of Lco; (800)
W/dalvikvm( 4606): Link of class 'Lco;' failed
,D/dalvikvm( 4606): DexOpt: unable to opt direct call 0x3b51 at 0x30 in Lefj;.a
,D/dalvikvm( 4606): DexOpt: unable to opt direct call 0x0a18 at 0x13 in Lefj;.a
,W/Settings( 4566): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4566): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,I/dalvikvm( 4606): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method eer.a
W/dalvikvm( 4606): VFY: unable to resolve virtual method 2532: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4606): VFY: replacing opcode 0x6e at 0x023c
I/dalvikvm( 4606): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eer.a
W/dalvikvm( 4606): VFY: unable to resolve virtual method 2906: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4606): VFY: replacing opcode 0x6e at 0x000f
I/dalvikvm( 4606): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method eer.c
W/dalvikvm( 4606): VFY: unable to resolve virtual method 2532: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4606): VFY: replacing opcode 0x6e at 0x0207
,D/dalvikvm( 4606): Trying to load lib /data/app-lib/com.google.android.apps.plus-1/libcrashreporterer.so 0x4294a7d0
,D/dalvikvm( 4606): Added shared lib /data/app-lib/com.google.android.apps.plus-1/libcrashreporterer.so 0x4294a7d0
,D/WearableService( 1224): callingUid 10022, callindPid: 1224
,D/dalvikvm( 4621): DexOpt: load 4ms, verify+opt 8ms, 128132 bytes
,I/ActivityManager( 1022): Killing 4259:com.quickoffice.android/u0a95 (adj 15): empty #9
,E/MDM     ( 1224): [127] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 4566): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4566): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 112ms
,D/AuthorizationBluetoothService( 1345): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1729): Restart initialization of location
,E/AuthorizationBluetoothService( 1345): Proximity feature is not enabled.
,I/Adreno-EGL( 4566): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4566): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4566): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4566): Local Branch: 
I/Adreno-EGL( 4566): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4566): Local Patches: NONE
I/Adreno-EGL( 4566): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,V/GLSActivity( 1345): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1224): No location to return for getLastLocation()
,W/FusedLocationProvider( 1224): location=null
,I/Adreno-EGL( 4566): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4566): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4566): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4566): Local Branch: 
I/Adreno-EGL( 4566): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4566): Local Patches: NONE
I/Adreno-EGL( 4566): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/jxcore-log( 4348): Test app app.js loaded
I/jxcore-log( 4348): 
,I/chromium( 4348): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Adreno-EGL( 4566): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4566): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4566): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4566): Local Branch: 
I/Adreno-EGL( 4566): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4566): Local Patches: NONE
I/Adreno-EGL( 4566): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4566): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4566): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4566): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4566): Local Branch: 
I/Adreno-EGL( 4566): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4566): Local Patches: NONE
I/Adreno-EGL( 4566): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/WVCdm   (  284): CdmEngine::OpenSession
,D/DrmWidevineDash(  284): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  284): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  284): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  284): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  284): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  284): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  284): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  284): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  284): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  284): calling OEMCrypto_GetDeviceID...
,I/jxcore-log( 4348): --= Surplus to requirements =--
I/jxcore-log( 4348): 
I/jxcore-log( 4348): ****TEST TOOK:  ms ****
I/jxcore-log( 4348): 
,I/jxcore-log( 4348): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4348): 
,D/DrmWidevineDash(  284): OEMCrypto_GetDeviceID returns 0
D/DrmWidevineDash(  284): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  284): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  284): PrepareKeyRequest: nonce=1607077991
D/DrmWidevineDash(  284): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  284): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  284): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  284): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  284): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  284): CdmEngine::CloseSession
,D/DrmWidevineDash(  284): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  284): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1729): Classify the device as Phone.
,D/AndroidRuntime( 4653): 
D/AndroidRuntime( 4653): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4653): CheckJNI is OFF
,D/dalvikvm( 4653): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4653): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4653): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4653): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4653): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4653): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,I/CheckinTask( 1729): Sending checkin request (11761 bytes)
,E/memtrack( 4653): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4653): failed to load memtrack module: -2
,D/AndroidRuntime( 4653): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1022): Force stopping com.test.thalitest appid=10116 user=-1: uninstall pkg
,I/ActivityManager( 1022): Killing 4348:com.test.thalitest/u0a116 (adj 0): stop com.test.thalitest
,W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1022):   Force finishing activity ActivityRecord{450c9708 u0 com.test.thalitest/.MainActivity t3}
,I/WindowState( 1022): WIN DEATH: Window{450dce78 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1022): Client connection lost with reason: 4
,I/ActivityManager( 1022): Force stopping com.test.thalitest appid=10116 user=0: pkg removed
I/ActivityManager( 1022):   Force finishing activity ActivityRecord{450c9708 u0 com.test.thalitest/.MainActivity t3 f}
,W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ActivityManager( 1022): Duplicate finish request for ActivityRecord{450c9708 u0 com.test.thalitest/.MainActivity t3 f}
,D/dalvikvm( 1729): GC_EXPLICIT freed 1517K, 31% free 12055K/17224K, paused 4ms+6ms, total 57ms
,W/SQLiteConnectionPool( 1729): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/dalvikvm( 2298): GC_EXPLICIT freed 5178K, 44% free 9646K/17224K, paused 4ms+5ms, total 54ms
,W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/Keyboard.Facilitator( 1210): resetDictionaries() : en_GB
W/GeofencerStateMachine( 1224): Ignoring removeGeofence because network location is disabled.
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "sms"
I/Keyboard.Facilitator.DecoderInitializer( 1210): run()
I/InputReader( 1022): Reconfiguring input devices.  changes=0x00000010
I/Decoder ( 1210): createOrResetDecoder
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "smsto"
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mms"
D/OtaApp  ( 1624): [debug] > DownloadActivity, FormattedText
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mmsto"
D/dalvikvm( 1299): GC_EXPLICIT freed 3248K, 33% free 11596K/17224K, paused 2ms+9ms, total 119ms
I/OtaApp  ( 1624): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 1624): publish the event [tag = MOT_OTA event name = LOG]
I/Launcher( 1299): Deferring update until onResume
I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
W/XTWiFiOS( 1267): No entry in secure settings for enhanced location services: false
D/VoicemailCleanupService( 1193): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "sms"
,D/dalvikvm( 2331): GC_EXPLICIT freed 4081K, 42% free 10085K/17224K, paused 5ms+18ms, total 173ms
I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "smsto"
W/XTWiFiOS( 1267): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
D/OtaApp  ( 1624): [debug] > cancelling the previous pending intent set for download later
I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/OtaApp  ( 1624): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 1624): publish the event [tag = MOT_OTA event name = LOG]
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mms"
I/ConfigService( 1224): onCreate
D/BackupManagerService( 1022): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1022): removePackageParticipantsLocked: uid=10116 #1
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
D/Tethering( 1022): MasterInitialState.processMessage what=3
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mmsto"
D/Tethering( 1022): MasterInitialState.processMessage what=3
I/ActivityManager( 1022): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4686 uid=10033 gids={50033, 3003, 1028, 1015}
D/CaptivePortalTracker( 1022): NoActiveNetworkState{ when=-7ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/CaptivePortalTracker( 1022): DelayedCaptiveCheckState{ when=-4ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/OtaApp  ( 1624): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
D/OtaApp  ( 1624): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
I/Launcher( 1299): Deferring update until onResume
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1210): run()
,D/PollingManager( 1624): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1624): now: 329396 ,futureTime: 63680929
,D/PollingManager( 1624): Polling alarm set to expire at: 63680929 Current Time: 329396
,E/ActivityThread( 1624): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1624): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1624): now: 329399 ,futureTime: 63680929
D/PollingManager( 1624): Polling alarm set to expire at: 63680929 Current Time: 329399
,E/ActivityThread( 1624): Failed to find provider info for com.motorola.blur.setupprovider
,W/InputMethodManagerService( 1022): Got RemoteException sending setActive(false) notification to pid 4348 uid 10116
,W/Binder  ( 1210): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1210): java.lang.NullPointerException
W/Binder  ( 1210): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1210): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1210): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1210): 	at dalvik.system.NativeStart.run(Native Method)
,I/Keyboard.Facilitator( 1210): onFinishInput()
,D/OtaApp  ( 1624): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1624): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1624): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1624): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1210): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1.apk (offset=5018356, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Loading LM = history
,D/OtaApp  ( 1624): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Loaded File = UserHistory.en_GB.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Loading LM = user
I/OtaApp  ( 1624): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (RequestPermission)
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1210): run() : Loaded (exit)
D/Checkin ( 1624): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator.Delight2FileSweeper( 1210): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1210): run()
I/StatsUtilsManager( 1210): startPeriodStatsRecorder() : Success
,I/PeriodicStatsRecorder( 1210): shouldRecordStats() = Too Soon
,D/OtaApp  ( 1624): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1624): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,D/OtaApp  ( 1624): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 1624): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,D/dalvikvm( 1022): GC_EXPLICIT freed 1623K, 66% free 18768K/53676K, paused 7ms+13ms, total 233ms
,D/OtaApp  ( 1624): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1624): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/TelephonyProvider( 1256): Column apn id key is 'apn_id'
,I/InternalIcingCorporaPro( 2331): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/OtaApp  ( 1624): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1624): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 1624): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager( 1022): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4703 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/OtaApp  ( 1624): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1624): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
D/OtaApp  ( 1624): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 1624): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/dalvikvm(  280): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 1ms+3ms, total 22ms
I/ActivityManager( 1022): Killing 3796:com.android.vending/u0a38 (adj 15): empty #9
W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  280): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,W/ContextImpl( 4703): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/dalvikvm(  280): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 18ms
,I/ActivityManager( 1022): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4718 uid=10038 gids={50038, 3003, 1028, 1015}
,D/AndroidRuntime( 4653): Shutting down VM
,D/dalvikvm( 4653): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
,I/ActivityManager( 1022): Killing 4315:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinRequestBuilder( 1729): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1729): Failed to find provider info for com.google.android.wearable.settings
,I/InternalIcingCorporaPro( 2331): UpdateCorporaTask done [took 157 ms] updated apps [took 157 ms] 
,I/dalvikvm( 4718): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
,W/dalvikvm( 4718): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4718): VFY: replacing opcode 0x6e at 0x000e
,D/dalvikvm( 1345): GC_EXPLICIT freed 1479K, 40% free 10395K/17224K, paused 2ms+4ms, total 31ms
,D/Finsky  ( 4718): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/CheckinRequestBuilder( 1729): Classify the device as Phone.
,I/CheckinTask( 1729): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/dalvikvm( 4718): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4718): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4718): VFY: replacing opcode 0x6e at 0x01d3
I/CheckinService( 1729): Checking schedule, now: 1453033011685 next: 1453582665680
,I/CheckinService( 1729): active receiver: disabled
,D/CheckinService( 1729): Recording last checkin time for package unspecified as 1453033011698
I/dalvikvm( 4718): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4718): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4718): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4718): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/dalvikvm( 4718): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4718): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4718): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4718): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4718): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4718): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4718): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4718): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 4718): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4718): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4718): VFY: replacing opcode 0x6e at 0x037f
,I/dalvikvm( 4718): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4718): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4718): VFY: replacing opcode 0x6e at 0x0385
,I/dalvikvm( 4718): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 4718): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4718): VFY: replacing opcode 0x6e at 0x0019
,I/ActivityManager( 1022): Killing 4494:com.android.mms/u0a30 (adj 15): empty #9
,D/Ads     ( 4718): Skipping gmscore version check
,W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Finsky  ( 4718): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4718): [1] Libraries$2.run: Finished loading 1 libraries.
D/PackageBroadcastService( 1729): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1729): Clearing selected account for com.test.thalitest
E/SQLiteLog( 2298): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
D/Finsky  ( 4718): [1] GmsCoreHelper.cleanupNlp: result=false type=4
E/SQLiteDatabase( 2298): Error inserting state=event=am_kill pid=4494 process=com.android.mms reason=empty+%239 selectadj=15 timestamp=1453033011804 timezone=3600 name=ProcessKillTrigger
E/SQLiteDatabase( 2298): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2298): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2298): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2298): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2298): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2298): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2298): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2298): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2298): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2298): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2298): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2298): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2298): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2298): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2298): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2298): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ChimeraCfgMgr( 1729): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1729): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 1729): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/LocationSettingsChecker( 1729): Removing dialog suppression flag for package com.test.thalitest
E/DriveAsyncService( 1729): disk I/O error (code 3850)
E/DriveAsyncService( 1729): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1729): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1729): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1729): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1729): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1729): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1729): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1729): 	at com.google.android.gms.drive.dat,abase.k.k(SourceFile:486)
E/DriveAsyncService( 1729): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1729): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1729): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1729): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1729): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1729): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1729): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1729): 	at java.lang.Thread.run(Thread.java:841)
I/dalvikvm( 4718): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4718): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4718): VFY: replacing opcode 0x6e at 0x0013
D/ChimeraCfgMgr( 1729): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1729): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 1345): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 1345): Shutting down VM
W/dalvikvm( 1345): threadid=1: thread exiting with uncaught exception (group=0x4206ed40)
E/AndroidRuntime( 1345): FATAL EXCEPTION: main
E/AndroidRuntime( 1345): Process: com.google.process.gapps, PID: 1345
E/AndroidRuntime( 1345): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1345): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 1345): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 1345): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 1345): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1345): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1345): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 1345): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1345): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1345): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 1345): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 1345): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1345): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1345): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1345): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1345): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1345): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1345): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1345): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1345): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1345): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1345): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 1345): 	... 10 more
E/SQLiteDatabase( 1729): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1729): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1729): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1729): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1729): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1729): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1729): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1729): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1729): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1729): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1729): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1729): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1729): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1729): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1729): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1729): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1729): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1729): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1729): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1729): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1729): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 1729): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1729): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1729): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1729): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1729): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1729): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1729): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1729): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1729): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1729): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1729): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1729): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1729): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1729): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1729): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1729): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1729): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1729): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1729): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1729): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1729): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1729): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1729): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1729): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 1729): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/Finsky  ( 4718): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
E/PhenotypeInitializer( 1729): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 1729): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1729): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1729): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/PhenotypeInitializer( 1729): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/PhenotypeInitializer( 1729): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1729): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1729): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1729): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/PhenotypeInitializer( 1729): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/PhenotypeInitializer( 1729): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/PhenotypeInitializer( 1729): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/PhenotypeInitializer( 1729): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/PhenotypeInitializer( 1729): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/PhenotypeInitializer( 1729): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 1729): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 1729): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1729): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1729): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1729): 	at android.os.Looper.loop(Looper.java:136)
E/PhenotypeInitializer( 1729): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 1729): threadid=51: thread exiting with uncaught exception (group=0x4206ed40)
E/SQLiteOpenHelper( 1729): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1729): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1729): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1729): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1729): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1729): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1729): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1729): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1729): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 1729): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 1729): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1729): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 1729): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1729): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1729): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1729): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1729): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1729): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1729): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1729): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1729): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1729): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 1729): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1729): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/Process ( 1345): Sending signal. PID: 1345 SIG: 9
W/SQLiteOpenHelper( 1729): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1729): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1729): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/ClearPendingStateOp( 1729): Runtime exception while performing operation
E/ClearPendingStateOp( 1729): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 1729): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 1729): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearPendingStateOp( 1729): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 1729): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 1729): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearPendingStateOp( 1729): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/ClearPendingStateOp( 1729): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 1729): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 1729): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/ClearPendingStateOp( 1729): 	at android.content.ContentResolver.delete(ContentResolver.java:1282)
E/ClearPendingStateOp( 1729): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1729): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1729): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 1729): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1729): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1729): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 1729): 	at java.lang.Thread.run(Thread.java:841)
F/ClearPendingStateOp( 1729): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1729): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 1729): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 1729): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
F/ClearPendingStateOp( 1729): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 1729): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 1729): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
F/ClearPendingStateOp( 1729): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
F/ClearPendingStateOp( 1729): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 1729): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 1729): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
F/ClearPendingStateOp( 1729): 	at android.content.ContentResolver.delete(ContentResolver.java:1282)
F/ClearPendingStateOp( 1729): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1729): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1729): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 1729): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1729): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1729): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 1729): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteLog( 1729): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
I/Icing   ( 1729): doRemovePackageData com.test.thalitest
D/gH_CompatibleDatabase( 1729): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 1729): threadid=50: thread exiting with uncaught exception (group=0x4206ed40)
I/Process ( 1729): Sending signal. PID: 1729 SIG: 9
E/GMPM-SVC( 1729): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
E/DropBoxManagerService( 1022): Can't write: system_app_crash
E/DropBoxManagerService( 1022): java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
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
E/SharedPreferencesImpl( 4718): Couldn't rename file /data/data/com.android.vending/shared_prefs/finsky.xml to backup file /data/data/com.android.vending/shared_prefs/finsky.xml.bak

```
