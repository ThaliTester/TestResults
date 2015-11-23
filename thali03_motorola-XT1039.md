#### Test 513350289b9c5d6_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1023): sending alarm Alarm{42850e08 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 4007): 
D/AndroidRuntime( 4007): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4007): CheckJNI is OFF
D/dalvikvm( 4007): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4007): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4007): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4007): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4007): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4007): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4007): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4007): failed to load memtrack module: -2
D/AndroidRuntime( 4007): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1023): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4007
W/WindowManager( 1023): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1023): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4023 uid=10397 gids={50397, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4007): Shutting down VM
D/dalvikvm( 4007): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4023): Binding Chromium to main looper Looper (main, tid 1) {4251db68}
I/LibraryLoader( 4023): Expected native library version number "",actual native library version number ""
I/chromium( 4023): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4023): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1023): Message: 20
D/BluetoothManagerService( 1023): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425ae820:true
I/Adreno-EGL( 4023): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4023): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4023): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4023): Local Branch: 
I/Adreno-EGL( 4023): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4023): Local Patches: NONE
I/Adreno-EGL( 4023): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4023): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4023): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4023): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4023): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4023): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4023): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4023): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4023): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4023): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4023): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4023): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4023): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4023): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4023): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4023): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4023): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4023): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4023): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4023): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4023): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4023): Enabling debug mode 0
,W/AwContents( 4023): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4023): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1023): Displayed com.test.thalitest/.MainActivity,cp,ca,422
I/ActivityManager( 1023): Displayed com.test.thalitest/.MainActivity: +397ms (total +423ms)
,I/SFPerfTracer(  278):      triggers: (rate: 3:28) (compose: 0:4) (post: 0:1) (render: 0:5) (0:113 frames) (1:555)
,D/SFPerfTracer(  278):        layers: (0:12) (FocusedStackFrame: 0:9)* (StatusBar: 0:216)* (NavigationBar: 0:40)* (com.android.systemui.ImageWallpaper: 0:6)* (Starting com.motorola.ccc.ota: 0:34)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:18)* (ElectronBeam: 0:27)* (com.test.thalitest/com.test.thalitest.MainActivity: 1:3)* 
,D/JsMessageQueue( 4023): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4023): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42522018
,D/dalvikvm( 4023): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42522018
D/jxcore_app_log( 4023): JniHelper::setJavaVM(0x41c39f78), pthread_self() = 1613489720
,D/JX-Cordova( 4023): jxcore cordova android initializing
,I/dalvikvm( 4023): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 4023): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4023): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 4023): GC_CONCURRENT freed 2856K, 17% free 14333K/17224K, paused 3ms+3ms, total 39ms
,D/dalvikvm( 4023): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 4023): GC_FOR_ALLOC freed 56K, 18% free 14278K/17224K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4023): Grow heap (frag case) to 16.069MB for 98002-byte allocation
,D/dalvikvm( 4023): GC_FOR_ALLOC freed 201K, 18% free 14293K/17320K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4023): Grow heap (frag case) to 16.130MB for 146998-byte allocation
,D/dalvikvm( 4023): GC_FOR_ALLOC freed 259K, 18% free 14338K/17464K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4023): Grow heap (frag case) to 16.245MB for 220492-byte allocation
,D/dalvikvm( 4023): GC_FOR_ALLOC freed 374K, 19% free 14413K/17680K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4023): Grow heap (frag case) to 16.423MB for 330734-byte allocation
,D/dalvikvm( 4023): GC_FOR_ALLOC freed 578K, 20% free 14538K/18004K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4023): Grow heap (frag case) to 16.703MB for 496096-byte allocation
,D/dalvikvm( 4023): GC_FOR_ALLOC freed 879K, 21% free 14716K/18492K, paused 26ms, total 27ms
,D/dalvikvm( 4023): GC_FOR_ALLOC freed 1302K, 20% free 14977K/18492K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4023): Grow heap (frag case) to 17.722MB for 1116206-byte allocation
,D/dalvikvm( 4023): GC_CONCURRENT freed 1734K, 22% free 15364K/19584K, paused 2ms+3ms, total 33ms
,D/dalvikvm( 4023): GC_FOR_ALLOC freed 352K, 22% free 15309K/19584K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4023): Grow heap (frag case) to 18.580MB for 1674304-byte allocation
,D/dalvikvm( 4023): GC_CONCURRENT freed 1651K, 26% free 15882K/21220K, paused 2ms+5ms, total 32ms
,D/dalvikvm( 4023): GC_FOR_ALLOC freed 1436K, 25% free 15984K/21220K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4023): Grow heap (frag case) to 20.037MB for 2511452-byte allocation
,D/dalvikvm( 4023): GC_CONCURRENT freed 1875K, 30% free 16728K/23676K, paused 2ms+5ms, total 41ms
,D/dalvikvm( 4023): GC_CONCURRENT freed 2389K, 29% free 16915K/23676K, paused 2ms+6ms, total 39ms
,D/dalvikvm( 4023): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 4023): GC_FOR_ALLOC freed 598K, 30% free 16763K/23676K, paused 31ms, total 32ms
,I/dalvikvm-heap( 4023): Grow heap (frag case) to 21.995MB for 3767174-byte allocation
,D/dalvikvm( 4023): GC_CONCURRENT freed 2692K, 35% free 17881K/27356K, paused 4ms+3ms, total 33ms
,D/dalvikvm( 4023): GC_FOR_ALLOC freed 400K, 35% free 17907K/27356K, paused 25ms, total 25ms
,W/jxcore-log( 4023): Initializing JXcore engine
,W/jxcore-log( 4023): JXcore engine is ready
,D/dalvikvm( 4023): GC_CONCURRENT freed 288K, 25% free 20564K/27356K, paused 1ms+3ms, total 30ms
,D/dalvikvm( 4023): WAIT_FOR_CONCURRENT_GC blocked 28ms
,W/jxcore-log( 4023): Starting JXcore engine
,W/jxcore-log( 4023): Platform android
W/jxcore-log( 4023): 
,W/jxcore-log( 4023): Process ARCH arm
W/jxcore-log( 4023): 
,I/jxcore-log( 4023): JXcore Cordova bridge is ready!
I/jxcore-log( 4023): 
,W/jxcore-log( 4023): JXcore engine is started
,I/chromium( 4023): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4023): Turning radios to true
I/jxcore-log( 4023): 
,D/BluetoothAdapter( 4023): enable(): BT is already enabled..!
,I/jxcore-log( 4023): toggleBluetooth - 
I/jxcore-log( 4023): 
D/WifiService( 1023): New client listening to asynchronous messages
D/WifiService( 1023): setWifiEnabled: true pid=4023, uid=10397
,E/WifiService( 1023): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4023): toggleWiFi
I/jxcore-log( 4023): 
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,D/BluetoothManagerService( 1023): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4023): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): my name is : motorola-XT1039_PT6969
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): attempting to connect to test coordinator
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): check test folder
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): found test : ./testFindPeers.js
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): found test : ./testReConnect.js
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): found test : ./testSendData.js
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): Test app app.js loaded
I/jxcore-log( 4023): 
,I/chromium( 4023): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 4023): DBG, CoordinatorConnector connect called
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): Coordinator is now connected to the server!
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): printNetworkInfo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): found interfaceName: lo
I/jxcore-log( 4023): 
I/jxcore-log( 4023): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 4023): 
I/jxcore-log( 4023): found interfaceName: wlan0
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): -iface: IPv4 is internal : false, has ip: 192.168.1.123
I/jxcore-log( 4023): 
,I/chromium( 4023): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4023): BLE advertisement not supported: Build version is 19
I/jxcore-log( 4023): 
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
,I/dalvikvm( 1023): Jit: resizing JitTable from 8192 to 16384
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
,I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1023): sending alarm Alarm{428499e0 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4023): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): DBG, CoordinatorConnector command called
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":17,"addressList":[{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"50:2E:6C:AC:21:50","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"00:F4:6F:30:E0:6C","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0}]}
,I/jxcore-log( 4023): Start now : testSendData.js
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): stop tests now !
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 17
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): check server
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): serverPort is 43200
I/jxcore-log( 4023): 
,D/BluetoothManagerService( 1023): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/        ( 4023): Stoping All
I/        ( 4023): Stopping services
,I/        ( 4023): Stop Bluetooth
,D/BluetoothManagerService( 1023): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 4023): Start-My BT: F4:F1:E1:5C:3B:E2
,D/BluetoothManagerService( 1023): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 4023):  mInstanceString : {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6969"}
,I/        ( 4023): All stuff available and enabled
I/        ( 4023): Stoping All
I/        ( 4023): Stopping services
I/        ( 4023): Stop Bluetooth
I/        ( 4023): Starting All
I/        ( 4023): Stopping services
,I/        ( 4023): Starting services address: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6969"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@425acfe8
I/        ( 4023): Stopping services
,I/        ( 4023): Starting services address: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6969"}
,I/        ( 4023): Add local service :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6969"}, length : 81
D/WifiP2pService( 1023): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2832686 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2832686 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState add service
,D/WifiP2pService( 1023): add a new client
,I/        ( 4023): peerDiscoveryTimer timeout value:6359
D/WifiP2pService( 1023): InactiveState{ when=0 what=139307 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=139307 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState clear service request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=0 what=139265 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=139265 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 4023): Stop Bluetooth
I/        ( 4023): StartBluetooth listener
I/        ( 4023): StartBluetooth listener
D/BluetoothManagerService( 1023): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 4023): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1772): SOCK FLAG = 0 ***********************
I/jxcore-log( 4023): StartBroadcasting started ok
I/jxcore-log( 4023): 
I/jxcore-log( 4023): do fake peer & start
I/jxcore-log( 4023): 
I/jxcore-log( 4023): Connect to fake peer: F8:CF:C5:D9:E5:61
I/jxcore-log( 4023): 
I/jxcore-log( 4023): 2015-11-23T11:36:45.285Z SendDataConnector.js: Start called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 4023): 
I/jxcore-log( 4023): 2015-11-23T11:36:45.285Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 4023): 
I/jxcore-log( 4023): 2015-11-23T11:36:45.285Z SendDataConnector.js: do connect now
I/jxcore-log( 4023): 
I/BTListenerThread( 4023): starting to listen
I/BTListenerThread( 4023): waiting to accept incoming Connection
I/        ( 4023): Selected device address: F8:CF:C5:D9:E5:61, name: null
I/        ( 4023): Connecting to null, at F8:CF:C5:D9:E5:61
I/jxcore-log( 4023): 2015-11-23T11:36:45.292Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
I/jxcore-log( 4023): 
I/chromium( 4023): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/WB      ( 4023): We already were running, thus doing nothing
I/        ( 4023): Added local service
I/        ( 4023): Cleared service requests
I/        ( 4023): Stopped peer discovery
I/BTConnectToThread( 4023): Starting to connect
W/BluetoothAdapter( 4023): getBluetoothService() called with no BluetoothManagerCallback
,D/WifiP2pService( 1023): discovery change broadcast true
D/BTIF_SOCK( 1772): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
I/        ( 4023): Started peer discovery
I/        ( 4023): Discovery state changed to Started.
D/BluetoothSocket( 4023): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[131]}
,D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
I/wpa_supplicant( 1173): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-45
D/MDMCTBK (  276): reply_len: 49 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_add
,D/MDMCTBK (  276): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_add
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: A5-1
D/WifiP2pService( 1023):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=147477 obj=Device: A5-1
D/WifiP2pService( 1023):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=-1ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 4023): Found 1 peers.
,I/SS      ( 4023): Peer(1): A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1023): InactiveState{ when=0 what=139301 arg2=6 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=139301 arg2=6 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState add service request
D/WifiP2pManager( 4023): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4023): Added service request
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
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 7e:f9:0e:37
,D/MDMCTBK (  276): Event received = P2P-SERV-DISC-REQ 2412 7e:f9:0e:37
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139310 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139310 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState discover services
,I/        ( 4023): Started service discovery
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:
,D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:
,I/wpa_supplicant( 1173): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-23
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0:ff:d4:d3
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 1 c0:ff:d4:d3
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 49 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_add
,D/MDMCTBK (  276): Event received = P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_add,
I/wpa_supplicant( 1173): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-43
D/MDMCTBK (  276): reply_len: 49 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_add
,D/MDMCTBK (  276): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_add,
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: Android_2dc2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 a2:39:f7:6f
,D/MDMCTBK (  276): Event received = P2P-SERV-DISC-REQ 2412 a2:39:f7:6f
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 44:80:eb:7b
,D/MDMCTBK (  276): Event received = P2P-SERV-DISC-REQ 2412 44:80:eb:7b
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 44:80:eb:7b
,D/MDMCTBK (  276): Event received = P2P-SERV-DISC-REQ 2412 44:80:eb:7b
,D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 fa:cf:c5:d9
,D/MDMCTBK (  276): Event received = P2P-SERV-DISC-REQ 2412 fa:cf:c5:d9
,I/wpa_supplicant( 1173): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 level=-83
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 9e:93:4e:3e
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 2 9e:93:4e:3e
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 49 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_add
,D/MDMCTBK (  276): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_add,
I/wpa_supplicant( 1173): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-21,
D/MDMCTBK (  276): reply_len: 49 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_add
,D/MDMCTBK (  276): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_add
,D/WifiP2pService( 1023): InactiveState{ when=-8ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService( 1023):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService( 1023):  primary type: 3-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 128
D/WifiP2pService( 1023):  grpcapab: 9
D/WifiP2pService( 1023):  devcapab: 4
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -83 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-8ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService( 1023):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService( 1023):  primary type: 3-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 128
D/WifiP2pService( 1023):  grpcapab: 9
D/WifiP2pService( 1023):  devcapab: 4
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -83 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -21 target=com.android.internal.util.StateMachine$SmHandler }
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 1772): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothManagerService( 1023): Message: 20
,D/BluetoothManagerService( 1023): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4257f1d8:true
,I/BluetoothBondStateMachine( 1772): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
,I/ActivityManager( 1023): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.bluetooth.BTReceiver: pid=4092 uid=10011 gids={50011, 3003, 3002, 3001}
I/BluetoothBondStateMachine( 1772): Entering PendingCommandState State
,D/BluetoothManagerService( 1023): Message: 20
,D/BluetoothManagerService( 1023): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4257dd18:true
,I/CE-BTReceiver( 4092): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,I/ActivityManager( 1023): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.BluetoothPairReceiver: pid=4104 uid=10016 gids={50016, 3002}
,E/bt-btif ( 1772): services_to_search = 3fffffff
,E/bt-btif ( 1772): ****************search UUID = 1200***********
,I/ActivityManager( 1023): Killing 3765:com.android.calendar/u0a7 (adj 15): empty #9
V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
V/BluetoothFtpService( 1772): Ftp Service onStartCommand
V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,I/ActivityManager( 1023): Killing 3861:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,E/bt-btif ( 1772): services_to_search = 3ffffffe
,E/bt-btif ( 1772): ****************search UUID = 0100***********
,W/bt-btif ( 1772): new conn_srvc id:26, app_id:1
W/bt-btif ( 1772): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 1772): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 4023): Starting to Handshake
I/BTHandshakeSocketThread( 4023): Creating BTHandshakeSocketThread
I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread started
,I/BTConnectToThread( 4023): MESSAGE_WRITE 81 bytes.
,I/BTConnectToThread( 4023): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 4023): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8557","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 4023): HandshakeOk : motorola-Nexus 6_PT8557
I/HS      ( 4023): Hand Shake finished outgoing for : motorola-Nexus 6_PT8557
,I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4023): Starting the connected thread incoming : false, motorola-Nexus 6_PT8557
I/BtToSocketBase( 4023): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 4023): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 4023): mHTTPPort  set to : 54214
I/BtConnectorHelper( 4023): Request socket is using : 54214
,I/BtToRequestSocket( 4023): Now accepting connections
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,E/bt-btif ( 1772): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 4 uuid:0000110e-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1772): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 1772): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
D/BluetoothAdapterProperties( 1772): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 1772): Failed to remove device: F8:CF:C5:D9:E5:61
,I/BluetoothBondStateMachine( 1772): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,I/CE-BTReceiver( 4092): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 1772): StableState(): Entering Off State
,D/BluetoothMetrics( 1772): btclass1f00
,D/Checkin ( 1772): publish the event [tag = MOT_BT event name = PAIRING]
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BtConnectorHelper( 4023): Calling ConnectionStatusUpdate with port :54214
,I/jxcore-log( 4023): 2015-11-23T11:36:51.634Z SendDataConnector.js: CLIENT connected to 54214, error: null
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:36:51.635Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 4023): 
I/BtToRequestSocket( 4023): incoming data from: /127.0.0.1, port: 54214
,I/BtToRequestSocket( 4023): Set local streams
,I/jxcore-log( 4023): 2015-11-23T11:36:51.646Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 4023): 
,I/BtToRequestSocket( 4023): rin ended ---------------------------;
,I/jxcore-log( 4023): 2015-11-23T11:36:51.806Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:36:51.839Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:36:51.918Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:36:51.956Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:36:52.006Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:36:52.079Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:36:52.126Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 4023): 
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/jxcore-log( 4023): 2015-11-23T11:36:52.251Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:36:52.312Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:36:52.439Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:36:52.440Z SendDataConnector.js: got all data for this round
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:36:52.459Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:36:52.459Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4023): 
,I/BtConnectorHelper( 4023): Disconnect outgoing peer: F8:CF:C5:D9:E5:61
I/BtToSocketBase( 4023): Stop ReceivingThread
I/BtToSocketBase( 4023): Stop SendingThread
I/BtToSocketBase( 4023): Close local in
,I/BtToSocketBase( 4023): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 4023): Close LocalOutputStream
I/BtToSocketBase( 4023): Close localHostSocket
I/BtToSocketBase( 4023): Close bt in
,I/BtToSocketBase( 4023): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 4023): Close bt out
I/BtToSocketBase( 4023): Close bt socket
,I/BtToRequestSocket( 4023): Close server socket
,I/jxcore-log( 4023): 2015-11-23T11:36:52.467Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): ---- round done--------
I/jxcore-log( 4023): 
I/jxcore-log( 4023): do fake peer & start
I/jxcore-log( 4023): 
I/jxcore-log( 4023): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:36:52.470Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 4023): 
I/jxcore-log( 4023): 2015-11-23T11:36:52.470Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:36:52.471Z SendDataConnector.js: do connect now
I/jxcore-log( 4023): 
,I/        ( 4023): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 4023): Connecting to null, at 34:FC:EF:11:B1:66
,I/chromium( 4023): [INFO:CONSOLE(63)] "logCallback round[0] time: 7158 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 1772): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/BTConnectToThread( 4023): Starting to connect
,W/BluetoothAdapter( 4023): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1772): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 4023): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[132]}
,I/wpa_supplicant( 1173): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-41
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 49 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_add
,D/MDMCTBK (  276): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_add
I/wpa_supplicant( 1173): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-42
D/MDMCTBK (  276): reply_len: 49 reply is = <3>P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_add
,D/MDMCTBK (  276): Event received = P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_add
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1023):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1023):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-2ms what=147477 obj=Device: Note3-1
D/WifiP2pService( 1023):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=147477 obj=Device: Note3-1
D/WifiP2pService( 1023):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f20836c rs_disc_pending=0
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f20836c rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f208528 rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,I/wpa_supplicant( 1173): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-42
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 9e:93:4e:
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 2 9e:93:4e:
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 49 reply is = <3>P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_add
,D/MDMCTBK (  276): Event received = P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_add
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: Android_d8c3
D/WifiP2pService( 1023):  deviceAddress: 02:ee:bd:dd:33:d2
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_d8c3
D/WifiP2pService( 1023):  deviceAddress: 02:ee:bd:dd:33:d2
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4092): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,I/BluetoothBondStateMachine( 1772): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
,I/BluetoothBondStateMachine( 1772): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 1772): Entering PendingCommandState State
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4092): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,E/bt-btif ( 1772): services_to_search = 3fffffff
,E/bt-btif ( 1772): ****************search UUID = 1200***********
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,E/bt-btif ( 1772): services_to_search = 3ffffffe
,E/bt-btif ( 1772): ****************search UUID = 0100***********
,W/bt-btif ( 1772): invalid rfc slot id: 7
,I/BTConnectToThread( 4023): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 4023): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 4023): 2015-11-23T11:36:57.124Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:36:57.126Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:36:57.129Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4023): 
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,W/bt-btif ( 1772): btif_dm_search_services_evt:SDP failed after bonding re-attempting
,E/bt-btif ( 1772): services_to_search = 3fffffff
,E/bt-btif ( 1772): ****************search UUID = 1200***********
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:
,D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:
,E/bt-btif ( 1772): services_to_search = 3ffffffe
,E/bt-btif ( 1772): ****************search UUID = 0100***********
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,E/bt-btif ( 1772): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1772): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1772): Index: 4 uuid:0000110e-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1772): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1772): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 1772): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
,D/BluetoothAdapterProperties( 1772): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 1772): Failed to remove device: 34:FC:EF:11:B1:66
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 1772): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 1772): StableState(): Entering Off State
,D/BluetoothMetrics( 1772): btclass1f00
,D/Checkin ( 1772): publish the event [tag = MOT_BT event name = PAIRING]
,I/CE-BTReceiver( 4092): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 c0:ff:d4:d3
,D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 3 c0:ff:d4:d3
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,V/AlarmManager( 1023): sending alarm Alarm{42726758 type 3 android}
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/jxcore-log( 4023): 2015-11-23T11:37:02.145Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:02.147Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 4023): 
,I/wpa_supplicant( 1173): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-15
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 49 reply is = <3>P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_add
,D/MDMCTBK (  276): Event received = P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_add
I/wpa_supplicant( 1173): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 level=-30
D/MDMCTBK (  276): reply_len: 49 reply is = <3>P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_add
D/MDMCTBK (  276): Event received = P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_add
I/wpa_supplicant( 1173): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-33
D/MDMCTBK (  276): reply_len: 49 reply is = <3>P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_add
,D/MDMCTBK (  276): Event received = P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_add,
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -15 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -15 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-2ms what=147477 obj=Device: XT1072_23d5
D/WifiP2pService( 1023):  deviceAddress: 44:80:eb:7b:5a:07
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 33
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=147477 obj=Device: XT1072_23d5
D/WifiP2pService( 1023):  deviceAddress: 44:80:eb:7b:5a:07
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 33
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-5ms what=147477 obj=Device: Android_50a5
D/WifiP2pService( 1023):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-6ms what=147477 obj=Device: Android_50a5
D/WifiP2pService( 1023):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP fa:cf:c5:d9:e5:
,D/MDMCTBK (  276): Event received = P2P-SERV-DISC-RESP fa:cf:c5:d9:e5:
D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:fa:cf:c5:d9:e5:62 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8557","ra":"F8:CF:C5:D9:E5:61"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:fa:cf:c5:d9:e5:62 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8557","ra":"F8:CF:C5:D9:E5:61"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState receive service response
I/        ( 4023): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8557","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 4023): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8557","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT8557, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 4023): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT8557, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 44:80:eb:7b:5a:
,D/MDMCTBK (  276): Event received = P2P-SERV-DISC-RESP 44:80:eb:7b:5a:
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5877","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5877","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState receive service response
I/        ( 4023): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5877","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 4023): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5877","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT5877, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 4023): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT5877, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1772): info:x10
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/        ( 1772): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,I/CE-BTReceiver( 4092): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 1772): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
,I/BluetoothBondStateMachine( 1772): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 1772): Entering PendingCommandState State
,I/CE-BTReceiver( 4092): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 1772): services_to_search = 3fffffff
,E/bt-btif ( 1772): ****************search UUID = 1200***********
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,E/bt-btif ( 1772): services_to_search = 3ffffffe
,E/bt-btif ( 1772): ****************search UUID = 0100***********
,W/bt-btif ( 1772): new conn_srvc id:26, app_id:255
,W/bt-btif ( 1772): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 1772): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 4023): we got incoming connection
,I/BTHandshakeSocketThread( 4023): Creating BTHandshakeSocketThread
,I/BTListenerThread( 4023): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread started
,I/BTListenerThread( 4023): got MESSAGE_READ 83 bytes.
,I/BTListenerThread( 4023): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT5957","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 4023): MESSAGE_WRITE 81 bytes.
I/HS      ( 4023): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT5957
,I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 4023): Starting the connected thread incoming : true, samsung-SM-A300FU_PT5957
I/BtToSocketBase( 4023): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4023): Creating BTConnectedThread
I/BtConnectorHelper( 4023): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 4023): --DoOneRunRound started
,I/jxcore-log( 4023): 2015-11-23T11:37:03.476Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4023): 
,I/BtToRequestSocket( 4023): LocalHost address: localhost/127.0.0.1, port: 43200
,I/BtToRequestSocket( 4023): --DoOneRunRound ended
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,E/bt-btif ( 1772): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1772): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb,
E/bt-btif ( 1772): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1772): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1772): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 1772): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 1772): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 1772): Failed to remove device: 08:EC:A9:50:76:27
,I/CE-BTReceiver( 4092): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 1772): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 1772): StableState(): Entering Off State
,D/BluetoothMetrics( 1772): btclass5a020c
,D/Checkin ( 1772): publish the event [tag = MOT_BT event name = PAIRING]
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/jxcore-log( 4023): 2015-11-23T11:37:03.899Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:03.907Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:03.916Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:03.919Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:03.980Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:04.022Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:04.035Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:04.066Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 4023): 
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/jxcore-log( 4023): 2015-11-23T11:37:04.129Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:04.144Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:04.173Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:04.180Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:04.216Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:04.227Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:04.272Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:04.280Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:04.317Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:04.322Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:04.330Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:04.337Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:04.374Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:04.377Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:04.383Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:04.470Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:04.506Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:04.516Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:04.545Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 4023): 
,W/bt-btif ( 1772): invalid rfc slot id: 5
,I/BtToSocketBase( 4023): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 4023): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 4023): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT5957
,I/BtToSocketBase( 4023): Stop ReceivingThread
I/BtToSocketBase( 4023): Stop SendingThread
,I/BtToSocketBase( 4023): Close local in
,W/bt-rfcomm( 1772): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
,W/bt-rfcomm( 1772): RFCOMM_DisconnectInd LCID:0x40
,I/BtToSocketBase( 4023): Close LocalOutputStream
,I/BtToSocketBase( 4023): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4023): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 4023): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT5957
I/BtToSocketBase( 4023): Close localHostSocket
,I/BtToSocketBase( 4023): Close bt in
I/BtToSocketBase( 4023): Close bt out
,I/BtToSocketBase( 4023): Close bt socket
,I/BtToSocketBase( 4023): Close bt in
I/BtToSocketBase( 4023): Close bt out
,I/BtToSocketBase( 4023): Close bt socket
,I/jxcore-log( 4023): 2015-11-23T11:37:04.631Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4023): 
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2086e4 rs_disc_pending=0
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 ea:50:8b:de
,D/MDMCTBK (  276): Event received = P2P-SERV-DISC-REQ 2412 ea:50:8b:de
,I/jxcore-log( 4023): 2015-11-23T11:37:07.158Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:07.159Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:07.160Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:07.162Z SendDataConnector.js: do connect now
I/jxcore-log( 4023): 
,I/        ( 4023): Selected device address: 34:FC:EF:11:B1:66, name: Nexus 5
,I/        ( 4023): Connecting to Nexus 5, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 4023): Starting to connect
,W/BluetoothAdapter( 4023): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1772): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 4023): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[134]}
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2086e4 rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 c0:ff:d4:
,D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 3 c0:ff:d4:
,D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 c0:ff:d4:d3
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 4 c0:ff:d4:d3
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,I/CE-BTReceiver( 4092): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f208528 rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4092): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,W/bt-l2cap( 1772): L2CAP - con rsp - bad ID. Exp: 5 Got: 3
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139307 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=139307 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState clear service request
,I/        ( 4023): Cleared service requests
D/WifiP2pService( 1023): InactiveState{ when=-13ms what=139265 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-13ms what=139265 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 4023): Started peer discovery
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f208528 rs_disc_pending=0
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1772): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 4023): Starting to Handshake
,W/bt-btif ( 1772): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 1772): bta_dm_pm_ssr:2, lat:1200
,I/BTHandshakeSocketThread( 4023): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 4023): MESSAGE_WRITE 81 bytes.
,I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread started
,I/BTConnectToThread( 4023): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 4023): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT3069"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 4023): HandshakeOk : LGE-Nexus 5_PT3069
,I/HS      ( 4023): Hand Shake finished outgoing for : LGE-Nexus 5_PT3069
,I/BtConnectorHelper( 4023): Starting the connected thread incoming : false, LGE-Nexus 5_PT3069
,I/BtToSocketBase( 4023): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 4023): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 4023): mHTTPPort  set to : 56968
,I/BtConnectorHelper( 4023): Request socket is using : 56968
,I/BtToRequestSocket( 4023): Now accepting connections
,I/wpa_supplicant( 1173): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-26
D/MDMCTBK (  276): reply_len: 49 reply is = <3>P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_add
,D/MDMCTBK (  276): Event received = P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_add
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
I/wpa_supplicant( 1173): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-37
D/MDMCTBK (  276): reply_len: 49 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_add
,D/MDMCTBK (  276): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_add,
I/wpa_supplicant( 1173): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-41
D/MDMCTBK (  276): reply_len: 49 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_add
,D/MDMCTBK (  276): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_add,
,D/WifiP2pService( 1023): InactiveState{ when=-17ms what=147477 obj=Device: G3-1
D/WifiP2pService( 1023):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-18ms what=147477 obj=Device: G3-1
D/WifiP2pService( 1023):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 4023): Found 12 peers.
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -37 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 4023): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 4023): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4023): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 4023): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 4023): Peer(5): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 4023): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 4023): Peer(7): Android_50a5 fa:cf:c5:d9:e5:62
,I/SS      ( 4023): Peer(8): XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -37 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 4023): Peer(9): Note4-1 92:b6:86:43:73:1c
I/SS      ( 4023): Peer(10): DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/SS      ( 4023): Peer(11): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 4023): Peer(12): Note3-1 ea:50:8b:de:28:a3
D/WifiP2pService( 1023): InactiveState{ when=-5ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1023):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-6ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1023):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-6ms what=139301 arg2=11 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-6ms what=139301 arg2=11 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState add service request
D/WifiP2pManager( 4023): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4023): Added service request
,I/BtConnectorHelper( 4023): Calling ConnectionStatusUpdate with port :56968
,I/jxcore-log( 4023): 2015-11-23T11:37:10.108Z SendDataConnector.js: CLIENT connected to 56968, error: null
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:10.109Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 4023): 
,I/BtToRequestSocket( 4023): incoming data from: /127.0.0.1, port: 56968
,I/BtToRequestSocket( 4023): Set local streams
,I/jxcore-log( 4023): 2015-11-23T11:37:10.123Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 4023): 
,I/BtToRequestSocket( 4023): rin ended ---------------------------;
,I/wpa_supplicant( 1173): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-36
D/MDMCTBK (  276): reply_len: 49 reply is = <3>P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_add
,D/MDMCTBK (  276): Event received = P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_add
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1023):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1023):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139310 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=139310 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState discover services
,I/        ( 4023): Started service discovery
,I/jxcore-log( 4023): 2015-11-23T11:37:11.289Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:11.410Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:11.416Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:11.480Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:11.590Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 4023): 
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 4023): 2015-11-23T11:37:11.897Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:12.022Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 4023): 
,I/wpa_supplicant( 1173): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-23
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 49 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_add
,D/MDMCTBK (  276): Event received = P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_add
,D/WifiP2pService( 1023): InactiveState{ when=-3ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-4ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 4023): 2015-11-23T11:37:12.184Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:12.185Z SendDataConnector.js: got all data for this round
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:12.204Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:12.204Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4023): 
,I/BtConnectorHelper( 4023): Disconnect outgoing peer: 34:FC:EF:11:B1:66
,I/BtToSocketBase( 4023): Stop ReceivingThread
,I/BtToSocketBase( 4023): Stop SendingThread
,I/BtToSocketBase( 4023): Close local in
,I/BtToSocketBase( 4023): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 4023): Close LocalOutputStream
I/BtToSocketBase( 4023): Close localHostSocket
I/BtToSocketBase( 4023): Close bt in
,I/BtToSocketBase( 4023): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 4023): Close bt out
I/BtToSocketBase( 4023): Close bt socket
,I/BtToRequestSocket( 4023): Close server socket
,I/jxcore-log( 4023): 2015-11-23T11:37:12.218Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): ---- round done--------
I/jxcore-log( 4023): 
I/jxcore-log( 4023): do fake peer & start
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 4023): 
I/jxcore-log( 4023): 2015-11-23T11:37:12.221Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:12.221Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:12.222Z SendDataConnector.js: do connect now
I/jxcore-log( 4023): 
,I/        ( 4023): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 4023): Connecting to null, at 44:80:EB:7B:5A:05
,I/chromium( 4023): [INFO:CONSOLE(63)] "logCallback round[0] time: 19716 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 4023): Starting to connect
,W/BluetoothAdapter( 4023): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 1772): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/BluetoothSocket( 4023): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[135]}
,I/wpa_supplicant( 1173): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-37
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 49 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_add
,D/MDMCTBK (  276): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_add
,D/WifiP2pService( 1023): InactiveState{ when=-8ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -37 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-9ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -37 target=com.android.internal.util.StateMachine$SmHandler }
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f208528 rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1772): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 c0:ff:d4:
,D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 4 c0:ff:d4:
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4092): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 c0:ff:d4:d3
,D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 5 c0:ff:d4:d3
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 c0:ff:d4:
,D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 5 c0:ff:d4:
,D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 c0:ff:d4:d3
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-ADDED 6 c0:ff:d4:d3
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 1000 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/TCMD    (  458): NL - Read 68 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
I/wpa_supplicant( 1173): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
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
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  276): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
,I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=0 stat
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE id=0 stat
D/TCMD    (  458): NL - Read 68 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/Tethering( 1023): InitialState.processMessage what=4
D/WifiStateMachine( 1023): handleMessage: E msg.what=147460
D/WifiStateMachine( 1023): processMsg: ConnectedState
D/WifiStateMachine( 1023): processMsg: L2ConnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): Network connection lost
,D/WifiStateMachine( 1023): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1023): setSuspendOptimizationsNative: 1 true
,V/ConnectivityService( 1023): WiFi NOT Tethered!
D/Tethering( 1023): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiP2pService( 1023): InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  274): Clearing all IP addresses on wlan0
D/TCMD    (  458): NL - Read 60 bytes from update socket.
D/TCMD    (  458): NL - ignore NL message, type = 21
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiStateMachine( 1023): addressRemoved: 192.168.1.123/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1023): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1023): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1023): connected time updated 429812
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1023): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1023): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1023): Attempting to switch to mobile
D/ConnectivityService( 1023): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1023): Attempting to switch to ETHERNET
,I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,I/SBar.NetworkController( 1085): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1085): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/ConnectivityService( 1023): resetConnections(wlan0, 3)
D/NetUtils( 1023): android_net_utils_resetConnections in env=0x5ff8b688 clazz=0x60c00001 iface=wlan0 mask=0x3
D/WifiStateMachine( 1023): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1023): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1023): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1023): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1023): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1023): Stopping DHCP and clearing IP
D/WifiStateMachine( 1023): setSuspendOptimizationsNative: 1 true
D/Checkin ( 1023): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
V/NativeCrypto( 1340): Read error: ssl=0x62cd8e78: I/O error during system call, Connection timed out
V/NativeCrypto( 1340): SSL shutdown failed: ssl=0x62cd8e78: I/O error during system call, Broken pipe
,I/jxcore-log( 4023): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): The Coordinator has disconnected!
I/jxcore-log( 4023): 
,D/WifiP2pService( 1023): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  274): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1023): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1023): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1023): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1023): invokeEnterMethods: DisconnectedState
D/Checkin ( 1023): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=147462
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131101
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): processMsg: DriverStartedState
D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131216
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): processMsg: DriverStartedState
D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131216
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): processMsg: DriverStartedState
D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
,D/Nat464Xlat( 1023): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityService( 1023): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1285): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1285): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1285): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1023): Attempting to switch to mobile
D/ConnectivityService( 1023): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1023): Attempting to switch to ETHERNET
D/Nat464Xlat( 1023): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityService( 1023): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1285): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1285): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1285): onReceive() - done, currentInetCondition=0
,D/dalvikvm( 1023): GC_CONCURRENT freed 1899K, 65% free 18156K/50444K, paused 4ms+10ms, total 96ms
,D/dalvikvm( 1023): WAIT_FOR_CONCURRENT_GC blocked 50ms
,D/MDMCTBK (  276): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE id=-1 sta
,D/WifiStateMachine( 1023): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1023): processMsg: DisconnectedState
,D/WifiStateMachine( 1023): setDetailed state, old =DISCONNECTED and new state=SCANNING
,D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): handleMessage: X
,I/jxcore-log( 4023): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): printNetworkInfo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): found interfaceName: lo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): Turning Wifi off
I/jxcore-log( 4023): 
D/WifiService( 1023): setWifiEnabled: false pid=4023, uid=10397
E/WifiService( 1023): Invoking mWifiStateMachine.setWifiEnabled
,W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1269): Active network info is not available
E/XTCC-3.0.0.2(  580): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  580): [WwanPosMgr] handleConnectivtyStatusChange failed
,W/Settings( 1244): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/XTCC-3.0.0.2(  580): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  580): [CSMgr] handleConnectivtyStatusChange failed
,D/WifiStateMachine( 1023): handleMessage: E msg.what=131084
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): processMsg: DriverStartedState
,D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1023): transitionTo: destState=WaitForP2pDisableState
D/WifiStateMachine( 1023): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1023): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
,D/WifiStateMachine( 1023): invokeExitMethods: DisconnectedState
,W/wpa_supplicant( 1173): wlan0: Failed to initiate AP scan
D/MDMCTBK (  276): reply_len: 42 reply is = IFNAME=wlan0 <4>Failed to initiate AP scan
,D/MDMCTBK (  276): Event received = Failed to initiate AP scan
,D/WifiStateMachine( 1023): invokeExitMethods: ConnectModeState
,I/jxcore-log( 4023): Turning Wifi back on
I/jxcore-log( 4023): 
,D/WifiStateMachine( 1023): invokeExitMethods: DriverStartedState
D/WifiService( 1023): setWifiEnabled: true pid=4023, uid=10397
,E/WifiService( 1023): Invoking mWifiStateMachine.setWifiEnabled
E/WifiStateMachine( 1023): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1023): moveTempStackToStateStack: i=0,j=2
,D/WifiStateMachine( 1023): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
,D/WifiStateMachine( 1023): invokeEnterMethods: WaitForP2pDisableState
D/WifiP2pService( 1023): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pDisablingState
D/WifiP2pService( 1023): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): p2p socket connection lost
,D/WifiP2pService( 1023): P2pDisabledState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131205
D/WifiStateMachine( 1023): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1023): transitionTo: destState=SupplicantStoppingState
D/WifiStateMachine( 1023): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1023): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1023): invokeExitMethods: WaitForP2pDisableState
D/WifiStateMachine( 1023): invokeExitMethods: SupplicantStartedState
D/WifiStateMachine( 1023): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1023): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/WifiStateMachine( 1023): invokeEnterMethods: SupplicantStoppingState
D/WifiStateMachine( 1023): Stopping DHCP and clearing IP
D/WifiStateMachine( 1023): setSuspendOptimizationsNative: 1 true
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  276): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE i
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
,D/WifiController( 1023): WifiController msg { when=-1ms what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 460ms
,I/jxcore-log( 4023): toggleWiFi finished
I/jxcore-log( 4023): 
,W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
,I/jxcore-log( 4023): ReconnectWifiAP finished
I/jxcore-log( 4023): 
,D/WifiP2pService( 1023): P2pDisabledState{ when=-32ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=-32ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/WB      ( 4023): Wifi is DISABLED !!
I/        ( 4023): Stoping All
I/        ( 4023): Stopping services
I/        ( 4023): Stopping services
,W/XTWiFiOS( 1269): Active network info is not available
D/WifiP2pService( 1023): P2pDisabledState{ when=0 what=139298 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=0 what=139298 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
E/XTCC-3.0.0.2(  580): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  580): [WwanPosMgr] handleConnectivtyStatusChange failed
D/WifiP2pService( 1023): P2pDisabledState{ when=0 what=139307 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): DefaultState{ when=0 what=139307 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pDisabledState{ when=-1ms what=139268 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=-1ms what=139268 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 4023): Stop Bluetooth
I/        ( 4023): Stop Bluetooth
I/BTListenerThread( 4023): Stopped
E/bt-btif ( 1772): bta_jv_rfcomm_stop_server
I/BTConnectToThread( 4023): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btif ( 1772): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:10, channel:-1
I/chromium( 4023): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
I/        ( 4023): Clearing local services failed, error code 2
I/        ( 4023): Clearing service requests failed, error code 2
I/        ( 4023): Stopping peer discovery failed, error code 2
I/CONNEC  ( 4023): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 4023): 2015-11-23T11:37:31.700Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 4023): 
I/jxcore-log( 4023): 2015-11-23T11:37:31.701Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 4023): 
I/jxcore-log( 4023): 2015-11-23T11:37:31.701Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4023): 
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  274): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1023): setDetailed state, old =SCANNING and new state=DISCONNECTED
I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
E/XTCC-3.0.0.2(  580): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  580): [CSMgr] handleConnectivtyStatusChange failed
D/Checkin ( 1023): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1023): stopping supplicant
I/wpa_supplicant( 1173): P2P-FIND-STOPPED 
I/wpa_supplicant( 1173): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1173): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1173): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1173): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1173): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 1173): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 1173): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1173): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1173): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1173): P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5
I/wpa_supplicant( 1173): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1173): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1173): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 1173): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
D/MDMCTBK (  276): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  276): Event received = P2P-FIND-STOPPED 
D/MDMCTBK (  276): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  276): Event received = P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  276): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=02:9a:02
D/MDMCTBK (  276): Event received = P2P-DEVICE-LOST p2p_dev_addr=02:9a:02
D/MDMCTBK (  276): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5
D/MDMCTBK (  276): Event received = P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5
D/MDMCTBK (  276): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=44:80:eb
D/MDMCTBK (  276): Event received = P2P-DEVICE-LOST p2p_dev_addr=44:80:eb
D/MDMCTBK (  276): reply_len: 40 reply is = <3>P,2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6
D/MDMCTBK (  276): Event received = P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6
D/MDMCTBK (  276): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd
D/MDMCTBK (  276): Event received = P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd
D/MDMCTBK (  276): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b
D/MDMCTBK (  276): Event received = P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b
D/MDMCTBK (  276): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  276): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  276): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f
D/MDMCTBK (  276): Event received = P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f
D/MDMCTBK (  276): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
D/MDMCTBK (  276): Event received = P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
D/MDMCTBK (  276): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=82:01:84
D/MDMCTBK (  276): Event received = P2P-DEVICE-LOST p2p_dev_addr=82:01:84
D/MDMCTBK (  276): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  276): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  276): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  276): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  276): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  276): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  276): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1023): setWifiState: disabling
I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
W/XTWiFiOS( 1269): Active network info is not available
E/XTCC-3.0.0.2(  580): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  580): [WwanPosMgr] handleConnectivtyStatusChange failed
I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=false Wifi=(none) Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
E/XTCC-3.0.0.2(  580): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  580): [CSMgr] handleConnectivtyStatusChange failed
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=147461
D/WifiStateMachine( 1023): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131146
D/WifiStateMachine( 1023): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131145
D/WifiStateMachine( 1023): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131146
D/WifiStateMachine( 1023): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=196614
D/WifiStateMachine( 1023): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=147462
D/WifiStateMachine( 1023): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
I/ActivityManager( 1023): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=4299 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/dalvikvm(  279): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+2ms, total 21ms
I/wpa_supplicant( 1173): eap_proxy Deinitialzed
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  276): Event received = CTRL-EVENT-BSS-REMOVED 0
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms
D/BluetoothManagerService( 1023): Message: 20
D/BluetoothManagerService( 1023): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42963c38:true
D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
D/LocalBluetoothProfileManager( 4299): Adding local A2DP profile
D/BluetoothManagerService( 1023): Message: 30
D/dalvikvm( 1023): GC_EXPLICIT freed 397K, 65% free 17918K/50444K, paused 16ms+11ms, total 185ms
W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1244): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1244): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/LocalBluetoothProfileManager( 4299): Adding local HEADSET profile
,W/Settings( 1244): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/BluetoothManagerService( 1023): Message: 30
,W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
,D/BluetoothManagerService( 1023): Message: 30
,W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
,D/BluetoothManagerService( 1023): Message: 30
,W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 4299): Adding local MAP profile
D/BluetoothMap( 4299): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1023): Message: 30
,W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/BluetoothManagerService( 1023): Message: 30
,W/ContextImpl( 4299): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 4299): LocalBluetoothProfileManager construction complete
D/TCMD    (  458): NL - Read 1000 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
I/wpa_supplicant( 1173): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  276): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  276): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  276):  Wpa Supplicant Exiting !!
D/MDMCTBK (  276): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  276): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  276): wifi_close_sockets: Exit
I/wpa_supplicant( 1173): CTRL_IFACE monitor[0]: 2 - No such file or directory
D/WifiStateMachine( 1023): handleMessage: E msg.what=147458
D/WifiStateMachine( 1023): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1023): Supplicant connection lost
D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/ActivityManager( 1023): Killing 3487:android.process.acore/u0a10 (adj 15): empty #9
D/BluetoothA2dp( 4299): Proxy object connected
,D/A2dpProfile( 4299): Bluetooth service connected
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/BluetoothHeadset( 4299): Proxy object connected
D/HeadsetProfile( 4299): Bluetooth service connected
D/BluetoothInputDevice( 4299): Proxy object connected
D/HidProfile( 4299): Bluetooth service connected
D/BluetoothPan( 4299): BluetoothPAN Proxy object connected
D/PanProfile( 4299): Bluetooth service connected
D/BluetoothMap( 4299): Proxy object connected
D/MapProfile( 4299): Bluetooth service connected
D/BluetoothMap( 4299): getConnectedDevices()
D/BluetoothPbap( 4299): Proxy object connected
D/PbapServerProfile( 4299): Bluetooth service connected
,D/WifiStateMachine( 1023): setWifiState: disabled
,D/WifiStateMachine( 1023): transitionTo: destState=InitialState
D/WifiStateMachine( 1023): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1023): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1023): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine( 1023): moveTempStackToStateStack: i=0,j=1
I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1023): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
,D/WifiStateMachine( 1023): invokeEnterMethods: InitialState
,W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1269): Active network info is not available
E/XTCC-3.0.0.2(  580): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  580): [WwanPosMgr] handleConnectivtyStatusChange failed
E/XTCC-3.0.0.2(  580): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  580): [CSMgr] handleConnectivtyStatusChange failed
,W/Settings( 1222): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiService( 1023): New client listening to asynchronous messages
,I/rmt_storage(  417): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb721f1d0
I/rmt_storage(  417): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  417): wakelock acquired: 1, error no: 42
,I/rmt_storage(  417): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1222512920)
,I/rmt_storage(  417): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  417): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  417): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1222512920) wakelock released: 1, error no: 0
I/rmt_storage(  417): 
,I/rmt_storage(  417): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb721f1d0
,D/WifiController( 1023): DEFERRED_TOGGLE handled
,D/WifiStateMachine( 1023): setting operational mode to 1
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/NetlinkEvent(  274): Unexpected netlink message. type=0x11
W/Netd    (  274): No subsystem found in netlink event
D/TCMD    (  458): NL - Read 444 bytes from update socket.
D/TCMD    (  458): NL - ignore NL message, type = 17
D/TCMD    (  458): Listening for incoming client connection request
I/MDMCTBK (  276): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  276): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  276): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  276): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  276): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/TCMD    (  458): NL - Read 1000 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/NetlinkEvent(  274): Unexpected netlink message. type=0x11
W/Netd    (  274): No subsystem found in netlink event
D/TCMD    (  458): NL - Read 444 bytes from update socket.
D/TCMD    (  458): NL - ignore NL message, type = 17
D/TCMD    (  458): Listening for incoming client connection request
I/MDMCTBK (  276): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  276): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  276): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  276): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  276): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  276): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131208
D/WifiStateMachine( 1023): processMsg: InitialState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131208
D/WifiStateMachine( 1023): processMsg: InitialState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131208
D/WifiStateMachine( 1023): processMsg: InitialState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131083
,D/WifiStateMachine( 1023): processMsg: InitialState
,I/MDMCTBK (  276): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  276): NetlinkHandler, interfaceAdded
I/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
E/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  276): , Wifi = 0
I/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
,I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
,E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Tethering( 1023): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1023): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering( 1023): InitialState.processMessage what=4
,D/Tethering( 1023): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/Tethering( 1023): sendTetherStateChangedBroadcast 0, 0, 0
D/TCMD    (  458): NL - Read 1004 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/MDMCTBK (  276): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  276): NetlinkHandler, interfaceAdded
I/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
E/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  276): , Wifi = 0
I/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
,I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
,E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/TCMD    (  458): NL - Read 1004 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/QsoftapCmd(  274): Got softap fwreload command we are passing on
,D/SoftapController(  274): Softap fwReload - Ok
,D/CommandListener(  274): Setting iface cfg
,D/CommandListener(  274): Trying to bring down wlan0
,E/WifiHW  ( 1023): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
,E/WifiHW  ( 1023): ctrl_interface != /data/misc/wifi/sockets
,D/WifiStateMachine( 1023): setWifiState: enabling
,D/WifiStateMachine( 1023): Supplicant start successful
,D/WifiMonitor( 1023): startMonitoring(wlan0) with mConnected = false
,I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1269): Active network info is not available
E/XTCC-3.0.0.2(  580): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  580): [WwanPosMgr] handleConnectivtyStatusChange failed
,E/XTCC-3.0.0.2(  580): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  580): [CSMgr] handleConnectivtyStatusChange failed
,I/wpa_supplicant( 4340): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 4340): rfkill: Cannot open RFKILL control device
D/TCMD    (  458): NL - Read 1000 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/TCMD    (  458): NL - Read 1000 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,E/Diag_Lib( 4340): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 4340): Setting internal use port to rmnet0
,E/wpa_supplicant( 4340): baseband property is set to [msm]
,E/wpa_supplicant( 4340):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 4340): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 4340): card_info[i].card_state: 0x2
E/wpa_supplicant( 4340): card_info[i].error_code: 0x3
E/wpa_supplicant( 4340): SIM/USIM not ready
,E/wpa_supplicant( 4340): Error while reading SIM card status
,E/wpa_supplicant( 4340): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 4340): card_info[i].card_state: 0x2
E/wpa_supplicant( 4340): card_info[i].error_code: 0x3
E/wpa_supplicant( 4340): SIM/USIM not ready
,I/wpa_supplicant( 4340): eap_proxy: Card not ready
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/wpa_supplicant( 4340): Long line in configuration file truncated
,I/wpa_supplicant( 4340): rfkill: Cannot open RFKILL control device
D/TCMD    (  458): NL - Read 1000 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,E/wpa_supplicant( 4340): COUNTRY Code Recived
,E/wpa_supplicant( 4340): COUNTRY Code Recived -COUNTRY PL
,E/wpa_supplicant( 4340): baseband property is set to [msm]
,E/wpa_supplicant( 4340):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 4340): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 4340): card_info[i].card_state: 0x2
,E/wpa_supplicant( 4340): card_info[i].error_code: 0x3
E/wpa_supplicant( 4340): SIM/USIM not ready
,E/wpa_supplicant( 4340): Error while reading SIM card status
,E/wpa_supplicant( 4340): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 4340): card_info[i].card_state: 0x2
E/wpa_supplicant( 4340): card_info[i].error_code: 0x3
E/wpa_supplicant( 4340): SIM/USIM not ready
,I/wpa_supplicant( 4340): eap_proxy: Card not ready
D/WifiStateMachine( 1023): transitionTo: destState=SupplicantStartingState
D/WifiStateMachine( 1023): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1023): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1023): invokeExitMethods: InitialState
D/WifiStateMachine( 1023): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1023): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine( 1023): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131144
D/WifiStateMachine( 1023): processMsg: SupplicantStartingState
D/WifiStateMachine( 1023): deferMessage: msg=131144
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131085
D/WifiStateMachine( 1023): processMsg: SupplicantStartingState
D/WifiStateMachine( 1023): deferMessage: msg=131085
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131149
D/WifiStateMachine( 1023): processMsg: SupplicantStartingState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): setSuspendOptimizations: 2 true
D/WifiStateMachine( 1023): mSuspendOptNeedsDisabled 0
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131101
D/WifiStateMachine( 1023): processMsg: SupplicantStartingState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131101
D/WifiStateMachine( 1023): processMsg: SupplicantStartingState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=147457
D/WifiStateMachine( 1023): processMsg: SupplicantStartingState
D/WifiStateMachine( 1023): Supplicant connection established
,D/WifiStateMachine( 1023): setWifiState: enabled
,I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
,D/WifiConfigStore( 1023): Loading config and enabling all networks
,W/XTWiFiOS( 1269): Active network info is not available
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
E/XTCC-3.0.0.2(  580): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  580): [WwanPosMgr] handleConnectivtyStatusChange failed
,I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,E/WifiConfigStore( 1023): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,E/wpa_supplicant( 4340): COUNTRY Code Recived -COUNTRY PL
,D/WifiStateMachine( 1023): transitionTo: destState=DriverStartedState
D/WifiStateMachine( 1023): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1023): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
,D/WifiStateMachine( 1023): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine( 1023): moveTempStackToStateStack: i=1,j=1
D/WifiStateMachine( 1023): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1023): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
,D/WifiStateMachine( 1023): invokeEnterMethods: SupplicantStartedState
,D/WifiStateMachine( 1023): invokeEnterMethods: DriverStartedState
,D/WifiStateMachine( 1023): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
E/XTCC-3.0.0.2(  580): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  580): [CSMgr] handleConnectivtyStatusChange failed
E/wpa_supplicant( 4340): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 4340): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/WifiStateMachine( 1023): Attempting to reconnect to wifi network ..
,D/WifiStateMachine( 1023): transitionTo: destState=DisconnectedState
,D/WifiP2pService( 1023): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1023): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine( 1023): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine( 1023): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1023): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
D/WifiStateMachine( 1023): moveTempStackToStateStack: i=1,j=3
D/WifiStateMachine( 1023): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1023): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
D/WifiStateMachine( 1023): invokeEnterMethods: ConnectModeState
D/WifiStateMachine( 1023): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131144
,D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131085
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): processMsg: DriverStartedState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131152
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): processMsg: DriverStartedState
,D/WifiStateMachine( 1023): set country code PL
D/CommandListener(  274): Setting iface cfg
,D/CommandListener(  274): Trying to bring up p2p0
E/wpa_supplicant( 4340): COUNTRY Code Recived
,E/wpa_supplicant( 4340): COUNTRY Code Recived
,D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131162
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): processMsg: DriverStartedState
,D/WifiStateMachine( 1023): set frequency band 2
,D/WifiMonitor( 1023): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 1023): P2pEnablingState
D/WifiP2pService( 1023): P2pEnablingState{ when=-3ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnablingState{ when=-3ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): DefaultState{ when=-3ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2p socket connection successful
D/WifiP2pService( 1023): P2pEnabledState
,D/WifiP2pService( 1023): sending p2p connection changed broadcast
I/WB      ( 4023): Wifi is now enabled !
I/        ( 4023): Stoping All
I/        ( 4023): Stopping services
I/        ( 4023): Stop Bluetooth
I/        ( 4023): Starting All
I/        ( 4023): Stopping services
I/        ( 4023): Starting services address: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6969"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@425acfe8
I/        ( 4023): Stopping services
I/        ( 4023): Starting services address: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6969"}
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=147462
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131167
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): processMsg: DriverStartedState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=147462
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=143371
D/WifiStateMachine( 1023): processMsg: DisconnectedState
I/        ( 4023): Add local service :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6969"}, length : 81
D/WifiStateMachine( 1023): processMsg: ConnectModeState
I/        ( 4023): peerDiscoveryTimer timeout value:5956
D/WifiStateMachine( 1023): processMsg: DriverStartedState
D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
I/        ( 4023): Stop Bluetooth
I/        ( 4023): StartBluetooth listener
I/        ( 4023): StartBluetooth listener
D/Tethering( 1023): MasterInitialState.processMessage what=3
I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
D/CaptivePortalTracker( 1023): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1023): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/PollingManager( 1549): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: null, inetCondition= 0
W/XTWiFiOS( 1269): Active network info is not available
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,I/ActivityManager( 1023): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4354 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/BluetoothManagerService( 1023): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 4023): getBluetoothService() called with no BluetoothManagerCallback
,D/WifiP2pService( 1023): DeviceAddress: f4:f1:e1:5c:43:c8
,D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
,D/WifiP2pService( 1023): MCC mode enabled 0
D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: null, inetCondition= 0
,E/ActivityThread( 1549): Failed to find provider info for com.motorola.blur.setupprovider
E/BluetoothServiceJni( 1772): SOCK FLAG = 0 ***********************
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/WifiP2pService( 1023): mP2pAutoConnectSupport = 0
D/PollingManager( 1549): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1549): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
I/BTListenerThread( 4023): starting to listen
I/BTListenerThread( 4023): waiting to accept incoming Connection
I/        ( 4023): Discovery state changed to Started.
,E/ActivityThread( 1549): Failed to find provider info for com.motorola.blur.setupprovider
,D/CCE     ( 1549): Registering with Alarm Manager to restart CCE
D/WifiP2pService( 1023): sending p2p persistent groups changed broadcast
D/WifiP2pService( 1023): InactiveState
,D/WifiP2pService( 1023): InactiveState{ when=-7m38s606ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
D/WifiP2pService( 1023): P2pEnabledState{ when=-7m38s607ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-39ms what=139292 arg2=16 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2832686 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-39ms what=139292 arg2=16 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2832686 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState add service
D/WifiP2pService( 1023): add a new client
D/WifiP2pService( 1023): InactiveState{ when=-41ms what=139307 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-41ms what=139307 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState clear service request
,D/WifiP2pService( 1023): InactiveState{ when=-41ms what=139268 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
D/OtaApp  ( 1549): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/XTWiFiOS( 1269): Active network info is not available
,D/WifiP2pService( 1023): InactiveState{ when=-43ms what=139265 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/OtaApp  ( 1549): [debug] > CusSM.onRadioDown
I/        ( 4023): Added local service
I/        ( 4023): Cleared service requests
,I/        ( 4023): Stopped peer discovery
,D/WifiP2pService( 1023): P2pEnabledState{ when=-43ms what=139265 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/CaptivePortalTracker( 1023): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering( 1023): MasterInitialState.processMessage what=3
,I/        ( 4023): Started peer discovery
D/WifiP2pService( 1023): InactiveState{ when=-27ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-27ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 4340): COUNTRY Code Recived
E/wpa_supplicant( 4340): COUNTRY Code Recived
D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
,I/jxcore-log( 4023): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4023): 
I/jxcore-log( 4023): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): printNetworkInfo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): found interfaceName: lo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 4023): 
,I/chromium( 4023): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/dalvikvm( 4354): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x4251e0a8, skipping init
I/openssl ( 4354): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4354): Crypto mode 0 already enabled
I/ActivityManager( 1023): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4372 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1023): Killing 3900:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 4372): mnc/mcc: 
,V/MmsConfig( 4372): tag: bool value: enabledMMS - true
V/MmsConfig( 4372): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4372): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4372): tag: int value: maxImageWidth - 2592
,V/MmsConfig( 4372): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4372): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4372): tag: int value: minMessageCountPerThread - 10
,V/MmsConfig( 4372): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4372): tag: int value: recipientLimit - 20
V/MmsConfig( 4372): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4372): tag: int value: smsToMmsTextThreshold - 6
,V/MmsConfig( 4372): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4372): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4372): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4372): tag: bool value: smsForceShowEncodingMenu - true
,V/MmsConfig( 4372): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4372): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4372): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1023): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4393 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1023): Killing 3510:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4393): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4393): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4393): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4393): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1023): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4406 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1023): Killing 3926:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1023): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4419 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1023): Killing 3526:com.google.android.apps.plus/u0a90 (adj 15): empty #9
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4419): Binding Chromium to main looper Looper (main, tid 1) {4251ab48}
,I/LibraryLoader( 4419): Expected native library version number "",actual native library version number ""
,I/chromium( 4419): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4419): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4419): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4419): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4419): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4419): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4419): Local Branch: 
I/Adreno-EGL( 4419): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4419): Local Patches: NONE
I/Adreno-EGL( 4419): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4419): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4419): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4419): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 4419): Starting up...
,I/ActivityManager( 1023): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4463 uid=10090 gids={50090, 3003, 3002, 1028, 1015}
,I/ActivityManager( 1023): Killing 3546:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/TCMD    (  458): NL - Read 1000 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/ActivityManager( 1023): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=4480 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ImageResourceManager( 4463): ImageResourceManager: uninitalized
,I/iu.Environment( 4463): update battery state; isPlugged? true*
,I/iu.Environment( 4463): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,I/iu.Environment( 4463): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
I/ActivityManager( 1023): Killing 4092:com.motorola.context/u0a11 (adj 15): empty #9
W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1023): Killing 4104:com.motorola.deviceauthenticator/u0a16 (adj 15): empty #10
W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.Environment( 1400): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1400): num queued entries: 0
,D/MobileConnectivityChangeReceiver( 4393): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,I/iu.UploadsManager( 1400): num updated entries: 0
,D/MobileConnectivityChangeReceiver( 4393): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.SyncManager( 1400): NEXT; no task
,I/iu.Environment( 4463): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,D/DEBUG   ( 1549): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1549): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1549): bindWebServices(): registering our AIDL callback...
I/SundryService( 1549): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1549): ServiceHandler.handleMessage: mWaitCount=0
,D/EmailService.MarketingOptInSetter( 1549): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1549): onServiceConnected()
D/GetNotificationsWS( 1549): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1549): unbindWebServices(): un-registering our AIDL callback...
,D/dalvikvm( 4463): GC_FOR_ALLOC freed 387K, 5% free 16403K/17224K, paused 14ms, total 14ms
,I/dalvikvm-heap( 4463): Grow heap (frag case) to 19.788MB for 1821008-byte allocation
,I/iu.UploadsManager( 4463): #reloadSettings(); account: null; pageID: none; IU: disabled; IS: disabled; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,D/dalvikvm( 4463): GC_FOR_ALLOC freed 19K, 5% free 18189K/19004K, paused 11ms, total 11ms
,I/iu.FingerprintManager( 4463): Start processing all media
,I/iu.UploadsManager( 4463): End new media; added: 0, uploading: 0, time: 40 ms
,I/iu.FingerprintManager( 4463): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 4463): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 4463): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 4463): Start processing media store URI: content://media/phoneStorage/video/media
I/iu.FingerprintManager( 4463): Finished generating fingerprints; 0.021 seconds
,I/iu.FingerprintManager( 4463):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/ContactLocale( 4480): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledStateupdate channel list
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
I/wpa_supplicant( 4339): fatal error opening "/sys/power/wake_lock"
,I/wpa_supplicant( 4339): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=-4ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 4023): 2015-11-23T11:37:36.701Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:36.702Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 4023): 
,D/WifiStateMachine( 1023): handleMessage: E msg.what=131089
,D/WifiStateMachine( 1023): processMsg: DisconnectedState
,D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): processMsg: DriverStartedState
,D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1023): processMsg: DefaultState
,D/WifiStateMachine( 1023): handleMessage: X
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/jxcore-log( 4023): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): printNetworkInfo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): found interfaceName: lo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 4023): 
,I/chromium( 4023): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/GAV2    ( 4419): Thread[GAThread,5,main]: No campaign data found.
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/jxcore-log( 4023): 2015-11-23T11:37:41.725Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:41.726Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:41.728Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:41.730Z SendDataConnector.js: do connect now
I/jxcore-log( 4023): 
,I/        ( 4023): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 4023): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 4023): Starting to connect
,W/BluetoothAdapter( 4023): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1772): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
E/bt-btif ( 1772): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:2, scn:341678176
,W/bt-btif ( 1772): invalid rfc slot id: 12
,D/BluetoothSocket( 4023): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[136]}
,I/BTConnectToThread( 4023): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 4023): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 4023): 2015-11-23T11:37:41.758Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 4023): 
I/jxcore-log( 4023): 2015-11-23T11:37:41.758Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:41.759Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4023): 
,W/bt-sdp  ( 1772): SDP - Rcvd conn cnf with error: 0xd  CID 0x44
,E/bt-btif ( 1772): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 1772): invalid rfc slot id: 10
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiStateMachine( 1023): handleMessage: E msg.what=147461
D/WifiP2pService( 1023): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiP2pService( 1023): DefaultState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@43e322b8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-7ms what=147462 obj=android.net.wifi.StateChangeResult@43e322b8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=-8ms what=147462 obj=android.net.wifi.StateChangeResult@43e322b8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): processMsg: DriverStartedState
D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1023): handleMessage: X
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-23
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-41
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-3ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-6ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1023):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1023):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-2ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=-5ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 4023): Found 2 peers.
I/SS      ( 4023): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 4023): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023): InactiveState{ when=-5ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-5ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): DefaultState{ when=-5ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-2ms what=139301 arg2=22 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=139301 arg2=22 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState add service request
D/WifiP2pManager( 4023): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4023): Added service request
,I/jxcore-log( 4023): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): printNetworkInfo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): found interfaceName: lo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 4023): 
,I/chromium( 4023): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-15
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-4ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -15 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-8ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -15 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139310 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139310 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState discover services
,I/        ( 4023): Started service discovery
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-13
I/wpa_supplicant( 4340): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-41
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-45
D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -13 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-5ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1023):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-6ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1023):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-14ms what=147477 obj=Device: A5-1
D/WifiP2pService( 1023):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-15ms what=147477 obj=Device: A5-1
D/WifiP2pService( 1023):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
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
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/jxcore-log( 4023): 2015-11-23T11:37:46.778Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:46.779Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 4023): 
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-21
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-3ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-4ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -21 target=com.android.internal.util.StateMachine$SmHandler }
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/BluetoothBondStateMachine( 1772): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,I/BluetoothBondStateMachine( 1772): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 1772): Entering PendingCommandState State
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/ActivityManager( 1023): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.bluetooth.BTReceiver: pid=4529 uid=10011 gids={50011, 3003, 3002, 3001}
W/BluetoothEventManager( 4299): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,E/BluetoothEventManager( 4299): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,D/BluetoothManagerService( 1023): Message: 20
,D/BluetoothManagerService( 1023): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4257b570:true
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,E/bt-btif ( 1772): services_to_search = 3fffffff
,E/bt-btif ( 1772): ****************search UUID = 1200***********
,I/ActivityManager( 1023): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.BluetoothPairReceiver: pid=4541 uid=10016 gids={50016, 3002}
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,E/bt-btif ( 1772): services_to_search = 3ffffffe
,E/bt-btif ( 1772): ****************search UUID = 0100***********
,W/bt-btif ( 1772): new conn_srvc id:26, app_id:255
I/BTListenerThread( 4023): we got incoming connection
W/bt-btif ( 1772): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 1772): bta_dm_pm_ssr:2, lat:1200
,I/BTHandshakeSocketThread( 4023): Creating BTHandshakeSocketThread
I/BTListenerThread( 4023): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread started
,D/dalvikvm( 1023): GC_EXPLICIT freed 832K, 64% free 18047K/49260K, paused 4ms+10ms, total 102ms
,I/BTListenerThread( 4023): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 4023): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6816","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 4023): MESSAGE_WRITE 81 bytes.
I/HS      ( 4023): Incoming connection Hand Shake finished for : samsung-SM-N910C_PT6816
,I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 4023): Starting the connected thread incoming : true, samsung-SM-N910C_PT6816
,I/BtToSocketBase( 4023): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4023): Creating BTConnectedThread
I/BtConnectorHelper( 4023): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 4023): --DoOneRunRound started
,I/BtToRequestSocket( 4023): LocalHost address: localhost/127.0.0.1, port: 43200
,I/BtToRequestSocket( 4023): --DoOneRunRound ended
,I/jxcore-log( 4023): 2015-11-23T11:37:47.869Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4023): 
,I/ActivityManager( 1023): Killing 4299:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,I/ActivityManager( 1023): Killing 4480:android.process.acore/u0a10 (adj 15): empty #9
V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
V/BluetoothFtpService( 1772): Ftp Service onStartCommand
V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.BOND_STATE_CHANGED
E/bt-btif ( 1772): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 1772): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/WifiService( 1023): Client connection lost with reason: 4
D/BluetoothAdapterProperties( 1772): setRemoteTrust() result=true
D/BluetoothAdapterProperties( 1772): Failed to remove device: E0:DB:10:14:E2:C0
I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
I/BluetoothBondStateMachine( 1772): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
D/BluetoothMetrics( 1772): btclass5a020c
D/Checkin ( 1772): publish the event [tag = MOT_BT event name = PAIRING]
I/BluetoothBondStateMachine( 1772): StableState(): Entering Off State
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-26
D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/jxcore-log( 4023): 2015-11-23T11:37:48.269Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:48.273Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:48.279Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:48.325Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:48.328Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:48.339Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:48.347Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:48.385Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:48.389Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:48.428Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:48.437Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:48.476Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:48.480Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 4023): 
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState receive service response
I/jxcore-log( 4023): 2015-11-23T11:37:48.503Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 4023): 
I/        ( 4023): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"}, typeCordovap2p._tcp.local.:
I/        ( 4023): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT9160, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 4023): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT9160, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
I/jxcore-log( 4023): 2015-11-23T11:37:48.507Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:48.544Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:48.547Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:48.585Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:48.596Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:48.624Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:48.627Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:48.629Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:48.665Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): printNetworkInfo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): found interfaceName: lo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:48.728Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 4023): 
,I/chromium( 4023): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4023): 2015-11-23T11:37:48.732Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 4023): 
,W/bt-btif ( 1772): invalid rfc slot id: 11
,I/BtToSocketBase( 4023): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4023): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 4023): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT6816
I/BtToSocketBase( 4023): Stop ReceivingThread
I/BtToSocketBase( 4023): Stop SendingThread
,I/BtToSocketBase( 4023): Close local in
,I/BtToSocketBase( 4023): Close LocalOutputStream
,I/BtToSocketBase( 4023): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4023): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 4023): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT6816
,I/BtToSocketBase( 4023): Close localHostSocket
I/BtToSocketBase( 4023): Close bt in
I/BtToSocketBase( 4023): Close bt out
,I/BtToSocketBase( 4023): Close bt in
W/bt-rfcomm( 1772): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 1772): RFCOMM_DisconnectInd LCID:0x49
I/BtToSocketBase( 4023): Close bt out
,I/BtToSocketBase( 4023): Close bt socket
,I/BtToSocketBase( 4023): Close bt socket
,I/jxcore-log( 4023): 2015-11-23T11:37:48.819Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4023): 
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-44
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-4ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-6ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/jxcore-log( 4023): 2015-11-23T11:37:51.804Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:51.804Z SendDataConnector.js: Connect (retry count 2) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:51.806Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:51.807Z SendDataConnector.js: do connect now
I/jxcore-log( 4023): 
,I/        ( 4023): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 4023): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 4023): Starting to connect
,W/BluetoothAdapter( 4023): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1772): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 4023): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[138]}
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f208a5c rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/jxcore-log( 4023): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): printNetworkInfo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): found interfaceName: lo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 4023): 
,I/chromium( 4023): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139307 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=139307 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState clear service request
,I/        ( 4023): Cleared service requests
D/WifiP2pService( 1023): InactiveState{ when=-7ms what=139265 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-8ms what=139265 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 4023): Started peer discovery
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-27
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=-1ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 4023): Found 6 peers.
I/SS      ( 4023): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 4023): Peer(2): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 4023): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4023): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 4023): Peer(5): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 4023): Peer(6): A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1023): InactiveState{ when=0 what=139301 arg2=27 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139301 arg2=27 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState add service request
D/WifiP2pManager( 4023): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4023): Added service request
,W/bt-sdp  ( 1772): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
,E/bt-btif ( 1772): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 4023): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 1772): invalid rfc slot id: 14
,I/CONNEC  ( 4023): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 4023): 2015-11-23T11:37:57.657Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:57.659Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:37:57.661Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4023): 
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=139310 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-4ms what=139310 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState discover services
,I/        ( 4023): Started service discovery
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiStateMachine( 1023): handleMessage: E msg.what=147461
D/WifiStateMachine( 1023): processMsg: DisconnectedState
,D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): processMsg: DriverStartedState
,D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1023): handleMessage: X
D/WifiP2pService( 1023): InactiveState{ when=-10ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-10ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): DefaultState{ when=-10ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 4023): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): printNetworkInfo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): found interfaceName: lo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 4023): 
,I/chromium( 4023): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 level=-85
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
I/wpa_supplicant( 4340): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-41
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-43
,D/WifiP2pService( 1023): InactiveState{ when=-13ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService( 1023):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService( 1023):  primary type: 3-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 128
D/WifiP2pService( 1023):  grpcapab: 9
D/WifiP2pService( 1023):  devcapab: 4
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -85 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-19ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService( 1023):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService( 1023):  primary type: 3-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 128
D/WifiP2pService( 1023):  grpcapab: 9
D/WifiP2pService( 1023):  devcapab: 4
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -85 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-11ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1023):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-11ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1023):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-13ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-14ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,V/AlarmManager( 1023): sending alarm Alarm{42902568 type 3 android}
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-13
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-2ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -13 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-4ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -13 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT910","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT910","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState receive service response
I/        ( 4023): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT910","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
I/        ( 4023): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT910","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT910, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 4023): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT910, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5500"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5500"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState receive service response
I/        ( 4023): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5500"}, typeCordovap2p._tcp.local.:
I/        ( 4023): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5500"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT5500, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 4023): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT5500, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-21
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-23
,D/WifiP2pService( 1023): InactiveState{ when=-10ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-10ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-3ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService( 1023):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService( 1023):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/jxcore-log( 4023): 2015-11-23T11:38:02.687Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:02.687Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 4023): 
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/BluetoothBondStateMachine( 1772): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 1772): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 1772): Entering PendingCommandState State
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 1772): services_to_search = 3fffffff
,E/bt-btif ( 1772): ****************search UUID = 1200***********
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,E/bt-btif ( 1772): services_to_search = 3ffffffe
,E/bt-btif ( 1772): ****************search UUID = 0100***********
,W/bt-btif ( 1772): new conn_srvc id:26, app_id:255
,W/bt-btif ( 1772): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 1772): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 4023): we got incoming connection
,I/BTHandshakeSocketThread( 4023): Creating BTHandshakeSocketThread
,I/BTListenerThread( 4023): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread started
,I/BTListenerThread( 4023): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 4023): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4588","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 4023): MESSAGE_WRITE 81 bytes.
,I/HS      ( 4023): Incoming connection Hand Shake finished for : LGE-LG-D722_PT4588
I/BtConnectorHelper( 4023): Starting the connected thread incoming : true, LGE-LG-D722_PT4588
I/BtToSocketBase( 4023): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 4023): Creating BTConnectedThread
I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4023): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 4023): --DoOneRunRound started
,I/BtToRequestSocket( 4023): LocalHost address: localhost/127.0.0.1, port: 43200
,I/jxcore-log( 4023): 2015-11-23T11:38:03.233Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4023): 
,I/BtToRequestSocket( 4023): --DoOneRunRound ended
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,E/bt-btif ( 1772): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 2 uuid:00001106-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1772): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 1772): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
D/BluetoothAdapterProperties( 1772): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 1772): Failed to remove device: F8:95:C7:87:85:54
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 1772): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,D/BluetoothMetrics( 1772): btclass5a020c
,I/BluetoothBondStateMachine( 1772): StableState(): Entering Off State
,D/Checkin ( 1772): publish the event [tag = MOT_BT event name = PAIRING]
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/jxcore-log( 4023): 2015-11-23T11:38:03.637Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:03.676Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:03.682Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:03.689Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:03.692Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:03.699Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:03.707Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:03.720Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:03.755Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:03.757Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:03.759Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:03.796Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): printNetworkInfo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): found interfaceName: lo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:03.828Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 4023): 
,I/chromium( 4023): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4023): 2015-11-23T11:38:03.855Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:03.874Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:03.878Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:03.892Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:03.895Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:03.935Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:03.963Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 4023): 
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/jxcore-log( 4023): 2015-11-23T11:38:04.041Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:04.281Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:04.285Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:04.382Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:04.511Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:04.545Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 4023): 
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/jxcore-log( 4023): 2015-11-23T11:38:04.615Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:04.670Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:04.706Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:04.718Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:04.729Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:04.738Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:04.765Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:04.880Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:04.915Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 4023): 
,W/bt-btif ( 1772): invalid rfc slot id: 13
,I/BtToSocketBase( 4023): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4023): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 4023): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT4588
,I/BtToSocketBase( 4023): Stop ReceivingThread
I/BtToSocketBase( 4023): Stop SendingThread
,I/BtToSocketBase( 4023): Close local in
,I/BtToSocketBase( 4023): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 4023): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4023): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT4588
,I/BtToSocketBase( 4023): Close localHostSocket
I/BtToSocketBase( 4023): Close bt in
,I/BtToSocketBase( 4023): Close bt out
,I/BtToSocketBase( 4023): Close bt socket
,I/BtToSocketBase( 4023): Close LocalOutputStream
I/BtToSocketBase( 4023): Close bt in
I/BtToSocketBase( 4023): Close bt out
,I/BtToSocketBase( 4023): Close bt socket
,I/jxcore-log( 4023): 2015-11-23T11:38:05.027Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4023): 
,W/bt-rfcomm( 1772): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
,W/bt-rfcomm( 1772): RFCOMM_DisconnectInd LCID:0x4c
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139307 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139307 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState clear service request
,I/        ( 4023): Cleared service requests
D/WifiP2pService( 1023): InactiveState{ when=-9ms what=139265 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-9ms what=139265 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 4023): Started peer discovery
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-15
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-48
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/WifiP2pService( 1023): InactiveState{ when=-2ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-6ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-7ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-3ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=-4ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 4023): Found 8 peers.
I/SS      ( 4023): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 4023): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 4023): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4023): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 4023): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 4023): Peer(6): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 4023): Peer(7): DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,I/SS      ( 4023): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1023): InactiveState{ when=-6ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-6ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): DefaultState{ when=-7ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-4ms what=139301 arg2=33 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-4ms what=139301 arg2=33 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState add service request
D/WifiP2pManager( 4023): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4023): Added service request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=139310 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139310 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState discover services
,I/        ( 4023): Started service discovery
,I/jxcore-log( 4023): 2015-11-23T11:38:07.699Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:07.699Z SendDataConnector.js: Connect (retry count 3) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:07.701Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:07.702Z SendDataConnector.js: do connect now
I/jxcore-log( 4023): 
,I/        ( 4023): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 4023): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 4023): Starting to connect
,W/BluetoothAdapter( 4023): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1772): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 4023): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[140]}
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f208c18 rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 4023): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): printNetworkInfo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): found interfaceName: lo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 4023): 
,I/chromium( 4023): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-13
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -13 target=com.android.internal.util.StateMachine$SmHandler }
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5500"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5500"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState receive service response
I/        ( 4023): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5500"}, typeCordovap2p._tcp.local.:
I/        ( 4023): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5500"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT5500, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 4023): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT5500, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,W/bt-sdp  ( 1772): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
,E/bt-btif ( 1772): DISCOVERY_COMP_EVT slot id:16, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 1772): invalid rfc slot id: 16
,I/BTConnectToThread( 4023): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 4023): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 4023): 2015-11-23T11:38:13.331Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:13.333Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:13.335Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4023): 
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-22
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState receive service response
,I/        ( 4023): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"}, typeCordovap2p._tcp.local.:
,I/        ( 4023): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT9160, peerAddress: 00:F4:6F:30:E0:6C
,I/BtConnectorHelper( 4023): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT9160, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 4023): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): printNetworkInfo
I/jxcore-log( 4023): 
I/jxcore-log( 4023): found interfaceName: lo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 4023): 
,I/chromium( 4023): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiStateMachine( 1023): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1023): processMsg: DisconnectedState
,D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiP2pService( 1023): InactiveState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1023): processMsg: DriverStartedState
D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
D/WifiStateMachine( 1023): handleMessage: X
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/BluetoothBondStateMachine( 1772): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 1772): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 1772): Entering PendingCommandState State
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 1772): services_to_search = 3fffffff
,E/bt-btif ( 1772): ****************search UUID = 1200***********
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-45
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService( 1023):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-11ms what=147477 obj=Device: A5-1
D/WifiP2pService( 1023):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,E/bt-btif ( 1772): services_to_search = 3ffffffe
,E/bt-btif ( 1772): ****************search UUID = 0100***********
,W/bt-btif ( 1772): new conn_srvc id:26, app_id:255
,I/BTListenerThread( 4023): we got incoming connection
,W/bt-btif ( 1772): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 1772): bta_dm_pm_ssr:2, lat:1200
,I/BTHandshakeSocketThread( 4023): Creating BTHandshakeSocketThread
,I/BTListenerThread( 4023): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread started
,I/BTListenerThread( 4023): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 4023): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3613","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 4023): MESSAGE_WRITE 81 bytes.
,I/HS      ( 4023): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT3613
,I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4023): Starting the connected thread incoming : true, samsung-SM-G900F_PT3613
,I/BtToSocketBase( 4023): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 4023): Creating BTConnectedThread
I/BtConnectorHelper( 4023): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 4023): --DoOneRunRound started
,I/jxcore-log( 4023): 2015-11-23T11:38:16.240Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4023): 
,I/BtToRequestSocket( 4023): LocalHost address: localhost/127.0.0.1, port: 43200
,I/BtToRequestSocket( 4023): --DoOneRunRound ended
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,E/bt-btif ( 1772): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1772): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1772): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1772): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 1772): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 1772): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 1772): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,I/BluetoothBondStateMachine( 1772): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 1772): StableState(): Entering Off State
,D/BluetoothMetrics( 1772): btclass5a020c
,D/Checkin ( 1772): publish the event [tag = MOT_BT event name = PAIRING]
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/jxcore-log( 4023): 2015-11-23T11:38:16.780Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:16.787Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:16.790Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:16.877Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:16.930Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:16.941Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:16.975Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:17.034Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:17.046Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:17.106Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 4023): 
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/jxcore-log( 4023): 2015-11-23T11:38:17.163Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:17.195Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:17.203Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:17.214Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:17.245Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:17.254Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:17.286Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:17.296Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:17.335Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:17.345Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:17.385Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:17.404Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:17.435Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:17.443Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:17.476Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 4023): 
,W/bt-btif ( 1772): invalid rfc slot id: 15
,I/BtToSocketBase( 4023): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 4023): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 4023): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT3613
,I/BtToSocketBase( 4023): Stop ReceivingThread
,I/BtToSocketBase( 4023): Stop SendingThread
,I/BtToSocketBase( 4023): Close local in
,I/BtToSocketBase( 4023): Close LocalOutputStream
,I/BtToSocketBase( 4023): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 4023): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 4023): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT3613
,I/BtToSocketBase( 4023): Close localHostSocket
,I/BtToSocketBase( 4023): Close bt in
,I/BtToSocketBase( 4023): Close bt out
,I/BtToSocketBase( 4023): Close bt in
,I/BtToSocketBase( 4023): Close bt out
,I/BtToSocketBase( 4023): Close bt socket
,I/BtToSocketBase( 4023): Close bt socket
,I/jxcore-log( 4023): 2015-11-23T11:38:17.599Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4023): 
,W/bt-rfcomm( 1772): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
,W/bt-rfcomm( 1772): RFCOMM_DisconnectInd LCID:0x41
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/jxcore-log( 4023): 2015-11-23T11:38:18.378Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:18.379Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): printNetworkInfo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): found interfaceName: lo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 4023): 
,I/chromium( 4023): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139307 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139307 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState clear service request
,D/WifiP2pService( 1023): InactiveState{ when=-7ms what=139265 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 4023): Cleared service requests
D/WifiP2pService( 1023): P2pEnabledState{ when=-8ms what=139265 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 4023): Started peer discovery
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-15
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -15 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -15 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=-2ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 4023): Found 8 peers.
I/SS      ( 4023): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 4023): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 4023): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4023): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 4023): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 4023): Peer(6): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 4023): Peer(7): DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,I/SS      ( 4023): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1023): InactiveState{ when=0 what=139301 arg2=38 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139301 arg2=38 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState add service request
D/WifiP2pManager( 4023): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4023): Added service request
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=139310 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139310 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState discover services
,I/        ( 4023): Started service discovery
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-27
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -27 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-13
D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -13 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5500"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5500"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState receive service response
I/        ( 4023): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5500"}, typeCordovap2p._tcp.local.:
I/        ( 4023): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5500"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT5500, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 4023): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT5500, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,D/WifiP2pService( 1023): InactiveState{ when=-7ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-8ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState receive service response
I/        ( 4023): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"}, typeCordovap2p._tcp.local.:
I/        ( 4023): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT9160, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 4023): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT9160, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 4023): 2015-11-23T11:38:23.400Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:23.400Z SendDataConnector.js: Connect (retry count 4) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:23.402Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:23.404Z SendDataConnector.js: do connect now
I/jxcore-log( 4023): 
,I/        ( 4023): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 4023): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 4023): Starting to connect
,W/BluetoothAdapter( 4023): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1772): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 4023): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[142]}
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/jxcore-log( 4023): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): printNetworkInfo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): found interfaceName: lo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 4023): 
,I/chromium( 4023): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,W/bt-rfcomm( 1772): PORT_StartCnf failed result:5
,W/bt-btif ( 1772): invalid rfc slot id: 18
,I/BTConnectToThread( 4023): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 4023): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 4023): 2015-11-23T11:38:26.601Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:26.601Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:26.604Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:26.609Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): ---- round done--------
I/jxcore-log( 4023): 
I/jxcore-log( 4023): ---- gotta redo : 44:80:EB:7B:5A:05, try count now: 1
I/jxcore-log( 4023): 
I/jxcore-log( 4023): do fake peer & start
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 4023): 
I/jxcore-log( 4023): 2015-11-23T11:38:26.613Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 4023): 
I/jxcore-log( 4023): 2015-11-23T11:38:26.613Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:26.613Z SendDataConnector.js: do connect now
I/jxcore-log( 4023): 
,I/        ( 4023): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 4023): Connecting to null, at 00:F4:6F:30:E0:6C
,I/chromium( 4023): [INFO:CONSOLE(63)] "logCallback round[0] time: 74380 ms, rnd: 5, ex: Connection to 44:80:EB:7B:5A:05 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 4023): Starting to connect
,W/BluetoothAdapter( 4023): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1772): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 4023): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[143]}
,I/BluetoothBondStateMachine( 1772): No record of the device:null
,I/BluetoothBondStateMachine( 1772): bondStateChangeCallback: Status: 1 Address: 44:80:EB:7B:5A:05 newState: 0
,E/BluetoothBondStateMachine( 1772): In stable state, received invalid newState: 10
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2088a0 rs_disc_pending=1
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1772): bta_dm_check_av:0
,E/bt-btif ( 1772): Do not find the bg connection mask for the remote device
,W/bt-btif ( 1772): Do not find the bg connection mask for the remote device
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,W/bt-l2cap( 1772): L2CAP - con rsp - bad ID. Exp: 5 Got: 3
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/BluetoothBondStateMachine( 1772): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 1772): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 1772): Entering PendingCommandState State
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/jxcore-log( 4023): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): printNetworkInfo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): found interfaceName: lo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 4023): 
,I/chromium( 4023): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
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
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=139307 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139307 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState clear service request
,I/        ( 4023): Cleared service requests
D/WifiP2pService( 1023): InactiveState{ when=-11ms what=139265 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-11ms what=139265 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 4023): Started peer discovery
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,E/bt-btif ( 1772): services_to_search = 3fffffff
,E/bt-btif ( 1772): ****************search UUID = 1200***********
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,E/bt-btif ( 1772): services_to_search = 3ffffffe
,E/bt-btif ( 1772): ****************search UUID = 0100***********
,W/bt-btif ( 1772): new conn_srvc id:26, app_id:1
,W/bt-btif ( 1772): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 1772): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 4023): Starting to Handshake
,I/BTHandshakeSocketThread( 4023): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 4023): MESSAGE_WRITE 81 bytes.
,I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread started
,I/BTConnectToThread( 4023): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 4023): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 4023): HandshakeOk : samsung-SM-G800F_PT9160
,I/HS      ( 4023): Hand Shake finished outgoing for : samsung-SM-G800F_PT9160
,I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread fully stopped
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,I/BtConnectorHelper( 4023): Starting the connected thread incoming : false, samsung-SM-G800F_PT9160
,I/BtToSocketBase( 4023): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 4023): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 4023): mHTTPPort  set to : 39457
,I/BtConnectorHelper( 4023): Request socket is using : 39457
,I/BtToRequestSocket( 4023): Now accepting connections
,E/bt-btif ( 1772): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1772): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1772): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1772): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 1772): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
,D/BluetoothAdapterProperties( 1772): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 1772): Failed to remove device: 00:F4:6F:30:E0:6C
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 1772): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 1772): StableState(): Entering Off State
,D/BluetoothMetrics( 1772): btclass1f00
,D/Checkin ( 1772): publish the event [tag = MOT_BT event name = PAIRING]
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/BtConnectorHelper( 4023): Calling ConnectionStatusUpdate with port :39457
,I/jxcore-log( 4023): 2015-11-23T11:38:30.352Z SendDataConnector.js: CLIENT connected to 39457, error: null
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:30.353Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 4023): 
,I/BtToRequestSocket( 4023): incoming data from: /127.0.0.1, port: 39457
,I/BtToRequestSocket( 4023): Set local streams
,I/jxcore-log( 4023): 2015-11-23T11:38:30.368Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 4023): 
,I/BtToRequestSocket( 4023): rin ended ---------------------------;
,D/ConnectivityService( 1023): NetTransition Wakelock for ConnectedState released by timeout
,I/jxcore-log( 4023): 2015-11-23T11:38:30.751Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:30.937Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 4023): 
,I/wpa_supplicant( 4340): wlan0: Trying to associate with SSID 'NG700'
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,E/wpa_supplicant( 4340): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1023): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1023): processMsg: DisconnectedState
,D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): processMsg: DriverStartedState
,D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1023): handleMessage: X
,D/WifiStateMachine( 1023): handleMessage: E msg.what=147462
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): handleMessage: X
,I/jxcore-log( 4023): 2015-11-23T11:38:31.598Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:31.720Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 4023): 
,I/wpa_supplicant( 4340): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 4340): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  458): NL - Read 312 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
D/TCMD    (  458): NL - Read 192 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
D/TCMD    (  458): NL - Read 68 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
D/TCMD    (  458): NL - Read 1000 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 4340): wlan0: Associated with c0:ff:d4:d3:aa:48
D/TCMD    (  458): NL - Read 80 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
D/TCMD    (  458): NL - Read 80 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
D/TCMD    (  458): NL - Read 68 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiStateMachine( 1023): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1023): processMsg: DisconnectedState,
,D/WifiStateMachine( 1023): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1023): processMsg: ConnectModeState,
,D/WifiStateMachine( 1023): handleMessage: X
,D/Tethering( 1023): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1023): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1023): handleMessage: E msg.what=131101
D/WifiStateMachine( 1023): processMsg: DisconnectedState
,D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): processMsg: DriverStartedState
,D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1023): processMsg: DefaultState
,D/WifiStateMachine( 1023): handleMessage: X
,I/jxcore-log( 4023): 2015-11-23T11:38:32.034Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:32.396Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:32.567Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:32.719Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:32.997Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:33.232Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:33.235Z SendDataConnector.js: got all data for this round
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:33.254Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:33.254Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4023): 
,I/BtConnectorHelper( 4023): Disconnect outgoing peer: 00:F4:6F:30:E0:6C
I/BtToSocketBase( 4023): Stop ReceivingThread
,I/BtToSocketBase( 4023): Stop SendingThread
,I/BtToSocketBase( 4023): Close local in
,I/BtToSocketBase( 4023): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 4023): Close LocalOutputStream
,I/BtToSocketBase( 4023): Close localHostSocket
I/BtToSocketBase( 4023): Close bt in
,I/BtToSocketBase( 4023): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 4023): Close bt out
I/BtToSocketBase( 4023): Close bt socket
,I/BtToRequestSocket( 4023): Close server socket
I/jxcore-log( 4023): 2015-11-23T11:38:33.268Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 4023): 
I/jxcore-log( 4023): ---- round done--------
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): do fake peer & start
I/jxcore-log( 4023): 
I/jxcore-log( 4023): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 4023): 
I/jxcore-log( 4023): 2015-11-23T11:38:33.269Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:33.270Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:33.270Z SendDataConnector.js: do connect now
I/jxcore-log( 4023): 
,I/        ( 4023): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 4023): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/chromium( 4023): [INFO:CONSOLE(63)] "logCallback round[0] time: 6624 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 4023): Starting to connect
,W/BluetoothAdapter( 4023): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1772): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 4023): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[144]}
,W/bt-btif ( 1772): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,I/wpa_supplicant( 4340): P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5
,I/wpa_supplicant( 4340): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-3ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-4ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=-4ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 4023): Found 6 peers.
I/SS      ( 4023): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 4023): Peer(2): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 4023): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4023): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 4023): Peer(5): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 4023): Peer(6): A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1023): InactiveState{ when=-4ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-4ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): DefaultState{ when=-4ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-3ms what=139301 arg2=44 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=139301 arg2=44 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState add service request
D/WifiP2pManager( 4023): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4023): Added service request
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f208f90 rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 4023): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): printNetworkInfo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): found interfaceName: lo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 4023): 
,I/chromium( 4023): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139310 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139310 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState discover services
,I/        ( 4023): Starting service discovery failed, error code 0
D/WifiP2pService( 1023): InactiveState{ when=-2ms what=139307 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-5ms what=139307 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState clear service request
,I/        ( 4023): Cleared service requests
,D/WifiStateMachine( 1023): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1023): processMsg: DisconnectedState
,D/WifiStateMachine( 1023): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): handleMessage: X
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [e0:db:10:14:e2:c0]: 6, f, 6109
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,I/wpa_supplicant( 4340): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 4340): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,D/TCMD    (  458): NL - Read 1000 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiStateMachine( 1023): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=147459
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): Network connection established
,D/WifiStateMachine( 1023): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1023): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1023): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1023): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1023): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1023): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1023): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1023): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1023): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1023): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1023): handleMessage: X
,D/WifiStateMachine( 1023): handleMessage: E msg.what=147462
D/WifiStateMachine( 1023): processMsg: ObtainingIpState
D/WifiStateMachine( 1023): ObtainingIpState{ when=-19ms what=147462 obj=android.net.wifi.StateChangeResult@43eb1e48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1023): processMsg: L2ConnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): handleMessage: X
,D/WifiStateMachine( 1023): handleMessage: E msg.what=196612
D/WifiStateMachine( 1023): processMsg: ObtainingIpState
D/WifiStateMachine( 1023): ObtainingIpState{ when=-1ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1023): processMsg: L2ConnectedState
,D/WifiStateMachine( 1023): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1023): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1023): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43eb42f8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43eb42f8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1023): handleMessage: X
,W/bt-btif ( 1772): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 4023): Starting to Handshake
W/bt-btif ( 1772): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 1772): bta_dm_pm_ssr:2, lat:1200
,I/BTHandshakeSocketThread( 4023): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 4023): MESSAGE_WRITE 81 bytes.
,I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread started
,I/BTConnectToThread( 4023): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 4023): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6816","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 4023): HandshakeOk : samsung-SM-N910C_PT6816
I/HS      ( 4023): Hand Shake finished outgoing for : samsung-SM-N910C_PT6816
,I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4023): Starting the connected thread incoming : false, samsung-SM-N910C_PT6816
I/BtToSocketBase( 4023): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 4023): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 4023): mHTTPPort  set to : 36415
,I/BtConnectorHelper( 4023): Request socket is using : 36415
,I/BtToRequestSocket( 4023): Now accepting connections
,I/BtConnectorHelper( 4023): Calling ConnectionStatusUpdate with port :36415
,I/jxcore-log( 4023): 2015-11-23T11:38:36.166Z SendDataConnector.js: CLIENT connected to 36415, error: null
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:36.168Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 4023): 
,I/BtToRequestSocket( 4023): incoming data from: /127.0.0.1, port: 36415
,I/BtToRequestSocket( 4023): Set local streams
,I/jxcore-log( 4023): 2015-11-23T11:38:36.183Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 4023): 
,I/BtToRequestSocket( 4023): rin ended ---------------------------;
,I/jxcore-log( 4023): 2015-11-23T11:38:36.626Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:36.690Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:37.262Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 4023): 
,D/TCMD    (  458): NL - Read 60 bytes from update socket.
D/TCMD    (  458): NL - ignore NL message, type = 20
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiStateMachine( 1023): addressUpdated: 192.168.1.123/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1023): handleMessage: E msg.what=131215
D/WifiStateMachine( 1023): processMsg: ObtainingIpState
D/WifiStateMachine( 1023): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.123/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1023): processMsg: L2ConnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): processMsg: DriverStartedState
,D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1023): handleMessage: X
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f208f90 rs_disc_pending=0
W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,D/WifiStateMachine( 1023): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1023): processMsg: ObtainingIpState
,D/WifiStateMachine( 1023): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1023): processMsg: L2ConnectedState
D/WifiStateMachine( 1023): setSuspendOptimizationsNative: 1 true
,I/jxcore-log( 4023): 2015-11-23T11:38:37.648Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 4023): 
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1023): DHCP successful
,D/WifiStateMachine( 1023): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1023): Calling ARP set with IP = 192.168.1.123
,D/WifiStateMachine( 1023): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1023): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1023): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1023): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1023): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1023): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1023): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1023): VerifyingLinkState enter
,D/WifiStateMachine( 1023): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=147461
D/WifiStateMachine( 1023): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1023): VerifyingLinkState what=147461 NOT_HANDLED
D/WifiStateMachine( 1023): processMsg: L2ConnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): processMsg: DriverStartedState
,D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1023): handleMessage: X
,D/WifiStateMachine( 1023): handleMessage: E msg.what=151572
D/WifiStateMachine( 1023): processMsg: VerifyingLinkState
D/WifiStateMachine( 1023): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1023): processMsg: L2ConnectedState
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/jxcore-log( 4023): 2015-11-23T11:38:38.512Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 4023): 
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-13
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -13 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -13 target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1085): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
D/WifiP2pService( 1023): InactiveState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=-1ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 4023): Found 6 peers.
I/SS      ( 4023): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 4023): Peer(2): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 4023): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4023): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 4023): Peer(5): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 4023): Peer(6): A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1023): InactiveState{ when=0 what=139301 arg2=48 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139301 arg2=48 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState add service request
D/WifiP2pManager( 4023): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4023): Added service request
,D/WifiStateMachine( 1023): handleMessage: X
,D/WifiStateMachine( 1023): handleMessage: E msg.what=151572
D/WifiStateMachine( 1023): processMsg: VerifyingLinkState
D/WifiStateMachine( 1023): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1023): processMsg: L2ConnectedState
,D/WifiStateMachine( 1023): handleMessage: X
,D/WifiStateMachine( 1023): handleMessage: E msg.what=135190
D/WifiStateMachine( 1023): processMsg: VerifyingLinkState
D/WifiStateMachine( 1023): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 1023): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1023): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1023): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1023): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1023): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1023): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1023): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1023): CaptivePortalCheckState enter
,D/WifiStateMachine( 1023): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/ConnectivityService( 1023): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1023): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1023): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService( 1023): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=135190
D/WifiStateMachine( 1023): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1023): processMsg: L2ConnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): processMsg: DriverStartedState
D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131092
D/WifiStateMachine( 1023): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1023): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1023): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/ConnectivityService( 1023): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1023): WiFi NOT Tethered!
,E/ConnectivityService( 1023): Unexpected mtu value: android.net.wifi.WifiStateTracker@425f9b38
I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/WifiStateMachine( 1023): transitionTo: destState=ConnectedState
,D/WifiStateMachine( 1023): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1023): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1023): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1023): moveTempStackToStateStack: i=0,j=5
D/Checkin ( 1023): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/WifiStateMachine( 1023): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1023): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131092
D/WifiStateMachine( 1023): processMsg: ConnectedState
D/WifiStateMachine( 1023): processMsg: L2ConnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): processMsg: DriverStartedState
,D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
D/WifiStateMachine( 1023): processMsg: DefaultState
,D/WifiStateMachine( 1023): handleMessage: X
,D/Nat464Xlat( 1023): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1285): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1285): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1285): onReceive() - done, currentInetCondition=0
I/SBar.NetworkController( 1085): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/ConnectivityService( 1023): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1023): WiFi NOT Tethered!
,E/ConnectivityService( 1023): Unexpected mtu value: android.net.wifi.WifiStateTracker@425f9b38
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService( 1023): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1023): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1285): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1285): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1285): onReceive() - done, currentInetCondition=0
I/CheckinService( 1400): Checkin interval check for package: unspecified last checkin: 1448278236198 min interval config: 0 actual interval: 482675
,I/CheckinService( 1400): Checking schedule, now: 1448278718890 next: 1448278266134
,I/CheckinService( 1400): active receiver: enabled
,I/CheckinService( 1400): Preparing to send checkin request
,I/EventLogService( 1400): Accumulating logs since 1448278231913
,D/dalvikvm( 1400): GC_CONCURRENT freed 1971K, 33% free 11690K/17224K, paused 6ms+6ms, total 68ms
,W/SQLiteConnectionPool( 1400): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/CheckinRequestBuilder( 1400): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1400): Failed to find provider info for com.google.android.wearable.settings
,I/jxcore-log( 4023): 2015-11-23T11:38:38.959Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 4023): 
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1023): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4717 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4717): VFY: unable to resolve static field 529 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4717): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4717): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
,W/dalvikvm( 4717): VFY: unable to resolve virtual method 10979: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4717): VFY: replacing opcode 0x6e at 0x00ca
,I/MultiDex( 4717): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4717): install
,I/MultiDex( 4717): MultiDexExtractor.load(/data/app/com.google.android.gms-2.apk, false)
,I/MultiDex( 4717): loading existing secondary dex files
,I/MultiDex( 4717): load found 3 secondary dex files
,I/MultiDex( 4717): install done
,D/dalvikvm( 4717): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4717): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4717): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4717): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4717): VFY: unable to resolve instance field 46
,D/dalvikvm( 4717): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 4717): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4717): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4717): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4717): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4717): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 4717): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42524878
,D/dalvikvm( 4717): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42524878
,D/dalvikvm( 4717): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42524878, skipping init
D/dalvikvm( 4717): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42524878
,D/dalvikvm( 4717): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42524878
,V/JNIHelp ( 4717): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/dalvikvm( 4717): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42524878
,D/dalvikvm( 4717): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x42524878
D/dalvikvm( 4717): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42524878
,D/dalvikvm( 4717): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42524878
,I/ProviderInstaller( 4717): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1222): callingUid 10022, callindPid: 1222
,E/MDM     ( 1222): [78] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/GCM     ( 1340): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1340): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1400): Restart initialization of location
,E/AuthorizationBluetoothService( 1340): Proximity feature is not enabled.
,I/dalvikvm( 4717): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
,W/dalvikvm( 4717): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4717): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4717): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 4717): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4717): VFY: replacing opcode 0x6e at 0x0220
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1400): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/dalvikvm( 4717): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4717): Link of class 'Lcom/google/android/gms/common/h/c;' failed
,E/dalvikvm( 4717): Could not find class 'com.google.android.gms.common.h.c', referenced from method com.google.android.gms.common.h.b.a
W/dalvikvm( 4717): VFY: unable to resolve new-instance 2668 (Lcom/google/android/gms/common/h/c;) in Lcom/google/android/gms/common/h/b;
,D/dalvikvm( 4717): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4717): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.h.b.b
W/dalvikvm( 4717): VFY: unable to resolve virtual method 328: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4717): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4717): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4717): Link of class 'Lcom/google/android/gms/common/h/c;' failed
,D/dalvikvm( 4717): DexOpt: unable to opt direct call 0x2d44 at 0x02 in Lcom/google/android/gms/common/h/b;.a
,I/jxcore-log( 4023): DBG, CoordinatorConnector connect called
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): Coordinator is now connected to the server!
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): printNetworkInfo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): found interfaceName: lo
I/jxcore-log( 4023): 
I/jxcore-log( 4023): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 4023): 
I/jxcore-log( 4023): found interfaceName: wlan0
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): -iface: IPv4 is internal : false, has ip: 192.168.1.123
I/jxcore-log( 4023): 
,I/chromium( 4023): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,W/GCoreFlp( 1222): No location to return for getLastLocation()
,W/FusedLocationProvider( 1340): location=null
,D/WVCdm   (  281): Instantiating CDM.
,I/WVCdm   (  281): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  281): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  281): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  281): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5138000
,E/DrmWidevineDash(  281): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5138000
D/DrmWidevineDash(  281): OEMCrypto_Initialize exit returns 0
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
I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=3209679579
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4717): Install completed successfully. count=13 extracted=0
,D/dalvikvm( 4717): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x426ed048
D/dalvikvm( 4717): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x426ed048
,D/dalvikvm( 4717): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x426ed048, skipping init
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139310 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139310 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState discover services
I/        ( 4023): Started service discovery
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f208a5c rs_disc_pending=0
W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,D/dalvikvm( 4717): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/dalvikvm( 4754): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4717): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4717): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 70ms
,I/Adreno-EGL( 4717): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4717): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4717): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4717): Local Branch: 
I/Adreno-EGL( 4717): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4717): Local Patches: NONE
I/Adreno-EGL( 4717): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4717): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4717): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4717): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4717): Local Branch: 
I/Adreno-EGL( 4717): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4717): Local Patches: NONE
I/Adreno-EGL( 4717): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/jxcore-log( 4023): 2015-11-23T11:38:40.141Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 4023): 
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
D/WVCdm   (  281): PrepareKeyRequest: nonce=1789083437
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/WifiStateMachine( 1023): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1023): handleMessage: E msg.what=131215
D/WifiStateMachine( 1023): processMsg: ConnectedState
D/WifiStateMachine( 1023): processMsg: L2ConnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): processMsg: DriverStartedState
D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1023): processMsg: DefaultState
,D/WifiStateMachine( 1023): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1023): handleMessage: X
,D/ConnectivityService( 1023): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1023):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1023): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1023): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1023): requiresClat: netType=1, hasIPv4Address=true
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-45
D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: A5-1
D/WifiP2pService( 1023):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService( 1023):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,I/Adreno-EGL( 4717): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4717): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4717): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4717): Local Branch: 
I/Adreno-EGL( 4717): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4717): Local Patches: NONE
I/Adreno-EGL( 4717): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4717): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4717): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4717): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4717): Local Branch: 
I/Adreno-EGL( 4717): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4717): Local Patches: NONE
I/Adreno-EGL( 4717): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/jxcore-log( 4023): 2015-11-23T11:38:40.978Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 4023): 
,W/Settings( 4717): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1400): Classify the device as Phone.
,V/NativeCrypto( 1400): SSL shutdown failed: ssl=0x6b9bac68: I/O error during system call, Connection timed out
,I/CheckinTask( 1400): Sending checkin request (11723 bytes)
,I/jxcore-log( 4023): 2015-11-23T11:38:41.831Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 4023): 
,D/Tethering( 1023): MasterInitialState.processMessage what=3
,W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1549): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/PollingManager( 1549): now: 526883 ,futureTime: 82580999
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/PollingManager( 1549): Polling alarm set to expire at: 82580999 Current Time: 526885
,E/ActivityThread( 1549): Failed to find provider info for com.motorola.blur.setupprovider
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/OtaApp  ( 1549): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1549): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1549): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/OtaApp  ( 1549): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1549): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1549): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1549): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/CaptivePortalTracker( 1023): NoActiveNetworkState{ when=-8ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/PollingManager( 1549): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/CaptivePortalTracker( 1023): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering( 1023): MasterInitialState.processMessage what=3
D/OtaApp  ( 1549): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/PollingManager( 1549): now: 526951 ,futureTime: 82580999
D/PollingManager( 1549): Polling alarm set to expire at: 82580999 Current Time: 526952
I/openssl ( 4354): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4354): Crypto mode 0 already enabled
D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
E/ActivityThread( 1549): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1549): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1549): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1549): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/OtaApp  ( 1549): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1549): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1549): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1549): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/OtaApp  ( 1549): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
D/MobileConnectivityChangeReceiver( 4393): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4393): onReceive CONNECTIVITY_CHANGE networkType=1
I/iu.Environment( 4463): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.SyncManager( 4463): SYNC; picasa accounts
I/iu.UploadsManager( 4463): num queued entries: 0
I/iu.UploadsManager( 4463): num updated entries: 0
,I/iu.SyncManager( 4463): NEXT; no task
,I/iu.Environment( 1400): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1400): num queued entries: 0
,I/iu.UploadsManager( 1400): num updated entries: 0
,I/iu.SyncManager( 1400): NEXT; no task
,I/CheckinService( 1400): Checkin interval check for package: unspecified last checkin: 1448278236198 min interval config: 0 actual interval: 485815
,D/DEBUG   ( 1549): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1549): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1549): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1549): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1549): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1549): onServiceConnected()
,D/GetNotificationsWS( 1549): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1549): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1549): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4354): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4354): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 4393): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4393): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 4463): GC_FOR_ALLOC freed 52K, 3% free 20804K/21288K, paused 13ms, total 13ms
,I/iu.Environment( 4463): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1400): Checkin interval check for package: unspecified last checkin: 1448278236198 min interval config: 0 actual interval: 485891
,D/OtaApp  ( 1549): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1549): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1023): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1549
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/OtaApp  ( 1549): [info] > Updatetime from metadata: 10
,D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm( 1549): GC_CONCURRENT freed 1898K, 38% free 10748K/17224K, paused 3ms+4ms, total 47ms
,D/OtaApp  ( 1549): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1549): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1549): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1549): [info] > Updatetime from metadata: 10
,D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1549): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1549): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
,D/DEBUG   ( 1549): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1549): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/IInputConnectionWrapper( 4023): showStatusIcon on inactive InputConnection
,W/ContextImpl( 1549): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,I/LaunchCheckinHandler( 1023): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,112
,D/dalvikvm( 1023): GC_EXPLICIT freed 1847K, 64% free 18171K/49260K, paused 4ms+10ms, total 96ms
,D/GetNotificationsWS( 1549): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1549): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1549): onServiceConnected()
D/GetNotificationsWS( 1549): onServiceConnected(): Registered for remote service callbacks...
,I/SundryService( 1549): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1549): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1549): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1549): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1023): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1549
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1549): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1549): [info] > Updatetime from metadata: 10
,D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1549): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1549): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1549): [info] > Updatetime from metadata: 10
,D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1549): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1549): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1549): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1549): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/CheckinRequestBuilder( 1400): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1400): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1400): Classify the device as Phone.
,I/CheckinTask( 1400): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1400): Checking schedule, now: 1448278722738 next: 1448871792729
,I/CheckinService( 1400): active receiver: disabled
,I/CheckinService( 1400): Checking schedule, now: 1448278722764 next: 1448871792729
,I/CheckinService( 1400): active receiver: disabled
,D/CheckinService( 1400): Recording last checkin time for package unspecified as 1448278722776
,D/GCM     ( 1340): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/jxcore-log( 4023): 2015-11-23T11:38:42.903Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:42.904Z SendDataConnector.js: got all data for this round
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:42.905Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 4023): 
I/jxcore-log( 4023): 2015-11-23T11:38:42.905Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4023): 
I/BtConnectorHelper( 4023): Disconnect outgoing peer: E0:DB:10:14:E2:C0
,I/BtToSocketBase( 4023): Stop ReceivingThread
I/BtToSocketBase( 4023): Stop SendingThread
I/BtToSocketBase( 4023): Close local in
I/BtToSocketBase( 4023): Close LocalOutputStream
,I/BtToSocketBase( 4023): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 4023): Close localHostSocket
I/BtToSocketBase( 4023): Close bt in
I/BtToSocketBase( 4023): Close bt out
I/BtToSocketBase( 4023): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 4023): Close bt socket
,I/BtToRequestSocket( 4023): Close server socket
I/jxcore-log( 4023): 2015-11-23T11:38:42.909Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): ---- round done--------
I/jxcore-log( 4023): 
I/jxcore-log( 4023): do fake peer & start
I/jxcore-log( 4023): 
I/jxcore-log( 4023): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:42.910Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 4023): 
I/jxcore-log( 4023): 2015-11-23T11:38:42.911Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:38:42.911Z SendDataConnector.js: do connect now
I/jxcore-log( 4023): 
,I/        ( 4023): Selected device address: 58:2A:F7:ED:96:BE, name: null
I/BTConnectToThread( 4023): Starting to connect
,W/BluetoothAdapter( 4023): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 4023): Connecting to null, at 58:2A:F7:ED:96:BE
,I/chromium( 4023): [INFO:CONSOLE(63)] "logCallback round[0] time: 9634 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 1772): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 4023): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]}
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f208a5c rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,D/GetConfigurationSnapshotOperation( 1340): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,W/bt-btif ( 1772): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,I/PhenotypeFlagCommitter( 1340): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1340): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1340): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/dalvikvm( 1340): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1340): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1340): VFY: replacing opcode 0x6e at 0x0033
,V/AlarmManager( 1023): sending alarm Alarm{43cbeb18 type 2 com.google.android.gms}
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/dalvikvm( 1340): GC_CONCURRENT freed 1567K, 37% free 10938K/17224K, paused 11ms+5ms, total 51ms
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/ConnectivityService( 1023): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/ModemStatsDSDetect( 1285): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1085): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
,I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1285): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1285): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1285): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f208a5c rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-24
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-4ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState receive service response
I/        ( 4023): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"}, typeCordovap2p._tcp.local.:
I/        ( 4023): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT9160, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 4023): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT9160, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,W/bt-l2cap( 1772): L2CAP - con rsp - bad ID. Exp: 5 Got: 3
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,W/Uploader( 1340):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1340): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/ActivityManager( 1023): Killing 4541:com.motorola.deviceauthenticator/u0a16 (adj 15): empty #9
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/BluetoothBondStateMachine( 1772): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 1772): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 1772): Entering PendingCommandState State
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,I/ActivityManager( 1023): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.BluetoothPairReceiver: pid=4820 uid=10016 gids={50016, 3002}
,D/dalvikvm(  279): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+9ms, total 30ms
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 33ms
,I/ActivityManager( 1023): Killing 4354:android.process.media/u0a18 (adj 15): empty #9
V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 1772): Ftp Service onStartCommand
V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
E/bt-btif ( 1772): services_to_search = 3fffffff
,E/bt-btif ( 1772): ****************search UUID = 1200***********
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/GetCommittedConfigurationOperation( 1340): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,I/wpa_supplicant( 4340): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,E/bt-btif ( 1772): services_to_search = 3ffffffe
,E/bt-btif ( 1772): ****************search UUID = 0100***********
,W/bt-btif ( 1772): new conn_srvc id:26, app_id:1
,W/bt-btif ( 1772): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 1772): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 4023): Starting to Handshake
,I/BTHandshakeSocketThread( 4023): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 4023): MESSAGE_WRITE 81 bytes.
,I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread started
,I/InputReader( 1023): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1023): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1023):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1023):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1023):   Scheme: "sms"
,I/ActivityManager( 1023): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4854 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1023): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1023):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1023):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1023):   Scheme: "smsto"
,I/PackageManager( 1023): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1023):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1023):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1023):   Scheme: "mms"
I/Launcher( 1301): Deferring update until onResume
,I/PackageManager( 1023): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1023):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1023):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1023):   Scheme: "mmsto"
I/Launcher( 1301): Deferring update until onResume
,I/PackageManager( 1023): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1023):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1023):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1023):   Scheme: "sms"
,I/PackageManager( 1023): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1023):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1023):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1023):   Scheme: "smsto"
,I/PackageManager( 1023): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1023):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1023):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1023):   Scheme: "mms"
,I/PackageManager( 1023): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1023):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1023):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1023):   Scheme: "mmsto"
,V/GmsNetworkLocationProvi( 1222): DISABLE
,I/GCoreNlp( 1222): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4854): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4854): MmsConfig.loadMmsSettings
,I/Babel   ( 4854): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4854): MmsConfig.loadFromDatabase
,W/Settings( 4854): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Babel   ( 4854): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4854): MmsConfig.loadFromResources
,E/Babel   ( 4854): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4854): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/ActivityManager( 1023): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4892 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1023): Killing 4372:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1023): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4911 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1023): Killing 4393:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2299): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1023): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4929 uid=10038 gids={50038, 3003, 1028, 1015}
,D/PackageBroadcastService( 1400): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1400): Null package name or gms related package.  Ignoreing.
I/ActivityManager( 1023): Killing 4406:com.android.chrome/u0a56 (adj 15): empty #9
W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Icing   ( 1400): updateResources: need to parse f{com.google.android.gms}
,I/ContactLocale( 4892): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4929): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4929): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4929): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4929): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 4929): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4929): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4929): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4929): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4929): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4929): VFY: replacing opcode 0x6e at 0x000a
,I/InternalIcingCorporaPro( 2299): UpdateCorporaTask done [took 253 ms] updated apps [took 253 ms] 
,D/Finsky  ( 4929): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4929): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4929): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4929): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4929): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4929): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4929): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4929): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4929): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4929): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4929): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4929): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4929): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4929): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4929): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1023): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4966 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4929): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4929): VFY: unable to resolve virtual method 9030: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4929): VFY: replacing opcode 0x6e at 0x0019
,D/Finsky  ( 4929): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Ads     ( 4929): Skipping gmscore version check
,D/Finsky  ( 4929): [1] Libraries$2.run: Finished loading 1 libraries.
,I/dalvikvm( 4929): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4929): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4929): VFY: replacing opcode 0x6e at 0x0017
,I/ActivityManager( 1023): Killing 4419:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 4966): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x42521270, skipping init
I/openssl ( 4966): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4966): Crypto mode 0 already enabled
,I/ActivityManager( 1023): Killing 4717:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
,D/Finsky  ( 4929): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Finsky  ( 4929): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-13
D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -13 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -13 target=com.android.internal.util.StateMachine$SmHandler }
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=139307 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139307 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState clear service request
,D/WifiP2pService( 1023): InactiveState{ when=-2ms what=139265 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=139265 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 4023): Cleared service requests
I/        ( 4023): Started peer discovery
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/CaptivePortalTracker( 1023): DelayedCaptiveCheckState{ when=-16ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1023): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1023): Checking http://216.58.209.46/generate_204
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/CaptivePortalTracker( 1023): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1023): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 1023): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1023): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1023): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-22
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-4ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-8ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 4023): Found 6 peers.
I/SS      ( 4023): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 4023): Peer(2): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 4023): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4023): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 4023): Peer(5): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 4023): Peer(6): A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1023): InactiveState{ when=0 what=139301 arg2=53 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139301 arg2=53 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState add service request
D/WifiP2pManager( 4023): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4023): Added service request
,W/bt-btif ( 1772): dm_pm_timer expires
,W/bt-btif ( 1772): dm_pm_timer expires 0
,W/bt-btif ( 1772): proc dm_pm_timer expires
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=139310 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139310 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState discover services
,I/        ( 4023): Started service discovery
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-40
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService( 1023):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1023):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,V/AlarmManager( 1023): sending alarm Alarm{43f947c0 type 3 android}
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-30
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-36
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: Android_2dc2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1023):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1023):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/BTConnectToThread( 4023): got MESSAGE_READ 80 bytes.
,I/BTConnectToThread( 4023): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6669","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 4023): HandshakeOk : HUAWEI-ALE-L21_PT6669
,I/HS      ( 4023): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT6669
,I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4023): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT6669
I/BtToSocketBase( 4023): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 4023): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 4023): mHTTPPort  set to : 35471
,I/BtConnectorHelper( 4023): Request socket is using : 35471
,I/BtToRequestSocket( 4023): Now accepting connections
,I/BtConnectorHelper( 4023): Calling ConnectionStatusUpdate with port :35471
,I/jxcore-log( 4023): 2015-11-23T11:39:02.090Z SendDataConnector.js: CLIENT connected to 35471, error: null
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:02.092Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 4023): 
,I/BtToRequestSocket( 4023): incoming data from: /127.0.0.1, port: 35471
,I/BtToRequestSocket( 4023): Set local streams
,I/jxcore-log( 4023): 2015-11-23T11:39:02.104Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 4023): 
,I/BtToRequestSocket( 4023): rin ended ---------------------------;
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:ff:f0 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT3069"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:ff:f0 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT3069"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState receive service response
I/        ( 4023): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT3069"}, typeCordovap2p._tcp.local.:
I/        ( 4023): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT3069"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT3069, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 4023): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT3069, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9241"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9241"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState receive service response
I/        ( 4023): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9241"}, typeCordovap2p._tcp.local.:
I/        ( 4023): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9241"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9241, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 4023): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9241, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/wpa_supplicant( 4340): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
D/WifiP2pService( 1023): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-14
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-40
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-4ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-4ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1023):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-6ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1023):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-42
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-47
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: S5-1
D/WifiP2pService( 1023):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1023):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,W/bt-btif ( 1772): dm_pm_timer expires
,W/bt-btif ( 1772): dm_pm_timer expires 0
W/bt-btif ( 1772): proc dm_pm_timer expires
,E/bt-btif ( 1772): bta_dm_pm_sniff BTM_SetPowerMode() returns ERROR status=3
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-5ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6816","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-7ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6816","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState receive service response
I/        ( 4023): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6816","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 4023): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6816","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT6816, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 4023): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT6816, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-41
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-10ms what=147477 obj=Device: Android_d8c3
D/WifiP2pService( 1023):  deviceAddress: 02:ee:bd:dd:33:d2
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-10ms what=147477 obj=Device: Android_d8c3
D/WifiP2pService( 1023):  deviceAddress: 02:ee:bd:dd:33:d2
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-24
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-27
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: G3-1
D/WifiP2pService( 1023):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=147477 obj=Device: G3-1
D/WifiP2pService( 1023):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:ee:bd:dd:33:d2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT699","ra":"50:2E:6C:AC:21:50"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:ee:bd:dd:33:d2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT699","ra":"50:2E:6C:AC:21:50"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState receive service response
,I/        ( 4023): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT699","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 4023): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT699","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT699, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 4023): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT699, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/jxcore-log( 4023): 2015-11-23T11:39:12.167Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:12.168Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:12.171Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:12.172Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:12.174Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 4023): 
,I/BtToSocketBase( 4023): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 4023): Disconnect outgoing peer: HUAWEI-ALE-L21_PT6669
,I/BtToSocketBase( 4023): Stop ReceivingThread
I/BtToSocketBase( 4023): Stop SendingThread
,I/BtToSocketBase( 4023): Close local in
,I/BtToSocketBase( 4023): Close LocalOutputStream
I/BtToSocketBase( 4023): Close localHostSocket
,I/BtToSocketBase( 4023): Close bt in
,I/BtToSocketBase( 4023): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 4023): Close bt out
I/BtToSocketBase( 4023): Close bt socket
,I/BtToRequestSocket( 4023): Close server socket
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [00:f4:6f:30:e0:6c]: 7, f, 2205
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f208f90 rs_disc_pending=0
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1772): new conn_srvc id:26, app_id:255
,W/bt-btif ( 1772): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 1772): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 4023): we got incoming connection
,I/BTHandshakeSocketThread( 4023): Creating BTHandshakeSocketThread
,I/BTListenerThread( 4023): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread started
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f208f90 rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 4023): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 4023): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 4023): MESSAGE_WRITE 81 bytes.
,I/HS      ( 4023): Incoming connection Hand Shake finished for : samsung-SM-G800F_PT9160
,I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4023): Starting the connected thread incoming : true, samsung-SM-G800F_PT9160
I/BtToSocketBase( 4023): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 4023): Creating BTConnectedThread
,I/BtConnectorHelper( 4023): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 4023): --DoOneRunRound started
,I/jxcore-log( 4023): 2015-11-23T11:39:16.371Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4023): 
,I/BtToRequestSocket( 4023): LocalHost address: localhost/127.0.0.1, port: 43200
,I/BtToRequestSocket( 4023): --DoOneRunRound ended
,I/jxcore-log( 4023): 2015-11-23T11:39:16.836Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:16.846Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:16.891Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:16.920Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:16.940Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:16.944Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:17.024Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:17.175Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:17.175Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:17.230Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 4023): 
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139307 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=139307 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState clear service request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139265 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=139265 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 4023): 2015-11-23T11:39:17.297Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 4023): 
I/        ( 4023): Cleared service requests
I/        ( 4023): Started peer discovery
,I/jxcore-log( 4023): 2015-11-23T11:39:17.305Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:17.309Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:17.335Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:17.375Z SendDataTCPServer.js: TCP/IP server has received 24576 bytes of data
I/jxcore-log( 4023): 
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-21
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-22
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-34
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-11ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-12ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-13ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-13ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 4023): 2015-11-23T11:39:17.442Z SendDataTCPServer.js: TCP/IP server has received 26556 bytes of data
I/jxcore-log( 4023): 
D/WifiP2pService( 1023): InactiveState{ when=0 what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): DefaultState{ when=-1ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=0 what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): DefaultState{ when=0 what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=0 what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=0 what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 4023): 2015-11-23T11:39:17.452Z SendDataTCPServer.js: TCP/IP server has received 28536 bytes of data
I/jxcore-log( 4023): 
I/SS      ( 4023): Found 12 peers.
I/SS      ( 4023): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 4023): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 4023): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 4023): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4023): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 4023): Peer(6): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 4023): Peer(7): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 4023): Peer(8): G3-1 02:9a:02:7b:60:ac
I/SS      ( 4023): Peer(9): Note4-1 92:b6:86:43:73:1c
I/SS      ( 4023): Peer(10): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 4023): Peer(11): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 4023): Peer(12): Android_63cc 82:01:84:6b:e8:5d
D/WifiP2pService( 1023): InactiveState{ when=0 what=139301 arg2=60 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139301 arg2=60 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState add service request
D/WifiP2pManager( 4023): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4023): Added service request
,I/jxcore-log( 4023): 2015-11-23T11:39:17.493Z SendDataTCPServer.js: TCP/IP server has received 30516 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:17.515Z SendDataTCPServer.js: TCP/IP server has received 32496 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:17.679Z SendDataTCPServer.js: TCP/IP server has received 34476 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:17.705Z SendDataTCPServer.js: TCP/IP server has received 36456 bytes of data
I/jxcore-log( 4023): 
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 4023): 2015-11-23T11:39:17.779Z SendDataTCPServer.js: TCP/IP server has received 38436 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:17.783Z SendDataTCPServer.js: TCP/IP server has received 40416 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:17.786Z SendDataTCPServer.js: TCP/IP server has received 42396 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:17.824Z SendDataTCPServer.js: TCP/IP server has received 44376 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:17.868Z SendDataTCPServer.js: TCP/IP server has received 46356 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:17.997Z SendDataTCPServer.js: TCP/IP server has received 48336 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:18.000Z SendDataTCPServer.js: TCP/IP server has received 50316 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:18.056Z SendDataTCPServer.js: TCP/IP server has received 52296 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:18.159Z SendDataTCPServer.js: TCP/IP server has received 54276 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:18.163Z SendDataTCPServer.js: TCP/IP server has received 56256 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:18.210Z SendDataTCPServer.js: TCP/IP server has received 58236 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:18.233Z SendDataTCPServer.js: TCP/IP server has received 60216 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:18.242Z SendDataTCPServer.js: TCP/IP server has received 62196 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:18.276Z SendDataTCPServer.js: TCP/IP server has received 64176 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:18.293Z SendDataTCPServer.js: TCP/IP server has received 66156 bytes of data
I/jxcore-log( 4023): 
,I/wpa_supplicant( 4340): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/wpa_supplicant( 4340): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 4023): 2015-11-23T11:39:18.381Z SendDataTCPServer.js: TCP/IP server has received 68136 bytes of data
I/jxcore-log( 4023): 
I/jxcore-log( 4023): 2015-11-23T11:39:18.386Z SendDataTCPServer.js: TCP/IP server has received 70116 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:18.396Z SendDataTCPServer.js: TCP/IP server has received 72096 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:18.415Z SendDataTCPServer.js: TCP/IP server has received 74076 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:18.455Z SendDataTCPServer.js: TCP/IP server has received 81996 bytes of data
I/jxcore-log( 4023): 
,D/WifiP2pService( 1023): InactiveState{ when=-2ms what=139310 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=139310 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState discover services
,I/        ( 4023): Started service discovery
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-29
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 4023): 2015-11-23T11:39:18.567Z SendDataTCPServer.js: TCP/IP server has received 83976 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:18.605Z SendDataTCPServer.js: TCP/IP server has received 89916 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:18.620Z SendDataTCPServer.js: TCP/IP server has received 91896 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:18.753Z SendDataTCPServer.js: TCP/IP server has received 93876 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:18.802Z SendDataTCPServer.js: TCP/IP server has received 95856 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:18.879Z SendDataTCPServer.js: TCP/IP server has received 97836 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:18.932Z SendDataTCPServer.js: TCP/IP server has received 99816 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:18.965Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 4023): 
,W/bt-btif ( 1772): invalid rfc slot id: 17
,I/BtToSocketBase( 4023): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 4023): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 4023): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT9160
,I/BtToSocketBase( 4023): Stop ReceivingThread
I/BtToSocketBase( 4023): Stop SendingThread
,I/BtToSocketBase( 4023): Close local in
,I/BtToSocketBase( 4023): Close LocalOutputStream
,I/BtToSocketBase( 4023): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4023): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 4023): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT9160
I/BtToSocketBase( 4023): Close localHostSocket
,I/BtToSocketBase( 4023): Close bt in
,I/BtToSocketBase( 4023): Close bt out
I/BtToSocketBase( 4023): Close bt in
,I/BtToSocketBase( 4023): Close bt out
I/BtToSocketBase( 4023): Close bt socket
,I/BtToSocketBase( 4023): Close bt socket
,I/jxcore-log( 4023): 2015-11-23T11:39:19.117Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4023): 
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f208f90 rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-29
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-12ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-13ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,W/bt-rfcomm( 1772): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
,W/bt-rfcomm( 1772): RFCOMM_DisconnectInd LCID:0x46
,W/bt-btif ( 1772): btif_dm_search_services_evt:SDP failed after bonding re-attempting
,E/bt-btif ( 1772): services_to_search = 3fffffff
,E/bt-btif ( 1772): ****************search UUID = 1200***********
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-6ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-7ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState receive service response
I/        ( 4023): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"}, typeCordovap2p._tcp.local.:
I/        ( 4023): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT9160, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 4023): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT9160, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/jxcore-log( 4023): 2015-11-23T11:39:22.180Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:22.180Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:22.182Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:22.184Z SendDataConnector.js: do connect now
I/jxcore-log( 4023): 
,I/        ( 4023): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 4023): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 4023): Starting to connect
,W/BluetoothAdapter( 4023): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1772): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 4023): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[141]}
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/dalvikvm( 1023): GC_EXPLICIT freed 2151K, 64% free 18161K/49260K, paused 4ms+10ms, total 96ms
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-22
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-4ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-7ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,E/bt-btif ( 1772): bta_dm_pm_btm_status  hci_status=34
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-14
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-27
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-36
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: G3-1
D/WifiP2pService( 1023):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147477 obj=Device: G3-1
D/WifiP2pService( 1023):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1023):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1023):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=139307 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139307 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState clear service request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139265 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139265 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 4023): Cleared service requests
I/        ( 4023): Started peer discovery
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,W/bt-sdp  ( 1772): SDP - Rcvd L2CAP disc cfm, unknown CID: 0x41
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-29
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-32
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-8ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=-1ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139283 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=139283 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=-1ms what=139283 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 4023): Found 10 peers.
I/SS      ( 4023): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 4023): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 4023): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4023): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 4023): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 4023): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 4023): Peer(7): Note4-1 92:b6:86:43:73:1c
I/SS      ( 4023): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 4023): Peer(9): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 4023): Peer(10): Android_63cc 82:01:84:6b:e8:5d
D/WifiP2pService( 1023): InactiveState{ when=0 what=139301 arg2=66 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139301 arg2=66 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState add service request
D/WifiP2pManager( 4023): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4023): Added service request
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
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=139310 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139310 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState discover services
,I/        ( 4023): Started service discovery
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-37
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1023):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -37 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1023):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -37 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [f8:cf:c5:d9:e5:61]: 6, f, 410d
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,W/bt-btif ( 1772): new conn_srvc id:26, app_id:255
W/bt-btif ( 1772): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 1772): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 4023): we got incoming connection
,I/BTHandshakeSocketThread( 4023): Creating BTHandshakeSocketThread
I/BTListenerThread( 4023): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread started
,I/BTListenerThread( 4023): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 4023): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8557","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 4023): MESSAGE_WRITE 81 bytes.
I/HS      ( 4023): Incoming connection Hand Shake finished for : motorola-Nexus 6_PT8557
I/BtConnectorHelper( 4023): Starting the connected thread incoming : true, motorola-Nexus 6_PT8557
I/BtToSocketBase( 4023): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4023): Creating BTConnectedThread
,I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 4023): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 4023): --DoOneRunRound started
I/BtToRequestSocket( 4023): LocalHost address: localhost/127.0.0.1, port: 43200
,I/BtToRequestSocket( 4023): --DoOneRunRound ended
,I/jxcore-log( 4023): 2015-11-23T11:39:37.966Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:38.390Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:38.455Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:38.465Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:38.470Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:38.478Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:38.487Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:38.515Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 4023): 
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/jxcore-log( 4023): 2015-11-23T11:39:38.786Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:38.790Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:38.800Z SendDataTCPServer.js: TCP/IP server has received 24576 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:38.835Z SendDataTCPServer.js: TCP/IP server has received 26556 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:38.915Z SendDataTCPServer.js: TCP/IP server has received 28536 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:38.922Z SendDataTCPServer.js: TCP/IP server has received 30516 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:38.931Z SendDataTCPServer.js: TCP/IP server has received 34476 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:38.964Z SendDataTCPServer.js: TCP/IP server has received 46356 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:38.968Z SendDataTCPServer.js: TCP/IP server has received 48336 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:39.005Z SendDataTCPServer.js: TCP/IP server has received 58236 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:39.010Z SendDataTCPServer.js: TCP/IP server has received 60216 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:39.021Z SendDataTCPServer.js: TCP/IP server has received 64176 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:39.057Z SendDataTCPServer.js: TCP/IP server has received 76056 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:39.068Z SendDataTCPServer.js: TCP/IP server has received 78036 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:39.093Z SendDataTCPServer.js: TCP/IP server has received 80016 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:39.125Z SendDataTCPServer.js: TCP/IP server has received 87936 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:39.131Z SendDataTCPServer.js: TCP/IP server has received 89916 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:39.136Z SendDataTCPServer.js: TCP/IP server has received 91896 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:39.146Z SendDataTCPServer.js: TCP/IP server has received 93876 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:39:39.175Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 4023): 
,W/bt-btif ( 1772): invalid rfc slot id: 22
,I/BtToSocketBase( 4023): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 4023): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4023): Disconnect:::Stop : mBtToServerSocket :motorola-Nexus 6_PT8557
,I/BtToSocketBase( 4023): Stop ReceivingThread
,I/BtToSocketBase( 4023): Stop SendingThread
I/BtToSocketBase( 4023): Close local in
,I/BtToSocketBase( 4023): Close LocalOutputStream
,W/bt-rfcomm( 1772): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
,W/bt-rfcomm( 1772): RFCOMM_DisconnectInd LCID:0x4d
,I/BtToSocketBase( 4023): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4023): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 4023): Disconnect:::Stop : mBtToServerSocket :motorola-Nexus 6_PT8557
,I/BtToSocketBase( 4023): Close localHostSocket
I/BtToSocketBase( 4023): Close bt in
,I/BtToSocketBase( 4023): Close bt out
I/BtToSocketBase( 4023): Close bt in
,I/BtToSocketBase( 4023): Close bt socket
,I/BtToSocketBase( 4023): Close bt out
,I/BtToSocketBase( 4023): Close bt socket
,I/jxcore-log( 4023): 2015-11-23T11:39:39.261Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4023): 
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f20836c rs_disc_pending=0
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-22
D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: Android_2dc2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-27
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: G3-1
D/WifiP2pService( 1023):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147477 obj=Device: G3-1
D/WifiP2pService( 1023):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -27 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 4340): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 4340): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/wpa_supplicant( 4340): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
D/WifiP2pService( 1023): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 02:ee:bd:dd:33:d2
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 02:ee:bd:dd:33:d2
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-14ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
,D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-16ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-40
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-47
,D/WifiP2pService( 1023): InactiveState{ when=-5ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1023):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-5ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1023):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-5ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-6ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6816","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6816","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState receive service response
I/        ( 4023): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6816","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 4023): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6816","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT6816, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 4023): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT6816, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-33
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-9ms what=147477 obj=Device: Android_50a5
D/WifiP2pService( 1023):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-9ms what=147477 obj=Device: Android_50a5
D/WifiP2pService( 1023):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-30
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-32
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,E/bt-btif ( 1772): bta_dm_pm_btm_status  hci_status=34
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139307 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139307 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState clear service request
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=139265 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139265 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 4023): Cleared service requests
,I/        ( 4023): Started peer discovery
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-21
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-3ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-7ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=0 what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 4023): Found 10 peers.
I/SS      ( 4023): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4023): Peer(2): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 4023): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 4023): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 4023): Peer(5): G3-1 02:9a:02:7b:60:ac
I/SS      ( 4023): Peer(6): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 4023): Peer(7): Note4-1 92:b6:86:43:73:1c
I/SS      ( 4023): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 4023): Peer(9): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 4023): Peer(10): Android_63cc 82:01:84:6b:e8:5d
D/WifiP2pService( 1023): InactiveState{ when=0 what=139301 arg2=71 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139301 arg2=71 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState add service request
D/WifiP2pManager( 4023): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4023): Added service request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139310 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=139310 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState discover services
,I/        ( 4023): Started service discovery
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-14
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-43
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1023):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1023):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-29
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-3ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-4ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
,D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,V/AlarmManager( 1023): sending alarm Alarm{440419d8 type 3 android}
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3613","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3613","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState receive service response
I/        ( 4023): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3613","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 4023): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3613","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT3613, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 4023): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT3613, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-41
D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: Note3-1
D/WifiP2pService( 1023):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note3-1
D/WifiP2pService( 1023):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,E/bt-btif ( 1772): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1772): invalid rfc slot id: 23
,I/BTConnectToThread( 4023): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/LaunchCheckinHandler( 1023): cleanup(): cleared. Last call was 76717 ms ago
,I/ActivityManager( 1023): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=5068 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/BluetoothBondStateMachine( 1772): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
E/bt-btif ( 1772): property type:3, len:0 is invalid
D/BluetoothAdapterProperties( 1772): setRemoteTrust() result=true
D/BluetoothAdapterProperties( 1772): Failed to remove device: 58:2A:F7:ED:96:BE
E/        ( 1772): ### ASSERT : external/bluetooth/bluedroid/main/../btif/src/btif_dm.c line 1250 storing remote services failed (1) ###
E/BluetoothRemoteDevices( 1772): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 3
I/BluetoothBondStateMachine( 1772): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 1772): StableState(): Entering Off State,
,D/BluetoothMetrics( 1772): btclass1f00
,D/Checkin ( 1772): publish the event [tag = MOT_BT event name = PAIRING]
,I/CONNEC  ( 4023): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 4023): 2015-11-23T11:40:06.417Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 4023): 
I/jxcore-log( 4023): 2015-11-23T11:40:06.418Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:40:06.418Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4023): 
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
I/ActivityManager( 1023): Killing 4820:com.motorola.deviceauthenticator/u0a16 (adj 15): empty #9
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,I/ActivityManager( 1023): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.BluetoothPairReceiver: pid=5101 uid=10016 gids={50016, 3002}
,I/ActivityManager( 1023): Killing 4854:com.google.android.talk/u0a70 (adj 15): empty #9
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 1772): Ftp Service onStartCommand
V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-40
D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139307 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139307 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState clear service request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139265 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139265 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 4023): Cleared service requests
,I/        ( 4023): Started peer discovery
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-40
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139283 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139283 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=-1ms what=139283 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 4023): Found 12 peers.
I/SS      ( 4023): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 4023): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4023): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 4023): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 4023): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 4023): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 4023): Peer(7): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 4023): Peer(8): Note4-1 92:b6:86:43:73:1c
I/SS      ( 4023): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 4023): Peer(10): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 4023): Peer(11): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 4023): Peer(12): Note3-1 ea:50:8b:de:28:a3
D/WifiP2pService( 1023): InactiveState{ when=0 what=139301 arg2=76 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139301 arg2=76 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState add service request
D/WifiP2pManager( 4023): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4023): Added service request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139310 arg2=77 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139310 arg2=77 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState discover services
,I/        ( 4023): Started service discovery
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-23
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-40
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService( 1023):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService( 1023):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-5ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-5ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-25
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: G3-1
D/WifiP2pService( 1023):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -25 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=147477 obj=Device: G3-1
D/WifiP2pService( 1023):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -25 target=com.android.internal.util.StateMachine$SmHandler }
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-36
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-41
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1023):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1023):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-6ms what=147477 obj=Device: Android_d8c3
D/WifiP2pService( 1023):  deviceAddress: 02:ee:bd:dd:33:d2
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-7ms what=147477 obj=Device: Android_d8c3
D/WifiP2pService( 1023):  deviceAddress: 02:ee:bd:dd:33:d2
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT626","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT626","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState receive service response
I/        ( 4023): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT626","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 4023): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT626","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT626, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 4023): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT626, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/jxcore-log( 4023): 2015-11-23T11:40:11.424Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:40:11.452Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 4023): 
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
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-39
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService( 1023):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -39 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1023):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -39 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-14
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -14 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-22
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-49
,D/WifiP2pService( 1023): InactiveState{ when=-7ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-7ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-7ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-7ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/jxcore-log( 4023): 2015-11-23T11:40:16.454Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:40:16.455Z SendDataConnector.js: Connect (retry count 2) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:40:16.457Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:40:16.458Z SendDataConnector.js: do connect now
I/jxcore-log( 4023): 
,I/        ( 4023): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 4023): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 4023): Starting to connect
,W/BluetoothAdapter( 4023): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1772): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 4023): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[146]}
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139307 arg2=78 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139307 arg2=78 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState clear service request
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=139265 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139265 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 4023): Cleared service requests
,I/        ( 4023): Started peer discovery
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-14
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139283 arg2=80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139283 arg2=80 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=-1ms what=139283 arg2=80 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 4023): Found 14 peers.
I/SS      ( 4023): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 4023): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 4023): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 4023): Peer(4): G3-1 02:9a:02:7b:60:ac
I/SS      ( 4023): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 4023): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 4023): Peer(7): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 4023): Peer(8): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 4023): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4023): Peer(10): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 4023): Peer(11): G3s-1 a2:39:f7:70:12:80
I/SS      ( 4023): Peer(12): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 4023): Peer(13): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 4023): Peer(14): Note3-1 ea:50:8b:de:28:a3
D/WifiP2pService( 1023): InactiveState{ when=0 what=139301 arg2=81 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139301 arg2=81 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState add service request
D/WifiP2pManager( 4023): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4023): Added service request
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=139310 arg2=82 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139310 arg2=82 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState discover services
,I/        ( 4023): Started service discovery
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-23
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService( 1023):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService( 1023):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-23
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService( 1023):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService( 1023):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
,I/BluetoothBondStateMachine( 1772): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 1772): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 1772): Entering PendingCommandState State
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 1772): services_to_search = 3fffffff
,E/bt-btif ( 1772): ****************search UUID = 1200***********
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-14
I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-30
I/wpa_supplicant( 4340): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-32
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-48
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,E/bt-btif ( 1772): services_to_search = 3ffffffe
,E/bt-btif ( 1772): ****************search UUID = 0100***********
,W/bt-btif ( 1772): new conn_srvc id:26, app_id:1
,W/bt-btif ( 1772): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 1772): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 4023): Starting to Handshake
,I/BTHandshakeSocketThread( 4023): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 4023): MESSAGE_WRITE 81 bytes.
,I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread started
,I/BTConnectToThread( 4023): got MESSAGE_READ 80 bytes.
,I/BTConnectToThread( 4023): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6669","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 4023): HandshakeOk : HUAWEI-ALE-L21_PT6669
I/HS      ( 4023): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT6669
,I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4023): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT6669
I/BtToSocketBase( 4023): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 4023): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 4023): mHTTPPort  set to : 57653
,I/BtConnectorHelper( 4023): Request socket is using : 57653
,I/BtToRequestSocket( 4023): Now accepting connections
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/BtConnectorHelper( 4023): Calling ConnectionStatusUpdate with port :57653
,I/jxcore-log( 4023): 2015-11-23T11:40:23.612Z SendDataConnector.js: CLIENT connected to 57653, error: null
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:40:23.613Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 4023): 
,I/BtToRequestSocket( 4023): incoming data from: /127.0.0.1, port: 57653
,I/BtToRequestSocket( 4023): Set local streams
,I/jxcore-log( 4023): 2015-11-23T11:40:23.625Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 4023): 
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,I/BtToRequestSocket( 4023): rin ended ---------------------------;
,E/bt-btif ( 1772): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1772): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 4 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 5 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 6 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 7 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1772): Index: 8 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 1772): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BluetoothAdapterProperties( 1772): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 1772): Failed to remove device: 58:2A:F7:ED:96:BE
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 1772): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 1772): StableState(): Entering Off State
,D/BluetoothMetrics( 1772): btclass1f00
,D/Checkin ( 1772): publish the event [tag = MOT_BT event name = PAIRING]
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5500"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5500"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState receive service response
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/        ( 4023): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5500"}, typeCordovap2p._tcp.local.:
,I/        ( 4023): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5500"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT5500, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 4023): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT5500, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 4023): 2015-11-23T11:40:24.737Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 4023): 
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/jxcore-log( 4023): 2015-11-23T11:40:25.730Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:40:26.425Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 4023): 
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/jxcore-log( 4023): 2015-11-23T11:40:27.032Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:40:27.663Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 4023): 
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-36
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-42
D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1023):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1023):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: Android_d8c3
D/WifiP2pService( 1023):  deviceAddress: 02:ee:bd:dd:33:d2
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_d8c3
D/WifiP2pService( 1023):  deviceAddress: 02:ee:bd:dd:33:d2
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState receive service response
I/        ( 4023): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"}, typeCordovap2p._tcp.local.:
I/        ( 4023): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9160"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT9160, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 4023): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT9160, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,E/bt-btm  ( 1772): RS in progress - Set DISC Pending flag in btm_sec_send_hci_disconnect to delay disconnect
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-35
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: Android_50a5
D/WifiP2pService( 1023):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_50a5
D/WifiP2pService( 1023):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -35 target=com.android.internal.util.StateMachine$SmHandler }
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-59
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: S5-1
D/WifiP2pService( 1023):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -59 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=147477 obj=Device: S5-1
D/WifiP2pService( 1023):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -59 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139307 arg2=83 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=139307 arg2=83 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState clear service request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139265 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139265 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 4023): Cleared service requests
I/        ( 4023): Started peer discovery
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-45
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService( 1023):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService( 1023):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=0 what=139283 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=139283 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=0 what=139283 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 4023): Found 15 peers.
I/SS      ( 4023): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 4023): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 4023): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 4023): Peer(4): G3-1 02:9a:02:7b:60:ac
I/SS      ( 4023): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 4023): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 4023): Peer(7): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 4023): Peer(8): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 4023): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4023): Peer(10): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 4023): Peer(11): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 4023): Peer(12): G3s-1 a2:39:f7:70:12:80
I/SS      ( 4023): Peer(13): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 4023): Peer(14): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 4023): Peer(15): Note3-1 ea:50:8b:de:28:a3
D/WifiP2pService( 1023): InactiveState{ when=0 what=139301 arg2=86 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=139301 arg2=86 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState add service request
D/WifiP2pManager( 4023): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4023): Added service request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=139310 arg2=87 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=139310 arg2=87 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState discover services
I/        ( 4023): Started service discovery
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-13
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-36
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1023):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1023):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 4023): 2015-11-23T11:40:37.664Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:40:37.664Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:40:37.665Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4023): 
I/jxcore-log( 4023): 2015-11-23T11:40:37.665Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:40:37.666Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 4023): 
I/BtToSocketBase( 4023): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 4023): Disconnect outgoing peer: HUAWEI-ALE-L21_PT6669
I/BtToSocketBase( 4023): Stop ReceivingThread
I/BtToSocketBase( 4023): Stop SendingThread
I/BtToSocketBase( 4023): Close local in
,I/BtToSocketBase( 4023): Close LocalOutputStream
I/BtToSocketBase( 4023): Close localHostSocket
I/BtToSocketBase( 4023): Close bt in
I/BtToSocketBase( 4023): Close bt out
,I/BtToSocketBase( 4023): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 4023): Close bt socket
,I/BtToRequestSocket( 4023): Close server socket
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-14
,I/wpa_supplicant( 4340): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-31
D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/jxcore-log( 4023): 2015-11-23T11:40:42.666Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:40:42.666Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:40:47.669Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:40:47.669Z SendDataConnector.js: Connect (retry count 3) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 4023): 
I/jxcore-log( 4023): 2015-11-23T11:40:47.669Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:40:47.669Z SendDataConnector.js: do connect now
I/jxcore-log( 4023): 
,I/        ( 4023): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
I/        ( 4023): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
I/BTConnectToThread( 4023): Starting to connect
,W/BluetoothAdapter( 4023): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1772): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 4023): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[148]}
,I/wpa_supplicant( 4340): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 4340): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 4340): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/wpa_supplicant( 4340): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: nul,l
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2088a0 rs_disc_pending=1
E/bt-btif ( 1772): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1772): bta_dm_check_av:0
I/BTConnectToThread( 4023): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
W/bt-btif ( 1772): invalid rfc slot id: 26
W/bt-btif ( 1772): invalid rfc slot id: 25
,I/CONNEC  ( 4023): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 4023): 2015-11-23T11:40:59.906Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 4023): 
I/jxcore-log( 4023): 2015-11-23T11:40:59.906Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:40:59.906Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4023): 
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,V/AlarmManager( 1023): sending alarm Alarm{42dbffd0 type 3 android}
,W/bt-btm  ( 1772): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f20914c rs_disc_pending=2
W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1772): l2cu_get_conn_role 0
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [f8:95:c7:87:3c:51]: 6, 10f, 608
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 1772): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 1772): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 1772): Entering PendingCommandState State
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 1772): services_to_search = 3fffffff
,E/bt-btif ( 1772): ****************search UUID = 1200***********
,I/wpa_supplicant( 4340): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 4340): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 4340): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 4340): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 4340): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,D/WifiP2pService( 1023): InactiveState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 02:ee:bd:dd:33:d2
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-4ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 02:ee:bd:dd:33:d2
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-15ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-16ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-17ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-8ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,E/bt-btif ( 1772): services_to_search = 3ffffffe
,E/bt-btif ( 1772): ****************search UUID = 0100***********
W/bt-btif ( 1772): new conn_srvc id:26, app_id:255
W/bt-btif ( 1772): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 1772): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 4023): we got incoming connection
,I/BTHandshakeSocketThread( 4023): Creating BTHandshakeSocketThread
I/BTListenerThread( 4023): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread started
,I/BTListenerThread( 4023): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 4023): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3952","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 4023): MESSAGE_WRITE 81 bytes.
I/HS      ( 4023): Incoming connection Hand Shake finished for : LGE-LG-H815_PT3952
,I/BTHandshakeSocketThread( 4023): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4023): Starting the connected thread incoming : true, LGE-LG-H815_PT3952
,I/BtToSocketBase( 4023): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 4023): Creating BTConnectedThread
,I/BtConnectorHelper( 4023): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 4023): --DoOneRunRound started
,I/BtToRequestSocket( 4023): LocalHost address: localhost/127.0.0.1, port: 43200
,I/jxcore-log( 4023): 2015-11-23T11:41:03.678Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4023): 
,I/BtToRequestSocket( 4023): --DoOneRunRound ended
,W/bt-sdp  ( 1772): process_service_search_attr_rsp
,E/bt-btif ( 1772): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1772): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 2 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 3 uuid:0000112d-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1772): Index: 4 uuid:0000110e-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1772): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1772): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1772): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1772): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 1772): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 1772): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 1772): Failed to remove device: F8:95:C7:87:3C:51
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 1772): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 1772): StableState(): Entering Off State
,D/BluetoothMetrics( 1772): btclass5a020c
,D/Checkin ( 1772): publish the event [tag = MOT_BT event name = PAIRING]
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4023): 2015-11-23T11:41:04.082Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:04.089Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:04.095Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 4023): 
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
,I/jxcore-log( 4023): 2015-11-23T11:41:04.166Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:04.171Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:04.181Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:04.271Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:04.304Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:04.334Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:04.384Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:04.416Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:04.577Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:04.615Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:04.641Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:04.675Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:04.714Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:04.747Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:04.756Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:04.795Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:04.856Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:04.863Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:04.905Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:04.907Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:04.909Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:04.960Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:05.045Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:05.075Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:05.268Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:05.342Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:05.403Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:05.440Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:05.488Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:05.491Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 4023): 
,W/bt-btif ( 1772): invalid rfc slot id: 24
,I/BtToSocketBase( 4023): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4023): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 4023): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT3952
I/BtToSocketBase( 4023): Stop ReceivingThread
,I/BtToSocketBase( 4023): Stop SendingThread
I/BtToSocketBase( 4023): Close local in
,I/BtToSocketBase( 4023): Close LocalOutputStream
,I/BtToSocketBase( 4023): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4023): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 4023): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT3952
I/BtToSocketBase( 4023): Close localHostSocket
I/BtToSocketBase( 4023): Close bt in
,I/BtToSocketBase( 4023): Close bt in
I/BtToSocketBase( 4023): Close bt out
,I/BtToSocketBase( 4023): Close bt out
I/BtToSocketBase( 4023): Close bt socket
,I/BtToSocketBase( 4023): Close bt socket
,I/jxcore-log( 4023): 2015-11-23T11:41:05.556Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4023): 
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f20914c rs_disc_pending=0
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 1772): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
,W/bt-rfcomm( 1772): RFCOMM_DisconnectInd LCID:0x41
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4529): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/jxcore-log( 4023): 2015-11-23T11:41:09.914Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:09.915Z SendDataConnector.js: Connect (retry count 4) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 4023): 
I/jxcore-log( 4023): 2015-11-23T11:41:09.915Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): 2015-11-23T11:41:09.916Z SendDataConnector.js: do connect now
I/jxcore-log( 4023): 
,I/        ( 4023): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/BTConnectToThread( 4023): Starting to connect
,W/BluetoothAdapter( 4023): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 4023): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,D/BTIF_SOCK( 1772): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 4023): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[150]}
,I/wpa_supplicant( 4340): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 4340): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 4340): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 4340): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 4340): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,I/wpa_supplicant( 4340): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,D/WifiP2pService( 1023): InactiveState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-11ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-12ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-18ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-19ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-24ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-25ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-16ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-17ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-17ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-17ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 4340): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/TCMD    (  458): NL - Read 1000 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/TCMD    (  458): NL - Read 68 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
D/TCMD    (  458): NL - Read 68 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
,D/WifiStateMachine( 1023): handleMessage: E msg.what=147460
,D/Tethering( 1023): InitialState.processMessage what=4
D/WifiStateMachine( 1023): processMsg: ConnectedState
D/WifiStateMachine( 1023): processMsg: L2ConnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): Network connection lost
D/WifiStateMachine( 1023): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1023): setSuspendOptimizationsNative: 1 true
,D/Tethering( 1023): sendTetherStateChangedBroadcast 0, 0, 0
V/ConnectivityService( 1023): WiFi NOT Tethered!
,D/WifiP2pService( 1023): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 4340): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 4340): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  274): Clearing all IP addresses on wlan0
D/TCMD    (  458): NL - Read 60 bytes from update socket.
D/TCMD    (  458): NL - ignore NL message, type = 21
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiStateMachine( 1023): addressRemoved: 192.168.1.123/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1023): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1023): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1023): connected time updated 590626
D/ConnectivityService( 1023): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1023): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1023): Attempting to switch to mobile
D/ConnectivityService( 1023): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1023): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1023): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1023): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1023): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1023): invokeExitMethods: ConnectedState
D/Checkin ( 1023): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1023): invokeExitMethods: L2ConnectedState
I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1085): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1085): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/WifiStateMachine( 1023): Stopping DHCP and clearing IP
D/WifiStateMachine( 1023): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1023): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 4340): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 4340): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  274): Clearing all IP addresses on wlan0
,D/ConnectivityService( 1023): resetConnections(wlan0, 3)
D/NetUtils( 1023): android_net_utils_resetConnections in env=0x5ff8b688 clazz=0x89000001 iface=wlan0 mask=0x3
,V/NativeCrypto( 1340): Read error: ssl=0x62d45100: I/O error during system call, Connection timed out
,V/NativeCrypto( 1340): SSL shutdown failed: ssl=0x62d45100: I/O error during system call, Broken pipe
,I/jxcore-log( 4023): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 4023): 
,D/WifiStateMachine( 1023): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/jxcore-log( 4023): The Coordinator has disconnected!
I/jxcore-log( 4023): 
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1023): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1023): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine( 1023): invokeEnterMethods: DisconnectedState
,D/Checkin ( 1023): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=147462
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131101
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): processMsg: DriverStartedState
D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131216
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): processMsg: DriverStartedState
D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131216
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): processMsg: DriverStartedState
D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
D/WifiStateMachine( 1023): processMsg: DefaultState
,D/WifiStateMachine( 1023): handleMessage: X
,D/Nat464Xlat( 1023): requiresClat: netType=1, hasIPv4Address=false
I/ModemStatsDSDetect( 1285): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1285): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1285): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1023): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1023): Attempting to switch to mobile
D/ConnectivityService( 1023): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1023): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1023): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1023): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1285): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1285): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1285): onReceive() - done, currentInetCondition=0
,I/jxcore-log( 4023): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): printNetworkInfo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): found interfaceName: lo
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 4023): 
,I/jxcore-log( 4023): Turning Wifi off
I/jxcore-log( 4023): 
D/WifiService( 1023): setWifiEnabled: false pid=4023, uid=10397
E/WifiService( 1023): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiStateMachine( 1023): handleMessage: E msg.what=131084
,D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): processMsg: DriverStartedState
D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1023): transitionTo: destState=WaitForP2pDisableState
D/WifiStateMachine( 1023): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1023): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
,D/WifiStateMachine( 1023): invokeExitMethods: DisconnectedState
,W/Settings( 1244): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1269): Active network info is not available
E/XTCC-3.0.0.2(  580): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  580): [WwanPosMgr] handleConnectivtyStatusChange failed
W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1244): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiStateMachine( 1023): invokeExitMethods: ConnectModeState
E/XTCC-3.0.0.2(  580): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  580): [CSMgr] handleConnectivtyStatusChange failed
D/WifiStateMachine( 1023): invokeExitMethods: DriverStartedState
E/WifiStateMachine( 1023): Unexpected BatchedScanResults :OK
I/jxcore-log( 4023): Turning Wifi back on
I/jxcore-log( 4023): 
D/WifiStateMachine( 1023): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1023): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
,D/WifiStateMachine( 1023): invokeEnterMethods: WaitForP2pDisableState
D/WifiP2pService( 1023): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pDisablingState
D/WifiP2pService( 1023): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): p2p socket connection lost
,D/WifiP2pService( 1023): P2pDisabledState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131205
D/WifiStateMachine( 1023): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1023): transitionTo: destState=SupplicantStoppingState
D/WifiStateMachine( 1023): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1023): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1023): invokeExitMethods: WaitForP2pDisableState
D/WifiStateMachine( 1023): invokeExitMethods: SupplicantStartedState
D/WifiStateMachine( 1023): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1023): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/WifiStateMachine( 1023): invokeEnterMethods: SupplicantStoppingState
D/WifiStateMachine( 1023): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1023): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1023): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 4340): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 4340): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  274): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1023): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/WifiService( 1023): setWifiEnabled: true pid=4023, uid=10397
,E/WifiService( 1023): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1023): stopping supplicant
I/wpa_supplicant( 4340): P2P-FIND-STOPPED 
D/Checkin ( 1023): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1023): setWifiState: disabling
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=196614
D/WifiStateMachine( 1023): processMsg: SupplicantStoppingState
W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
W/XTWiFiOS( 1269): Active network info is not available
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
E/XTCC-3.0.0.2(  580): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  580): [WwanPosMgr] handleConnectivtyStatusChange failed
I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=false Wifi=(none) Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/BluetoothManagerService( 1023): Message: 20
,D/BluetoothManagerService( 1023): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44159658:true
,W/Settings( 1244): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiController( 1023): WifiController msg { when=-1ms what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 411ms
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
I/wpa_supplicant( 4340): eap_proxy Deinitialzed
,W/Settings( 1244): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
I/jxcore-log( 4023): toggleWiFi finished
I/jxcore-log( 4023): 
D/WifiStateMachine( 1023): handleMessage: E msg.what=131146
D/WifiStateMachine( 1023): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131145
D/WifiStateMachine( 1023): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1023): processMsg: DefaultState
I/jxcore-log( 4023): ReconnectWifiAP finished
I/jxcore-log( 4023): 
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131146
D/WifiStateMachine( 1023): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
E/XTCC-3.0.0.2(  580): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  580): [CSMgr] handleConnectivtyStatusChange failed
D/LocalBluetoothProfileManager( 5068): Adding local A2DP profile
D/BluetoothManagerService( 1023): Message: 30
,W/ContextImpl( 5068): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
I/WB      ( 4023): Wifi is DISABLED !!
I/        ( 4023): Stoping All
I/        ( 4023): Stopping services
,I/        ( 4023): Stopping services
D/WifiP2pService( 1023): P2pDisabledState{ when=0 what=139298 arg2=88 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=0 what=139298 arg2=88 target=com.android.internal.util.StateMachine$SmHandler }
D/LocalBluetoothProfileManager( 5068): Adding local HEADSET profile
,D/BluetoothManagerService( 1023): Message: 30
D/WifiP2pService( 1023): P2pDisabledState{ when=0 what=139307 arg2=89 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): DefaultState{ when=0 what=139307 arg2=89 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pDisabledState{ when=0 what=139268 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=0 what=139268 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 4023): Stop Bluetooth
I/        ( 4023): Stop Bluetooth
I/BTListenerThread( 4023): Stopped
W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
I/BTConnectToThread( 4023): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btif ( 1772): bta_jv_rfcomm_stop_server
E/bt-btif ( 1772): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:28, channel:-1
I/chromium( 4023): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
I/        ( 4023): Clearing local services failed, error code 2
W/XTWiFiOS( 1269): Active network info is not available
I/        ( 4023): Clearing service requests failed, error code 2
I/        ( 4023): Stopping peer discovery failed, error code 2
I/CONNEC  ( 4023): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 4023): 2015-11-23T11:41:20.760Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 4023): 
E/XTCC-3.0.0.2(  580): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  580): [WwanPosMgr] handleConnectivtyStatusChange failed
I/jxcore-log( 4023): 2015-11-23T11:41:20.760Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 4023): 
,W/ContextImpl( 5068): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
E/XTCC-3.0.0.2(  580): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  580): [CSMgr] handleConnectivtyStatusChange failed
I/jxcore-log( 4023): 2015-11-23T11:41:20.762Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 4023): 
I/jxcore-log( 4023): 2015-11-23T11:41:20.762Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 4023): 
I/jxcore-log( 4023): 2015-11-23T11:41:20.763Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 4023): 
I/jxcore-log( 4023): ---- round done--------
I/jxcore-log( 4023): 
I/jxcore-log( 4023): ---- gotta redo : 58:2A:F7:ED:96:BE, try count now: 1
I/jxcore-log( 4023): 
D/TCMD    (  458): NL - Read 1000 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
I/jxcore-log( 4023): do fake peer & start
I/jxcore-log( 4023): 
I/jxcore-log( 4023): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 4023): 
I/jxcore-log( 4023): 2015-11-23T11:41:20.764Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 4023): 
I/jxcore-log( 4023): 2015-11-23T11:41:20.764Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 4023): 
I/jxcore-log( 4023): 2015-11-23T11:41:20.764Z SendDataConnector.js: do connect now
I/jxcore-log( 4023): 
I/wpa_supplicant( 4340): wlan0: CTRL-EVENT-TERMINATING 
D/WifiStateMachine( 1023): handleMessage: E msg.what=147458
D/AndroidRuntime( 4023): Shutting down VM
W/dalvikvm( 4023): threadid=1: thread exiting with uncaught exception (group=0x41c4bd40)
D/WifiStateMachine( 1023): processMsg: SupplicantStoppingState
I/BtConnection( 4023): Got uncaughtException: java.lang.RuntimeException: Connector class is not initialized properly
D/WifiStateMachine( 1023): Supplicant connection lost
,D/BluetoothManagerService( 1023): Message: 30
,W/ContextImpl( 5068): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
,D/BluetoothManagerService( 1023): Message: 30
,W/ContextImpl( 5068): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 5068): Adding local MAP profile
D/BluetoothMap( 5068): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1023): Message: 30
,W/ContextImpl( 5068): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/BluetoothManagerService( 1023): Message: 30
,W/ContextImpl( 5068): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 5068): LocalBluetoothProfileManager construction complete
D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothA2dp( 5068): Proxy object connected
,D/A2dpProfile( 5068): Bluetooth service connected
,D/BluetoothHeadset( 5068): Proxy object connected
,D/HeadsetProfile( 5068): Bluetooth service connected
D/BluetoothInputDevice( 5068): Proxy object connected
,D/HidProfile( 5068): Bluetooth service connected
,D/BluetoothPan( 5068): BluetoothPAN Proxy object connected
D/PanProfile( 5068): Bluetooth service connected
D/BluetoothMap( 5068): Proxy object connected
D/MapProfile( 5068): Bluetooth service connected
,D/BluetoothMap( 5068): getConnectedDevices()
,D/BluetoothPbap( 5068): Proxy object connected
,D/PbapServerProfile( 5068): Bluetooth service connected
,D/WifiStateMachine( 1023): setWifiState: disabled
D/WifiStateMachine( 1023): transitionTo: destState=InitialState
D/WifiStateMachine( 1023): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1023): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1023): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine( 1023): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1023): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
,D/WifiStateMachine( 1023): invokeEnterMethods: InitialState
,I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1269): Active network info is not available
E/XTCC-3.0.0.2(  580): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  580): [WwanPosMgr] handleConnectivtyStatusChange failed
,W/Settings( 1222): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiService( 1023): New client listening to asynchronous messages
,E/XTCC-3.0.0.2(  580): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  580): [CSMgr] handleConnectivtyStatusChange failed
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiController( 1023): DEFERRED_TOGGLE handled
,D/WifiStateMachine( 1023): setting operational mode to 1
,D/NetlinkEvent(  274): Unexpected netlink message. type=0x11
W/Netd    (  274): No subsystem found in netlink event
D/TCMD    (  458): NL - Read 444 bytes from update socket.
D/TCMD    (  458): NL - ignore NL message, type = 17
D/TCMD    (  458): Listening for incoming client connection request
I/MDMCTBK (  276): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  276): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  276): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  276): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  276): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/TCMD    (  458): NL - Read 1000 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/NetlinkEvent(  274): Unexpected netlink message. type=0x11
W/Netd    (  274): No subsystem found in netlink event
D/TCMD    (  458): NL - Read 444 bytes from update socket.
D/TCMD    (  458): NL - ignore NL message, type = 17
D/TCMD    (  458): Listening for incoming client connection request
I/MDMCTBK (  276): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  276): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  276): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  276): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  276): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  276): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiStateMachine( 1023): handleMessage: X
,D/WifiStateMachine( 1023): handleMessage: E msg.what=131208
D/WifiStateMachine( 1023): processMsg: InitialState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131208
D/WifiStateMachine( 1023): processMsg: InitialState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131208
,D/WifiStateMachine( 1023): processMsg: InitialState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131083
,D/WifiStateMachine( 1023): processMsg: InitialState
,I/MDMCTBK (  276): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  276): NetlinkHandler, interfaceAdded,
I/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
E/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  276): , Wifi = 0
I/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
,E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Tethering( 1023): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1023): sendTetherStateChangedBroadcast 1, 0, 0
,D/TCMD    (  458): NL - Read 1004 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/Tethering( 1023): InitialState.processMessage what=4
,D/Tethering( 1023): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1023): sendTetherStateChangedBroadcast 0, 0, 0
,I/MDMCTBK (  276): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  276): NetlinkHandler, interfaceAdded
I/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
E/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  276): , Wifi = 0
I/MDMCTBK (  276): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  276): set_property_value, Enter
I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
I/MDMCTBK (  276): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  276): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  276): set_property_value, Enter
,I/MDMCTBK (  276): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  276): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  276): set_property_value, Exit
,E/MDMCTBK (  276): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/TCMD    (  458): NL - Read 1004 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/QsoftapCmd(  274): Got softap fwreload command we are passing on
,D/SoftapController(  274): Softap fwReload - Ok
D/CommandListener(  274): Setting iface cfg
,D/CommandListener(  274): Trying to bring down wlan0
,E/WifiHW  ( 1023): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
,E/WifiHW  ( 1023): ctrl_interface != /data/misc/wifi/sockets
,I/wpa_supplicant( 5257): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 5257): rfkill: Cannot open RFKILL control device
D/TCMD    (  458): NL - Read 1000 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/TCMD    (  458): NL - Read 1000 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,E/Diag_Lib( 5257): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 5257): Setting internal use port to rmnet0
,E/wpa_supplicant( 5257): baseband property is set to [msm]
,E/wpa_supplicant( 5257):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5257): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5257): card_info[i].card_state: 0x2
E/wpa_supplicant( 5257): card_info[i].error_code: 0x3
E/wpa_supplicant( 5257): SIM/USIM not ready
,E/wpa_supplicant( 5257): Error while reading SIM card status
,E/wpa_supplicant( 5257): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5257): card_info[i].card_state: 0x2
E/wpa_supplicant( 5257): card_info[i].error_code: 0x3
E/wpa_supplicant( 5257): SIM/USIM not ready
,I/wpa_supplicant( 5257): eap_proxy: Card not ready
,D/WifiStateMachine( 1023): setWifiState: enabling
,I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1023): Supplicant start successful
,W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1269): Active network info is not available
,D/WifiMonitor( 1023): startMonitoring(wlan0) with mConnected = false
E/XTCC-3.0.0.2(  580): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  580): [WwanPosMgr] handleConnectivtyStatusChange failed
,E/XTCC-3.0.0.2(  580): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  580): [CSMgr] handleConnectivtyStatusChange failed
,I/wpa_supplicant( 5257): Long line in configuration file truncated
,I/wpa_supplicant( 5257): rfkill: Cannot open RFKILL control device
D/TCMD    (  458): NL - Read 1000 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,E/wpa_supplicant( 5257): COUNTRY Code Recived
,E/wpa_supplicant( 5257): COUNTRY Code Recived -COUNTRY PL
,E/wpa_supplicant( 5257): baseband property is set to [msm]
,E/wpa_supplicant( 5257):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5257): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5257): card_info[i].card_state: 0x2
E/wpa_supplicant( 5257): card_info[i].error_code: 0x3
E/wpa_supplicant( 5257): SIM/USIM not ready
,E/wpa_supplicant( 5257): Error while reading SIM card status
E/wpa_supplicant( 5257): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5257): card_info[i].card_state: 0x2
E/wpa_supplicant( 5257): card_info[i].error_code: 0x3
E/wpa_supplicant( 5257): SIM/USIM not ready
,I/wpa_supplicant( 5257): eap_proxy: Card not ready
,D/WifiStateMachine( 1023): transitionTo: destState=SupplicantStartingState
,D/WifiStateMachine( 1023): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1023): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1023): invokeExitMethods: InitialState
,D/WifiStateMachine( 1023): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1023): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine( 1023): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine( 1023): handleMessage: X
,D/WifiStateMachine( 1023): handleMessage: E msg.what=131144
D/WifiStateMachine( 1023): processMsg: SupplicantStartingState
D/WifiStateMachine( 1023): deferMessage: msg=131144
D/WifiStateMachine( 1023): handleMessage: X
,D/WifiStateMachine( 1023): handleMessage: E msg.what=131085
D/WifiStateMachine( 1023): processMsg: SupplicantStartingState
D/WifiStateMachine( 1023): deferMessage: msg=131085
D/WifiStateMachine( 1023): handleMessage: X
,D/WifiStateMachine( 1023): handleMessage: E msg.what=131149
D/WifiStateMachine( 1023): processMsg: SupplicantStartingState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): setSuspendOptimizations: 2 true
,D/WifiStateMachine( 1023): mSuspendOptNeedsDisabled 0
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1023): processMsg: SupplicantStartingState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
,D/WifiStateMachine( 1023): handleMessage: E msg.what=131101
D/WifiStateMachine( 1023): processMsg: SupplicantStartingState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
,D/WifiStateMachine( 1023): handleMessage: E msg.what=147457
D/WifiStateMachine( 1023): processMsg: SupplicantStartingState
D/WifiStateMachine( 1023): Supplicant connection established
,D/WifiStateMachine( 1023): setWifiState: enabled
,I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,W/XTWiFiOS( 1269): Active network info is not available
E/XTCC-3.0.0.2(  580): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  580): [WwanPosMgr] handleConnectivtyStatusChange failed
E/XTCC-3.0.0.2(  580): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  580): [CSMgr] handleConnectivtyStatusChange failed
,D/WifiConfigStore( 1023): Loading config and enabling all networks
,E/WifiConfigStore( 1023): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,E/wpa_supplicant( 5257): COUNTRY Code Recived -COUNTRY PL
,D/WifiStateMachine( 1023): transitionTo: destState=DriverStartedState
D/WifiStateMachine( 1023): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1023): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1023): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine( 1023): moveTempStackToStateStack: i=1,j=1
D/WifiStateMachine( 1023): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1023): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
,D/WifiStateMachine( 1023): invokeEnterMethods: SupplicantStartedState
,D/WifiStateMachine( 1023): invokeEnterMethods: DriverStartedState
,D/WifiStateMachine( 1023): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
E/wpa_supplicant( 5257): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 5257): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/WifiStateMachine( 1023): Attempting to reconnect to wifi network ..
,D/WifiStateMachine( 1023): transitionTo: destState=DisconnectedState
,D/WifiP2pService( 1023): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1023): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine( 1023): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine( 1023): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1023): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
D/WifiStateMachine( 1023): moveTempStackToStateStack: i=1,j=3
D/WifiStateMachine( 1023): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1023): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
D/WifiStateMachine( 1023): invokeEnterMethods: ConnectModeState
D/WifiStateMachine( 1023): invokeEnterMethods: DisconnectedState
,D/CommandListener(  274): Setting iface cfg
,D/CommandListener(  274): Trying to bring up p2p0
,D/WifiMonitor( 1023): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 1023): P2pEnablingState
D/WifiP2pService( 1023): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2p socket connection successful
D/WifiP2pService( 1023): P2pEnabledState
,D/WifiP2pService( 1023): sending p2p connection changed broadcast
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131144
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131085
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): processMsg: DriverStartedState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131152
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): processMsg: DriverStartedState
,D/WifiStateMachine( 1023): set country code PL
,D/WifiP2pService( 1023): DeviceAddress: f4:f1:e1:5c:43:c8
E/wpa_supplicant( 5257): COUNTRY Code Recived
E/wpa_supplicant( 5257): COUNTRY Code Recived
,D/WifiStateMachine( 1023): handleMessage: X
,D/WifiP2pService( 1023): MCC mode enabled 0
D/WifiStateMachine( 1023): handleMessage: E msg.what=131162
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): processMsg: DriverStartedState
,D/WifiStateMachine( 1023): set frequency band 2
,D/WifiP2pService( 1023): mP2pAutoConnectSupport = 0
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=147462
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiP2pService( 1023): sending p2p persistent groups changed broadcast
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131167
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): processMsg: DriverStartedState
D/WifiP2pService( 1023): InactiveState
D/WifiStateMachine( 1023): handleMessage: X
,D/WifiP2pService( 1023): InactiveState{ when=-10ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1023): handleMessage: E msg.what=143371
D/WifiStateMachine( 1023): processMsg: DisconnectedState
,D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiP2pService( 1023): P2pEnabledState{ when=-11ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 5257): COUNTRY Code Recived
D/WifiStateMachine( 1023): processMsg: DriverStartedState
E/wpa_supplicant( 5257): COUNTRY Code Recived
,D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
,D/WifiP2pService( 1023): InactiveState{ when=-11ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=147462
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): handleMessage: X
D/WifiP2pService( 1023): P2pEnabledState{ when=-13ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-15ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-15ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/dalvikvm( 1023): GC_CONCURRENT freed 2168K, 63% free 18270K/49260K, paused 7ms+9ms, total 105ms
,D/Tethering( 1023): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/CaptivePortalTracker( 1023): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1023): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: null, inetCondition= 0
W/XTWiFiOS( 1269): Active network info is not available
D/PollingManager( 1549): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: null, inetCondition= 0
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
,E/ActivityThread( 1549): Failed to find provider info for com.motorola.blur.setupprovider
W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
D/PollingManager( 1549): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1549): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
W/XTWiFiOS( 1269): Active network info is not available
,I/ActivityManager( 1023): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=5267 uid=10030 gids={50030, 3003, 1028, 1015}
D/CaptivePortalTracker( 1023): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering( 1023): MasterInitialState.processMessage what=3
,E/ActivityThread( 1549): Failed to find provider info for com.motorola.blur.setupprovider
D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
D/CCE     ( 1549): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 1549): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1549): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
,V/MmsConfig( 5267): mnc/mcc: 
V/MmsConfig( 5267): tag: bool value: enabledMMS - true
,V/MmsConfig( 5267): tag: int value: maxMessageSize - 307200
V/MmsConfig( 5267): tag: int value: maxImageHeight - 1944
V/MmsConfig( 5267): tag: int value: maxImageWidth - 2592
V/MmsConfig( 5267): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 5267): tag: int value: defaultMMSMessagesPerThread - 50
,V/MmsConfig( 5267): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 5267): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 5267): tag: int value: recipientLimit - 20
V/MmsConfig( 5267): tag: bool value: enableMultipartSMS - true
,V/MmsConfig( 5267): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 5267): tag: bool value: enableSlideDuration - true
V/MmsConfig( 5267): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 5267): tag: int value: maxSubjectLength - 80
,V/MmsConfig( 5267): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 5267): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 5267): tag: bool value: enableGroupMms - false
,E/MmsConfig( 5267): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1023): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5290 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1023): Killing 4892:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 5290): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5290): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 5290): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 5290): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1023): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5304 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1023): Killing 4911:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1023): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5318 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1023): Killing 4463:com.google.android.apps.plus/u0a90 (adj 15): empty #9
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  279): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 22ms
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,V/WebViewChromiumFactoryProvider( 5318): Binding Chromium to main looper Looper (main, tid 1) {42520da0}
,I/LibraryLoader( 5318): Expected native library version number "",actual native library version number ""
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms
,I/chromium( 5318): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5318): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 5318): BLUETOOTH permission is missing!
,I/Adreno-EGL( 5318): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5318): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5318): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5318): Local Branch: 
I/Adreno-EGL( 5318): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5318): Local Patches: NONE
I/Adreno-EGL( 5318): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 5318): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 5318): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5318): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/TCMD    (  458): NL - Read 1000 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/NSApplication( 5318): Starting up...
,I/ActivityManager( 1023): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5362 uid=10090 gids={50090, 3003, 3002, 1028, 1015}
,I/ActivityManager( 1023): Killing 4929:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ImageResourceManager( 5362): ImageResourceManager: uninitalized
,I/ActivityManager( 1023): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=5380 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
I/iu.Environment( 5362): update battery state; isPlugged? true*
I/iu.Environment( 5362): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,I/iu.Environment( 5362): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
I/ActivityManager( 1023): Killing 4529:com.motorola.context/u0a11 (adj 15): empty #9
I/ActivityManager( 1023): Killing 5101:com.motorola.deviceauthenticator/u0a16 (adj 15): empty #10
W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.Environment( 1400): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1400): num queued entries: 0
,I/iu.UploadsManager( 1400): num updated entries: 0
,I/iu.SyncManager( 1400): NEXT; no task
,D/MobileConnectivityChangeReceiver( 5290): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5290): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 5362): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledStateupdate channel list
,D/DEBUG   ( 1549): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1549): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1549): bindWebServices(): registering our AIDL callback...
I/SundryService( 1549): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1549): ServiceHandler.handleMessage: mWaitCount=0
,D/EmailService.MarketingOptInSetter( 1549): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1549): onServiceConnected()
D/GetNotificationsWS( 1549): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1549): unbindWebServices(): un-registering our AIDL callback...
,I/iu.UploadsManager( 5362): #reloadSettings(); account: null; pageID: none; IU: disabled; IS: disabled; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,D/dalvikvm( 5362): GC_FOR_ALLOC freed 374K, 5% free 16410K/17224K, paused 16ms, total 16ms
,I/dalvikvm-heap( 5362): Grow heap (frag case) to 19.794MB for 1821008-byte allocation
,D/dalvikvm( 5362): GC_FOR_ALLOC freed 16K, 5% free 18187K/19004K, paused 10ms, total 10ms
,I/iu.UploadsManager( 5362): End new media; added: 0, uploading: 0, time: 96 ms
,I/iu.FingerprintManager( 5362): Start processing all media
,I/iu.FingerprintManager( 5362): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 5362): Start processing media store URI: content://media/external/video/media
,I/ContactLocale( 5380): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/iu.FingerprintManager( 5362): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 5362): Start processing media store URI: content://media/phoneStorage/video/media
I/iu.FingerprintManager( 5362): Finished generating fingerprints; 0.020 seconds
,I/iu.FingerprintManager( 5362):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
I/wpa_supplicant( 5256): fatal error opening "/sys/power/wake_lock"
,I/wpa_supplicant( 5256): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
,D/WifiStateMachine( 1023): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4298e860 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4298e860 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): DefaultState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@4298e860 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): processMsg: DriverStartedState
,D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1023): handleMessage: X
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1023): handleMessage: E msg.what=131089
,D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): processMsg: DriverStartedState
D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1023): processMsg: DefaultState
,D/WifiStateMachine( 1023): handleMessage: X
,I/GAV2    ( 5318): Thread[GAThread,5,main]: No campaign data found.
,W/bt-sdp  ( 1772): SDP - Rcvd conn cnf with error: 0x8  CID 0x4d
,E/bt-btif ( 1772): DISCOVERY_COMP_EVT slot id:28, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 1772): invalid rfc slot id: 28
,I/wpa_supplicant( 5257): wlan0: Trying to associate with SSID 'NG700'
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiStateMachine( 1023): handleMessage: E msg.what=147461
,E/wpa_supplicant( 5257): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine( 1023): processMsg: DisconnectedState
,D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): processMsg: DriverStartedState
,D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1023): handleMessage: X
,D/WifiStateMachine( 1023): handleMessage: E msg.what=147462
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): handleMessage: X
,I/wpa_supplicant( 5257): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
,E/wpa_supplicant( 5257): Retrying assoc: 1 
,I/wpa_supplicant( 5257): wlan0: CTRL-EVENT-DISCONNECTED bssid=00:00:00:00:00:00 reason=3 locally_generated=1
,D/WifiStateMachine( 1023): handleMessage: E msg.what=147499
,D/WifiStateMachine( 1023): processMsg: DisconnectedState
,D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): handleMessage: X
,D/WifiStateMachine( 1023): handleMessage: E msg.what=147460
D/WifiStateMachine( 1023): processMsg: DisconnectedState
,D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): setDetailed state, old =CONNECTING and new state=DISCONNECTED
,D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): handleMessage: X
,D/WifiStateMachine( 1023): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): handleMessage: X
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/wpa_supplicant( 5257): wlan0: Trying to associate with SSID 'NG700'
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,E/wpa_supplicant( 5257): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1023): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1023): processMsg: DisconnectedState
,D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): processMsg: DriverStartedState
,D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1023): handleMessage: X
,D/WifiStateMachine( 1023): handleMessage: E msg.what=147462
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): handleMessage: X
,I/wpa_supplicant( 5257): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  458): NL - Read 312 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/TCMD    (  458): NL - Read 88 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 5257): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  458): NL - Read 68 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/TCMD    (  458): NL - Read 1000 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 5257): wlan0: Associated with c0:ff:d4:d3:aa:48
D/TCMD    (  458): NL - Read 80 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
D/TCMD    (  458): NL - Read 80 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
D/TCMD    (  458): NL - Read 68 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiStateMachine( 1023): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1023): processMsg: DisconnectedState
,D/WifiStateMachine( 1023): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): handleMessage: X
,D/WifiStateMachine( 1023): handleMessage: E msg.what=147462
,I/wpa_supplicant( 5257): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 5257): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/TCMD    (  458): NL - Read 1000 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiStateMachine( 1023): processMsg: DisconnectedState
,D/WifiStateMachine( 1023): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=147462
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): handleMessage: X
,D/Tethering( 1023): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1023): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1023): handleMessage: E msg.what=147459
D/WifiStateMachine( 1023): processMsg: DisconnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): Network connection established
,D/WifiStateMachine( 1023): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1023): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1023): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1023): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1023): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1023): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1023): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1023): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1023): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1023): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1023): handleMessage: X
,D/WifiStateMachine( 1023): handleMessage: E msg.what=147462
D/WifiStateMachine( 1023): processMsg: ObtainingIpState
D/WifiStateMachine( 1023): ObtainingIpState{ when=-49ms what=147462 obj=android.net.wifi.StateChangeResult@42734880 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1023): processMsg: L2ConnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): handleMessage: X
,D/WifiStateMachine( 1023): handleMessage: E msg.what=131101
D/WifiStateMachine( 1023): processMsg: ObtainingIpState
D/WifiStateMachine( 1023): ObtainingIpState{ when=-43ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@42898c80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1023): processMsg: L2ConnectedState
,D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): processMsg: DriverStartedState
D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
D/WifiStateMachine( 1023): processMsg: DefaultState
,D/WifiStateMachine( 1023): handleMessage: X
,D/WifiStateMachine( 1023): handleMessage: E msg.what=196612
D/WifiStateMachine( 1023): processMsg: ObtainingIpState
D/WifiStateMachine( 1023): ObtainingIpState{ when=-1ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1023): processMsg: L2ConnectedState
,D/WifiStateMachine( 1023): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1023): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1023): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43cfab08 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43cfab08 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1023): handleMessage: X
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
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
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiStateMachine( 1023): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1023): processMsg: ObtainingIpState
,D/WifiStateMachine( 1023): ObtainingIpState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1023): processMsg: L2ConnectedState
,D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): processMsg: DriverStartedState
D/WifiP2pService( 1023): InactiveState{ when=-8ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-9ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): DefaultState{ when=-10ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1023): handleMessage: X
D/TCMD    (  458): NL - Read 60 bytes from update socket.
D/TCMD    (  458): NL - ignore NL message, type = 20
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiStateMachine( 1023): addressUpdated: 192.168.1.123/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1023): handleMessage: E msg.what=131215
D/WifiStateMachine( 1023): processMsg: ObtainingIpState
D/WifiStateMachine( 1023): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.123/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1023): processMsg: L2ConnectedState
,D/WifiStateMachine( 1023): processMsg: ConnectModeState
,D/WifiStateMachine( 1023): processMsg: DriverStartedState
,D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1023): processMsg: DefaultState
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,D/WifiStateMachine( 1023): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1023): handleMessage: X
,D/WifiStateMachine( 1023): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1023): processMsg: ObtainingIpState
,D/WifiStateMachine( 1023): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1023): processMsg: L2ConnectedState
,D/WifiStateMachine( 1023): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1023): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1023): DHCP successful
,D/WifiStateMachine( 1023): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1023): Calling ARP set with IP = 192.168.1.123
,D/WifiStateMachine( 1023): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1023): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1023): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1023): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1023): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1023): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1023): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1023): VerifyingLinkState enter
,D/WifiStateMachine( 1023): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=151572
D/WifiStateMachine( 1023): processMsg: VerifyingLinkState
D/WifiStateMachine( 1023): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1023): processMsg: L2ConnectedState
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 5257): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-23
,D/WifiP2pService( 1023): InactiveState{ when=-11ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService( 1023):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-11ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService( 1023):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1085): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1023): handleMessage: X
,D/WifiStateMachine( 1023): handleMessage: E msg.what=151572
D/WifiStateMachine( 1023): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1023): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1023): processMsg: L2ConnectedState
,D/WifiStateMachine( 1023): handleMessage: X
,D/WifiStateMachine( 1023): handleMessage: E msg.what=135190
D/WifiStateMachine( 1023): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1023): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 1023): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1023): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1023): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1023): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1023): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1023): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1023): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1023): CaptivePortalCheckState enter
,D/WifiStateMachine( 1023): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1023): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1023): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1023): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1023): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=135190
D/WifiStateMachine( 1023): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1023): processMsg: L2ConnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): processMsg: DriverStartedState
D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131092
D/WifiStateMachine( 1023): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1023): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1023): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1023): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1023): WiFi NOT Tethered!
E/ConnectivityService( 1023): Unexpected mtu value: android.net.wifi.WifiStateTracker@425f9b38
,I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1023): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1285): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/WifiStateMachine( 1023): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1023): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1023): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1023): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1023): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1023): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1023): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1023): handleMessage: X
D/WifiStateMachine( 1023): handleMessage: E msg.what=131092
D/WifiStateMachine( 1023): processMsg: ConnectedState
D/WifiStateMachine( 1023): processMsg: L2ConnectedState
D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): processMsg: DriverStartedState
D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
D/WifiStateMachine( 1023): processMsg: DefaultState
D/WifiStateMachine( 1023): handleMessage: X
D/Checkin ( 1023): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.NetworkController( 1085): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/ModemStatsDSDetect( 1285): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1023): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,V/ConnectivityService( 1023): WiFi NOT Tethered!
I/ModemStatsDSDetect( 1285): onReceive() - done, currentInetCondition=0
,I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
E/ConnectivityService( 1023): Unexpected mtu value: android.net.wifi.WifiStateTracker@425f9b38
,D/ConnectivityService( 1023): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1023): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1285): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1285): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1285): onReceive() - done, currentInetCondition=0
,I/CheckinService( 1400): Checkin interval check for package: unspecified last checkin: 1448278722776 min interval config: 0 actual interval: 185879
I/CheckinService( 1400): Checking schedule, now: 1448278908659 next: 1448278752729
,I/CheckinService( 1400): active receiver: enabled
,I/CheckinService( 1400): Preparing to send checkin request
,I/EventLogService( 1400): Accumulating logs since 1448278718921
,I/CheckinRequestBuilder( 1400): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1400): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1023): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5485 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/dalvikvm( 1400): GC_CONCURRENT freed 1917K, 33% free 11712K/17224K, paused 4ms+7ms, total 44ms
,W/dalvikvm( 5485): VFY: unable to resolve static field 529 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5485): VFY: replacing opcode 0x60 at 0x000b
I/dalvikvm( 5485): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 5485): VFY: unable to resolve virtual method 10979: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 5485): VFY: replacing opcode 0x6e at 0x00ca
I/MultiDex( 5485): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5485): install
,I/MultiDex( 5485): MultiDexExtractor.load(/data/app/com.google.android.gms-2.apk, false)
,I/MultiDex( 5485): loading existing secondary dex files
,I/MultiDex( 5485): load found 3 secondary dex files
,I/MultiDex( 5485): install done
,D/dalvikvm( 5485): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5485): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5485): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5485): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5485): VFY: unable to resolve instance field 46
,D/dalvikvm( 5485): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 5485): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5485): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5485): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 5485): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5485): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 5485): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4251dd00
D/dalvikvm( 5485): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4251dd00
,D/dalvikvm( 5485): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4251dd00, skipping init
,D/dalvikvm( 5485): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4251dd00
D/dalvikvm( 5485): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4251dd00
,V/JNIHelp ( 5485): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/dalvikvm( 5485): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4251dd00,
D/dalvikvm( 5485): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x4251dd00
D/dalvikvm( 5485): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4251dd00
,D/dalvikvm( 5485): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4251dd00,
,I/ProviderInstaller( 5485): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1222): callingUid 10022, callindPid: 1222
,E/MDM     ( 1222): [59] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/dalvikvm( 5485): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
,W/dalvikvm( 5485): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5485): VFY: replacing opcode 0x6e at 0x000d
,D/LocationInitializer( 1400): Restart initialization of location
I/dalvikvm( 5485): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 5485): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5485): VFY: replacing opcode 0x6e at 0x0220
,D/GCM     ( 1340): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/dalvikvm( 5485): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 5485): Link of class 'Lcom/google/android/gms/common/h/c;' failed
E/dalvikvm( 5485): Could not find class 'com.google.android.gms.common.h.c', referenced from method com.google.android.gms.common.h.b.a
W/dalvikvm( 5485): VFY: unable to resolve new-instance 2668 (Lcom/google/android/gms/common/h/c;) in Lcom/google/android/gms/common/h/b;
D/dalvikvm( 5485): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 5485): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.h.b.b
W/dalvikvm( 5485): VFY: unable to resolve virtual method 328: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 5485): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 5485): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 5485): Link of class 'Lcom/google/android/gms/common/h/c;' failed
,D/dalvikvm( 5485): DexOpt: unable to opt direct call 0x2d44 at 0x02 in Lcom/google/android/gms/common/h/b;.a
,D/dalvikvm( 1023): GC_EXPLICIT freed 1178K, 64% free 18177K/49260K, paused 4ms+9ms, total 89ms
,D/AuthorizationBluetoothService( 1340): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1340): Proximity feature is not enabled.
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1222): No location to return for getLastLocation()
,W/FusedLocationProvider( 1340): location=null
,V/GmsCoreStatsServiceLauncher( 1400): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WVCdm   (  281): Instantiating CDM.
,I/WVCdm   (  281): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  281): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
,D/DrmWidevineDash(  281): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  281): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5138000
,E/DrmWidevineDash(  281): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5138000
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
D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=2929946700
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 5485): Install completed successfully. count=13 extracted=0
,D/dalvikvm( 5485): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x427507a0
D/dalvikvm( 5485): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x427507a0
,D/dalvikvm( 5485): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x427507a0, skipping init
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,D/ConnectivityService( 1023): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 5485): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,I/wpa_supplicant( 5257): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-43
,I/wpa_supplicant( 5257): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-45
D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: A5-1
D/WifiP2pService( 1023):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService( 1023):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
,D/dalvikvm( 5511): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 5485): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5485): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 71ms
,I/Adreno-EGL( 5485): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5485): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5485): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5485): Local Branch: 
I/Adreno-EGL( 5485): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5485): Local Patches: NONE
I/Adreno-EGL( 5485): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 5485): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5485): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5485): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5485): Local Branch: 
I/Adreno-EGL( 5485): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5485): Local Patches: NONE
I/Adreno-EGL( 5485): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/ProcessCpuTracker( 1023): Skipping unknown process pid 5480
,W/ProcessCpuTracker( 1023): Skipping unknown process pid 5481
,W/ProcessCpuTracker( 1023): Skipping unknown process pid 5516
,W/ProcessCpuTracker( 1023): Skipping unknown process pid 5518
,I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=3923271463
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,I/Adreno-EGL( 5485): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5485): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5485): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5485): Local Branch: 
I/Adreno-EGL( 5485): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5485): Local Patches: NONE
I/Adreno-EGL( 5485): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 5485): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5485): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5485): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5485): Local Branch: 
I/Adreno-EGL( 5485): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5485): Local Patches: NONE
I/Adreno-EGL( 5485): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 5485): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1400): Classify the device as Phone.
,I/wpa_supplicant( 5257): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 level=-83
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 5257): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-36
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService( 1023):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService( 1023):  primary type: 3-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 128
D/WifiP2pService( 1023):  grpcapab: 9
D/WifiP2pService( 1023):  devcapab: 4
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -83 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService( 1023):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService( 1023):  primary type: 3-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 128
D/WifiP2pService( 1023):  grpcapab: 9
D/WifiP2pService( 1023):  devcapab: 4
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -83 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1023):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1023):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering( 1023): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1023): NoActiveNetworkState{ when=-3ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/PollingManager( 1549): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
,D/PollingManager( 1549): now: 716675 ,futureTime: 82580999
,D/PollingManager( 1549): Polling alarm set to expire at: 82580999 Current Time: 716676
,W/XTWiFiOS( 1269): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1549): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1549): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/OtaApp  ( 1549): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1549): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1549): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/PollingManager( 1549): now: 716710 ,futureTime: 82580999
,D/PollingManager( 1549): Polling alarm set to expire at: 82580999 Current Time: 716711
,E/ActivityThread( 1549): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1549): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1549): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1549): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
,I/openssl ( 4966): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4966): Crypto mode 0 already enabled
D/OtaApp  ( 1549): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1549): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/Tethering( 1023): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1023): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
,D/OtaApp  ( 1549): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
D/TelephonyProvider( 1261): Column apn id key is 'apn_id'
D/MobileConnectivityChangeReceiver( 5290): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5290): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1549): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1549): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/iu.Environment( 5362): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.SyncManager( 5362): SYNC; picasa accounts
,I/iu.UploadsManager( 5362): num queued entries: 0
,D/OtaApp  ( 1549): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1549): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
,I/iu.UploadsManager( 5362): num updated entries: 0
,D/OtaApp  ( 1549): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1549): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,I/iu.SyncManager( 5362): NEXT; no task
,I/iu.Environment( 1400): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/OtaApp  ( 1549): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/iu.UploadsManager( 1400): num queued entries: 0
,I/iu.UploadsManager( 1400): num updated entries: 0
,I/iu.SyncManager( 1400): NEXT; no task
,I/CheckinService( 1400): Checkin interval check for package: unspecified last checkin: 1448278722776 min interval config: 0 actual interval: 189021
,D/DEBUG   ( 1549): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1549): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1549): bindWebServices(): registering our AIDL callback...
,D/EmailService.MarketingOptInSetter( 1549): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1549): onServiceConnected()
D/GetNotificationsWS( 1549): onServiceConnected(): Registered for remote service callbacks...
,I/SundryService( 1549): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1549): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1549): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4966): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4966): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 5290): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5290): onReceive CONNECTIVITY_CHANGE networkType=1
,D/dalvikvm( 5362): GC_FOR_ALLOC freed 51K, 3% free 20721K/21204K, paused 12ms, total 12ms
,I/iu.Environment( 5362): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1400): Checkin interval check for package: unspecified last checkin: 1448278722776 min interval config: 0 actual interval: 189086
,D/DEBUG   ( 1549): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1549): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1549): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1549): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1549): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1549): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1549): onServiceConnected()
,D/GetNotificationsWS( 1549): onServiceConnected(): Registered for remote service callbacks...
,D/OtaApp  ( 1549): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1549): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1023): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1549
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1549): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1549): [info] > Updatetime from metadata: 10
,D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1549): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1549): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1549): [info] > Updatetime from metadata: 10
,D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1549): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1549): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1549): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1549): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1549): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1023): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1549
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1549): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1549): [info] > Updatetime from metadata: 10
,D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1549): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1549): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1549): [info] > Updatetime from metadata: 10
,D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1549): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1549): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1549): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1549): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1549): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1023): Activity reported stop, but no longer stopping: ActivityRecord{42e4ae50 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiStateMachine( 1023): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1023): handleMessage: E msg.what=131215
D/WifiStateMachine( 1023): processMsg: ConnectedState
,D/WifiStateMachine( 1023): processMsg: L2ConnectedState
,D/WifiStateMachine( 1023): processMsg: ConnectModeState
D/WifiStateMachine( 1023): processMsg: DriverStartedState
,D/WifiStateMachine( 1023): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1023): processMsg: DefaultState
,D/WifiStateMachine( 1023): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1023): handleMessage: X
,D/ConnectivityService( 1023): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1023):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1023): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1023): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1023): requiresClat: netType=1, hasIPv4Address=true
,I/wpa_supplicant( 5257): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-13
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-10ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -13 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-12ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -13 target=com.android.internal.util.StateMachine$SmHandler }
,I/CheckinTask( 1400): Sending checkin request (11730 bytes)
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/ActivityManager( 1023): Killing 5068:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiService( 1023): Client connection lost with reason: 4
,I/wpa_supplicant( 5257): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-30
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: Android_2dc2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=147477 obj=Device: Android_2dc2
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,V/AlarmManager( 1023): sending alarm Alarm{429fb668 type 2 com.google.android.gms}
,D/ConnectivityService( 1023): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1285): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1285): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1085): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1285): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1285): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/CheckinRequestBuilder( 1400): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1400): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinRequestBuilder( 1400): Classify the device as Phone.
,I/CheckinTask( 1400): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1400): Checking schedule, now: 1448278918301 next: 1448871988294
,I/CheckinService( 1400): active receiver: disabled
,I/CheckinService( 1400): Checking schedule, now: 1448278918319 next: 1448871988294
,I/CheckinService( 1400): active receiver: disabled
,D/CheckinService( 1400): Recording last checkin time for package unspecified as 1448278918329
,D/GCM     ( 1340): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/wpa_supplicant( 5257): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-27
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -27 target=com.android.internal.util.StateMachine$SmHandler }
,I/PackageManager( 1023): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager( 1023):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1023):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1023):   Scheme: "sms"
,I/InputReader( 1023): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1023): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager( 1023): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5583 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
I/PackageManager( 1023):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1023):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1023):   Scheme: "smsto"
,I/PackageManager( 1023): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1023):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1023):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1023):   Scheme: "mms"
,I/PackageManager( 1023): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1023):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1023):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1023):   Scheme: "mmsto"
,I/PackageManager( 1023): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1023):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1023):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1023):   Scheme: "sms"
,I/Launcher( 1301): Deferring update until onResume
,I/PackageManager( 1023): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1023):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1023):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1023):   Scheme: "smsto"
,I/Launcher( 1301): Deferring update until onResume
,I/PackageManager( 1023): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1023):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1023):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1023):   Scheme: "mms"
,I/PackageManager( 1023): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1023):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1023):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1023):   Scheme: "mmsto"
,V/GmsNetworkLocationProvi( 1222): DISABLE
,I/GCoreNlp( 1222): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 5583): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5583): MmsConfig.loadMmsSettings
I/Babel   ( 5583): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 5583): MmsConfig.loadFromDatabase
,E/Babel   ( 5583): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5583): MmsConfig.loadFromResources
,E/Babel   ( 5583): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5583): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 5583): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1023): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5622 uid=10033 gids={50033, 3003, 1028, 1015}
,I/InternalIcingCorporaPro( 2299): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 1400): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager( 1023): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5645 uid=10038 gids={50038, 3003, 1028, 1015}
,I/PackageBroadcastService( 1400): Null package name or gms related package.  Ignoreing.
I/ActivityManager( 1023): Killing 4966:android.process.media/u0a18 (adj 15): empty #9
W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Icing   ( 1400): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager( 1023): Killing 5267:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 5645): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 5645): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5645): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 5645): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 5645): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 5645): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5645): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 5645): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
,W/dalvikvm( 5645): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 5645): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 5645): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 5645): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 5645): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 5645): VFY: replacing opcode 0x6e at 0x0032
,I/InternalIcingCorporaPro( 2299): UpdateCorporaTask done [took 242 ms] updated apps [took 242 ms] 
,W/Settings( 5645): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5645): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 5645): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 5645): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5645): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 5645): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5645): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 5645): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 5645): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5645): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5645): VFY: replacing opcode 0x6e at 0x0385
I/ActivityManager( 1023): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=5682 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 5645): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 5645): VFY: unable to resolve virtual method 9030: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5645): VFY: replacing opcode 0x6e at 0x0019
,D/dalvikvm( 1023): GC_EXPLICIT freed 1540K, 63% free 18246K/49260K, paused 3ms+10ms, total 90ms
,D/dalvikvm( 1340): GC_EXPLICIT freed 1672K, 37% free 10889K/17224K, paused 3ms+7ms, total 39ms
,D/dalvikvm( 5682): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x425232b8, skipping init
I/openssl ( 5682): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 5682): Crypto mode 0 already enabled
,D/Finsky  ( 5645): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5645): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 5645): Skipping gmscore version check
,I/dalvikvm( 5645): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 5645): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 5645): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1023): Killing 5290:com.google.android.setupwizard/u0a41 (adj 15): empty #9
W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1023): Killing 5304:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Finsky  ( 5645): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5645): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,V/AlarmManager( 1023): sending alarm Alarm{441597c0 type 3 android}
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/CaptivePortalTracker( 1023): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 1023): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker( 1023): Checking http://216.58.209.46/generate_204
,I/wpa_supplicant( 5257): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-32
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-6ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-7ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/CaptivePortalTracker( 1023): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1023): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 1023): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1023): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1023): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/wpa_supplicant( 5257): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-26
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-10ms what=147477 obj=Device: G3-1
D/WifiP2pService( 1023):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-12ms what=147477 obj=Device: G3-1
D/WifiP2pService( 1023):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 4488
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 5257): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-36
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: Android_50a5
D/WifiP2pService( 1023):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-5ms what=147477 obj=Device: Android_50a5
D/WifiP2pService( 1023):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,W/bt-l2cap( 1772): l2cu_get_conn_role 1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [58:3f:54:73:64:c0]: 7, f, 6109
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f209308 rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [34:fc:ef:11:ae:67]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 5257): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-42
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-9ms what=147477 obj=Device: Note3-1
D/WifiP2pService( 1023):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-9ms what=147477 obj=Device: Note3-1
D/WifiP2pService( 1023):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [58:2a:f7:ed:96:be]: 7, 1d, 7d3
,I/LaunchCheckinHandler( 1023): cleanup(): cleared. Last call was 21301 ms ago
,I/ActivityManager( 1023): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.bluetooth.BTReceiver: pid=5714 uid=10011 gids={50011, 3003, 3002, 3001}
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/BluetoothManagerService( 1023): Message: 20
,D/BluetoothManagerService( 1023): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42d3c0f8:true
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
I/ActivityManager( 1023): Killing 5318:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2088a0 rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 5257): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
D/WifiP2pService( 1023): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [58:3f:54:73:64:c0]: 7, f, 6109
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
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
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 5257): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-42
,D/WifiP2pService( 1023): InactiveState{ when=-5ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1023):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-13ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1023):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 5257): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 5257): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/wpa_supplicant( 5257): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/wpa_supplicant( 5257): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-8ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 5257): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-23
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
D/WifiP2pService( 1023): InactiveState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService( 1023):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService( 1023):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,V/AlarmManager( 1023): sending alarm Alarm{4407bb78 type 3 android}
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 5257): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-33
D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1023):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1023):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1023):  WFD CtrlPort: 7236
D/WifiP2pService( 1023):  WFD MaxThroughput: 50
D/WifiP2pService( 1023):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 5257): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/wpa_supplicant( 5257): P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5
D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
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
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
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
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,E/bt-btm  ( 1772): RS in progress - Set DISC Pending flag in btm_sec_send_hci_disconnect to delay disconnect
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,V/AlarmManager( 1023): sending alarm Alarm{4415a948 type 2 android}
,D/ConnectivityService( 1023): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1023): Done.
,D/ConnectivityService( 1023): Setting timer for 720seconds
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 5257): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-41
D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/WifiP2pService( 1023): InactiveState{ when=-3ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1023):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-4ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1023):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1023):  primary type: 10-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 392
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 37
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 5257): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
D/WifiP2pService( 1023): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,W/bt-btm  ( 1772): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2088a0 rs_disc_pending=2
E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,D/TCMD    (  458): NL - Read 56 bytes from update socket.
D/TCMD    (  458): NL - message type is RTM_NEWLINK
,D/TCMD    (  458): Listening for incoming client connection request
,I/wpa_supplicant( 5257): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 level=-83
D/WifiP2pService( 1023): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService( 1023):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService( 1023):  primary type: 3-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 128
D/WifiP2pService( 1023):  grpcapab: 9
D/WifiP2pService( 1023):  devcapab: 4
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -83 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService( 1023):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService( 1023):  primary type: 3-0050F204-5
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 128
D/WifiP2pService( 1023):  grpcapab: 9
D/WifiP2pService( 1023):  devcapab: 4
D/WifiP2pService( 1023):  status: 3
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: -83 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 5257): P2P-FIND-STOPPED 
D/WifiP2pService( 1023): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): discovery change broadcast false
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
,I/wpa_supplicant( 5257): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
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
,V/AlarmManager( 1023): sending alarm Alarm{42aa1238 type 3 android}
,I/wpa_supplicant( 5257): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/wpa_supplicant( 5257): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
D/WifiP2pService( 1023): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open '',
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
,I/wpa_supplicant( 5257): P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5
I/wpa_supplicant( 5257): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 5257): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 5257): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 5257): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,I/wpa_supplicant( 5257): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
D/WifiP2pService( 1023): InactiveState{ when=-1ms what=147478 obj=Device: ,
D/WifiP2pService( 1023):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-8ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-8ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): InactiveState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1023): P2pEnabledState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): InactiveState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1023): P2pEnabledState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService( 1023):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService( 1023):  primary type: null
D/WifiP2pService( 1023):  secondary type: null
D/WifiP2pService( 1023):  wps: 0
D/WifiP2pService( 1023):  grpcapab: 0
D/WifiP2pService( 1023):  devcapab: 0
D/WifiP2pService( 1023):  status: 4
D/WifiP2pService( 1023):  wfdInfo: null
D/WifiP2pService( 1023):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1023): sending alarm Alarm{43d77158 type 3 android}
,V/AlarmManager( 1023): sending alarm Alarm{44175630 type 1 com.android.deskclock}
,I/ActivityManager( 1023): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=5758 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1023): Killing 5485:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/MediatorProvider( 5714): Constructor
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
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,V/AlarmManager( 1023): sending alarm Alarm{440be320 type 3 android}
,W/bt-l2cap( 1772): l2cu_get_conn_role 1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,W/bt-l2cap( 1772): l2cu_get_conn_role 1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f20983c rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/dalvikvm( 1772): GC_EXPLICIT freed 2588K, 45% free 9556K/17224K, paused 2ms+5ms, total 44ms
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,W/bt-l2cap( 1772): l2cu_get_conn_role 0
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2081b0 rs_disc_pending=0
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2081b0 rs_disc_pending=0
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
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
,W/bt-l2cap( 1772): l2cu_get_conn_role 1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,V/AlarmManager( 1023): sending alarm Alarm{427cf7a8 type 3 android}
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [34:fc:ef:11:ae:67]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2099f8 rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,I/ActivityManager( 1023): Waited long enough for: ServiceRecord{440829f8 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [7c:f9:0e:37:96:ab]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1772): l2cu_get_conn_role 1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [50:2e:6c:ac:21:50]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1772): l2cu_get_conn_role 1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [7c:f9:0e:37:96:ab]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1772): l2cu_get_conn_role 1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [50:2e:6c:ac:21:50]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,W/bt-l2cap( 1772): l2cu_get_conn_role 1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
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
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2099f8 rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1772): l2cu_get_conn_role 0
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2099f8 rs_disc_pending=0
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2099f8 rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2094c4 rs_disc_pending=0
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,V/AlarmManager( 1023): sending alarm Alarm{42eb7048 type 3 android}
,V/AlarmManager( 1023): sending alarm Alarm{4254b960 type 2 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
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
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1772): l2cu_get_conn_role 1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1772): l2cu_get_conn_role 1
,W/bt-btif ( 1772): info:x10
D/        ( 1772): remote version info [50:2e:6c:ac:21:50]: 7, f, 6109
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1772): l2cu_get_conn_role 1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [e0:db:10:1f:c9:5e]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1772): l2cu_get_conn_role 1
,W/bt-btif ( 1772): info:x10
D/        ( 1772): remote version info [50:2e:6c:ac:21:50]: 7, f, 6109
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,V/AlarmManager( 1023): sending alarm Alarm{440b7ea0 type 3 android}
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1772): l2cu_get_conn_role 1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [e0:db:10:1f:c9:5e]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1772): l2cu_get_conn_role 1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [50:2e:6c:ac:21:50]: 7, f, 6109
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1772): l2cu_get_conn_role 1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [e0:db:10:1f:c9:5e]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [50:2e:6c:ac:21:50]: 7, f, 6109
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f209bb4 rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1772): l2cu_get_conn_role 0
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [50:2e:6c:ac:21:50]: 7, f, 6109
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2099f8 rs_disc_pending=0
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,V/AlarmManager( 1023): sending alarm Alarm{4407d608 type 3 android}
,W/bt-l2cap( 1772): l2cu_get_conn_role 1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [34:fc:ef:11:ae:67]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [58:2a:f7:ed:96:be]: 6, 1d, 7d3
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2094c4 rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2088a0 rs_disc_pending=0
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,W/bt-l2cap( 1772): l2cu_get_conn_role 0
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
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
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2088a0 rs_disc_pending=0
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,W/bt-l2cap( 1772): l2cu_get_conn_role 0
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2094c4 rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_read_remote_features_complete failed (status 0x16)
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,W/bt-l2cap( 1772): l2cu_get_conn_role 1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [50:2e:6c:ac:21:50]: 7, f, 6109
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [34:fc:ef:11:ae:67]: 6, 10f, 608
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2099f8 rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 1772): l2cu_get_conn_role 0
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [58:2a:f7:ed:96:be]: 7, f, 6109
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [80:01:84:8a:b3:68]: 0, 0, 0
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f209680 rs_disc_pending=0
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f209680 rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f209680 rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [34:fc:ef:11:ae:67]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,V/AlarmManager( 1023): sending alarm Alarm{4415cee8 type 3 android}
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f209680 rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2094c4 rs_disc_pending=0
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2094c4 rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
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
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED,
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,W/bt-l2cap( 1772): l2cu_get_conn_role 0
,D/dalvikvm( 1023): GC_EXPLICIT freed 1407K, 63% free 18264K/49260K, paused 8ms+11ms, total 99ms
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [50:2e:6c:ac:21:50]: 7, f, 6109
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [80:01:84:8a:b3:68]: 6, 10f, 608
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [58:2a:f7:ed:96:be]: 6, 1d, 7d3
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2088a0 rs_disc_pending=0
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/dalvikvm( 1772): GC_CONCURRENT freed 2178K, 46% free 9314K/17224K, paused 10ms+3ms, total 39ms
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,W/bt-l2cap( 1772): l2cu_get_conn_role 1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [50:2e:6c:ac:21:50]: 6, 10f, 608
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1772): l2cu_get_conn_role 1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [80:01:84:8a:b3:68]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1772): l2cu_get_conn_role 1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [50:2e:6c:ac:21:50]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1772): l2cu_get_conn_role 1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [80:01:84:8a:b3:68]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1772): l2cu_get_conn_role 1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
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
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,V/AlarmManager( 1023): sending alarm Alarm{42eba230 type 3 android}
,W/bt-l2cap( 1772): l2cu_get_conn_role 1
,W/bt-btif ( 1772): info:x10
D/        ( 1772): remote version info [50:2e:6c:ac:21:50]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1772): l2cu_get_conn_role 1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
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
,W/bt-l2cap( 1772): l2cu_get_conn_role 1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [7c:f9:0e:37:96:ab]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [34:fc:ef:11:ae:67]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f20983c rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2094c4 rs_disc_pending=0
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,V/AlarmManager( 1023): sending alarm Alarm{42d28958 type 3 android}
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [58:2a:f7:ed:96:be]: 7, 1d, 7d3
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [7c:f9:0e:37:96:ab]: 7, f, 6109
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2088a0 rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1772): info:x10
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/        ( 1772): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1772): l2cu_get_conn_role 0
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [50:2e:6c:ac:21:50]: 7, f, 6109
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2099f8 rs_disc_pending=0
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [58:2a:f7:ed:96:be]: 7, 1d, 7d3
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,E/bt-btm  ( 1772): tBTM_SEC_DEV:0x5f2099f8 rs_disc_pending=1
,W/bt-btif ( 1772): bta_dm_check_av:0
,W/bt-btif ( 1772): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
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
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [7c:f9:0e:37:96:ab]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [34:fc:ef:11:ae:67]: 6, 10f, 608
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1772): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1772): info:x10
,D/        ( 1772): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/btif_config_util( 1772): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1772): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5714): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 1772): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 1772): Ftp Service onStartCommand
,V/BluetoothFtpService( 1772): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,D/BluetoothAdapterService(1112704624)( 1772): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1772): getBondedDevices: length=1
,I/ActivityManager( 1023): Waited long enough for: ServiceRecord{441a3cf0 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1023): sending alarm Alarm{42d23be8 type 3 android}
,V/AlarmManager( 1023): sending alarm Alarm{4285f6f0 type 3 android}
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
,V/AlarmManager( 1023): sending alarm Alarm{42849ff0 type 3 android}
,V/AlarmManager( 1023): sending alarm Alarm{42830ef0 type 3 android}
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
,V/AlarmManager( 1023): sending alarm Alarm{427806a0 type 3 android}
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
,V/AlarmManager( 1023): sending alarm Alarm{42deaaa8 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1023): sending alarm Alarm{42d9c380 type 2 android}
,D/ConnectivityService( 1023): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1023): Done.
,D/ConnectivityService( 1023): Setting timer for 720seconds
,D/UdcCache:FPQuery( 1400): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1400): GC_CONCURRENT freed 1667K, 30% free 12092K/17224K, paused 4ms+4ms, total 45ms
,D/dalvikvm( 1400): WAIT_FOR_CONCURRENT_GC blocked 35ms
,D/ConnectivityService( 1023): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1285): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1285): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1285): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
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
,V/AlarmManager( 1023): sending alarm Alarm{43fc7cf0 type 3 android}
,V/AlarmManager( 1023): sending alarm Alarm{43fc69e0 type 0 com.google.android.gms}
,V/AlarmManager( 1023): sending alarm Alarm{43f6f8d8 type 1 com.android.deskclock}
,I/EventLogService( 1400): Aggregate from 1448278908717 (log), 1448278014453 (data)
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1023): sending alarm Alarm{428367d0 type 3 android}
,V/AlarmManager( 1023): sending alarm Alarm{4281fae8 type 3 com.google.android.gms}
,I/ProcessStatsService( 1023): Prepared write state in 17ms
,I/ProcessStatsService( 1023): Prepared write state in 19ms
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService( 1023): Pruning old procstats: /data/system/procstats/state-2015-11-22-14-25-00.bin
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
,V/AlarmManager( 1023): sending alarm Alarm{427650d8 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1023): sending alarm Alarm{43ed47f8 type 3 android}
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
,V/AlarmManager( 1023): sending alarm Alarm{440bec28 type 3 android}
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

```
