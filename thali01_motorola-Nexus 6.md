#### Test 8362733705cfec3_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-12 13:58:10.891  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:58:10.898  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 13:58:10.900  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 13:58:10.939  1523  2312 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-12 13:58:10.939  1523  2312 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 13:58:10.940  1523  2312 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:58:10.940  1523  2312 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-12 13:58:10.973  3511  3511 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-12 13:58:10.973  3511  3511 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 13:58:10.973  3511  3511 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
09-12 13:58:11.500  3832  3832 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-12 13:58:11.506  3832  3832 D AndroidRuntime: CheckJNI is OFF
09-12 13:58:11.549  3832  3832 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-12 13:58:11.600  3832  3832 I Radio-JNI: register_android_hardware_Radio DONE
09-12 13:58:11.622  3832  3832 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-12 13:58:11.629   874  1906 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-12 13:58:11.682   874  1906 I ActivityManager: Start proc 3841:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-12 13:58:11.685  3832  3832 D AndroidRuntime: Shutting down VM
09-12 13:58:11.806  3841  3841 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-12 13:58:11.840  3841  3841 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-12 13:58:11.848  3841  3841 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2284-2287)
09-12 13:58:11.848  3841  3841 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 13:58:11.865  3841  3841 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5c5fed}
09-12 13:58:11.865  3841  3841 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 13:58:11.865  3841  3841 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-12 13:58:11.872  3841  3841 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-12 13:58:11.873  3841  3841 E SysUtils: ApplicationContext is null in ApplicationStatus
09-12 13:58:11.893  3841  3841 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-12 13:58:11.914  3841  3841 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 13:58:11.914  3841  3841 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 13:58:11.915  3841  3841 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 13:58:11.915  3841  3841 I Adreno  : Build Date                       : 10/20/15
09-12 13:58:11.915  3841  3841 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 13:58:11.915  3841  3841 I Adreno  : Local Branch                     : M14
09-12 13:58:11.915  3841  3841 I Adreno  : Remote Branch                    : 
09-12 13:58:11.915  3841  3841 I Adreno  : Remote Branch                    : 
09-12 13:58:11.915  3841  3841 I Adreno  : Reconstruct Branch               : 
,09-12 13:58:11.978   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fc9a024:true
,09-12 13:58:12.023  3841  3841 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-12 13:58:12.039  3841  3841 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-12 13:58:12.112  3841  3879 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-12 13:58:12.128  3841  3866 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-12 13:58:12.170  3841  3879 I OpenGLRenderer: Initialized EGL, version 1.4
,09-12 13:58:12.247   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +489ms (total +583ms)
,09-12 13:58:12.258  1876  1876 I Keyboard.Facilitator: onFinishInput()
,09-12 13:58:12.307  3841  3841 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3841
,09-12 13:58:12.456  3841  3841 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-12 13:58:12.643  3841  3882 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1685325520
,09-12 13:58:12.653  3841  3882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-12 13:58:12.653  3841  3882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-12 13:58:12.653  3841  3882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-12 13:58:12.653  3841  3882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-12 13:58:12.653  3841  3882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-12 13:58:12.654  3841  3882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@721a848 added. We now have 1 listener(s)
,09-12 13:58:12.659  3841  3882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-12 13:58:12.659  3841  3882 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 13:58:12.660  3841  3882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:58:12.660  3841  3882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 13:58:12.664  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-12 13:58:12.664  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-12 13:58:12.664  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-12 13:58:12.664  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-12 13:58:12.664  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-12 13:58:12.664  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-12 13:58:12.664  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-12 13:58:12.664  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-12 13:58:12.664  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-12 13:58:12.664  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-12 13:58:12.664  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-12 13:58:12.664  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-12 13:58:12.664  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-12 13:58:12.664  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-12 13:58:12.664  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48d02c7 added. We now have 1 listener(s)
09-12 13:58:12.665  3841  3882 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:58:12.669   874  1310 D WifiService: New client listening to asynchronous messages
09-12 13:58:12.671  3841  3882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 13:58:12.671  3841  3882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-12 13:58:12.671  3841  3882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-12 13:58:12.671  3841  3882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-12 13:58:12.671  3841  3882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-12 13:58:12.677  3841  3882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:58:12.677  3841  3882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-12 13:58:12.683  3841  3882 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-12 13:58:12.683  3841  3882 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:58:12.683  3841  3882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:12.683  3841  3882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:12.683  3841  3882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:12.683  3841  3882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:12.683  3841  3882 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:12.683  3841  3882 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:58:12.683  3841  3882 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:58:12.683  3841  3882 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-12 13:58:12.683  3841  3882 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:58:12.684  3841  3882 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 13:58:12.688  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:12.690  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:12.714  3841  3841 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-12 13:58:13.535  3841  3888 W jxcore-log: Initializing JXcore engine,
09-12 13:58:13.535  3841  3888 W jxcore-log: JXcore engine is ready
,09-12 13:58:13.577  3888  3888 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8927 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-12 13:58:13.577  3888  3888 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[13349]" dev="sockfs" ino=13349 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-12 13:58:13.577  3888  3888 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-12 13:58:13.577  3888  3888 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25947]" dev="sockfs" ino=25947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-12 13:58:13.603  3841  3888 W jxcore-log: Starting JXcore engine
,09-12 13:58:13.721  3841  3888 W jxcore-log: Platform android
09-12 13:58:13.721  3841  3888 W jxcore-log: 
,09-12 13:58:13.721  3841  3888 W jxcore-log: Process ARCH arm
09-12 13:58:13.721  3841  3888 W jxcore-log: 
,09-12 13:58:13.920  3841  3888 I jxcore-log: JXcore Cordova bridge is ready!
09-12 13:58:13.920  3841  3888 I jxcore-log: 
,09-12 13:58:13.921  3841  3888 W jxcore-log: JXcore engine is started,
,09-12 13:58:13.930  3841  3882 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-12 13:58:13.935  3841  3841 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-12 13:58:16.341  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:58:16.344  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:58:16.373  1523  3821 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-12 13:58:16.373  1523  3821 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-12 13:58:16.373  1523  3821 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 13:58:16.373  1523  3821 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:58:16.388  1523  3821 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 13:58:16.388  1523  3821 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 13:58:16.388  1523  3821 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 13:58:16.388  1523  3821 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 13:58:16.388  1523  3821 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 13:58:16.388  1523  3821 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 13:58:16.388  1523  3821 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 13:58:16.388  1523  3821 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 13:58:16.388  1523  3821 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 13:58:16.388  1523  3821 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 13:58:16.388  1523  3821 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 13:58:16.388  1523  3821 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 13:58:16.388  1523  3821 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 13:58:16.890  1523  3821 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-12 13:58:16.890  1523  3821 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-12 13:58:16.890  1523  3821 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:58:16.890  1523  3821 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:58:16.912  1523  3821 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 13:58:16.912  1523  3821 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 13:58:16.912  1523  3821 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 13:58:16.912  1523  3821 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 13:58:16.912  1523  3821 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 13:58:16.912  1523  3821 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 13:58:16.912  1523  3821 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 13:58:16.912  1523  3821 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 13:58:16.912  1523  3821 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 13:58:16.912  1523  3821 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 13:58:16.912  1523  3821 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 13:58:16.912  1523  3821 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 13:58:16.912  1523  3821 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 13:58:17.229  1523  3821 I art     : Waiting for a blocking GC DisableMovingGc
,09-12 13:58:17.235  1523  3821 I art     : WaitForGcToComplete blocked for 5.717ms for cause DisableMovingGc
09-12 13:58:17.235  1523  3821 I art     : Starting a blocking GC DisableMovingGc
,09-12 13:58:17.373  1523  3821 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-12 13:58:17.374  1523  3821 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-12 13:58:17.374  1523  3821 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 13:58:17.374  1523  3821 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:58:17.385  1523  3821 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 13:58:17.385  1523  3821 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 13:58:17.385  1523  3821 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 13:58:17.385  1523  3821 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 13:58:17.385  1523  3821 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 13:58:17.385  1523  3821 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 13:58:17.385  1523  3821 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 13:58:17.385  1523  3821 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 13:58:17.385  1523  3821 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 13:58:17.385  1523  3821 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 13:58:17.385  1523  3821 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 13:58:17.385  1523  3821 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 13:58:17.385  1523  3821 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 13:58:23.958  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-12 13:58:23.958  3841  3888 I jxcore-log: 
,09-12 13:58:23.960  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-12 13:58:23.960  3841  3888 I jxcore-log: 
,09-12 13:58:23.975  3841  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:58:23.975  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:23.975  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:23.975  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:23.975  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:23.975  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:23.975  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:58:23.975  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:58:23.980  3841  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:58:23.982  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-12 13:58:23.982  3841  3888 I jxcore-log: 
,09-12 13:58:23.984  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-12 13:58:23.984  3841  3888 I jxcore-log: 
,09-12 13:58:24.476  3841  3888 I jxcore-log: Unit Test app is loaded
09-12 13:58:24.476  3841  3888 I jxcore-log: 
,09-12 13:58:24.482  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:58:24.482  3841  3888 I jxcore-log: 
,09-12 13:58:24.486  3841  3888 D executeNativeTests: Running unit tests
,09-12 13:58:24.487  3841  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
09-12 13:58:24.487  3841  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3feb801 added. We now have 2 listener(s)
,09-12 13:58:24.488  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:58:24.488  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:58:24.488  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:58:24.488  3841  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:58:24.488  3841  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14ad6a6 added. We now have 2 listener(s)
09-12 13:58:24.488  3841  3888 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:58:24.489  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 13:58:24.490  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:58:24.498  3841  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:58:24.498  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:24.498  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:24.498  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:24.498  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:24.498  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:24.498  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:58:24.498  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:58:24.499  3841  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:58:24.499  3841  3888 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:58:24.501  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:24.502  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:24.505  3841  3841 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-12 13:58:34.598  3841  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:58:34.598  3841  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69fb2c4 added. We now have 3 listener(s)
,09-12 13:58:34.599  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:58:34.599  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 13:58:34.599  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 13:58:34.599  3841  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 13:58:34.599  3841  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f05ad added. We now have 3 listener(s)
09-12 13:58:34.599  3841  3888 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:58:34.600  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:58:34.602  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:58:34.615  3841  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:58:34.615  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:34.615  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:34.615  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:34.615  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:34.615  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:34.615  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:58:34.615  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:58:34.616  3841  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:34.616  3841  3888 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:58:34.617  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:34.629  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:34.632  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
09-12 13:58:34.632  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 13:58:34.632  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 13:58:34.632  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 13:58:34.634  3841  3888 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-12 13:58:34.634  3841  3888 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-12 13:58:34.634  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-12 13:58:34.634  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 13:58:34.634  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:58:34.634  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
09-12 13:58:34.635  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-12 13:58:34.635  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,09-12 13:58:34.635  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:58:34.635  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
09-12 13:58:34.635  3841  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69fb2c4 removed from the list
,09-12 13:58:34.635  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:58:34.635  3841  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f05ad removed from the list
09-12 13:58:34.636  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:58:34.636  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:58:34.638  3841  3888 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-12 13:58:34.638  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-12 13:58:34.638  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:58:34.638  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-12 13:58:34.638  3841  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69fb2c4 not in the list
,09-12 13:58:34.639  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:58:34.639  3841  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f05ad not in the list
09-12 13:58:34.639  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:58:34.639  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:34.639  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:34.643  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 13:58:34.643  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-12 13:58:34.643  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 13:58:34.643  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 13:58:34.643  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 13:58:34.643  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 13:58:34.643  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 13:58:34.643  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610],
09-12 13:58:34.643  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 13:58:34.643  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 13:58:34.643  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 13:58:34.643  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 13:58:34.643  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-12 13:58:34.644  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 13:58:34.644  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 13:58:34.644  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 13:58:34.644  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 13:58:34.644  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 13:58:34.644  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 13:58:34.644  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810],
09-12 13:58:34.644  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 13:58:34.644  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 13:58:34.644  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 13:58:34.644  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 13:58:34.644  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 13:58:34.644  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410],
09-12 13:58:34.644  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 13:58:34.644  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 13:58:34.644  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 13:58:34.644  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 13:58:34.644  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 13:58:34.644  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:58:34.645  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:34.645  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:34.645  3841  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69fb2c4 not in the list
,09-12 13:58:34.645  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:58:34.645  3841  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f05ad not in the list
09-12 13:58:34.645  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:58:34.645  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:34.645  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:34.645  3841  3888 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-12 13:58:34.648  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:58:34.651  3841  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:58:34.651  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:34.651  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:34.651  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:34.651  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:34.651  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:34.651  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:58:34.651  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:58:34.654  3841  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:58:34.654  3841  3888 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:58:34.655  3841  3888 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-12 13:58:34.655  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-12 13:58:34.656  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:58:34.657  3841  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-12 13:58:34.658  3841  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-12 13:58:34.658  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 13:58:34.659  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:58:34.660  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:58:34.661  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-12 13:58:34.664  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 13:58:34.664  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 13:58:34.665  3841  3841 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 13:58:34.665  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 13:58:34.666  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-12 13:58:34.666  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:58:34.666  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 13:58:34.667  3841  3897 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:58:34.668  3841  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-12 13:58:34.674  3841  3888 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 13:58:34.674  3841  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:58:34.688  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,09-12 13:58:34.692  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings,
09-12 13:58:34.694  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:58:34.697  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...,
09-12 13:58:34.698  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 13:58:34.700  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,09-12 13:58:34.702  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-12 13:58:34.703  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-12 13:58:34.703  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-12 13:58:34.705  3841  3888 D BluetoothAdapter: STATE_ON
,09-12 13:58:34.719  2686  2825 D BtGatt.GattService: registerClient() - UUID=350b75b6-81ad-4f22-a002-4eb7876c8d63
,09-12 13:58:34.720  2686  2708 D BtGatt.GattService: onClientRegistered() - UUID=350b75b6-81ad-4f22-a002-4eb7876c8d63, clientIf=5
,09-12 13:58:34.721  3841  3851 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-12 13:58:34.723  2686  2713 D BtGatt.AdvertiseManager: message : 0
,09-12 13:58:34.725  2686  2713 D BtGatt.AdvertiseManager: starting multi advertising
,09-12 13:58:34.761  2686  2708 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-12 13:58:34.783  2686  2708 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-12 13:58:34.786  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-12 13:58:34.786  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:58:34.789  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:58:34.793  3841  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-12 13:58:34.793  3841  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-12 13:58:34.794  3841  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-12 13:58:34.794  3841  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-12 13:58:34.794  3841  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-12 13:58:34.794  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-12 13:58:34.797  3841  3888 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 13:58:34.799  3841  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-12 13:58:34.800  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-12 13:58:34.802  3841  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:58:34.803  3841  3888 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 13:58:34.803  3841  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-12 13:58:34.804  3841  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 13:58:34.804  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-12 13:58:34.804  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-12 13:58:34.804  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 13:58:34.806  3841  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 13:58:34.807  3841  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 13:58:34.807  3841  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-12 13:58:34.808  3841  3841 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-12 13:58:34.808  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 13:58:34.809  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-12 13:58:34.809  3841  3841 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 13:58:34.809  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:58:34.809  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:58:34.809  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 13:58:34.809  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:58:34.810  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:58:34.811  3841  3888 D BluetoothAdapter: STATE_ON,
09-12 13:58:34.812  3841  3888 D BluetoothLeScanner: could not find callback wrapper
,09-12 13:58:34.812  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:58:34.812  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-12 13:58:34.813  2686  2713 D BtGatt.AdvertiseManager: message : 1
09-12 13:58:34.814  2686  2713 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-12 13:58:34.824  2686  2708 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-12 13:58:34.824  2686  2708 D BtGatt.GattService: Client app is not null!
,09-12 13:58:34.825  2686  2828 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 13:58:34.825  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 13:58:34.825  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-12 13:58:34.826  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-12 13:58:34.826  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-12 13:58:34.826  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-12 13:58:34.827  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:58:34.827  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 13:58:34.828  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:58:34.830  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 13:58:34.832  3841  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:58:34.832  3841  3841 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-12 13:58:34.832  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:58:34.833  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 13:58:34.833  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:58:34.835  3841  3888 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-12 13:58:34.835  3841  3888 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-12 13:58:34.835  3841  3888 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-12 13:58:34.835  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-12 13:58:34.835  3841  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-12 13:58:34.835  3841  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-12 13:58:34.835  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-12 13:58:34.835  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:58:34.836  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-12 13:58:34.837  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 13:58:34.837  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-12 13:58:34.837  3841  3841 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-12 13:58:34.837  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 13:58:34.838  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-12 13:58:34.838  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:58:34.838  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 13:58:34.839  3841  3900 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:58:34.842  3841  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-12 13:58:34.843  3841  3888 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 13:58:34.843  3841  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:58:34.846  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 13:58:34.847  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 13:58:34.847  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:58:34.848  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-12 13:58:34.849  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:58:34.849  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 F8 CF C5 D9 E5 61
09-12 13:58:34.849  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-12 13:58:34.849  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-12 13:58:34.849  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-12 13:58:34.850  3841  3888 D BluetoothAdapter: STATE_ON
,09-12 13:58:34.852  2686  2697 D BtGatt.GattService: registerClient() - UUID=b1104d60-c40a-4833-8352-31c982c789e9
,09-12 13:58:34.852  2686  2708 D BtGatt.GattService: onClientRegistered() - UUID=b1104d60-c40a-4833-8352-31c982c789e9, clientIf=5
09-12 13:58:34.853  3841  3851 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-12 13:58:34.854  2686  2713 D BtGatt.AdvertiseManager: message : 0
,09-12 13:58:34.858  2686  2713 D BtGatt.AdvertiseManager: starting multi advertising
,09-12 13:58:34.870  2686  2708 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-12 13:58:34.877  2686  2708 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-12 13:58:34.878  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-12 13:58:34.878  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:58:34.879  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:58:34.881  3841  3888 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 13:58:34.881  3841  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-12 13:58:34.882  3841  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-12 13:58:34.882  3841  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-12 13:58:34.882  3841  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-12 13:58:34.882  3841  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-12 13:58:34.882  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-12 13:58:34.884  3841  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-12 13:58:34.884  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true,
,09-12 13:58:35.385  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:58:35.385  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-12 13:58:35.385  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 13:58:35.386  3841  3841 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-12 13:58:35.386  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 13:58:35.386  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-12 13:58:35.387  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 13:58:35.387  3841  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69fb2c4 not in the list
09-12 13:58:35.387  3841  3900 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 13:58:35.387  3841  3841 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 13:58:35.388  3841  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-12 13:58:35.387  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:58:35.388  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:58:35.388  3841  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-12 13:58:35.388  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 13:58:35.388  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:58:35.389  3841  3841 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 13:58:35.389  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:58:35.392  3841  3888 D BluetoothAdapter: STATE_ON
,09-12 13:58:35.392  3841  3888 D BluetoothLeScanner: could not find callback wrapper
,09-12 13:58:35.393  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 13:58:35.393  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-12 13:58:35.395  2686  2713 D BtGatt.AdvertiseManager: message : 1
09-12 13:58:35.397  2686  2713 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-12 13:58:35.412  2686  2708 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-12 13:58:35.412  2686  2708 D BtGatt.GattService: Client app is not null!
,09-12 13:58:35.415  2686  2825 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 13:58:35.416  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 13:58:35.416  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-12 13:58:35.417  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-12 13:58:35.418  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-12 13:58:35.418  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-12 13:58:35.423  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:58:35.423  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:58:35.423  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:58:35.425  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 13:58:35.428  3841  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f05ad not in the list
,09-12 13:58:35.428  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:58:35.429  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:58:35.429  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:35.429  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 13:58:35.429  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:58:35.432  3841  3888 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-12 13:58:35.436  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:58:35.449  3841  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:58:35.449  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:35.449  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:35.449  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:35.449  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:35.449  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:35.449  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:58:35.449  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:58:35.455  3841  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:58:35.455  3841  3888 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:58:35.455  3841  3888 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-12 13:58:35.455  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-12 13:58:35.457  3841  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-12 13:58:35.457  3841  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-12 13:58:35.457  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 13:58:35.458  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:58:35.460  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-12 13:58:35.461  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-12 13:58:35.461  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-12 13:58:35.461  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-12 13:58:35.461  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-12 13:58:35.462  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:58:35.462  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:35.462  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 13:58:35.464  3841  3903 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:58:35.468  3841  3903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-12 13:58:35.470  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:35.471  3841  3841 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-12 13:58:35.474  3841  3888 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 13:58:35.474  3841  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:58:35.486  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:58:35.488  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 13:58:35.488  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:58:35.495  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-12 13:58:35.496  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:58:35.496  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 F8 CF C5 D9 E5 61
09-12 13:58:35.497  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-12 13:58:35.497  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-12 13:58:35.497  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-12 13:58:35.499  3841  3888 D BluetoothAdapter: STATE_ON
,09-12 13:58:35.508  2686  2699 D BtGatt.GattService: registerClient() - UUID=ab5616b2-d149-4044-a929-f25fb6a738d3
,09-12 13:58:35.509  2686  2708 D BtGatt.GattService: onClientRegistered() - UUID=ab5616b2-d149-4044-a929-f25fb6a738d3, clientIf=5
,09-12 13:58:35.510  3841  3852 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-12 13:58:35.513  2686  2713 D BtGatt.AdvertiseManager: message : 0
,09-12 13:58:35.520  2686  2713 D BtGatt.AdvertiseManager: starting multi advertising
,09-12 13:58:35.549  2686  2708 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-12 13:58:35.562  2686  2708 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
09-12 13:58:35.564  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-12 13:58:35.564  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 13:58:35.566  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:58:35.568  3841  3888 I io.jxcore.node.ConnectionHelper: start: OK
09-12 13:58:35.568  3841  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-12 13:58:35.569  3841  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-12 13:58:35.569  3841  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-12 13:58:35.570  3841  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-12 13:58:35.570  3841  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-12 13:58:35.570  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-12 13:58:35.578  3841  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-12 13:58:35.579  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-12 13:58:36.073  3841  3888 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:58:36.073  3841  3888 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 13:58:36.074  3841  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-12 13:58:36.074  3841  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 13:58:36.074  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 13:58:36.075  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-12 13:58:36.075  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 13:58:36.077  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 13:58:36.078  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 13:58:36.078  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:58:36.078  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:58:36.078  3841  3841 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 13:58:36.079  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:58:36.079  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:58:36.079  3841  3903 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 13:58:36.079  3841  3903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 13:58:36.079  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:58:36.080  3841  3903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-12 13:58:36.082  3841  3888 D BluetoothAdapter: STATE_ON
09-12 13:58:36.082  3841  3888 D BluetoothLeScanner: could not find callback wrapper
09-12 13:58:36.082  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:58:36.083  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-12 13:58:36.085  2686  2713 D BtGatt.AdvertiseManager: message : 1
09-12 13:58:36.087  2686  2713 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-12 13:58:36.113  2686  2708 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-12 13:58:36.113  2686  2708 D BtGatt.GattService: Client app is not null!
,09-12 13:58:36.118  2686  2827 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 13:58:36.119  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 13:58:36.119  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-12 13:58:36.120  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-12 13:58:36.120  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-12 13:58:36.120  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-12 13:58:36.124  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:58:36.125  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 13:58:36.125  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:58:36.127  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:58:36.133  3841  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:58:36.133  3841  3841 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-12 13:58:36.134  3841  3841 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-12 13:58:36.136  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:58:36.137  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:58:36.137  3841  3841 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-12 13:58:36.137  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:58:36.145  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:58:36.145  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:36.145  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
09-12 13:58:36.145  3841  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69fb2c4 not in the list
,09-12 13:58:36.145  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:58:36.145  3841  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f05ad not in the list
,09-12 13:58:36.145  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:58:36.145  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:58:36.148  3841  3888 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-12 13:58:36.148  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,09-12 13:58:36.149  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:36.149  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:36.149  3841  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69fb2c4 not in the list
09-12 13:58:36.149  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:58:36.149  3841  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f05ad not in the list
09-12 13:58:36.149  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:58:36.149  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:58:36.149  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:36.150  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 13:58:36.150  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:58:36.151  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:58:36.151  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:36.151  3841  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69fb2c4 not in the list
09-12 13:58:36.151  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:58:36.151  3841  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f05ad not in the list
09-12 13:58:36.151  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:58:36.151  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:36.151  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:36.152  3841  3888 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-12 13:58:36.152  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:58:36.152  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:36.152  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:36.152  3841  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69fb2c4 not in the list
09-12 13:58:36.153  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:58:36.153  3841  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f05ad not in the list
09-12 13:58:36.153  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:58:36.153  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:36.153  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:36.155  3841  3888 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-12 13:58:36.155  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:58:36.155  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:36.155  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:36.155  3841  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69fb2c4 not in the list
09-12 13:58:36.155  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:58:36.155  3841  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f05ad not in the list
09-12 13:58:36.155  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:58:36.155  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:36.156  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:36.156  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will u,se port 1 when trying to connect
09-12 13:58:36.156  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:58:36.156  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:58:36.157  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 13:58:36.157  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:58:36.157  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:58:36.157  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 13:58:36.157  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:58:36.157  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:58:36.157  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:58:36.157  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:36.158  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:36.158  3841  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69fb2c4 not in the list
09-12 13:58:36.158  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:58:36.158  3841  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f05ad not in the list
09-12 13:58:36.158  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:58:36.158  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:36.158  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:36.159  3841  3888 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:58:36.159  3841  3888 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 13:58:36.159  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 13:58:36.169  3841  3888 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:58:36.169  3841  3888 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-12 13:58:36.170  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 13:58:36.170  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 13:58:36.170  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 13:58:36.170  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 13:58:36.171  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 13:58:36.171  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 13:58:36.171  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 13:58:36.171  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 13:58:36.171  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 13:58:36.172  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 13:58:36.172  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 13:58:36.172  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 13:58:36.172  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 13:58:36.172  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 13:58:36.173  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 13:58:36.173  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 13:58:36.173  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 13:58:36.173  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 13:58:36.173  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 13:58:36.174  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 13:58:36.174  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 13:58:36.174  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 13:58:36.174  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 13:58:36.175  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 13:58:36.175  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 13:58:36.175  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 13:58:36.175  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 13:58:36.175  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 13:58:36.176  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 13:58:36.176  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 13:58:36.176  3841  3888 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-12 13:58:36.177  3841  3888 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 13:58:36.177  3841  3888 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-12 13:58:36.177  3841  3888 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:58:36.177  3841  3888 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 13:58:36.178  3841  3888 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-12 13:58:36.178  3841  3888 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:58:36.178  3841  3888 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 13:58:36.178  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-12 13:58:36.184  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-12 13:58:36.185  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-12 13:58:36.185  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-12 13:58:36.186  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-12 13:58:36.186  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-12 13:58:36.186  3841  3888 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-12 13:58:36.187  3841  3888 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:58:36.187  3841  3888 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-12 13:58:36.187  3841  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 429)
09-12 13:58:36.188  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:58:36.188  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:36.188  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:36.188  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-12 13:58:36.189  3841  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69fb2c4 not in the list
09-12 13:58:36.189  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:58:36.189  3841  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f05ad not in the list
09-12 13:58:36.189  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:58:36.189  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:36.189  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:36.190  3841  3906 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:58:36.190  3841  3888 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-12 13:58:36.191  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:58:36.191  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:36.191  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:36.191  3841  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69fb2c4 not in the list
09-12 13:58:36.191  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:58:36.191  3841  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f05ad not in the list
09-12 13:58:36.191  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:58:36.191  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:36.191  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:36.192  3841  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 429
09-12 13:58:36.192  3841  3888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-12 13:58:36.192  3841  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 429)
09-12 13:58:36.192  3841  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 429)
09-12 13:58:36.192  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:58:36.192  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:36.192  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:36.192  3841  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69fb2c4 not in the list
09-12 13:58:36.193  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:58:36.193  3841  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f05ad not in the list
09-12 13:58:36.193  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:58:36.193  3841  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 429)
09-12 13:58:36.193  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:36.193  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:36.194  3841  3888 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-12 13:58:36.194  3841  3888 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-12 13:58:36.194  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 13:58:36.194  3841  3888 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-12 13:58:36.194  3841  3888 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 13:58:36.194  3841  3888 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-12 13:58:36.194  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 13:58:36.195  3841  3888 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-12 13:58:36.195  3841  3888 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 13:58:36.195  3841  3888 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 13:58:36.195  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 13:58:36.195  3841  3888 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-12 13:58:36.195  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:58:36.195  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:36.195  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:36.195  3841  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69fb2c4 not in the list
09-12 13:58:36.195  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:58:36.195  3841  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f05ad not in the list
09-12 13:58:36.196  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:58:36.196  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:58:36.196  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:36.196  3841  3888 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-12 13:58:36.200  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:58:36.204  3841  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:58:36.204  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:36.204  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:36.204  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:36.204  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:36.204  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:36.204  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:58:36.204  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:58:36.207  3841  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:36.207  3841  3888 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:58:36.207  3841  3888 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-12 13:58:36.207  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-12 13:58:36.208  3841  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-12 13:58:36.208  3841  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-12 13:58:36.208  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 13:58:36.208  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:58:36.209  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-12 13:58:36.209  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:58:36.210  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 13:58:36.210  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 13:58:36.210  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 13:58:36.210  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-12 13:58:36.210  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:58:36.210  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 13:58:36.213  3841  3908 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:58:36.214  3841  3888 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 13:58:36.214  3841  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 13:58:36.215  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:58:36.215  3841  3841 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 13:58:36.216  3841  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-12 13:58:36.218  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 13:58:36.218  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 13:58:36.219  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 13:58:36.221  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-12 13:58:36.221  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:58:36.221  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 F8 CF C5 D9 E5 61
09-12 13:58:36.221  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-12 13:58:36.221  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-12 13:58:36.221  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-12 13:58:36.222  3841  3888 D BluetoothAdapter: STATE_ON
09-12 13:58:36.224  2686  2825 D BtGatt.GattService: registerClient() - UUID=f11b9eba-fbea-42f3-bbd4-b4f47db0f566
09-12 13:58:36.225  2686  2708 D BtGatt.GattService: onClientRegistered() - UUID=f11b9eba-fbea-42f3-bbd4-b4f47db0f566, clientIf=5
09-12 13:58:36.226  3841  3852 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-12 13:58:36.227  2686  2713 D BtGatt.AdvertiseManager: message : 0
09-12 13:58:36.233  2686  2713 D BtGatt.AdvertiseManager: starting multi advertising
,09-12 13:58:36.246  2686  2708 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-12 13:58:36.259  2686  2708 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-12 13:58:36.261  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-12 13:58:36.261  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:58:36.264  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:58:36.266  3841  3888 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 13:58:36.266  3841  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-12 13:58:36.267  3841  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-12 13:58:36.267  3841  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-12 13:58:36.268  3841  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-12 13:58:36.268  3841  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-12 13:58:36.268  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-12 13:58:36.277  3841  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-12 13:58:36.278  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-12 13:58:36.774  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:58:36.774  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 13:58:36.775  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 13:58:36.775  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-12 13:58:36.777  3841  3908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-12 13:58:36.777  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-12 13:58:36.778  3841  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-12 13:58:36.778  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-12 13:58:36.778  3841  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-12 13:58:36.778  3841  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69fb2c4 not in the list
,09-12 13:58:36.778  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:58:36.779  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 13:58:36.779  3841  3841 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-12 13:58:36.779  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:58:36.779  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 13:58:36.780  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:58:36.780  3841  3841 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
09-12 13:58:36.780  3841  3841 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-12 13:58:36.782  3841  3888 D BluetoothAdapter: STATE_ON
09-12 13:58:36.782  3841  3888 D BluetoothLeScanner: could not find callback wrapper
,09-12 13:58:36.783  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:58:36.783  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-12 13:58:36.785  2686  2713 D BtGatt.AdvertiseManager: message : 1
09-12 13:58:36.786  2686  2713 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-12 13:58:36.806  2686  2708 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-12 13:58:36.806  2686  2708 D BtGatt.GattService: Client app is not null!
09-12 13:58:36.808  2686  2699 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 13:58:36.809  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 13:58:36.809  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-12 13:58:36.809  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-12 13:58:36.809  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-12 13:58:36.809  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-12 13:58:36.812  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:58:36.812  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 13:58:36.813  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:58:36.814  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 13:58:36.817  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 13:58:36.817  3841  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f05ad not in the list
,09-12 13:58:36.817  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 13:58:36.817  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:58:36.817  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:58:36.817  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,09-12 13:58:36.823  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:58:36.824  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:58:36.824  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:58:36.824  3841  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69fb2c4 not in the list
09-12 13:58:36.825  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:58:36.825  3841  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f05ad not in the list
09-12 13:58:36.825  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:58:36.825  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:36.825  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:58:36.829  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-12 13:58:36.830  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:58:36.832  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-12 13:58:36.833  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-12 13:58:36.833  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 13:58:36.833  3841  3841 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 13:58:36.833  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 13:58:36.834  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-12 13:58:36.835  3841  3911 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:58:36.835  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:58:36.835  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 13:58:36.835  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-12 13:58:36.835  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-12 13:58:36.835  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:36.836  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-12 13:58:36.836  3841  3841 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-12 13:58:36.836  3841  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69fb2c4 not in the list
,09-12 13:58:36.836  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:58:36.837  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 13:58:36.837  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:58:36.837  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 13:58:36.837  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:58:36.838  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:58:36.839  3841  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 13:58:36.840  3841  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-12 13:58:36.840  3841  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-12 13:58:36.840  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:58:36.841  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:58:36.841  3841  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f05ad not in the list
09-12 13:58:36.841  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:58:36.841  3841  3841 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 13:58:36.841  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:58:36.841  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:58:36.841  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:36.842  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:58:36.845  3841  3888 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-12 13:58:36.845  3841  3888 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 13:58:36.845  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 13:58:36.846  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:58:36.846  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
09-12 13:58:36.847  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:58:36.847  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:36.847  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:58:36.847  3841  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69fb2c4 not in the list
09-12 13:58:36.848  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:58:36.848  3841  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f05ad not in the list
09-12 13:58:36.848  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:58:36.848  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:36.849  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:58:36.859  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:58:36.859  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:58:36.859  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:58:36.859  3841  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69fb2c4 not in the list
,09-12 13:58:36.859  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:58:36.860  3841  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f05ad not in the list,
09-12 13:58:36.860  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:58:36.860  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:36.860  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:58:36.861  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:58:36.861  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:36.862  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:58:36.862  3841  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69fb2c4 not in the list
,09-12 13:58:36.862  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:58:36.862  3841  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f05ad not in the list
09-12 13:58:36.862  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:58:36.862  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:36.862  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:36.864  3841  3888 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing,
09-12 13:58:36.864  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 13:58:36.864  3841  3888 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing,
09-12 13:58:36.864  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-12 13:58:36.865  3841  3888 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-12 13:58:36.865  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-12 13:58:36.869  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-12 13:58:36.869  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-12 13:58:36.870  3841  3888 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-12 13:58:36.871  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-12 13:58:36.871  3841  3888 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-12 13:58:36.871  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 13:58:36.871  3841  3888 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2,
09-12 13:58:36.871  3841  3888 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-12 13:58:36.872  3841  3888 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-12 13:58:36.872  3841  3888 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-12 13:58:36.874  3841  3888 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-12 13:58:36.874  3841  3888 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-12 13:58:36.874  3841  3888 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-12 13:58:36.874  3841  3888 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-12 13:58:36.875  3841  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:58:36.875  3841  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f10b692 added. We now have 3 listener(s)
,09-12 13:58:36.878  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 13:58:36.878  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:58:36.878  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 13:58:36.878  3841  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:58:36.878  3841  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8aa6863 added. We now have 3 listener(s)
,09-12 13:58:36.879  3841  3888 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:58:36.879  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:58:36.883  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:58:36.890  3841  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:58:36.890  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:36.890  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:36.890  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:36.890  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:36.890  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:36.890  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:58:36.890  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:58:36.893  3841  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:58:36.893  3841  3888 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:58:36.897  3841  3888 D BluetoothAdapter: enable(): BT is already enabled..!
,09-12 13:58:36.898   874  1903 D WifiService: setWifiEnabled: true pid=3841, uid=10000
,09-12 13:58:36.898   874  1903 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 13:58:36.898  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:36.903  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:36.911   874   884 D WifiService: setWifiEnabled: false pid=3841, uid=10000
,09-12 13:58:36.911   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 13:58:36.935  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-12 13:58:36.940   874  1309 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-12 13:58:36.940   874  1309 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-12 13:58:36.941   874  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 13:58:36.941   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:58:36.953   874  1309 E native  : do suspend true
,09-12 13:58:36.966   874  1854 D DhcpClient: Clearing IP address
,09-12 13:58:36.966   370   872 D CommandListener: Clearing all IP addresses on wlan0
,09-12 13:58:36.970   370   872 D CommandListener: Setting iface cfg
,09-12 13:58:36.978  1523  2122 V NativeCrypto: Read error: ssl=0xaa23c600: I/O error during system call, Connection timed out
,09-12 13:58:36.980  1523  2122 V NativeCrypto: SSL shutdown failed: ssl=0xaa23c600: I/O error during system call, Broken pipe
09-12 13:58:36.981   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-12 13:58:36.981   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-12 13:58:36.985   393   393 E Parcel  : Reading a NULL string not supported here.
09-12 13:58:36.989   874  1309 D WifiStateMachine: Start Disconnecting Watchdog 1
,09-12 13:58:36.991   874  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 13:58:36.991   874  1309 E native  : do suspend true
,09-12 13:58:36.994   874  1856 D DhcpClient: Receive thread stopped
,09-12 13:58:36.996   874  1311 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-12 13:58:37.027   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:58:37.051   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:58:37.052   370   872 D CommandListener: Clearing all IP addresses on wlan0
,09-12 13:58:37.052   874  1311 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-12 13:58:37.053   874  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:58:37.054   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-12 13:58:37.065  3382  3382 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@a4ac6e1 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-12 13:58:37.071  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:37.071  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:37.071  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:37.071  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:37.071  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:37.071  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:58:37.071  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:58:37.071  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:58:37.072   874  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 13:58:37.074  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:58:37.078  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:37.078  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:37.078  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:37.078  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:37.078  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:37.078  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:58:37.078  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:58:37.078  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:58:37.080  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:58:37.082  1743  1743 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 13:58:37.083  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:37.083  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:37.083  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:37.083  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:37.083  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:37.083  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:58:37.083  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:58:37.083  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:58:37.087  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:58:37.089  1743  1743 D SystemUpdateService: onCreate
,09-12 13:58:37.094  1743  1743 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 13:58:37.097   874  1309 D WifiConfigStore: Retrieve network priorities after PNO.
09-12 13:58:37.101  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:37.101  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:37.101  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:37.101  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:58:37.101  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:37.101  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:58:37.101  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:58:37.101  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:58:37.103  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
09-12 13:58:37.104  2076  2329 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:58:37.105   874  1309 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 13:58:37.106  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:37.106  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:37.106  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:37.106  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:58:37.106  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:37.106  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:58:37.106  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:58:37.106  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:58:37.108  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:58:37.111  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:37.111  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:37.111  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:37.111  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:58:37.111  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:37.111  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:58:37.111  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:58:37.111  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:58:37.111  1743  1743 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-12 13:58:37.113  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:58:37.121  1743  2318 I iu.UploadsManager: num queued entries: 0
,09-12 13:58:37.122  1743  2318 I iu.UploadsManager: num updated entries: 0
,09-12 13:58:37.123  1743  2318 I iu.SyncManager: NEXT; no task
,09-12 13:58:37.125  1743  1743 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 13:58:37.126  1743  1743 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 13:58:37.127   370   872 E Netd    : netlink response contains error (No such file or directory)
09-12 13:58:37.128   874  1311 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-12 13:58:37.128  1743  3920 I SystemUpdateService: active receiver: enabled,
,09-12 13:58:37.131  1743  3920 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 13:58:37.133  1743  3920 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-12 13:58:37.133  1743  3920 I SystemUpdateService: now status is 0 (complete)
09-12 13:58:37.133  1743  3920 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 13:58:37.133  1743  3920 I SystemUpdateService: file has been verified
09-12 13:58:37.133  1743  3920 I SystemUpdateService: OTA package size = 12249756
,09-12 13:58:37.137  1743  3920 I SystemUpdateService: showing system update notification
,09-12 13:58:37.139   874  2065 I ActivityManager: Start proc 3924:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-12 13:58:37.151  1743  1743 D SystemUpdateService: onDestroy
,09-12 13:58:37.169  3924  3924 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-12 13:58:37.171  3924  3924 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:58:37.188  3924  3924 D SprintDMHelper: simOperator: 
,09-12 13:58:37.188  3924  3924 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 13:58:37.204   874  2065 I ActivityManager: Start proc 3936:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-12 13:58:37.207   874  2065 I ActivityManager: Killing 3382:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-12 13:58:37.342  3841  3841 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 13:58:37.368   874  1906 I ActivityManager: Start proc 3951:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-12 13:58:37.372  3050  3950 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-12 13:58:37.375   874   885 I ActivityManager: Killing 3568:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-12 13:58:37.427   874  2063 D WifiService: setWifiEnabled: true pid=3841, uid=10000
09-12 13:58:37.427   874  2063 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 13:58:37.432   874  1309 D WifiConfigStore: Loading config and enabling all networks 
,09-12 13:58:37.448   874  1309 D WifiConfigStore: loaded 0 passpoint configs
,09-12 13:58:37.449   874  1309 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-12 13:58:37.449   874  1309 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-12 13:58:37.451   874  1309 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-12 13:58:37.451   874  1309 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-12 13:58:37.451   874  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-12 13:58:37.452   874  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 13:58:37.457  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:37.457  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:37.457  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:37.457  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:37.457  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:37.457  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:58:37.457  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:58:37.457  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:58:37.461  3951  3951 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-12 13:58:37.462  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:58:37.464   370   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-12 13:58:37.465   874  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-12 13:58:37.465   370   872 D CommandListener: Setting iface cfg
09-12 13:58:37.466   874  1308 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-12 13:58:37.466   874  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 13:58:37.469  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:37.469  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:37.469  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:37.469  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:37.469  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:37.469  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:58:37.469  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:58:37.469  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:58:37.473  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:58:37.475   874  1309 E native  : do suspend true
09-12 13:58:37.475   874  1308 D WifiNative-HAL: p2pGetDeviceAddress
,09-12 13:58:37.478  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:37.478  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:37.478  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:37.478  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:37.478  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:37.478  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:58:37.478  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:58:37.478  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:58:37.481   874  1308 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-12 13:58:37.481  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:58:37.486   874  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 13:58:37.528  3951  3951 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-12 13:58:37.528  3951  3951 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-12 13:58:37.528  3951  3951 I GAv4    :   adb logcat -s GAv4
,09-12 13:58:37.541  3951  3951 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-12 13:58:37.546  3951  3951 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-12 13:58:37.573  3951  3970 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-12 13:58:37.680  3951  3951 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-12 13:58:37.723  3951  3951 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-12 13:58:37.734  3951  3951 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 8167-8173)
09-12 13:58:37.734  3951  3951 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 13:58:37.743  3951  3951 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8022a51}
09-12 13:58:37.743  3951  3951 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 13:58:37.744  3951  3951 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-12 13:58:37.752  3951  3951 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-12 13:58:37.754  3951  3951 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-12 13:58:37.772  3951  3951 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-12 13:58:37.785  3951  3951 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-12 13:58:37.785  3951  3951 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 13:58:37.785  3951  3951 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 13:58:37.785  3951  3951 I Adreno  : Build Date                       : 10/20/15
09-12 13:58:37.785  3951  3951 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 13:58:37.785  3951  3951 I Adreno  : Local Branch                     : M14
09-12 13:58:37.785  3951  3951 I Adreno  : Remote Branch                    : 
09-12 13:58:37.785  3951  3951 I Adreno  : Remote Branch                    : 
09-12 13:58:37.785  3951  3951 I Adreno  : Reconstruct Branch               : 
,09-12 13:58:37.853  3951  3951 I NSApplication: Starting up...
,09-12 13:58:37.862  3951  3999 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-12 13:58:37.896   874  1905 I ActivityManager: Start proc 4004:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-12 13:58:37.897   874  1905 I ActivityManager: Killing 3451:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-12 13:58:37.898   278   278 E lowmemorykiller: Error writing /proc/3451/oom_score_adj; errno=22
,09-12 13:58:37.979  2686  2704 D BluetoothAdapterState: Current state: ON, message: 23
,09-12 13:58:37.979  2686  2704 D BluetoothAdapterProperties: Setting state to 13
,09-12 13:58:37.979  2686  2704 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-12 13:58:37.987  2686  2704 D BluetoothAdapterProperties: onBluetoothDisable()
,09-12 13:58:37.988  2686  2704 I BluetoothAdapterState: Entering PendingCommandState
09-12 13:58:37.989  2686  2708 D BluetoothAdapterProperties: Scan Mode:20
09-12 13:58:37.991  2686  2704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-12 13:58:37.991  2686  2686 D BluetoothMapService: onReceive
09-12 13:58:37.991  2686  2686 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:58:37.992  2686  2686 D BluetoothMapService: STATE_TURNING_OFF
09-12 13:58:37.992  2686  2686 D BluetoothMapService: MAP Service closeService in
09-12 13:58:37.992  2686  2686 D BluetoothMapMasInstance0: MAP Service shutdown
,09-12 13:58:37.992  2686  2686 D ObexServerSockets0: shutdown(block = true)
09-12 13:58:37.993  2686  2686 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-12 13:58:37.993  2686  2686 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-12 13:58:37.993  2686  2835 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-12 13:58:37.994  2686  2836 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-12 13:58:37.994  2686  2808 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-12 13:58:37.997  2686  2686 I BtOppRfcommListener: stopping Accept Thread
,09-12 13:58:37.998  2686  3433 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-12 13:58:37.998  2686  3433 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-12 13:58:38.001  2686  2686 D HeadsetService: Received stop request...Stopping profile...
09-12 13:58:38.004  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:58:38.004  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:38.004  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:38.004  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:38.004  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:38.004  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:58:38.004  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:58:38.004  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:58:38.004  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:58:38.004  2686  2686 D A2dpService: Received stop request...Stopping profile...
09-12 13:58:38.004  1950  2276 D BluetoothHeadset: Proxy object disconnected
,09-12 13:58:38.004  2686  2815 D A2dpStateMachine: Exit Disconnected: -1
09-12 13:58:38.005   874   874 D BluetoothHeadset: Proxy object disconnected
,09-12 13:58:38.005  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:58:38.005  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:58:38.005  1366  1384 D BluetoothHeadset: Proxy object disconnected
09-12 13:58:38.006  2686  2686 D HidService: Received stop request...Stopping profile...
,09-12 13:58:38.006  2686  2686 D HidService: Stopping Bluetooth HidService
09-12 13:58:38.006   874   874 D BluetoothHeadset: Proxy object disconnected
09-12 13:58:38.006   874   874 D BluetoothHeadset: Proxy object disconnected
09-12 13:58:38.006   874   874 D BluetoothA2dp: Proxy object disconnected
,09-12 13:58:38.007  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:58:38.007  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:38.007  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:38.007  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:38.007  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:38.007  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:58:38.007  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:58:38.007  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:58:38.007  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:58:38.007  2686  2686 D HealthService: Received stop request...Stopping profile...
,09-12 13:58:38.007  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:58:38.008  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:58:38.009  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:58:38.009  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:38.009  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:38.009  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:38.009  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:38.009  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:58:38.009  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:58:38.009  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:58:38.009  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:58:38.010  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:58:38.010  2686  2686 D PanService: Received stop request...Stopping profile...
09-12 13:58:38.010  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:58:38.011  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:38.012  2686  2686 D BluetoothMapService: Received stop request...Stopping profile...
09-12 13:58:38.012  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:58:38.012  2686  2686 D BluetoothMapService: stop()
09-12 13:58:38.013  2686  2686 D BluetoothMapAppObserver: deinitObservers()
,09-12 13:58:38.013  2686  2686 D BluetoothMapAppObserver: removeReceiver()
09-12 13:58:38.013  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:58:38.015  1366  1366 D HeadsetProfile: Bluetooth service disconnected
09-12 13:58:38.015  1366  1366 D BluetoothA2dp: Proxy object disconnected
09-12 13:58:38.015  1366  1366 D BluetoothInputDevice: Proxy object disconnected
09-12 13:58:38.015  1366  1366 D HidProfile: Bluetooth service disconnected
,09-12 13:58:38.015  1366  1366 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 13:58:38.015  1366  1366 D PanProfile: Bluetooth service disconnected
09-12 13:58:38.016  1366  1366 D BluetoothMap: Proxy object disconnected
09-12 13:58:38.016  1366  1366 D MapProfile: Bluetooth service disconnected
,09-12 13:58:38.017  2686  2686 V BluetoothAdapterState: isTurningOff()=true
09-12 13:58:38.018  2686  2686 V BluetoothAdapterState: isTurningOn()=false
09-12 13:58:38.018  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 13:58:38.018  2686  2686 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:58:38.018  2686  2686 V BluetoothAdapterState: isTurningOff()=true
,09-12 13:58:38.018  2686  2686 V BluetoothAdapterState: isTurningOn()=false
09-12 13:58:38.018  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:58:38.018  2686  2686 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:58:38.020  2686  2686 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-12 13:58:38.020  2686  2686 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-12 13:58:38.020  2686  2708 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-12 13:58:38.020  2686  2792 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:58:38.020  2686  2792 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:58:38.020  2686  2792 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:58:38.021  2686  2708 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-12 13:58:38.022  2686  2708 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-12 13:58:38.022  2686  2792 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 13:58:38.022  2686  2792 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:58:38.023  2686  2792 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:58:38.023  2686  2792 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:58:38.023  2686  2792 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-12 13:58:38.023  2686  2792 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:58:38.023  2686  2686 V BluetoothAdapterState: isTurningOff()=true
09-12 13:58:38.023  2686  2686 V BluetoothAdapterState: isTurningOn()=false
09-12 13:58:38.023  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:58:38.023  2686  2686 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:58:38.024  2686  2686 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 13:58:38.024  2686  2686 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 13:58:38.024  2686  2686 V BluetoothAdapterState: isTurningOff()=true
09-12 13:58:38.024  2686  2686 V BluetoothAdapterState: isTurningOn()=false
09-12 13:58:38.024  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:58:38.024  2686  2686 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:58:38.024  2686  2686 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 13:58:38.024  2686  2708 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 13:58:38.025  2686  2708 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-12 13:58:38.025  2686  2686 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 13:58:38.025  2686  2686 V BluetoothAdapterState: isTurningOff()=true
09-12 13:58:38.025  2686  2686 V BluetoothAdapterState: isTurningOn()=false
,09-12 13:58:38.025  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:58:38.025  2686  2686 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:58:38.025  2686  2686 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 13:58:38.025  2686  2686 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-12 13:58:38.026  2686  2686 D BluetoothMapService: MAP Service closeService in
09-12 13:58:38.026  2686  2686 V BluetoothAdapterState: isTurningOff()=true
09-12 13:58:38.026  4004  4004 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
09-12 13:58:38.026  2686  2686 V BluetoothAdapterState: isTurningOn()=false
09-12 13:58:38.026  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:58:38.026  2686  2686 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:58:38.027  2686  2704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-12 13:58:38.027  2686  2704 D BluetoothAdapterProperties: Setting state to 15
09-12 13:58:38.027  2686  2686 D BluetoothMapService: cleanup()
09-12 13:58:38.027  2686  2704 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-12 13:58:38.027  2686  2686 D BluetoothMapService: MAP Service closeService in
09-12 13:58:38.027  2686  2704 I BluetoothAdapterState: Entering BleOnState
,09-12 13:58:38.027   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:58:38.027  1950  2138 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:58:38.028  1366  1378 D BluetoothPan: onBluetoothStateChange on: false
,09-12 13:58:38.028  1366  2028 D BluetoothMap: onBluetoothStateChange: up=false
09-12 13:58:38.029  1366  1384 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 13:58:38.030  1366  1693 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 13:58:38.030  1366  1378 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:58:38.030   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 13:58:38.030   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:58:38.030   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 13:58:38.031  1366  2028 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 13:58:38.031  2686  2704 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-12 13:58:38.032  2686  2704 D BluetoothAdapterProperties: Setting state to 16
09-12 13:58:38.032  2686  2704 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-12 13:58:38.033  2686  2704 D BluetoothAdapterProperties: onBleDisable
09-12 13:58:38.034  2686  2705 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-12 13:58:38.034  2686  2708 D BluetoothAdapterProperties: Scan Mode:20
09-12 13:58:38.033  2686  2704 I BluetoothAdapterState: Entering PendingCommandState
09-12 13:58:38.034  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:58:38.036  2686  2792 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 13:58:38.036  2686  2792 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 13:58:38.036  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:58:38.037  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:58:38.038  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:58:38.040  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:58:38.041  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:38.238  2686  2708 I bt_hci  : shut_down
,09-12 13:58:38.239  2686  2715 D bt_hwcfg: hw_epilog_process
,09-12 13:58:38.244   874   884 I ActivityManager: Killing 3493:android.process.acore/u0a5 (adj 15): empty #17
,09-12 13:58:38.319  2686  2715 I bt_vendor: low_power_mode_cb
,09-12 13:58:38.335   874  2791 I ActivityManager: Start proc 4020:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-12 13:58:38.344  2686  2715 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-12 13:58:38.345  2686  2715 I bt_vendor: epilog_cb
09-12 13:58:38.345  2686  2715 I bt_hci  : epilog_finished_callback
,09-12 13:58:38.349  2686  2708 I bt_hci_h4: hal_close
,09-12 13:58:38.350  2686  2708 I bt_userial_vendor: device fd = 51 close
,09-12 13:58:38.405  4020  4020 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-12 13:58:38.450  4020  4020 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-12 13:58:38.482  2686  2705 D bt_stack_manager: event_shut_down_stack finished.
,09-12 13:58:38.483  2686  2704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-12 13:58:38.484  2686  2704 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-12 13:58:38.485  2686  2686 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 13:58:38.486  2686  2686 D BtGatt.GattService: Received stop request...Stopping profile...
,09-12 13:58:38.487  2686  2686 D BtGatt.GattService: stop()
09-12 13:58:38.487  2686  2686 D BtGatt.AdvertiseManager: advertise clients cleared
,09-12 13:58:38.489  2686  2704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-12 13:58:38.489  2686  2704 I BluetoothAdapterState: Deferring BLE_TURN_ON request...
,09-12 13:58:38.490  2686  2686 V BluetoothAdapterState: isTurningOff()=false
09-12 13:58:38.490  2686  2686 V BluetoothAdapterState: isTurningOn()=false
,09-12 13:58:38.490  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:58:38.491  2686  2686 V BluetoothAdapterState: isBleTurningOff()=true
09-12 13:58:38.492  2686  2704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-12 13:58:38.492  2686  2704 D BluetoothAdapterProperties: Setting state to 10
09-12 13:58:38.492  2686  2704 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-12 13:58:38.493  2686  2704 I BluetoothAdapterState: Entering OffState
09-12 13:58:38.494  2686  2704 D BluetoothAdapterState: Current state: OFF, message: 0
09-12 13:58:38.494  2686  2704 D BluetoothAdapterProperties: Setting state to 14
09-12 13:58:38.494  2686  2704 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-12 13:58:38.495  2686  2704 D BluetoothBondStateMachine: make
,09-12 13:58:38.500  2686  4047 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 13:58:38.511   874  1903 I ActivityManager: Start proc 4048:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-12 13:58:38.516  2686  2704 I BluetoothAdapterState: Entering PendingCommandState
,09-12 13:58:38.517  2686  2686 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 13:58:38.517  2686  2686 D BtGatt.GattService: Received start request. Starting profile...
09-12 13:58:38.518  2686  2686 D BtGatt.GattService: start()
09-12 13:58:38.518  2686  2686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@73df50f
09-12 13:58:38.518  2686  2686 D BtGatt.AdvertiseManager: advertise manager created
,09-12 13:58:38.520   874  2064 I ActivityManager: Killing 3692:com.google.android.partnersetup/u0a16 (adj 15): empty #17
09-12 13:58:38.524  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:38.527  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:38.531  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:38.558  2686  2686 V BluetoothAdapterState: isTurningOff()=false
09-12 13:58:38.558  2686  2686 V BluetoothAdapterState: isTurningOn()=false
,09-12 13:58:38.558  2686  2686 V BluetoothAdapterState: isBleTurningOn()=true
09-12 13:58:38.558  2686  2686 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:58:38.558  2686  2704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-12 13:58:38.558  2686  2704 I bt_bluedroid: enable
09-12 13:58:38.559  2686  2705 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-12 13:58:38.559  2686  2705 I bt_hci  : start_up
,09-12 13:58:38.574  4048  4048 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-12 13:58:38.577  2686  2705 I bt_vendor: alloc value 0xb3a1c189
,09-12 13:58:38.577  2686  2705 I bt_vendor: init
09-12 13:58:38.577  2686  2705 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-12 13:58:38.577  2686  2705 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found,
,09-12 13:58:38.587  4048  4048 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 13:58:38.593  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 13:58:38.593   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a3cb74b:true
,09-12 13:58:38.625   874  1618 I ActivityManager: Start proc 4063:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-12 13:58:38.660  4048  4048 D LocalBluetoothProfileManager: Adding local MAP profile
,09-12 13:58:38.663  4048  4048 D BluetoothMap: Create BluetoothMap proxy object
,09-12 13:58:38.669  4063  4063 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-12 13:58:38.675  4048  4048 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-12 13:58:38.684  2686  2705 D bt_hci  : start_up starting async portion
,09-12 13:58:38.684  2686  4062 I bt_hci  : event_finish_startup
,09-12 13:58:38.684  2686  4062 I bt_hci_h4: hal_open
,09-12 13:58:38.685  2686  4062 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 13:58:38.692  2686  4062 I bt_userial_vendor: device fd = 57 open
,09-12 13:58:38.696  4048  4048 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:58:38.699   874  2064 I ActivityManager: Killing 3708:com.android.musicfx/u0a18 (adj 15): empty #17
,09-12 13:58:38.727  2686  4062 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 13:58:38.759  2686  4062 D bt_hwcfg: Chipset BCM4354A2
,09-12 13:58:38.759  2686  4062 D bt_hwcfg: Target name = [BCM4354A2]
09-12 13:58:38.759  2686  4062 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 13:58:38.760   874  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 13:58:38.842   874  1309 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.50 rxSuccessRate=11.56 delta 1000 -> 994
,09-12 13:58:38.844   874  1309 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-12 13:58:38.844   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:58:38.856   874  1309 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 13:58:38.872  4063  4063 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:58:38.872  4063  4063 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 13:58:38.872  4063  4063 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:58:38.872  4063  4063 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:58:38.872  4063  4063 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 13:58:38.873  4063  4063 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5417)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 13:58:38.873  4063  4063 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 13:58:38.873  4063  4063 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.r.k.d(PG:583)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:58:38.873  4063  4063 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 13:58:38.876  4063  4063 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:58:38.876  4063  4063 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 13:58:38.876  4063  4063 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:58:38.876  4063  4063 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:58:38.876  4063  4063 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 13:58:38.877  4063  4063 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:58:38.877  4063  4063 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:58:38.877  4063  4063 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-12 13:58:38.877  4063  4063 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-12 13:58:38.877  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-12 13:58:38.877  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:58:38.877  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:58:38.877  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:58:38.877  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:58:38.877  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:58:38.877  4063  4063 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:58:38.877  4063  4063 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:58:38.877  4063  4063 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:58:38.877  4063  4063 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:58:38.877  4063  4063 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:58:38.877  4063  4063 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:58:38.877  4063  4063 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:58:38.877  4063  4063 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:58:38.877  4063  4063 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:58:38.877  4063  4063 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:58:38.877  4063  4063 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 13:58:38.892  4048  4048 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 13:58:38.896   874  1309 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
09-12 13:58:38.897  1458  1458 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
09-12 13:58:38.897  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 13:58:38.900  4048  4048 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:58:38.927  4048  4048 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 13:58:38.932  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 13:58:38.937  4048  4048 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:58:38.977   874  1618 I ActivityManager: Killing 2239:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-12 13:58:39.011  2686  2704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-12 13:58:39.171  4063  4081 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-12 13:58:39.182   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@962637a:true
,09-12 13:58:39.295  2686  4062 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-12 13:58:39.296  2686  4062 D bt_hwcfg: Settlement delay -- 100 ms
09-12 13:58:39.296  2686  4062 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 13:58:39.321  1458  1458 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 13:58:39.379  1458  1458 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-12 13:58:39.381  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 13:58:39.391   874  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 13:58:39.409   874  1309 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-12 13:58:39.409   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:58:39.409   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 13:58:39.412  2686  4062 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 13:58:39.412  2686  4062 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 13:58:39.429   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:58:39.438   370   872 D CommandListener: Setting iface cfg
09-12 13:58:39.438   874  1309 D WifiStateMachine: Start Dhcp Watchdog 2
,09-12 13:58:39.446   874  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 13:58:39.448  2686  4062 I bt_hwcfg: vendor lib fwcfg completed
,09-12 13:58:39.448  2686  4062 I bt_vendor: firmware callback
09-12 13:58:39.448  2686  4062 I bt_hci  : firmware_config_callback
,09-12 13:58:39.454  2686  4104 I bt_btu  : btu_task pending for preload complete event
,09-12 13:58:39.454  2686  4104 I bt_btu_task: Bluetooth chip preload is complete
,09-12 13:58:39.455  2686  4104 I bt_btu  : btu_task received preload complete event
,09-12 13:58:39.461  2686  4104 I         : BTE_InitTraceLevels -- TRC_HCI
,09-12 13:58:39.461  2686  4104 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 13:58:39.461  2686  4104 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-12 13:58:39.461  2686  4104 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 13:58:39.461  2686  4104 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-12 13:58:39.462  2686  4104 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 13:58:39.462  2686  4104 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 13:58:39.462  2686  4104 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 13:58:39.462  2686  4104 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 13:58:39.462  2686  4104 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 13:58:39.463  2686  4104 I         : BTE_InitTraceLevels -- TRC_SDP
,09-12 13:58:39.463  2686  4104 I         : BTE_InitTraceLevels -- TRC_GATT
,09-12 13:58:39.464  2686  4104 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 13:58:39.465  2686  4104 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 13:58:39.465  2686  4104 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 13:58:39.466   874  4105 D DhcpClient: Receive thread started
,09-12 13:58:39.519  2686  2704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-12 13:58:39.553   874  1309 E native  : do suspend false
,09-12 13:58:39.576   874  1854 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 13:58:39.592   874  4105 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172612, domain null
,09-12 13:58:39.595   874  1854 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172612 seconds
,09-12 13:58:39.597  2686  4104 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3999d9d
09-12 13:58:39.597  2686  4104 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3999d9d 
09-12 13:58:39.600   874  1854 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 13:58:39.613   874  4105 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 13:58:39.614   874  1854 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 13:58:39.620   370   872 D CommandListener: Setting iface cfg
,09-12 13:58:39.624  2686  2708 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-12 13:58:39.625  2686  2708 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 13:58:39.626  2686  2708 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 13:58:39.628  2686  2708 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 13:58:39.629  2686  2708 D BluetoothAdapterProperties: Scan Mode:20
,09-12 13:58:39.629  2686  2708 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 13:58:39.629  2686  2708 D bt_hci  : do_postload posting postload work item
09-12 13:58:39.629  2686  4062 I bt_hci  : event_postload
09-12 13:58:39.629  2686  4062 I bt_vendor: sco_config_cb
,09-12 13:58:39.630  2686  4062 I bt_hci  : sco_config_callback postload finished.
09-12 13:58:39.630  2686  2708 D bt_bte_conf: Device ID record 1 : primary
09-12 13:58:39.630  2686  2708 D bt_bte_conf:   vendorId            = 000f
09-12 13:58:39.630  2686  2708 D bt_bte_conf:   vendorIdSource      = 0001
09-12 13:58:39.631  2686  2708 D bt_bte_conf:   product             = 1200
09-12 13:58:39.631  2686  2708 D bt_bte_conf:   version             = 1436
09-12 13:58:39.631  2686  2708 D bt_bte_conf:   clientExecutableURL = 
09-12 13:58:39.631  2686  2708 D bt_bte_conf:   serviceDescription  = 
09-12 13:58:39.631  2686  2708 D bt_bte_conf:   documentationURL    = 
,09-12 13:58:39.631  2686  2708 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-12 13:58:39.631  2686  2705 D bt_stack_manager: event_start_up_stack finished
09-12 13:58:39.632  2686  2704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-12 13:58:39.632  2686  2704 D BluetoothAdapterProperties: Setting state to 15
09-12 13:58:39.632  2686  2704 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-12 13:58:39.633  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:39.636  2686  2704 I BluetoothAdapterState: Entering BleOnState
09-12 13:58:39.637   874  1854 D DhcpClient: Scheduling renewal in 86399s
09-12 13:58:39.637  2686  4062 I bt_vendor: low_power_mode_cb
09-12 13:58:39.638  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:58:39.641   874  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
09-12 13:58:39.642  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:58:39.642  2686  2704 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-12 13:58:39.642  2686  2704 D BluetoothAdapterProperties: Setting state to 11
,09-12 13:58:39.642  2686  2704 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-12 13:58:39.650  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:58:39.650   874  1309 E native  : do suspend true
09-12 13:58:39.652  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:58:39.654  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:39.656  2686  2686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@73df50f
09-12 13:58:39.657  2686  2686 D HeadsetService: Received start request. Starting profile...
09-12 13:58:39.657  2686  2686 D HeadsetStateMachine: make
09-12 13:58:39.663  2686  2686 D HeadsetStateMachine: max_hf_connections = 1
09-12 13:58:39.663  2686  2686 I bt_bluedroid: get_profile_interface handsfree
09-12 13:58:39.665  2686  2708 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-12 13:58:39.665  2686  2708 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-12 13:58:39.668  2686  2686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@73df50f
,09-12 13:58:39.671   874  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 13:58:39.671   874  1309 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 13:58:39.672   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-12 13:58:39.672  2686  2686 D A2dpService: Received start request. Starting profile...
,09-12 13:58:39.672  2686  2686 I bt_bluedroid: get_profile_interface avrcp
,09-12 13:58:39.673   874  1311 D ConnectivityService: Adding iface wlan0 to network 101
09-12 13:58:39.676   874  1309 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-12 13:58:39.677  2686  2704 I BluetoothAdapterState: Entering PendingCommandState
09-12 13:58:39.677  2686  2686 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-12 13:58:39.677  2686  2686 D A2dpStateMachine: make
,09-12 13:58:39.684  2686  2686 I bt_bluedroid: get_profile_interface a2dp
,09-12 13:58:39.685  2686  2708 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-12 13:58:39.686  2686  4114 D A2dpStateMachine: Enter Disconnected: -2
,09-12 13:58:39.686  2686  2686 V BluetoothAdapterState: isTurningOff()=false
09-12 13:58:39.686  2686  2686 V BluetoothAdapterState: isTurningOn()=true
09-12 13:58:39.686  2686  4111 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 13:58:39.686  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:58:39.686  2686  2686 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:58:39.688  2686  2686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@73df50f
,09-12 13:58:39.689  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 13:58:39.689  2686  2686 D HidService: Received start request. Starting profile...
09-12 13:58:39.690  2686  2686 I bt_bluedroid: get_profile_interface hidhost
09-12 13:58:39.690  2686  2708 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb397b3e5
,09-12 13:58:39.690  4048  4048 D BluetoothInputDevice: Proxy object connected
09-12 13:58:39.690  2686  2708 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-12 13:58:39.690  4048  4048 D HidProfile: Bluetooth service connected
09-12 13:58:39.690  2686  2686 D HidService: setHidService(): set to: null
09-12 13:58:39.691  2686  2686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@73df50f
09-12 13:58:39.691  2686  2686 D HealthService: Received start request. Starting profile...,
09-12 13:58:39.692  2686  2686 I bt_bluedroid: get_profile_interface health
09-12 13:58:39.693  2686  2686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@73df50f
09-12 13:58:39.694  2686  2686 D PanService: Received start request. Starting profile...
09-12 13:58:39.694  2686  2686 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 13:58:39.694  2686  2686 I bt_bluedroid: get_profile_interface pan
,09-12 13:58:39.695  2686  2708 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-12 13:58:39.695  2686  2686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@73df50f
,09-12 13:58:39.696  2686  2686 D BluetoothMapService: Received start request. Starting profile...
,09-12 13:58:39.696  2686  2686 D BluetoothMapService: start()
,09-12 13:58:39.697  2686  2686 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-12 13:58:39.698  2686  2686 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-12 13:58:39.698  2686  2686 D BluetoothMapAppObserver: createReceiver()
09-12 13:58:39.698  2686  2686 D BluetoothMapAppObserver: initObservers()
,09-12 13:58:39.698  2686  2686 D BluetoothMapAppObserver: getEnabledAccountItems()
09-12 13:58:39.699  2686  2686 V BluetoothAdapterState: isTurningOff()=false
09-12 13:58:39.699  2686  2686 V BluetoothAdapterState: isTurningOn()=true
,09-12 13:58:39.699  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:58:39.699  2686  2686 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:58:39.699  2686  2686 V BluetoothAdapterState: isTurningOff()=false
,09-12 13:58:39.699  2686  2686 V BluetoothAdapterState: isTurningOn()=true
,09-12 13:58:39.699  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:58:39.699  2686  2686 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:58:39.701  2686  2686 V BluetoothAdapterState: isTurningOff()=false
,09-12 13:58:39.701  2686  2686 V BluetoothAdapterState: isTurningOn()=true
,09-12 13:58:39.701  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 13:58:39.701  2686  2686 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:58:39.701  2686  2686 V BluetoothAdapterState: isTurningOff()=false
09-12 13:58:39.701  2686  2686 V BluetoothAdapterState: isTurningOn()=true
,09-12 13:58:39.701  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 13:58:39.701  2686  2686 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:58:39.701  2686  2686 V BluetoothAdapterState: isTurningOff()=false
,09-12 13:58:39.701  2686  2686 V BluetoothAdapterState: isTurningOn()=true
09-12 13:58:39.701  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:58:39.701  2686  2686 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:58:39.702  2686  2704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-12 13:58:39.702  2686  2704 D BluetoothAdapterProperties: ScanMode =  20
09-12 13:58:39.702  2686  2704 D BluetoothAdapterProperties: State =  11
,09-12 13:58:39.702  2686  2704 D BluetoothAdapterProperties: Setting state to 12
09-12 13:58:39.702  2686  2704 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-12 13:58:39.702   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 13:58:39.703  2686  2704 I BluetoothAdapterState: Entering OnState
,09-12 13:58:39.703  4048  4060 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 13:58:39.703  2686  2708 D BluetoothAdapterProperties: Scan Mode:21
09-12 13:58:39.703  2686  2708 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 13:58:39.704  4048  4059 D BluetoothPan: onBluetoothStateChange on: true
09-12 13:58:39.705  1950  1965 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 13:58:39.707  4048  4060 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 13:58:39.707  1366  2028 D BluetoothPan: onBluetoothStateChange on: true
09-12 13:58:39.707  3841  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-12 13:58:39.710  3841  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-12 13:58:39.711  1366  1378 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 13:58:39.711  1366  1366 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 13:58:39.711  1366  1366 D PanProfile: Bluetooth service connected
,09-12 13:58:39.712  1366  1366 D BluetoothMap: Proxy object connected
,09-12 13:58:39.712  1366  1366 D MapProfile: Bluetooth service connected
,09-12 13:58:39.712  1366  1366 D BluetoothMap: getConnectedDevices()
09-12 13:58:39.712  1366  1384 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 13:58:39.713  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:39.713  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:39.713  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:39.713  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:39.713  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:39.713  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:58:39.713  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:58:39.713  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:58:39.715  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:58:39.715  1366  2028 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 13:58:39.716  1366  1366 D BluetoothInputDevice: Proxy object connected
,09-12 13:58:39.717  1366  1366 D HidProfile: Bluetooth service connected
09-12 13:58:39.717  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:39.717  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:39.717  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:39.717  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:39.717  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:39.717  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:58:39.717  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:58:39.717  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:58:39.718  1366  1378 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:58:39.718   874  1311 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-12 13:58:39.718   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 13:58:39.718   874  1311 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-12 13:58:39.718   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:58:39.719  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:58:39.719   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 13:58:39.719  4048  4059 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 13:58:39.719   874  1311 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-12 13:58:39.721   874   874 D BluetoothA2dp: Proxy object connected
,09-12 13:58:39.721   874  1311 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-12 13:58:39.721  1366  1366 D BluetoothA2dp: Proxy object connected
09-12 13:58:39.722   874  1311 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-12 13:58:39.724  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:39.724  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:39.724  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:39.724  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:39.724  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:39.724  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:58:39.724  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:58:39.724  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:58:39.726  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:58:39.727  2686  2686 D BluetoothMapMasInstance1: Map Service startRfcommSocketListener
,09-12 13:58:39.727  2686  2686 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-12 13:58:39.727  1366  2028 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 13:58:39.727  2686  2686 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:58:39.728   874  1311 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 13:58:39.728  2686  2686 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:58:39.729   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,09-12 13:58:39.730  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:39.731  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:39.732  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:39.733  2686  2686 D ObexServerSockets: Succeed to create listening sockets 
09-12 13:58:39.733  2686  2686 D ObexServerSockets1: startAccept()
,09-12 13:58:39.733  2686  2686 D ObexServerSockets1: prepareForNewConnect()
,09-12 13:58:39.733   874  1311 D ConnectivityService: scheduleUnvalidatedPrompt 101
09-12 13:58:39.734   874  1311 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-12 13:58:39.734   874  1311 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-12 13:58:39.734  4048  4048 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 13:58:39.734   874  1309 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-12 13:58:39.734   874  1311 D ConnectivityService:    accepting network in place of null
,09-12 13:58:39.734   874  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 13:58:39.734  2686  2686 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-12 13:58:39.735  2686  2686 D BluetoothSdpJni: SDP Create record success - handle: 1
09-12 13:58:39.735  2686  4121 D ObexServerSockets1: Accepting socket connection...
,09-12 13:58:39.735  2686  2686 D BluetoothMapService: onReceive
09-12 13:58:39.735  2686  2686 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:58:39.735  2686  2686 D BluetoothMapService: STATE_ON
,09-12 13:58:39.735  4048  4048 D PanProfile: Bluetooth service connected
09-12 13:58:39.735  4048  4048 D BluetoothMap: Proxy object connected
,09-12 13:58:39.735   874  1311 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-12 13:58:39.736  4048  4048 D MapProfile: Bluetooth service connected
,09-12 13:58:39.736  4048  4048 D BluetoothMap: getConnectedDevices()
09-12 13:58:39.736  2686  4123 D ObexServerSockets1: Accepting socket connection...
09-12 13:58:39.739  4048  4048 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-12 13:58:39.741  4048  4048 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-12 13:58:39.746  4048  4048 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 13:58:39.748  4048  4048 D BluetoothA2dp: Proxy object connected
09-12 13:58:39.753   874  4103 D NetlinkSocketObserver: NeighborEvent{elapsedMs=210193, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 13:58:39.754  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 13:58:39.757  2686  2686 D BluetoothMapMasInstance1: Map Service startRfcommSocketListener
09-12 13:58:39.757  2686  2686 D ObexServerSockets1: prepareForNewConnect()
,09-12 13:58:39.759  2686  4127 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:58:39.762   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-12 13:58:39.764  1366  1366 D BluetoothPbap: Proxy object connected
,09-12 13:58:39.764  1366  1366 D PbapServerProfile: Bluetooth service connected
09-12 13:58:39.769  2686  4132 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:58:39.770  2686  4132 I BtOppRfcommListener: Accept thread started.
,09-12 13:58:39.774  4048  4048 D DockEventReceiver: finishStartingService: stopping service
09-12 13:58:39.775  4048  4048 D BluetoothPbap: Proxy object connected
09-12 13:58:39.775  4048  4048 D PbapServerProfile: Bluetooth service connected
,09-12 13:58:39.787   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:58:39.789   874  1311 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-12 13:58:39.789   874  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:58:39.791   874  1311 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-12 13:58:39.792   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-12 13:58:39.803  1950  1965 D BluetoothHeadset: Proxy object connected
09-12 13:58:39.803   874   874 D BluetoothHeadset: Proxy object connected
09-12 13:58:39.804  1366  1378 D BluetoothHeadset: Proxy object connected
,09-12 13:58:39.804  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:39.804  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:39.804  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:39.804  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:39.804  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:39.804  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:39.804  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:58:39.804  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:58:39.804  1366  1366 D HeadsetProfile: Bluetooth service connected
,09-12 13:58:39.804   874   874 D BluetoothHeadset: Proxy object connected
09-12 13:58:39.804   874   874 D BluetoothHeadset: Proxy object connected
09-12 13:58:39.805  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:39.807  1950  2263 D BluetoothHeadset: Proxy object connected
,09-12 13:58:39.808  1743  1743 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 13:58:39.808  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:39.808  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:39.808  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:39.808  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:39.808  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:39.808  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:39.808  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:58:39.808  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:58:39.810  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:39.810  1743  1743 D SystemUpdateService: onCreate
,09-12 13:58:39.812  1743  1743 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 13:58:39.814  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:39.814  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:39.814  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:39.814  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:39.814  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:39.814  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:39.814  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:58:39.814  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:58:39.814  1743  4138 I SystemUpdateService: active receiver: enabled
,09-12 13:58:39.816  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:58:39.818  1743  4138 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-12 13:58:39.818  1366  2028 D BluetoothHeadset: Proxy object connected
09-12 13:58:39.818   874   891 D BluetoothHeadset: Proxy object connected
09-12 13:58:39.818   874   891 D BluetoothHeadset: Proxy object connected
09-12 13:58:39.819  1366  1366 D HeadsetProfile: Bluetooth service connected
09-12 13:58:39.820  1743  4138 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-12 13:58:39.820  1743  4138 I SystemUpdateService: now status is 0 (complete)
,09-12 13:58:39.820  1743  4138 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 13:58:39.820  1743  4138 I SystemUpdateService: file has been verified
09-12 13:58:39.820  1743  4138 I SystemUpdateService: OTA package size = 12249756
,09-12 13:58:39.824  1743  4138 I SystemUpdateService: showing system update notification
09-12 13:58:39.826   874  4102 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
09-12 13:58:39.827  1743  1743 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 13:58:39.829  1743  2318 I iu.UploadsManager: num queued entries: 0
09-12 13:58:39.830  1743  2318 I iu.UploadsManager: num updated entries: 0
,09-12 13:58:39.830  1743  2318 I iu.SyncManager: NEXT; no task
,09-12 13:58:39.833  1743  1743 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 13:58:39.834  1743  1743 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 13:58:39.835  3924  3924 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:58:39.837  1743  4142 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-12 13:58:39.837  1743  4142 W BaseAppContext: Using Auth Proxy for data requests.
,09-12 13:58:39.838  1743  1743 D SystemUpdateService: onDestroy
09-12 13:58:39.839  1743  4142 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
09-12 13:58:39.841  3924  3924 D SprintDMHelper: simOperator: 
09-12 13:58:39.841  3924  3924 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-12 13:58:39.844  4048  4059 D BluetoothHeadset: Proxy object connected
09-12 13:58:39.846  4048  4048 D HeadsetProfile: Bluetooth service connected
09-12 13:58:39.849  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 13:58:39.850  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:58:39.870  1523  2403 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-12 13:58:39.870  1523  2403 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-12 13:58:39.870  1523  2403 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:58:39.870  1523  2403 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:58:39.882  1743  4142 E MDM     : [176] SitrepService.a: Error sending sitrep.
,09-12 13:58:39.885   874  4102 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 11:58:39 GMT], X-Android-Received-Millis=[1473681519883], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473681519860]}
,09-12 13:58:39.886   874  1311 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 13:58:39.886   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-12 13:58:39.887   874  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 13:58:39.887   874  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 13:58:39.981  3050  4145 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 13:58:40.022  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:58:40.023  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:58:40.042  2686  2704 D BluetoothAdapterState: Current state: ON, message: 23
,09-12 13:58:40.042  2686  2704 D BluetoothAdapterProperties: Setting state to 13
,09-12 13:58:40.043  2686  2704 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-12 13:58:40.044  2686  2704 D BluetoothAdapterProperties: onBluetoothDisable()
,09-12 13:58:40.048  2686  2704 I BluetoothAdapterState: Entering PendingCommandState
,09-12 13:58:40.055  2686  2686 D BluetoothMapService: onReceive
,09-12 13:58:40.055  2686  2686 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:58:40.056  2686  2686 D BluetoothMapService: STATE_TURNING_OFF
,09-12 13:58:40.057  2686  2686 D BluetoothMapService: MAP Service closeService in
,09-12 13:58:40.057  2686  2686 D BluetoothMapMasInstance1: MAP Service shutdown
,09-12 13:58:40.058  2686  2686 D ObexServerSockets1: shutdown(block = true)
09-12 13:58:40.058  2686  4121 D ObexServerSockets1: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-12 13:58:40.061  2686  2686 D ObexServerSockets1: shutdown called from another thread - interrupt().
,09-12 13:58:40.063  2686  2708 D BluetoothAdapterProperties: Scan Mode:20
09-12 13:58:40.064  2686  2704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-12 13:58:40.068  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:58:40.068  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:40.068  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:40.068  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:40.068  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:40.068  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:58:40.068  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:40.068  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:58:40.068  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:58:40.071  4048  4048 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 13:58:40.071  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:58:40.071  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:58:40.072  2686  4123 D ObexServerSockets1: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-12 13:58:40.072  2686  4107 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-12 13:58:40.072  2686  2686 D ObexServerSockets1: shutdown called from another thread - interrupt().
,09-12 13:58:40.072  2686  2686 I BtOppRfcommListener: stopping Accept Thread
,09-12 13:58:40.072  2686  4132 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-12 13:58:40.074  2686  4132 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-12 13:58:40.075  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:58:40.075  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:40.075  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:40.075  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:40.075  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:40.075  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:58:40.075  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:40.075  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:58:40.075  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:58:40.076  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:58:40.076  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:40.079  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:58:40.079  2686  2686 D HeadsetService: Received stop request...Stopping profile...
,09-12 13:58:40.081  1950  2263 D BluetoothHeadset: Proxy object disconnected
09-12 13:58:40.081   874   874 D BluetoothHeadset: Proxy object disconnected
09-12 13:58:40.082  1366  1378 D BluetoothHeadset: Proxy object disconnected
09-12 13:58:40.082  2686  2686 D A2dpService: Received stop request...Stopping profile...
09-12 13:58:40.082   874   874 D BluetoothHeadset: Proxy object disconnected
09-12 13:58:40.082   874   874 D BluetoothHeadset: Proxy object disconnected
09-12 13:58:40.083  2686  4114 D A2dpStateMachine: Exit Disconnected: -1
09-12 13:58:40.083  4048  4059 D BluetoothHeadset: Proxy object disconnected
09-12 13:58:40.084   874   874 D BluetoothA2dp: Proxy object disconnected
,09-12 13:58:40.084  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:40.085  2686  2686 D HidService: Received stop request...Stopping profile...
09-12 13:58:40.085  2686  2686 D HidService: Stopping Bluetooth HidService
,09-12 13:58:40.085  1366  1366 D HeadsetProfile: Bluetooth service disconnected
09-12 13:58:40.085  1366  1366 D BluetoothA2dp: Proxy object disconnected
,09-12 13:58:40.086  1366  1366 D BluetoothInputDevice: Proxy object disconnected
,09-12 13:58:40.086  1366  1366 D HidProfile: Bluetooth service disconnected
,09-12 13:58:40.087  2686  2686 D HealthService: Received stop request...Stopping profile...
09-12 13:58:40.088  4048  4048 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:58:40.089  4048  4048 D HeadsetProfile: Bluetooth service disconnected
09-12 13:58:40.090  4048  4048 D BluetoothA2dp: Proxy object disconnected
09-12 13:58:40.090  4048  4048 D BluetoothInputDevice: Proxy object disconnected
09-12 13:58:40.090  4048  4048 D HidProfile: Bluetooth service disconnected
09-12 13:58:40.091  2686  2686 D PanService: Received stop request...Stopping profile...
09-12 13:58:40.092  1366  1366 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-12 13:58:40.093  4048  4048 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 13:58:40.093  1366  1366 D PanProfile: Bluetooth service disconnected
09-12 13:58:40.093  4048  4048 D PanProfile: Bluetooth service disconnected
09-12 13:58:40.093  2686  2686 V BluetoothAdapterState: isTurningOff()=true
,09-12 13:58:40.093  2686  2686 V BluetoothAdapterState: isTurningOn()=false
,09-12 13:58:40.093  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:58:40.093  2686  2686 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:58:40.095  2686  2686 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 13:58:40.095  2686  2708 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-12 13:58:40.095  2686  4104 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:58:40.095  2686  4104 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:58:40.095  2686  4104 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:58:40.095  2686  2686 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 13:58:40.095  2686  2708 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
09-12 13:58:40.096  2686  2686 D BluetoothMapService: Received stop request...Stopping profile...
09-12 13:58:40.096  2686  2686 D BluetoothMapService: stop()
09-12 13:58:40.096  2686  2686 D BluetoothMapAppObserver: deinitObservers()
09-12 13:58:40.096  2686  2686 D BluetoothMapAppObserver: removeReceiver()
09-12 13:58:40.098  1366  1366 D BluetoothMap: Proxy object disconnected
09-12 13:58:40.098  4048  4048 D BluetoothMap: Proxy object disconnected
09-12 13:58:40.098  1366  1366 D MapProfile: Bluetooth service disconnected
09-12 13:58:40.098  4048  4048 D MapProfile: Bluetooth service disconnected
09-12 13:58:40.098  2686  2686 V BluetoothAdapterState: isTurningOff()=true
09-12 13:58:40.098  2686  2686 V BluetoothAdapterState: isTurningOn()=false
09-12 13:58:40.098  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:58:40.098  2686  2686 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:58:40.101  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 13:58:40.102  2686  4104 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:58:40.102  2686  2686 V BluetoothAdapterState: isTurningOff()=true
,09-12 13:58:40.102  2686  2686 V BluetoothAdapterState: isTurningOn()=false
09-12 13:58:40.102  2686  4104 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 13:58:40.102  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 13:58:40.102  2686  2686 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:58:40.102  2686  4104 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:58:40.102  2686  4104 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:58:40.102  2686  4104 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:58:40.102  2686  4104 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-12 13:58:40.102  2686  2686 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-12 13:58:40.102  2686  2708 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-12 13:58:40.102  2686  2686 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-12 13:58:40.103  2686  2686 V BluetoothAdapterState: isTurningOff()=true
09-12 13:58:40.103  2686  2686 V BluetoothAdapterState: isTurningOn()=false
09-12 13:58:40.103  2686  2708 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 13:58:40.103  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:58:40.103  2686  2686 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:58:40.103  2686  2686 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-12 13:58:40.103  2686  2708 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-12 13:58:40.104  2686  2686 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-12 13:58:40.104  2686  2686 V BluetoothAdapterState: isTurningOff()=true
09-12 13:58:40.104  2686  2686 V BluetoothAdapterState: isTurningOn()=false
09-12 13:58:40.104  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:58:40.104  2686  2686 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:58:40.104  2686  2686 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 13:58:40.105  2686  2686 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 13:58:40.106  2686  2686 D BluetoothMapService: MAP Service closeService in
09-12 13:58:40.106  2686  2686 V BluetoothAdapterState: isTurningOff()=true
09-12 13:58:40.106  2686  2686 V BluetoothAdapterState: isTurningOn()=false
09-12 13:58:40.106  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:58:40.106  2686  2686 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:58:40.106  2686  2704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-12 13:58:40.106  2686  2704 D BluetoothAdapterProperties: Setting state to 15
09-12 13:58:40.106  2686  2704 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-12 13:58:40.106  2686  2686 D BluetoothMapService: cleanup()
09-12 13:58:40.106  2686  2686 D BluetoothMapService: MAP Service closeService in
09-12 13:58:40.107  2686  2704 I BluetoothAdapterState: Entering BleOnState
,09-12 13:58:40.107   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:58:40.107  4048  4060 D BluetoothMap: onBluetoothStateChange: up=false
09-12 13:58:40.108  4048  4059 D BluetoothPan: onBluetoothStateChange on: false
09-12 13:58:40.109  4048  4048 D BluetoothPbap: Proxy object disconnected
,09-12 13:58:40.109  1366  1366 D BluetoothPbap: Proxy object disconnected
09-12 13:58:40.110  1366  1366 D PbapServerProfile: Bluetooth service disconnected
09-12 13:58:40.110  4048  4060 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 13:58:40.114  1950  2276 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 13:58:40.114  4048  4120 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 13:58:40.115  4048  4059 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:58:40.115  1366  1693 D BluetoothPan: onBluetoothStateChange on: false
09-12 13:58:40.116  1366  1378 D BluetoothMap: onBluetoothStateChange: up=false
,09-12 13:58:40.118  1366  2028 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 13:58:40.109  4048  4048 D PbapServerProfile: Bluetooth service disconnected
09-12 13:58:40.118  1366  1384 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-12 13:58:40.119  1366  1693 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:58:40.119   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:58:40.119   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:58:40.119   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 13:58:40.119  4048  4060 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 13:58:40.120  1366  1378 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 13:58:40.121  2686  2704 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-12 13:58:40.121  2686  2704 D BluetoothAdapterProperties: Setting state to 16
09-12 13:58:40.121  2686  2704 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-12 13:58:40.121  2686  2704 D BluetoothAdapterProperties: onBleDisable
09-12 13:58:40.121  2686  2704 I BluetoothAdapterState: Entering PendingCommandState
,09-12 13:58:40.121  2686  2705 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-12 13:58:40.124  2686  4104 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 13:58:40.124  2686  4104 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:58:40.125  2686  2708 D BluetoothAdapterProperties: Scan Mode:20
09-12 13:58:40.125  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:58:40.125  4048  4048 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 13:58:40.128  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:58:40.132  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:40.134  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 13:58:40.134  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:58:40.134  4048  4048 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:58:40.324  2686  2708 I bt_hci  : shut_down
,09-12 13:58:40.325  2686  4062 D bt_hwcfg: hw_epilog_process
,09-12 13:58:40.327  2686  4062 I bt_vendor: low_power_mode_cb
,09-12 13:58:40.351  2686  4062 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-12 13:58:40.351  2686  4062 I bt_vendor: epilog_cb
09-12 13:58:40.351  2686  4062 I bt_hci  : epilog_finished_callback
,09-12 13:58:40.353  2686  2708 I bt_hci_h4: hal_close
,09-12 13:58:40.354  2686  2708 I bt_userial_vendor: device fd = 57 close
,09-12 13:58:40.497  2686  2705 D bt_stack_manager: event_shut_down_stack finished.
,09-12 13:58:40.498  2686  2704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-12 13:58:40.505  2686  2686 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 13:58:40.505  2686  2704 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-12 13:58:40.507  2686  2686 D BtGatt.GattService: Received stop request...Stopping profile...
09-12 13:58:40.507  2686  2686 D BtGatt.GattService: stop()
09-12 13:58:40.507  2686  2686 D BtGatt.AdvertiseManager: advertise clients cleared
,09-12 13:58:40.512  2686  2686 V BluetoothAdapterState: isTurningOff()=false
09-12 13:58:40.512  2686  2686 V BluetoothAdapterState: isTurningOn()=false
,09-12 13:58:40.512  2686  2686 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 13:58:40.513  2686  2686 V BluetoothAdapterState: isBleTurningOff()=true
,09-12 13:58:40.513  2686  2704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-12 13:58:40.514  2686  2704 D BluetoothAdapterProperties: Setting state to 10
09-12 13:58:40.514  2686  2704 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-12 13:58:40.516  2686  2704 I BluetoothAdapterState: Entering OffState
09-12 13:58:40.517   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-12 13:58:40.548  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:58:40.548  3841  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:40.548  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:40.548  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:40.548  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:40.548  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:58:40.548  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:40.548  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:58:40.548  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:58:40.549  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:58:40.549  3841  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:40.549  2686  2686 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-12 13:58:40.549  2686  2686 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-12 13:58:40.550  2686  2705 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-12 13:58:40.556  2686  2686 I BluetoothServiceJni: cleanupNative: return from cleanup
09-12 13:58:40.557  2686  2705 D bt_stack_manager: event_clean_up_stack finished.
,09-12 13:58:40.559  2686  2686 I art     : System.exit called, status: 0
,09-12 13:58:40.559  2686  2686 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 13:58:40.649   874  3164 I ActivityManager: Process com.android.bluetooth (pid 2686) has died
,09-12 13:58:40.651   874  3164 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
,09-12 13:58:40.790   874  1311 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-12 13:58:41.699   874   887 I ActivityManager: Start proc 4160:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-12 13:58:41.812  4160  4160 D AdapterServiceConfig: Adding HeadsetService
09-12 13:58:41.812  4160  4160 D AdapterServiceConfig: Adding A2dpService
09-12 13:58:41.813  4160  4160 D AdapterServiceConfig: Adding HidService
09-12 13:58:41.813  4160  4160 D AdapterServiceConfig: Adding HealthService
09-12 13:58:41.813  4160  4160 D AdapterServiceConfig: Adding PanService
09-12 13:58:41.813  4160  4160 D AdapterServiceConfig: Adding GattService
,09-12 13:58:41.813  4160  4160 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 13:58:41.827   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@858468e:true
,09-12 13:58:41.827  4160  4160 D BluetoothAdapterState: make() - Creating AdapterState
,09-12 13:58:41.831  4160  4160 I bt_bluedroid: init
,09-12 13:58:41.831  4160  4172 I BluetoothAdapterState: Entering OffState
,09-12 13:58:41.836  4160  4173 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-12 13:58:41.837  4160  4173 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-12 13:58:41.837  4160  4173 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-12 13:58:41.838  4160  4173 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-12 13:58:41.839  4160  4160 I bt_bluedroid: get_profile_interface socket
,09-12 13:58:41.841  4160  4160 I bt_bluedroid: get_profile_interface sdp
,09-12 13:58:41.845  4160  4171 I bt_bluedroid: config_hci_snoop_log
,09-12 13:58:41.845  4160  4176 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 13:58:41.848   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-12 13:58:41.848  4160  4176 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 13:58:41.857  4160  4172 D BluetoothAdapterState: Current state: OFF, message: 0
,09-12 13:58:41.857  4160  4172 D BluetoothAdapterProperties: Setting state to 14
,09-12 13:58:41.858  4160  4172 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-12 13:58:41.861  4160  4172 D BluetoothBondStateMachine: make
,09-12 13:58:41.866  4160  4177 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 13:58:41.874  4160  4172 I BluetoothAdapterState: Entering PendingCommandState
,09-12 13:58:41.876  4160  4160 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 13:58:41.882  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@73df50f
,09-12 13:58:41.883  4160  4160 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 13:58:41.884  4160  4160 D BtGatt.GattService: Received start request. Starting profile...
,09-12 13:58:41.885  4160  4160 D BtGatt.GattService: start()
09-12 13:58:41.885  4160  4160 I bt_bluedroid: get_profile_interface gatt
,09-12 13:58:41.886  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@73df50f
,09-12 13:58:41.887  4160  4160 D BtGatt.AdvertiseManager: advertise manager created
,09-12 13:58:41.898  4160  4160 V BluetoothAdapterState: isTurningOff()=false
,09-12 13:58:41.898  4160  4160 V BluetoothAdapterState: isTurningOn()=false
09-12 13:58:41.899  4160  4160 V BluetoothAdapterState: isBleTurningOn()=true
,09-12 13:58:41.899  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:58:41.900  4160  4172 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-12 13:58:41.900  4160  4172 I bt_bluedroid: enable
,09-12 13:58:41.901  4160  4173 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-12 13:58:41.902  4160  4173 I bt_hci  : start_up
,09-12 13:58:41.924  4160  4173 I bt_vendor: alloc value 0xb3a1c189
,09-12 13:58:41.924  4160  4173 I bt_vendor: init
09-12 13:58:41.925  4160  4173 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-12 13:58:41.925  4160  4173 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 13:58:42.032  4160  4173 D bt_hci  : start_up starting async portion
,09-12 13:58:42.033  4160  4180 I bt_hci  : event_finish_startup
09-12 13:58:42.033  4160  4180 I bt_hci_h4: hal_open
,09-12 13:58:42.034  4160  4180 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 13:58:42.042  4160  4180 I bt_userial_vendor: device fd = 51 open
,09-12 13:58:42.065  4160  4172 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-12 13:58:42.074  4160  4180 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 13:58:42.105  4160  4180 D bt_hwcfg: Chipset BCM4354A2
,09-12 13:58:42.106  4160  4180 D bt_hwcfg: Target name = [BCM4354A2]
,09-12 13:58:42.107  4160  4180 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 13:58:42.569  4160  4172 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-12 13:58:42.582  4160  4180 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-12 13:58:42.582  4160  4180 D bt_hwcfg: Settlement delay -- 100 ms
09-12 13:58:42.582  4160  4180 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 13:58:42.698  4160  4180 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 13:58:42.700  4160  4180 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 13:58:42.731  4160  4180 I bt_hwcfg: vendor lib fwcfg completed
,09-12 13:58:42.731  4160  4180 I bt_vendor: firmware callback
09-12 13:58:42.732  4160  4180 I bt_hci  : firmware_config_callback
,09-12 13:58:42.743  4160  4182 I bt_btu  : btu_task pending for preload complete event
,09-12 13:58:42.744  4160  4182 I bt_btu_task: Bluetooth chip preload is complete
09-12 13:58:42.744  4160  4182 I bt_btu  : btu_task received preload complete event
,09-12 13:58:42.754  4160  4182 I         : BTE_InitTraceLevels -- TRC_HCI
,09-12 13:58:42.754  4160  4182 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-12 13:58:42.755  4160  4182 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-12 13:58:42.755  4160  4182 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-12 13:58:42.755  4160  4182 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-12 13:58:42.756  4160  4182 I         : BTE_InitTraceLevels -- TRC_A2D
,09-12 13:58:42.756  4160  4182 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-12 13:58:42.756  4160  4182 I         : BTE_InitTraceLevels -- TRC_BTM
,09-12 13:58:42.756  4160  4182 I         : BTE_InitTraceLevels -- TRC_GAP
,09-12 13:58:42.757  4160  4182 I         : BTE_InitTraceLevels -- TRC_PAN,
09-12 13:58:42.757  4160  4182 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 13:58:42.757  4160  4182 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 13:58:42.757  4160  4182 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 13:58:42.758  4160  4182 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 13:58:42.758  4160  4182 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 13:58:42.897  4160  4182 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3999d9d
,09-12 13:58:42.897  4160  4182 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3999d9d 
,09-12 13:58:42.908  4160  4176 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-12 13:58:42.910  4160  4176 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 13:58:42.911  4160  4176 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 13:58:42.913  4160  4176 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 13:58:42.918  4160  4176 D BluetoothAdapterProperties: Scan Mode:20
,09-12 13:58:42.920  4160  4176 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 13:58:42.921  4160  4176 D bt_hci  : do_postload posting postload work item
,09-12 13:58:42.921  4160  4180 I bt_hci  : event_postload
09-12 13:58:42.921  4160  4180 I bt_vendor: sco_config_cb
09-12 13:58:42.921  4160  4180 I bt_hci  : sco_config_callback postload finished.
,09-12 13:58:42.926  4160  4176 D bt_bte_conf: Device ID record 1 : primary
09-12 13:58:42.926  4160  4176 D bt_bte_conf:   vendorId            = 000f
09-12 13:58:42.926  4160  4176 D bt_bte_conf:   vendorIdSource      = 0001
09-12 13:58:42.926  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:58:42.926  4160  4176 D bt_bte_conf:   product             = 1200
09-12 13:58:42.927  4160  4176 D bt_bte_conf:   version             = 1436
09-12 13:58:42.927  4160  4176 D bt_bte_conf:   clientExecutableURL = 
09-12 13:58:42.928  4160  4176 D bt_bte_conf:   serviceDescription  = 
09-12 13:58:42.928  4160  4176 D bt_bte_conf:   documentationURL    = 
09-12 13:58:42.928  4160  4176 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-12 13:58:42.929  4160  4173 D bt_stack_manager: event_start_up_stack finished
09-12 13:58:42.931  4160  4172 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-12 13:58:42.932  4160  4172 D BluetoothAdapterProperties: Setting state to 15
09-12 13:58:42.932  4160  4172 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-12 13:58:42.932  4160  4180 I bt_vendor: low_power_mode_cb
09-12 13:58:42.933  4160  4172 I BluetoothAdapterState: Entering BleOnState
09-12 13:58:42.938  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:58:42.940  4160  4172 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-12 13:58:42.941  4160  4172 D BluetoothAdapterProperties: Setting state to 11
09-12 13:58:42.941  4160  4172 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-12 13:58:42.949  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@73df50f
,09-12 13:58:42.949  4160  4160 D HeadsetService: Received start request. Starting profile...
,09-12 13:58:42.952  4160  4160 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-12 13:58:42.953  4160  4160 D HeadsetStateMachine: make
,09-12 13:58:42.960  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:42.963  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:42.971  4160  4172 I BluetoothAdapterState: Entering PendingCommandState
,09-12 13:58:42.972  4160  4160 D HeadsetStateMachine: max_hf_connections = 1
,09-12 13:58:42.972  4160  4160 I bt_bluedroid: get_profile_interface handsfree
,09-12 13:58:42.973  4160  4176 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-12 13:58:42.973  4160  4176 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-12 13:58:42.977  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@73df50f
,09-12 13:58:42.977  4160  4160 D A2dpService: Received start request. Starting profile...
,09-12 13:58:42.978  4160  4160 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-12 13:58:42.979  4160  4160 I bt_bluedroid: get_profile_interface avrcp
,09-12 13:58:42.986  4160  4160 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 13:58:42.987  4160  4160 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-12 13:58:42.987  4160  4160 D A2dpStateMachine: make
,09-12 13:58:42.989  4160  4160 I bt_bluedroid: get_profile_interface a2dp
,09-12 13:58:42.990  4160  4176 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-12 13:58:42.994  4160  4191 D A2dpStateMachine: Enter Disconnected: -2
,09-12 13:58:42.995  4160  4160 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 13:58:42.998  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@73df50f
,09-12 13:58:42.999  4160  4160 D HidService: Received start request. Starting profile...
,09-12 13:58:43.000  4160  4160 I bt_bluedroid: get_profile_interface hidhost
,09-12 13:58:43.000  4160  4176 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb397b3e5
,09-12 13:58:43.001  4160  4176 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-12 13:58:43.001  4160  4160 D HidService: setHidService(): set to: null
,09-12 13:58:43.003  4160  4160 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-12 13:58:43.005  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@73df50f
,09-12 13:58:43.006  4160  4160 D HealthService: Received start request. Starting profile...
,09-12 13:58:43.009  4160  4160 I bt_bluedroid: get_profile_interface health
,09-12 13:58:43.013  4160  4160 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 13:58:43.015  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@73df50f
,09-12 13:58:43.017  4160  4160 D PanService: Received start request. Starting profile...
,09-12 13:58:43.017  4160  4160 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-12 13:58:43.018  4160  4160 I bt_bluedroid: get_profile_interface pan
,09-12 13:58:43.018  4160  4176 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-12 13:58:43.023  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 13:58:43.026  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@73df50f
09-12 13:58:43.027  4160  4160 D BluetoothMapService: Received start request. Starting profile...
09-12 13:58:43.027  4160  4160 D BluetoothMapService: start()
,09-12 13:58:43.029  4160  4160 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-12 13:58:43.030  4160  4160 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-12 13:58:43.030  4160  4160 D BluetoothMapAppObserver: createReceiver()
09-12 13:58:43.032  4160  4160 D BluetoothMapAppObserver: initObservers()
,09-12 13:58:43.032  4160  4160 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-12 13:58:43.039  4160  4160 V BluetoothAdapterState: isTurningOff()=false
09-12 13:58:43.039  4160  4160 V BluetoothAdapterState: isTurningOn()=true
09-12 13:58:43.039  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:58:43.040  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:58:43.042  4160  4160 V BluetoothAdapterState: isTurningOff()=false
09-12 13:58:43.042  4160  4160 V BluetoothAdapterState: isTurningOn()=true
09-12 13:58:43.042  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:58:43.042  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:58:43.042  4160  4160 V BluetoothAdapterState: isTurningOff()=false
09-12 13:58:43.042  4160  4160 V BluetoothAdapterState: isTurningOn()=true
09-12 13:58:43.042  4160  4189 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 13:58:43.042  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:58:43.042  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:58:43.043  4160  4160 V BluetoothAdapterState: isTurningOff()=false
09-12 13:58:43.043  4160  4160 V BluetoothAdapterState: isTurningOn()=true
09-12 13:58:43.043  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:58:43.043  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:58:43.043  4160  4160 V BluetoothAdapterState: isTurningOff()=false
,09-12 13:58:43.043  4160  4160 V BluetoothAdapterState: isTurningOn()=true
09-12 13:58:43.043  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:58:43.043  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:58:43.048  4160  4160 V BluetoothAdapterState: isTurningOff()=false
09-12 13:58:43.048  4160  4160 V BluetoothAdapterState: isTurningOn()=true
09-12 13:58:43.049  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:58:43.049  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:58:43.049  4160  4172 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-12 13:58:43.049  4160  4172 D BluetoothAdapterProperties: ScanMode =  20
,09-12 13:58:43.049  4160  4172 D BluetoothAdapterProperties: State =  11
,09-12 13:58:43.050  4160  4172 D BluetoothAdapterProperties: Setting state to 12
,09-12 13:58:43.051  4160  4172 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-12 13:58:43.051  4160  4172 I BluetoothAdapterState: Entering OnState
09-12 13:58:43.051   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:58:43.052  4160  4176 D BluetoothAdapterProperties: Scan Mode:21
,09-12 13:58:43.052  4160  4176 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 13:58:43.053  4048  4060 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 13:58:43.056  4048  4120 D BluetoothPan: onBluetoothStateChange on: true
,09-12 13:58:43.058  4048  4048 D BluetoothMap: Proxy object connected
,09-12 13:58:43.058  4048  4048 D MapProfile: Bluetooth service connected
,09-12 13:58:43.058  4048  4048 D BluetoothMap: getConnectedDevices()
09-12 13:58:43.059  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:43.059  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:43.059  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:43.059  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:43.059  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:43.059  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:43.059  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:58:43.059  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:58:43.060  4160  4160 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 13:58:43.061  4048  4059 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 13:58:43.061  4160  4160 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-12 13:58:43.062  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:58:43.063  4160  4160 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:58:43.064  1950  1971 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 13:58:43.065  4160  4160 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:58:43.066  4048  4060 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 13:58:43.067  4160  4160 D ObexServerSockets: Succeed to create listening sockets 
,09-12 13:58:43.067  4160  4160 D ObexServerSockets0: startAccept()
,09-12 13:58:43.067  4160  4160 D ObexServerSockets0: prepareForNewConnect()
,09-12 13:58:43.069  4160  4160 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-12 13:58:43.069  4048  4120 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:58:43.069  4160  4160 D BluetoothSdpJni: SDP Create record success - handle: 0
09-12 13:58:43.070  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:43.070  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:43.070  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:43.070  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:43.070  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:43.070  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:43.070  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:58:43.070  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:58:43.070  1366  1693 D BluetoothPan: onBluetoothStateChange on: true
09-12 13:58:43.072  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:43.073  1366  1384 D BluetoothMap: onBluetoothStateChange: up=true
09-12 13:58:43.073  1366  1366 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 13:58:43.073  1366  1366 D PanProfile: Bluetooth service connected
,09-12 13:58:43.074  1366  2028 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 13:58:43.074  1366  1366 D BluetoothMap: Proxy object connected
09-12 13:58:43.075  1366  1366 D MapProfile: Bluetooth service connected
09-12 13:58:43.075  1366  1366 D BluetoothMap: getConnectedDevices()
,09-12 13:58:43.075  3841  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:43.075  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:43.075  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:43.075  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:43.075  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:43.075  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:43.075  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:58:43.075  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:58:43.077  1366  1384 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 13:58:43.077  3841  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:58:43.078  1366  1366 D BluetoothA2dp: Proxy object connected
,09-12 13:58:43.078  4160  4197 D ObexServerSockets0: Accepting socket connection...
,09-12 13:58:43.078  4160  4198 D ObexServerSockets0: Accepting socket connection...
,09-12 13:58:43.078  4048  4048 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 13:58:43.078  4048  4048 D PanProfile: Bluetooth service connected
,09-12 13:58:43.078   874  1377 D WifiService: setWifiEnabled: false pid=3841, uid=10000
,09-12 13:58:43.079   874  1377 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 13:58:43.079  4048  4048 D BluetoothA2dp: Proxy object connected
,09-12 13:58:43.079  1366  2028 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 13:58:43.079   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 13:58:43.080   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:58:43.080   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 13:58:43.081   874   874 D BluetoothA2dp: Proxy object connected
09-12 13:58:43.081   874  1903 D WifiService: setWifiEnabled: false pid=3841, uid=10000
09-12 13:58:43.081   874  1903 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 13:58:43.081  4048  4059 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 13:58:43.082  1366  1366 D BluetoothInputDevice: Proxy object connected
09-12 13:58:43.082  1366  1366 D HidProfile: Bluetooth service connected
09-12 13:58:43.082  1366  1693 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 13:58:43.084   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-12 13:58:43.085  4160  4160 D BluetoothMapService: onReceive
,09-12 13:58:43.086  4160  4160 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:58:43.086  4160  4160 D BluetoothMapService: STATE_ON
09-12 13:58:43.087  4048  4048 D BluetoothInputDevice: Proxy object connected
,09-12 13:58:43.087  4048  4048 D HidProfile: Bluetooth service connected
09-12 13:58:43.090  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:43.092  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:58:43.095  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-12 13:58:43.096   874  1309 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-12 13:58:43.096   874  1309 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-12 13:58:43.096   874  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 13:58:43.096   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 13:58:43.098  4048  4048 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 13:58:43.106  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 13:58:43.110   874  1309 E native  : do suspend true
,09-12 13:58:43.112  4048  4048 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:58:43.115  1366  1366 D BluetoothPbap: Proxy object connected
,09-12 13:58:43.115  4048  4048 D BluetoothPbap: Proxy object connected
09-12 13:58:43.115  4048  4048 D PbapServerProfile: Bluetooth service connected
09-12 13:58:43.115  1366  1366 D PbapServerProfile: Bluetooth service connected
,09-12 13:58:43.115  4160  4160 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 13:58:43.115  4160  4160 D ObexServerSockets0: prepareForNewConnect()
,09-12 13:58:43.121   370   872 D CommandListener: Clearing all IP addresses on wlan0
,09-12 13:58:43.121   874  1854 D DhcpClient: Clearing IP address
,09-12 13:58:43.123   370   872 D CommandListener: Setting iface cfg
,09-12 13:58:43.124  1523  4152 V NativeCrypto: Read error: ssl=0x99e4b000: I/O error during system call, Connection timed out
,09-12 13:58:43.125  1523  4152 V NativeCrypto: SSL shutdown failed: ssl=0x99e4b000: I/O error during system call, Broken pipe
09-12 13:58:43.126   874  2064 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
09-12 13:58:43.126   874  4102 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
09-12 13:58:43.129   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-12 13:58:43.129   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-12 13:58:43.130   874  1309 D WifiStateMachine: Start Disconnecting Watchdog 2
09-12 13:58:43.131   874  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 13:58:43.131   874  1309 E native  : do suspend true
,09-12 13:58:43.131   393   393 E Parcel  : Reading a NULL string not supported here.
09-12 13:58:43.132  4160  4206 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:58:43.133   874  4102 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-12 13:58:43.134   874  1311 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-12 13:58:43.150   874  4105 D DhcpClient: Receive thread stopped
09-12 13:58:43.151  4160  4212 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:58:43.152  4160  4212 I BtOppRfcommListener: Accept thread started.
,09-12 13:58:43.156  1950  2138 D BluetoothHeadset: Proxy object connected
,09-12 13:58:43.156   874   874 D BluetoothHeadset: Proxy object connected
,09-12 13:58:43.156  1366  2028 D BluetoothHeadset: Proxy object connected
,09-12 13:58:43.157   874   874 D BluetoothHeadset: Proxy object connected
09-12 13:58:43.157   874   874 D BluetoothHeadset: Proxy object connected,
,09-12 13:58:43.157  4048  4120 D BluetoothHeadset: Proxy object connected
,09-12 13:58:43.157  4048  4048 D HeadsetProfile: Bluetooth service connected
,09-12 13:58:43.160  1366  1366 D HeadsetProfile: Bluetooth service connected
,09-12 13:58:43.165  1950  1971 D BluetoothHeadset: Proxy object connected
,09-12 13:58:43.170   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:58:43.171  4048  4059 D BluetoothHeadset: Proxy object connected
,09-12 13:58:43.171  4048  4048 D HeadsetProfile: Bluetooth service connected
,09-12 13:58:43.179  1366  1693 D BluetoothHeadset: Proxy object connected
09-12 13:58:43.179  1366  1366 D HeadsetProfile: Bluetooth service connected
,09-12 13:58:43.181   874   891 D BluetoothHeadset: Proxy object connected
09-12 13:58:43.181   874   891 D BluetoothHeadset: Proxy object connected
,09-12 13:58:43.200   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:58:43.201   370   872 D CommandListener: Clearing all IP addresses on wlan0
09-12 13:58:43.201   874  1311 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-12 13:58:43.201   874  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:58:43.204   874  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 13:58:43.207   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-12 13:58:43.211  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:43.211  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:43.211  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:43.211  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:43.211  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:43.211  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:58:43.211  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:58:43.211  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:58:43.213  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:58:43.216  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:43.216  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:43.216  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:43.216  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:43.216  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:43.216  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:58:43.216  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:58:43.216  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:58:43.218  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:58:43.227  1743  1743 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 13:58:43.228   874  1309 D WifiConfigStore: Retrieve network priorities after PNO.
09-12 13:58:43.230  1743  1743 D SystemUpdateService: onCreate
09-12 13:58:43.234  1743  1743 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-12 13:58:43.234  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:43.234  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:43.234  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:43.234  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:58:43.234  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:43.234  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:58:43.234  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:58:43.234  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:58:43.234   874  1309 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-12 13:58:43.236  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:58:43.239  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:43.239  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:43.239  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:43.239  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:58:43.239  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:43.239  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:58:43.239  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:58:43.239  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:58:43.241  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:58:43.242  2076  2329 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 13:58:43.244  1743  4218 I SystemUpdateService: active receiver: enabled
,09-12 13:58:43.248  1743  1743 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 13:58:43.248  1743  4218 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 13:58:43.250  1743  4218 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-12 13:58:43.251  1743  4218 I SystemUpdateService: now status is 0 (complete)
,09-12 13:58:43.252  1743  4218 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-12 13:58:43.252  1743  1743 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-12 13:58:43.252  1743  2318 I iu.UploadsManager: num queued entries: 0
,09-12 13:58:43.253  1743  2318 I iu.UploadsManager: num updated entries: 0
,09-12 13:58:43.253  1743  2318 I iu.SyncManager: NEXT; no task
09-12 13:58:43.254  1743  1743 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000,
,09-12 13:58:43.254  1743  4218 I SystemUpdateService: file has been verified
09-12 13:58:43.256  3924  3924 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:58:43.259  1743  4218 I SystemUpdateService: OTA package size = 12249756
,09-12 13:58:43.261  3924  3924 D SprintDMHelper: simOperator: 
,09-12 13:58:43.261  3924  3924 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 13:58:43.267  1743  4218 I SystemUpdateService: showing system update notification
,09-12 13:58:43.274  3050  4222 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-12 13:58:43.280  1743  1743 D SystemUpdateService: onDestroy
,09-12 13:58:43.285   370   872 E Netd    : netlink response contains error (No such file or directory)
09-12 13:58:43.286   874  1311 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-12 13:58:43.286   874  1311 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 13:58:43.596  3841  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:43.596  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:43.596  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:43.596  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:58:43.596  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:43.596  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:58:43.596  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:58:43.596  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:58:43.603  3841  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:58:43.606   874  2065 D WifiService: setWifiEnabled: true pid=3841, uid=10000
,09-12 13:58:43.606   874  2065 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 13:58:43.619   874   885 D WifiService: setWifiEnabled: true pid=3841, uid=10000
,09-12 13:58:43.619   874   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 13:58:43.623   874  1309 D WifiConfigStore: Loading config and enabling all networks 
,09-12 13:58:43.639  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-12 13:58:43.639  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:43.639  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:43.639  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:43.639  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:43.639  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:58:43.639  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:58:43.639  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:58:43.645  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:58:43.651   874  1309 D WifiConfigStore: loaded 0 passpoint configs
,09-12 13:58:43.652   874  1309 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-12 13:58:43.653   874  1309 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-12 13:58:43.653   874  1309 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-12 13:58:43.654   874  1309 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-12 13:58:43.654   874  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-12 13:58:43.654   874  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK,
,09-12 13:58:43.654  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:43.654  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:43.654  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:43.654  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:43.654  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:43.654  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:58:43.654  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:58:43.654  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:58:43.659  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:58:43.669   370   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-12 13:58:43.671   874  1309 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=66.00 rxSuccessRate=105.50 delta 1000 -> 1
09-12 13:58:43.671   370   872 D CommandListener: Setting iface cfg
09-12 13:58:43.671   874  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-12 13:58:43.671   874  1308 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-12 13:58:43.671   874  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 13:58:43.673   874  1308 D WifiNative-HAL: p2pGetDeviceAddress
09-12 13:58:43.674   874  1308 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-12 13:58:43.688   874  1309 E native  : do suspend true
,09-12 13:58:43.707   874  1309 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=1 roam=3
,09-12 13:58:43.707   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:58:43.721   874  1309 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 13:58:43.777   874  1309 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 13:58:44.135  3841  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:44.135  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:44.135  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:44.135  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:44.135  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:44.135  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:58:44.135  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:58:44.135  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:58:44.142  3841  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:58:44.159  3841  4231 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-12 13:58:44.159  3841  4231 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 13:58:44.675  3841  4233 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-12 13:58:44.676  3841  4231 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-12 13:58:44.677  3841  4233 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-12 13:58:44.677  3841  4231 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-12 13:58:44.679  3841  4233 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 13:58:44.679  3841  4231 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 13:58:44.681  3841  4231 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 13:58:44.682  3841  4231 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-12 13:58:44.691  3841  4233 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 13:58:44.699  3841  4238 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 491, name: IncomingSocketThread/Sender)
,09-12 13:58:44.702  3841  4237 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 493, name: OutgoingSocketThread/Receiver)
,09-12 13:58:44.702  3841  4237 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 493, thread name: OutgoingSocketThread/Receiver)
09-12 13:58:44.702  3841  4237 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-12 13:58:44.703  3841  4237 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 493, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-12 13:58:44.704  3841  4233 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-12 13:58:44.705  3841  4236 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 492, name: OutgoingSocketThread/Sender)
,09-12 13:58:44.707  3841  4239 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 494, name: IncomingSocketThread/Receiver)
,09-12 13:58:44.707  3841  4239 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 494, thread name: IncomingSocketThread/Receiver)
09-12 13:58:44.708  3841  4239 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-12 13:58:44.708  3841  4239 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 494, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-12 13:58:45.139  1458  1458 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 13:58:45.182  3841  3888 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-12 13:58:45.184  3841  3888 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-12 13:58:45.192  3841  3888 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@e6ed32b Bundle[{}]
09-12 13:58:45.194  3841  3888 I io.jxcore.node.LifeCycleMonitor: start: OK
09-12 13:58:45.194  3841  3888 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-12 13:58:45.197  3841  3888 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-12 13:58:45.202  3841  3888 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-12 13:58:45.203  3841  3888 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-12 13:58:45.204  3841  3888 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 13:58:45.212  3841  4241 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-12 13:58:45.212  3841  4241 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 13:58:45.220  3841  4243 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-12 13:58:45.221  3841  4243 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-12 13:58:45.221  3841  4243 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 13:58:45.221  3841  4243 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 13:58:45.221  3841  4241 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-12 13:58:45.221  3841  4241 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-12 13:58:45.222  3841  4241 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 13:58:45.222  3841  4243 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-12 13:58:45.224  3841  4246 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 506, name: IncomingSocketThread/Receiver)
09-12 13:58:45.224  3841  4241 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 13:58:45.225  3841  4246 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 506, thread name: IncomingSocketThread/Receiver)
09-12 13:58:45.225  3841  4246 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-12 13:58:45.225  3841  4246 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 506, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-12 13:58:45.225  3841  4241 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-12 13:58:45.225  3841  4247 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 507, name: OutgoingSocketThread/Sender)
,09-12 13:58:45.231  3841  4245 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 505, name: IncomingSocketThread/Sender)
,09-12 13:58:45.232  3841  4248 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 508, name: OutgoingSocketThread/Receiver)
,09-12 13:58:45.233  3841  4248 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 508, thread name: OutgoingSocketThread/Receiver)
,09-12 13:58:45.234  3841  4248 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-12 13:58:45.234  3841  4248 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 508, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-12 13:58:45.582  1458  1458 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 13:58:45.625  1458  1458 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-12 13:58:45.628  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 13:58:45.636   874  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 13:58:45.652   874  1309 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 13:58:45.652   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-12 13:58:45.652   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:58:45.672   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:58:45.682   370   872 D CommandListener: Setting iface cfg
,09-12 13:58:45.684   874  1309 D WifiStateMachine: Start Dhcp Watchdog 3
,09-12 13:58:45.698   874  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 13:58:45.729  3841  3888 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 517)
,09-12 13:58:45.731  3841  3888 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-12 13:58:45.731  3841  3888 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 518)
,09-12 13:58:45.736  3841  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 13:58:45.737  3841  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9327519 added. We now have 4 listener(s)
,09-12 13:58:45.740  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 13:58:45.741  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:58:45.741  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:58:45.741  3841  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:58:45.741  3841  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47fa9de added. We now have 4 listener(s)
09-12 13:58:45.742  3841  3888 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:58:45.743  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:58:45.745   874  4251 D DhcpClient: Receive thread started
,09-12 13:58:45.752  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:58:45.760  3841  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:58:45.760  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:45.760  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:45.760  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:45.760  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:45.760  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:58:45.760  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:58:45.760  3841  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:58:45.765  3841  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:58:45.766  3841  3888 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:58:45.772  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:58:45.774  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:58:45.774  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:45.775  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 13:58:45.775  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:58:45.775  3841  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9327519 removed from the list
09-12 13:58:45.775  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:58:45.775  3841  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47fa9de removed from the list
,09-12 13:58:45.777  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:58:45.777  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:58:45.778  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:58:45.780  3841  3888 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-12 13:58:45.780  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-12 13:58:45.781  3841  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-12 13:58:45.781  3841  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-12 13:58:45.781  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-12 13:58:45.782  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:58:45.783  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-12 13:58:45.785  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 13:58:45.785  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 13:58:45.785  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 13:58:45.786  3841  3841 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 13:58:45.786  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-12 13:58:45.786  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:58:45.787  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:58:45.795  3841  3888 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 13:58:45.795  3841  4252 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:58:45.796  3841  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:58:45.802  3841  4252 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-12 13:58:45.806  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:58:45.807  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 13:58:45.807  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:58:45.809  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-12 13:58:45.809  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:58:45.809  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 F8 CF C5 D9 E5 61
09-12 13:58:45.810  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-12 13:58:45.810  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-12 13:58:45.810  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-12 13:58:45.811  3841  3888 D BluetoothAdapter: STATE_ON
,09-12 13:58:45.814  4160  4196 D BtGatt.GattService: registerClient() - UUID=660f5230-30f0-4c29-b83d-88078c6b14bb
,09-12 13:58:45.815  4160  4176 D BtGatt.GattService: onClientRegistered() - UUID=660f5230-30f0-4c29-b83d-88078c6b14bb, clientIf=5
,09-12 13:58:45.815  3841  3851 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-12 13:58:45.817  4160  4178 D BtGatt.AdvertiseManager: message : 0
,09-12 13:58:45.820  4160  4178 D BtGatt.AdvertiseManager: starting multi advertising
,09-12 13:58:45.830  4160  4176 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-12 13:58:45.831   874  1309 E native  : do suspend false
,09-12 13:58:45.838  4160  4176 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
09-12 13:58:45.839  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-12 13:58:45.839  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 13:58:45.841  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:58:45.842  3841  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-12 13:58:45.843  3841  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-12 13:58:45.843  3841  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-12 13:58:45.843  3841  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-12 13:58:45.843  3841  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-12 13:58:45.843  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-12 13:58:45.847  3841  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-12 13:58:45.847  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-12 13:58:45.849   874  1854 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 13:58:45.874   874  4251 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172794, domain null
,09-12 13:58:45.875   874  1854 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172794 seconds
,09-12 13:58:45.878   874  1854 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 13:58:45.895   874  4251 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 13:58:45.897   874  1854 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 13:58:45.901   370   872 D CommandListener: Setting iface cfg
,09-12 13:58:45.911   874  1854 D DhcpClient: Scheduling renewal in 86399s
09-12 13:58:45.911   874  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-12 13:58:45.915   874  1309 E native  : do suspend true
,09-12 13:58:45.938   874  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 13:58:45.942   874  1309 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 13:58:45.945   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-12 13:58:45.948   874  1311 D ConnectivityService: Adding iface wlan0 to network 102
,09-12 13:58:45.962   874  1309 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 13:58:46.007   874  1311 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-12 13:58:46.008   874  1311 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-12 13:58:46.010   874  1311 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-12 13:58:46.012   874  1311 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-12 13:58:46.015   874  1311 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-12 13:58:46.025   874  1311 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 13:58:46.032   874  1311 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-12 13:58:46.033   874  1311 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-12 13:58:46.033   874  1309 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-12 13:58:46.034   874  1311 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,09-12 13:58:46.034   874  1311 D ConnectivityService:    accepting network in place of null
09-12 13:58:46.035   874  1311 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 13:58:46.035   874  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 13:58:46.050   874  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=216490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 13:58:46.097   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:58:46.121   874  4249 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,09-12 13:58:46.153   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:58:46.159   874  1311 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-12 13:58:46.159   874  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:58:46.164   874  1311 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-12 13:58:46.167   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-12 13:58:46.185   874  4249 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 11:58:46 GMT], X-Android-Received-Millis=[1473681526184], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473681526162]}
,09-12 13:58:46.187   874  1311 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 13:58:46.188   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-12 13:58:46.188   874  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-12 13:58:46.188  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:46.188  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:46.188  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:46.188  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:46.188  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:46.188  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:46.188  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:58:46.188  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:58:46.189   874  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 13:58:46.195  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:58:46.200  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:58:46.200  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:58:46.200  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:58:46.200  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:58:46.200  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:58:46.200  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:58:46.200  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:58:46.200  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:58:46.202  1743  1743 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 13:58:46.204  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:58:46.206  1743  1743 D SystemUpdateService: onCreate
,09-12 13:58:46.210  1743  1743 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 13:58:46.233  1743  4263 I SystemUpdateService: active receiver: enabled
,09-12 13:58:46.236  1743  1743 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 13:58:46.239  1743  2318 I iu.UploadsManager: num queued entries: 0
,09-12 13:58:46.239  1743  2318 I iu.UploadsManager: num updated entries: 0
,09-12 13:58:46.251  1743  1743 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 13:58:46.253  1743  1743 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-12 13:58:46.254  3924  3924 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:58:46.259  1743  4265 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-12 13:58:46.259  1743  4265 W BaseAppContext: Using Auth Proxy for data requests.
,09-12 13:58:46.250  1743  4263 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 13:58:46.262  1743  4265 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,09-12 13:58:46.264  3924  3924 D SprintDMHelper: simOperator: ,
09-12 13:58:46.264  3924  3924 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 13:58:46.276  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:58:46.279  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:58:46.240  1743  2318 I iu.SyncManager: NEXT; no task
,09-12 13:58:46.282  1743  4263 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-12 13:58:46.283  1743  4263 I SystemUpdateService: now status is 0 (complete)
,09-12 13:58:46.283  1743  4263 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-12 13:58:46.283  1743  4263 I SystemUpdateService: file has been verified
09-12 13:58:46.287  1743  4263 I SystemUpdateService: OTA package size = 12249756
,09-12 13:58:46.290  1743  4263 I SystemUpdateService: showing system update notification
,09-12 13:58:46.337  1743  1743 D SystemUpdateService: onDestroy
,09-12 13:58:46.346  1523  1540 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-12 13:58:46.346  1523  1540 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-12 13:58:46.346  1523  1540 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:58:46.346  1523  1540 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-12 13:58:46.348  3841  3841 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-12 13:58:46.348  3841  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 13:58:46.348  3841  3841 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 13:58:46.375  1743  4265 E MDM     : [181] SitrepService.a: Error sending sitrep.
,09-12 13:58:46.383  3050  4268 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 13:58:47.160   874  1311 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-12 13:58:47.734   874  1311 D ConnectivityService: handlePromptUnvalidated 101
,09-12 13:58:49.347  3841  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-12 13:58:49.347  3841  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 13:58:49.347  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 13:58:49.347  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-12 13:58:49.347  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 13:58:49.347  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:58:49.347  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 13:58:49.347  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:58:49.347  3841  4252 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 13:58:49.348  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:58:49.348  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:58:49.348  3841  4252 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 13:58:49.348  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:58:49.348  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:58:49.348  3841  4252 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-12 13:58:49.350  3841  3888 D BluetoothAdapter: STATE_ON
,09-12 13:58:49.350  3841  3888 D BluetoothLeScanner: could not find callback wrapper
,09-12 13:58:49.350  3841  3841 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 13:58:49.350  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:58:49.351  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-12 13:58:49.352  4160  4178 D BtGatt.AdvertiseManager: message : 1
09-12 13:58:49.353  4160  4178 D BtGatt.AdvertiseManager: stop advertise for client 5
09-12 13:58:49.361  4160  4176 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-12 13:58:49.361  4160  4176 D BtGatt.GattService: Client app is not null!
09-12 13:58:49.364  4160  4171 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 13:58:49.365  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 13:58:49.365  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-12 13:58:49.365  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-12 13:58:49.366  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-12 13:58:49.366  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-12 13:58:49.369  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:58:49.369  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:58:49.369  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 13:58:49.371  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:49.374  3841  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:58:49.374  3841  3841 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-12 13:58:49.374  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:58:49.374  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:58:49.375  3841  3841 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 13:58:49.375  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:58:49.379  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:58:49.379  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:49.379  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:49.380  3841  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9327519 not in the list
09-12 13:58:49.380  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:58:49.380  3841  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47fa9de not in the list
09-12 13:58:49.380  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:58:49.381  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:49.381  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:49.383  3841  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:58:49.384  3841  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:58:49.384  3841  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:58:49.384  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:58:49.385  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:58:49.385  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 13:58:49.393  3841  3888 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 13:58:49.393  3841  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 13:58:49.403  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 13:58:49.404  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 13:58:49.404  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 13:58:49.410  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 13:58:49.410  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 13:58:49.411  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 13:58:49.413  3841  3888 D BluetoothAdapter: STATE_ON
09-12 13:58:49.417  4160  4187 D BtGatt.GattService: registerClient() - UUID=ac1fb29d-a032-4034-895f-40f86b857140
09-12 13:58:49.418  4160  4176 D BtGatt.GattService: onClientRegistered() - UUID=ac1fb29d-a032-4034-895f-40f86b857140, clientIf=5
09-12 13:58:49.419  3841  4133 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 13:58:49.420  4160  4171 D BtGatt.GattService: start scan with filters
09-12 13:58:49.424  4160  4179 D BtGatt.ScanManager: handling starting scan
09-12 13:58:49.424  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 13:58:49.424  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 13:58:49.424  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 13:58:49.424  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 13:58:49.425  4160  4179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@73df50f
09-12 13:58:49.430  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 13:58:49.430  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 13:58:49.430  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 13:58:49.432  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-12 13:58:49.437  4160  4176 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 13:58:49.438  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:58:49.438  4160  4179 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 13:58:49.443  4160  4176 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 13:58:49.443  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:58:49.444  4160  4179 D BtGatt.ScanManager: Starting BLE batch scan
09-12 13:58:49.444  4160  4179 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 13:58:49.453  4160  4176 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 13:58:49.453  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:58:49.458  4160  4176 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 13:58:49.458  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:58:49.931  3841  3841 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-12 13:58:49.931  3841  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 13:58:49.932  3841  3841 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 13:58:50.965  4160  4160 D BtGatt.ScanManager: awakened up at time 221405
,09-12 13:58:50.969  4160  4179 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 13:58:51.018  4160  4176 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-12 13:58:51.019  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:58:51.019  4160  4176 D BtGatt.GattService: current time is 221459647538
09-12 13:58:51.021  4160  4176 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -84, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -91, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -96, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -83, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -80, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-12 13:58:51.026  4160  4176 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-12 13:58:51.028  4160  4176 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,09-12 13:58:51.029  4160  4176 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-12 13:58:51.030  4160  4176 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-12 13:58:51.031  4160  4176 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-12 13:58:52.435  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:58:52.436  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:52.436  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:58:52.437  3841  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9327519 not in the list
,09-12 13:58:52.437  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:58:52.437  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:58:52.437  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:58:52.438  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 13:58:52.440  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:58:52.441  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 13:58:52.445  3841  3888 D BluetoothAdapter: STATE_ON
,09-12 13:58:52.448  4160  4187 D BtGatt.GattService: stopScan() - queue size =1
,09-12 13:58:52.451  4160  4171 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 13:58:52.452  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:58:52.453  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 13:58:52.454  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 13:58:52.454  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 13:58:52.454  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 13:58:52.458  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:58:52.458  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 13:58:52.458  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:58:52.458  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:58:52.460  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:58:52.461  4160  4160 D BtGatt.ScanManager: awakened up at time 222901
09-12 13:58:52.461  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:58:52.461  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:58:52.462  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:58:52.462  3841  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47fa9de not in the list
09-12 13:58:52.462  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:58:52.462  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:52.462  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:52.463  3841  3888 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
09-12 13:58:52.463  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
09-12 13:58:52.465  3841  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-12 13:58:52.466  3841  3888 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-12 13:58:52.466  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 13:58:52.466  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:58:52.468  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-12 13:58:52.469  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 13:58:52.469  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 13:58:52.469  3841  3841 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 13:58:52.469  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-12 13:58:52.469  4160  4176 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 13:58:52.469  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-12 13:58:52.470  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:58:52.470  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:58:52.470  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:58:52.472  4160  4179 D BtGatt.ScanManager: stopping BLe Batch
,09-12 13:58:52.475  3841  3888 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 13:58:52.475  3841  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:58:52.482  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:58:52.483  3841  4276 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:58:52.484  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 13:58:52.484  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:58:52.485  4160  4176 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 13:58:52.485  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:58:52.485  4160  4179 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 13:58:52.487  3841  4276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-12 13:58:52.489  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-12 13:58:52.489  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:58:52.490  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 F8 CF C5 D9 E5 61
,09-12 13:58:52.490  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-12 13:58:52.491  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-12 13:58:52.491  3841  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-12 13:58:52.492  4160  4176 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 13:58:52.492  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:58:52.492  3841  3888 D BluetoothAdapter: STATE_ON
,09-12 13:58:52.498  4160  4187 D BtGatt.GattService: registerClient() - UUID=cd0ab9d6-c47d-4ec8-b881-cfeee6cffd18
,09-12 13:58:52.498  4160  4176 D BtGatt.GattService: onClientRegistered() - UUID=cd0ab9d6-c47d-4ec8-b881-cfeee6cffd18, clientIf=5
,09-12 13:58:52.499  3841  3852 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5,
,09-12 13:58:52.499  4160  4178 D BtGatt.AdvertiseManager: message : 0
,09-12 13:58:52.501  4160  4178 D BtGatt.AdvertiseManager: starting multi advertising
,09-12 13:58:52.510  4160  4176 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-12 13:58:52.516  4160  4176 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-12 13:58:52.516  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-12 13:58:52.516  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:58:52.518  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:58:52.519  3841  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-12 13:58:52.519  3841  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-12 13:58:52.519  3841  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-12 13:58:52.519  3841  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-12 13:58:52.519  3841  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-12 13:58:52.519  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-12 13:58:52.521  3841  3841 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-12 13:58:52.522  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-12 13:58:53.023  3841  3841 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-12 13:58:53.023  3841  3841 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 13:58:53.024  3841  3841 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 13:58:54.039   874  1311 D ConnectivityService: handlePromptUnvalidated 102
,09-12 13:58:56.024  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:58:56.024  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 13:58:56.025  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 13:58:56.025  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 13:58:56.026  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 13:58:56.026  3841  4276 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 13:58:56.026  3841  4276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 13:58:56.027  3841  4276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-12 13:58:56.027  3841  3841 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-12 13:58:56.028  3841  3888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-12 13:58:56.030  3841  3841 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 13:58:56.031  3841  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9327519 not in the list
,09-12 13:58:56.031  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:58:56.032  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 13:58:56.033  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 13:58:56.033  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 13:58:56.034  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:58:56.036  3841  3888 D BluetoothAdapter: STATE_ON
09-12 13:58:56.037  3841  3888 D BluetoothLeScanner: could not find callback wrapper
09-12 13:58:56.037  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:58:56.037  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-12 13:58:56.040  4160  4178 D BtGatt.AdvertiseManager: message : 1
09-12 13:58:56.042  4160  4178 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-12 13:58:56.051  4160  4176 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-12 13:58:56.051  4160  4176 D BtGatt.GattService: Client app is not null!
,09-12 13:58:56.052  4160  4196 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 13:58:56.052  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 13:58:56.052  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-12 13:58:56.053  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-12 13:58:56.053  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-12 13:58:56.053  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-12 13:58:56.054  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:58:56.054  3841  3888 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:58:56.054  3841  3888 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 13:58:56.055  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:58:56.057  3841  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47fa9de not in the list
,09-12 13:58:56.057  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:58:56.057  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:58:56.057  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:58:56.057  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 13:58:56.057  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:58:56.058  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:58:56.058  3841  3888 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:58:56.058  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:56.058  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:58:56.058  3841  3888 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9327519 not in the list
09-12 13:58:56.058  3841  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:58:56.058  3841  3888 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47fa9de not in the list
09-12 13:58:56.058  3841  3888 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:58:56.058  3841  3888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:58:56.058  3841  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:58:56.059  3841  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-12 13:58:56.059  3841  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 13:58:56.059  3841  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-12 13:58:56.060  3841  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:58:56.060  3841  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-12 13:58:56.060  3841  3888 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 13:58:56.069  3841  4278 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 538, name: My test thread name)
,09-12 13:58:56.559  3841  3841 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 13:58:58.068  3841  3888 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 538
,09-12 13:58:58.068  3841  3888 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 538, name: My test thread name)
,09-12 13:58:58.074  3841  4279 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 539, name: My test thread name)
,09-12 13:58:58.075  3841  4279 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 539, thread name: My test thread name)
09-12 13:58:58.075  3841  4279 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 539, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-12 13:58:58.080  3841  3888 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 13:58:58.088  3841  4280 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 543, name: My test thread name)
,09-12 13:58:58.089  3841  4280 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 543, thread name: My test thread name): Test exception.
09-12 13:58:58.089  3841  4280 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 543, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-12 13:58:58.098  3841  3888 I jxcore-log: Total number of executed tests:  82
09-12 13:58:58.098  3841  3888 I jxcore-log: 
,09-12 13:58:58.098  3841  3888 I jxcore-log: Number of passed tests:  82
09-12 13:58:58.098  3841  3888 I jxcore-log: 
09-12 13:58:58.098  3841  3888 I jxcore-log: Number of failed tests:  0
09-12 13:58:58.098  3841  3888 I jxcore-log: 
09-12 13:58:58.099  3841  3888 I jxcore-log: Number of ignored tests:  0
09-12 13:58:58.099  3841  3888 I jxcore-log: 
,09-12 13:58:58.099  3841  3888 I jxcore-log: Total duration:  23496
09-12 13:58:58.099  3841  3888 I jxcore-log: 
09-12 13:58:58.101  3841  3888 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-12 13:58:58.101  3841  3888 I jxcore-log: 
,09-12 13:58:58.102  3841  3888 I jxcore-log: My device name is: motorola-Nexus 6
09-12 13:58:58.102  3841  3888 I jxcore-log: 
09-12 13:58:58.104  3841  3888 I jxcore-log: WARN testUtils: myNameCallback not set!
09-12 13:58:58.104  3841  3888 I jxcore-log: 
09-12 13:58:58.107  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:58:58.107  3841  3888 I jxcore-log: 
09-12 13:58:58.108  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:58:58.108  3841  3888 I jxcore-log: 
09-12 13:58:58.109  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:58:58.109  3841  3888 I jxcore-log: 
09-12 13:58:58.117  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-12 13:58:58.117  3841  3888 I jxcore-log: 
,09-12 13:58:58.128  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:58:58.128  3841  3888 I jxcore-log: 
,09-12 13:58:58.133  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-12 13:58:58.133  3841  3888 I jxcore-log: 
09-12 13:58:58.134  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:58:58.134  3841  3888 I jxcore-log: 
,09-12 13:58:58.136  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-12 13:58:58.136  3841  3888 I jxcore-log: 
,09-12 13:58:58.137  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:58:58.137  3841  3888 I jxcore-log: 
,09-12 13:58:58.138  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:58:58.138  3841  3888 I jxcore-log: 
09-12 13:58:58.139  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:58:58.139  3841  3888 I jxcore-log: 
,09-12 13:58:58.140  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:58:58.140  3841  3888 I jxcore-log: 
,09-12 13:58:58.142  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:58:58.142  3841  3888 I jxcore-log: 
,09-12 13:58:58.144  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:58:58.144  3841  3888 I jxcore-log: 
,09-12 13:58:58.145  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:58:58.145  3841  3888 I jxcore-log: 
,09-12 13:58:58.147  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:58:58.147  3841  3888 I jxcore-log: 
,09-12 13:58:58.150  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:58:58.150  3841  3888 I jxcore-log: 
,09-12 13:58:58.152  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:58:58.152  3841  3888 I jxcore-log: 
,09-12 13:58:58.154  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:58:58.154  3841  3888 I jxcore-log: 
,09-12 13:58:58.156  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:58:58.156  3841  3888 I jxcore-log: 
,09-12 13:58:58.159  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:58:58.159  3841  3888 I jxcore-log: 
,09-12 13:58:58.161  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:58:58.161  3841  3888 I jxcore-log: 
,09-12 13:58:58.166  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:58:58.166  3841  3888 I jxcore-log: 
,09-12 13:58:58.168  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:58:58.168  3841  3888 I jxcore-log: 
,09-12 13:58:58.171  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:58:58.171  3841  3888 I jxcore-log: 
,09-12 13:58:58.171  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:58:58.171  3841  3888 I jxcore-log: 
,09-12 13:58:58.172  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:58:58.172  3841  3888 I jxcore-log: 
,09-12 13:58:58.173  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:58:58.173  3841  3888 I jxcore-log: 
,09-12 13:58:58.174  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:58:58.174  3841  3888 I jxcore-log: 
09-12 13:58:58.175  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:58:58.175  3841  3888 I jxcore-log: 
,09-12 13:58:58.175  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:58:58.175  3841  3888 I jxcore-log: 
,09-12 13:58:58.176  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:58:58.176  3841  3888 I jxcore-log: 
,09-12 13:58:58.177  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:58:58.177  3841  3888 I jxcore-log: 
,09-12 13:58:58.178  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:58:58.178  3841  3888 I jxcore-log: 
,09-12 13:58:58.179  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:58:58.179  3841  3888 I jxcore-log: 
09-12 13:58:58.179  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:58:58.179  3841  3888 I jxcore-log: 
,09-12 13:58:58.180  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:58:58.180  3841  3888 I jxcore-log: 
,09-12 13:58:58.181  3841  4278 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 538, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,09-12 13:58:58.183  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:58:58.183  3841  3888 I jxcore-log: 
,09-12 13:58:58.184  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:58:58.184  3841  3888 I jxcore-log: 
,09-12 13:58:58.185  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:58:58.185  3841  3888 I jxcore-log: 
09-12 13:58:58.185  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:58:58.185  3841  3888 I jxcore-log: 
09-12 13:58:58.186  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:58:58.186  3841  3888 I jxcore-log: 
,09-12 13:58:58.187  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:58:58.187  3841  3888 I jxcore-log: 
,09-12 13:58:58.188  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:58:58.188  3841  3888 I jxcore-log: 
,09-12 13:58:58.189  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:58:58.189  3841  3888 I jxcore-log: 
09-12 13:58:58.190  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-12 13:58:58.190  3841  3888 I jxcore-log: 
,09-12 13:58:58.191  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-12 13:58:58.191  3841  3888 I jxcore-log: 
,09-12 13:58:58.192  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-12 13:58:58.192  3841  3888 I jxcore-log: 
09-12 13:58:58.193  3841  3888 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:58:58.193  3841  3888 I jxcore-log: 
,09-12 13:58:58.756  4281  4281 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-12 13:58:58.761  4281  4281 D AndroidRuntime: CheckJNI is OFF
,09-12 13:58:58.841  4281  4281 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-12 13:58:58.885  4281  4281 I Radio-JNI: register_android_hardware_Radio DONE
,09-12 13:58:58.909  4281  4281 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-12 13:58:58.917   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-12 13:58:58.917   874   887 I ActivityManager: Killing 3841:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-12 13:58:59.030   874  1905 D GraphicsStats: Buffer count: 2
,09-12 13:58:59.030   874  1310 D WifiService: Client connection lost with reason: 4
,09-12 13:58:59.039   874  1298 W InputDispatcher: channel '6e75a54 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,09-12 13:58:59.039   874  1298 E InputDispatcher: channel '6e75a54 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
09-12 13:58:59.037   874  2064 I WindowState: WIN DEATH: Window{6e75a54 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-12 13:58:59.040   874  2064 W InputDispatcher: Attempted to unregister already unregistered input channel '6e75a54 com.test.thalitest/com.test.thalitest.MainActivity (server)'
,09-12 13:58:59.045   874   898 W PackageSettings: Skipping PackageSetting{28efdc0 com.example.hello/10273} due to missing metadata
,09-12 13:58:59.078   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-12 13:58:59.079   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-12 13:58:59.079   874   887 E ActivityManager: Failure starting process com.test.thalitest
09-12 13:58:59.079   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-12 13:58:59.079   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-12 13:58:59.079   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-12 13:58:59.079   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-12 13:58:59.079   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-12 13:58:59.079   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-12 13:58:59.079   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-12 13:58:59.079   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-12 13:58:59.079   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-12 13:58:59.079   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-12 13:58:59.079   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-12 13:58:59.079   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-12 13:58:59.079   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-12 13:58:59.079   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-12 13:58:59.079   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-12 13:58:59.079   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:58:59.079   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:58:59.079   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 13:58:59.079   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-12 13:58:59.080   874   887 I ActivityManager:   Force finishing activity ActivityRecord{8643e19 u0 com.test.thalitest/.MainActivity t4}
,09-12 13:58:59.082   874   898 I art     : Starting a blocking GC Explicit
,09-12 13:58:59.092   874   885 W ActivityManager: Spurious death for ProcessRecord{560ef3f 0:com.test.thalitest/u0a0}, curProc for 3841: null
,09-12 13:58:59.150   874   898 I art     : Explicit concurrent mark sweep GC freed 19641(1254KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 1.115ms total 67.356ms
,09-12 13:58:59.186   874   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-12 13:58:59.193  4281  4281 I art     : System.exit called, status: 0
,09-12 13:58:59.193  4281  4281 I AndroidRuntime: VM exiting with result code 0.
,09-12 13:58:59.199   874   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-12 13:58:59.217   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-12 13:58:59.221  4160  4160 D BluetoothMapAppObserver: onReceive
,09-12 13:58:59.221  4160  4160 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-12 13:58:59.233   874  1299 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-12 13:58:59.235  2076  2302 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-12 13:58:59.235  1876  1876 I Keyboard.Facilitator: resetDictionaries() : en_US
09-12 13:58:59.236  3678  3678 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-12 13:58:59.249  1876  4293 I Keyboard.Facilitator.DecoderInitializer: run()
,09-12 13:58:59.253  1876  4293 I Decoder : createOrResetDecoder
,09-12 13:58:59.286  1950  1950 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-12 13:58:59.299   874  1906 I ActivityManager: Start proc 4296:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-12 13:58:59.305  1523  1523 I ConfigService: onCreate
,09-12 13:58:59.327  1523  4302 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-12 13:58:59.327  1523  4302 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:58:59.327  1523  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:58:59.327  1523  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:58:59.327  1523  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:58:59.327  1523  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:58:59.327  1523  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:58:59.327  1523  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:58:59.327  1523  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:58:59.327  1523  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:58:59.327  1523  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:58:59.327  1523  4302 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:58:59.327  1523  4302 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:58:59.327  1523  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:58:59.327  1523  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 13:58:59.327  1523  4302 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-12 13:58:59.327  1523  4302 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-12 13:58:59.327  1523  4302 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-12 13:58:59.330  1523  4302 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-12 13:58:59.330  1523  4302 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:58:59.330  1523  4302 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:58:59.330  1523  4302 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:58:59.330  1523  4302 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:58:59.330  1523  4302 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:58:59.330  1523  4302 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:58:59.330  1523  4302 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:58:59.330  1523  4302 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:58:59.330  1523  4302 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:58:59.330  1523  4302 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:58:59.330  1523  4302 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:58:59.330  1523  4302 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:58:59.330  1523  4302 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:58:59.330  1523  4302 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 13:58:59.330  1523  4302 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-12 13:58:59.330  1523  4302 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-12 13:58:59.330  1523  4302 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,09-12 13:58:59.334  1523  4302 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-12 13:58:59.340   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-12 13:58:59.340  4296  4296 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-12 13:58:59.356  1876  4293 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-12 13:58:59.362   874  2065 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3841 uid 10000
,09-12 13:58:59.364  1876  1876 I Keyboard.Facilitator: onFinishInput()
,09-12 13:58:59.364  1966  2035 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-12 13:58:59.364   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-12 13:58:59.365   874   886 E PackageManager: Failed to write settings, restoring backup
09-12 13:58:59.365   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-12 13:58:59.365   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-12 13:58:59.365   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-12 13:58:59.365   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-12 13:58:59.365   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-12 13:58:59.365   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:58:59.365   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:58:59.365   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 13:58:59.369   874   887 E DropBoxManagerService: Can't write: system_server_wtf
09-12 13:58:59.369   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-12 13:58:59.369   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 13:58:59.369   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 13:58:59.369   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 13:58:59.369   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 13:58:59.369   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 13:58:59.369   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 13:58:59.369   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-12 13:58:59.369   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-12 13:58:59.369   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-12 13:58:59.369   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 13:58:59.369   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 13:58:59.369   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:58:59.369   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 13:58:59.369   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 13:58:59.369   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 13:58:59.369   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 13:58:59.369   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 13:58:59.369   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:58:59.369   874   887 E DropBoxManagerService: 	... 13 more
,09-12 13:58:59.377   874  1377 I ActivityManager: Start proc 4309:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-12 13:58:59.377  1966  2035 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-12 13:58:59.377  1966  2035 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1966
09-12 13:58:59.377  1966  2035 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 13:58:59.377  1966  2035 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 13:58:59.377  1966  2035 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 13:58:59.377  1966  2035 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 13:58:59.377  1966  2035 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 13:58:59.377  1966  2035 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 13:58:59.377  1966  2035 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-12 13:58:59.377  1966  2035 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-12 13:58:59.377  1966  2035 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 13:58:59.377  1966  2035 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 13:58:59.377  1966  2035 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:58:59.377  1966  2035 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 13:58:59.379   874  2791 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-12 13:58:59.380   874  4315 E DropBoxManagerService: Can't write: system_app_crash
09-12 13:58:59.380   874  4315 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-12 13:58:59.380   874  4315 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 13:58:59.380   874  4315 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 13:58:59.380   874  4315 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 13:58:59.380   874  4315 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 13:58:59.380   874  4315 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 13:58:59.380   874  4315 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 13:58:59.380   874  4315 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 13:58:59.380   874  4315 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 13:58:59.380   874  4315 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 13:58:59.380   874  4315 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:58:59.380   874  4315 E DropBoxManagerService: 	... 5 more
09-12 13:58:59.383  1966  2035 I Process : Sending signal. PID: 1966 SIG: 9
,09-12 13:58:59.463  1876  4293 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-12 13:58:59.465  1876  4293 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-12 13:58:59.465  1876  4293 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-12 13:58:59.467  1876  4293 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-12 13:58:59.467  1876  4293 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-12 13:58:59.468  1876  4293 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,09-12 13:58:59.468  1876  4293 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-12 13:58:59.469  1876  4293 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-12 13:58:59.469  1876  4293 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,09-12 13:58:59.469  1876  4293 I Keyboard.Facilitator.Delight2FileSweeper: run()
,09-12 13:58:59.483  1876  4293 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,09-12 13:58:59.483  1876  4293 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,09-12 13:58:59.483  1876  4293 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-12 13:58:59.536  4296  4296 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-12 13:58:59.548   874  1906 I WindowState: WIN DEATH: Window{33bc21e u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL},
09-12 13:58:59.548   874  2065 D GraphicsStats: Buffer count: 1
,09-12 13:58:59.559   874  1618 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1966) has died
,09-12 13:58:59.559   874  1618 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-12 13:58:59.565  4296  4325 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-12 13:58:59.565  4296  4325 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:58:59.565  4296  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:58:59.565  4296  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:58:59.565  4296  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:58:59.565  4296  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:58:59.565  4296  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:58:59.565  4296  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:58:59.565  4296  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:58:59.565  4296  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:58:59.565  4296  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:58:59.565  4296  4325 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:58:59.565  4296  4325 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:58:59.565  4296  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:58:59.565  4296  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 13:58:59.565  4296  4325 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-12 13:58:59.565  4296  4325 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-12 13:58:59.565  4296  4325 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-12 13:58:59.565  4296  4325 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-12 13:58:59.565  4296  4325 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:58:59.565  4296  4325 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:58:59.565  4296  4325 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 13:58:59.565  4296  4325 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-12 13:58:59.565  4296  4325 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:58:59.565  4296  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:58:59.565  4296  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:58:59.565  4296  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:58:59.565  4296  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:58:59.565  4296  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:58:59.565  4296  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:58:59.565  4296  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:58:59.565  4296  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:58:59.565  4296  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:58:59.565  4296  4325 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:58:59.565  4296  4325 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:58:59.565  4296  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:58:59.565  4296  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 13:58:59.565  4296  4325 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-12 13:58:59.565  4296  4325 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-12 13:58:59.565  4296  4325 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-12 13:58:59.565  4296  4325 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-12 13:58:59.565  4296  4325 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:58:59.565  4296  4325 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:58:59.565  4296  4325 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 13:58:59.567   874  1618 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-12 13:58:59.586   874   887 I ActivityManager: Start proc 4329:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-12 13:58:59.593  4296  4336 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-12 13:58:59.601   874   885 I ActivityManager: Start proc 4342:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-12 13:58:59.619  1743  4328 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-12 13:58:59.621  1743  4328 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-12 13:58:59.632  4342  4342 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-12 13:58:59.636  4329  4329 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:58:59.636  4329  4329 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 13:58:59.636  4329  4329 D AndroidRuntime: Shutting down VM
,09-12 13:58:59.643  4329  4329 E AndroidRuntime: FATAL EXCEPTION: main
09-12 13:58:59.643  4329  4329 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4329
09-12 13:58:59.643  4329  4329 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 13:58:59.643  4329  4329 E AndroidRuntime: 	... 10 more
,09-12 13:58:59.649   874  2064 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-12 13:58:59.649  4329  4329 I Process : Sending signal. PID: 4329 SIG: 9
09-12 13:58:59.654   874  4355 E DropBoxManagerService: Can't write: system_app_crash
09-12 13:58:59.654   874  4355 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-12 13:58:59.654   874  4355 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 13:58:59.654   874  4355 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 13:58:59.654   874  4355 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 13:58:59.654   874  4355 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 13:58:59.654   874  4355 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 13:58:59.654   874  4355 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 13:58:59.654   874  4355 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 13:58:59.654   874  4355 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 13:58:59.654   874  4355 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 13:58:59.654   874  4355 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:58:59.654   874  4355 E DropBoxManagerService: 	... 5 more
,09-12 13:58:59.659  1743  4328 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-12 13:58:59.660  1743  4328 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-12 13:58:59.665  1523  1523 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-12 13:58:59.666  1523  1523 D AndroidRuntime: Shutting down VM
,09-12 13:58:59.668  1523  1523 E AndroidRuntime: FATAL EXCEPTION: main
09-12 13:58:59.668  1523  1523 E AndroidRuntime: Process: com.google.process.gapps, PID: 1523
09-12 13:58:59.668  1523  1523 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 13:58:59.668  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-12 13:58:59.668  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-12 13:58:59.668  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-12 13:58:59.668  1523  1523 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:58:59.668  1523  1523 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:58:59.668  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:58:59.668  1523  1523 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:58:59.668  1523  1523 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:58:59.668  1523  1523 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 13:58:59.668  1523  1523 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 13:58:59.668  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 13:58:59.668  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 13:58:59.668  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 13:58:59.668  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 13:58:59.668  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 13:58:59.668  1523  1523 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-12 13:58:59.668  1523  1523 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-12 13:58:59.668  1523  1523 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-12 13:58:59.668  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-12 13:58:59.668  1523  1523 E AndroidRuntime: 	... 8 more
,09-12 13:58:59.671   874  4358 E DropBoxManagerService: Can't write: system_app_crash
09-12 13:58:59.671   874  4358 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-12 13:58:59.671   874  4358 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 13:58:59.671   874  4358 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 13:58:59.671   874  4358 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 13:58:59.671   874  4358 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 13:58:59.671   874  4358 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 13:58:59.671   874  4358 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 13:58:59.671   874  4358 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 13:58:59.671   874  4358 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 13:58:59.671   874  4358 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 13:58:59.671   874  4358 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:58:59.671   874  4358 E DropBoxManagerService: 	... 5 more
,09-12 13:58:59.671  1523  1523 I Process : Sending signal. PID: 1523 SIG: 9
,09-12 13:58:59.673   874  2063 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4329) has died
,09-12 13:58:59.674   874  2063 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-12 13:58:59.688   874   887 I ActivityManager: Start proc 4359:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-12 13:58:59.690   874  4290 I ActivityManager: Killing 3735:com.google.android.apps.docs/u0a46 (adj 15): empty #17

```
