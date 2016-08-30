#### Test 828946826174a68_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-30 17:08:57.596  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 17:08:57.599  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 17:08:57.632  1515  3963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-30 17:08:57.632  1515  3963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-30 17:08:57.632  1515  3963 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 17:08:57.632  1515  3963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-30 17:08:57.650  1515  3963 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-30 17:08:57.650  1515  3963 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-30 17:08:57.650  1515  3963 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-30 17:08:57.650  1515  3963 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-30 17:08:57.650  1515  3963 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-30 17:08:57.650  1515  3963 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-30 17:08:57.650  1515  3963 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-30 17:08:57.650  1515  3963 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-30 17:08:57.650  1515  3963 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-30 17:08:57.650  1515  3963 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-30 17:08:57.650  1515  3963 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-30 17:08:57.650  1515  3963 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-30 17:08:57.650  1515  3963 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
08-30 17:08:58.242  3980  3980 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 17:08:58.247  3980  3980 D AndroidRuntime: CheckJNI is OFF
08-30 17:08:58.294  3980  3980 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 17:08:58.297  1515  3963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-30 17:08:58.297  1515  3963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-30 17:08:58.297  1515  3963 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 17:08:58.297  1515  3963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-30 17:08:58.312  1515  3963 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-30 17:08:58.312  1515  3963 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-30 17:08:58.312  1515  3963 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-30 17:08:58.312  1515  3963 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-30 17:08:58.312  1515  3963 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-30 17:08:58.312  1515  3963 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-30 17:08:58.312  1515  3963 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-30 17:08:58.312  1515  3963 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-30 17:08:58.312  1515  3963 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-30 17:08:58.312  1515  3963 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-30 17:08:58.312  1515  3963 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-30 17:08:58.312  1515  3963 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-30 17:08:58.312  1515  3963 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
08-30 17:08:58.343  3980  3980 I Radio-JNI: register_android_hardware_Radio DONE
08-30 17:08:58.362  3980  3980 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 17:08:58.365   875  1405 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 17:08:58.416   875  1405 I ActivityManager: Start proc 3992:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-30 17:08:58.419  3980  3980 D AndroidRuntime: Shutting down VM
08-30 17:08:58.527  3992  3992 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-30 17:08:58.555  3992  3992 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 17:08:58.562  3992  3992 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4362-4364)
08-30 17:08:58.562  3992  3992 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 17:08:58.575  3992  3992 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {dba0a80}
08-30 17:08:58.575  3992  3992 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 17:08:58.575  3992  3992 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 17:08:58.584  3992  3992 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 17:08:58.586  3992  3992 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 17:08:58.598  3992  3992 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-30 17:08:58.608  3992  3992 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 17:08:58.608  3992  3992 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 17:08:58.608  3992  3992 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 17:08:58.608  3992  3992 I Adreno  : Build Date                       : 10/20/15
08-30 17:08:58.608  3992  3992 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 17:08:58.608  3992  3992 I Adreno  : Local Branch                     : M14
08-30 17:08:58.608  3992  3992 I Adreno  : Remote Branch                    : 
08-30 17:08:58.608  3992  3992 I Adreno  : Remote Branch                    : 
08-30 17:08:58.608  3992  3992 I Adreno  : Reconstruct Branch               : 
,08-30 17:08:58.675   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1360ea2:true
08-30 17:08:58.697  3992  3992 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 17:08:58.709  3992  3992 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
08-30 17:08:58.745  3992  4030 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-30 17:08:58.769  3992  4017 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-30 17:08:58.804  3992  4030 I OpenGLRenderer: Initialized EGL, version 1.4
08-30 17:08:58.821  1900  1900 I Keyboard.Facilitator: onFinishInput()
08-30 17:08:58.865   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +388ms (total +485ms)
08-30 17:08:58.905  3992  3992 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3992
08-30 17:08:58.957  1515  3963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-30 17:08:58.957  1515  3963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-30 17:08:58.957  1515  3963 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 17:08:58.957  1515  3963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-30 17:08:58.967  1515  3963 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-30 17:08:58.967  1515  3963 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-30 17:08:58.967  1515  3963 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-30 17:08:58.967  1515  3963 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-30 17:08:58.967  1515  3963 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-30 17:08:58.967  1515  3963 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-30 17:08:58.967  1515  3963 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-30 17:08:58.967  1515  3963 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-30 17:08:58.967  1515  3963 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-30 17:08:58.967  1515  3963 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-30 17:08:58.967  1515  3963 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-30 17:08:58.967  1515  3963 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-30 17:08:58.967  1515  3963 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
08-30 17:08:59.028  3992  3992 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-30 17:08:59.169  3992  4031 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1661507280
08-30 17:08:59.176  3992  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 17:08:59.176  3992  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 17:08:59.176  3992  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 17:08:59.176  3992  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 17:08:59.176  3992  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 17:08:59.176  3992  4031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1f0c17 added. We now have 1 listener(s)
08-30 17:08:59.179  3992  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-30 17:08:59.181  3992  4031 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 17:08:59.182  3992  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:59.182  3992  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:59.188  3992  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 17:08:59.188  3992  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 17:08:59.188  3992  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 17:08:59.188  3992  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-30 17:08:59.188  3992  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 17:08:59.188  3992  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 17:08:59.188  3992  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 17:08:59.188  3992  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 17:08:59.188  3992  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 17:08:59.188  3992  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 17:08:59.188  3992  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 17:08:59.188  3992  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 17:08:59.188  3992  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 17:08:59.188  3992  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 17:08:59.188  3992  4031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c139822 added. We now have 1 listener(s)
08-30 17:08:59.188  3992  4031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:59.194   875  1318 D WifiService: New client listening to asynchronous messages
08-30 17:08:59.194  3992  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:08:59.195  3992  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 17:08:59.196  3992  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 17:08:59.196  3992  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 17:08:59.196  3992  4031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 17:08:59.200  3992  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:59.200  3992  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-30 17:08:59.221  3992  4031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-30 17:08:59.222  3992  4031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:59.222  3992  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:59.222  3992  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:59.222  3992  4031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:59.222  3992  4031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:59.222  3992  4031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:59.222  3992  4031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:59.222  3992  4031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:08:59.222  3992  4031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 17:08:59.222  3992  4031 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:08:59.222  3992  4031 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 17:08:59.224  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:59.226  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:59.244  3992  3992 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-30 17:09:00.116  3992  4040 W jxcore-log: Initializing JXcore engine
08-30 17:09:00.116  3992  4040 W jxcore-log: JXcore engine is ready
08-30 17:09:00.165  4040  4040 W Thread-346: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8944 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-30 17:09:00.165  4040  4040 W Thread-346: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12708]" dev="sockfs" ino=12708 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-30 17:09:00.165  4040  4040 W Thread-346: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 17:09:00.165  4040  4040 W Thread-346: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[23449]" dev="sockfs" ino=23449 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-30 17:09:00.181  3992  4040 W jxcore-log: Starting JXcore engine
08-30 17:09:00.266  3992  4040 W jxcore-log: Platform android
08-30 17:09:00.266  3992  4040 W jxcore-log: 
08-30 17:09:00.266  3992  4040 W jxcore-log: Process ARCH arm
08-30 17:09:00.266  3992  4040 W jxcore-log: 
,08-30 17:09:00.465  3992  4040 I jxcore-log: JXcore Cordova bridge is ready!
08-30 17:09:00.465  3992  4040 I jxcore-log: 
,08-30 17:09:00.466  3992  4040 W jxcore-log: JXcore engine is started
,08-30 17:09:00.474  3992  4031 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 17:09:00.479  3992  3992 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 17:09:07.202  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 17:09:07.212  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 17:09:07.215  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 17:09:07.259  1515  2151 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 17:09:07.259  1515  2151 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 17:09:07.259  1515  2151 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 17:09:07.259  1515  2151 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 17:09:07.299  3532  3532 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 17:09:07.299  3532  3532 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 17:09:07.300  3532  3532 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-30 17:09:10.091  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 17:09:10.091  3992  4040 I jxcore-log: 
,08-30 17:09:10.094  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 17:09:10.094  3992  4040 I jxcore-log: 
,08-30 17:09:10.105  3992  4040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:09:10.105  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:10.105  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:10.105  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:09:10.105  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:09:10.105  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:09:10.105  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:09:10.105  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:09:10.108  3992  4040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:09:10.111  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 17:09:10.111  3992  4040 I jxcore-log: 
,08-30 17:09:10.112  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 17:09:10.112  3992  4040 I jxcore-log: 
,08-30 17:09:10.603  3992  4040 D executeNativeTests: Running unit tests
,08-30 17:09:10.660  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 17:09:10.660  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da825d4 added. We now have 2 listener(s)
08-30 17:09:10.661  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 17:09:10.661  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 17:09:10.661  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 17:09:10.661  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:09:10.661  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d added. We now have 2 listener(s)
08-30 17:09:10.661  3992  4040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:09:10.662  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:09:10.671  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:09:10.685  3992  4040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:09:10.685  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:10.685  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:10.685  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:09:10.685  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:09:10.685  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:09:10.685  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:09:10.685  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:09:10.690  3992  4040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:09:10.690  3992  4040 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:09:10.694  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:10.697  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:10.698  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 17:09:10.703  3992  4040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 17:09:10.703  3992  4040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 17:09:10.707  3992  4040 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-30 17:09:10.708  3992  4040 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-30 17:09:10.710  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-30 17:09:10.710  3992  4040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 17:09:10.711  3992  4040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 17:09:10.712  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:09:10.713  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 17:09:10.713  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:09:10.714  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 17:09:10.715  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:10.715  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:09:10.715  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:09:10.716  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da825d4 removed from the list
08-30 17:09:10.716  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 17:09:10.716  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d removed from the list
08-30 17:09:10.717  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:09:10.717  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:10.719  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:10.719  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:09:10.721  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:09:10.721  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:10.721  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:10.722  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
,08-30 17:09:10.723  3992  4040 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-30 17:09:10.724  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:09:10.724  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:09:10.724  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:09:10.724  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:10.724  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:10.724  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:10.724  3992  4040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da825d4 not in the list
,08-30 17:09:10.724  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:10.725  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:10.725  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:09:10.725  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:10.725  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:10.725  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:09:10.725  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:10.726  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:09:10.726  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:10.726  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:10.726  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
,08-30 17:09:10.731  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 17:09:10.732  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 17:09:10.732  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-30 17:09:10.732  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 17:09:10.732  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 17:09:10.732  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 17:09:10.732  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 17:09:10.732  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 17:09:10.732  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 17:09:10.732  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 17:09:10.732  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 17:09:10.732  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 17:09:10.732  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 17:09:10.732  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 17:09:10.732  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 17:09:10.733  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 17:09:10.733  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 17:09:10.733  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 17:09:10.733  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 17:09:10.733  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 17:09:10.733  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 17:09:10.733  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 17:09:10.733  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 17:09:10.733  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 17:09:10.733  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-30 17:09:10.733  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 17:09:10.733  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 17:09:10.733  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 17:09:10.733  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 17:09:10.733  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 17:09:10.734  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 17:09:10.734  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:09:10.734  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:09:10.734  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:09:10.734  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:10.734  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:10.734  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:10.734  3992  4040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da825d4 not in the list
08-30 17:09:10.734  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:10.734  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:10.734  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:09:10.734  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:10.734  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:10.735  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:10.735  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:10.736  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:09:10.736  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:10.736  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:10.736  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:10.736  3992  4040 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 17:09:10.738  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:09:10.744  3992  4040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:09:10.744  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:10.744  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:10.744  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:09:10.744  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:09:10.744  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:09:10.744  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:09:10.744  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:09:10.747  3992  4040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:09:10.748  3992  4040 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:09:10.749  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:09:10.749  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:09:10.749  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:09:10.749  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:09:10.749  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 17:09:10.750  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:09:10.759  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:09:10.761  3992  4040 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 17:09:10.761  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 17:09:10.770  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 17:09:10.773  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 17:09:10.773  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 17:09:10.779  3992  4040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-30 17:09:10.785  3992  4040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-30 17:09:10.786  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 17:09:10.786  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 17:09:10.788  3992  4040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 17:09:10.790  3992  4040 D BluetoothAdapter: STATE_ON
08-30 17:09:10.802  2685  2815 D BtGatt.GattService: registerClient() - UUID=d7130945-fe2f-4f4b-bddb-abf04dd55db5
08-30 17:09:10.803  2685  2705 D BtGatt.GattService: onClientRegistered() - UUID=d7130945-fe2f-4f4b-bddb-abf04dd55db5, clientIf=5
08-30 17:09:10.804  3992  4003 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 17:09:10.805  2685  2695 D BtGatt.GattService: start scan with filters
,08-30 17:09:10.811  2685  2708 D BtGatt.ScanManager: handling starting scan
08-30 17:09:10.811  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 17:09:10.812  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 17:09:10.812  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 17:09:10.812  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:09:10.812  2685  2708 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba4d30a
,08-30 17:09:10.814  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:09:10.815  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 17:09:10.815  3992  3992 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:09:10.816  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:09:10.820  3992  4040 I io.jxcore.node.ConnectionHelper: start: OK
08-30 17:09:10.820  2685  2705 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 17:09:10.820  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:09:10.821  2685  2708 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 17:09:10.824  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:09:10.824  3992  4040 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 17:09:10.825  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 17:09:10.825  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 17:09:10.825  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:10.825  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 17:09:10.825  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 17:09:10.825  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:09:10.825  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 17:09:10.825  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 17:09:10.826  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 17:09:10.826  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 17:09:10.827  3992  4040 D BluetoothAdapter: STATE_ON
08-30 17:09:10.828  2685  2696 D BtGatt.GattService: stopScan() - queue size =1
,08-30 17:09:10.829  2685  2814 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 17:09:10.829  2685  2705 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 17:09:10.829  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:09:10.829  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:09:10.829  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 17:09:10.829  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 17:09:10.830  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 17:09:10.830  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 17:09:10.830  2685  2708 D BtGatt.ScanManager: Starting BLE batch scan
08-30 17:09:10.830  2685  2708 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 17:09:10.831  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:09:10.831  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 17:09:10.831  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 17:09:10.832  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 17:09:10.832  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:09:10.833  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 17:09:10.833  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:09:10.834  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:09:10.834  3992  4040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da825d4 not in the list
08-30 17:09:10.834  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:10.834  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:10.834  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:09:10.834  3992  3992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:09:10.834  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:10.834  3992  3992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:09:10.835  3992  4040 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 17:09:10.835  3992  3992 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:09:10.837  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:09:10.844  2685  2705 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 17:09:10.844  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:09:10.845  3992  4040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:09:10.845  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:10.845  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:10.845  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:09:10.845  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:09:10.845  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:09:10.845  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:09:10.845  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:09:10.847  3992  4040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:09:10.848  3992  4040 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:09:10.848  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:09:10.848  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 17:09:10.848  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:09:10.848  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:09:10.849  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 17:09:10.851  2685  2705 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 17:09:10.851  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:09:10.851  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:09:10.852  3992  4040 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 17:09:10.852  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 17:09:10.853  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:09:10.857  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 17:09:10.858  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 17:09:10.858  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 17:09:10.859  2685  2705 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 17:09:10.859  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:09:10.859  2685  2708 D BtGatt.ScanManager: stopping BLe Batch
08-30 17:09:10.863  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 17:09:10.863  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 17:09:10.863  3992  4040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 17:09:10.864  3992  4040 D BluetoothAdapter: STATE_ON
08-30 17:09:10.866  2685  2705 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 17:09:10.866  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:09:10.866  2685  2708 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 17:09:10.867  2685  2695 D BtGatt.GattService: registerClient() - UUID=01b9a56b-75cc-4865-97ba-4ffac5d8a5bf
,08-30 17:09:10.867  2685  2705 D BtGatt.GattService: onClientRegistered() - UUID=01b9a56b-75cc-4865-97ba-4ffac5d8a5bf, clientIf=5
,08-30 17:09:10.868  3992  4003 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 17:09:10.868  2685  2790 D BtGatt.GattService: start scan with filters
,08-30 17:09:10.871  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 17:09:10.872  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 17:09:10.872  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 17:09:10.872  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:09:10.873  2685  2705 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 17:09:10.873  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:09:10.875  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:09:10.875  3992  3992 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:09:10.876  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 17:09:10.876  2685  2708 D BtGatt.ScanManager: handling starting scan
08-30 17:09:10.878  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:09:10.881  3992  4040 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 17:09:10.883  2685  2705 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 17:09:10.883  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:09:10.883  2685  2708 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 17:09:10.883  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:09:10.883  3992  4040 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 17:09:10.884  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 17:09:10.884  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 17:09:10.884  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:10.884  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 17:09:10.884  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 17:09:10.884  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:09:10.884  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 17:09:10.884  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 17:09:10.885  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:09:10.885  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 17:09:10.885  3992  4040 D BluetoothAdapter: STATE_ON
,08-30 17:09:10.886  2685  2815 D BtGatt.GattService: stopScan() - queue size =1
08-30 17:09:10.887  2685  2814 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 17:09:10.888  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 17:09:10.888  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 17:09:10.888  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 17:09:10.888  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 17:09:10.888  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 17:09:10.889  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:09:10.890  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 17:09:10.890  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 17:09:10.890  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:09:10.890  2685  2705 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 17:09:10.890  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:09:10.890  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:09:10.890  2685  2708 D BtGatt.ScanManager: Starting BLE batch scan
08-30 17:09:10.891  2685  2708 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 17:09:10.891  3992  3992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:09:10.892  3992  3992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:09:10.892  3992  3992 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:09:10.892  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:10.892  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:10.892  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:09:10.892  3992  4040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da825d4 not in the list
08-30 17:09:10.892  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 17:09:10.892  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:10.892  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:09:10.893  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:09:10.893  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:09:10.893  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:10.894  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:09:10.894  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-30 17:09:10.894  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:10.894  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
,08-30 17:09:10.895  3992  4040 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 17:09:10.896  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:09:10.902  3992  4040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:09:10.902  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:10.902  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:10.902  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:09:10.902  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:09:10.902  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:09:10.902  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:09:10.902  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:09:10.904  2685  2705 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 17:09:10.904  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:09:10.905  3992  4040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:09:10.906  3992  4040 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:09:10.906  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:09:10.906  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 17:09:10.906  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:09:10.906  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:09:10.906  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 17:09:10.908  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:10.917  3992  4040 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 17:09:10.917  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 17:09:10.917  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:10.918  2685  2705 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 17:09:10.918  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:09:10.922  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 17:09:10.923  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 17:09:10.923  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 17:09:10.927  2685  2705 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 17:09:10.927  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:09:10.928  2685  2708 D BtGatt.ScanManager: stopping BLe Batch
,08-30 17:09:10.928  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 17:09:10.928  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 17:09:10.928  3992  4040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 17:09:10.929  3992  4040 D BluetoothAdapter: STATE_ON
,08-30 17:09:10.932  2685  2815 D BtGatt.GattService: registerClient() - UUID=29db693b-fbcc-40be-be04-3ae247871288
,08-30 17:09:10.932  2685  2705 D BtGatt.GattService: onClientRegistered() - UUID=29db693b-fbcc-40be-be04-3ae247871288, clientIf=5
,08-30 17:09:10.933  3992  4003 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 17:09:10.933  2685  2695 D BtGatt.GattService: start scan with filters
,08-30 17:09:10.936  2685  2705 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 17:09:10.936  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:09:10.937  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 17:09:10.937  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 17:09:10.937  2685  2708 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 17:09:10.937  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 17:09:10.937  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:09:10.941  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:09:10.941  3992  3992 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:09:10.941  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 17:09:10.943  2685  2705 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 17:09:10.943  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:09:10.943  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:09:10.945  2685  2708 D BtGatt.ScanManager: handling starting scan
,08-30 17:09:10.947  3992  4040 I io.jxcore.node.ConnectionHelper: start: OK
08-30 17:09:10.947  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:09:10.947  3992  4040 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 17:09:10.947  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 17:09:10.947  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 17:09:10.947  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:09:10.947  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 17:09:10.947  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 17:09:10.947  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:09:10.947  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:09:10.947  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 17:09:10.948  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:09:10.948  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 17:09:10.948  3992  4040 D BluetoothAdapter: STATE_ON
08-30 17:09:10.949  2685  2815 D BtGatt.GattService: stopScan() - queue size =1
08-30 17:09:10.950  2685  2695 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 17:09:10.950  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:09:10.951  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 17:09:10.951  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 17:09:10.951  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 17:09:10.951  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 17:09:10.952  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:09:10.952  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 17:09:10.952  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 17:09:10.953  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:09:10.953  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:09:10.955  3992  3992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:09:10.955  2685  2705 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 17:09:10.955  3992  3992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:09:10.955  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:09:10.955  3992  3992 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:09:10.955  2685  2708 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 17:09:10.956  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:09:10.956  3992  4040 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 17:09:10.956  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:09:10.956  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 17:09:10.957  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 17:09:10.957  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:09:10.957  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:09:10.957  3992  4040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da825d4 not in the list
,08-30 17:09:10.957  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:10.957  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:10.957  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 17:09:10.958  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:10.958  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:10.958  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:10.960  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:09:10.960  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:10.960  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:10.961  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
,08-30 17:09:10.962  3992  4040 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-30 17:09:10.962  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:09:10.963  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:09:10.963  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 17:09:10.963  2685  2705 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 17:09:10.963  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:10.963  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:09:10.963  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:10.963  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:10.963  2685  2708 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 17:09:10.964  2685  2708 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 17:09:10.964  3992  4040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da825d4 not in the list
08-30 17:09:10.964  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:10.964  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:10.964  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:09:10.964  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:10.965  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:10.965  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:10.965  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:10.966  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:09:10.966  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:10.966  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:10.966  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:10.967  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 17:09:10.967  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:09:10.967  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:09:10.967  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:09:10.968  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:10.968  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:10.968  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:10.968  3992  4040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da825d4 not in the list
08-30 17:09:10.968  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:10.968  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:10.968  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:09:10.968  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:10.968  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:10.968  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:10.969  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: releas,e: 1 listener(s) left
08-30 17:09:10.969  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:09:10.970  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:10.970  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:10.970  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:10.970  3992  4040 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 17:09:10.971  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:09:10.971  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:09:10.971  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:09:10.971  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:10.971  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:10.971  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:10.971  3992  4040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da825d4 not in the list,
08-30 17:09:10.971  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:10.971  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:10.971  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 17:09:10.972  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:10.972  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:09:10.972  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:10.972  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:09:10.973  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:09:10.973  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:10.973  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:10.973  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
,08-30 17:09:10.973  3992  4040 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 17:09:10.974  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:09:10.974  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:09:10.974  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-30 17:09:10.974  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:10.974  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-30 17:09:10.974  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:10.974  3992  4040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da825d4 not in the list
08-30 17:09:10.975  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:10.975  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:10.975  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:09:10.975  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:10.975  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:09:10.975  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:10.975  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:10.975  2685  2705 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 17:09:10.976  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:09:10.976  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:09:10.976  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:10.976  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:10.976  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:10.977  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 17:09:10.979  3992  4040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 17:09:10.979  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 17:09:10.979  3992  4040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 17:09:10.979  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 17:09:10.980  3992  4040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 17:09:10.981  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:09:10.981  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:09:10.981  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 17:09:10.981  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 17:09:10.982  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:09:10.982  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:10.983  3992  4040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da825d4 not in the list
,08-30 17:09:10.983  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:10.983  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:10.983  2685  2705 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 17:09:10.983  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:09:10.983  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 17:09:10.985  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:10.985  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:09:10.986  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:10.986  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:10.988  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:09:10.988  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:10.988  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 17:09:10.988  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:10.989  3992  4040 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-30 17:09:10.990  3992  4040 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 17:09:10.990  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-30 17:09:10.992  2685  2705 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 17:09:10.992  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:09:10.992  2685  2708 D BtGatt.ScanManager: stopping BLe Batch
,08-30 17:09:10.997  3992  4040 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-30 17:09:10.998  3992  4040 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 17:09:10.998  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-30 17:09:10.998  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 17:09:10.998  2685  2705 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 17:09:10.998  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:09:10.999  2685  2708 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 17:09:10.999  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-30 17:09:10.999  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 17:09:10.999  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-30 17:09:10.999  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 17:09:10.999  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-30 17:09:10.999  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-30 17:09:10.999  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 17:09:11.000  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 17:09:11.000  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010],
08-30 17:09:11.000  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 17:09:11.000  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-30 17:09:11.000  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 17:09:11.000  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-30 17:09:11.000  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 17:09:11.000  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 17:09:11.000  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-30 17:09:11.001  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 17:09:11.001  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 17:09:11.001  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 17:09:11.001  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-30 17:09:11.001  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 17:09:11.001  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-30 17:09:11.001  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 17:09:11.001  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 17:09:11.001  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 17:09:11.002  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-30 17:09:11.002  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 17:09:11.002  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 17:09:11.002  3992  4040 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,08-30 17:09:11.002  3992  4040 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 17:09:11.003  3992  4040 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-30 17:09:11.003  3992  4040 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-30 17:09:11.003  3992  4040 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 17:09:11.003  3992  4040 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-30 17:09:11.003  3992  4040 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:09:11.003  3992  4040 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-30 17:09:11.003  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-30 17:09:11.004  2685  2705 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 17:09:11.004  2685  2705 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:09:11.008  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-30 17:09:11.009  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 17:09:11.009  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-30 17:09:11.010  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 17:09:11.010  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 17:09:11.010  3992  4040 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-30 17:09:11.011  3992  4040 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:09:11.011  3992  4040 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-30 17:09:11.011  3992  4043 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 410)
,08-30 17:09:11.012  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:09:11.012  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 17:09:11.012  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 17:09:11.012  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:11.012  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-30 17:09:11.012  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.012  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 17:09:11.013  3992  4040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da825d4 not in the list
,08-30 17:09:11.013  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:11.013  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:11.013  3992  4043 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:09:11.013  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:09:11.013  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:09:11.013  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.014  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.014  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.014  3992  4044 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 410
08-30 17:09:11.014  3992  4044 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 410)
08-30 17:09:11.015  3992  4044 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 410)
08-30 17:09:11.015  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:09:11.015  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:11.015  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:11.015  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:11.016  3992  4040 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 17:09:11.016  3992  4043 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 410)
08-30 17:09:11.017  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:09:11.017  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:09:11.017  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:09:11.017  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 17:09:11.017  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.017  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.018  3992  4040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da825d4 not in the list
,08-30 17:09:11.018  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:11.018  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
,08-30 17:09:11.018  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:09:11.018  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.018  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.018  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.018  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:09:11.019  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:09:11.019  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:11.019  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:11.020  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:11.021  3992  4040 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 17:09:11.021  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:09:11.021  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:09:11.021  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:09:11.021  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:11.021  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.021  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.022  3992  4040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da825d4 not in the list
,08-30 17:09:11.022  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 17:09:11.022  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
,08-30 17:09:11.022  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 17:09:11.022  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.022  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.022  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.022  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.024  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:09:11.024  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:11.024  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:11.024  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:11.025  3992  4040 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 17:09:11.025  3992  4040 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 17:09:11.025  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-30 17:09:11.026  3992  4040 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 17:09:11.026  3992  4040 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 17:09:11.026  3992  4040 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 17:09:11.026  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left,
08-30 17:09:11.026  3992  4040 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 17:09:11.026  3992  4040 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 17:09:11.026  3992  4040 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 17:09:11.026  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 17:09:11.026  3992  4040 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 17:09:11.027  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:09:11.027  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:09:11.027  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:09:11.027  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:11.027  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.027  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.027  3992  4040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da825d4 not in the list
08-30 17:09:11.027  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:11.027  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:11.028  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:09:11.028  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.028  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.028  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.028  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.029  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:09:11.029  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:11.029  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:11.029  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:11.030  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:11.030  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.030  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.030  3992  4040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da825d4 not in the list
08-30 17:09:11.030  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:11.031  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:11.031  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:09:11.031  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.031  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.031  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:11.031  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:11.031  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:11.031  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.031  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.031  3992  4040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da825d4 not in the list
08-30 17:09:11.032  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:09:11.032  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:09:11.032  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:09:11.032  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:11.032  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.032  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.032  3992  4040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da825d4 not in the list
08-30 17:09:11.032  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:11.032  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:11.032  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:09:11.033  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.033  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.033  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.033  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.034  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:09:11.034  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:11.035  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:11.035  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:11.036  3992  4040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 17:09:11.037  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:09:11.038  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 17:09:11.038  3992  4040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 17:09:11.039  3992  4040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 17:09:11.039  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 17:09:11.039  3992  3992 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 17:09:11.039  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 17:09:11.039  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:11.040  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 17:09:11.040  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 17:09:11.040  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 17:09:11.040  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.040  3992  4040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 17:09:11.040  3992  4045 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:09:11.040  3992  3992 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 17:09:11.040  3992  4040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da825d4 not in the list
08-30 17:09:11.040  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:11.040  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:09:11.040  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:09:11.040  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 17:09:11.041  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.041  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.042  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:09:11.042  3992  4045 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 17:09:11.042  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:11.042  3992  4045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 17:09:11.042  3992  3992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:09:11.042  3992  4045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 17:09:11.043  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:09:11.043  3992  3992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:09:11.043  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:09:11.043  3992  3992 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:09:11.043  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:09:11.043  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:11.043  3992  3992 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 17:09:11.043  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.043  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.043  3992  4040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da825d4 not in the list
08-30 17:09:11.043  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:11.043  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:11.043  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:09:11.044  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.044  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.044  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.044  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.045  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:09:11.046  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:11.046  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:11.046  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:11.047  3992  4040 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 17:09:11.047  3992  4040 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 17:09:11.047  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 17:09:11.049  3992  4040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 17:09:11.049  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:09:11.049  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:09:11.049  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:09:11.049  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:11.049  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.050  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.050  3992  4040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da825d4 not in the list
08-30 17:09:11.050  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:11.050  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:11.050  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:09:11.050  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.050  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.050  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.050  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.052  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:09:11.052  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:11.052  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:11.052  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:11.056  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:09:11.056  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:09:11.056  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:09:11.056  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:11.056  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.056  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.056  3992  4040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da825d4 not in the list
08-30 17:09:11.056  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:11.057  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:11.057  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:09:11.057  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.057  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.057  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.057  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.058  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:09:11.058  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:11.058  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:11.058  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:11.059  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:09:11.059  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:09:11.059  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:09:11.059  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:11.059  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.060  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.060  3992  4040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da825d4 not in the list
08-30 17:09:11.060  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:11.060  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:11.060  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:09:11.060  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.060  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.060  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:11.060  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:11.061  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:09:11.061  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:11.061  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:11.061  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216e37d not in the list
08-30 17:09:11.062  3992  4040 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 17:09:11.062  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 17:09:11.063  3992  4040 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 17:09:11.063  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 17:09:11.063  3992  4040 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 17:09:11.063  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 17:09:11.065  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 17:09:11.065  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 17:09:11.067  3992  4040 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 17:09:11.067  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 17:09:11.067  3992  4040 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 17:09:11.067  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 17:09:11.067  3992  4040 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 17:09:11.067  3992  4040 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 17:09:11.069  3992  4040 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 17:09:11.069  3992  4040 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 17:09:11.070  3992  4040 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 17:09:11.070  3992  4040 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 17:09:11.071  3992  4040 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 17:09:11.071  3992  4040 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 17:09:11.073  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:09:11.073  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3793017 added. We now have 2 listener(s)
08-30 17:09:11.073  3992  4040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:09:11.077  3992  4040 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 17:09:11.077   875  1405 D WifiService: setWifiEnabled: true pid=3992, uid=10000
08-30 17:09:11.078   875  1405 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 17:09:11.079  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:09:11.079  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aac04 added. We now have 3 listener(s)
08-30 17:09:11.080  3992  4040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:09:11.090  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:09:11.090  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@40ca5ed added. We now have 4 listener(s)
,08-30 17:09:11.090  3992  4040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:09:11.093  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:09:11.093  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@63f0c22 added. We now have 5 listener(s)
08-30 17:09:11.093  3992  4040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:09:11.096   875  1399 D WifiService: setWifiEnabled: false pid=3992, uid=10000
,08-30 17:09:11.096   875  1399 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 17:09:11.103  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:09:11.102  2685  2701 D BluetoothAdapterState: Current state: ON, message: 23
08-30 17:09:11.103  2685  2701 D BluetoothAdapterProperties: Setting state to 13
08-30 17:09:11.103  2685  2701 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-30 17:09:11.105  2685  2701 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 17:09:11.106  2685  2685 D BluetoothMapService: onReceive
,08-30 17:09:11.106  2685  2685 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:09:11.108  2685  2685 D BluetoothMapService: STATE_TURNING_OFF
08-30 17:09:11.108  2685  2685 D BluetoothMapService: MAP Service closeService in
08-30 17:09:11.108  2685  2685 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 17:09:11.108  2685  2685 D ObexServerSockets0: shutdown(block = true)
,08-30 17:09:11.109  2685  2685 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-30 17:09:11.109  2685  2685 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-30 17:09:11.110  2685  2787 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-30 17:09:11.111  2685  2816 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-30 17:09:11.114  2685  2701 I BluetoothAdapterState: Entering PendingCommandState
08-30 17:09:11.111  2685  2817 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 17:09:11.116  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:09:11.116  3992  4040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:09:11.116  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:11.116  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:11.116  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:09:11.116  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:09:11.116  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:09:11.116  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:09:11.116  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:09:11.116  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 17:09:11.117  2685  2685 I BtOppRfcommListener: stopping Accept Thread
08-30 17:09:11.117  2685  3453 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-30 17:09:11.119  2685  3453 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 17:09:11.119   875  1317 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 17:09:11.119   875  1317 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-30 17:09:11.120   875  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 17:09:11.120   875  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 17:09:11.121  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:09:11.121  3992  4040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:09:11.122  3992  4040 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:09:11.126  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:11.128  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:11.130   875   888 I ActivityManager: Start proc 4048:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-30 17:09:11.131  2685  2705 D BluetoothAdapterProperties: Scan Mode:20
,08-30 17:09:11.131  2685  2701 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-30 17:09:11.135  2685  2685 D HeadsetService: Received stop request...Stopping profile...
,08-30 17:09:11.136  1361  1381 D BluetoothHeadset: Proxy object disconnected
,08-30 17:09:11.136   875   875 D BluetoothHeadset: Proxy object disconnected
,08-30 17:09:11.136   875   875 D BluetoothHeadset: Proxy object disconnected
,08-30 17:09:11.137  1969  1996 D BluetoothHeadset: Proxy object disconnected
08-30 17:09:11.137   875  1317 E native  : do suspend true
08-30 17:09:11.138   875   875 D BluetoothHeadset: Proxy object disconnected
,08-30 17:09:11.139  2685  2685 D A2dpService: Received stop request...Stopping profile...
08-30 17:09:11.139  2685  2795 D A2dpStateMachine: Exit Disconnected: -1
08-30 17:09:11.140  3992  3992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:09:11.140  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:09:11.140  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:11.140  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:11.140  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:09:11.140  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:09:11.140  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:09:11.140  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:09:11.140  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:09:11.142  1361  1361 D HeadsetProfile: Bluetooth service disconnected
,08-30 17:09:11.142  3992  3992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:09:11.142  3992  3992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:09:11.142   875   875 D BluetoothA2dp: Proxy object disconnected
08-30 17:09:11.142  2685  2685 V BluetoothAdapterState: isTurningOff()=true
08-30 17:09:11.142  2685  2685 V BluetoothAdapterState: isTurningOn()=false
,08-30 17:09:11.142  2685  2685 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 17:09:11.142  2685  2685 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:09:11.145  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:11.145  2685  2685 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 17:09:11.145  2685  2778 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 17:09:11.145  2685  2778 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 17:09:11.145  2685  2778 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 17:09:11.145  2685  2705 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-30 17:09:11.145  2685  2705 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-30 17:09:11.145  2685  2685 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 17:09:11.147  2685  2685 D HidService: Received stop request...Stopping profile...
,08-30 17:09:11.147  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:09:11.147  2685  2685 D HidService: Stopping Bluetooth HidService
08-30 17:09:11.149  2685  2685 D HealthService: Received stop request...Stopping profile...
08-30 17:09:11.149  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:11.150   875  1917 D DhcpClient: Clearing IP address
08-30 17:09:11.151   371   873 D CommandListener: Clearing all IP addresses on wlan0
08-30 17:09:11.153  2685  2685 D PanService: Received stop request...Stopping profile...
08-30 17:09:11.154   371   873 D CommandListener: Setting iface cfg,
08-30 17:09:11.156  2685  2685 V BluetoothAdapterState: isTurningOff()=true
08-30 17:09:11.156  2685  2685 V BluetoothAdapterState: isTurningOn()=false
,08-30 17:09:11.156  2685  2685 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:09:11.156  2685  2685 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:09:11.156  2685  2685 D BluetoothMapService: Received stop request...Stopping profile...
08-30 17:09:11.157  2685  2685 D BluetoothMapService: stop()
08-30 17:09:11.158  2685  2685 D BluetoothMapAppObserver: deinitObservers()
,08-30 17:09:11.158  2685  2685 D BluetoothMapAppObserver: removeReceiver()
08-30 17:09:11.160  2685  2778 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 17:09:11.160  2685  2778 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 17:09:11.160  2685  2778 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:09:11.160  2685  2778 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:09:11.160  2685  2778 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:09:11.160  2685  2778 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:09:11.160  2685  2705 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-30 17:09:11.160  2685  2685 V BluetoothAdapterState: isTurningOff()=true
,08-30 17:09:11.161  2685  2685 V BluetoothAdapterState: isTurningOn()=false
08-30 17:09:11.161  2685  2685 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:09:11.161  2685  2685 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:09:11.161   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 17:09:11.161   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-30 17:09:11.161  2685  2685 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 17:09:11.162  2685  2705 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 17:09:11.162  2685  2685 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 17:09:11.162  2685  2685 V BluetoothAdapterState: isTurningOff()=true
08-30 17:09:11.162  2685  2685 V BluetoothAdapterState: isTurningOn()=false
08-30 17:09:11.162  2685  2685 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:09:11.162  2685  2685 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 17:09:11.164  2685  2685 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 17:09:11.164  2685  2705 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 17:09:11.164   414   414 E Parcel  : Reading a NULL string not supported here.
08-30 17:09:11.165  2685  2685 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-30 17:09:11.165  2685  2685 V BluetoothAdapterState: isTurningOff()=true
,08-30 17:09:11.165  2685  2685 V BluetoothAdapterState: isTurningOn()=false
,08-30 17:09:11.165  2685  2685 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 17:09:11.165  2685  2685 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:09:11.165  2685  2685 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-30 17:09:11.165  2685  2685 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-30 17:09:11.165   875  1317 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-30 17:09:11.166  2685  2685 D BluetoothMapService: MAP Service closeService in
,08-30 17:09:11.167  2685  2685 V BluetoothAdapterState: isTurningOff()=true
08-30 17:09:11.167  2685  2685 V BluetoothAdapterState: isTurningOn()=false
08-30 17:09:11.167  2685  2685 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:09:11.167  2685  2685 V BluetoothAdapterState: isBleTurningOff()=false,
08-30 17:09:11.167   875  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 17:09:11.167   875  1317 E native  : do suspend true
,08-30 17:09:11.168  1361  1361 D BluetoothA2dp: Proxy object disconnected
08-30 17:09:11.168   875  1319 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-30 17:09:11.169  1361  1361 D BluetoothInputDevice: Proxy object disconnected
,08-30 17:09:11.169  1361  1361 D HidProfile: Bluetooth service disconnected
,08-30 17:09:11.170  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 17:09:11.170  1361  1361 D PanProfile: Bluetooth service disconnected
08-30 17:09:11.170  1361  1361 D BluetoothMap: Proxy object disconnected
08-30 17:09:11.170  1361  1361 D MapProfile: Bluetooth service disconnected
08-30 17:09:11.171  2685  2701 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 17:09:11.171  2685  2701 D BluetoothAdapterProperties: Setting state to 15
08-30 17:09:11.171  2685  2701 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 17:09:11.171  1361  1374 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 17:09:11.171  2685  2701 I BluetoothAdapterState: Entering BleOnState
08-30 17:09:11.172  2685  2685 D BluetoothMapService: cleanup()
08-30 17:09:11.172  2685  2685 D BluetoothMapService: MAP Service closeService in
08-30 17:09:11.172  1361  1381 D BluetoothMap: onBluetoothStateChange: up=false
08-30 17:09:11.172   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:09:11.172   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 17:09:11.172  1361  2124 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 17:09:11.173  1361  1374 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:09:11.173  1969  2161 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:09:11.173   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:09:11.174  1361  1381 D BluetoothPan: onBluetoothStateChange on: false
08-30 17:09:11.175  1361  2124 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 17:09:11.175   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:09:11.176  2685  2701 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 17:09:11.176  2685  2701 D BluetoothAdapterProperties: Setting state to 16
08-30 17:09:11.176  2685  2701 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 17:09:11.177  2685  2701 D BluetoothAdapterProperties: onBleDisable
08-30 17:09:11.177  2685  2702 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 17:09:11.177  2685  2701 I BluetoothAdapterState: Entering PendingCommandState
08-30 17:09:11.178  2685  2705 D BluetoothAdapterProperties: Scan Mode:20
08-30 17:09:11.179  2685  2778 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 17:09:11.179  2685  2778 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 17:09:11.179  3992  3992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:09:11.179  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:09:11.179  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:11.179  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:11.179  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:09:11.179  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:09:11.179  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:09:11.179  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:09:11.179  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:09:11.179  3992  3992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:09:11.179  3992  3992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:09:11.181  3992  3992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checki,ng support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:09:11.181  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:09:11.181  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:11.181  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:11.181  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:09:11.181  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:09:11.181  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:09:11.181  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:09:11.181  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:09:11.182  3992  3992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:09:11.182  3992  3992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:09:11.183  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:09:11.184  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:09:11.184   875  3916 D DhcpClient: Receive thread stopped
08-30 17:09:11.184  1515  3944 V NativeCrypto: Read error: ssl=0x9ad44000: I/O error during system call, Connection timed out
08-30 17:09:11.189  1515  3944 V NativeCrypto: SSL shutdown failed: ssl=0x9ad44000: I/O error during system call, Broken pipe
08-30 17:09:11.198   371   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 17:09:11.213  4048  4048 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-30 17:09:11.216   371   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 17:09:11.217   875  1319 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 17:09:11.217   875  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:09:11.218   371   873 D CommandListener: Clearing all IP addresses on wlan0
,08-30 17:09:11.218   875   892 D Tethering: MasterInitialState.processMessage what=3
08-30 17:09:11.221  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:09:11.223  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:09:11.229  4048  4048 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 17:09:11.233  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 17:09:11.235   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a20bcc8:true
,08-30 17:09:11.245   875   886 I ActivityManager: Start proc 4067:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-30 17:09:11.263  4048  4048 D LocalBluetoothProfileManager: Adding local MAP profile
,08-30 17:09:11.266  4048  4048 D BluetoothMap: Create BluetoothMap proxy object
,08-30 17:09:11.268   371   873 E Netd    : netlink response contains error (No such file or directory)
,08-30 17:09:11.269   875  1319 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-30 17:09:11.270   875  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 17:09:11.278  4048  4048 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-30 17:09:11.286   875  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 17:09:11.289   875  1317 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 17:09:11.289  3992  3992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:09:11.289  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:09:11.289  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:11.289  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:11.289  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:09:11.289  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:09:11.289  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:09:11.289  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:09:11.289  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:09:11.290  3992  3992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:09:11.290  3992  3992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:09:11.292  3992  3992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:09:11.292  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:09:11.292  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:11.292  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:11.292  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:09:11.292  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:09:11.292  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:09:11.292  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:09:11.292  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:09:11.292  1871  2337 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:09:11.293  3992  3992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:09:11.293  3992  3992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:09:11.295  4067  4067 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-30 17:09:11.297  4048  4048 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:09:11.304   875  2211 I ActivityManager: Killing 3674:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-30 17:09:11.381  2685  2705 I bt_hci  : shut_down
,08-30 17:09:11.381  2685  2709 D bt_hwcfg: hw_epilog_process
,08-30 17:09:11.382  2685  2709 I bt_vendor: low_power_mode_cb
,08-30 17:09:11.403  2685  2709 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 17:09:11.403  2685  2709 I bt_vendor: epilog_cb
,08-30 17:09:11.404  2685  2709 I bt_hci  : epilog_finished_callback
,08-30 17:09:11.413  2685  2705 I bt_hci_h4: hal_close
,08-30 17:09:11.414  2685  2705 I bt_userial_vendor: device fd = 51 close,
,08-30 17:09:11.528  4067  4067 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 17:09:11.528  4067  4067 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 17:09:11.528  4067  4067 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 17:09:11.528  4067  4067 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 17:09:11.528  4067  4067 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 17:09:11.528  4067  4067 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 17:09:11.528  4067  4067 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 17:09:11.528  4067  4067 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-30 17:09:11.528  4067  4067 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 17:09:11.528  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 17:09:11.528  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 17:09:11.528  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:09:11.528  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 17:09:11.528  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:09:11.528  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:09:11.528  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 17:09:11.528  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 17:09:11.528  4067  4067 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 17:09:11.528  4067  4067 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 17:09:11.528  4067  4067 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:11.528  4067  4067 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:11.528  4067  4067 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:11.528  4067  4067 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:11.528  4067  4067 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:11.528  4067  4067 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:11.528  4067  4067 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:11.528  4067  4067 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:09:11.529  4067  4067 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:09:11.529  4067  4067 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:09:11.529  4067  4067 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:09:11.529  4067  4067 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.r.k.d(PG:583)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:11.529  4067  4067 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at and,roid.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:11.529  4067  4067 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:11.529  4067  4067 D StrictMod,e: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:11.529  4067  4067 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:11.529  4067  4067 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:11.537  4048  4048 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 17:09:11.544  3992  3992 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-30 17:09:11.558  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 17:09:11.570  2685  2702 D bt_stack_manager: event_shut_down_stack finished.
,08-30 17:09:11.570  2685  2701 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-30 17:09:11.574  1721  1721 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 17:09:11.578  4048  4048 D DockEventReceiver: finishStartingService: stopping service
08-30 17:09:11.578  2685  2701 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-30 17:09:11.579  2685  2685 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 17:09:11.584  2685  2685 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 17:09:11.584  2685  2685 D BtGatt.GattService: stop()
08-30 17:09:11.585  2685  2685 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 17:09:11.588  1721  1721 D SystemUpdateService: onCreate
,08-30 17:09:11.589  2685  2685 V BluetoothAdapterState: isTurningOff()=false
,08-30 17:09:11.589  2685  2685 V BluetoothAdapterState: isTurningOn()=false
,08-30 17:09:11.590  2685  2685 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:09:11.590  2685  2685 V BluetoothAdapterState: isBleTurningOff()=true
,08-30 17:09:11.591  2685  2701 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-30 17:09:11.591  2685  2701 D BluetoothAdapterProperties: Setting state to 10
,08-30 17:09:11.591  2685  2701 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-30 17:09:11.592  2685  2701 I BluetoothAdapterState: Entering OffState
,08-30 17:09:11.592  1721  1721 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-30 17:09:11.593   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-30 17:09:11.604  2685  2685 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 17:09:11.604  2685  2685 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 17:09:11.605  2685  2702 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 17:09:11.606  2685  2702 D bt_stack_manager: event_clean_up_stack finished.
,08-30 17:09:11.606  2685  2685 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 17:09:11.608  1721  1721 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 17:09:11.610  1721  2472 I iu.UploadsManager: num queued entries: 0
,08-30 17:09:11.610  1721  2472 I iu.UploadsManager: num updated entries: 0
,08-30 17:09:11.613  2685  2685 I art     : System.exit called, status: 0
,08-30 17:09:11.613  2685  2685 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 17:09:11.622  1721  1721 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 17:09:11.623  1721  1721 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 17:09:11.625  3817  3817 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:09:11.628  1721  2472 I iu.SyncManager: NEXT; no task
,08-30 17:09:11.629  1721  4099 I SystemUpdateService: active receiver: enabled
,08-30 17:09:11.639  3817  3817 D SprintDMHelper: simOperator: 
,08-30 17:09:11.639  3817  3817 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 17:09:11.650  2290  4102 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 17:09:11.652  1721  4099 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 17:09:11.658  1721  4099 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-30 17:09:11.659  1721  4099 I SystemUpdateService: now status is 0 (complete)
08-30 17:09:11.659  1721  4099 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 17:09:11.659  1721  4099 I SystemUpdateService: file has been verified
08-30 17:09:11.659  1721  4099 I SystemUpdateService: OTA package size = 12249756
,08-30 17:09:11.680  1721  4099 I SystemUpdateService: showing system update notification
,08-30 17:09:11.704   875  1713 I ActivityManager: Start proc 4103:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-30 17:09:11.707   875  1399 I ActivityManager: Process com.android.bluetooth (pid 2685) has died
,08-30 17:09:11.724  1721  1721 D SystemUpdateService: onDestroy
,08-30 17:09:11.728   875  2209 I ActivityManager: Killing 3689:com.android.musicfx/u0a18 (adj 15): empty #17
,08-30 17:09:11.796  4103  4103 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-30 17:09:11.871  4103  4103 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-30 17:09:11.887  4067  4091 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 17:09:11.941   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33296c3:true
,08-30 17:09:14.125   875  2071 D WifiService: setWifiEnabled: true pid=3992, uid=10000
,08-30 17:09:14.126   875  2071 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 17:09:14.139   875  1317 D WifiConfigStore: Loading config and enabling all networks 
,08-30 17:09:14.150  3992  3992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:09:14.150  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:09:14.150  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:14.150  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:14.150  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:09:14.150  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:09:14.150  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:09:14.150  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:09:14.150  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:09:14.150  3992  3992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:09:14.151  3992  3992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:09:14.152  3992  3992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:09:14.153  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:09:14.153  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:14.153  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:14.153  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:09:14.153  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:09:14.153  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:09:14.153  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:09:14.153  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:09:14.153  3992  3992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:09:14.153  3992  3992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:09:14.162   875  1317 D WifiConfigStore: loaded 0 passpoint configs
,08-30 17:09:14.163   875  1317 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-30 17:09:14.164   875  1317 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 17:09:14.167   875  1317 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 17:09:14.168   875  1317 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-30 17:09:14.168   875  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-30 17:09:14.169   875  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 17:09:14.188   371   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-30 17:09:14.188   875  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 17:09:14.189   371   873 D CommandListener: Setting iface cfg
,08-30 17:09:14.190   875  1316 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '155 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 155 Failed to set address (No such device)'
08-30 17:09:14.190   875  1316 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 17:09:14.206   875  1317 E native  : do suspend true
,08-30 17:09:14.206   875  1316 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 17:09:14.213   875  1316 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 17:09:14.220   875  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 17:09:15.605   875  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 17:09:15.695   875  1317 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.81 rxSuccessRate=12.88 delta 1000 -> 994
,08-30 17:09:15.698   875  1317 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-30 17:09:15.698   875  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 17:09:15.717   875  1317 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 17:09:15.774   875  1317 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 17:09:15.777  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 17:09:16.658  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 17:09:16.722  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 17:09:16.724  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 17:09:16.729   875  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 17:09:16.746   875  1317 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 17:09:16.746   875  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 17:09:16.746   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 17:09:16.770   875  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 17:09:16.789   371   873 D CommandListener: Setting iface cfg
,08-30 17:09:16.790   875  1317 D WifiStateMachine: Start Dhcp Watchdog 3
,08-30 17:09:16.810   875  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 17:09:16.834   875  4137 D DhcpClient: Receive thread started
,08-30 17:09:16.918   875  1317 E native  : do suspend false
,08-30 17:09:16.936   875  1917 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 17:09:16.960   875  4137 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172740, domain null
,08-30 17:09:16.961   875  1917 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172740 seconds
08-30 17:09:16.962   875  1917 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 17:09:17.015   875  2210 I ActivityManager: Killing 2084:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-30 17:09:17.025   875  4137 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 17:09:17.025   875  1917 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 17:09:17.028   371   873 D CommandListener: Setting iface cfg
,08-30 17:09:17.037   875  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 17:09:17.040   875  1317 E native  : do suspend true
,08-30 17:09:17.062   875  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 17:09:17.063   875  1317 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 17:09:17.063   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 17:09:17.066   875  1319 D ConnectivityService: Adding iface wlan0 to network 102
,08-30 17:09:17.089   875  1917 D DhcpClient: Scheduling renewal in 86399s
,08-30 17:09:17.108   875  1317 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 17:09:17.117   875  1319 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 17:09:17.117   875  1319 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-30 17:09:17.118   875  1319 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-30 17:09:17.120   875  1319 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-30 17:09:17.121   875  1319 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-30 17:09:17.130   875  2068 D WifiService: setWifiEnabled: false pid=3992, uid=10000
,08-30 17:09:17.130   875  2068 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 17:09:17.135   875  1319 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 17:09:17.138   875  1319 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-30 17:09:17.139   875  1319 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-30 17:09:17.139   875  1319 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-30 17:09:17.139   875  1319 D ConnectivityService:    accepting network in place of null
,08-30 17:09:17.140   875  1319 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 17:09:17.145  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 17:09:17.146   875  1317 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 17:09:17.146   875  1317 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-30 17:09:17.146   875  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 17:09:17.147   875  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 17:09:17.151   875  1317 E native  : do suspend true
,08-30 17:09:17.158   875  1917 D DhcpClient: Clearing IP address
,08-30 17:09:17.166   371   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 17:09:17.203   371   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 17:09:17.203   371   873 D CommandListener: Clearing all IP addresses on wlan0
,08-30 17:09:17.206   371   873 D CommandListener: Setting iface cfg
,08-30 17:09:17.212   875  1319 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-30 17:09:17.212   875  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:09:17.213   875  1319 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-30 17:09:17.214   875   892 D Tethering: MasterInitialState.processMessage what=3
08-30 17:09:17.218   875  1317 D WifiStateMachine: Start Disconnecting Watchdog 3
08-30 17:09:17.218   875  1317 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-30 17:09:17.219   875  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 17:09:17.219   875  1317 E native  : do suspend true
08-30 17:09:17.219  3992  3992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:09:17.219  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:09:17.219  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:17.219  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:17.219  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:09:17.219  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:09:17.219  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:09:17.219  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:09:17.219  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:09:17.221  3992  3992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:09:17.221  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:09:17.221  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:17.221  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:17.221  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:09:17.221  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:09:17.221  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:09:17.221  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:09:17.221  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:09:17.224   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 17:09:17.224   875  4137 D DhcpClient: Receive thread stopped
08-30 17:09:17.224   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] got DISCONNECTED, was satisfying 3
08-30 17:09:17.226   414   414 E Parcel  : Reading a NULL string not supported here.
08-30 17:09:17.226   371   873 D CommandListener: Clearing all IP addresses on wlan0
08-30 17:09:17.231   875  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-30 17:09:17.232   875  1319 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 102]
,08-30 17:09:17.240  1721  1721 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 17:09:17.244  1721  1721 D SystemUpdateService: onCreate
,08-30 17:09:17.244   875  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 17:09:17.247  3992  3992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:09:17.248  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:09:17.248  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:17.248  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:17.248  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:09:17.248  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:09:17.248  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:09:17.248  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:09:17.248  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:09:17.248  3992  3992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:09:17.248  3992  3992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:09:17.249  3992  3992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:09:17.249  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:09:17.249  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:17.249  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:17.249  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:09:17.249  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:09:17.249  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:09:17.249  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:09:17.249  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:09:17.249  3992  3992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:09:17.249  3992  3992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:09:17.250  1871  2337 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:09:17.256   875  1317 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-30 17:09:17.258   371   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 17:09:17.259  1721  1721 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 17:09:17.273  1721  4151 I SystemUpdateService: active receiver: enabled
,08-30 17:09:17.282  1721  1721 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 17:09:17.283  1721  1721 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 17:09:17.284   371   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-30 17:09:17.285   875  1319 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-30 17:09:17.285   875  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 17:09:17.285  3817  3817 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:09:17.287   875   892 D Tethering: MasterInitialState.processMessage what=3
08-30 17:09:17.290  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:17.292  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:17.296  3817  3817 D SprintDMHelper: simOperator: 
08-30 17:09:17.296  3817  3817 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 17:09:17.308  1721  4154 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 17:09:17.308  1721  4154 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 17:09:17.313  1721  4154 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 17:09:17.325  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 17:09:17.326  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 17:09:17.330  1721  1721 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 17:09:17.333  1721  4151 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 17:09:17.342  1721  1721 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 17:09:17.356  1721  4151 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-30 17:09:17.356  1721  4151 I SystemUpdateService: now status is 0 (complete)
08-30 17:09:17.356  1721  4151 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 17:09:17.356  1721  4151 I SystemUpdateService: file has been verified
08-30 17:09:17.356  1721  4151 I SystemUpdateService: OTA package size = 12249756
,08-30 17:09:17.356   371   873 E Netd    : netlink response contains error (No such file or directory)
,08-30 17:09:17.368  1721  1721 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 17:09:17.382  1721  1721 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 17:09:17.384  1721  4151 I SystemUpdateService: showing system update notification
,08-30 17:09:17.387  3817  3817 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:09:17.390  3817  3817 D SprintDMHelper: simOperator: 
,08-30 17:09:17.390  3817  3817 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 17:09:17.429  1515  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 17:09:17.429  1515  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-30 17:09:17.429  1515  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 17:09:17.429  1515  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 17:09:17.448  1721  4165 I SystemUpdateService: active receiver: enabled
,08-30 17:09:17.458  1721  4165 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 17:09:17.461  1721  4154 E MDM     : [182] SitrepService.a: Error sending sitrep.
,08-30 17:09:17.464  1721  4165 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-30 17:09:17.464  1721  4165 I SystemUpdateService: now status is 0 (complete)
08-30 17:09:17.464  1721  4165 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 17:09:17.464  1721  4165 I SystemUpdateService: file has been verified
08-30 17:09:17.464  1721  4165 I SystemUpdateService: OTA package size = 12249756
,08-30 17:09:17.470  1721  4165 I SystemUpdateService: showing system update notification
,08-30 17:09:17.480  1721  1721 D SystemUpdateService: onDestroy
,08-30 17:09:18.212   875  1319 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-30 17:09:20.184   875   892 I ActivityManager: Start proc 4167:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 17:09:20.346  4167  4167 D AdapterServiceConfig: Adding HeadsetService
,08-30 17:09:20.347  4167  4167 D AdapterServiceConfig: Adding A2dpService
,08-30 17:09:20.348  4167  4167 D AdapterServiceConfig: Adding HidService
,08-30 17:09:20.348  4167  4167 D AdapterServiceConfig: Adding HealthService
,08-30 17:09:20.349  4167  4167 D AdapterServiceConfig: Adding PanService
,08-30 17:09:20.350  4167  4167 D AdapterServiceConfig: Adding GattService
,08-30 17:09:20.350  4167  4167 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 17:09:20.378   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2efea91:true
08-30 17:09:20.378  4167  4167 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 17:09:20.382  4167  4167 I bt_bluedroid: init
,08-30 17:09:20.382  4167  4179 I BluetoothAdapterState: Entering OffState
,08-30 17:09:20.388  4167  4180 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 17:09:20.388  4167  4180 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-30 17:09:20.388  4167  4180 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-30 17:09:20.389  4167  4180 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 17:09:20.391  4167  4167 I bt_bluedroid: get_profile_interface socket
,08-30 17:09:20.393  4167  4183 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 17:09:20.395  4167  4183 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 17:09:20.396  4167  4167 I bt_bluedroid: get_profile_interface sdp
,08-30 17:09:20.401  4167  4178 I bt_bluedroid: config_hci_snoop_log
,08-30 17:09:20.404   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 17:09:20.412  4167  4179 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 17:09:20.412  4167  4179 D BluetoothAdapterProperties: Setting state to 14
08-30 17:09:20.413  4167  4179 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 17:09:20.417  4167  4179 D BluetoothBondStateMachine: make
,08-30 17:09:20.422  4167  4184 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 17:09:20.428  4167  4179 I BluetoothAdapterState: Entering PendingCommandState
,08-30 17:09:20.431  4167  4167 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 17:09:20.436  4167  4167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba4d30a
,08-30 17:09:20.437  4167  4167 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 17:09:20.438  4167  4167 D BtGatt.GattService: Received start request. Starting profile...
,08-30 17:09:20.438  4167  4167 D BtGatt.GattService: start()
08-30 17:09:20.439  4167  4167 I bt_bluedroid: get_profile_interface gatt
,08-30 17:09:20.440  4167  4167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba4d30a
08-30 17:09:20.440  4167  4167 D BtGatt.AdvertiseManager: advertise manager created
,08-30 17:09:20.451  4167  4167 V BluetoothAdapterState: isTurningOff()=false
,08-30 17:09:20.451  4167  4167 V BluetoothAdapterState: isTurningOn()=false
08-30 17:09:20.452  4167  4167 V BluetoothAdapterState: isBleTurningOn()=true
,08-30 17:09:20.452  4167  4167 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:09:20.453  4167  4179 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-30 17:09:20.454  4167  4179 I bt_bluedroid: enable
08-30 17:09:20.454  4167  4180 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-30 17:09:20.455  4167  4180 I bt_hci  : start_up
,08-30 17:09:20.476  4167  4180 I bt_vendor: alloc value 0xb39c4189
,08-30 17:09:20.476  4167  4180 I bt_vendor: init
08-30 17:09:20.476  4167  4180 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 17:09:20.476  4167  4180 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 17:09:20.583  4167  4180 D bt_hci  : start_up starting async portion
,08-30 17:09:20.584  4167  4187 I bt_hci  : event_finish_startup
08-30 17:09:20.584  4167  4187 I bt_hci_h4: hal_open
,08-30 17:09:20.585  4167  4187 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 17:09:20.592  4167  4187 I bt_userial_vendor: device fd = 51 open
,08-30 17:09:20.625  4167  4187 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 17:09:20.656  4167  4187 D bt_hwcfg: Chipset BCM4354A2
08-30 17:09:20.657  4167  4187 D bt_hwcfg: Target name = [BCM4354A2]
08-30 17:09:20.658  4167  4187 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 17:09:21.320  4167  4187 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 17:09:21.321  4167  4187 D bt_hwcfg: Settlement delay -- 100 ms
,08-30 17:09:21.322  4167  4187 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 17:09:21.439  4167  4187 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 17:09:21.440  4167  4187 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 17:09:21.469  4167  4187 I bt_hwcfg: vendor lib fwcfg completed
,08-30 17:09:21.470  4167  4187 I bt_vendor: firmware callback
08-30 17:09:21.470  4167  4187 I bt_hci  : firmware_config_callback
,08-30 17:09:21.483  4167  4189 I bt_btu  : btu_task pending for preload complete event
,08-30 17:09:21.483  4167  4189 I bt_btu_task: Bluetooth chip preload is complete
08-30 17:09:21.483  4167  4189 I bt_btu  : btu_task received preload complete event
,08-30 17:09:21.493  4167  4189 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 17:09:21.493  4167  4189 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 17:09:21.493  4167  4189 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 17:09:21.494  4167  4189 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-30 17:09:21.494  4167  4189 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 17:09:21.494  4167  4189 I         : BTE_InitTraceLevels -- TRC_A2D
,08-30 17:09:21.495  4167  4189 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 17:09:21.495  4167  4189 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 17:09:21.495  4167  4189 I         : BTE_InitTraceLevels -- TRC_GAP
,08-30 17:09:21.495  4167  4189 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 17:09:21.496  4167  4189 I         : BTE_InitTraceLevels -- TRC_SDP
,08-30 17:09:21.496  4167  4189 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 17:09:21.496  4167  4189 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 17:09:21.496  4167  4189 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-30 17:09:21.497  4167  4189 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 17:09:21.632  4167  4189 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3941d9d
,08-30 17:09:21.632  4167  4189 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3941d9d 
,08-30 17:09:21.657  4167  4183 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-30 17:09:21.658  4167  4183 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 17:09:21.659  4167  4183 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 17:09:21.662  4167  4183 D BluetoothAdapterProperties: Name is: Nexus 6
08-30 17:09:21.665  4167  4183 D BluetoothAdapterProperties: Scan Mode:20
,08-30 17:09:21.666  4167  4183 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 17:09:21.666  4167  4183 D bt_hci  : do_postload posting postload work item
,08-30 17:09:21.668  4167  4187 I bt_hci  : event_postload
,08-30 17:09:21.669  4167  4187 I bt_vendor: sco_config_cb
,08-30 17:09:21.669  4167  4187 I bt_hci  : sco_config_callback postload finished.
,08-30 17:09:21.671  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:21.673  4167  4183 D bt_bte_conf: Device ID record 1 : primary
08-30 17:09:21.673  4167  4183 D bt_bte_conf:   vendorId            = 000f
08-30 17:09:21.673  4167  4183 D bt_bte_conf:   vendorIdSource      = 0001
08-30 17:09:21.673  4167  4183 D bt_bte_conf:   product             = 1200
,08-30 17:09:21.673  4167  4183 D bt_bte_conf:   version             = 1436
08-30 17:09:21.673  4167  4183 D bt_bte_conf:   clientExecutableURL = 
08-30 17:09:21.674  4167  4183 D bt_bte_conf:   serviceDescription  = 
08-30 17:09:21.674  4167  4183 D bt_bte_conf:   documentationURL    = 
,08-30 17:09:21.674  4167  4183 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-30 17:09:21.674  4167  4180 D bt_stack_manager: event_start_up_stack finished
08-30 17:09:21.675  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:09:21.675  4167  4179 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-30 17:09:21.676  4167  4179 D BluetoothAdapterProperties: Setting state to 15
08-30 17:09:21.676  4167  4179 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 17:09:21.677  4167  4179 I BluetoothAdapterState: Entering BleOnState
08-30 17:09:21.680  4167  4187 I bt_vendor: low_power_mode_cb
08-30 17:09:21.683  4167  4179 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-30 17:09:21.683  4167  4179 D BluetoothAdapterProperties: Setting state to 11,
08-30 17:09:21.683  4167  4179 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-30 17:09:21.696  4167  4167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba4d30a
08-30 17:09:21.700  4167  4167 D HeadsetService: Received start request. Starting profile...,
08-30 17:09:21.702  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:21.705  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:21.711  4167  4179 I BluetoothAdapterState: Entering PendingCommandState
,08-30 17:09:21.711  4167  4167 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 17:09:21.712  4167  4167 D HeadsetStateMachine: make
,08-30 17:09:21.720  4167  4167 D HeadsetStateMachine: max_hf_connections = 1
,08-30 17:09:21.720  4167  4167 I bt_bluedroid: get_profile_interface handsfree
08-30 17:09:21.720  4167  4183 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 17:09:21.721  4167  4183 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-30 17:09:21.723  4167  4167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba4d30a
,08-30 17:09:21.724  4167  4167 D A2dpService: Received start request. Starting profile...
,08-30 17:09:21.725  4167  4167 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 17:09:21.725  4167  4167 I bt_bluedroid: get_profile_interface avrcp
,08-30 17:09:21.731  4167  4167 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 17:09:21.731  4167  4167 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 17:09:21.731  4167  4167 D A2dpStateMachine: make
,08-30 17:09:21.733  4167  4167 I bt_bluedroid: get_profile_interface a2dp
,08-30 17:09:21.733  4167  4183 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 17:09:21.735  4167  4198 D A2dpStateMachine: Enter Disconnected: -2
,08-30 17:09:21.736  4167  4167 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 17:09:21.737  4167  4167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba4d30a
,08-30 17:09:21.738  4167  4167 D HidService: Received start request. Starting profile...
08-30 17:09:21.738  4167  4167 I bt_bluedroid: get_profile_interface hidhost
08-30 17:09:21.738  4167  4167 D HidService: setHidService(): set to: null
08-30 17:09:21.738  4167  4183 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39233e5
08-30 17:09:21.738  4048  4048 D BluetoothInputDevice: Proxy object connected
08-30 17:09:21.738  4167  4183 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-30 17:09:21.739  4048  4048 D HidProfile: Bluetooth service connected
08-30 17:09:21.740  4167  4167 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 17:09:21.741  4167  4167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba4d30a
08-30 17:09:21.741  4167  4167 D HealthService: Received start request. Starting profile...,
08-30 17:09:21.741  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 17:09:21.742  4167  4167 I bt_bluedroid: get_profile_interface health
08-30 17:09:21.743  4167  4167 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 17:09:21.744  4167  4167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba4d30a
,08-30 17:09:21.745  4167  4167 D PanService: Received start request. Starting profile...
,08-30 17:09:21.745  4167  4167 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-30 17:09:21.745  4167  4167 I bt_bluedroid: get_profile_interface pan
08-30 17:09:21.745  4048  4048 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 17:09:21.746  4167  4183 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 17:09:21.746  4048  4048 D PanProfile: Bluetooth service connected
,08-30 17:09:21.748  4167  4167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba4d30a
08-30 17:09:21.749  4167  4167 D BluetoothMapService: Received start request. Starting profile...
08-30 17:09:21.749  4167  4167 D BluetoothMapService: start()
,08-30 17:09:21.749  4048  4048 D BluetoothMap: Proxy object connected
08-30 17:09:21.750  4048  4048 D MapProfile: Bluetooth service connected
08-30 17:09:21.750  4048  4048 D BluetoothMap: getConnectedDevices()
08-30 17:09:21.751  4167  4167 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-30 17:09:21.751  4048  4048 D BluetoothMap: Bluetooth is Not enabled
,08-30 17:09:21.751  4167  4167 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-30 17:09:21.751  4167  4167 D BluetoothMapAppObserver: createReceiver()
08-30 17:09:21.752  4167  4167 D BluetoothMapAppObserver: initObservers()
08-30 17:09:21.752  4167  4167 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 17:09:21.759  4167  4167 V BluetoothAdapterState: isTurningOff()=false
,08-30 17:09:21.760  4167  4167 V BluetoothAdapterState: isTurningOn()=true
08-30 17:09:21.760  4167  4196 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 17:09:21.760  4167  4167 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:09:21.760  4167  4167 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:09:21.761  4167  4167 V BluetoothAdapterState: isTurningOff()=false
,08-30 17:09:21.761  4167  4167 V BluetoothAdapterState: isTurningOn()=true
08-30 17:09:21.761  4167  4167 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:09:21.761  4167  4167 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 17:09:21.761  4167  4167 V BluetoothAdapterState: isTurningOff()=false
08-30 17:09:21.762  4167  4167 V BluetoothAdapterState: isTurningOn()=true
08-30 17:09:21.762  4167  4167 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:09:21.762  4167  4167 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:09:21.762  4167  4167 V BluetoothAdapterState: isTurningOff()=false
08-30 17:09:21.762  4167  4167 V BluetoothAdapterState: isTurningOn()=true
,08-30 17:09:21.762  4167  4167 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:09:21.762  4167  4167 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 17:09:21.764  4167  4167 V BluetoothAdapterState: isTurningOff()=false
,08-30 17:09:21.764  4167  4167 V BluetoothAdapterState: isTurningOn()=true
08-30 17:09:21.764  4167  4167 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:09:21.764  4167  4167 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:09:21.764  4167  4167 V BluetoothAdapterState: isTurningOff()=false
08-30 17:09:21.765  4167  4167 V BluetoothAdapterState: isTurningOn()=true
,08-30 17:09:21.765  4167  4167 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:09:21.765  4167  4167 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:09:21.765  4167  4179 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-30 17:09:21.765  4167  4179 D BluetoothAdapterProperties: ScanMode =  20
08-30 17:09:21.765  4167  4179 D BluetoothAdapterProperties: State =  11
08-30 17:09:21.766  4167  4179 D BluetoothAdapterProperties: Setting state to 12
08-30 17:09:21.766  4167  4179 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 17:09:21.766  1361  2124 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 17:09:21.767  4167  4183 D BluetoothAdapterProperties: Scan Mode:21
08-30 17:09:21.767  4167  4183 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 17:09:21.767  4167  4179 I BluetoothAdapterState: Entering OnState
08-30 17:09:21.770  1361  1361 D BluetoothInputDevice: Proxy object connected
08-30 17:09:21.770  1361  1361 D HidProfile: Bluetooth service connected
08-30 17:09:21.771  4048  4059 D BluetoothPan: onBluetoothStateChange on: true
08-30 17:09:21.771  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:09:21.771  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:21.771  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:21.771  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:09:21.771  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:09:21.771  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:09:21.771  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:09:21.771  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:09:21.771  1361  1381 D BluetoothMap: onBluetoothStateChange: up=true
08-30 17:09:21.773  3992  3992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:09:21.774   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 17:09:21.775  4048  4058 D BluetoothMap: onBluetoothStateChange: up=true
08-30 17:09:21.775   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 17:09:21.776  1361  1361 D BluetoothMap: Proxy object connected
08-30 17:09:21.776  1361  1361 D MapProfile: Bluetooth service connected
08-30 17:09:21.776  1361  1361 D BluetoothMap: getConnectedDevices()
,08-30 17:09:21.777  1361  2124 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 17:09:21.777   875   875 D BluetoothA2dp: Proxy object connected
08-30 17:09:21.778  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:09:21.778  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:21.778  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:21.778  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:09:21.778  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:09:21.778  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:09:21.778  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:09:21.778  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:09:21.780  4167  4167 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 17:09:21.780  3992  3992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:09:21.780  1361  1361 D BluetoothA2dp: Proxy object connected
,08-30 17:09:21.781  4167  4167 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-30 17:09:21.781  1361  1381 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:09:21.782  1969  2161 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:09:21.782   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:09:21.783  4167  4167 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:09:21.783  4048  4059 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 17:09:21.783  1361  1374 D BluetoothPan: onBluetoothStateChange on: true
,08-30 17:09:21.785  4167  4167 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:09:21.785  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 17:09:21.786  1361  1361 D PanProfile: Bluetooth service connected
,08-30 17:09:21.786  1361  1381 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 17:09:21.786  4167  4167 D ObexServerSockets: Succeed to create listening sockets 
,08-30 17:09:21.786  4167  4167 D ObexServerSockets0: startAccept()
08-30 17:09:21.787  4167  4167 D ObexServerSockets0: prepareForNewConnect()
,08-30 17:09:21.788  4048  4058 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 17:09:21.789  4167  4167 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-30 17:09:21.789  4167  4167 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-30 17:09:21.790   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 17:09:21.790  4167  4206 D ObexServerSockets0: Accepting socket connection...
08-30 17:09:21.791  4167  4207 D ObexServerSockets0: Accepting socket connection...
,08-30 17:09:21.792   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 17:09:21.793  4167  4167 D BluetoothMapService: onReceive
,08-30 17:09:21.794  4167  4167 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:09:21.794  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:09:21.794  4167  4167 D BluetoothMapService: STATE_ON
08-30 17:09:21.795  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:21.797  4048  4048 D LocalBluetoothProfileManager: Adding local A2DP profile
08-30 17:09:21.800  4048  4048 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-30 17:09:21.806  4048  4048 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:09:21.808  4048  4048 D BluetoothA2dp: Proxy object connected
,08-30 17:09:21.818  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 17:09:21.821  1361  1361 D BluetoothPbap: Proxy object connected
08-30 17:09:21.821  1361  1361 D PbapServerProfile: Bluetooth service connected
,08-30 17:09:21.821  4167  4167 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 17:09:21.822  4167  4167 D ObexServerSockets0: prepareForNewConnect()
,08-30 17:09:21.824  4167  4208 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:09:21.827  4048  4048 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:09:21.828  4048  4048 D BluetoothPbap: Proxy object connected
08-30 17:09:21.828  4048  4048 D PbapServerProfile: Bluetooth service connected
,08-30 17:09:21.849  4167  4215 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:09:21.851  4167  4215 I BtOppRfcommListener: Accept thread started.
,08-30 17:09:21.877  1361  2124 D BluetoothHeadset: Proxy object connected
,08-30 17:09:21.877  1361  1361 D HeadsetProfile: Bluetooth service connected
,08-30 17:09:21.877   875   875 D BluetoothHeadset: Proxy object connected
08-30 17:09:21.878   875   875 D BluetoothHeadset: Proxy object connected
,08-30 17:09:21.878  1969  1996 D BluetoothHeadset: Proxy object connected
08-30 17:09:21.878   875   875 D BluetoothHeadset: Proxy object connected
,08-30 17:09:21.882  1361  1374 D BluetoothHeadset: Proxy object connected
,08-30 17:09:21.883  1361  1361 D HeadsetProfile: Bluetooth service connected
,08-30 17:09:21.883  1969  2163 D BluetoothHeadset: Proxy object connected,
08-30 17:09:21.884   875   892 D BluetoothHeadset: Proxy object connected
,08-30 17:09:21.890   875   892 D BluetoothHeadset: Proxy object connected
,08-30 17:09:21.904  4048  4058 D BluetoothHeadset: Proxy object connected
,08-30 17:09:21.906  4048  4048 D HeadsetProfile: Bluetooth service connected
,08-30 17:09:22.148   875  4135 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-30 17:09:22.154   875  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 17:09:23.145  4167  4179 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 17:09:23.145  4167  4179 D BluetoothAdapterProperties: Setting state to 13
08-30 17:09:23.145  4167  4179 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 17:09:23.147  4167  4179 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 17:09:23.151  4167  4179 I BluetoothAdapterState: Entering PendingCommandState
,08-30 17:09:23.155  4167  4183 D BluetoothAdapterProperties: Scan Mode:20
,08-30 17:09:23.156  4167  4179 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-30 17:09:23.160  4167  4167 D BluetoothMapService: onReceive
08-30 17:09:23.160  4167  4167 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:09:23.161  4167  4167 D BluetoothMapService: STATE_TURNING_OFF
08-30 17:09:23.161  4167  4167 D BluetoothMapService: MAP Service closeService in
08-30 17:09:23.162  4167  4167 D BluetoothMapMasInstance0: MAP Service shutdown,
08-30 17:09:23.162  4167  4167 D ObexServerSockets0: shutdown(block = true)
,08-30 17:09:23.163  4167  4167 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 17:09:23.163  4167  4167 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-30 17:09:23.163  4167  4191 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-30 17:09:23.163  4167  4206 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 17:09:23.164  4167  4207 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-30 17:09:23.169  4167  4167 I BtOppRfcommListener: stopping Accept Thread
,08-30 17:09:23.170  4167  4215 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:09:23.172  4167  4215 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-30 17:09:23.182  3992  3992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:09:23.182  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-30 17:09:23.182  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:23.182  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:23.182  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:09:23.182  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:09:23.182  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:09:23.182  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:09:23.182  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:09:23.183  3992  3992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:09:23.183  3992  3992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:09:23.184  4167  4167 D HeadsetService: Received stop request...Stopping profile...
08-30 17:09:23.187  1361  1381 D BluetoothHeadset: Proxy object disconnected
08-30 17:09:23.187   875   875 D BluetoothHeadset: Proxy object disconnected
,08-30 17:09:23.187  3992  3992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:09:23.187   875   875 D BluetoothHeadset: Proxy object disconnected
08-30 17:09:23.187  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:09:23.187  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:23.187  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:23.187  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:09:23.187  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:09:23.187  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,08-30 17:09:23.187  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:09:23.187  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:09:23.188  1969  1989 D BluetoothHeadset: Proxy object disconnected
08-30 17:09:23.188  3992  3992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:09:23.188  4167  4167 D A2dpService: Received stop request...Stopping profile...
08-30 17:09:23.188  3992  3992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:09:23.188  4048  4059 D BluetoothHeadset: Proxy object disconnected
,08-30 17:09:23.189   875   875 D BluetoothHeadset: Proxy object disconnected
08-30 17:09:23.189  4167  4198 D A2dpStateMachine: Exit Disconnected: -1
08-30 17:09:23.189  1361  1361 D HeadsetProfile: Bluetooth service disconnected
08-30 17:09:23.190  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:23.190   875   875 D BluetoothA2dp: Proxy object disconnected
08-30 17:09:23.191  1361  1361 D BluetoothA2dp: Proxy object disconnected
08-30 17:09:23.191  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:09:23.191  4048  4048 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:09:23.192  4167  4167 D HidService: Received stop request...Stopping profile...
08-30 17:09:23.192  4167  4167 D HidService: Stopping Bluetooth HidService
08-30 17:09:23.194  1361  1361 D BluetoothInputDevice: Proxy object disconnected
,08-30 17:09:23.194  1361  1361 D HidProfile: Bluetooth service disconnected
08-30 17:09:23.195  4167  4167 D HealthService: Received stop request...Stopping profile...
08-30 17:09:23.196  4048  4048 D HeadsetProfile: Bluetooth service disconnected
08-30 17:09:23.197  4048  4048 D BluetoothA2dp: Proxy object disconnected
08-30 17:09:23.198  4167  4167 D PanService: Received stop request...Stopping profile...
,08-30 17:09:23.199  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 17:09:23.200  1361  1361 D PanProfile: Bluetooth service disconnected
,08-30 17:09:23.200  4167  4167 D BluetoothMapService: Received stop request...Stopping profile...
08-30 17:09:23.200  4167  4167 D BluetoothMapService: stop()
08-30 17:09:23.201  4167  4167 D BluetoothMapAppObserver: deinitObservers()
08-30 17:09:23.201  4167  4167 D BluetoothMapAppObserver: removeReceiver()
,08-30 17:09:23.201  4048  4048 D DockEventReceiver: finishStartingService: stopping service
08-30 17:09:23.202  1361  1361 D BluetoothMap: Proxy object disconnected
08-30 17:09:23.202  1361  1361 D MapProfile: Bluetooth service disconnected
08-30 17:09:23.203  4048  4048 D BluetoothInputDevice: Proxy object disconnected
08-30 17:09:23.203  4048  4048 D HidProfile: Bluetooth service disconnected
,08-30 17:09:23.203  4167  4167 V BluetoothAdapterState: isTurningOff()=true
08-30 17:09:23.203  4167  4167 V BluetoothAdapterState: isTurningOn()=false
08-30 17:09:23.203  4048  4048 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 17:09:23.203  4167  4167 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:09:23.203  4048  4048 D PanProfile: Bluetooth service disconnected
08-30 17:09:23.203  4167  4167 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 17:09:23.203  4048  4048 D BluetoothMap: Proxy object disconnected
08-30 17:09:23.204  4048  4048 D MapProfile: Bluetooth service disconnected
,08-30 17:09:23.206  4167  4167 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 17:09:23.206  4167  4167 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 17:09:23.206  4167  4183 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-30 17:09:23.206  4167  4189 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 17:09:23.206  4167  4189 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 17:09:23.206  4167  4189 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 17:09:23.206  4167  4183 E bt_btif : btif_hf_upstreams_evt: Invalid index 65534
08-30 17:09:23.207  4167  4167 V BluetoothAdapterState: isTurningOff()=true
08-30 17:09:23.207  4167  4167 V BluetoothAdapterState: isTurningOn()=false
08-30 17:09:23.207  4167  4167 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 17:09:23.208  4167  4167 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 17:09:23.209  4167  4183 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-30 17:09:23.209  4167  4189 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 17:09:23.209  4167  4189 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 17:09:23.209  4167  4189 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 17:09:23.209  4167  4189 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:09:23.209  4167  4189 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:09:23.209  4167  4189 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 17:09:23.210  4167  4167 V BluetoothAdapterState: isTurningOff()=true
,08-30 17:09:23.210  4167  4167 V BluetoothAdapterState: isTurningOn()=false
08-30 17:09:23.210  4167  4167 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 17:09:23.210  4167  4167 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:09:23.210  4167  4167 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 17:09:23.211  4167  4183 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 17:09:23.211  4167  4167 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-30 17:09:23.213  4167  4167 V BluetoothAdapterState: isTurningOff()=true
08-30 17:09:23.214  4167  4167 V BluetoothAdapterState: isTurningOn()=false
08-30 17:09:23.214  4167  4167 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 17:09:23.214  4167  4167 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:09:23.214  4167  4167 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 17:09:23.214  4167  4183 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 17:09:23.214  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 17:09:23.215  4167  4167 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 17:09:23.215  4167  4167 V BluetoothAdapterState: isTurningOff()=true
08-30 17:09:23.215  4167  4167 V BluetoothAdapterState: isTurningOn()=false
08-30 17:09:23.215  4167  4167 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:09:23.215  4167  4167 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:09:23.215  4167  4167 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 17:09:23.216  4167  4167 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-30 17:09:23.217  4167  4167 D BluetoothMapService: MAP Service closeService in
08-30 17:09:23.217  4167  4167 V BluetoothAdapterState: isTurningOff()=true
08-30 17:09:23.217  4167  4167 V BluetoothAdapterState: isTurningOn()=false
08-30 17:09:23.217  4167  4167 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:09:23.217  4167  4167 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 17:09:23.217  4167  4179 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 17:09:23.217  4167  4179 D BluetoothAdapterProperties: Setting state to 15
,08-30 17:09:23.217  4167  4179 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 17:09:23.217  4167  4167 D BluetoothMapService: cleanup()
,08-30 17:09:23.218  4167  4167 D BluetoothMapService: MAP Service closeService in
08-30 17:09:23.218  4167  4179 I BluetoothAdapterState: Entering BleOnState
,08-30 17:09:23.218  1361  1381 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 17:09:23.219  4048  4058 D BluetoothPan: onBluetoothStateChange on: false
,08-30 17:09:23.220  4048  4059 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 17:09:23.221  1361  1361 D BluetoothPbap: Proxy object disconnected
,08-30 17:09:23.221  1361  1361 D PbapServerProfile: Bluetooth service disconnected
08-30 17:09:23.221  1361  1374 D BluetoothMap: onBluetoothStateChange: up=false
08-30 17:09:23.221  4048  4048 D BluetoothPbap: Proxy object disconnected,
08-30 17:09:23.222   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:09:23.223  4048  4059 D BluetoothMap: onBluetoothStateChange: up=false,
08-30 17:09:23.224   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 17:09:23.224  1361  2124 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 17:09:23.225  1361  1381 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:09:23.225  1969  2161 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 17:09:23.225   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:09:23.226  4048  4058 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:09:23.226  4048  4221 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-30 17:09:23.221  4048  4048 D PbapServerProfile: Bluetooth service disconnected
08-30 17:09:23.228  1361  1374 D BluetoothPan: onBluetoothStateChange on: false
08-30 17:09:23.229  1361  2124 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 17:09:23.229  4048  4059 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 17:09:23.230   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:09:23.230  4167  4179 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-30 17:09:23.230  4167  4179 D BluetoothAdapterProperties: Setting state to 16
08-30 17:09:23.230  4167  4179 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-30 17:09:23.231  4167  4179 D BluetoothAdapterProperties: onBleDisable
08-30 17:09:23.231  4167  4179 I BluetoothAdapterState: Entering PendingCommandState
08-30 17:09:23.233  4167  4180 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 17:09:23.234  4167  4189 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 17:09:23.234  4167  4189 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 17:09:23.235  4167  4183 D BluetoothAdapterProperties: Scan Mode:20
08-30 17:09:23.236  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:09:23.237  4048  4048 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:09:23.237  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:09:23.238  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:09:23.239  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:23.242  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 17:09:23.245  4048  4048 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:09:23.435  4167  4183 I bt_hci  : shut_down
08-30 17:09:23.436  4167  4187 D bt_hwcfg: hw_epilog_process
,08-30 17:09:23.437  4167  4187 I bt_vendor: low_power_mode_cb
,08-30 17:09:23.463  4167  4187 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 17:09:23.463  4167  4187 I bt_vendor: epilog_cb
08-30 17:09:23.463  4167  4187 I bt_hci  : epilog_finished_callback
08-30 17:09:23.465  4167  4183 I bt_hci_h4: hal_close
,08-30 17:09:23.467  4167  4183 I bt_userial_vendor: device fd = 51 close
,08-30 17:09:23.597  4167  4180 D bt_stack_manager: event_shut_down_stack finished.
,08-30 17:09:23.598  4167  4179 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 17:09:23.604  4167  4167 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 17:09:23.604  4167  4179 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-30 17:09:23.605  4167  4167 D BtGatt.GattService: Received stop request...Stopping profile...
,08-30 17:09:23.606  4167  4167 D BtGatt.GattService: stop()
08-30 17:09:23.606  4167  4167 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 17:09:23.610  4167  4167 V BluetoothAdapterState: isTurningOff()=false
,08-30 17:09:23.611  4167  4167 V BluetoothAdapterState: isTurningOn()=false
08-30 17:09:23.611  4167  4167 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 17:09:23.611  4167  4167 V BluetoothAdapterState: isBleTurningOff()=true
08-30 17:09:23.612  4167  4179 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-30 17:09:23.613  4167  4179 D BluetoothAdapterProperties: Setting state to 10
08-30 17:09:23.613  4167  4179 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-30 17:09:23.615  4167  4179 I BluetoothAdapterState: Entering OffState
,08-30 17:09:23.617   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-30 17:09:23.648  4167  4167 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-30 17:09:23.648  4167  4167 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 17:09:23.648  4167  4180 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 17:09:23.656  4167  4180 D bt_stack_manager: event_clean_up_stack finished.
08-30 17:09:23.656  4167  4167 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 17:09:23.659  4167  4167 I art     : System.exit called, status: 0
,08-30 17:09:23.659  4167  4167 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 17:09:23.698   875   886 I ActivityManager: Process com.android.bluetooth (pid 4167) has died
,08-30 17:09:25.142   875  1319 D ConnectivityService: handlePromptUnvalidated 102
,08-30 17:09:26.142  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 17:09:26.142  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:09:29.151  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:09:29.151  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2888470 added. We now have 6 listener(s)
08-30 17:09:29.151  3992  4040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:09:29.155  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:09:29.156  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b1ab3e9 added. We now have 7 listener(s)
,08-30 17:09:29.156  3992  4040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:09:29.158  3992  4040 I System.out: IsBluetoothEnabled
,08-30 17:09:29.170  3992  4040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:29.208   875   892 I ActivityManager: Start proc 4228:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 17:09:29.334  4228  4228 D AdapterServiceConfig: Adding HeadsetService
08-30 17:09:29.335  4228  4228 D AdapterServiceConfig: Adding A2dpService
08-30 17:09:29.335  4228  4228 D AdapterServiceConfig: Adding HidService
08-30 17:09:29.335  4228  4228 D AdapterServiceConfig: Adding HealthService
08-30 17:09:29.335  4228  4228 D AdapterServiceConfig: Adding PanService
08-30 17:09:29.336  4228  4228 D AdapterServiceConfig: Adding GattService
08-30 17:09:29.336  4228  4228 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 17:09:29.353   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ee49fea:true
08-30 17:09:29.353  4228  4228 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 17:09:29.358  4228  4228 I bt_bluedroid: init,
08-30 17:09:29.359  4228  4240 I BluetoothAdapterState: Entering OffState
,08-30 17:09:29.364  4228  4241 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 17:09:29.365  4228  4241 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 17:09:29.365  4228  4241 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 17:09:29.366  4228  4241 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 17:09:29.367  4228  4228 I bt_bluedroid: get_profile_interface socket
,08-30 17:09:29.370  4228  4228 I bt_bluedroid: get_profile_interface sdp
,08-30 17:09:29.375  4228  4244 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 17:09:29.375  4228  4239 I bt_bluedroid: config_hci_snoop_log
,08-30 17:09:29.379   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 17:09:29.379  4228  4244 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 17:09:29.389  4228  4240 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 17:09:29.390  4228  4240 D BluetoothAdapterProperties: Setting state to 14
,08-30 17:09:29.391  4228  4240 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 17:09:29.395  4228  4240 D BluetoothBondStateMachine: make
,08-30 17:09:29.400  4228  4245 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 17:09:29.406  4228  4240 I BluetoothAdapterState: Entering PendingCommandState
,08-30 17:09:29.408  4228  4228 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 17:09:29.413  4228  4228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba4d30a
,08-30 17:09:29.415  4228  4228 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 17:09:29.416  4228  4228 D BtGatt.GattService: Received start request. Starting profile...
,08-30 17:09:29.416  4228  4228 D BtGatt.GattService: start()
08-30 17:09:29.417  4228  4228 I bt_bluedroid: get_profile_interface gatt
,08-30 17:09:29.419  4228  4228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba4d30a
,08-30 17:09:29.419  4228  4228 D BtGatt.AdvertiseManager: advertise manager created
,08-30 17:09:29.434  4228  4228 V BluetoothAdapterState: isTurningOff()=false
08-30 17:09:29.435  4228  4228 V BluetoothAdapterState: isTurningOn()=false
08-30 17:09:29.435  4228  4228 V BluetoothAdapterState: isBleTurningOn()=true
08-30 17:09:29.435  4228  4228 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 17:09:29.436  4228  4240 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-30 17:09:29.437  4228  4240 I bt_bluedroid: enable
,08-30 17:09:29.438  4228  4241 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-30 17:09:29.439  4228  4241 I bt_hci  : start_up
,08-30 17:09:29.461  4228  4241 I bt_vendor: alloc value 0xb39c4189
,08-30 17:09:29.462  4228  4241 I bt_vendor: init
,08-30 17:09:29.462  4228  4241 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-30 17:09:29.462  4228  4241 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 17:09:29.568  4228  4241 D bt_hci  : start_up starting async portion
,08-30 17:09:29.569  4228  4248 I bt_hci  : event_finish_startup
08-30 17:09:29.569  4228  4248 I bt_hci_h4: hal_open
08-30 17:09:29.570  4228  4248 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 17:09:29.579  4228  4248 I bt_userial_vendor: device fd = 51 open
,08-30 17:09:29.611  4228  4248 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 17:09:29.643  4228  4248 D bt_hwcfg: Chipset BCM4354A2
,08-30 17:09:29.644  4228  4248 D bt_hwcfg: Target name = [BCM4354A2]
,08-30 17:09:29.644  4228  4248 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 17:09:30.312  4228  4248 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 17:09:30.313  4228  4248 D bt_hwcfg: Settlement delay -- 100 ms
,08-30 17:09:30.314  4228  4248 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 17:09:30.430  4228  4248 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 17:09:30.432  4228  4248 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 17:09:30.462  4228  4248 I bt_hwcfg: vendor lib fwcfg completed
,08-30 17:09:30.462  4228  4248 I bt_vendor: firmware callback
,08-30 17:09:30.462  4228  4248 I bt_hci  : firmware_config_callback
,08-30 17:09:30.474  4228  4250 I bt_btu  : btu_task pending for preload complete event
,08-30 17:09:30.474  4228  4250 I bt_btu_task: Bluetooth chip preload is complete
,08-30 17:09:30.474  4228  4250 I bt_btu  : btu_task received preload complete event
,08-30 17:09:30.485  4228  4250 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 17:09:30.486  4228  4250 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-30 17:09:30.486  4228  4250 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-30 17:09:30.486  4228  4250 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 17:09:30.486  4228  4250 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 17:09:30.487  4228  4250 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 17:09:30.487  4228  4250 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 17:09:30.488  4228  4250 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 17:09:30.488  4228  4250 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 17:09:30.488  4228  4250 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 17:09:30.489  4228  4250 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 17:09:30.489  4228  4250 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 17:09:30.489  4228  4250 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 17:09:30.490  4228  4250 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 17:09:30.490  4228  4250 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 17:09:30.628  4228  4250 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3941d9d
,08-30 17:09:30.628  4228  4250 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3941d9d 
,08-30 17:09:30.651  4228  4244 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 17:09:30.652  4228  4244 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 17:09:30.653  4228  4244 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 17:09:30.654  4228  4244 D BluetoothAdapterProperties: Name is: Nexus 6
08-30 17:09:30.655  4228  4244 D BluetoothAdapterProperties: Scan Mode:20
08-30 17:09:30.655  4228  4244 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 17:09:30.655  4228  4244 D bt_hci  : do_postload posting postload work item
08-30 17:09:30.655  4228  4248 I bt_hci  : event_postload
08-30 17:09:30.656  4228  4248 I bt_vendor: sco_config_cb
08-30 17:09:30.656  4228  4248 I bt_hci  : sco_config_callback postload finished.
,08-30 17:09:30.659  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:30.660  4228  4244 D bt_bte_conf: Device ID record 1 : primary
,08-30 17:09:30.660  4228  4244 D bt_bte_conf:   vendorId            = 000f
,08-30 17:09:30.661  4228  4244 D bt_bte_conf:   vendorIdSource      = 0001
,08-30 17:09:30.661  4228  4244 D bt_bte_conf:   product             = 1200
08-30 17:09:30.661  4228  4244 D bt_bte_conf:   version             = 1436
08-30 17:09:30.661  4228  4244 D bt_bte_conf:   clientExecutableURL = 
08-30 17:09:30.661  4228  4244 D bt_bte_conf:   serviceDescription  = 
08-30 17:09:30.661  4228  4244 D bt_bte_conf:   documentationURL    = 
08-30 17:09:30.661  4228  4244 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-30 17:09:30.661  4228  4241 D bt_stack_manager: event_start_up_stack finished
,08-30 17:09:30.662  4228  4240 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 17:09:30.663  4228  4240 D BluetoothAdapterProperties: Setting state to 15
08-30 17:09:30.663  4228  4240 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 17:09:30.665  4228  4240 I BluetoothAdapterState: Entering BleOnState
08-30 17:09:30.669  4228  4248 I bt_vendor: low_power_mode_cb
,08-30 17:09:30.671  4228  4240 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-30 17:09:30.671  4228  4240 D BluetoothAdapterProperties: Setting state to 11
08-30 17:09:30.671  4228  4240 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-30 17:09:30.680  4228  4228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba4d30a
,08-30 17:09:30.682  4228  4228 D HeadsetService: Received start request. Starting profile...
,08-30 17:09:30.691  4228  4228 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-30 17:09:30.691  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:30.691  4228  4228 D HeadsetStateMachine: make
,08-30 17:09:30.698  4228  4240 I BluetoothAdapterState: Entering PendingCommandState
,08-30 17:09:30.702  4228  4228 D HeadsetStateMachine: max_hf_connections = 1
08-30 17:09:30.702  4228  4228 I bt_bluedroid: get_profile_interface handsfree
,08-30 17:09:30.702  4228  4244 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 17:09:30.703  4228  4244 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-30 17:09:30.707  4228  4228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba4d30a
,08-30 17:09:30.708  4228  4228 D A2dpService: Received start request. Starting profile...
,08-30 17:09:30.709  4228  4228 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 17:09:30.709  4228  4228 I bt_bluedroid: get_profile_interface avrcp
,08-30 17:09:30.716  4228  4228 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 17:09:30.716  4228  4228 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-30 17:09:30.716  4228  4228 D A2dpStateMachine: make
,08-30 17:09:30.717  4228  4228 I bt_bluedroid: get_profile_interface a2dp
,08-30 17:09:30.718  4228  4244 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 17:09:30.719  4228  4259 D A2dpStateMachine: Enter Disconnected: -2
,08-30 17:09:30.720  4228  4228 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 17:09:30.721  4228  4228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba4d30a
,08-30 17:09:30.722  4228  4228 D HidService: Received start request. Starting profile...
,08-30 17:09:30.722  4228  4228 I bt_bluedroid: get_profile_interface hidhost
08-30 17:09:30.722  4228  4228 D HidService: setHidService(): set to: null
08-30 17:09:30.722  4228  4244 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39233e5
,08-30 17:09:30.722  4228  4244 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-30 17:09:30.722  4228  4228 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 17:09:30.723  4228  4228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba4d30a
08-30 17:09:30.724  4228  4228 D HealthService: Received start request. Starting profile...
,08-30 17:09:30.725  4228  4228 I bt_bluedroid: get_profile_interface health
,08-30 17:09:30.726  4228  4228 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 17:09:30.727  4228  4228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba4d30a
,08-30 17:09:30.727  4228  4228 D PanService: Received start request. Starting profile...
08-30 17:09:30.728  4228  4228 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 17:09:30.728  4228  4228 I bt_bluedroid: get_profile_interface pan
08-30 17:09:30.728  4228  4244 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 17:09:30.731  4228  4228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba4d30a
,08-30 17:09:30.732  4228  4228 D BluetoothMapService: Received start request. Starting profile...
08-30 17:09:30.732  4228  4228 D BluetoothMapService: start()
,08-30 17:09:30.735  4228  4228 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 17:09:30.736  4228  4228 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-30 17:09:30.736  4228  4228 D BluetoothMapAppObserver: createReceiver()
,08-30 17:09:30.737  4228  4228 D BluetoothMapAppObserver: initObservers()
08-30 17:09:30.737  4228  4228 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 17:09:30.746  4228  4228 V BluetoothAdapterState: isTurningOff()=false
08-30 17:09:30.747  4228  4228 V BluetoothAdapterState: isTurningOn()=true
08-30 17:09:30.747  4228  4228 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:09:30.747  4228  4228 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:09:30.747  4228  4257 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 17:09:30.748  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 17:09:30.749  4228  4228 V BluetoothAdapterState: isTurningOff()=false
,08-30 17:09:30.749  4228  4228 V BluetoothAdapterState: isTurningOn()=true
,08-30 17:09:30.749  4228  4228 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:09:30.749  4228  4228 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 17:09:30.749  4228  4228 V BluetoothAdapterState: isTurningOff()=false
,08-30 17:09:30.749  4228  4228 V BluetoothAdapterState: isTurningOn()=true
08-30 17:09:30.750  4228  4228 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 17:09:30.750  4228  4228 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 17:09:30.750  4228  4228 V BluetoothAdapterState: isTurningOff()=false
08-30 17:09:30.750  4228  4228 V BluetoothAdapterState: isTurningOn()=true
,08-30 17:09:30.750  4228  4228 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 17:09:30.750  4228  4228 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 17:09:30.750  4228  4228 V BluetoothAdapterState: isTurningOff()=false
08-30 17:09:30.750  4228  4228 V BluetoothAdapterState: isTurningOn()=true
,08-30 17:09:30.751  4228  4228 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:09:30.751  4228  4228 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 17:09:30.751  4228  4228 V BluetoothAdapterState: isTurningOff()=false
,08-30 17:09:30.751  4228  4228 V BluetoothAdapterState: isTurningOn()=true
08-30 17:09:30.751  4228  4228 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 17:09:30.751  4228  4228 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:09:30.751  4228  4240 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-30 17:09:30.752  4228  4240 D BluetoothAdapterProperties: ScanMode =  20
08-30 17:09:30.752  4228  4240 D BluetoothAdapterProperties: State =  11
,08-30 17:09:30.754  4228  4240 D BluetoothAdapterProperties: Setting state to 12
,08-30 17:09:30.754  4228  4240 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 17:09:30.755  4228  4240 I BluetoothAdapterState: Entering OnState
08-30 17:09:30.755  1361  1381 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 17:09:30.756  4228  4244 D BluetoothAdapterProperties: Scan Mode:21
,08-30 17:09:30.756  4228  4244 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 17:09:30.760  4048  4058 D BluetoothPan: onBluetoothStateChange on: true
08-30 17:09:30.760  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:09:30.760  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:30.760  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:30.760  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:09:30.760  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:09:30.760  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:09:30.760  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:09:30.760  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:09:30.762  3992  3992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:09:30.763  1361  1361 D BluetoothInputDevice: Proxy object connected
,08-30 17:09:30.763  1361  1361 D HidProfile: Bluetooth service connected
,08-30 17:09:30.764  4048  4221 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 17:09:30.764  4228  4228 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 17:09:30.765  4228  4228 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-30 17:09:30.766  1361  2124 D BluetoothMap: onBluetoothStateChange: up=true
08-30 17:09:30.767  4228  4228 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:09:30.768   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 17:09:30.768  4048  4059 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 17:09:30.769  4228  4228 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:09:30.769   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 17:09:30.770  1361  1381 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 17:09:30.771  4228  4228 D ObexServerSockets: Succeed to create listening sockets 
08-30 17:09:30.771  4228  4228 D ObexServerSockets0: startAccept()
,08-30 17:09:30.771  4228  4228 D ObexServerSockets0: prepareForNewConnect()
08-30 17:09:30.772  1361  1374 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 17:09:30.772  4228  4228 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 17:09:30.773  4228  4228 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 17:09:30.773  1969  2161 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:09:30.774   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:09:30.774  4048  4221 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:09:30.774   875   875 D BluetoothA2dp: Proxy object connected
08-30 17:09:30.775  1361  1361 D BluetoothA2dp: Proxy object connected
08-30 17:09:30.775  4048  4048 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 17:09:30.775  4048  4048 D PanProfile: Bluetooth service connected
08-30 17:09:30.775  4048  4048 D BluetoothA2dp: Proxy object connected
08-30 17:09:30.776  4048  4059 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 17:09:30.776  4228  4264 D ObexServerSockets0: Accepting socket connection...
08-30 17:09:30.776  4228  4265 D ObexServerSockets0: Accepting socket connection...
08-30 17:09:30.777  1361  1361 D BluetoothMap: Proxy object connected
08-30 17:09:30.777  1361  1361 D MapProfile: Bluetooth service connected
08-30 17:09:30.777  1361  1374 D BluetoothPan: onBluetoothStateChange on: true
08-30 17:09:30.778  1361  1361 D BluetoothMap: getConnectedDevices()
08-30 17:09:30.778  4048  4048 D BluetoothInputDevice: Proxy object connected
08-30 17:09:30.778  4048  4048 D HidProfile: Bluetooth service connected
,08-30 17:09:30.779  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 17:09:30.779  1361  1361 D PanProfile: Bluetooth service connected
,08-30 17:09:30.779  1361  1381 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 17:09:30.780  4048  4048 D BluetoothMap: Proxy object connected
08-30 17:09:30.780  4048  4048 D MapProfile: Bluetooth service connected
,08-30 17:09:30.780  4048  4048 D BluetoothMap: getConnectedDevices()
,08-30 17:09:30.781  4048  4058 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 17:09:30.782   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:09:30.784   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 17:09:30.786  4228  4228 D BluetoothMapService: onReceive
,08-30 17:09:30.786  4228  4228 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:09:30.786  4228  4228 D BluetoothMapService: STATE_ON
08-30 17:09:30.786  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:30.791  4048  4048 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:09:30.797  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 17:09:30.800  4048  4048 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:09:30.806  4048  4048 D BluetoothPbap: Proxy object connected
,08-30 17:09:30.806  4048  4048 D PbapServerProfile: Bluetooth service connected
,08-30 17:09:30.813  4228  4228 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 17:09:30.813  1361  1361 D BluetoothPbap: Proxy object connected
08-30 17:09:30.813  1361  1361 D PbapServerProfile: Bluetooth service connected
08-30 17:09:30.814  4228  4228 D ObexServerSockets0: prepareForNewConnect()
08-30 17:09:30.816  4228  4270 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:09:30.836  4228  4274 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:09:30.838  4228  4274 I BtOppRfcommListener: Accept thread started.
,08-30 17:09:30.869  1361  1374 D BluetoothHeadset: Proxy object connected
,08-30 17:09:30.869  1361  1361 D HeadsetProfile: Bluetooth service connected
,08-30 17:09:30.869   875   875 D BluetoothHeadset: Proxy object connected
08-30 17:09:30.870   875   875 D BluetoothHeadset: Proxy object connected
,08-30 17:09:30.871  1969  1996 D BluetoothHeadset: Proxy object connected
,08-30 17:09:30.872  4048  4059 D BluetoothHeadset: Proxy object connected
,08-30 17:09:30.873   875   875 D BluetoothHeadset: Proxy object connected
,08-30 17:09:30.874  1361  2124 D BluetoothHeadset: Proxy object connected
,08-30 17:09:30.874  1361  1361 D HeadsetProfile: Bluetooth service connected
08-30 17:09:30.876  1969  2163 D BluetoothHeadset: Proxy object connected
,08-30 17:09:30.877   875   892 D BluetoothHeadset: Proxy object connected
,08-30 17:09:30.878  4048  4221 D BluetoothHeadset: Proxy object connected
,08-30 17:09:30.873  4048  4048 D HeadsetProfile: Bluetooth service connected
,08-30 17:09:30.882   875   892 D BluetoothHeadset: Proxy object connected
,08-30 17:09:30.885  4048  4048 D HeadsetProfile: Bluetooth service connected
,08-30 17:09:31.193  3992  4040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:09:31.193  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:31.193  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:31.193  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:09:31.193  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:09:31.193  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:09:31.193  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:09:31.193  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:09:31.200  3992  4040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:09:31.204  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:09:31.205  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c65c86e added. We now have 8 listener(s)
,08-30 17:09:31.205  3992  4040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:09:31.211   875  1713 D WifiService: setWifiEnabled: false pid=3992, uid=10000
,08-30 17:09:31.212   875  1713 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 17:09:31.223  3992  4040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:31.225   875  2071 D WifiService: setWifiEnabled: true pid=3992, uid=10000
,08-30 17:09:31.225   875  2071 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 17:09:31.241   875  1317 D WifiConfigStore: Loading config and enabling all networks 
,08-30 17:09:31.257  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:09:31.257  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:31.257  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:31.257  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
08-30 17:09:31.257  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:09:31.257  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:09:31.257  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:09:31.257  3992  3992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:09:31.270  3992  3992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:09:31.273   875  1317 D WifiConfigStore: loaded 0 passpoint configs
,08-30 17:09:31.274   875  1317 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-30 17:09:31.275   875  1317 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-30 17:09:31.276   875  1317 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-30 17:09:31.277   875  1317 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-30 17:09:31.277   875  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-30 17:09:31.277   875  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 17:09:31.293   371   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 17:09:31.294   875  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 17:09:31.294   371   873 D CommandListener: Setting iface cfg
08-30 17:09:31.295   875  1316 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '180 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 180 Failed to set address (No such device)'
08-30 17:09:31.295   875  1316 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 17:09:31.349   875  1316 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 17:09:31.350   875  1316 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 17:09:31.351   875  1317 E native  : do suspend true
,08-30 17:09:31.397   875  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 17:09:32.248  3992  4040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:09:32.248  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:32.248  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:32.248  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:09:32.248  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:09:32.248  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:09:32.248  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:09:32.248  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:09:32.256  3992  4040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:09:32.268  3992  4040 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 17:09:32.271  3992  4040 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 17:09:32.276  3992  4040 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@137177b Bundle[{}]
,08-30 17:09:32.277  3992  4040 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 17:09:32.277  3992  4040 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 17:09:32.278  3992  4040 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 17:09:32.278  3992  4040 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-30 17:09:32.279  3992  4040 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-30 17:09:32.280  3992  4040 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 17:09:32.284  3992  4040 I System.out: Running OutgoingSocketThread
,08-30 17:09:32.288  3992  4282 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 441)
,08-30 17:09:32.290  3992  4282 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48746
,08-30 17:09:32.291  3992  4282 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 17:09:32.787   875  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 17:09:32.924   875  1317 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.25 rxSuccessRate=13.12 delta 1000 -> 994
,08-30 17:09:32.928   875  1317 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-30 17:09:32.928   875  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 17:09:32.952   875  1317 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 17:09:33.023   875  1317 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 17:09:33.028  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 17:09:33.288  3992  4040 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 442)
,08-30 17:09:33.288  3992  4040 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 442)
,08-30 17:09:33.299  3992  4040 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 447)
,08-30 17:09:33.302  3992  4040 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-30 17:09:33.302  3992  4040 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 448)
,08-30 17:09:33.309  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 17:09:33.309  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7c0b0f added. We now have 2 listener(s)
,08-30 17:09:33.311  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 17:09:33.312  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 17:09:33.312  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:09:33.312  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:09:33.312  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c9779c added. We now have 9 listener(s)
08-30 17:09:33.312  3992  4040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:09:33.313  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:09:33.317  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:09:33.324  3992  4040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:09:33.324  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:33.324  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:33.324  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:09:33.324  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:09:33.324  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:09:33.324  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:09:33.324  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:09:33.329  3992  4040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:09:33.330  3992  4040 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:09:33.330  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:09:33.331  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e29fd7a added. We now have 3 listener(s)
,08-30 17:09:33.332  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:33.335  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:09:33.336  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 17:09:33.337  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:09:33.337  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 17:09:33.338  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:09:33.338  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@978492b added. We now have 10 listener(s)
08-30 17:09:33.338  3992  4040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:09:33.339  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:09:33.339  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 17:09:33.339  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:09:33.340  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:33.340  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:33.340  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:09:33.340  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:09:33.341  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7c0b0f removed from the list
08-30 17:09:33.341  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:33.341  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c9779c removed from the list
,08-30 17:09:33.341  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:09:33.342  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:33.343  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:33.343  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:09:33.345  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:09:33.346  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:33.346  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:33.346  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c9779c not in the list
08-30 17:09:33.347  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:33.347  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:09:33.349  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:33.349  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:09:33.349  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:33.349  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@978492b removed from the list
08-30 17:09:33.349  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:33.349  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:09:33.349  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:33.349  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:09:33.349  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e29fd7a removed from the list
08-30 17:09:33.350  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:09:33.350  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c47188 added. We now have 2 listener(s)
,08-30 17:09:33.352  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 17:09:33.352  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:09:33.352  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:09:33.352  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:09:33.353  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56bf721 added. We now have 9 listener(s)
08-30 17:09:33.353  3992  4040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:09:33.353  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:09:33.356  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:09:33.360  3992  4040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:09:33.360  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:33.360  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:33.360  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:09:33.360  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:09:33.360  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:09:33.360  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:09:33.360  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:09:33.362  3992  4040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:09:33.362  3992  4040 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:09:33.363  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:09:33.363  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b04d07 added. We now have 3 listener(s)
,08-30 17:09:33.364  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:33.365  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 17:09:33.365  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:09:33.365  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 17:09:33.365  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:09:33.365  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f31e34 added. We now have 10 listener(s)
,08-30 17:09:33.365  3992  4040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:09:33.366  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:09:33.366  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:09:33.366  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:09:33.366  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:09:33.366  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 17:09:33.369  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:09:33.370  3992  4040 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 17:09:33.370  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 17:09:33.375  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 17:09:33.376  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 17:09:33.376  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 17:09:33.380  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 17:09:33.380  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 17:09:33.380  3992  4040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 17:09:33.381  3992  4040 D BluetoothAdapter: STATE_ON
,08-30 17:09:33.385  4228  4266 D BtGatt.GattService: registerClient() - UUID=4f24acce-228a-4305-b89a-30819b2824d7
,08-30 17:09:33.386  4228  4244 D BtGatt.GattService: onClientRegistered() - UUID=4f24acce-228a-4305-b89a-30819b2824d7, clientIf=5
08-30 17:09:33.387  3992  4166 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 17:09:33.388  4228  4256 D BtGatt.GattService: start scan with filters
,08-30 17:09:33.395  4228  4247 D BtGatt.ScanManager: handling starting scan
,08-30 17:09:33.395  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 17:09:33.395  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 17:09:33.395  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 17:09:33.396  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:09:33.397  4228  4247 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba4d30a
,08-30 17:09:33.400  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:09:33.400  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 17:09:33.400  3992  3992 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:09:33.402  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 17:09:33.403  4228  4244 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 17:09:33.403  4228  4244 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:09:33.404  4228  4247 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 17:09:33.417  3992  4040 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 17:09:33.417  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 17:09:33.417  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 17:09:33.418  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:33.418  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 17:09:33.418  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 17:09:33.418  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:09:33.418  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:09:33.418  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 17:09:33.418  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:09:33.419  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 17:09:33.420  3992  4040 D BluetoothAdapter: STATE_ON
08-30 17:09:33.421  4228  4256 D BtGatt.GattService: stopScan() - queue size =1
,08-30 17:09:33.422  4228  4239 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 17:09:33.422  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:09:33.423  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 17:09:33.423  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 17:09:33.423  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 17:09:33.424  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 17:09:33.426  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:09:33.426  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 17:09:33.426  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 17:09:33.427  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:09:33.427  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:09:33.429  3992  3992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:09:33.429  3992  3992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:09:33.430  3992  3992 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:09:33.432  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:09:33.432  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:09:33.432  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:09:33.432  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:33.433  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:33.433  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:09:33.433  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:09:33.433  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c47188 removed from the list
,08-30 17:09:33.433  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:33.433  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56bf721 removed from the list
08-30 17:09:33.433  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:09:33.433  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:33.434  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:33.434  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:09:33.436  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:09:33.436  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:33.436  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:33.436  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56bf721 not in the list
08-30 17:09:33.436  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:33.437  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:33.438  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:33.438  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:09:33.438  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:33.438  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f31e34 removed from the list
08-30 17:09:33.439  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:33.439  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:33.439  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:33.439  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 17:09:33.439  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b04d07 removed from the list
08-30 17:09:33.440  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:09:33.440  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fbde9a0 added. We now have 2 listener(s)
08-30 17:09:33.442  4228  4244 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 17:09:33.442  4228  4244 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:09:33.443  4228  4247 D BtGatt.ScanManager: Starting BLE batch scan
08-30 17:09:33.443  4228  4247 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 17:09:33.448  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 17:09:33.448  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:09:33.448  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:09:33.448  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:09:33.448  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cb6959 added. We now have 9 listener(s)
08-30 17:09:33.448  3992  4040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:09:33.449  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:09:33.453  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:09:33.457  3992  4040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:09:33.457  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:33.457  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:33.457  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:09:33.457  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:09:33.457  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:09:33.457  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:09:33.457  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:09:33.459  3992  4040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:09:33.459  3992  4040 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:09:33.460  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 17:09:33.461  4228  4244 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 17:09:33.461  4228  4244 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:09:33.461  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fbd5ff added. We now have 3 listener(s)
,08-30 17:09:33.463  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:33.465  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:33.467  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 17:09:33.467  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:09:33.467  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:09:33.467  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:09:33.467  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a7ffcc added. We now have 10 listener(s)
08-30 17:09:33.467  3992  4040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:09:33.468  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:09:33.469  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 17:09:33.469  4228  4244 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 17:09:33.469  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:09:33.469  4228  4244 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:09:33.469  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:09:33.469  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:09:33.469  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 17:09:33.473  3992  4040 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 17:09:33.473  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 17:09:33.476  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 17:09:33.477  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 17:09:33.477  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 17:09:33.477  4228  4244 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 17:09:33.477  4228  4244 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:09:33.477  4228  4247 D BtGatt.ScanManager: stopping BLe Batch
,08-30 17:09:33.479  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 17:09:33.479  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 17:09:33.480  3992  4040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 17:09:33.480  3992  4040 D BluetoothAdapter: STATE_ON
,08-30 17:09:33.482  4228  4238 D BtGatt.GattService: registerClient() - UUID=af891505-c49a-4ddd-aa85-895dab1a067d
,08-30 17:09:33.482  4228  4244 D BtGatt.GattService: onClientRegistered() - UUID=af891505-c49a-4ddd-aa85-895dab1a067d, clientIf=5
08-30 17:09:33.482  3992  4166 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 17:09:33.483  4228  4266 D BtGatt.GattService: start scan with filters
,08-30 17:09:33.484  4228  4244 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 17:09:33.484  4228  4244 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:09:33.484  4228  4247 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 17:09:33.485  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 17:09:33.486  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 17:09:33.486  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 17:09:33.486  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:09:33.488  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:09:33.488  3992  3992 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:09:33.488  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 17:09:33.490  4228  4244 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 17:09:33.490  4228  4244 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:09:33.491  4228  4247 D BtGatt.ScanManager: handling starting scan
,08-30 17:09:33.491  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:09:33.493  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:09:33.494  3992  4040 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 17:09:33.494  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:09:33.494  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:09:33.494  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:09:33.494  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:33.494  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:33.494  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 17:09:33.494  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:09:33.495  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fbde9a0 removed from the list
08-30 17:09:33.495  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:33.495  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cb6959 removed from the list
08-30 17:09:33.495  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:09:33.495  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:09:33.495  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:09:33.495  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 17:09:33.495  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:33.495  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:09:33.496  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:09:33.496  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:33.496  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 17:09:33.496  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cb6959 not in the list
,08-30 17:09:33.496  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:09:33.496  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:09:33.496  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 17:09:33.497  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:09:33.497  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 17:09:33.497  4228  4244 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 17:09:33.497  4228  4244 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:09:33.498  4228  4247 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 17:09:33.498  3992  4040 D BluetoothAdapter: STATE_ON
08-30 17:09:33.498  4228  4239 D BtGatt.GattService: stopScan() - queue size =1
,08-30 17:09:33.499  4228  4238 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 17:09:33.499  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:09:33.499  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 17:09:33.499  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 17:09:33.499  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 17:09:33.499  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 17:09:33.501  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:09:33.501  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 17:09:33.501  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 17:09:33.501  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:09:33.502  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:09:33.503  3992  3992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:09:33.503  3992  3992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:09:33.503  3992  3992 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:09:33.503  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 17:09:33.503  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:09:33.503  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:33.503  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a7ffcc removed from the list
08-30 17:09:33.503  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 17:09:33.503  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:33.503  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:33.503  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:09:33.504  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fbd5ff removed from the list
08-30 17:09:33.504  4228  4244 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 17:09:33.504  4228  4244 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:09:33.504  4228  4247 D BtGatt.ScanManager: Starting BLE batch scan
08-30 17:09:33.504  4228  4247 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 17:09:33.504  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:09:33.504  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23b4cb8 added. We now have 2 listener(s)
08-30 17:09:33.506  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 17:09:33.506  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:09:33.506  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:09:33.506  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:09:33.506  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2efea91 added. We now have 9 listener(s)
08-30 17:09:33.506  3992  4040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:09:33.507  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:09:33.510  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:09:33.513  3992  4040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:09:33.513  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:33.513  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:33.513  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:09:33.513  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:09:33.513  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:09:33.513  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:09:33.513  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:09:33.515  3992  4040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:09:33.516  3992  4040 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:09:33.517  4228  4244 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 17:09:33.517  4228  4244 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:09:33.517  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:09:33.516  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:09:33.517  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2085f7 added. We now have 3 listener(s)
08-30 17:09:33.518  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:33.521  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 17:09:33.521  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:09:33.521  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:09:33.521  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:09:33.521  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b47c64 added. We now have 10 listener(s)
08-30 17:09:33.521  3992  4040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:09:33.521  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:09:33.521  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:09:33.522  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:09:33.522  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:09:33.522  4228  4244 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 17:09:33.522  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 17:09:33.522  4228  4244 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:09:33.525  3992  4040 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 17:09:33.525  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 17:09:33.527   875   884 I art     : Background partial concurrent mark sweep GC freed 25658(1494KB) AllocSpace objects, 6(160KB) LOS objects, 33% free, 29MB/43MB, paused 1.463ms total 117.637ms
,08-30 17:09:33.527  4228  4244 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 17:09:33.527  4228  4244 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:09:33.528  4228  4247 D BtGatt.ScanManager: stopping BLe Batch
08-30 17:09:33.529  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 17:09:33.530  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 17:09:33.530  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 17:09:33.533  4228  4244 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 17:09:33.533  4228  4244 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:09:33.533  4228  4247 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 17:09:33.533  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 17:09:33.533  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 17:09:33.533  3992  4040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 17:09:33.534  3992  4040 D BluetoothAdapter: STATE_ON
,08-30 17:09:33.535  4228  4239 D BtGatt.GattService: registerClient() - UUID=3abce198-7ae0-4f6a-9701-9938bd0d91b0
08-30 17:09:33.536  4228  4244 D BtGatt.GattService: onClientRegistered() - UUID=3abce198-7ae0-4f6a-9701-9938bd0d91b0, clientIf=5
,08-30 17:09:33.536  3992  4003 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 17:09:33.536  4228  4266 D BtGatt.GattService: start scan with filters
08-30 17:09:33.537  4228  4244 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 17:09:33.537  4228  4244 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:09:33.538  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 17:09:33.538  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 17:09:33.538  4228  4247 D BtGatt.ScanManager: handling starting scan
08-30 17:09:33.538  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 17:09:33.538  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:09:33.540  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:09:33.541  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 17:09:33.541  3992  3992 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:09:33.542  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 17:09:33.543  4228  4244 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 17:09:33.543  4228  4244 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:09:33.543  4228  4247 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 17:09:33.545  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:09:33.546  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:09:33.546  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:09:33.546  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:33.546  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:33.546  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 17:09:33.546  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:09:33.546  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23b4cb8 removed from the list
08-30 17:09:33.546  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:33.546  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2efea91 removed from the list
08-30 17:09:33.546  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:09:33.546  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:09:33.547  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:09:33.547  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 17:09:33.547  4228  4244 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 17:09:33.547  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:33.547  4228  4244 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:09:33.547  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:09:33.547  4228  4247 D BtGatt.ScanManager: Starting BLE batch scan
08-30 17:09:33.547  4228  4247 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 17:09:33.548  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:09:33.548  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:33.548  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:33.548  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2efea91 not in the list
08-30 17:09:33.548  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:09:33.548  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:09:33.548  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 17:09:33.548  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:09:33.548  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 17:09:33.549  3992  4040 D BluetoothAdapter: STATE_ON
08-30 17:09:33.549  4228  4256 D BtGatt.GattService: stopScan() - queue size =1
08-30 17:09:33.549  4228  4239 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 17:09:33.550  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:09:33.550  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 17:09:33.550  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 17:09:33.550  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 17:09:33.550  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 17:09:33.551  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:09:33.551  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 17:09:33.551  3992  4040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 17:09:33.551  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:09:33.552  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:33.553  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:33.553  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:09:33.553  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 17:09:33.553  3992  3992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:09:33.553  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b47c64 removed from the list
08-30 17:09:33.553  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:33.553  3992  3992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:09:33.553  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:33.553  3992  3992 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:09:33.553  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:33.553  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 17:09:33.553  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2085f7 removed from the list
08-30 17:09:33.554  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:09:33.554  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16efad0 added. We now have 2 listener(s)
08-30 17:09:33.555  4228  4244 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 17:09:33.555  4228  4244 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:09:33.555  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 17:09:33.555  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:09:33.556  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:09:33.556  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:09:33.556  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98c5ac9 added. We now have 9 listener(s)
08-30 17:09:33.556  3992  4040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:09:33.556  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:09:33.558  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:09:33.559  4228  4244 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 17:09:33.559  4228  4244 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:09:33.561  3992  4040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:09:33.561  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:09:33.561  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:09:33.561  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:09:33.561  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:09:33.561  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:09:33.561  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:09:33.561  3992  4040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:09:33.562  3992  4040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:09:33.562  3992  4040 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:09:33.562  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:09:33.563  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23c3cef added. We now have 3 listener(s)
08-30 17:09:33.563  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:33.563  4228  4244 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 17:09:33.564  4228  4244 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:09:33.564  4228  4247 D BtGatt.ScanManager: stopping BLe Batch
08-30 17:09:33.564  3992  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:09:33.566  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 17:09:33.566  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:09:33.566  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:09:33.566  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:09:33.566  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e10f3fc added. We now have 10 listener(s)
08-30 17:09:33.566  3992  4040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:09:33.566  3992  4040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:09:33.566  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:09:33.566  3992  4040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:09:33.567  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:33.567  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:09:33.567  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:09:33.567  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:09:33.567  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16efad0 removed from the list
08-30 17:09:33.567  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:33.567  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98c5ac9 removed from the list
08-30 17:09:33.567  3992  4040 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:09:33.567  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:33.568  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:33.568  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:09:33.568  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:09:33.568  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:33.569  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:33.569  3992  4040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98c5ac9 not in the list
08-30 17:09:33.569  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:33.569  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:33.569  4228  4244 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 17:09:33.569  4228  4244 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:09:33.569  4228  4247 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 17:09:33.570  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:09:33.570  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:09:33.570  3992  4040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:09:33.570  3992  4040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e10f3fc removed from the list
08-30 17:09:33.570  3992  4040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:09:33.570  3992  4040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:09:33.570  3992  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:09:33.570  3992  4040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:09:33.570  3992  4040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23c3cef removed from the list
,08-30 17:09:33.571  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 17:09:33.571  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 17:09:33.571  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 17:09:33.571  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:09:33.571  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 17:09:33.571  3992  4040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 17:09:33.574  4228  4244 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 17:09:33.574  4228  4244 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:09:33.577  3992  4283 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 455, name: My test thread name)
,08-30 17:09:33.577  3992  4283 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 455, thread name: My test thread name)
08-30 17:09:33.577  3992  4283 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 455, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-30 17:09:33.579  3992  4284 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 457, name: My test thread name)
,08-30 17:09:33.579  3992  4284 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 457, thread name: My test thread name)
08-30 17:09:33.579  3992  4284 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 457, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-30 17:09:33.581  3992  4040 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-30 17:09:33.581  3992  4040 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-30 17:09:33.581  3992  4040 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-30 17:09:33.581  3992  4040 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-30 17:09:33.581  3992  4040 D com.test.thalitest.ThaliTestRunner: Total duration: 22923 ms
,08-30 17:09:33.582  3992  4040 I jxcore-log: *Native tests were executed*
08-30 17:09:33.582  3992  4040 I jxcore-log: 
,08-30 17:09:33.583  3992  4040 I jxcore-log: Total number of executed tests:  80
08-30 17:09:33.583  3992  4040 I jxcore-log: 
08-30 17:09:33.583  3992  4040 I jxcore-log: Number of passed tests:  80
08-30 17:09:33.583  3992  4040 I jxcore-log: 
08-30 17:09:33.583  3992  4040 I jxcore-log: Number of failed tests:  0
08-30 17:09:33.583  3992  4040 I jxcore-log: 
08-30 17:09:33.583  3992  4040 I jxcore-log: Number of ignored tests:  0
08-30 17:09:33.583  3992  4040 I jxcore-log: 
08-30 17:09:33.583  3992  4040 I jxcore-log: Total duration:  22923
08-30 17:09:33.583  3992  4040 I jxcore-log: 
08-30 17:09:33.584  3992  4040 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 17:09:33.584  3992  4040 I jxcore-log: 
,08-30 17:09:33.587  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:09:33.587  3992  4040 I jxcore-log: 
08-30 17:09:33.590  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:09:33.590  3992  4040 I jxcore-log: 
08-30 17:09:33.590  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:09:33.590  3992  4040 I jxcore-log: 
08-30 17:09:33.592  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:09:33.592  3992  4040 I jxcore-log: 
08-30 17:09:33.593  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:09:33.593  3992  4040 I jxcore-log: 
,08-30 17:09:33.594  3992  3992 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 17:09:33.595  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:09:33.595  3992  4040 I jxcore-log: 
08-30 17:09:33.597  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:09:33.597  3992  4040 I jxcore-log: 
,08-30 17:09:33.598  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 17:09:33.598  3992  4040 I jxcore-log: 
08-30 17:09:33.599  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 17:09:33.599  3992  4040 I jxcore-log: 
,08-30 17:09:33.599  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:09:33.599  3992  4040 I jxcore-log: 
,08-30 17:09:33.600  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:09:33.600  3992  4040 I jxcore-log: 
,08-30 17:09:33.601  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 17:09:33.601  3992  4040 I jxcore-log: 
,08-30 17:09:33.602  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 17:09:33.602  3992  4040 I jxcore-log: 
,08-30 17:09:33.603  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 17:09:33.603  3992  4040 I jxcore-log: 
08-30 17:09:33.603  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:09:33.603  3992  4040 I jxcore-log: 
,08-30 17:09:33.604  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:09:33.604  3992  4040 I jxcore-log: 
,08-30 17:09:33.604  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:09:33.604  3992  4040 I jxcore-log: 
08-30 17:09:33.605  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:09:33.605  3992  4040 I jxcore-log: 
,08-30 17:09:33.605  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:09:33.605  3992  4040 I jxcore-log: 
08-30 17:09:33.606  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:09:33.606  3992  4040 I jxcore-log: 
,08-30 17:09:33.607  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:09:33.607  3992  4040 I jxcore-log: 
08-30 17:09:33.607  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:09:33.607  3992  4040 I jxcore-log: 
08-30 17:09:33.608  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:09:33.608  3992  4040 I jxcore-log: 
,08-30 17:09:33.608  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:09:33.608  3992  4040 I jxcore-log: 
,08-30 17:09:33.609  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:09:33.609  3992  4040 I jxcore-log: 
08-30 17:09:33.609  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:09:33.609  3992  4040 I jxcore-log: 
,08-30 17:09:33.610  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:09:33.610  3992  4040 I jxcore-log: 
,08-30 17:09:33.611  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:09:33.611  3992  4040 I jxcore-log: 
,08-30 17:09:33.611  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:09:33.611  3992  4040 I jxcore-log: 
,08-30 17:09:33.791  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 17:09:33.897  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 17:09:33.899  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 17:09:33.905   875  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 17:09:33.921   875  1317 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 17:09:33.923   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 17:09:33.924   875  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 17:09:33.930  3992  3992 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 17:09:33.936  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 17:09:33.936  3992  4040 I jxcore-log: 
,08-30 17:09:33.945   875  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 17:09:33.963   371   873 D CommandListener: Setting iface cfg
,08-30 17:09:33.964   875  1317 D WifiStateMachine: Start Dhcp Watchdog 4
,08-30 17:09:33.979   875  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 17:09:34.003  3992  3992 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 17:09:34.004   875  4289 D DhcpClient: Receive thread started
,08-30 17:09:34.005  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 17:09:34.005  3992  4040 I jxcore-log: 
,08-30 17:09:34.052  3992  3992 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 17:09:34.055  3992  4040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 17:09:34.055  3992  4040 I jxcore-log: 
,08-30 17:09:34.090   875  1317 E native  : do suspend false
,08-30 17:09:34.105   875  1917 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 17:09:34.230   875  4289 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
,08-30 17:09:34.231   875  1917 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
,08-30 17:09:34.232   875  1917 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 17:09:34.246  4285  4285 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 17:09:34.251  4285  4285 D AndroidRuntime: CheckJNI is OFF
,08-30 17:09:34.294  4285  4285 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 17:09:34.342  4285  4285 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 17:09:34.364  4285  4285 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 17:09:34.378   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-30 17:09:34.379   875   888 I ActivityManager: Killing 3992:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-30 17:09:34.426   875  4289 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 17:09:34.428   875  1917 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
08-30 17:09:34.432   371   873 D CommandListener: Setting iface cfg
08-30 17:09:34.436   875  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 17:09:34.439   875  1317 E native  : do suspend true
,08-30 17:09:34.449   875  2006 D GraphicsStats: Buffer count: 2
,08-30 17:09:34.450   875  2224 I WindowState: WIN DEATH: Window{6a36452 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 17:09:34.451   875  1318 D WifiService: Client connection lost with reason: 4
08-30 17:09:34.454   875  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
08-30 17:09:34.460   875  1317 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 17:09:34.464   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 17:09:34.465   875  1319 D ConnectivityService: Adding iface wlan0 to network 103
,08-30 17:09:34.492   875  1319 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 17:09:34.492   875  1319 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 103
,08-30 17:09:34.493   875  1319 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 103
08-30 17:09:34.493   875  1319 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 103
,08-30 17:09:34.494   875  1319 D ConnectivityService: Setting Dns servers for network 103 to [/192.168.1.1]
,08-30 17:09:34.512   875   898 W PackageSettings: Skipping PackageSetting{cf09bef com.example.hello/10273} due to missing metadata
,08-30 17:09:34.546   875   888 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-30 17:09:34.546   875   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-30 17:09:34.547   875   888 E ActivityManager: Failure starting process com.test.thalitest
08-30 17:09:34.547   875   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-30 17:09:34.547   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-30 17:09:34.547   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-30 17:09:34.547   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-30 17:09:34.547   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-30 17:09:34.547   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-30 17:09:34.547   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-30 17:09:34.547   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-30 17:09:34.547   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-30 17:09:34.547   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-30 17:09:34.547   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-30 17:09:34.547   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-30 17:09:34.547   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-30 17:09:34.547   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-30 17:09:34.547   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-30 17:09:34.547   875   888 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:34.547   875   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:34.547   875   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:09:34.547   875   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-30 17:09:34.547   875   888 I ActivityManager:   Force finishing activity ActivityRecord{8de549f u0 com.test.thalitest/.MainActivity t2}
,08-30 17:09:34.550   875   898 I art     : Starting a blocking GC Explicit
,08-30 17:09:34.558   875  2006 W ActivityManager: Spurious death for ProcessRecord{416475f 0:com.test.thalitest/u0a0}, curProc for 3992: null
,08-30 17:09:34.559   875  1917 D DhcpClient: Scheduling renewal in 86399s
,08-30 17:09:34.565   875  1317 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 17:09:34.582   875  1319 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,08-30 17:09:34.586   875  1319 D ConnectivityService: scheduleUnvalidatedPrompt 103
,08-30 17:09:34.586   875  1319 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 103]
,08-30 17:09:34.586   875  1319 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 103]
08-30 17:09:34.586   875  1319 D ConnectivityService:    accepting network in place of null
08-30 17:09:34.586   875  1317 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-30 17:09:34.586   875  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 17:09:34.587   875  1319 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 17:09:34.610   371   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 17:09:34.611   875   898 I art     : Explicit concurrent mark sweep GC freed 28252(1802KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 29MB/43MB, paused 839us total 58.209ms
,08-30 17:09:34.632   875   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-30 17:09:34.632   371   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 17:09:34.634   875  1319 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 103] isDefaultNetwork=true
08-30 17:09:34.634   875  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 17:09:34.635  4285  4285 I art     : System.exit called, status: 0
08-30 17:09:34.635  4285  4285 I AndroidRuntime: VM exiting with result code 0.
08-30 17:09:34.636   875  1319 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 103]
08-30 17:09:34.638   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-30 17:09:34.655   875   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-30 17:09:34.671   875   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-30 17:09:34.675  1900  1900 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-30 17:09:34.676  4228  4228 D BluetoothMapAppObserver: onReceive
,08-30 17:09:34.677  4228  4228 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-30 17:09:34.678  1871  2313 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 17:09:34.682   875  1307 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 17:09:34.684  1721  1721 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 17:09:34.704  1900  4307 I Keyboard.Facilitator.DecoderInitializer: run()
,08-30 17:09:34.715  1969  1969 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-30 17:09:34.721  1721  1721 D SystemUpdateService: onCreate
,08-30 17:09:34.728  1721  1721 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 17:09:34.728   875  4288 D NetlinkSocketObserver: NeighborEvent{elapsedMs=210531, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 17:09:34.733  1900  4307 I Decoder : createOrResetDecoder
,08-30 17:09:34.751  1721  4310 I SystemUpdateService: active receiver: enabled
,08-30 17:09:34.758   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 17:09:34.765  1721  4310 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 17:09:34.772  1515  1515 I ConfigService: onCreate
,08-30 17:09:34.775  1721  4310 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-30 17:09:34.775  1721  4310 I SystemUpdateService: now status is 0 (complete)
08-30 17:09:34.775  1721  4310 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 17:09:34.776  1721  4310 I SystemUpdateService: file has been verified
,08-30 17:09:34.777  1721  1721 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 17:09:34.783  1515  4314 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-30 17:09:34.783  1515  4314 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:34.783  1515  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:34.783  1515  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:34.783  1515  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:34.783  1515  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:34.783  1515  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:34.783  1515  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:34.783  1515  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:34.783  1515  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:34.783  1515  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:34.783  1515  4314 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:34.783  1515  4314 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:34.783  1515  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:34.783  1515  4314 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:09:34.783  1515  4314 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-30 17:09:34.783  1515  4314 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-30 17:09:34.783  1515  4314 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:09:34.784  1515  4314 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-30 17:09:34.784  1515  4314 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:34.784  1515  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:34.784  1515  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:34.784  1515  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:34.784  1515  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:34.784  1515  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:34.784  1515  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:34.784  1515  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:34.784  1515  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:34.784  1515  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:34.784  1515  4314 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:34.784  1515  4314 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:34.784  1515  4314 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:34.784  1515  4314 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:09:34.784  1515  4314 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-30 17:09:34.784  1515  4314 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-30 17:09:34.784  1515  4314 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:09:34.786  1515  4314 W SQLiteOpenHelper: Opened config.db in read-only mode
08-30 17:09:34.790  1721  2472 I iu.UploadsManager: num queued entries: 0
08-30 17:09:34.790  1721  2472 E SQLiteLog: (3850) statement aborts at 61: [UPDATE media_record SET upload_state=? WHERE upload_account_id != -1 AND upload_state = 200] disk I/O error
08-30 17:09:34.792  1721  1721 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-30 17:09:34.793  1721  1721 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-30 17:09:34.794  3817  3817 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-30 17:09:34.799  1721  4313 I MDM     : [187] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-30 17:09:34.799  1721  4313 W BaseAppContext: Using Auth Proxy for data requests.
08-30 17:09:34.800  3817  3817 D SprintDMHelper: simOperator: 
08-30 17:09:34.800  3817  3817 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-30 17:09:34.808  1721  4313 V GoogleAuthProtoRequest: [187] a.<init>: mAccountName set to: thalitester@gmail.com
08-30 17:09:34.813  1990  2088 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-30 17:09:34.813  1721  4310 I SystemUpdateService: OTA package size = 12249756
,08-30 17:09:34.814  1721  2473 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/update.download.scheduler.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/update.download.scheduler.xml.bak
,08-30 17:09:34.815   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-30 17:09:34.816   875   887 E PackageManager: Failed to write settings, restoring backup
08-30 17:09:34.816   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-30 17:09:34.816   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-30 17:09:34.816   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-30 17:09:34.816   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-30 17:09:34.816   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-30 17:09:34.816   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:34.816   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:34.816   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:09:34.821   875   888 E DropBoxManagerService: Can't write: system_server_wtf
08-30 17:09:34.821   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:34.821   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:34.821   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:34.821   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:34.821   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:34.821   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:34.821   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:34.821   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-30 17:09:34.821   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-30 17:09:34.821   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-30 17:09:34.821   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 17:09:34.821   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 17:09:34.821   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:34.821   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:09:34.821   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 17:09:34.821   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:34.821   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:34.821   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:34.821   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:34.821   875   888 E DropBoxManagerService: 	... 13 more
,08-30 17:09:34.821  3570  3908 E SQLiteLog: (3850) statement aborts at 61: [UPDATE media_record SET upload_state=? WHERE upload_account_id != -1 AND upload_state = 200] disk I/O error
08-30 17:09:34.823  3771  4317 I BooksSync: Starting books sync for 61035162, extras: ade
08-30 17:09:34.825   875  2210 I ActivityManager: Start proc 4318:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-30 17:09:34.826  1990  2088 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-30 17:09:34.826  1990  2088 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1990
08-30 17:09:34.826  1990  2088 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 17:09:34.826  1990  2088 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 17:09:34.826  1990  2088 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 17:09:34.826  1990  2088 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 17:09:34.826  1990  2088 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 17:09:34.826  1990  2088 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 17:09:34.826  1990  2088 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-30 17:09:34.826  1990  2088 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-30 17:09:34.826  1990  2088 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 17:09:34.826  1990  2088 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 17:09:34.826  1990  2088 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:34.826  1990  2088 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:09:34.829  3662  3662 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-30 17:09:34.830   875  4323 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:34.830   875  4323 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:34.830   875  4323 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:34.830   875  4323 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:34.830   875  4323 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:34.830   875  4323 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:34.830   875  4323 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:34.830   875  4323 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:34.830   875  4323 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:34.830   875  4323 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:34.830   875  4323 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:34.830   875  4323 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
,08-30 17:09:34.830   875  4323 E DropBoxManagerService: 	... 5 more
08-30 17:09:34.830   875  1399 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 17:09:34.830  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 17:09:34.834  1990  2088 I Process : Sending signal. PID: 1990 SIG: 9
,08-30 17:09:34.849   875  1713 I ActivityManager: Start proc 4331:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-30 17:09:34.852  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 17:09:34.862  1900  4307 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-30 17:09:34.893  1721  2472 E AndroidRuntime: FATAL EXCEPTION: iu-sync-manager
08-30 17:09:34.893  1721  2472 E AndroidRuntime: Process: com.google.android.gms, PID: 1721
08-30 17:09:34.893  1721  2472 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 17:09:34.893  1721  2472 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 17:09:34.893  1721  2472 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 17:09:34.893  1721  2472 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 17:09:34.893  1721  2472 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 17:09:34.893  1721  2472 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1576)
08-30 17:09:34.893  1721  2472 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1522)
08-30 17:09:34.893  1721  2472 E AndroidRuntime: 	at com.google.android.libraries.social.autobackup.ae.a(SourceFile:403)
08-30 17:09:34.893  1721  2472 E AndroidRuntime: 	at com.google.android.libraries.social.autobackup.j.a(SourceFile:307)
08-30 17:09:34.893  1721  2472 E AndroidRuntime: 	at com.google.android.libraries.social.autobackup.j.b(SourceFile:43)
08-30 17:09:34.893  1721  2472 E AndroidRuntime: 	at com.google.android.libraries.social.autobackup.l.handleMessage(SourceFile:218)
08-30 17:09:34.893  1721  2472 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:34.893  1721  2472 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:34.893  1721  2472 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:09:34.895   875  4344 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:34.895   875  4344 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:34.895   875  4344 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:34.895   875  4344 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:34.895   875  4344 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:34.895   875  4344 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:34.895   875  4344 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:34.895   875  4344 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:34.895   875  4344 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:34.895   875  4344 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:34.895   875  4344 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:34.895   875  4344 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:34.895   875  4344 E DropBoxManagerService: 	... 5 more
,08-30 17:09:34.913  1721  4310 I SystemUpdateService: showing system update notification
,08-30 17:09:34.916  4331  4331 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-30 17:09:34.937  1900  4307 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-30 17:09:34.939  1900  4307 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-30 17:09:34.939  1900  4307 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-30 17:09:34.941  1900  4307 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-30 17:09:34.941  1900  4307 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-30 17:09:34.941  1900  4307 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-30 17:09:34.941  1900  4307 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-30 17:09:34.942  1900  4307 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-30 17:09:34.942  1900  4307 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-30 17:09:34.942  1900  4307 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-30 17:09:34.942  1900  4307 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-30 17:09:34.942  1900  4307 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-30 17:09:34.943  1900  4307 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-30 17:09:34.955  1721  2472 I Process : Sending signal. PID: 1721 SIG: 9
,08-30 17:09:34.968   875  4287 D NetworkMonitor/NetworkAgentInfo [WIFI () - 103]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-30 17:09:34.972   875  2209 D GraphicsStats: Buffer count: 1
,08-30 17:09:34.974   875  2210 I WindowState: WIN DEATH: Window{8f29910 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-30 17:09:34.984   875  2209 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1990) has died
,08-30 17:09:34.985   875  2209 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-30 17:09:35.061  4331  4331 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-30 17:09:35.066  1515  3004 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 17:09:35.066  1515  3004 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-30 17:09:35.066  1515  3004 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 17:09:35.066  1515  3004 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 17:09:35.067  4331  4350 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 17:09:35.067  4331  4350 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:35.067  4331  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:35.067  4331  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:35.067  4331  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:35.067  4331  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:35.067  4331  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:35.067  4331  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:35.067  4331  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:35.067  4331  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:35.067  4331  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:35.067  4331  4350 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:35.067  4331  4350 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:35.067  4331  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:35.067  4331  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:09:35.067  4331  4350 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 17:09:35.067  4331  4350 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 17:09:35.067  4331  4350 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 17:09:35.067  4331  4350 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 17:09:35.067  4331  4350 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:35.067  4331  4350 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:35.067  4331  4350 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:09:35.078   875  1999 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@78b51c9)
,08-30 17:09:35.081   875  1319 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 17:09:35.081   875  1319 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 17:09:35.087   875  2211 I ActivityManager: Process com.google.android.gms (pid 1721) has died
,08-30 17:09:35.087  3570  3908 E EsApplication: Uncaught exception in background thread Thread[iu-sync-manager,5,main]
08-30 17:09:35.087  3570  3908 E EsApplication: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 17:09:35.087  3570  3908 E EsApplication: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 17:09:35.087  3570  3908 E EsApplication: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 17:09:35.087  3570  3908 E EsApplication: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 17:09:35.087  3570  3908 E EsApplication: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 17:09:35.087  3570  3908 E EsApplication: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1576)
08-30 17:09:35.087  3570  3908 E EsApplication: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1522)
08-30 17:09:35.087  3570  3908 E EsApplication: ,	at ger.a(PG:321)
08-30 17:09:35.087  3570  3908 E EsApplication: 	at gdz.a(PG:307)
08-30 17:09:35.087  3570  3908 E EsApplication: 	at gdz.a(PG:4414)
08-30 17:09:35.087  3570  3908 E EsApplication: 	at geb.handleMessage(PG:1230)
08-30 17:09:35.087  3570  3908 E EsApplication: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:35.087  3570  3908 E EsApplication: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:35.087  3570  3908 E EsApplication: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:09:35.088  3771  4353 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 17:09:35.089  1515  1515 E ActivityThread: Service com.google.android.gms.auth.GetToken has leaked ServiceConnection com.google.android.gms.common.b@5549574 that was originally bound here
08-30 17:09:35.089  1515  1515 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.auth.GetToken has leaked ServiceConnection com.google.android.gms.common.b@5549574 that was originally bound here
08-30 17:09:35.089  1515  1515 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1092)
08-30 17:09:35.089  1515  1515 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:986)
08-30 17:09:35.089  1515  1515 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1303)
08-30 17:09:35.089  1515  1515 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1286)
08-30 17:09:35.089  1515  1515 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
08-30 17:09:35.089  1515  1515 E ActivityThread: 	at com.google.android.gms.common.stats.h.a(SourceFile:128)
08-30 17:09:35.089  1515  1515 E ActivityThread: 	at com.google.android.gms.common.stats.h.a(SourceFile:145)
,08-30 17:09:35.089  1515  1515 E ActivityThread: 	at com.google.android.gms.auth.firstparty.dataservice.x.a(SourceFile:572)
08-30 17:09:35.089  1515  1515 E ActivityThread: 	at com.google.android.gms.auth.firstparty.dataservice.x.a(SourceFile:213)
08-30 17:09:35.089  1515  1515 E ActivityThread: 	at com.google.android.gms.auth.n.a(SourceFile:295)
08-30 17:09:35.089  1515  1515 E ActivityThread: 	at com.google.android.gms.auth.n.a(SourceFile:202)
08-30 17:09:35.089  1515  1515 E ActivityThread: 	at com.google.android.b.b.onTransact(SourceFile:137)
08-30 17:09:35.089  1515  1515 E ActivityThread: 	at android.os.Binder.execTransact(Binder.java:453)
,08-30 17:09:35.089   875  2211 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.update.SystemUpdateService in 1000ms
,08-30 17:09:35.090   875  2211 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackAsyncService in 11000ms
,08-30 17:09:35.091   875  2211 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.mdm.services.SitrepService in 10999ms
,08-30 17:09:35.091   875  2211 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20999ms
08-30 17:09:35.091   875  2211 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackService in 30998ms
,08-30 17:09:35.109  4331  4355 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-30 17:09:35.111   875  2071 I ActivityManager: Start proc 4356:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-30 17:09:35.067  4331  4350 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-30 17:09:35.067  4331  4350 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:35.067  4331  4350 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:35.067  4331  4350 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:35.067  4331  4350 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:35.067  4331  4350 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:35.067  4331  4350 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:35.067  4331  4350 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:35.067  4331  4350 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:35.067  4331  4350 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:35.067  4331  4350 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:35.067  4331  4350 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:35.067  4331  4350 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:35.067  4331  4350 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:35.067  4331  4350 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:09:35.067  4331  4350 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 17:09:35.067  4331  4350 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 17:09:35.067  4331  4350 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 17:09:35.067  4331  4350 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 17:09:35.067  4331  4350 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:35.067  4331  4350 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:35.067  4331  4350 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:09:35.135  3570  3570 E AndroidRuntime: FATAL EXCEPTION: iu-sync-manager
08-30 17:09:35.135  3570  3570 E AndroidRuntime: Process: com.google.android.apps.plus, PID: 3570
08-30 17:09:35.135  3570  3570 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 17:09:35.135  3570  3570 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 17:09:35.135  3570  3570 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 17:09:35.135  3570  3570 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 17:09:35.135  3570  3570 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 17:09:35.135  3570  3570 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1576)
08-30 17:09:35.135  3570  3570 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1522)
08-30 17:09:35.135  3570  3570 E AndroidRuntime: 	at ger.a(PG:321)
08-30 17:09:35.135  3570  3570 E AndroidRuntime: 	at gdz.a(PG:307)
08-30 17:09:35.135  3570  3570 E AndroidRuntime: 	at gdz.a(PG:4414)
08-30 17:09:35.135  3570  3570 E AndroidRuntime: 	at geb.handleMessage(PG:1230)
08-30 17:09:35.135  3570  3570 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:35.135  3570  3570 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:35.135  3570  3570 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:09:35.137   875  4369 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:35.137   875  4369 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:35.137   875  4369 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:35.137   875  4369 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:35.137   875  4369 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:35.137   875  4369 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:35.137   875  4369 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:35.137   875  4369 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:35.137   875  4369 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:35.137   875  4369 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:35.137   875  4369 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:35.137   875  4369 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:35.137   875  4369 E DropBoxManagerService: 	... 5 more
,08-30 17:09:35.137  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 17:09:35.138  3570  3570 I Process : Sending signal. PID: 3570 SIG: 9
08-30 17:09:35.139  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 17:09:35.160  1515  2007 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 17:09:35.160  1515  2007 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 17:09:35.160  1515  2007 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 17:09:35.161  1515  2007 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 17:09:35.183  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 17:09:35.185  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 17:09:35.192  4356  4356 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-30 17:09:35.197  1515  3004 W Auth    : [GetToken] RuntimeException thrown during GetToken!
08-30 17:09:35.197  1515  3004 W Auth    : java.lang.IllegalArgumentException: Service not registered: com.google.android.gms.common.b@5549574
08-30 17:09:35.197  1515  3004 W Auth    : 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1044)
08-30 17:09:35.197  1515  3004 W Auth    : 	at android.app.ContextImpl.unbindService(ContextImpl.java:1337)
08-30 17:09:35.197  1515  3004 W Auth    : 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
08-30 17:09:35.197  1515  3004 W Auth    : 	at com.google.android.gms.common.stats.h.a(SourceFile:153)
08-30 17:09:35.197  1515  3004 W Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(SourceFile:585)
08-30 17:09:35.197  1515  3004 W Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(SourceFile:213)
08-30 17:09:35.197  1515  3004 W Auth    : 	at com.google.android.gms.auth.n.a(SourceFile:295)
08-30 17:09:35.197  1515  3004 W Auth    : 	at com.google.android.gms.auth.n.a(SourceFile:202)
08-30 17:09:35.197  1515  3004 W Auth    : 	at com.google.android.b.b.onTransact(SourceFile:137)
08-30 17:09:35.197  1515  3004 W Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,08-30 17:09:35.208  1515  2007 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 17:09:35.208  1515  2007 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-30 17:09:35.208  1515  2007 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 17:09:35.208  1515  2007 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 17:09:35.224  3771  4353 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 17:09:35.225  3771  4317 E BooksSync: Soft error
08-30 17:09:35.225  3771  4317 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 17:09:35.225  3771  4317 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 17:09:35.225  3771  4317 E BooksSync: Sync error
08-30 17:09:35.225  3771  4317 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 17:09:35.225  3771  4317 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 17:09:35.225  3771  4317 I BooksSync: Finished books sync
,08-30 17:09:35.226  1515  4368 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-30 17:09:35.226  1515  4368 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:35.226  1515  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:35.226  1515  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:35.226  1515  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:35.226  1515  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:35.226  1515  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:35.226  1515  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:35.226  1515  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:35.226  1515  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:35.226  1515  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:35.226  1515  4368 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:35.226  1515  4368 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:35.226  1515  4368 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:35.226  1515  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:35.226  1515  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:09:35.226  1515  4368 E SQLiteDatabase: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:100)
08-30 17:09:35.226  1515  4368 E SQLiteDatabase: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-30 17:09:35.226  1515  4368 E SQLiteDatabase: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-30 17:09:35.226  1515  4368 E SQLiteDatabase: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-30 17:09:35.226  1515  4368 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 17:09:35.226  1515  4368 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 17:09:35.226  1515  4368 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-30 17:09:35.226  1515  4368 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
08-30 17:09:35.226  1515  4368 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:35.226  1515  4368 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:35.226  1515  4368 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:35.226  1515  4368 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:35.226  1515  4368 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:35.226  1515  4368 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:35.226  1515  4368 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:35.226  1515  4368 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:35.226  1515  4368 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:35.226  1515  4368 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:35.226  1515  4368 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:35.226  1515  4368 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:35.226  1515  4368 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:35.226  1515  4368 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:35.226  1515  4368 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:09:35.226  1515  4368 E SQLiteOpenHelper: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:100)
08-30 17:09:35.226  1515  4368 E SQLiteOpenHelper: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-30 17:09:35.226  1515  4368 E SQLiteOpenHelper: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-30 17:09:35.226  1515  4368 E SQLiteOpenHelper: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-30 17:09:35.226  1515  4368 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 17:09:35.226  1515  4368 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 17:09:35.226  1515  4368 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-30 17:09:35.229  1515  4368 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,08-30 17:09:35.229  1515  4368 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,08-30 17:09:35.229   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 195434, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,08-30 17:09:35.230  1515  4368 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
08-30 17:09:35.230  1515  4368 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-30 17:09:35.230  1515  4368 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-30 17:09:35.230  1515  4368 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-30 17:09:35.230  1515  4368 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-30 17:09:35.230  1515  4368 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-30 17:09:35.230  1515  4368 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-30 17:09:35.230  1515  4368 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-30 17:09:35.230  1515  4368 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-30 17:09:35.230  1515  4368 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-30 17:09:35.230  1515  4368 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-30 17:09:35.230  1515  4368 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-30 17:09:35.230  1515  4368 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 17:09:35.230  1515  4368 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 17:09:35.230  1515  4368 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,08-30 17:09:35.236  1515  1515 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-30 17:09:35.237   875   887 W AtomicFile: Couldn't rename file /data/system/sync/pending.xml to backup file /data/system/sync/pending.xml.bak
,08-30 17:09:35.238  1515  1515 D AndroidRuntime: Shutting down VM
,08-30 17:09:35.239  1515  1515 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:35.239  1515  1515 E AndroidRuntime: Process: com.google.process.gapps, PID: 1515
08-30 17:09:35.239  1515  1515 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 17:09:35.239  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-30 17:09:35.239  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-30 17:09:35.239  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-30 17:09:35.239  1515  1515 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:35.239  1515  1515 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:35.239  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:35.239  1515  1515 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:35.239  1515  1515 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:35.239  1515  1515 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:35.239  1515  1515 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 17:09:35.239  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 17:09:35.239  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 17:09:35.239  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 17:09:35.239  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 17:09:35.239  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 17:09:35.239  1515  1515 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-30 17:09:35.239  1515  1515 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-30 17:09:35.239  1515  1515 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-30 17:09:35.239  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-30 17:09:35.239  1515  1515 E AndroidRuntime: 	... 8 more
,08-30 17:09:35.241   875   887 W SyncManager: Error writing pending operations
08-30 17:09:35.241   875   887 W SyncManager: java.io.IOException: Couldn't create directory /data/system/sync/pending.xml
08-30 17:09:35.241   875   887 W SyncManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-30 17:09:35.241   875   887 W SyncManager: 	at com.android.server.content.SyncStorageEngine.writePendingOperationsLocked(SyncStorageEngine.java:2629)
08-30 17:09:35.241   875   887 W SyncManager: 	at com.android.server.content.SyncStorageEngine.appendPendingOperationLocked(SyncStorageEngine.java:2678)
08-30 17:09:35.241   875   887 W SyncManager: 	at com.android.server.content.SyncStorageEngine.insertIntoPending(SyncStorageEngine.java:1121)
08-30 17:09:35.241   875   887 W SyncManager: 	at com.android.server.content.SyncQueue.add(SyncQueue.java:145)
08-30 17:09:35.241   875   887 W SyncManager: 	at com.android.server.content.SyncQueue.add(SyncQueue.java:109)
08-30 17:09:35.241   875   887 W SyncManager: 	at com.android.server.content.SyncManager.scheduleSyncOperation(SyncManager.java:1112)
08-30 17:09:35.241   875   887 W SyncManager: 	at com.android.server.content.SyncManager.maybeRescheduleSync(SyncManager.java:1216)
08-30 17:09:35.241   875   887 W SyncManager: 	at com.android.server.content.SyncManager$SyncHandler.runSyncFinishedOrCanceledH(SyncManager.java:3072)
08-30 17:09:35.241   875   887 W SyncManager: 	at com.android.server.content.SyncManager$SyncHandler.handleMessage(SyncManager.java:2241)
08-30 17:09:35.241   875   887 W SyncManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:35.241   875   887 W SyncManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:35.241   875   887 W SyncManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:09:35.246   875  4374 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:35.246   875  4374 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop134.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:35.246   875  4374 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:35.246   875  4374 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:35.246   875  4374 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:35.246   875  4374 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:35.246   875  4374 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:35.246   875  4374 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:35.246   875  4374 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:35.246   875  4374 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:35.246   875  4374 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:35.246   875  4374 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:35.246   875  4374 E DropBoxManagerService: 	... 5 more
,08-30 17:09:35.252  1515  1515 I Process : Sending signal. PID: 1515 SIG: 9
,08-30 17:09:35.254   875  4287 D NetworkMonitor/NetworkAgentInfo [WIFI () - 103]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 15:09:35 GMT], X-Android-Received-Millis=[1472569775253], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472569775168]}
,08-30 17:09:35.255   875  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-30 17:09:35.255   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] validation  passed
,08-30 17:09:35.255   875  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,08-30 17:09:35.255   875  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 17:09:35.261  2290  4316 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 17:09:35.265   875   886 I ActivityManager: Killing 3717:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-30 17:09:35.309  4331  4350 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-30 17:09:35.314  4331  4355 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 17:09:35.314  4331  4355 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:35.314  4331  4355 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:35.314  4331  4355 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:35.314  4331  4355 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:35.314  4331  4355 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:35.314  4331  4355 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:35.314  4331  4355 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:35.314  4331  4355 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:35.314  4331  4355 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:35.314  4331  4355 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:35.314  4331  4355 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:35.314  4331  4355 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:35.314  4331  4355 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:35.314  4331  4355 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:35.314  4331  4355 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 17:09:35.314  4331  4355 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 17:09:35.314  4331  4355 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 17:09:35.314  4331  4355 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 17:09:35.314  4331  4355 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 17:09:35.314  4331  4355 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 17:09:35.314  4331  4355 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 17:09:35.314  4331  4355 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:35.314  4331  4355 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:35.314  4331  4355 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:09:35.314  4331  4355 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-30 17:09:35.314  4331  4355 E AndroidRuntime: Process: android.process.acore, PID: 4331
08-30 17:09:35.314  4331  4355 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:35.314  4331  4355 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:35.314  4331  4355 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:35.314  4331  4355 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:35.314  4331  4355 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:35.314  4331  4355 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:35.314  4331  4355 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:35.314  4331  4355 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:35.314  4331  4355 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:35.314  4331  4355 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:35.314  4331  4355 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:35.314  4331  4355 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:35.314  4331  4355 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:35.314  4331  4355 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:35.314  4331  4355 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 17:09:35.314  4331  4355 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 17:09:35.314  4331  4355 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 17:09:35.314  4331  4355 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 17:09:35.314  4331  4355 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 17:09:35.314  4331  4355 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 17:09:35.314  4331  4355 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 17:09:35.314  4331  4355 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:35.314  4331  4355 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:35.314  4331  4355 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:09:35.315  4331  4350 I Process : Sending signal. PID: 4331 SIG: 9
,08-30 17:09:35.335   875  1318 D WifiService: Client connection lost with reason: 4
,08-30 17:09:35.348   875  1405 I ActivityManager: Process com.google.process.gapps (pid 1515) has died
,08-30 17:09:35.348   875  1405 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 40741ms
,08-30 17:09:35.348   875  1405 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 50741ms
08-30 17:09:35.349   875  1405 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerIntentService in 60741ms
,08-30 17:09:35.349   875  1405 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 60741ms
,08-30 17:09:35.354   875  4378 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:35.354   875  4378 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop136.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:35.354   875  4378 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:35.354   875  4378 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:35.354   875  4378 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:35.354   875  4378 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:35.354   875  4378 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:35.354   875  4378 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:35.354   875  4378 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:35.354   875  4378 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:35.354   875  4378 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:35.354   875  4378 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:35.354   875  4378 E DropBoxManagerService: 	... 5 more
,08-30 17:09:35.365   875   888 I ActivityManager: Start proc 4379:com.google.android.gms/u0a11 for broadcast com.google.android.gms/.photos.autobackup.PhotosAppUninstalledReceiver
,08-30 17:09:35.366   875  1713 I ActivityManager: Process com.google.android.apps.plus (pid 3570) has died
,08-30 17:09:35.381   875  2006 I ActivityManager: Start proc 4391:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-30 17:09:35.381   875  2055 I ActivityManager: Process android.process.acore (pid 4331) has died
,08-30 17:09:35.381   875  2055 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 70708ms
,08-30 17:09:35.422  4379  4379 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-30 17:09:35.437  4391  4391 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-30 17:09:35.446  4379  4379 I MultiDex: VM with version 2.1.0 has multidex support
,08-30 17:09:35.446  4379  4379 I MultiDex: install
08-30 17:09:35.446  4379  4379 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 17:09:35.455  4391  4391 I MultiDex: VM with version 2.1.0 has multidex support
08-30 17:09:35.455  4391  4391 I MultiDex: install
08-30 17:09:35.456  4391  4391 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 17:09:35.462  4391  4391 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-30 17:09:35.484  4391  4391 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-30 17:09:35.487  4391  4391 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:35.487  4391  4391 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:35.487  4391  4391 D AndroidRuntime: Shutting down VM
,08-30 17:09:35.494  4391  4391 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:35.494  4391  4391 E AndroidRuntime: Process: com.google.process.gapps, PID: 4391
08-30 17:09:35.494  4391  4391 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	at android.app.ActivityTh,read.installProvider(ActivityThread.java:5153)
08-30 17:09:35.494  4391  4391 E AndroidRuntime: 	... 10 more
08-30 17:09:35.502  4391  4391 I Process : Sending signal. PID: 4391 SIG: 9
08-30 17:09:35.506   875  4403 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:35.506   875  4403 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:35.506   875  4403 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:35.506   875  4403 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:35.506   875  4403 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:35.506   875  4403 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:35.506   875  4403 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:35.506   875  4403 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:35.506   875  4403 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:35.506   875  4403 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:35.506   875  4403 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:35.506   875  4403 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:35.506   875  4403 E DropBoxManagerService: 	... 5 more
,08-30 17:09:35.569   875  2211 I ActivityManager: Process com.google.process.gapps (pid 4391) has died
,08-30 17:09:35.570   875  2211 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{b55965e u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
08-30 17:09:35.571   875  2211 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{8c42c35 u0 com.google.android.gms/.config.ConfigService}
,08-30 17:09:35.573   875  2211 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{2653ba2 u0 com.google.android.gms/.gcm.GcmService}
,08-30 17:09:35.597   875  2211 I ActivityManager: Start proc 4407:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,08-30 17:09:35.709  4407  4407 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-30 17:09:35.729  4407  4407 I MultiDex: VM with version 2.1.0 has multidex support
,08-30 17:09:35.729  4407  4407 I MultiDex: install
08-30 17:09:35.729  4407  4407 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 17:09:35.738  4407  4407 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-30 17:09:35.746  4407  4407 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-30 17:09:35.749  4407  4407 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:35.749  4407  4407 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:35.750  4407  4407 D AndroidRuntime: Shutting down VM
,08-30 17:09:35.753  4407  4407 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:35.753  4407  4407 E AndroidRuntime: Process: com.google.process.gapps, PID: 4407
08-30 17:09:35.753  4407  4407 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	at android.app.ActivityTh,read.installProvider(ActivityThread.java:5153)
08-30 17:09:35.753  4407  4407 E AndroidRuntime: 	... 10 more
08-30 17:09:35.756   875  2071 W ActivityManager: Process com.google.android.gms has crashed too many times: killing!
08-30 17:09:35.757   875  2071 I ActivityManager: Killing 4407:com.google.process.gapps/u0a11 (adj 0): crash
08-30 17:09:35.761   875  4419 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:35.761   875  4419 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:35.761   875  4419 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:35.761   875  4419 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:35.761   875  4419 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:35.761   875  4419 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:35.761   875  4419 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:35.761   875  4419 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:35.761   875  4419 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:35.761   875  4419 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:35.761   875  4419 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:35.761   875  4419 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:35.761   875  4419 E DropBoxManagerService: 	... 5 more
,08-30 17:09:35.801   875  2224 W ActivityManager: Unable to launch app com.google.android.gsf/10011 for provider com.google.android.gsf.gservices: launching app became null
,08-30 17:09:35.802  4379  4379 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
,08-30 17:09:35.835   875  2071 I ActivityManager: Start proc 4420:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,08-30 17:09:35.838   875  2071 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 17:09:35.879   875   888 I ActivityManager: Start proc 4432:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 17:09:35.880   875  1999 W ActivityManager: Spurious death for ProcessRecord{1c4435c 4420:com.google.process.gapps/u0a11}, curProc for 4407: null
,08-30 17:09:35.914  4379  4379 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-30 17:09:35.928  4420  4420 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-30 17:09:35.950  4420  4420 I MultiDex: VM with version 2.1.0 has multidex support
,08-30 17:09:35.950  4420  4420 I MultiDex: install
,08-30 17:09:35.950  4420  4420 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 17:09:35.951  4432  4432 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:35.951  4432  4432 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:09:35.952  4432  4432 D AndroidRuntime: Shutting down VM
,08-30 17:09:35.961  4432  4432 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:35.961  4432  4432 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4432
08-30 17:09:35.961  4432  4432 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:35.961  4432  4432 E AndroidRuntime: 	... 10 more
08-30 17:09:35.963   875  2006 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 17:09:35.964  4432  4432 I Process : Sending signal. PID: 4432 SIG: 9
08-30 17:09:35.965  4379  4379 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-30 17:09:35.970   875  4444 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:35.970   875  4444 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:35.970   875  4444 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:35.970   875  4444 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:35.970   875  4444 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:35.970   875  4444 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:35.970   875  4444 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:35.970   875  4444 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:35.970   875  4444 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:35.970   875  4444 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:35.970   875  4444 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:35.970   875  4444 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:35.970   875  4444 E DropBoxManagerService: 	... 5 more
08-30 17:09:35.971  4420  4420 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-30 17:09:35.975  4420  4420 I GservicesProvider: Gservices pushing to system: true; secure/global: true
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:35.977  4420  4420 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:35.977  4420  4420 D AndroidRuntime: Shutting down VM
08-30 17:09:35.978  4420  4420 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:35.978  4420  4420 E AndroidRuntime: Process: com.google.process.gapps, PID: 4420
08-30 17:09:35.978  4420  4420 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:35.978  4420  4420 E AndroidRuntime: 	... 10 more
08-30 17:09:35.980  4420  4420 I Process : Sending signal. PID: 4420 SIG: 9
08-30 17:09:35.981   875  4445 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:35.981   875  4445 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:35.981   875  4445 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:35.981   875  4445 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:35.981   875  4445 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:35.981   875  4445 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:35.981   875  4445 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:35.981   875  4445 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:35.981   875  4445 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:35.981   875  4445 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:35.981   875  4445 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:35.981   875  4445 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:35.981   875  4445 E DropBoxManagerService: 	... 5 more
08-30 17:09:35.983  1900  4307 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-30 17:09:35.983  1900  4307 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-30 17:09:35.995   875   885 I ActivityManager: Start proc 4446:android.process.acore/u0a5 for content provider com.android.providers.contacts/.ContactsProvider2
,08-30 17:09:36.020   279   279 E lowmemorykiller: Error writing /proc/4420/oom_score_adj; errno=22
08-30 17:09:36.020   875  2071 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
08-30 17:09:36.021   875  2209 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4432) has died
08-30 17:09:36.023   875  2209 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-30 17:09:36.034  4446  4446 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-30 17:09:36.046   875   888 I ActivityManager: Start proc 4458:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 17:09:36.046   875  2006 I ActivityManager: Process com.google.process.gapps (pid 4420) has died
,08-30 17:09:36.047   875  2055 W ActivityManager: Unable to launch app com.google.android.gsf/10011 for provider com.google.android.gsf.gservices: launching app became null
,08-30 17:09:36.047  4379  4379 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
,08-30 17:09:36.059  4379  4379 D SystemUpdateService: onCreate
,08-30 17:09:36.068   875  2006 I ActivityManager: Start proc 4472:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,08-30 17:09:36.073  4379  4463 W NativeLibraryUtils: Failed to open lock file
08-30 17:09:36.073  4379  4463 W NativeLibraryUtils: java.io.FileNotFoundException: /data/user/0/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
08-30 17:09:36.073  4379  4463 W NativeLibraryUtils: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:36.073  4379  4463 W NativeLibraryUtils: 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
08-30 17:09:36.073  4379  4463 W NativeLibraryUtils: 	at com.google.android.gms.common.util.ay.b(SourceFile:325)
08-30 17:09:36.073  4379  4463 W NativeLibraryUtils: 	at com.google.android.gms.common.app.a.run(SourceFile:171)
08-30 17:09:36.073  4379  4463 W NativeLibraryUtils: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:36.073  4379  4463 W NativeLibraryUtils: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:36.073  4379  4463 W NativeLibraryUtils: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:36.073  4379  4463 W NativeLibraryUtils: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:36.073  4379  4463 W NativeLibraryUtils: 	... 3 more
,08-30 17:09:36.081  4379  4379 D SystemUpdateService: onStartCommand: intent: null
,08-30 17:09:36.103  4446  4446 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-30 17:09:36.106  4446  4485 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 17:09:36.106  4446  4485 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.106  4446  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:36.106  4446  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:36.106  4446  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:36.106  4446  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:36.106  4446  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:36.106  4446  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:36.106  4446  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:36.106  4446  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:36.106  4446  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:36.106  4446  4485 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:36.106  4446  4485 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:36.106  4446  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:36.106  4446  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:09:36.106  4446  4485 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 17:09:36.106  4446  4485 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 17:09:36.106  4446  4485 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 17:09:36.106  4446  4485 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 17:09:36.106  4446  4485 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.106  4446  4485 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.106  4446  4485 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:09:36.106  4446  4485 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-30 17:09:36.106  4446  4485 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.106  4446  4485 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:36.106  4446  4485 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:36.106  4446  4485 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:36.106  4446  4485 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:36.106  4446  4485 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:36.106  4446  4485 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:36.106  4446  4485 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:36.106  4446  4485 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:36.106  4446  4485 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:36.106  4446  4485 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:36.106  4446  4485 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:36.106  4446  4485 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:36.106  4446  4485 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:09:36.106  4446  4485 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 17:09:36.106  4446  4485 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 17:09:36.106  4446  4485 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 17:09:36.106  4446  4485 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 17:09:36.106  4446  4485 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.106  4446  4485 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.106  4446  4485 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:09:36.127  4472  4472 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-30 17:09:36.130  4458  4458 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:36.130  4458  4458 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:09:36.131  4458  4458 D AndroidRuntime: Shutting down VM
,08-30 17:09:36.138  4458  4458 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:36.138  4458  4458 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4458
08-30 17:09:36.138  4458  4458 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:36.138  4458  4458 E AndroidRuntime: 	... 10 more
08-30 17:09:36.142   875   886 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 17:09:36.143  4458  4458 I Process : Sending signal. PID: 4458 SIG: 9
,08-30 17:09:36.145   875  4488 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:36.145   875  4488 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:36.145   875  4488 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:36.145   875  4488 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:36.145   875  4488 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:36.145   875  4488 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:36.145   875  4488 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:36.145   875  4488 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:36.145   875  4488 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:36.145   875  4488 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:36.145   875  4488 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:36.145   875  4488 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:36.145   875  4488 E DropBoxManagerService: 	... 5 more
08-30 17:09:36.147  4472  4472 I MultiDex: VM with version 2.1.0 has multidex support
,08-30 17:09:36.147  4472  4472 I MultiDex: install
08-30 17:09:36.147  4472  4472 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 17:09:36.152  4472  4472 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-30 17:09:36.156  4472  4472 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-30 17:09:36.158  4472  4472 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:36.158  4472  4472 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:36.159  4472  4472 D AndroidRuntime: Shutting down VM
08-30 17:09:36.159  4472  4472 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:36.159  4472  4472 E AndroidRuntime: Process: com.google.process.gapps, PID: 4472
08-30 17:09:36.159  4472  4472 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvid,er: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:36.159  4472  4472 E AndroidRuntime: 	... 10 more
,08-30 17:09:36.161   875  2055 W ActivityManager: Process com.google.android.gms has crashed too many times: killing!
,08-30 17:09:36.162   875  2055 I ActivityManager: Killing 4472:com.google.process.gapps/u0a11 (adj 0): crash
,08-30 17:09:36.162   875  4489 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:36.162   875  4489 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:36.162   875  4489 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:36.162   875  4489 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:36.162   875  4489 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:36.162   875  4489 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:36.162   875  4489 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:36.162   875  4489 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:36.162   875  4489 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:36.162   875  4489 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:36.162   875  4489 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:36.162   875  4489 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:36.162   875  4489 E DropBoxManagerService: 	... 5 more
,08-30 17:09:36.183  4446  4485 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-30 17:09:36.187  4446  4485 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
08-30 17:09:36.187  4446  4485 E AndroidRuntime: Process: android.process.acore, PID: 4446
08-30 17:09:36.187  4446  4485 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-30 17:09:36.187  4446  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 17:09:36.187  4446  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 17:09:36.187  4446  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 17:09:36.187  4446  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 17:09:36.187  4446  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1676)
08-30 17:09:36.187  4446  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1605)
08-30 17:09:36.187  4446  4485 E AndroidRuntime: 	at com.android.providers.contacts.ContactsDatabaseHelper.onOpen(ContactsDatabaseHelper.java:1084)
08-30 17:09:36.187  4446  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:266)
08-30 17:09:36.187  4446  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:09:36.187  4446  4485 E AndroidRuntime: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 17:09:36.187  4446  4485 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 17:09:36.187  4446  4485 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 17:09:36.187  4446  4485 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 17:09:36.187  4446  4485 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.187  4446  4485 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.187  4446  4485 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:09:36.211   875  1703 W ActivityManager: Unable to launch app com.google.android.gsf/10011 for provider com.google.android.gsf.gservices: launching app became null
08-30 17:09:36.211  4379  4379 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
,08-30 17:09:36.229   875  2055 I ActivityManager: Start proc 4490:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,08-30 17:09:36.231   875   885 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4458) has died
,08-30 17:09:36.235   875   885 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 17:09:36.247   875  2210 W ActivityManager: Spurious death for ProcessRecord{1c4435c 4490:com.google.process.gapps/u0a11}, curProc for 4472: null
,08-30 17:09:36.263   875   888 I ActivityManager: Start proc 4502:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 17:09:36.267   875  4507 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:36.267   875  4507 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:36.267   875  4507 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:36.267   875  4507 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:36.267   875  4507 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:36.267   875  4507 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:36.267   875  4507 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:36.267   875  4507 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:36.267   875  4507 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:36.267   875  4507 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:36.267   875  4507 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:36.267   875  4507 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:36.267   875  4507 E DropBoxManagerService: 	... 5 more
,08-30 17:09:36.282  4446  4485 I Process : Sending signal. PID: 4446 SIG: 9
,08-30 17:09:36.300  4490  4490 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
08-30 17:09:36.311  4490  4490 I MultiDex: VM with version 2.1.0 has multidex support
08-30 17:09:36.311  4490  4490 I MultiDex: install
08-30 17:09:36.311  4490  4490 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 17:09:36.318  4490  4490 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-30 17:09:36.323  4490  4490 I GservicesProvider: Gservices pushing to system: true; secure/global: true
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:36.326  4490  4490 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:36.327  4490  4490 D AndroidRuntime: Shutting down VM
08-30 17:09:36.328  4490  4490 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:36.328  4490  4490 E AndroidRuntime: Process: com.google.process.gapps, PID: 4490
08-30 17:09:36.328  4490  4490 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:36.328  4490  4490 E AndroidRuntime: 	... 10 more
08-30 17:09:36.330  4490  4490 I Process : Sending signal. PID: 4490 SIG: 9
08-30 17:09:36.332   875  4515 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:36.332   875  4515 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:36.332   875  4515 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:36.332   875  4515 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:36.332   875  4515 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:36.332   875  4515 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:36.332   875  4515 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:36.332   875  4515 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:36.332   875  4515 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:36.332   875  4515 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:36.332   875  4515 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:36.332   875  4515 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:36.332   875  4515 E DropBoxManagerService: 	... 5 more
,08-30 17:09:36.341  4502  4502 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:36.341  4502  4502 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:36.342  4502  4502 D AndroidRuntime: Shutting down VM
,08-30 17:09:36.349  4502  4502 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:36.349  4502  4502 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4502
08-30 17:09:36.349  4502  4502 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:36.349  4502  4502 E AndroidRuntime: 	... 10 more
,08-30 17:09:36.351   875  2055 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 17:09:36.351  4502  4502 I Process : Sending signal. PID: 4502 SIG: 9
,08-30 17:09:36.352   875  4516 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:36.352   875  4516 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:36.352   875  4516 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:36.352   875  4516 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:36.352   875  4516 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:36.352   875  4516 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:36.352   875  4516 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:36.352   875  4516 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:36.352   875  4516 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:36.352   875  4516 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:36.352   875  4516 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:36.352   875  4516 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:36.352   875  4516 E DropBoxManagerService: 	... 5 more
,08-30 17:09:36.369  1900  4307 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@7fb32c3
,08-30 17:09:36.369  1900  4307 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@7fb32c3
,08-30 17:09:36.373   875  1703 I ActivityManager: Process com.google.process.gapps (pid 4490) has died
,08-30 17:09:36.374   875  2068 W ActivityManager: Unable to launch app com.google.android.gsf/10011 for provider com.google.android.gsf.gservices: launching app became null
08-30 17:09:36.374  4379  4379 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
,08-30 17:09:36.397   875  1703 I ActivityManager: Start proc 4520:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,08-30 17:09:36.399   875   885 I ActivityManager: Process android.process.acore (pid 4446) has died
,08-30 17:09:36.407   875  1405 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4502) has died
,08-30 17:09:36.409   875  1405 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 17:09:36.431   875  2071 I ActivityManager: Start proc 4532:android.process.acore/u0a5 for content provider com.android.providers.contacts/.ContactsProvider2
,08-30 17:09:36.454   875  2210 I ActivityManager: Start proc 4544:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 17:09:36.486  4532  4532 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-30 17:09:36.502  4520  4520 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-30 17:09:36.513  4544  4544 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:36.513  4544  4544 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:09:36.513  4544  4544 D AndroidRuntime: Shutting down VM
,08-30 17:09:36.524  4544  4544 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:36.524  4544  4544 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4544
08-30 17:09:36.524  4544  4544 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:36.524  4544  4544 E AndroidRuntime: 	... 10 more
,08-30 17:09:36.528   875  2224 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 17:09:36.528  4520  4520 I MultiDex: VM with version 2.1.0 has multidex support
08-30 17:09:36.528  4520  4520 I MultiDex: install
08-30 17:09:36.529  4520  4520 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 17:09:36.530  4544  4544 I Process : Sending signal. PID: 4544 SIG: 9
,08-30 17:09:36.532   875  4556 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:36.532   875  4556 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:36.532   875  4556 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:36.532   875  4556 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:36.532   875  4556 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:36.532   875  4556 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:36.532   875  4556 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:36.532   875  4556 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:36.532   875  4556 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:36.532   875  4556 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:36.532   875  4556 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:36.532   875  4556 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:36.532   875  4556 E DropBoxManagerService: 	... 5 more
,08-30 17:09:36.534  4520  4520 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-30 17:09:36.551  4520  4520 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-30 17:09:36.555  4532  4532 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-30 17:09:36.557  4520  4520 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:36.557  4520  4520 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:09:36.557  4520  4520 D AndroidRuntime: Shutting down VM
,08-30 17:09:36.559  4520  4520 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:36.559  4520  4520 E AndroidRuntime: Process: com.google.process.gapps, PID: 4520
08-30 17:09:36.559  4520  4520 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	at android.app.ActivityTh,read.installProvider(ActivityThread.java:5153)
08-30 17:09:36.559  4520  4520 E AndroidRuntime: 	... 10 more
08-30 17:09:36.561   875  2209 W ActivityManager: Process com.google.android.gms has crashed too many times: killing!
08-30 17:09:36.561   875  2209 I ActivityManager: Killing 4520:com.google.process.gapps/u0a11 (adj 0): crash
08-30 17:09:36.562   875  4560 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:36.562   875  4560 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop147.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:36.562   875  4560 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:36.562   875  4560 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:36.562   875  4560 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:36.562   875  4560 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:36.562   875  4560 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:36.562   875  4560 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:36.562   875  4560 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:36.562   875  4560 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:36.562   875  4560 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:36.562   875  4560 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:36.562   875  4560 E DropBoxManagerService: 	... 5 more
,08-30 17:09:36.576  4532  4558 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 17:09:36.576  4532  4558 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.576  4532  4558 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:36.576  4532  4558 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:36.576  4532  4558 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:36.576  4532  4558 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:36.576  4532  4558 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:36.576  4532  4558 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:36.576  4532  4558 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:36.576  4532  4558 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:36.576  4532  4558 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:36.576  4532  4558 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:36.576  4532  4558 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:36.576  4532  4558 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:36.576  4532  4558 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:09:36.576  4532  4558 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 17:09:36.576  4532  4558 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 17:09:36.576  4532  4558 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 17:09:36.576  4532  4558 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 17:09:36.576  4532  4558 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.576  4532  4558 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.576  4532  4558 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:09:36.576  4532  4558 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):,
08-30 17:09:36.576  4532  4558 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.576  4532  4558 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:36.576  4532  4558 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:36.576  4532  4558 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:36.576  4532  4558 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:36.576  4532  4558 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:36.576  4532  4558 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:36.576  4532  4558 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:36.576  4532  4558 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:36.576  4532  4558 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:36.576  4532  4558 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:36.576  4532  4558 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:36.576  4532  4558 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:36.576  4532  4558 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:09:36.576  4532  4558 E SQLiteOpenHelper: ,	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 17:09:36.576  4532  4558 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 17:09:36.576  4532  4558 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 17:09:36.576  4532  4558 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 17:09:36.576  4532  4558 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.576  4532  4558 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.576  4532  4558 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:09:36.596  4532  4558 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-30 17:09:36.600  4532  4558 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
08-30 17:09:36.600  4532  4558 E AndroidRuntime: Process: android.process.acore, PID: 4532
08-30 17:09:36.600  4532  4558 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-30 17:09:36.600  4532  4558 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 17:09:36.600  4532  4558 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 17:09:36.600  4532  4558 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 17:09:36.600  4532  4558 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 17:09:36.600  4532  4558 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1676)
08-30 17:09:36.600  4532  4558 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1605)
08-30 17:09:36.600  4532  4558 E AndroidRuntime: 	at com.android.providers.contacts.ContactsDatabaseHelper.onOpen(ContactsDatabaseHelper.java:1084)
08-30 17:09:36.600  4532  4558 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:266)
08-30 17:09:36.600  4532  4558 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:09:36.600  4532  4558 E AndroidRuntime: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 17:09:36.600  4532  4558 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 17:09:36.600  4532  4558 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 17:09:36.600  4532  4558 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 17:09:36.600  4532  4558 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.600  4532  4558 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.600  4532  4558 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:09:36.619   875  2006 W ActivityManager: Unable to launch app com.google.android.gsf/10011 for provider com.google.android.gsf.gservices: launching app became null
,08-30 17:09:36.619   875  1713 W ActivityManager: Unable to launch app com.google.android.gsf/10011 for provider com.google.android.gsf.gservices: launching app became null
,08-30 17:09:36.620   875  1399 W ActivityManager: Unable to launch app com.google.android.gsf/10011 for provider com.google.android.gsf.gservices: launching app became null
,08-30 17:09:36.620  4379  4518 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
08-30 17:09:36.620  4379  4518 W WakefulBroadcastReceiver: No active wake lock id #8
,08-30 17:09:36.620  4379  4379 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
08-30 17:09:36.621  4379  4517 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
,08-30 17:09:36.621  4379  4379 I GAv4-SVC: Google Analytics 8.1.86 is starting up.
,08-30 17:09:36.653   875  2209 I ActivityManager: Start proc 4561:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,08-30 17:09:36.655   875   886 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4544) has died
,08-30 17:09:36.657   875   886 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-30 17:09:36.663   875  1999 W ActivityManager: Spurious death for ProcessRecord{1c4435c 4561:com.google.process.gapps/u0a11}, curProc for 4520: null
08-30 17:09:36.664   875  4572 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:36.664   875  4572 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop148.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:36.664   875  4572 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:36.664   875  4572 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:36.664   875  4572 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:36.664   875  4572 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:36.664   875  4572 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:36.664   875  4572 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:36.664   875  4572 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:36.664   875  4572 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:36.664   875  4572 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:36.664   875  4572 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:36.664   875  4572 E DropBoxManagerService: 	... 5 more
08-30 17:09:36.664  4532  4558 I Process : Sending signal. PID: 4532 SIG: 9
,08-30 17:09:36.676   875   888 I ActivityManager: Start proc 4574:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 17:09:36.700  4561  4561 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-30 17:09:36.709  4561  4561 I MultiDex: VM with version 2.1.0 has multidex support
,08-30 17:09:36.709  4561  4561 I MultiDex: install
08-30 17:09:36.709  4561  4561 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 17:09:36.714  4561  4561 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-30 17:09:36.718  4561  4561 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-30 17:09:36.720  4561  4561 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:36.720  4561  4561 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:36.720  4561  4561 D AndroidRuntime: Shutting down VM
,08-30 17:09:36.720  4561  4561 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:36.720  4561  4561 E AndroidRuntime: Process: com.google.process.gapps, PID: 4561
08-30 17:09:36.720  4561  4561 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	at android.app.ActivityTh,read.installProvider(ActivityThread.java:5153)
08-30 17:09:36.720  4561  4561 E AndroidRuntime: 	... 10 more
,08-30 17:09:36.725  4561  4561 I Process : Sending signal. PID: 4561 SIG: 9
,08-30 17:09:36.729   875  4586 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:36.729   875  4586 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop149.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:36.729   875  4586 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:36.729   875  4586 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:36.729   875  4586 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:36.729   875  4586 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:36.729   875  4586 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:36.729   875  4586 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:36.729   875  4586 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:36.729   875  4586 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:36.729   875  4586 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:36.729   875  4586 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:36.729   875  4586 E DropBoxManagerService: 	... 5 more
,08-30 17:09:36.738  4574  4574 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:36.738  4574  4574 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:09:36.738  4574  4574 D AndroidRuntime: Shutting down VM
,08-30 17:09:36.746  4574  4574 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:36.746  4574  4574 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4574
08-30 17:09:36.746  4574  4574 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:36.746  4574  4574 E AndroidRuntime: 	... 10 more
08-30 17:09:36.747   875  2068 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 17:09:36.748  4574  4574 I Process : Sending signal. PID: 4574 SIG: 9
,08-30 17:09:36.752   875  4587 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:36.752   875  4587 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop150.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:36.752   875  4587 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:36.752   875  4587 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:36.752   875  4587 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:36.752   875  4587 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:36.752   875  4587 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:36.752   875  4587 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:36.752   875  4587 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:36.752   875  4587 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:36.752   875  4587 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:36.752   875  4587 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:36.752   875  4587 E DropBoxManagerService: 	... 5 more
,08-30 17:09:36.758   875  2210 I ActivityManager: Process android.process.acore (pid 4532) has died
,08-30 17:09:36.759   875  2210 I ActivityManager: Killing 1900:com.google.android.inputmethod.latin/u0a63 (adj 2): depends on provider com.android.providers.contacts/.ContactsProvider2 in dying proc android.process.acore
,08-30 17:09:36.787   875   875 W InputMethodManagerService: Session failed to close due to remote exception
08-30 17:09:36.787   875   875 W InputMethodManagerService: android.os.DeadObjectException
08-30 17:09:36.787   875   875 W InputMethodManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 17:09:36.787   875   875 W InputMethodManagerService: 	at android.os.BinderProxy.transact(Binder.java:503)
08-30 17:09:36.787   875   875 W InputMethodManagerService: 	at com.android.internal.view.IInputMethodSession$Stub$Proxy.finishSession(IInputMethodSession.java:305)
08-30 17:09:36.787   875   875 W InputMethodManagerService: 	at com.android.server.InputMethodManagerService.finishSessionLocked(InputMethodManagerService.java:1599)
08-30 17:09:36.787   875   875 W InputMethodManagerService: 	at com.android.server.InputMethodManagerService.clearClientSessionLocked(InputMethodManagerService.java:1590)
08-30 17:09:36.787   875   875 W InputMethodManagerService: 	at com.android.server.InputMethodManagerService.clearCurMethodLocked(InputMethodManagerService.java:1616)
08-30 17:09:36.787   875   875 W InputMethodManagerService: 	at com.android.server.InputMethodManagerService.onServiceDisconnected(InputMethodManagerService.java:1635)
08-30 17:09:36.787   875   875 W InputMethodManagerService: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1228)
08-30 17:09:36.787   875   875 W InputMethodManagerService: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1242)
08-30 17:09:36.787   875   875 W InputMethodManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 17:09:36.787   875   875 W InputMethodManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 17:09:36.787   875   875 W InputMethodManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.787   875   875 W InputMethodManagerService: 	at com.android.server.SystemServer.run(SystemServer.java:283)
08-30 17:09:36.787   875   875 W InputMethodManagerService: 	at com.android.server.SystemServer.main(SystemServer.java:168)
08-30 17:09:36.787   875   875 W InputMethodManagerService: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:36.787   875   875 W InputMethodManagerService: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:36.787   875   875 W InputMethodManagerService: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:09:36.792   875  1713 I ActivityManager: Process com.google.process.gapps (pid 4561) has died
,08-30 17:09:36.792   875  1405 W ActivityManager: Unable to launch app com.google.android.gsf/10011 for provider com.google.android.gsf.gservices: launching app became null
,08-30 17:09:36.793   875  2224 W ActivityManager: Unable to launch app com.google.android.gsf/10011 for provider com.google.android.gsf.gservices: launching app became null
,08-30 17:09:36.794  4379  4517 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
,08-30 17:09:36.794  4379  4518 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
,08-30 17:09:36.794   875   885 W ActivityManager: Unable to launch app com.google.android.gsf/10011 for provider com.google.android.gsf.gservices: launching app became null
,08-30 17:09:36.795  4379  4379 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
,08-30 17:09:36.796  4379  4518 E MDM     : [365] SitrepService.onHandleIntent: Android ID == 0, not sending sitrep
,08-30 17:09:36.796  4379  4518 E MDM     : [365] SitrepService.a: Error sending sitrep.
,08-30 17:09:36.813   875  1713 I ActivityManager: Start proc 4589:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,08-30 17:09:36.815   875  2071 W ActivityManager: Scheduling restart of crashed service com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME in 1000ms
,08-30 17:09:36.808  4379  4517 I SystemUpdateService: cancelUpdate (empty URL)
,08-30 17:09:36.815  4379  4517 I SystemUpdateService: active receiver: disabled
08-30 17:09:36.817   875  1703 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4574) has died
,08-30 17:09:36.822  4379  4517 I DownloadAttempt:  deleting /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 17:09:36.822   875  1703 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-30 17:09:36.823  4379  4517 I DownloadAttempt:  deleting /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 17:09:36.826  4379  4595 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/update.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/update.xml.bak
,08-30 17:09:36.827  4379  4595 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/update.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/update.xml.bak
,08-30 17:09:36.828   875  1323 E SQLiteLog: (3850) statement aborts at 24: [INSERT INTO log(key,first_expansion_time_ms,expansion_airtime_ms,posttime_ms,event_time_ms,event_type,expansion_count,airtime_ms,event_user_id,pkg) VALUES (?,?,?,?,?,?,?,?,?,?)] disk I
,08-30 17:09:36.829   875  1323 E SQLiteDatabase: Error inserting key=-1|com.google.android.gms|2130838104|null|10011 first_expansion_time_ms=-1 expansion_airtime_ms=0 posttime_ms=185997 event_time_ms=1472569776826 event_type=3 expansion_count=0 airtime_ms=0 event_user_id=-1 pkg=com.google.android.gms
08-30 17:09:36.829   875  1323 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 17:09:36.829   875  1323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-30 17:09:36.829   875  1323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:780)
08-30 17:09:36.829   875  1323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-30 17:09:36.829   875  1323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-30 17:09:36.829   875  1323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1471)
08-30 17:09:36.829   875  1323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1341)
08-30 17:09:36.829   875  1323 E SQLiteDatabase: 	at com.android.server.notification.NotificationUsageStats$SQLiteLog.writeEvent(NotificationUsageStats.java:942)
08-30 17:09:36.829   875  1323 E SQLiteDatabase: 	at com.android.server.notification.NotificationUsageStats$SQLiteLog.-wrap0(NotificationUsageStats.java)
08-30 17:09:36.829   875  1323 E SQLiteDatabase: 	at com.android.server.notification.NotificationUsageStats$SQLiteLog$1.handleMessage(NotificationUsageStats.java:792)
08-30 17:09:36.829   875  1323 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.829   875  1323 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.829   875  1323 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:09:36.829   875  1323 E NotificationSQLiteLog: Error while trying to insert values: key=-1|com.google.android.gms|2130838104|null|10011 first_expansion_time_ms=-1 expansion_airtime_ms=0 posttime_ms=185997 event_time_ms=1472569776826 event_type=3 expansion_count=0 airtime_ms=0 event_user_id=-1 pkg=com.google.android.gms
,08-30 17:09:36.834   875  1323 E DropBoxManagerService: Can't write: system_server_wtf
08-30 17:09:36.834   875  1323 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop47.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:36.834   875  1323 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:36.834   875  1323 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:36.834   875  1323 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:36.834   875  1323 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:36.834   875  1323 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:36.834   875  1323 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:36.834   875  1323 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-30 17:09:36.834   875  1323 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-30 17:09:36.834   875  1323 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12334)
08-30 17:09:36.834   875  1323 E DropBoxManagerService: 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:348)
08-30 17:09:36.834   875  1323 E DropBoxManagerService: 	at android.util.Log$1.onTerribleFailure(Log.java:104)
08-30 17:09:36.834   875  1323 E DropBoxManagerService: 	at android.util.Log.wtf(Log.java:297)
08-30 17:09:36.834   875  1323 E DropBoxManagerService: 	at android.util.Log.wtf(Log.java:256)
08-30 17:09:36.834   875  1323 E DropBoxManagerService: 	at com.android.server.notification.NotificationUsageStats$SQLiteLog.writeEvent(NotificationUsageStats.java:943)
08-30 17:09:36.834   875  1323 E DropBoxManagerService: 	at com.android.server.notification.NotificationUsageStats$SQLiteLog.-wrap0(NotificationUsageStats.java)
08-30 17:09:36.834   875  1323 E DropBoxManagerService: 	at com.android.server.notification.NotificationUsageStats$SQLiteLog$1.handleMessage(NotificationUsageStats.java:792)
08-30 17:09:36.834   875  1323 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.834   875  1323 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.834   875  1323 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:09:36.834   875  1323 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:36.834   875  1323 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:36.834   875  1323 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:36.834   875  1323 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:36.834   875  1323 E DropBoxManagerService: 	... 18 more
,08-30 17:09:36.857   875   888 I ActivityManager: Start proc 4602:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 17:09:36.882  4589  4589 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-30 17:09:36.895  4589  4589 I MultiDex: VM with version 2.1.0 has multidex support
08-30 17:09:36.895  4589  4589 I MultiDex: install
08-30 17:09:36.895  4589  4589 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 17:09:36.900  4589  4589 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-30 17:09:36.905  4589  4589 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-30 17:09:36.907  4589  4589 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:36.907  4589  4589 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:36.907  4589  4589 D AndroidRuntime: Shutting down VM
08-30 17:09:36.908  4589  4589 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:36.908  4589  4589 E AndroidRuntime: Process: com.google.process.gapps, PID: 4589
08-30 17:09:36.908  4589  4589 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvid,er: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:36.908  4589  4589 E AndroidRuntime: 	... 10 more
08-30 17:09:36.910   875   886 W ActivityManager: Process com.google.android.gms has crashed too many times: killing!
08-30 17:09:36.910   875   886 I ActivityManager: Killing 4589:com.google.process.gap,ps/u0a11 (adj 0): crash
08-30 17:09:36.915   875  4614 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:36.915   875  4614 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop152.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:36.915   875  4614 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:36.915   875  4614 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:36.915   875  4614 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:36.915   875  4614 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:36.915   875  4614 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:36.915   875  4614 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:36.915   875  4614 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:36.915   875  4614 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:36.915   875  4614 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:36.915   875  4614 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:36.915   875  4614 E DropBoxManagerService: 	... 5 more
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:36.936  4602  4602 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:36.936  4602  4602 D AndroidRuntime: Shutting down VM
,08-30 17:09:36.952   875  1999 W ActivityManager: Unable to launch app com.google.android.gsf/10011 for provider com.google.android.gsf.gservices: launching app became null
08-30 17:09:36.952   875  2006 W ActivityManager: Unable to launch app com.google.android.gsf/10011 for provider com.google.android.gsf.gservices: launching app became null
08-30 17:09:36.954  4379  4379 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
08-30 17:09:36.954  4379  4518 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
08-30 17:09:36.967  4379  4595 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/mdm.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/mdm.xml.bak
08-30 17:09:36.967  4379  4595 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/mdm.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/mdm.xml.bak
08-30 17:09:36.970   875   886 I ActivityManager: Start proc 4615:com.google.process.gapps/u0a11 for restart com.google.process.gapps
08-30 17:09:36.971   875  1404 W ActivityManager: Spurious death for ProcessRecord{1c4435c 4615:com.google.process.gapps/u0a11}, curProc for 4589: null
08-30 17:09:36.986  4602  4602 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:36.986  4602  4602 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4602
08-30 17:09:36.986  4602  4602 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:36.986  4602  4602 E AndroidRuntime: 	... 10 more
,08-30 17:09:36.988   875  2210 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 17:09:36.989  4602  4602 I Process : Sending signal. PID: 4602 SIG: 9
,08-30 17:09:36.989   875  4629 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:36.989   875  4629 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop153.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:36.989   875  4629 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:36.989   875  4629 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:36.989   875  4629 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:36.989   875  4629 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:36.989   875  4629 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:36.989   875  4629 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:36.989   875  4629 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:36.989   875  4629 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:36.989   875  4629 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:36.989   875  4629 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:36.989   875  4629 E DropBoxManagerService: 	... 5 more
,08-30 17:09:37.018  4615  4615 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-30 17:09:37.029  4615  4615 I MultiDex: VM with version 2.1.0 has multidex support
,08-30 17:09:37.029  4615  4615 I MultiDex: install
08-30 17:09:37.029  4615  4615 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 17:09:37.035   875   886 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4602) has died
,08-30 17:09:37.036   875   886 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 17:09:37.038  4615  4615 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-30 17:09:37.042  4615  4615 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-30 17:09:37.044  4615  4615 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:37.044  4615  4615 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:37.044  4615  4615 D AndroidRuntime: Shutting down VM
,08-30 17:09:37.045  4615  4615 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:37.045  4615  4615 E AndroidRuntime: Process: com.google.process.gapps, PID: 4615
08-30 17:09:37.045  4615  4615 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	at android.app.ActivityTh,read.installProvider(ActivityThread.java:5153)
08-30 17:09:37.045  4615  4615 E AndroidRuntime: 	... 10 more
,08-30 17:09:37.076   875   888 I ActivityManager: Start proc 4630:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 17:09:37.079  4615  4615 I Process : Sending signal. PID: 4615 SIG: 9
,08-30 17:09:37.082   875  4635 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:37.082   875  4635 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop154.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:37.082   875  4635 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:37.082   875  4635 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:37.082   875  4635 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:37.082   875  4635 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:37.082   875  4635 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:37.082   875  4635 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:37.082   875  4635 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:37.082   875  4635 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:37.082   875  4635 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:37.082   875  4635 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:37.082   875  4635 E DropBoxManagerService: 	... 5 more
,08-30 17:09:37.129   875  2209 I ActivityManager: Process com.google.process.gapps (pid 4615) has died
,08-30 17:09:37.131   875  1703 W ActivityManager: Unable to launch app com.google.android.gsf/10011 for provider com.google.android.gsf.gservices: launching app became null
,08-30 17:09:37.131   875  1405 W ActivityManager: Unable to launch app com.google.android.gsf/10011 for provider com.google.android.gsf.gservices: launching app became null
08-30 17:09:37.132  4379  4379 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
08-30 17:09:37.132  4379  4618 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_analytics_v4.db'.
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.w.getWritableDatabase(SourceFile:884)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.o(SourceFile:812)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.a(SourceFile:630)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.q(SourceFile:264)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.e(SourceFile:274)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.y.e(SourceFile:885)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.y.b(SourceFile:258)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.ab.run(SourceFile:152)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:09:37.138  4379  4618 E SQLiteDatabase: 	at com.google.android.gms.measurement.n.run(SourceFile:388)
08-30 17:09:3,7.138  4379  4618 E GAv4-SVC: Opening the database failed, dropping the table and recreating it
08-30 17:09:37.139  4379  4618 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
08-30 17:09:37.139  4379  4595 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_analytics_v4.db'.
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.w.getWritableDatabase(SourceFile:897)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.o(SourceFile:812)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.a(SourceFile:630)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.q(SourceFile:264)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.e(SourceFile:274)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.y.e(SourceFile:885)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.y.b(SourceFile:258)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.ab.run(SourceFile:152)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Work,er.run(ThreadPoolExecutor.java:588)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:09:37.141  4379  4618 E SQLiteDatabase: 	at com.google.android.gms.measurement.n.run(SourceFile:388)
08-30 17:09:37.141  4379  4618 E GAv4-SVC: Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.142  4379  4595 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
08-30 17:09:37.142  4379  4618 W GAv4-SVC: Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.143  4379  4595 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
08-30 17:09:37.143  4379  4618 E GAv4-SVC: Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.143  4379  4595 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
08-30 17:09:37.160   875  2209 I ActivityManager: Start proc 4643:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,08-30 17:09:37.214  4630  4630 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:37.214  4630  4630 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:09:37.215  4630  4630 D AndroidRuntime: Shutting down VM
,08-30 17:09:37.223  4630  4630 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:37.223  4630  4630 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4630
08-30 17:09:37.223  4630  4630 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:37.223  4630  4630 E AndroidRuntime: 	... 10 more
08-30 17:09:37.226   875  2071 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 17:09:37.227  4630  4630 I Process : Sending signal. PID: 4630 SIG: 9
08-30 17:09:37.230   875  4659 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:37.230   875  4659 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop155.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:37.230   875  4659 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:37.230   875  4659 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:37.230   875  4659 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:37.230   875  4659 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:37.230   875  4659 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:37.230   875  4659 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:37.230   875  4659 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:37.230   875  4659 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:37.230   875  4659 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:37.230   875  4659 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:37.230   875  4659 E DropBoxManagerService: 	... 5 more
08-30 17:09:37.259   875  2210 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4630) has died
,08-30 17:09:37.261   875  2210 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 17:09:37.280  4643  4643 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-30 17:09:37.282   875   888 I ActivityManager: Start proc 4660:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 17:09:37.309  4643  4643 I MultiDex: VM with version 2.1.0 has multidex support
08-30 17:09:37.309  4643  4643 I MultiDex: install
,08-30 17:09:37.309  4643  4643 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 17:09:37.303  4379  4658 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/reminders.db'.
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:421)
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:1017)
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:238)
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:491)
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:434)
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at com.google.android.gms.reminders.a.a.a(SourceFile:64)
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:45)
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:234)
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 17:09:37.303  4379  4658 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: Couldn't open reminders.db for writing (will try read-only):
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:421)
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at android.content.ContentProvider.query(ContentProvider.java:1017)
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:238)
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:491)
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:434)
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.a.a.a(SourceFile:64)
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:45)
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:234)
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 17:09:37.315  4379  4658 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-30 17:09:37.317  4379  4658 W SQLiteOpenHelper: Opened reminders.db in read-only mode
,08-30 17:09:37.322  4643  4643 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-30 17:09:37.327  4643  4643 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-30 17:09:37.329  4643  4643 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:37.329  4643  4643 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:37.330  4643  4643 D AndroidRuntime: Shutting down VM
08-30 17:09:37.330  4643  4643 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:37.330  4643  4643 E AndroidRuntime: Process: com.google.process.gapps, PID: 4643
08-30 17:09:37.330  4643  4643 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvid,er: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:37.330  4643  4643 E AndroidRuntime: 	... 10 more
08-30 17:09:37.332   875  2211 W ActivityManager: Process com.google.android.gms has crashed too many times: killing!
08-30 17:09:37.333   875  2211 I ActivityManager: Killing 4643:com.google.process.gapps/u0a11 (adj 0): crash
08-30 17:09:37.337   875  4672 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:37.337   875  4672 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop156.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:37.337   875  4672 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:37.337   875  4672 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:37.337   875  4672 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:37.337   875  4672 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:37.337   875  4672 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:37.337   875  4672 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:37.337   875  4672 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:37.337   875  4672 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:37.337   875  4672 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:37.337   875  4672 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:37.337   875  4672 E DropBoxManagerService: 	... 5 more
08-30 17:09:37.353  4379  4673 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/plus.db'.
08-30 17:09:37.353  4379  4673 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.353  4379  4673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:37.353  4379  4673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:37.353  4379  4673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:37.353  4379  4673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:37.353  4379  4673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:37.353  4379  4673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:37.353  4379  4673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:37.353  4379  4673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:37.353  4379  4673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:37.353  4379  4673 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:37.353  4379  4673 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:37.353  4379  4673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:37.353  4379  4673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:37.353  4379  4673 E SQLiteDatabase: 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
08-30 17:09:37.353  4379  4673 E SQLiteDatabase: 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
08-30 17:09:37.353  4379  4673 E SQLiteDatabase: 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
08-30 17:09:37.353  4379  4673 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
08-30 17:09:37.353  4379  4673 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 17:09:37.353  4379  4673 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:234)
08-30 17:09:37.353  4379  4673 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 17:09:37.353  4379  4673 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 17:09:37.353  4379  4673 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: FATAL EXCEPTION: AsyncTask #2
08-30 17:09:37.355  4379  4673 E AndroidRuntime: Process: com.google.android.gms, PID: 4379
08-30 17:09:37.355  4379  4673 E AndroidRuntime: java.lang.RuntimeException: An error occurred while executing doInBackground()
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at android.os.AsyncTask$3.done(AsyncTask.java:309)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:354)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:223)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:234)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 17:09:37.355  4379  4673 E AndroidRuntime: 	... 4 more
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:37.362  4660  4660 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:37.362  4660  4660 D AndroidRuntime: Shutting down VM
,08-30 17:09:37.380   875  1404 W ActivityManager: Unable to launch app com.google.android.gsf/10011 for provider com.google.android.gsf.gservices: launching app became null
08-30 17:09:37.381  4379  4379 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
08-30 17:09:37.397   875  2211 I ActivityManager: Start proc 4675:com.google.process.gapps/u0a11 for restart com.google.process.gapps
08-30 17:09:37.404   875  4686 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:37.404   875  4686 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop157.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:37.404   875  4686 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:37.404   875  4686 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:37.404   875  4686 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:37.404   875  4686 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:37.404   875  4686 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:37.404   875  4686 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:37.404   875  4686 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:37.404   875  4686 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:37.404   875  4686 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:37.404   875  4686 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:37.404   875  4686 E DropBoxManagerService: 	... 5 more
08-30 17:09:37.410   875  2209 W ActivityManager: Spurious death for ProcessRecord{1c4435c 4675:com.google.process.gapps/u0a11}, curProc for 4643: null
,08-30 17:09:37.415  4379  4673 I Process : Sending signal. PID: 4379 SIG: 9
,08-30 17:09:37.417  4660  4660 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:37.417  4660  4660 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4660
08-30 17:09:37.417  4660  4660 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:37.417  4660  4660 E AndroidRuntime: 	... 10 more
,08-30 17:09:37.422   875  2071 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 17:09:37.424   875  4690 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:37.424   875  4690 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop158.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:37.424   875  4690 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:37.424   875  4690 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:37.424   875  4690 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:37.424   875  4690 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:37.424   875  4690 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:37.424   875  4690 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:37.424   875  4690 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:37.424   875  4690 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:37.424   875  4690 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:37.424   875  4690 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:37.424   875  4690 E DropBoxManagerService: 	... 5 more
08-30 17:09:37.425  4660  4660 I Process : Sending signal. PID: 4660 SIG: 9
,08-30 17:09:37.448  4675  4675 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-30 17:09:37.458  4675  4675 I MultiDex: VM with version 2.1.0 has multidex support
08-30 17:09:37.458  4675  4675 I MultiDex: install
,08-30 17:09:37.458  4675  4675 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 17:09:37.463  4675  4675 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-30 17:09:37.466  4675  4675 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-30 17:09:37.469  4675  4675 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:37.469  4675  4675 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:09:37.469  4675  4675 D AndroidRuntime: Shutting down VM
08-30 17:09:37.470  4675  4675 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:37.470  4675  4675 E AndroidRuntime: Process: com.google.process.gapps, PID: 4675
08-30 17:09:37.470  4675  4675 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:37.470  4675  4675 E AndroidRuntime: 	... 10 more
08-30 17:09:37.473   875  1405 W ActivityManager: Process com.google.android.gms has crashed too many times: killing!
08-30 17:09:37.473   875  1405 I ActivityManager: Killing 4675:com.google.process.gapps/u0a11 (adj 0): crash
08-30 17:09:37.474   875  4691 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:37.474   875  4691 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop159.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:37.474   875  4691 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:37.474   875  4691 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:37.474   875  4691 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:37.474   875  4691 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:37.474   875  4691 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:37.474   875  4691 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:37.474   875  4691 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:37.474   875  4691 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:37.474   875  4691 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:37.474   875  4691 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:37.474   875  4691 E DropBoxManagerService: 	... 5 more
,08-30 17:09:37.481  4318  4345 W GmsClient: service died
,08-30 17:09:37.483  4318  4318 E SilentFeedbackService: GoogleApiClient silent feedback connection failed with result: 8
,08-30 17:09:37.544   875  1405 W ActivityManager: Failure disconnecting service ComponentInfo{com.google.android.gms/com.google.android.gms.clearcut.service.ClearcutLoggerService} to connection android.os.BinderProxy@8003faf (in com.google.android.gms)
08-30 17:09:37.544   875  1405 W ActivityManager: android.os.DeadObjectException
08-30 17:09:37.544   875  1405 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 17:09:37.544   875  1405 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
08-30 17:09:37.544   875  1405 W ActivityManager: 	at android.app.IServiceConnection$Stub$Proxy.connected(IServiceConnection.java:92)
08-30 17:09:37.544   875  1405 W ActivityManager: 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1704)
08-30 17:09:37.544   875  1405 W ActivityManager: 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2336)
08-30 17:09:37.544   875  1405 W ActivityManager: 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15543)
08-30 17:09:37.544   875  1405 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4567)
08-30 17:09:37.544   875  1405 W ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-30 17:09:37.544   875  1405 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppCrashLocked(ActivityManagerService.java:12031)
08-30 17:09:37.544   875  1405 W ActivityManager: 	at com.android.server.am.ActivityManagerService.makeAppCrashingLocked(ActivityManagerService.java:11933)
08-30 17:09:37.544   875  1405 W ActivityManager: 	at com.android.server.am.ActivityManagerService.crashApplication(ActivityManagerService.java:12622)
08-30 17:09:37.544   875  1405 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12129)
08-30 17:09:37.544   875  1405 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12111)
08-30 17:09:37.544   875  1405 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1458)
08-30 17:09:37.544   875  1405 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
08-30 17:09:37.544   875  1405 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:453)
,08-30 17:09:37.546   875  1404 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4660) has died
,08-30 17:09:37.551   875  1404 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 17:09:37.563   875  1399 W ActivityManager: Spurious death for ProcessRecord{1c4435c 0:com.google.process.gapps/u0a11}, curProc for 4675: null
,08-30 17:09:37.564   875  2209 I ActivityManager: Process com.google.android.gms (pid 4379) has died
,08-30 17:09:37.564   875  2209 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{cb05f55 u0 com.google.android.gms/.update.SystemUpdateService}
08-30 17:09:37.564   875  2209 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackAsyncService in 10251ms
08-30 17:09:37.564   875  2209 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{3d9be13 u0 com.google.android.gms/.analytics.service.AnalyticsService}
08-30 17:09:37.564   875  2209 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackService in 20251ms
,08-30 17:09:37.585   875   888 I ActivityManager: Start proc 4693:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 17:09:37.602  2038  4699 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-30 17:09:37.648  2038  4699 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-30 17:09:37.672  2038  4699 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,08-30 17:09:37.672  2038  4699 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-30 17:09:37.672  2038  4699 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 2038
08-30 17:09:37.672  2038  4699 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 17:09:37.672  2038  4699 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-30 17:09:37.672  2038  4699 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-30 17:09:37.672  2038  4699 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-30 17:09:37.672  2038  4699 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-30 17:09:37.672  2038  4699 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-30 17:09:37.672  2038  4699 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-30 17:09:37.672  2038  4699 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-30 17:09:37.672  2038  4699 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-30 17:09:37.672  2038  4699 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-30 17:09:37.672  2038  4699 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-30 17:09:37.672  2038  4699 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-30 17:09:37.672  2038  4699 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-30 17:09:37.672  2038  4699 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-30 17:09:37.672  2038  4699 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-30 17:09:37.672  2038  4699 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 17:09:37.672  2038  4699 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:37.672  2038  4699 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:37.672  2038  4699 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:09:37.679   875  2211 I ActivityManager: Start proc 4706:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
,08-30 17:09:37.683  2038  4699 I Process : Sending signal. PID: 2038 SIG: 9
,08-30 17:09:37.683   875  4712 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:37.683   875  4712 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop160.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:37.683   875  4712 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:37.683   875  4712 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:37.683   875  4712 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:37.683   875  4712 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:37.683   875  4712 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:37.683   875  4712 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:37.683   875  4712 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:37.683   875  4712 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:37.683   875  4712 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:37.683   875  4712 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:37.683   875  4712 E DropBoxManagerService: 	... 5 more
,08-30 17:09:37.718  4693  4693 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:37.718  4693  4693 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:09:37.719  4693  4693 D AndroidRuntime: Shutting down VM
08-30 17:09:37.722   875  1318 D WifiService: Client connection lost with reason: 4
,08-30 17:09:37.728   875  1404 I ActivityManager: Process com.google.android.googlequicksearchbox:search (pid 2038) has died
,08-30 17:09:37.728   875  1404 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 10087ms
,08-30 17:09:37.733  4693  4693 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:37.733  4693  4693 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4693
08-30 17:09:37.733  4693  4693 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:37.733  4693  4693 E AndroidRuntime: 	... 10 more
08-30 17:09:37.735   875  2068 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
,08-30 17:09:37.735   875  2068 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 17:09:37.736   875  4719 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:37.736   875  4719 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop161.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:37.736   875  4719 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:37.736   875  4719 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:37.736   875  4719 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:37.736   875  4719 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:37.736   875  4719 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:37.736   875  4719 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:37.736   875  4719 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:37.736   875  4719 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:37.736   875  4719 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:37.736   875  4719 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:37.736   875  4719 E DropBoxManagerService: 	... 5 more
,08-30 17:09:37.736   875  2068 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 17:09:37.738   875  2068 I ActivityManager: Killing 4693:com.google.android.googlequicksearchbox/u0a28 (adj 0): crash
,08-30 17:09:37.750  4706  4706 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-30 17:09:37.765  4706  4706 I MultiDex: VM with version 2.1.0 has multidex support
,08-30 17:09:37.765  4706  4706 I MultiDex: install
08-30 17:09:37.765  4706  4706 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 17:09:37.783   875  2068 I ActivityManager: Start proc 4720:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 17:09:37.802   875   888 I ActivityManager: Start proc 4727:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,08-30 17:09:37.802   875  1399 W ActivityManager: Spurious death for ProcessRecord{9e1d43e 0:com.google.android.googlequicksearchbox/u0a28}, curProc for 4693: null
,08-30 17:09:37.835   875   888 I ActivityManager: Start proc 4745:com.google.android.inputmethod.latin/u0a63 for service com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME
,08-30 17:09:37.854  4727  4727 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,08-30 17:09:37.861  4720  4720 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:37.861  4720  4720 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:09:37.861  4720  4720 D AndroidRuntime: Shutting down VM
,08-30 17:09:37.874   875  2211 I ActivityManager: Start proc 4759:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,08-30 17:09:37.878  4720  4720 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:37.878  4720  4720 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4720
08-30 17:09:37.878  4720  4720 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:37.878  4720  4720 E AndroidRuntime: 	... 10 more
,08-30 17:09:37.879   875  2210 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 17:09:37.880  4720  4720 I Process : Sending signal. PID: 4720 SIG: 9
08-30 17:09:37.880   875  4769 E DropBoxManagerService: Can't write: system_app_crash
,08-30 17:09:37.880   875  4769 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop162.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:37.880   875  4769 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:37.880   875  4769 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:37.880   875  4769 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:37.880   875  4769 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:37.880   875  4769 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:37.880   875  4769 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:37.880   875  4769 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:37.880   875  4769 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:37.880   875  4769 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:37.880   875  4769 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:37.880   875  4769 E DropBoxManagerService: 	... 5 more
,08-30 17:09:37.921  4759  4759 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-30 17:09:37.931   875   885 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4720) has died
,08-30 17:09:37.933   875   885 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 17:09:37.938  4759  4759 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-30 17:09:37.940  4759  4759 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:37.940  4759  4759 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:09:37.941  4759  4759 D AndroidRuntime: Shutting down VM
,08-30 17:09:37.941  4759  4759 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:37.941  4759  4759 E AndroidRuntime: Process: com.google.process.gapps, PID: 4759
08-30 17:09:37.941  4759  4759 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at android.content,.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:37.941  4759  4759 E AndroidRuntime: 	... 10 more
,08-30 17:09:37.952  4745  4745 I Decoder : createOrResetDecoder
,08-30 17:09:37.953  4745  4745 I Decoder : createOrResetDecoder
,08-30 17:09:37.959  4745  4745 I LatinIME: Hardware accelerated drawing: true
,08-30 17:09:37.977   875   888 I ActivityManager: Start proc 4774:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 17:09:37.979  4759  4759 I Process : Sending signal. PID: 4759 SIG: 9
,08-30 17:09:37.982   875  4779 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:37.982   875  4779 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop163.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:37.982   875  4779 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:37.982   875  4779 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:37.982   875  4779 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:37.982   875  4779 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:37.982   875  4779 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:37.982   875  4779 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:37.982   875  4779 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:37.982   875  4779 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:37.982   875  4779 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:37.982   875  4779 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:37.982   875  4779 E DropBoxManagerService: 	... 5 more
,08-30 17:09:38.001   875  2209 W AtomicFile: Couldn't rename file /data/system/inputmethod/subtypes.xml to backup file /data/system/inputmethod/subtypes.xml.bak
,08-30 17:09:38.005   875  2209 W InputMethodManagerService: Error writing subtypes
08-30 17:09:38.005   875  2209 W InputMethodManagerService: java.io.IOException: Couldn't create directory /data/system/inputmethod/subtypes.xml
08-30 17:09:38.005   875  2209 W InputMethodManagerService: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-30 17:09:38.005   875  2209 W InputMethodManagerService: 	at com.android.server.InputMethodManagerService$InputMethodFileManager.writeAdditionalInputMethodSubtypes(InputMethodManagerService.java:3631)
08-30 17:09:38.005   875  2209 W InputMethodManagerService: 	at com.android.server.InputMethodManagerService$InputMethodFileManager.addInputMethodSubtypes(InputMethodManagerService.java:3613)
08-30 17:09:38.005   875  2209 W InputMethodManagerService: 	at com.android.server.InputMethodManagerService.setAdditionalInputMethodSubtypes(InputMethodManagerService.java:2561)
08-30 17:09:38.005   875  2209 W InputMethodManagerService: 	at com.android.internal.view.IInputMethodManager$Stub.onTransact(IInputMethodManager.java:439)
08-30 17:09:38.005   875  2209 W InputMethodManagerService: 	at com.android.server.InputMethodManagerService.onTransact(InputMethodManagerService.java:1068)
08-30 17:09:38.005   875  2209 W InputMethodManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
,08-30 17:09:38.031   875   885 I ActivityManager: Process com.google.process.gapps (pid 4759) has died
,08-30 17:09:38.044   875   885 I ActivityManager: Start proc 4787:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,08-30 17:09:38.055  4774  4774 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:38.055  4774  4774 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:09:38.057  4774  4774 D AndroidRuntime: Shutting down VM
,08-30 17:09:38.063  4774  4774 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:38.063  4774  4774 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4774
08-30 17:09:38.063  4774  4774 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:38.063  4774  4774 E AndroidRuntime: 	... 10 more
08-30 17:09:38.065   875  2209 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 17:09:38.066  4774  4774 I Process : Sending signal. PID: 4774 SIG: 9
,08-30 17:09:38.066   875  4799 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:38.066   875  4799 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop164.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:38.066   875  4799 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:38.066   875  4799 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:38.066   875  4799 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:38.066   875  4799 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:38.066   875  4799 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:38.066   875  4799 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:38.066   875  4799 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:38.066   875  4799 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:38.066   875  4799 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:38.066   875  4799 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:38.066   875  4799 E DropBoxManagerService: 	... 5 more
08-30 17:09:38.068  4745  4745 I StatsUtilsManager: onCreate()
08-30 17:09:38.068  4745  4745 I PeriodicStatsRecorder: shouldRecordStats() = Disabled
,08-30 17:09:38.091  4787  4787 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-30 17:09:38.093   875  2068 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4774) has died
,08-30 17:09:38.094   875  2068 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 17:09:38.114  4787  4787 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-30 17:09:38.117  4787  4787 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:38.117  4787  4787 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:09:38.117  4787  4787 D AndroidRuntime: Shutting down VM
,08-30 17:09:38.118   875   888 I ActivityManager: Start proc 4801:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 17:09:38.121  4745  4745 W InputAttributes: No editor info for this field. Bug?
,08-30 17:09:38.124  4787  4787 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:38.124  4787  4787 E AndroidRuntime: Process: com.google.process.gapps, PID: 4787
08-30 17:09:38.124  4787  4787 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at android.content,.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:38.124  4787  4787 E AndroidRuntime: 	... 10 more
,08-30 17:09:38.136   875  2210 W ActivityManager: Process com.google.process.gapps has crashed too many times: killing!
08-30 17:09:38.136   875  2210 I ActivityManager: Killing 4787:com.google.process.gapps/u0a11 (adj 0): crash
,08-30 17:09:38.138   875  4812 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:38.138   875  4812 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop165.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:38.138   875  4812 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:38.138   875  4812 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:38.138   875  4812 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:38.138   875  4812 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:38.138   875  4812 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:38.138   875  4812 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:38.138   875  4812 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:38.138   875  4812 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:38.138   875  4812 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:38.138   875  4812 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:38.138   875  4812 E DropBoxManagerService: 	... 5 more
,08-30 17:09:38.171  4745  4745 I Keyboard.Facilitator: resetDictionaries() : en_US
08-30 17:09:38.171  4745  4745 I Keyboard.Personal: create()
,08-30 17:09:38.176  4745  4745 I StatsUtilsManager: onLoadSettings()
,08-30 17:09:38.184  4745  4814 I Keyboard.Facilitator.DecoderInitializer: run()
08-30 17:09:38.184  4745  4814 I Decoder : createOrResetDecoder
,08-30 17:09:38.224   875  2211 W ActivityManager: Unable to launch app com.google.android.gsf/10011 for provider com.google.android.gsf.gservices: launching app became null
,08-30 17:09:38.225  4706  4706 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
,08-30 17:09:38.264   875  2210 I ActivityManager: Start proc 4815:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,08-30 17:09:38.280   875  1404 W ActivityManager: Spurious death for ProcessRecord{349c8ee 4815:com.google.process.gapps/u0a11}, curProc for 4787: null
,08-30 17:09:38.319  4801  4801 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:38.319  4801  4801 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:09:38.320  4801  4801 D AndroidRuntime: Shutting down VM
,08-30 17:09:38.326  4801  4801 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:38.326  4801  4801 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4801
08-30 17:09:38.326  4801  4801 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:38.326  4801  4801 E AndroidRuntime: 	... 10 more
,08-30 17:09:38.328   875  2210 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 17:09:38.329  4801  4801 I Process : Sending signal. PID: 4801 SIG: 9
,08-30 17:09:38.331   875  4827 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:38.331   875  4827 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop166.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:38.331   875  4827 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:38.331   875  4827 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:38.331   875  4827 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:38.331   875  4827 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:38.331   875  4827 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:38.331   875  4827 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:38.331   875  4827 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:38.331   875  4827 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:38.331   875  4827 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:38.331   875  4827 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:38.331   875  4827 E DropBoxManagerService: 	... 5 more
,08-30 17:09:38.351  4706  4706 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-30 17:09:38.358  4815  4815 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-30 17:09:38.372   875  1999 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4801) has died
,08-30 17:09:38.373   875  1999 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 17:09:38.384  4815  4815 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-30 17:09:38.388  4815  4815 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:38.388  4815  4815 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:38.388  4815  4815 D AndroidRuntime: Shutting down VM
08-30 17:09:38.389  4815  4815 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:38.389  4815  4815 E AndroidRuntime: Process: com.google.process.gapps, PID: 4815
08-30 17:09:38.38,9  4815  4815 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:38.389  4815  4815 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30, 17:09:38.389  4815  4815 E AndroidRuntime: 	... 10 more
08-30 17:09:38.412  4706  4706 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-30 17:09:38.412   875   888 I ActivityManager: Start proc 4830:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 17:09:38.417  4815  4815 I Process : Sending signal. PID: 4815 SIG: 9
08-30 17:09:38.420   875  4835 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:38.420   875  4835 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop167.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:38.420   875  4835 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:38.420   875  4835 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:38.420   875  4835 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:38.420   875  4835 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:38.420   875  4835 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:38.420   875  4835 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:38.420   875  4835 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:38.420   875  4835 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:38.420   875  4835 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:38.420   875  4835 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:38.420   875  4835 E DropBoxManagerService: 	... 5 more
,08-30 17:09:38.460  4727  4772 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-30 17:09:38.460  4727  4772 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 17:09:38.460  4727  4772 I GAv4    :   adb logcat -s GAv4
,08-30 17:09:38.465   279   279 E lowmemorykiller: Error writing /proc/4815/oom_score_adj; errno=22
08-30 17:09:38.465   875  1399 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
,08-30 17:09:38.479   875  2006 I ActivityManager: Process com.google.process.gapps (pid 4815) has died
,08-30 17:09:38.480   875  1404 W ActivityManager: Unable to launch app com.google.android.gsf/10011 for provider com.google.android.gsf.gservices: launching app became null
,08-30 17:09:38.481  4706  4706 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
,08-30 17:09:38.494   875  2006 I ActivityManager: Start proc 4847:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,08-30 17:09:38.518  4830  4830 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:38.518  4830  4830 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:09:38.519  4830  4830 D AndroidRuntime: Shutting down VM
,08-30 17:09:38.525  4830  4830 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:38.525  4830  4830 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4830
08-30 17:09:38.525  4830  4830 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:38.525  4830  4830 E AndroidRuntime: 	... 10 more
08-30 17:09:38.527   875  2068 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 17:09:38.528  4830  4830 I Process : Sending signal. PID: 4830 SIG: 9
08-30 17:09:38.532   875  4859 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:38.532   875  4859 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop168.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:38.532   875  4859 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:38.532   875  4859 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:38.532   875  4859 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:38.532   875  4859 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:38.532   875  4859 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:38.532   875  4859 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:38.532   875  4859 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:38.532   875  4859 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:38.532   875  4859 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:38.532   875  4859 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:38.532   875  4859 E DropBoxManagerService: 	... 5 more
08-30 17:09:38.572   875   886 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4830) has died
08-30 17:09:38.577   875   886 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-30 17:09:38.582  4706  4846 W NativeLibraryUtils: Failed to open lock file
08-30 17:09:38.582  4706  4846 W NativeLibraryUtils: java.io.FileNotFoundException: /data/user/0/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
08-30 17:09:38.582  4706  4846 W NativeLibraryUtils: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:38.582  4706  4846 W NativeLibraryUtils: 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
08-30 17:09:38.582  4706  4846 W NativeLibraryUtils: 	at com.google.android.gms.common.util.ay.b(SourceFile:325)
08-30 17:09:38.582  4706  4846 W NativeLibraryUtils: 	at com.google.android.gms.common.app.a.run(SourceFile:171)
08-30 17:09:38.582  4706  4846 W NativeLibraryUtils: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:38.582  4706  4846 W NativeLibraryUtils: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:38.582  4706  4846 W NativeLibraryUtils: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:38.582  4706  4846 W NativeLibraryUtils: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:38.582  4706  4846 W NativeLibraryUtils: 	... 3 more
,08-30 17:09:38.599  4847  4847 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-30 17:09:38.613   875   888 I ActivityManager: Start proc 4863:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 17:09:38.622  4727  4873 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.apps.docs/databases/DocList.db'.
08-30 17:09:38.622  4727  4873 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.622  4727  4873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:38.622  4727  4873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:38.622  4727  4873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:38.622  4727  4873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:38.622  4727  4873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:38.622  4727  4873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:38.622  4727  4873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:38.622  4727  4873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:38.622  4727  4873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:38.622  4727  4873 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:38.622  4727  4873 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:38.622  4727  4873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:38.622  4727  4873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:38.622  4727  4873 E SQLiteDatabase: 	at ahx.getWritableDatabase(PG:238)
08-30 17:09:38.622  4727  4873 E SQLiteDatabase: 	at ahn.a(PG:1527)
08-30 17:09:38.622  4727  4873 E SQLiteDatabase: 	at heh$a.a(PG:125)
08-30 17:09:38.622  4727  4873 E SQLiteDatabase: 	at ahp.run(PG:542)
08-30 17:09:38.623  4727  4873 E CAKEMIX_CRASHED: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.623  4727  4873 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:38.623  4727  4873 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:38.623  4727  4873 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:38.623  4727  4873 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:38.623  4727  4873 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:38.623  4727  4873 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:38.623  4727  4873 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:38.623  4727  4873 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:38.623  4727  4873 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:38.623  4727  4873 E CAKEMIX_CRASHED: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:38.623  4727  4873 E CAKEMIX_CRASHED: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:38.623  4727  4873 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:38.623  4727  4873 E CAKEMIX_C,RASHED: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:38.623  4727  4873 E CAKEMIX_CRASHED: 	at ahx.getWritableDatabase(PG:238)
08-30 17:09:38.623  4727  4873 E CAKEMIX_CRASHED: 	at ahn.a(PG:1527)
08-30 17:09:38.623  4727  4873 E CAKEMIX_CRASHED: 	at heh$a.a(PG:125)
08-30 17:09:38.623  4727  4873 E CAKEMIX_CRASHED: 	at ahp.run(PG:542)
08-30 17:09:38.636  4847  4847 I GservicesProvider: Gservices pushing to system: true; secure/global: true
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:38.648  4847  4847 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:38.648  4847  4847 D AndroidRuntime: Shutting down VM
08-30 17:09:38.652  4847  4847 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:38.652  4847  4847 E AndroidRuntime: Process: com.google.process.gapps, PID: 4847
08-30 17:09:38.652  4847  4847 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:38.652  4847  4847 E AndroidRuntime: 	... 10 more
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/reminders.db'.
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:421)
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:1017)
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:238)
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:491)
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:434)
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at com.google.android.gms.reminders.a.a.a(SourceFile:64)
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:45)
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:234)
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 17:09:38.654  4706  4862 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:09:38.660  4727  4772 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 17:09:38.661   875  1713 W ActivityManager: Process com.google.process.gapps has crashed too many times: killing!
08-30 17:09:38.662   875  1713 I ActivityManager: Killing 4847:com.google.process.gapps/u0a11 (adj 5): crash
08-30 17:09:38.663   875  4876 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:38.663   875  4876 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop169.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:38.663   875  4876 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:38.663   875  4876 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:38.663   875  4876 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:38.663   875  4876 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:38.663   875  4876 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:38.663   875  4876 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:38.663   875  4876 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:38.663   875  4876 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:38.663   875  4876 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:38.663   875  4876 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:38.663   875  4876 E DropBoxManagerService: 	... 5 more
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:38.679  4863  4863 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:38.679  4863  4863 D AndroidRuntime: Shutting down VM
,08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: Couldn't open reminders.db for writing (will try read-only):
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:421)
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at android.content.ContentProvider.query(ContentProvider.java:1017)
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:238)
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:491)
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:434)
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.a.a.a(SourceFile:64)
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:45)
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:234)
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 17:09:38.702  4706  4862 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-30 17:09:38.723   875   885 W ActivityManager: Unable to launch app com.google.android.gsf/10011 for provider com.google.android.gsf.gservices: launching app became null
08-30 17:09:38.723  4706  4861 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
,08-30 17:09:38.734  4706  4861 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-30 17:09:38.735  4706  4861 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-30 17:09:38.715  4706  4862 W SQLiteOpenHelper: Opened reminders.db in read-only mode
,08-30 17:09:38.758   875  1713 I ActivityManager: Start proc 4880:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,08-30 17:09:38.761   875  2211 I ActivityManager: START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
,08-30 17:09:38.775  4727  4772 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-30 17:09:38.790  4727  4873 I Process : Sending signal. PID: 4727 SIG: 9
,08-30 17:09:38.790   875  2068 W ActivityManager: Spurious death for ProcessRecord{349c8ee 4880:com.google.process.gapps/u0a11}, curProc for 4847: null
,08-30 17:09:38.793  4706  4861 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-30 17:09:38.793  4863  4863 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:38.793  4863  4863 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4863
08-30 17:09:38.793  4863  4863 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:38.793  4863  4863 E AndroidRuntime: 	... 10 more
08-30 17:09:38.794  4706  4861 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-30 17:09:38.799   875  1399 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 4160)
08-30 17:09:38.800   875  1399 W ActivityManager: Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
08-30 17:09:38.800   875  1399 W ActivityManager: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
08-30 17:09:38.800   875  1399 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 17:09:38.800   875  1399 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
08-30 17:09:38.800   875  1399 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:826)
08-30 17:09:38.800   875  1399 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1284)
08-30 17:09:38.800   875  1399 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1384)
08-30 17:09:38.800   875  1399 W ActivityManager: 	at com.android.server.am.ActivityStack.ensureActivitiesVisibleLocked(ActivityStack.java:1324)
08-30 17:09:38.800   875  1399 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.ensureActivitiesVisibleLocked(ActivityStackSupervisor.java:3305)
08-30 17:09:38.800   875  1399 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.attachApplicationLocked(ActivityStackSupervisor.java:638)
08-30 17:09:38.800   875  1399 W ActivityManager: 	at com.android.server.am.ActivityManagerService.attachApplicationLocked(ActivityManagerService.java:6187)
08-30 17:09:38.800   875  1399 W ActivityManager: 	at com.android.server.am.ActivityManagerService.attachApplication(ActivityManagerService.java:6250)
08-30 17:09:38.800   875  1399 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:507)
08-30 17:09:38.800   875  1399 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
08-30 17:09:38.800   875  1399 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:453)
,08-30 17:09:38.803  4706  4894 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/plus.db'.
08-30 17:09:38.803  4706  4894 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.803  4706  4894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:38.803  4706  4894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:38.803  4706  4894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:38.803  4706  4894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:38.803  4706  4894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:38.803  4706  4894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:38.803  4706  4894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:38.803  4706  4894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:38.803  4706  4894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:38.803  4706  4894 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:38.803  4706  4894 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:38.803  4706  4894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:38.803  4706  4894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:38.803  4706  4894 E SQLiteDatabase: 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
08-30 17:09:38.803  4706  4894 E SQLiteDatabase: 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
08-30 17:09:38.803  4706  4894 E SQLiteDatabase: 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
08-30 17:09:38.803  4706  4894 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
08-30 17:09:38.803  4706  4894 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 17:09:38.803  4706  4894 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:234)
08-30 17:09:38.803  4706  4894 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 17:09:38.803  4706  4894 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 17:09:38.803  4706  4894 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: FATAL EXCEPTION: AsyncTask #2
08-30 17:09:38.804  4706  4894 E AndroidRuntime: Process: com.google.android.gms, PID: 4706
08-30 17:09:38.804  4706  4894 E AndroidRuntime: java.lang.RuntimeException: An error occurred while executing doInBackground()
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	at android.os.AsyncTask$3.done(AsyncTask.java:309)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:354)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:223)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:234)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 17:09:38.804  4706  4894 E And,roidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 17:09:38.804  4706  4894 E AndroidRuntime: 	... 4 more
,08-30 17:09:38.884   875  1399 I ActivityManager: Start proc 4896:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
,08-30 17:09:38.899  4706  4861 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-30 17:09:38.900  4706  4861 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-30 17:09:38.901   875  4906 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:38.901   875  4906 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop171.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:38.901   875  4906 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:38.901   875  4906 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:38.901   875  4906 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:38.901   875  4906 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:38.901   875  4906 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:38.901   875  4906 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:38.901   875  4906 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:38.901   875  4906 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:38.901   875  4906 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:38.901   875  4906 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:38.901   875  4906 E DropBoxManagerService: 	... 5 more
,08-30 17:09:38.902   875  4905 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:38.902   875  4905 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop170.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:38.902   875  4905 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:38.902   875  4905 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:38.902   875  4905 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:38.902   875  4905 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:38.902   875  4905 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:38.902   875  4905 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:38.902   875  4905 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:38.902   875  4905 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:38.902   875  4905 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:38.902   875  4905 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:38.902   875  4905 E DropBoxManagerService: 	... 5 more
,08-30 17:09:38.907   875   888 I ActivityManager: Start proc 4909:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
08-30 17:09:38.911   875  2071 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 17:09:38.921  4863  4863 I Process : Sending signal. PID: 4863 SIG: 9
08-30 17:09:38.921   875  2210 W ActivityManager: Spurious death for ProcessRecord{1b30d11 4896:com.google.android.apps.docs/u0a46}, curProc for 4727: null
08-30 17:09:38.922   279   279 E lowmemorykiller: Error writing /proc/4863/oom_score_adj; errno=22
08-30 17:09:38.934  4896  4896 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
08-30 17:09:38.948   875  2071 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4863) has died
,08-30 17:09:38.960  4706  4894 I Process : Sending signal. PID: 4706 SIG: 9
,08-30 17:09:39.003   875  2055 W InputMethodManagerService: Client died receiving input method InputBindResult{com.android.internal.view.IInputMethodSession$Stub$Proxy@a96687c com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME sequence:4 userActionNotificationSequenceNumber:1}
,08-30 17:09:39.005  4880  4880 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-30 17:09:39.023  4909  4909 W System  : ClassLoader referenced unknown path: /system/app/KeyChain/lib/arm
,08-30 17:09:39.025  4880  4880 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-30 17:09:39.027  4880  4880 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:39.027  4880  4880 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:09:39.027  4880  4880 D AndroidRuntime: Shutting down VM
08-30 17:09:39.028  4880  4880 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:39.028  4880  4880 E AndroidRuntime: Process: com.google.process.gapps, PID: 4880
08-30 17:09:39.028  4880  4880 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:39.028  4880  4880 E AndroidRuntime: 	... 10 more
08-30 17:09:39.034  4909  4909 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
08-30 17:09:39.035   875  4926 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:39.035   875  4926 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop172.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:39.035   875  4926 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:39.035   875  4926 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:39.035   875  4926 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:39.035   875  4926 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:39.035   875  4926 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:39.035   875  4926 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:39.035   875  4926 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:39.035   875  4926 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:39.035   875  4926 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:39.035   875  4926 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:39.035   875  4926 E DropBoxManagerService: 	... 5 more
,08-30 17:09:39.050   875  1405 I ActivityManager: Start proc 4927:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
08-30 17:09:39.051  4880  4880 I Process : Sending signal. PID: 4880 SIG: 9
08-30 17:09:39.068   875  2224 I ActivityManager: Process com.google.android.gms (pid 4706) has died
08-30 17:09:39.068   875  2224 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{9fbe78d u0 com.google.android.gms/.feedback.FeedbackAsyncService}
08-30 17:09:39.068   875  2224 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{2830191 u0 com.google.android.gms/.feedback.FeedbackService}
08-30 17:09:39.091  4909  4932 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.keychain/databases/grants.db'.
08-30 17:09:39.091  4909  4932 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.091  4909  4932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:39.091  4909  4932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:39.091  4909  4932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:39.091  4909  4932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:39.091  4909  4932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:39.091  4909  4932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:39.091  4909  4932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:39.091  4909  4932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:39.091  4909  4932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:39.091  4909  4932 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:39.091  4909  4932 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:39.091  4909  4932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:39.091  4909  4932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:39.091  4909  4932 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-30 17:09:39.091  4909  4932 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-30 17:09:39.091  4909  4932 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 17:09:39.091  4909  4932 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:39.091  4909  4932 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:39.091  4909  4932 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:09:39.097  4909  4932 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-30 17:09:39.097  4909  4932 E AndroidRuntime: Process: com.android.keychain, PID: 4909
08-30 17:09:39.097  4909  4932 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.097  4909  4932 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:39.097  4909  4932 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:39.097  4909  4932 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:39.097  4909  4932 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:39.097  4909  4932 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:39.097  4909  4932 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:39.097  4909  4932 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:39.097  4909  4932 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:39.097  4909  4932 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:39.097  4909  4932 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:39.097  4909  4932 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:39.097  4909  4932 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:39.097  4909  4932 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:39.097  4909  4932 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-30 17:09:39.097  4909  4932 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-30 17:09:39.097  4909  4932 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 17:09:39.097  4909  4932 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:39.097  4909  4932 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:39.097  4909  4932 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:09:39.104  4909  4932 I Process : Sending signal. PID: 4909 SIG: 9
,08-30 17:09:39.104   875  4940 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:39.104   875  4940 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop173.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:39.104   875  4940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:39.104   875  4940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:39.104   875  4940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:39.104   875  4940 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:39.104   875  4940 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:39.104   875  4940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:39.104   875  4940 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:39.104   875  4940 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:39.104   875  4940 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:39.104   875  4940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:39.104   875  4940 E DropBoxManagerService: 	... 5 more
,08-30 17:09:39.110   875  1399 I ActivityManager: Process com.google.process.gapps (pid 4880) has died
,08-30 17:09:39.110   875  1399 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 18704ms
08-30 17:09:39.110   875  1399 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 28704ms
,08-30 17:09:39.144   875  1404 I ActivityManager: Process com.android.keychain (pid 4909) has died
,08-30 17:09:39.144   875  1404 W ActivityManager: Scheduling restart of crashed service com.android.keychain/.KeyChainService in 38671ms
,08-30 17:09:39.155  4896  4924 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-30 17:09:39.155  4896  4924 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 17:09:39.155  4896  4924 I GAv4    :   adb logcat -s GAv4
,08-30 17:09:39.168  4896  4924 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 17:09:39.174  4896  4924 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-30 17:09:39.177  4896  4949 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/user/0/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
08-30 17:09:39.179  4896  4948 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.apps.docs/databases/DocList.db'.
08-30 17:09:39.179  4896  4948 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.179  4896  4948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:39.179  4896  4948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:39.179  4896  4948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:39.179  4896  4948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:39.179  4896  4948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:39.179  4896  4948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:39.179  4896  4948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:39.179  4896  4948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:39.179  4896  4948 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:39.179  4896  4948 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:39.179  4896  4948 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:39.179  4896  4948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:39.179  4896  4948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:39.179  4896  4948 E SQLiteDatabase: 	at ahx.getWritableDatabase(PG:238)
08-30 17:09:39.179  4896  4948 E SQLiteDatabase: 	at ahn.a(PG:1527)
08-30 17:09:39.179  4896  4948 E SQLiteDatabase: 	at heh$a.a(PG:125)
08-30 17:09:39.179  4896  4948 E SQLiteDatabase: 	at ahp.run(PG:542)
08-30 17:09:39.181  4896  4949 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/user/0/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
08-30 17:09:39.184  4896  4948 E CAKEMIX_CRASHED: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.184  4896  4948 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:39.184  4896  4948 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:39.184  4896  4948 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:39.184  4896  4948 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:39.184  4896  4948 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:39.184  4896  4948 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:39.184  4896  4948 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:39.184  4896  4948 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:39.184  4896  4948 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:39.184  4896  4948 E CAKEMIX_CRASHED: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:39.184  4896  4948 E CAKEMIX_CRASHED: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:39.184  4896  4948 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:39.184  4896  4948 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:39.184  4896  4948 E CAKEMIX_CRASHED: 	at ahx.getWritableDatabase(PG:238)
08-30 17:09:39.184  4896  4948 E CAKEMIX_CRASHED: 	at ahn.a(PG:1527)
08-30 17:09:39.184  4896  4948 E CAKEMIX_CRASHED: 	at heh$a.a(PG:125)
08-30 17:09:39.184  4896  4948 E CAKEMIX_CRASHED: 	at ahp.run(PG:542)
,08-30 17:09:39.194  4896  4924 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.327.05.36
,08-30 17:09:39.204   875  2209 I ActivityManager: START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
,08-30 17:09:39.206  4896  4950 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
08-30 17:09:39.206  4896  4948 I Process : Sending signal. PID: 4896 SIG: 9
,08-30 17:09:39.246   875  1999 I ActivityManager: Process com.google.android.apps.docs (pid 4896) has died
,08-30 17:09:39.264   875  1999 I ActivityManager: Start proc 4954:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
,08-30 17:09:39.282   875   886 I ActivityManager: Start proc 4966:android.process.acore/u0a5 for content provider com.android.providers.contacts/.ContactsProvider2
,08-30 17:09:39.318   875   875 I ActivityManager: Start proc 4980:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
08-30 17:09:39.319  4966  4966 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-30 17:09:39.319  4954  4954 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,08-30 17:09:39.362  4980  4980 W System  : ClassLoader referenced unknown path: /system/app/DocumentsUI/lib/arm
,08-30 17:09:39.402  4980  4980 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.documentsui/databases/recents.db'.
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:398)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1398)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:39.402  4980  4980 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:09:39.415  1375  2456 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10000)] disk I/O error
,08-30 17:09:39.425  1375  2456 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
08-30 17:09:39.425  1375  2456 E AndroidRuntime: Process: android.process.media, PID: 1375
08-30 17:09:39.425  1375  2456 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 17:09:39.425  1375  2456 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 17:09:39.425  1375  2456 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 17:09:39.425  1375  2456 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 17:09:39.425  1375  2456 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 17:09:39.425  1375  2456 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 17:09:39.425  1375  2456 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1215)
08-30 17:09:39.425  1375  2456 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 17:09:39.425  1375  2456 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 17:09:39.425  1375  2456 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:117)
08-30 17:09:39.425  1375  2456 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.-wrap1(DownloadReceiver.java)
08-30 17:09:39.425  1375  2456 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:85)
08-30 17:09:39.425  1375  2456 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 17:09:39.425  1375  2456 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 17:09:39.425  1375  2456 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:39.425  1375  2456 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:09:39.434  1375  2456 I Process : Sending signal. PID: 1375 SIG: 9
08-30 17:09:39.436   875  4997 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:39.436   875  4997 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop174.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:39.436   875  4997 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:39.436   875  4997 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:39.436   875  4997 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:39.436   875  4997 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:39.436   875  4997 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:39.436   875  4997 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:39.436   875  4997 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:39.436   875  4997 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:39.436   875  4997 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:39.436   875  4997 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:39.436   875  4997 E DropBoxManagerService: 	... 5 more
,08-30 17:09:39.446  4980  4980 D AndroidRuntime: Shutting down VM
08-30 17:09:39.449  4980  4980 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:39.449  4980  4980 E AndroidRuntime: Process: com.android.documentsui, PID: 4980
08-30 17:09:39.449  4980  4980 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:398)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1398)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	at android.app.Act,ivityThread.handleReceiver(ActivityThread.java:2725)
08-30 17:09:39.449  4980  4980 E AndroidRuntime: 	... 8 more
08-30 17:09:39.451  4966  4966 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-30 17:09:39.452  4980  4980 I Process : Sending signal. PID: 4980 SIG: 9
,08-30 17:09:39.453   875  5001 E DropBoxManagerService: Can't write: system_app_crash
,08-30 17:09:39.453   875  5001 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop175.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:39.453   875  5001 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:39.453   875  5001 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:39.453   875  5001 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:39.453   875  5001 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:39.453   875  5001 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:39.453   875  5001 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:39.453   875  5001 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:39.453   875  5001 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:39.453   875  5001 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:39.453   875  5001 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:39.453   875  5001 E DropBoxManagerService: 	... 5 more
,08-30 17:09:39.493   875  2055 I ActivityManager: Start proc 5004:com.google.android.gms/u0a11 for broadcast com.google.android.gms/.herrevad.receivers.CaptivePortalReceiver
,08-30 17:09:39.499  4954  4992 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:,
08-30 17:09:39.499  4954  4992 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 17:09:39.499  4954  4992 I GAv4    :   adb logcat -s GAv4
,08-30 17:09:39.504   875  1344 E TaskPersister: Unable to open android.util.AtomicFile@c6cf97b for persisting. java.io.IOException: Couldn't create directory /data/system/recent_tasks/17_task.xml
08-30 17:09:39.509  4954  4992 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 17:09:39.512  4954  4992 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-30 17:09:39.513  4954  5015 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/user/0/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,08-30 17:09:39.513  4954  5015 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/user/0/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
08-30 17:09:39.520   875  1405 I ActivityManager: Process android.process.media (pid 1375) has died
08-30 17:09:39.521   875  1405 W ActivityManager: Scheduling restart of crashed service com.android.providers.media/.MtpService in 391150ms
,08-30 17:09:39.526  4954  5017 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 17:09:39.527  4954  5015 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/user/0/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,08-30 17:09:39.534  4954  4992 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.327.05.36
,08-30 17:09:39.536  4954  5021 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.apps.docs/databases/DocList.db'.
08-30 17:09:39.536  4954  5021 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.536  4954  5021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:39.536  4954  5021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:39.536  4954  5021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:39.536  4954  5021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:39.536  4954  5021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:39.536  4954  5021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:39.536  4954  5021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:39.536  4954  5021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:39.536  4954  5021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:39.536  4954  5021 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:39.536  4954  5021 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:39.536  4954  5021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:39.536  4954  5021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:39.536  4954  5021 E SQLiteDatabase: 	at ahx.getWritableDatabase(PG:238)
08-30 17:09:39.536  4954  5021 E SQLiteDatabase: 	at ahn.a(PG:1527)
08-30 17:09:39.536  4954  5021 E SQLiteDatabase: 	at heh$a.a(PG:125)
08-30 17:09:39.536  4954  5021 E SQLiteDatabase: 	at ahp.run(PG:542)
,08-30 17:09:39.538  4954  5017 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.apps.docs/databases/google_analytics_v4.db'.
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: 	at fek$a.getWritableDatabase(Unknown Source)
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: 	at fek.g(Unknown Source)
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: 	at fek.a(Unknown Source)
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: 	at fek.e(Unknown Source)
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: 	at fem.b(Unknown Source)
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: 	at fep.run(Unknown Source)
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:09:39.538  4954  5017 E SQLiteDatabase: 	at ghj$c.run(Unknown Source)
08-30 17:09:39.538  4954  5017 E GAv4    : Opening the database failed, dropping the table and recreating it
08-30 17:09:39.539  4954  5015 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/user/0/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.apps.docs/databases/google_analytics_v4.db'.
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: 	at android.database.sqlite.,SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: 	at fek$a.getWritableDatabase(Unknown Source)
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: 	at fek.g(Unknown Source)
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: 	at fek.a(Unknown Source)
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: 	at fek.e(Unknown Source)
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: 	at fem.b(Unknown Source)
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: 	at fep.run(Unknown Source)
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:09:39.539  4954  5017 E SQLiteDatabase: 	at ghj$c.run(Unknown Source)
08-30 17:09:39.539  4954  5017 E GAv4    : Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.540  4954  5015 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/user/0/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
08-30 17:09:39.540  4954  5017 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.541  4954  5015 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/user/0/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
08-30 17:09:39.541  4954  5017 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.541  4954  5015 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/user/0/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xm,l.bak
08-30 17:09:39.543  4966  4994 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 17:09:39.543  4966  4994 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.543  4966  4994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:39.543  4966  4994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:39.543  4966  4994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:39.543  4966  4994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:39.543  4966  4994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:39.543  4966  4994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:39.543  4966  4994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:39.543  4966  4994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:39.543  4966  4994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:39.543  4966  4994 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:39.543  4966  4994 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:39.543  4966  4994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:39.543  4966  4994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:09:39.543  4966  4994 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 17:09:39.543  4966  4994 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 17:09:39.543  4966  4994 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 17:09:39.543  4966  4994 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 17:09:39.543  4966  4994 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:39.543  4966  4994 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:39.543  4966  4994 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:09:39.552  4966  4994 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-30 17:09:39.552  4966  4994 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.552  4966  4994 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:39.552  4966  4994 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:39.552  4966  4994 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:39.552  4966  4994 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:39.552  4966  4994 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:39.552  4966  4994 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:39.552  4966  4994 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:39.552  4966  4994 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:39.552  4966  4994 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:39.552  4966  4994 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:39.552  4966  4994 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:39.552  4966  4994 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:39.552  4966  4994 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:09:39.552  4966  4994 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 17:09:39.552  4966  4994 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 17:09:39.552  4966  4994 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 17:09:39.552  4966  4994 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 17:09:39.552  4966  4994 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:39.552  4966  4994 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:39.552  4966  4994 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:09:39.554   875   885 I ActivityManager: Start proc 5022:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
08-30 17:09:39.560  5004  5004 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-30 17:09:39.575  5004  5004 I MultiDex: VM with version 2.1.0 has multidex support
08-30 17:09:39.575  5004  5004 I MultiDex: install
08-30 17:09:39.575  5004  5004 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 17:09:39.596  5022  5022 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-30 17:09:39.602  5022  5022 I GservicesProvider: Gservices pushing to system: true; secure/global: true
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:39.604  5022  5022 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:39.604  5022  5022 D AndroidRuntime: Shutting down VM
08-30 17:09:39.605  5022  5022 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:39.605  5022  5022 E AndroidRuntime: Process: com.google.process.gapps, PID: 5022
08-30 17:09:39.605  5022  5022 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:39.605  5022  5022 E AndroidRuntime: 	... 10 more
,08-30 17:09:39.609  5022  5022 I Process : Sending signal. PID: 5022 SIG: 9
08-30 17:09:39.615   875  5038 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:39.615   875  5038 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop176.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:39.615   875  5038 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:39.615   875  5038 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:39.615   875  5038 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:39.615   875  5038 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:39.615   875  5038 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:39.615   875  5038 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:39.615   875  5038 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:39.615   875  5038 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:39.615   875  5038 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:39.615   875  5038 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:39.615   875  5038 E DropBoxManagerService: 	... 5 more
08-30 17:09:39.633  4966  4994 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-30 17:09:39.635   875  1405 I ActivityManager: Process com.google.process.gapps (pid 5022) has died
08-30 17:09:39.635   875  1405 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{bde3c95 u0 com.google.android.gms/.config.ConfigService}
08-30 17:09:39.635   875  1405 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{4636938 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
08-30 17:09:39.643  4954  4954 E ErrorNotificationActivity: Google Drive has stopped unexpectedly. Please provide additional details to help us diagnose the issue.
08-30 17:09:39.646  4966  4994 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
08-30 17:09:39.646  4966  4994 E AndroidRuntime: Process: android.process.acore, PID: 4966
08-30 17:09:39.646  4966  4994 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-30 17:09:39.646  4966  4994 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 17:09:39.646  4966  4994 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 17:09:39.646  4966  4994 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 17:09:39.646  4966  4994 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 17:09:39.646  4966  4994 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1676)
08-30 17:09:39.646  4966  4994 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1605)
08-30 17:09:39.646  4966  4994 E AndroidRuntime: 	at com.android.providers.contacts.ContactsDatabaseHelper.onOpen(ContactsDatabaseHelper.java:1084)
08-30 17:09:39.646  4966  4994 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:266)
08-30 17:09:39.646  4966  4994 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:09:39.646  4966  4994 E AndroidRuntime: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 17:09:39.646  4966  4994 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 17:09:39.646  4966  4994 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 17:09:39.646  4966  4994 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 17:09:39.646  4966  4994 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:39.646  4966  4994 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:39.646  4966  4994 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:09:39.646   875  1405 I ActivityManager: Start proc 5044:com.google.process.gapps/u0a11 for restart com.google.process.gapps
08-30 17:09:39.647   875  1399 I ActivityManager: Process com.android.documentsui (pid 4980) has died
08-30 17:09:39.651  4966  4994 I Process : Sending signal. PID: 4966 SIG: 9
08-30 17:09:39.652   875  5051 E DropBoxManagerService: Can't write: system_app_crash
,08-30 17:09:39.652   875  5051 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop177.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:39.652   875  5051 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:39.652   875  5051 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:39.652   875  5051 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:39.652   875  5051 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:39.652   875  5051 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:39.652   875  5051 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:39.652   875  5051 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:39.652   875  5051 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:39.652   875  5051 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:39.652   875  5051 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:39.652   875  5051 E DropBoxManagerService: 	... 5 more
,08-30 17:09:39.676  5044  5044 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-30 17:09:39.679  4954  5059 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 17:09:39.682  5044  5044 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-30 17:09:39.684  5044  5044 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:39.684  5044  5044 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:39.685   875  2006 I ActivityManager: Process android.process.acore (pid 4966) has died
08-30 17:09:39.685  5044  5044 D AndroidRuntime: Shutting down VM
,08-30 17:09:39.686  5044  5044 E AndroidRuntime: FATAL EXCEPTION: main
,08-30 17:09:39.686  5044  5044 E AndroidRuntime: Process: com.google.process.gapps, PID: 5044
08-30 17:09:39.686  5044  5044 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:39.6,86  5044  5044 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:39.686  5044  5044 E AndroidRuntime: 	... 10 more
,08-30 17:09:39.688   875  1703 W ActivityManager: Process com.google.process.gapps has crashed too many times: killing!
,08-30 17:09:39.689   875  1703 I ActivityManager: Killing 5044:com.google.process.gapps/u0a11 (adj 0): crash
,08-30 17:09:39.689   875  5060 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:39.689   875  5060 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop178.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:39.689   875  5060 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:39.689   875  5060 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:39.689   875  5060 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:39.689   875  5060 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:39.689   875  5060 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:39.689   875  5060 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:39.689   875  5060 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:39.689   875  5060 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:39.689   875  5060 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:39.689   875  5060 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:39.689   875  5060 E DropBoxManagerService: 	... 5 more
,08-30 17:09:39.738   875   885 W ActivityManager: Unable to launch app com.google.android.gsf/10011 for provider com.google.android.gsf.gservices: launching app became null
,08-30 17:09:39.738   875  1404 W ActivityManager: Unable to launch app com.google.android.gsf/10011 for provider com.google.android.gsf.gservices: launching app became null
08-30 17:09:39.738  4927  4978 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
08-30 17:09:39.739  5004  5004 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
,08-30 17:09:39.776   875  1703 I ActivityManager: Start proc 5062:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,08-30 17:09:39.777  5004  5004 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-30 17:09:39.777   875  1713 W ActivityManager: Spurious death for ProcessRecord{85528e3 5062:com.google.process.gapps/u0a11}, curProc for 5044: null
,08-30 17:09:39.799  4954  5075 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.apps.docs/databases/DocList.db'.
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at ahx.getWritableDatabase(PG:238)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at ahn.a(PG:1527)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at heh$a.a(PG:125)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at ahl.c(PG:140)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at ahl.a(PG:359)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at ahl.a(PG:346)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at ajh.c(PG:862)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at alj.doInBackground(PG:1063)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:234)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 17:09:39.799  4954  5075 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: Failed to query Account138 object
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at ahx.getWritableDatabase(PG:238)
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at ahn.a(PG:1527)
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at heh$a.a(PG:125)
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at ahl.c(PG:140),
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at ahl.a(PG:359)
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at ahl.a(PG:346)
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at ajh.c(PG:862)
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at alj.doInBackground(PG:1063)
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:234)
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 17:09:39.799  4954  5075 E AbstractDatabaseInstance: 	at java.lang.Thread.run(Thread.java:818)
,08-30 17:09:39.806  5004  5004 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-30 17:09:39.816  5062  5062 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-30 17:09:39.822  5062  5062 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-30 17:09:39.824  5062  5062 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:39.824  5062  5062 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:09:39.824  5062  5062 D AndroidRuntime: Shutting down VM
08-30 17:09:39.825  5062  5062 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:09:39.825  5062  5062 E AndroidRuntime: Process: com.google.process.gapps, PID: 5062
08-30 17:09:39.825  5062  5062 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	,at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:39.825  5062  5062 E AndroidRuntime: 	... 10 more
,08-30 17:09:39.827  5062  5062 I Process : Sending signal. PID: 5062 SIG: 9
,08-30 17:09:39.828   875  5079 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:09:39.828   875  5079 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop179.tmp: open failed: EROFS (Read-only file system)
08-30 17:09:39.828   875  5079 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:39.828   875  5079 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:09:39.828   875  5079 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:09:39.828   875  5079 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:09:39.828   875  5079 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:09:39.828   875  5079 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:09:39.828   875  5079 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:39.828   875  5079 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:39.828   875  5079 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:39.828   875  5079 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:39.828   875  5079 E DropBoxManagerService: 	... 5 more
,08-30 17:09:39.841  4954  5059 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 17:09:39.841  4954  5059 I Adreno  : Build Date                       : 10/20/15
08-30 17:09:39.841  4954  5059 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 17:09:39.841  4954  5059 I Adreno  : Local Branch                     : M14
08-30 17:09:39.841  4954  5059 I Adreno  : Remote Branch                    : 
08-30 17:09:39.841  4954  5059 I Adreno  : Remote Branch                    : 
08-30 17:09:39.841  4954  5059 I Adreno  : Reconstruct Branch               : 
,08-30 17:09:39.845  4954  5059 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 17:09:39.879   875  1713 I ActivityManager: Process com.google.process.gapps (pid 5062) has died
,08-30 17:09:39.880   875  1703 W ActivityManager: Unable to launch app com.google.android.gsf/10011 for provider com.google.android.gsf.gservices: launching app became null
,08-30 17:09:39.881  5004  5004 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
,08-30 17:09:39.891  5004  5080 W NativeLibraryUtils: Failed to open lock file
08-30 17:09:39.891  5004  5080 W NativeLibraryUtils: java.io.FileNotFoundException: /data/user/0/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
08-30 17:09:39.891  5004  5080 W NativeLibraryUtils: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:09:39.891  5004  5080 W NativeLibraryUtils: 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
08-30 17:09:39.891  5004  5080 W NativeLibraryUtils: 	at com.google.android.gms.common.util.ay.b(SourceFile:325)
08-30 17:09:39.891  5004  5080 W NativeLibraryUtils: 	at com.google.android.gms.common.app.a.run(SourceFile:171)
08-30 17:09:39.891  5004  5080 W NativeLibraryUtils: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:09:39.891  5004  5080 W NativeLibraryUtils: 	at libcore.io.Posix.open(Native Method)
08-30 17:09:39.891  5004  5080 W NativeLibraryUtils: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:09:39.891  5004  5080 W NativeLibraryUtils: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:09:39.891  5004  5080 W NativeLibraryUtils: 	... 3 more
,08-30 17:09:39.914   875  1713 I ActivityManager: Start proc 5083:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,08-30 17:09:39.976  5083  5083 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-30 17:09:40.016   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
08-30 17:09:40.017  5083  5083 I GservicesProvider: Gservices pushing to system: true; secure/global: true
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:09:40.019  5083  5083 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:09:40.019  5083  5083 D AndroidRuntime:
```
