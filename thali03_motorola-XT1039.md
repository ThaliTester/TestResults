#### Test 50388019b27d54e_thali03_motorola-XT1039 Logs


```--------- beginning of /dev/log/main
11-17 18:21:43.680  1535  2902 I MMApiBackOffService: MMAPIWebServiceRequest backOff fired!
,11-17 18:21:43.681  1535  2902 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
11-17 18:21:43.695  1535  1535 D MMApiWebService: MMApiBackOffService told us it's okay to retry the waiting requests: 2
11-17 18:21:43.697  1535  2319 D MMApiWebService: doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
11-17 18:21:43.697  1535  2901 D MMApiWebService: doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
11-17 18:21:43.699  1535  2901 D MMApiWebService: doRequest(): polling manager says we're not connected, returning with an error: devices.json
11-17 18:21:43.699  1535  2319 D MMApiWebService: doRequest(): polling manager says we're not connected, returning with an error: 
11-17 18:21:43.699  1535  2901 E MMApiProvisionService: ProvisionWS.Response: Missing mandatory message data in response from DM server...
11-17 18:21:43.700  1535  2319 I MMApiWebService: _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
11-17 18:21:43.700  1535  2901 E MMApiProvisionService: ProvisionWS.Response.setError: error RadioDownError
11-17 18:21:43.701  1535  2319 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
11-17 18:21:43.702  1535  2319 I MMApiBackOffService: connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
11-17 18:21:43.702  1535  2319 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
11-17 18:21:43.704  1535  2319 I MMApiWebService: MMApiWebService told us not to continue at the moment with this request: 
11-17 18:21:43.704  1535  2901 I MMApiWebService: _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
11-17 18:21:43.704  1535  2901 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
11-17 18:21:43.705  1535  2319 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
11-17 18:21:43.706  1535  2901 I MMApiBackOffService: connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 60000
11-17 18:21:43.707  1535  2901 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
11-17 18:21:43.709  1535  2901 I MMApiWebService: MMApiWebService told us not to continue at the moment with this request: devices.json
11-17 18:21:43.710  1535  2901 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
11-17 18:21:44.094  3459  3459 D AndroidRuntime: 
11-17 18:21:44.094  3459  3459 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
11-17 18:21:44.096  3459  3459 D AndroidRuntime: CheckJNI is OFF
11-17 18:21:44.112  3459  3459 D dalvikvm: Trying to load lib libjavacore.so 0x0
11-17 18:21:44.114  3459  3459 D dalvikvm: Added shared lib libjavacore.so 0x0
11-17 18:21:44.118  3459  3459 D dalvikvm: Trying to load lib libnativehelper.so 0x0
11-17 18:21:44.118  3459  3459 D dalvikvm: Added shared lib libnativehelper.so 0x0
11-17 18:21:44.118  3459  3459 D dalvikvm: No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
11-17 18:21:44.154  3459  3459 D dalvikvm: Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
11-17 18:21:44.316  3459  3459 E memtrack: Couldn't load memtrack module (No such file or directory)
11-17 18:21:44.316  3459  3459 E android.os.Debug: failed to load memtrack module: -2
11-17 18:21:44.370  3459  3459 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
11-17 18:21:44.428  1020  1162 I ActivityManager: START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3459
11-17 18:21:44.430  1020  1162 W WindowManager: Not okToDisplay, so not showing Starting Window
11-17 18:21:44.438  1020  1162 I ActivityManager: Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3475 uid=10374 gids={50374, 3003, 3001, 3002}
11-17 18:21:44.440  3459  3459 D AndroidRuntime: Shutting down VM
11-17 18:21:44.444  3459  3468 D dalvikvm: GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
11-17 18:21:44.455  1257  2880 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
11-17 18:21:44.462  1257  2880 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
11-17 18:21:44.502  3475  3475 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {41fc4bb8}
11-17 18:21:44.504  3475  3475 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:21:44.509  3475  3475 I chromium: [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
11-17 18:21:44.510  3475  3475 I BrowserStartupController: Initializing chromium process, renderers=0
11-17 18:21:44.544  1020  1041 D BluetoothManagerService: Message: 20
11-17 18:21:44.544  1020  1041 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42226840:true
11-17 18:21:44.544  3475  3475 D BluetoothAdapter: 1107136424: getState() :  mService = null. Returning STATE_OFF
11-17 18:21:44.567  3475  3475 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
11-17 18:21:44.567  3475  3475 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.24.00.08
11-17 18:21:44.567  3475  3475 I Adreno-EGL: Build Date: 03/07/14 Fri
11-17 18:21:44.567  3475  3475 I Adreno-EGL: Local Branch: 
11-17 18:21:44.567  3475  3475 I Adreno-EGL: Remote Branch: quic/LNX.LA.3.5.1_RB1.1
11-17 18:21:44.567  3475  3475 I Adreno-EGL: Local Patches: NONE
11-17 18:21:44.567  3475  3475 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
11-17 18:21:44.646  3475  3495 W chromium: [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,11-17 18:21:44.664  3475  3475 I dalvikvm: Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
11-17 18:21:44.664  3475  3475 W dalvikvm: VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
11-17 18:21:44.664  3475  3475 D dalvikvm: VFY: replacing opcode 0x6e at 0x0016
11-17 18:21:44.665  3475  3475 I dalvikvm: Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
11-17 18:21:44.665  3475  3475 W dalvikvm: VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
,11-17 18:21:44.665  3475  3475 D dalvikvm: VFY: replacing opcode 0x6e at 0x0008
,11-17 18:21:44.669  3475  3475 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
11-17 18:21:44.670  3475  3475 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
11-17 18:21:44.670  3475  3475 I dalvikvm: Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
11-17 18:21:44.670  3475  3475 W dalvikvm: VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,11-17 18:21:44.670  3475  3475 D dalvikvm: VFY: replacing opcode 0x6f at 0x001a
,11-17 18:21:44.673  3475  3475 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
11-17 18:21:44.673  3475  3475 I dalvikvm: Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
11-17 18:21:44.673  3475  3475 W dalvikvm: VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
11-17 18:21:44.673  3475  3475 D dalvikvm: VFY: replacing opcode 0x6e at 0x000d
11-17 18:21:44.674  3475  3475 I dalvikvm: Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
11-17 18:21:44.674  3475  3475 W dalvikvm: VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,11-17 18:21:44.674  3475  3475 D dalvikvm: VFY: replacing opcode 0x6e at 0x0000
,11-17 18:21:44.676  3475  3475 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,11-17 18:21:44.761  3475  3475 D OpenGLRenderer: Enabling debug mode 0
,11-17 18:21:44.767  3475  3475 W AwContents: nativeOnDraw failed; clearing to background color.
,11-17 18:21:44.807  1020  1034 I LaunchCheckinHandler: Displayed com.example.hello/.MainActivity,cp,ca,376
11-17 18:21:44.808  1020  1034 I ActivityManager: Displayed com.example.hello/.MainActivity: +351ms (total +377ms)
11-17 18:21:44.809  3475  3475 W AwContents: nativeOnDraw failed; clearing to background color.
11-17 18:21:44.813  3475  3475 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,11-17 18:21:44.978  3475  3475 I chromium: [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,11-17 18:21:44.981  3475  3497 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
,11-17 18:21:45.038  3475  3475 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-17 18:21:45.151  3475  3508 D dalvikvm: Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41fc8e60
,11-17 18:21:45.161  3475  3508 D dalvikvm: Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41fc8e60
11-17 18:21:45.161  3475  3508 D jxcore_app_log: JniHelper::setJavaVM(0x41611fa8), pthread_self() = 1610663896
,11-17 18:21:45.162  3475  3508 D JX-Cordova: jxcore cordova android initializing
,11-17 18:21:45.264  3475  3475 W jxcore-log: Initializing JXcore engine
,11-17 18:21:45.264  3475  3475 W jxcore-log: JXcore engine is ready
,11-17 18:21:45.280  3475  3475 W jxcore-log: Starting JXcore engine
,11-17 18:21:45.552  3475  3475 W jxcore-log: Platform android
11-17 18:21:45.552  3475  3475 W jxcore-log: 
,11-17 18:21:45.552  3475  3475 W jxcore-log: Process ARCH arm
11-17 18:21:45.552  3475  3475 W jxcore-log: 
,11-17 18:21:45.622  3475  3475 I jxcore-log: JXcore Cordova bridge is ready!
11-17 18:21:45.622  3475  3475 I jxcore-log: 
,11-17 18:21:45.623  3475  3475 W jxcore-log: JXcore engine is started
,11-17 18:21:45.668  3475  3475 E jxcore-log: >> motorola-XT1039
11-17 18:21:45.668  3475  3475 E jxcore-log: 
,11-17 18:21:45.670  3475  3475 I jxcore-log: Total memory 893136896
11-17 18:21:45.670  3475  3475 I jxcore-log: 
,11-17 18:21:45.671  3475  3475 I jxcore-log: Free memory 33771520
11-17 18:21:45.671  3475  3475 I jxcore-log: 
11-17 18:21:45.672  3475  3475 I jxcore-log: execPath /data/data/com.example.hello/files/www/jxcore
11-17 18:21:45.672  3475  3475 I jxcore-log: 
,11-17 18:21:45.672  3475  3475 I jxcore-log: process.cwd /data/data/com.example.hello/files/www/jxcore
11-17 18:21:45.672  3475  3475 I jxcore-log: 
,11-17 18:21:45.679  3475  3475 I jxcore-log: userPath [ 'www' ]
11-17 18:21:45.679  3475  3475 I jxcore-log: 
,11-17 18:21:45.681  3475  3475 I jxcore-log: Size 720 1184
11-17 18:21:45.681  3475  3475 I jxcore-log: 
,11-17 18:21:45.683  3475  3475 I jxcore-log: Screen Brightness 10
11-17 18:21:45.683  3475  3475 I jxcore-log: 
,11-17 18:21:45.683  3475  3475 E jxcore-log: Dummy Error Log.
11-17 18:21:45.683  3475  3475 E jxcore-log: 
,11-17 18:21:46.222  3475  3475 I jxcore-log: getBuffer is called!!!!
11-17 18:21:46.222  3475  3475 I jxcore-log: 
,11-17 18:21:48.581   276   615 I MDMCTBK : NetlinkHandler, power_supply subsys
11-17 18:21:48.581   276   615 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
11-17 18:21:48.581   276   615 I MDMCTBK : checkDefaultInst, current pid is = 276
11-17 18:21:48.581   276   615 I MDMCTBK : checkDefaultInst, pid match
11-17 18:21:48.581   276   615 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
11-17 18:21:48.582   276   615 I MDMCTBK : MdmCutbackHndler,readFromFile = 
,11-17 18:21:48.582   276   615 E MDMCTBK : MdmCutbackHndler,Could not open ''
,11-17 18:21:49.497   276   615 I MDMCTBK : NetlinkHandler, power_supply subsys
11-17 18:21:49.497   276   615 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
11-17 18:21:49.497   276   615 I MDMCTBK : checkDefaultInst, current pid is = 276
11-17 18:21:49.497   276   615 I MDMCTBK : checkDefaultInst, pid match
11-17 18:21:49.497   276   615 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
11-17 18:21:49.498   276   615 I MDMCTBK : MdmCutbackHndler,readFromFile = 
,11-17 18:21:49.498   276   615 E MDMCTBK : MdmCutbackHndler,Could not open ''
,11-17 18:21:49.544   276   615 I MDMCTBK : NetlinkHandler, power_supply subsys
11-17 18:21:49.544   276   615 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
11-17 18:21:49.544   276   615 I MDMCTBK : checkDefaultInst, current pid is = 276
11-17 18:21:49.544   276   615 I MDMCTBK : checkDefaultInst, pid match
11-17 18:21:49.544   276   615 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
11-17 18:21:49.544   276   615 I MDMCTBK : MdmCutbackHndler,readFromFile = 
,11-17 18:21:49.545   276   615 E MDMCTBK : MdmCutbackHndler,Could not open ''
11-17 18:21:49.550   276   615 I MDMCTBK : NetlinkHandler, power_supply subsys
11-17 18:21:49.550   276   615 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
11-17 18:21:49.550   276   615 I MDMCTBK : checkDefaultInst, current pid is = 276
11-17 18:21:49.550   276   615 I MDMCTBK : checkDefaultInst, pid match
11-17 18:21:49.550   276   615 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
11-17 18:21:49.550   276   615 I MDMCTBK : MdmCutbackHndler,readFromFile = 
,11-17 18:21:49.550   276   615 E MDMCTBK : MdmCutbackHndler,Could not open ''
,11-17 18:21:50.695  1020  1030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,11-17 18:21:50.696  1020  1030 D BluetoothManagerService: Disable(): Service is not Connected Or Bluetooth is not enabled
,11-17 18:21:50.709  1020  1070 D WifiService: New client listening to asynchronous messages,
,11-17 18:21:50.711  1020  1249 D WifiService: setWifiEnabled: false pid=3475, uid=10374
,11-17 18:21:50.714  1020  1249 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-17 18:21:50.715  3475  3475 I jxcore-log: ****TEST TOOK:  5053  ms ****
11-17 18:21:50.715  3475  3475 I jxcore-log: 
11-17 18:21:50.716  3475  3475 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
11-17 18:21:50.716  3475  3475 I jxcore-log: 
,11-17 18:21:51.104  3539  3539 D AndroidRuntime: 
11-17 18:21:51.104  3539  3539 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,11-17 18:21:51.106  3539  3539 D AndroidRuntime: CheckJNI is OFF
,11-17 18:21:51.126  3539  3539 D dalvikvm: Trying to load lib libjavacore.so 0x0
,11-17 18:21:51.129  3539  3539 D dalvikvm: Added shared lib libjavacore.so 0x0
,11-17 18:21:51.133  3539  3539 D dalvikvm: Trying to load lib libnativehelper.so 0x0
11-17 18:21:51.134  3539  3539 D dalvikvm: Added shared lib libnativehelper.so 0x0
,11-17 18:21:51.134  3539  3539 D dalvikvm: No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,11-17 18:21:51.169  3539  3539 D dalvikvm: Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,11-17 18:21:51.347  3539  3539 E memtrack: Couldn't load memtrack module (No such file or directory)
,11-17 18:21:51.347  3539  3539 E android.os.Debug: failed to load memtrack module: -2
,11-17 18:21:51.411  3539  3539 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-17 18:21:51.426  1020  1035 I ActivityManager: Force stopping com.example.hello appid=10374 user=-1: uninstall pkg
,11-17 18:21:51.426  1020  1035 I ActivityManager: Killing 3475:com.example.hello/u0a374 (adj 0): stop com.example.hello
,11-17 18:21:51.429  1257  2880 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,11-17 18:21:51.451  1020  1308 I WindowState: WIN DEATH: Window{427d2918 u0 com.example.hello/com.example.hello.MainActivity}
,11-17 18:21:51.451  1020  1070 D WifiService: Client connection lost with reason: 4
,11-17 18:21:51.471  1020  1035 I ActivityManager:   Force finishing activity ActivityRecord{4235efe0 u0 com.example.hello/.MainActivity t3}
,11-17 18:21:51.485  1020  1045 W PackageSettings: Skipping PackageSetting{422c12c0 com.test.thalitest/10370} due to missing metadata
,11-17 18:21:51.500  1257  2880 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,11-17 18:21:51.500  1020  1045 I ActivityManager: Force stopping com.example.hello appid=10374 user=0: pkg removed
,11-17 18:21:51.501  1020  1045 I ActivityManager:   Force finishing activity ActivityRecord{4235efe0 u0 com.example.hello/.MainActivity t3 f}
,11-17 18:21:51.501  1020  1045 W ActivityManager: Duplicate finish request for ActivityRecord{4235efe0 u0 com.example.hello/.MainActivity t3 f}
,11-17 18:21:51.545  2147  2147 D dalvikvm: GC_EXPLICIT freed 4669K, 45% free 9620K/17224K, paused 3ms+5ms, total 40ms
,11-17 18:21:51.561  1020  1057 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-17 18:21:51.575  1257  2880 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,11-17 18:21:51.578  1020  1308 I PackageManager: Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
11-17 18:21:51.578  1020  1308 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:21:51.578  1020  1308 I PackageManager:   Category: "android.intent.category.DEFAULT"
11-17 18:21:51.578  1020  1308 I PackageManager:   Scheme: "sms"
11-17 18:21:51.580  1535  1535 I OtaApp  : [info] > Updatetime from metadata: 10
,11-17 18:21:51.586  1535  1535 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,11-17 18:21:51.599  1020  1112 I PackageManager: Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
11-17 18:21:51.599  1020  1112 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:21:51.599  1020  1112 I PackageManager:   Category: "android.intent.category.DEFAULT"
11-17 18:21:51.599  1020  1112 I PackageManager:   Scheme: "smsto"
,11-17 18:21:51.612  1535  1535 D OtaApp  : [debug] > cancelling the previous pending intent set for install later
,11-17 18:21:51.613  1020  1282 I PackageManager: Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
11-17 18:21:51.613  1020  1282 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:21:51.613  1187  1345 I LatinIME:LogUtils: Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1447780911
11-17 18:21:51.613  1020  1282 I PackageManager:   Category: "android.intent.category.DEFAULT"
11-17 18:21:51.614  1020  1282 I PackageManager:   Scheme: "mms"
11-17 18:21:51.616  1202  1548 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-17 18:21:51.618  1535  1535 I OtaApp  : [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
11-17 18:21:51.619  1535  1535 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,11-17 18:21:51.628  1187  1339 I LatinIME:LogUtils: Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,11-17 18:21:51.629  1187  1339 I LatinIME:LogUtils: Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,11-17 18:21:51.635  1020  1282 I PackageManager: Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
11-17 18:21:51.635  1020  1282 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:21:51.635  1020  1282 I PackageManager:   Category: "android.intent.category.DEFAULT"
11-17 18:21:51.635  1020  1282 I PackageManager:   Scheme: "mmsto"
11-17 18:21:51.636  1535  1535 D OtaApp  : [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,11-17 18:21:51.648  1535  1535 D OtaApp  : [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,11-17 18:21:51.652  1020  1254 I PackageManager: Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
11-17 18:21:51.652  3082  3566 D VoicemailCleanupService: Cleaning up data for package: com.example.hello
11-17 18:21:51.652  1020  1254 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:21:51.652  1020  1254 I PackageManager:   Category: "android.intent.category.DEFAULT"
11-17 18:21:51.652  1020  1254 I PackageManager:   Scheme: "sms"
,11-17 18:21:51.660  1295  1295 D dalvikvm: GC_EXPLICIT freed 2692K, 33% free 11592K/17224K, paused 2ms+24ms, total 151ms
,11-17 18:21:51.666  1295  1295 I Launcher: Deferring update until onResume
,11-17 18:21:51.669  1020  1162 I PackageManager: Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
11-17 18:21:51.669  1020  1162 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:21:51.669  1020  1162 I PackageManager:   Category: "android.intent.category.DEFAULT"
11-17 18:21:51.669  1020  1162 I PackageManager:   Scheme: "smsto"
,11-17 18:21:51.680  2181  2181 D dalvikvm: GC_EXPLICIT freed 2171K, 44% free 9768K/17224K, paused 4ms+12ms, total 165ms
,11-17 18:21:51.700  1020  1112 I PackageManager: Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
11-17 18:21:51.700  1020  1112 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:21:51.700  1020  1112 I PackageManager:   Category: "android.intent.category.DEFAULT"
11-17 18:21:51.700  1020  1112 I PackageManager:   Scheme: "mms"
,11-17 18:21:51.700  1020  1020 D dalvikvm: GC_EXPLICIT freed 1583K, 15% free 17830K/20744K, paused 4ms+12ms, total 162ms
,11-17 18:21:51.701  1020  1031 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3475 uid 10374
11-17 18:21:51.705  1187  1197 W Binder  : Caught a RuntimeException from the binder stub implementation.
11-17 18:21:51.705  1187  1197 W Binder  : java.lang.NullPointerException
11-17 18:21:51.705  1187  1197 W Binder  : 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
11-17 18:21:51.705  1187  1197 W Binder  : 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
11-17 18:21:51.705  1187  1197 W Binder  : 	at android.os.Binder.execTransact(Binder.java:404)
11-17 18:21:51.705  1187  1197 W Binder  : 	at dalvik.system.NativeStart.run(Native Method)
,11-17 18:21:51.719  1020  1283 I PackageManager: Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
11-17 18:21:51.719  1020  1283 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:21:51.719  1020  1283 I PackageManager:   Category: "android.intent.category.DEFAULT"
11-17 18:21:51.719  1020  1283 I PackageManager:   Scheme: "mmsto"
,11-17 18:21:51.729  1295  1295 I Launcher: Deferring update until onResume
,11-17 18:21:51.749  2181  3570 I InternalIcingCorporaPro: Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,11-17 18:21:51.764  1020  3568 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3571 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
11-17 18:21:51.765  1187  1345 I LatinIME:LogUtils: Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1447780911
,11-17 18:21:51.779   279   279 D dalvikvm: GC_EXPLICIT freed 43K, 48% free 9013K/17224K, paused 2ms+3ms, total 21ms
,11-17 18:21:51.796  3571  3571 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
11-17 18:21:51.799   279   279 D dalvikvm: GC_EXPLICIT freed <1K, 48% free 9013K/17224K, paused 1ms+2ms, total 19ms
,11-17 18:21:51.817   279   279 D dalvikvm: GC_EXPLICIT freed <1K, 48% free 9013K/17224K, paused 1ms+3ms, total 18ms
11-17 18:21:51.818  3142  3142 I dalvikvm: Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
11-17 18:21:51.818  3142  3142 W dalvikvm: VFY: unable to resolve virtual method 338: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,11-17 18:21:51.818  3142  3142 D dalvikvm: VFY: replacing opcode 0x6e at 0x0013
,11-17 18:21:51.820  1370  3585 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,11-17 18:21:51.820  1370  3585 D AccountUtils: Clearing selected account for com.example.hello
,11-17 18:21:51.822  1370  1370 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.gms
,11-17 18:21:51.828  1370  3585 I LocationSettingsChecker: Removing dialog suppression flag for package com.example.hello
,11-17 18:21:51.851  1370  3587 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,11-17 18:21:51.851  1370  3587 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
11-17 18:21:51.852  1370  3587 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.example.hello.
,11-17 18:21:51.852  1370  3587 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
11-17 18:21:51.854  1020  1020 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,11-17 18:21:51.854  1020  1020 V BackupManagerService: removePackageParticipantsLocked: uid=10374 #1
11-17 18:21:51.856  1326  1326 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
11-17 18:21:51.856  1326  1326 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
11-17 18:21:51.858  1370  3587 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
11-17 18:21:51.859  1370  3587 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
11-17 18:21:51.859  1370  3587 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,11-17 18:21:51.867  1370  3587 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,11-17 18:21:51.867  1370  3587 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,11-17 18:21:51.868  1370  3587 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,11-17 18:21:51.869  1370  3587 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,11-17 18:21:51.870  1370  3587 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,11-17 18:21:51.871  1020  3568 I ActivityManager: Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3590 uid=10058 gids={50058}
11-17 18:21:51.871  1370  3587 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,11-17 18:21:51.880  1370  3602 I PeopleContactsSync: CP2 sync disabled
,11-17 18:21:51.892  1370  1433 I Icing   : doRemovePackageData com.example.hello
,11-17 18:21:51.893  1202  3258 D dalvikvm: GC_EXPLICIT freed 1353K, 41% free 10260K/17224K, paused 2ms+7ms, total 54ms
,11-17 18:21:51.906  1202  1210 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@422dc760)
,11-17 18:21:51.915  2181  3570 I InternalIcingCorporaPro: UpdateCorporaTask done [took 166 ms] updated apps [took 166 ms] 
,11-17 18:21:51.933  3590  3608 D Documents: Loading roots for com.android.providers.downloads.documents
,11-17 18:21:51.950  1020  1112 I ActivityManager: Killing 3270:com.android.calendar/u0a7 (adj 15): empty #9
,11-17 18:21:51.952  1257  2880 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
11-17 18:21:51.955  1020  1045 D dalvikvm: GC_EXPLICIT freed 555K, 15% free 17717K/20744K, paused 11ms+14ms, total 254ms
,11-17 18:21:51.970  1020  1254 I ActivityManager: Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3609 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,11-17 18:21:51.974  1020  1030 I ActivityManager: Killing 3340:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,11-17 18:21:51.976  1257  2880 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,11-17 18:21:51.986  1020  1112 I ActivityManager: Killing 3326:com.android.defcontainer/u0a13 (adj 15): empty #9
,11-17 18:21:51.987  1257  2880 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,11-17 18:21:52.025  3539  3539 D AndroidRuntime: Shutting down VM
,11-17 18:21:52.029  3539  3548 D dalvikvm: GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
,11-17 18:21:52.061  3590  3608 D Documents: Loading roots for com.android.externalstorage.documents
,11-17 18:21:52.064  3609  3609 D dalvikvm: No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fc3480, skipping init
11-17 18:21:52.064  3609  3609 I openssl : Crypto mode not selected, openssl will run on its regular mode.
11-17 18:21:52.064  3609  3609 I openssl : Crypto mode 0 already enabled
,11-17 18:21:52.070  1020  1306 I ActivityManager: Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3625 uid=10020 gids={50020, 1028, 1015, 1023}
,11-17 18:21:52.084  1020  1112 I ActivityManager: Killing 3082:android.process.acore/u0a10 (adj 15): empty #9
,11-17 18:21:52.085  1257  2880 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,11-17 18:21:52.107  3625  3625 D ExternalStorage: After updating volumes, found 1 active roots
,11-17 18:21:52.108  3590  3590 D Documents: Updating roots due to change at content://com.android.externalstorage.documents/root
,11-17 18:21:52.113  3590  3608 D Documents: Loading roots for com.android.providers.media.documents
,11-17 18:21:52.126  3590  3608 D Documents: Loading roots for com.google.android.apps.docs.storage
,11-17 18:21:52.145  3590  3608 D Documents: Update found 7 roots in 216ms
11-17 18:21:52.149  3590  3637 D Documents: Used cached roots for com.android.providers.downloads.documents
,11-17 18:21:52.149  3590  3637 D Documents: Loading roots for com.android.externalstorage.documents
11-17 18:21:52.152  3590  3637 D Documents: Used cached roots for com.android.providers.media.documents
11-17 18:21:52.152  3590  3637 D Documents: Used cached roots for com.google.android.apps.docs.storage
,11-17 18:21:52.152  3590  3637 D Documents: Update found 7 roots in 6ms
```
