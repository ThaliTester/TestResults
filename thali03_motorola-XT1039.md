#### Test 5024228542a63d7_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
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
E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 3965): 
D/AndroidRuntime( 3965): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3965): CheckJNI is OFF
D/dalvikvm( 3965): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3965): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3965): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3965): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3965): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3965): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3965): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3965): failed to load memtrack module: -2
D/AndroidRuntime( 3965): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3965
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3988 uid=10529 gids={50529, 3003, 3001, 3002}
D/AndroidRuntime( 3965): Shutting down VM
D/dalvikvm( 3965): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1293): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1293): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3988): Binding Chromium to main looper Looper (main, tid 1) {41f56af0}
I/LibraryLoader( 3988): Expected native library version number "",actual native library version number ""
I/chromium( 3988): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3988): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@422892e0:true
I/Adreno-EGL( 3988): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3988): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3988): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3988): Local Branch: 
I/Adreno-EGL( 3988): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3988): Local Patches: NONE
I/Adreno-EGL( 3988): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3988): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3988): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3988): VFY: unable to resolve virtual method 172: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3988): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3988): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3988): VFY: unable to resolve virtual method 167: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3988): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3988): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3988): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3988): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3988): VFY: unable to resolve virtual method 225: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3988): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3988): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3988): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3988): VFY: unable to resolve virtual method 183: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3988): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3988): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3988): VFY: unable to resolve virtual method 188: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3988): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3988): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3988): Enabling debug mode 0
,W/AwContents( 3988): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3988): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1019): Displayed com.example.hello/.MainActivity,cp,ca,311
I/ActivityManager( 1019): Displayed com.example.hello/.MainActivity: +287ms (total +312ms)
,I/chromium( 3988): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 3988): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 3988): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3988): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41f5b290
,D/dalvikvm( 3988): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41f5b290
,D/jxcore_app_log( 3988): JniHelper::setJavaVM(0x415a9fa8), pthread_self() = 1609472520
,D/JX-Cordova( 3988): jxcore cordova android initializing
,W/jxcore-log( 3988): Initializing JXcore engine
,W/jxcore-log( 3988): JXcore engine is ready
,W/jxcore-log( 3988): Starting JXcore engine
,W/jxcore-log( 3988): Platform android
W/jxcore-log( 3988): 
,W/jxcore-log( 3988): Process ARCH arm
W/jxcore-log( 3988): 
,I/jxcore-log( 3988): JXcore Cordova bridge is ready!
I/jxcore-log( 3988): 
,W/jxcore-log( 3988): JXcore engine is started
,E/jxcore  ( 3988): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 3988): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:267:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,V/AlarmManager( 1019): sending alarm Alarm{42848960 type 3 android}
,E/global frequency( 1578): no tags to log
,D/Checkin ( 1578): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1578): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1578): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1578): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1578): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1578): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/Checkin ( 1578): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/global frequency( 1578): BcsDSCheckin.events found events 204
,D/Checkin ( 1578): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1578): BcsDSDropBox.events found events 17
,D/Checkin ( 1578): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1578): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1578): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/MMApiWSBase( 1578): doRequest(): url: https://api.svcmot.com:443/v1/cs/checkin.pb/1135300315450105856?appId=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
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
,D/MMApiWSBase( 1578): doRequest(): v1/cs/checkin resp length: 4
,D/CCE     ( 1578): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
,D/CCE     ( 1578): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/global frequency( 1578): BcsCore.status() called with error code=ERROR_OK
,D/Checkin ( 1578): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/CheckinProvider( 1019): 204 events delete 0 left
,I/global frequency( 1578): BcsDSCheckin.events found events 0
,D/Checkin ( 1578): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1578): BcsDSDropBox.events found events 0
,D/Checkin ( 1578): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1578): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/dalvikvm( 1578): GC_CONCURRENT freed 1909K, 38% free 10716K/17224K, paused 3ms+4ms, total 34ms
,I/BSUtils ( 1578): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1578): BcsTimer.onReceive checkin completed (0:ERROR_OK)
,D/Checkin ( 1578): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1 38:f8:89
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 1 38:f8:89
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2 9e:93:4e
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 2 9e:93:4e
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3 06:7c:34
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 3 06:7c:34
D/MDMCTBK (  274): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4 64:7c:34
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 4 64:7c:34
,V/AlarmManager( 1019): sending alarm Alarm{42919cd8 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{4278ab80 type 3 android}
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
,TIME-OUT KILL (timeout was 150000ms),D/AndroidRuntime( 4062): 
D/AndroidRuntime( 4062): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4062): CheckJNI is OFF
D/dalvikvm( 4062): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4062): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4062): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4062): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4062): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4062): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4062): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4062): failed to load memtrack module: -2
D/AndroidRuntime( 4062): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1019): Force stopping com.example.hello appid=10529 user=-1: uninstall pkg
I/ActivityManager( 1019): Killing 3988:com.example.hello/u0a529 (adj 0): stop com.example.hello
W/ContextImpl( 1293): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1019):   Force finishing activity ActivityRecord{4285a118 u0 com.example.hello/.MainActivity t3}
I/WindowState( 1019): WIN DEATH: Window{428496c8 u0 com.example.hello/com.example.hello.MainActivity}
W/InputDispatcher( 1019): channel '42103bf8 com.example.hello/com.example.hello.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher( 1019): channel '42103bf8 com.example.hello/com.example.hello.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
I/WindowState( 1019): WIN DEATH: Window{42103bf8 u0 com.example.hello/com.example.hello.MainActivity}
W/InputDispatcher( 1019): Attempted to unregister already unregistered input channel '42103bf8 com.example.hello/com.example.hello.MainActivity (server)'
W/PackageSettings( 1019): Skipping PackageSetting{42235930 com.test.thalitest/10528} due to missing metadata
I/ActivityManager( 1019): Force stopping com.example.hello appid=10529 user=0: pkg removed
I/ActivityManager( 1019):   Force finishing activity ActivityRecord{4285a118 u0 com.example.hello/.MainActivity t3 f}
W/ContextImpl( 1293): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ActivityManager( 1019): Duplicate finish request for ActivityRecord{4285a118 u0 com.example.hello/.MainActivity t3 f}
D/dalvikvm( 2285): GC_EXPLICIT freed 5086K, 44% free 9666K/17224K, paused 3ms+5ms, total 40ms
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
D/dalvikvm( 1418): GC_EXPLICIT freed 1633K, 31% free 11970K/17224K, paused 4ms+36ms, total 113ms
W/SQLiteConnectionPool( 1418): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/ContextImpl( 1293): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/OtaApp  ( 1578): [info] > Updatetime from metadata: 10
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/Checkin ( 1578): publish the event [tag = MOT_OTA event name = LOG]
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
D/dalvikvm( 2321): GC_EXPLICIT freed 4072K, 42% free 10093K/17224K, paused 14ms+5ms, total 96ms
I/LatinIME:LogUtils( 1219): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1219): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
W/GeofencerStateMachine( 1248): Ignoring removeGeofence because network location is disabled.
D/VoicemailCleanupService( 3412): Cleaning up data for package: com.example.hello
D/dalvikvm( 1319): GC_EXPLICIT freed 3241K, 33% free 11595K/17224K, paused 49ms+7ms, total 131ms
I/Launcher( 1319): Deferring update until onResume
I/LatinIME:LogUtils( 1219): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452276845
D/dalvikvm( 1019): GC_EXPLICIT freed 1903K, 15% free 18185K/21220K, paused 4ms+11ms, total 140ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
D/OtaApp  ( 1578): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1578): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1578): publish the event [tag = MOT_OTA event name = LOG]
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
D/OtaApp  ( 1578): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/OtaApp  ( 1578): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/InputMethodManagerService( 1019): Got RemoteException sending setActive(false) notification to pid 3988 uid 10529
W/Binder  ( 1219): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1219): java.lang.NullPointerException
W/Binder  ( 1219): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1219): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1219): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1219): 	at dalvik.system.NativeStart.run(Native Method)
I/Launcher( 1319): Deferring update until onResume
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/InternalIcingCorporaPro( 2321): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/LatinIME:LogUtils( 1219): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452276846
I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4095 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/ContextImpl( 4095): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10529 #1
I/dalvikvm( 3462): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3462): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3462): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1418): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1418): Clearing selected account for com.example.hello
I/dalvikvm( 1019): Jit: resizing JitTable from 8192 to 16384
D/dalvikvm( 1019): GC_EXPLICIT freed 644K, 15% free 18057K/21220K, paused 6ms+13ms, total 181ms
D/ChimeraCfgMgr( 1418): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1418): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1418): Removing dialog suppression flag for package com.example.hello
D/ChimeraCfgMgr( 1418): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1418): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 1418): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1418): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1418): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1418): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1418): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1418): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1418): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/ActivityManager( 1019): Killing 3738:com.android.calendar/u0a7 (adj 15): empty #9
W/ContextImpl( 1293): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/gH_CompatibleDatabase( 1418): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1418): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1418): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1418): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1418): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1418): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
E/NetworkScheduler.SchedulerReceiver( 1363): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1363): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager( 1019): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4119 uid=10058 gids={50058}
I/Icing   ( 1418): doRemovePackageData com.example.hello
I/InternalIcingCorporaPro( 2321): UpdateCorporaTask done [took 161 ms] updated apps [took 161 ms] 
D/AndroidRuntime( 4062): Shutting down VM
D/dalvikvm( 4062): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+1ms, total 2ms
D/Documents( 4119): Loading roots for com.android.providers.downloads.documents
I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4133 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/ActivityManager( 1019): Killing 3825:com.google.android.partnersetup/u0a25 (adj 15): empty #9
I/ActivityManager( 1019): Killing 3802:com.android.defcontainer/u0a13 (adj 15): empty #9
W/ContextImpl( 1293): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/ContextImpl( 1293): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Documents( 4119): Loading roots for com.android.externalstorage.documents
D/dalvikvm( 4133): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f60440, skipping init
I/openssl ( 4133): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4133): Crypto mode 0 already enabled
I/ActivityManager( 1019): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4153 uid=10020 gids={50020, 1028, 1015, 1023}
I/ActivityManager( 1019): Killing 3412:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1293): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ExternalStorage( 4153): After updating volumes, found 1 active roots
D/Documents( 4119): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 4119): Loading roots for com.android.providers.media.documents
D/Documents( 4119): Loading roots for com.google.android.apps.docs.storage
D/Documents( 4119): Update found 7 roots in 177ms
D/Documents( 4119): Used cached roots for com.android.providers.downloads.documents
D/Documents( 4119): Loading roots for com.android.externalstorage.documents
D/Documents( 4119): Used cached roots for com.android.providers.media.documents
D/Documents( 4119): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 4119): Update found 7 roots in 14ms

```
