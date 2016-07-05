#### Test 757892685fc4836_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
07-05 15:39:20.029   874  2106 D NetlinkSocketObserver: NeighborEvent{elapsedMs=269197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 15:39:20.815  3673  3673 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-05 15:39:20.820  3673  3673 D AndroidRuntime: CheckJNI is OFF
07-05 15:39:20.862  3673  3673 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-05 15:39:20.912  3673  3673 I Radio-JNI: register_android_hardware_Radio DONE
07-05 15:39:20.935  3673  3673 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-05 15:39:20.940   874  1694 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-05 15:39:21.008   874  1694 I ActivityManager: Start proc 3683:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-05 15:39:21.023  3673  3673 D AndroidRuntime: Shutting down VM
07-05 15:39:21.099  3683  3683 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-05 15:39:21.121  3683  3683 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
07-05 15:39:21.129  3683  3683 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 294-298)
07-05 15:39:21.129  3683  3683 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 15:39:21.147  3683  3683 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {69c9ef3}
07-05 15:39:21.148  3683  3683 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 15:39:21.148  3683  3683 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 15:39:21.154  3683  3683 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-05 15:39:21.156  3683  3683 E SysUtils: ApplicationContext is null in ApplicationStatus
07-05 15:39:21.177  3683  3683 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-05 15:39:21.189  3683  3683 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 15:39:21.189  3683  3683 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 15:39:21.189  3683  3683 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-05 15:39:21.189  3683  3683 I Adreno  : Build Date                       : 10/20/15
07-05 15:39:21.189  3683  3683 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-05 15:39:21.189  3683  3683 I Adreno  : Local Branch                     : M14
07-05 15:39:21.189  3683  3683 I Adreno  : Remote Branch                    : 
07-05 15:39:21.189  3683  3683 I Adreno  : Remote Branch                    : 
07-05 15:39:21.189  3683  3683 I Adreno  : Reconstruct Branch               : 
07-05 15:39:21.261   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@528f44a:true
,07-05 15:39:21.285  3683  3683 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-05 15:39:21.296  3683  3683 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,07-05 15:39:21.345  3683  3720 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-05 15:39:21.359  3683  3707 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-05 15:39:21.399  3683  3720 I OpenGLRenderer: Initialized EGL, version 1.4
,07-05 15:39:21.432  1653  1653 I Keyboard.Facilitator: onFinishInput()
,07-05 15:39:21.479   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +433ms (total +496ms)
,07-05 15:39:21.536  3683  3683 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3683
,07-05 15:39:21.660  3683  3683 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-05 15:39:21.723  3683  3683 I chromium: [INFO:CONSOLE(90)] "Uncaught SyntaxError: Unexpected token function", source: file:///android_asset/www/js/thali_main.js (90)
,07-05 15:39:21.854  3683  3723 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1697773264
,07-05 15:39:21.862  3683  3723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 15:39:21.862  3683  3723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 15:39:21.862  3683  3723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 15:39:21.862  3683  3723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 15:39:21.862  3683  3723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-05 15:39:21.862  3683  3723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@950b746 added. We now have 1 listener(s)
,07-05 15:39:21.867  3683  3723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,07-05 15:39:21.867  3683  3723 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-05 15:39:21.868  3683  3723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-05 15:39:21.869  3683  3723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-05 15:39:21.873  3683  3723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 15:39:21.873  3683  3723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 15:39:21.873  3683  3723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 15:39:21.873  3683  3723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
07-05 15:39:21.873  3683  3723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 15:39:21.873  3683  3723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 15:39:21.873  3683  3723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 15:39:21.873  3683  3723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 15:39:21.873  3683  3723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 15:39:21.873  3683  3723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 15:39:21.873  3683  3723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-05 15:39:21.874  3683  3723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db245d added. We now have 1 listener(s)
07-05 15:39:21.874  3683  3723 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-05 15:39:21.877   874  1311 D WifiService: New client listening to asynchronous messages
,07-05 15:39:21.884  3683  3723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-05 15:39:21.885  3683  3723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-05 15:39:21.885  3683  3723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,07-05 15:39:21.885  3683  3723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-05 15:39:21.885  3683  3723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-05 15:39:21.889  3683  3723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-05 15:39:21.889  3683  3723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,07-05 15:39:21.895  3683  3723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 15:39:21.895  3683  3723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 15:39:21.895  3683  3723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-05 15:39:21.895  3683  3723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 15:39:21.895  3683  3723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 15:39:21.895  3683  3723 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 15:39:21.895  3683  3723 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 15:39:21.895  3683  3723 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-05 15:39:21.895  3683  3723 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 15:39:21.895  3683  3723 D io.jxcore.node.ConnectivityMonitor: start: OK
07-05 15:39:21.896  3683  3723 I io.jxcore.node.LifeCycleMonitor: start: OK
07-05 15:39:21.898  3683  3683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-05 15:39:21.899  3683  3683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 15:39:21.927  3683  3683 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 15:39:22.527  3683  3729 W jxcore-log: Initializing JXcore engine
,07-05 15:39:22.527  3683  3729 W jxcore-log: JXcore engine is ready
,07-05 15:39:22.562  3729  3729 W Thread-325: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8944 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,07-05 15:39:22.562  3729  3729 W Thread-325: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9914]" dev="sockfs" ino=9914 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-05 15:39:22.562  3729  3729 W Thread-325: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,07-05 15:39:22.562  3729  3729 W Thread-325: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[23324]" dev="sockfs" ino=23324 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
07-05 15:39:22.577  3683  3729 W jxcore-log: Starting JXcore engine
,07-05 15:39:22.655  3683  3729 W jxcore-log: Platform android
07-05 15:39:22.655  3683  3729 W jxcore-log: 
,07-05 15:39:22.656  3683  3729 W jxcore-log: Process ARCH arm
07-05 15:39:22.656  3683  3729 W jxcore-log: 
,07-05 15:39:22.841  3683  3729 I jxcore-log: JXcore Cordova bridge is ready!
07-05 15:39:22.841  3683  3729 I jxcore-log: 
,07-05 15:39:22.842  3683  3729 W jxcore-log: JXcore engine is started
,07-05 15:39:36.642   874  2106 D NetlinkSocketObserver: NeighborEvent{elapsedMs=285810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 15:39:37.920  3432  3735 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 15:39:37.981  3432  3736 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-05 15:39:38.007  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:39:38.010  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:39:38.063  1509  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 15:39:38.063  1509  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 15:39:38.064  1509  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:39:38.064  1509  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:39:38.119  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:39:38.121  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:39:38.159  1509  3496 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 15:39:38.160  1509  3496 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 15:39:38.160  1509  3496 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:39:38.160  1509  3496 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:39:38.184  3432  3736 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-05 15:39:38.187  3432  3735 E BooksSync: Soft error
07-05 15:39:38.187  3432  3735 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 15:39:38.187  3432  3735 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-05 15:39:38.189  3432  3735 E BooksSync: Sync error
07-05 15:39:38.189  3432  3735 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 15:39:38.189  3432  3735 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-05 15:39:38.189  3432  3735 I BooksSync: Finished books sync
,07-05 15:39:38.199   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 287032, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 15:39:42.362   874  1379 I ActivityManager: Start proc 3737:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,07-05 15:39:42.416  3737  3737 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,07-05 15:39:42.463  3737  3737 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-05 15:39:42.483  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:39:42.485  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:39:42.527  3737  3760 V GoogleAuthProtoRequest: [317] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 15:39:42.562  1509  2052 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-05 15:39:42.562  1509  2052 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-05 15:39:42.562  1509  2052 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 15:39:42.563  1509  2052 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:39:42.580  3737  3760 W ExperimentUpdateService: [317] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-05 15:39:42.580  3737  3760 W ExperimentUpdateService: [317] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 15:39:42.580  3737  3760 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 15:39:42.580  3737  3760 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-05 15:39:42.580  3737  3760 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-05 15:39:42.580  3737  3760 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-05 15:39:42.580  3737  3760 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-05 15:39:42.580  3737  3760 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-05 15:39:42.580  3737  3760 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-05 15:39:42.580  3737  3760 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-05 15:39:42.580  3737  3760 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-05 15:39:42.580  3737  3760 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-05 15:39:42.585   874  1694 I ActivityManager: Killing 2831:com.google.android.calendar/u0a37 (adj 15): empty #17
,07-05 15:40:08.580  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:40:08.585  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:40:08.623  1509  3495 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-05 15:40:08.623  1509  3495 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-05 15:40:08.623  1509  3495 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:40:08.623  1509  3495 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-05 15:40:08.652  2467  3767 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-05 15:40:08.652  2467  3767 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 15:40:08.652  2467  3767 E HttpOperation: 	at jdm.a(PG:82)
07-05 15:40:08.652  2467  3767 E HttpOperation: 	at jcs.o(PG:406)
07-05 15:40:08.652  2467  3767 E HttpOperation: 	at jcn.a(PG:1379)
07-05 15:40:08.652  2467  3767 E HttpOperation: 	at jcs.i(PG:143)
07-05 15:40:08.652  2467  3767 E HttpOperation: 	at blb.a(PG:3937)
07-05 15:40:08.652  2467  3767 E HttpOperation: 	at czp.a(PG:18188)
07-05 15:40:08.652  2467  3767 E HttpOperation: 	at czp.a(PG:9081)
07-05 15:40:08.652  2467  3767 E HttpOperation: 	at czq.run(PG:1686)
07-05 15:40:08.652  2467  3767 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 15:40:08.652  2467  3767 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 15:40:08.652  2467  3767 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 15:40:08.652  2467  3767 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 15:40:08.652  2467  3767 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 15:40:08.652  2467  3767 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 15:40:08.652  2467  3767 E HttpOperation: 	at jdj.a(PG:4091)
07-05 15:40:08.652  2467  3767 E HttpOperation: 	at jdj.a(PG:1125)
07-05 15:40:08.652  2467  3767 E HttpOperation: 	at jdm.a(PG:77)
07-05 15:40:08.652  2467  3767 E HttpOperation: 	... 12 more
07-05 15:40:08.652  2467  3767 E HttpOperation: Caused by: faj: BadAuthentication
07-05 15:40:08.652  2467  3767 E HttpOperation: 	at fal.a(PG:38)
07-05 15:40:08.652  2467  3767 E HttpOperation: 	at jdj.a(PG:4089)
07-05 15:40:08.652  2467  3767 E HttpOperation: 	... 14 more
,07-05 15:40:08.745  1509  3496 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-05 15:40:08.745  1509  3496 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-05 15:40:08.745  1509  3496 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:40:08.746  1509  3496 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:40:08.769  2467  3767 E HttpOperation: [getmobileexperiments] Unexpected exception
07-05 15:40:08.769  2467  3767 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 15:40:08.769  2467  3767 E HttpOperation: 	at jdm.a(PG:82)
07-05 15:40:08.769  2467  3767 E HttpOperation: 	at jcs.o(PG:406)
07-05 15:40:08.769  2467  3767 E HttpOperation: 	at jcn.a(PG:1379)
07-05 15:40:08.769  2467  3767 E HttpOperation: 	at jcs.i(PG:143)
07-05 15:40:08.769  2467  3767 E HttpOperation: 	,at hec.a(PG:42)
07-05 15:40:08.769  2467  3767 E HttpOperation: 	at hee.a(PG:102)
07-05 15:40:08.769  2467  3767 E HttpOperation: 	at czr.a(PG:65)
07-05 15:40:08.769  2467  3767 E HttpOperation: 	at kka.a(PG:108)
07-05 15:40:08.769  2467  3767 E HttpOperation: 	at czp.a(PG:19176)
07-05 15:40:08.769  2467  3767 E HttpOperation: 	at czp.a(PG:9081)
07-05 15:40:08.769  2467  3767 E HttpOperation: 	at czq.run(PG:1686)
07-05 15:40:08.769  2467  3767 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 15:40:08.769  2467  3767 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 15:40:08.769  2467  3767 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 15:40:08.769  2467  3767 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 15:40:08.769  2467  3767 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 15:40:08.769  2467  3767 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 15:40:08.769  2467  3767 E HttpOperation: 	at jdj.a(PG:4091)
07-05 15:40:08.769  2467  3767 E HttpOperation: 	at jdj.a(PG:1125)
07-05 15:40:08.769  2467  3767 E HttpOperation: 	at jdm.a(PG:77)
07-05 15:40:08.769  2467  3767 E HttpOperation: 	... 15 more
07-05 15:40:08.769  2467  3767 E HttpOperation: Caused by: faj: BadAuthentication
07-05 15:40:08.769  2467  3767 E HttpOperation: 	at fal.a(PG:38)
07-05 15:40:08.769  2467  3767 E HttpOperation: ,	at jdj.a(PG:4089)
07-05 15:40:08.769  2467  3767 E HttpOperation: 	... 17 more
,07-05 15:40:08.770  2467  3767 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-05 15:40:08.770  2467  3767 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-05 15:40:08.770  2467  3767 E ExperimentLoader: 	at jdm.a(PG:82)
07-05 15:40:08.770  2467  3767 E ExperimentLoader: 	at jcs.o(PG:406)
07-05 15:40:08.770  2467  3767 E ExperimentLoader: 	at jcn.a(PG:1379)
07-05 15:40:08.770  2467  3767 E ExperimentLoader: 	at jcs.i(PG:143)
07-05 15:40:08.770  2467  3767 E ExperimentLoader: 	at hec.a(PG:42)
07-05 15:40:08.770  2467  3767 E ExperimentLoader: 	at hee.a(PG:102)
07-05 15:40:08.770  2467  3767 E ExperimentLoader: 	at czr.a(PG:65)
07-05 15:40:08.770  2467  3767 E ExperimentLoader: 	at kka.a(PG:108)
07-05 15:40:08.770  2467  3767 E ExperimentLoader: 	at czp.a(PG:19176)
07-05 15:40:08.770  2467  3767 E ExperimentLoader: 	at czp.a(PG:9081)
07-05 15:40:08.770  2467  3767 E ExperimentLoader: 	at czq.run(PG:1686)
07-05 15:40:08.770  2467  3767 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 15:40:08.770  2467  3767 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 15:40:08.770  2467  3767 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 15:40:08.770  2467  3767 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 15:40:08.770  2467  3767 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-05 15:40:08.770  2467  3767 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 15:40:08.770  2467  3767 E ExperimentLoader: 	at jdj.a(PG:4091)
07-05 15:40:08.770  2467  3767 E ExperimentLoader: 	at jdj.a(PG:1125)
07-05 15:40:08.770  2467  3767 E ExperimentLoader: 	at jdm.a(PG:77)
07-05 15:40:08.770  2467  3767 E ExperimentLoader: 	... 15 more
07-05 15:40:08.770  2467  3767 E ExperimentLoader: Caused by: faj: BadAuthentication
07-05 15:40:08.770  2467  3767 E ExperimentLoader: 	at fal.a(PG:38)
07-05 15:40:08.770  2467  3767 E ExperimentLoader: 	at jdj.a(PG:4089)
07-05 15:40:08.770  2467  3767 E ExperimentLoader: 	... 17 more
,07-05 15:40:08.886   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 290557, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-05 15:40:12.727  3737  3769 V GoogleAuthProtoRequest: [318] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 15:40:12.763  1509  3495 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-05 15:40:12.763  1509  3495 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-05 15:40:12.763  1509  3495 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:40:12.763  1509  3495 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:40:12.790  3737  3769 W ExperimentUpdateService: [318] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-05 15:40:12.790  3737  3769 W ExperimentUpdateService: [318] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 15:40:12.790  3737  3769 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 15:40:12.790  3737  3769 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-05 15:40:12.790  3737  3769 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-05 15:40:12.790  3737  3769 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-05 15:40:12.790  3737  3769 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-05 15:40:12.790  3737  3769 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-05 15:40:12.790  3737  3769 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-05 15:40:12.790  3737  3769 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-05 15:40:12.790  3737  3769 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-05 15:40:12.790  3737  3769 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-05 15:40:19.815   874  2106 D NetlinkSocketObserver: NeighborEvent{elapsedMs=328983, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 15:40:21.473  1653  1766 I Keyboard.Facilitator.LanguageModelFlusher: run()
07-05 15:40:21.473  1653  1766 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-05 15:40:21.515  1509  1509 I ConfigService: onCreate
,07-05 15:40:26.584  1509  1509 I ConfigService: onDestroy
,07-05 15:40:32.647  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:40:32.657  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:40:32.663  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:40:32.723  1509  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-05 15:40:32.724  1509  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-05 15:40:32.724  1509  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:40:32.725  1509  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:40:32.761  1509  1523 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 15:40:32.761  1509  1523 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 15:40:32.761  1509  1523 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 15:40:32.761  1509  1523 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-05 15:40:32.761  1509  1523 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 15:40:32.761  1509  1523 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 15:40:32.761  1509  1523 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 15:40:32.771  3367  3399 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-05 15:40:32.771  3367  3399 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-05 15:40:32.771  3367  3399 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-05 15:40:32.771  3367  3399 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-05 15:40:32.771  3367  3399 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-05 15:40:32.771  3367  3399 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-05 15:40:32.771  3367  3399 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 15:40:42.908   874   884 I ActivityManager: Start proc 3775:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,07-05 15:40:42.966  3775  3775 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,07-05 15:40:43.027  3775  3787 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-05 15:40:43.145  3775  3787 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-05 15:40:43.206  3775  3787 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 15:40:43.251  3775  3775 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,07-05 15:40:43.488  3775  3775 W InstanceID/Rpc: Found 10011
,07-05 15:40:43.638  3811  3811 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-49621204.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-49621204.dex
,07-05 15:40:43.703  3811  3811 I dex2oat : dex2oat took 66.014ms (threads: 4) arena alloc=218KB java alloc=29KB native alloc=1642KB free=1685KB
,07-05 15:40:43.736   874  3078 I ActivityManager: Killing 2372:com.google.android.talk/u0a61 (adj 15): empty #17
,07-05 15:41:09.629   874  2106 D NetlinkSocketObserver: NeighborEvent{elapsedMs=378797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 15:41:13.730  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:41:13.732  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:41:13.750  3737  3860 V GoogleAuthProtoRequest: [319] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 15:41:13.825  1509  2052 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-05 15:41:13.825  1509  2052 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-05 15:41:13.826  1509  2052 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:41:13.826  1509  2052 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:41:13.840  3737  3860 W ExperimentUpdateService: [319] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-05 15:41:13.841  3737  3860 W ExperimentUpdateService: [319] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 15:41:13.841  3737  3860 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 15:41:13.841  3737  3860 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-05 15:41:13.841  3737  3860 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-05 15:41:13.841  3737  3860 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-05 15:41:13.841  3737  3860 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-05 15:41:13.841  3737  3860 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-05 15:41:13.841  3737  3860 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-05 15:41:13.841  3737  3860 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-05 15:41:13.841  3737  3860 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-05 15:41:13.841  3737  3860 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-05 15:41:21.389   874  2106 D NetlinkSocketObserver: NeighborEvent{elapsedMs=390557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 15:41:38.029   874  2106 D NetlinkSocketObserver: NeighborEvent{elapsedMs=407197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 15:41:57.962   874  2106 D NetlinkSocketObserver: NeighborEvent{elapsedMs=427130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 15:42:14.615   874  2106 D NetlinkSocketObserver: NeighborEvent{elapsedMs=443784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 15:42:37.762   874  2106 D NetlinkSocketObserver: NeighborEvent{elapsedMs=466930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 15:42:54.402   874  2106 D NetlinkSocketObserver: NeighborEvent{elapsedMs=483570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 15:43:09.180  2986  3869 V KeepSync: Connecting to GoogleApiClient
,07-05 15:43:09.181   874  1379 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-05 15:43:09.236  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:43:09.240  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:43:09.271  1509  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-05 15:43:09.271  1509  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-05 15:43:09.271  1509  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:43:09.271  1509  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:43:09.294  1925  3870 V BaseAuthAsyncOperation: access token request failed
07-05 15:43:09.295  2986  3869 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-05 15:43:09.343  1509  3495 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-05 15:43:09.343  1509  3495 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,07-05 15:43:09.343  1509  3495 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:43:09.344  1509  3495 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:43:09.357  2986  3869 E KeepSync: IOException
07-05 15:43:09.357  2986  3869 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-05 15:43:09.357  2986  3869 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-05 15:43:09.357  2986  3869 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-05 15:43:09.357  2986  3869 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-05 15:43:09.357  2986  3869 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-05 15:43:09.357  2986  3869 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-05 15:43:09.357  2986  3869 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-05 15:43:09.357  2986  3869 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-05 15:43:09.357  2986  3869 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-05 15:43:09.357  2986  3869 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-05 15:43:09.357  2986  3869 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-05 15:43:09.357  2986  3869 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-05 15:43:09.357  2986  3869 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-05 15:43:09.357  2986  3869 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-05 15:43:09.357  2986  3869 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 15:43:09.357  2986  3869 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 15:43:09.357  2986  3869 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-05 15:43:09.357  2986  3869 E KeepSync: 	... 10 more
,07-05 15:43:09.357  2986  3869 W KeepSync: Sync result 2
,07-05 15:43:09.369   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 498228, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-05 15:43:13.931  3737  3871 V GoogleAuthProtoRequest: [320] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 15:43:13.954  1509  3496 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-05 15:43:13.954  1509  3496 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,07-05 15:43:13.954  1509  3496 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:43:13.954  1509  3496 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:43:13.968  3737  3871 W ExperimentUpdateService: [320] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-05 15:43:13.968  3737  3871 W ExperimentUpdateService: [320] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 15:43:13.968  3737  3871 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 15:43:13.968  3737  3871 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-05 15:43:13.968  3737  3871 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-05 15:43:13.968  3737  3871 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-05 15:43:13.968  3737  3871 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-05 15:43:13.968  3737  3871 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-05 15:43:13.968  3737  3871 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-05 15:43:13.968  3737  3871 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-05 15:43:13.968  3737  3871 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-05 15:43:13.968  3737  3871 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-05 15:43:55.814  3432  3873 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 15:43:55.830  3432  3874 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-05 15:43:55.839  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:43:55.840  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:43:55.866  1509  3495 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 15:43:55.866  1509  3495 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 15:43:55.866  1509  3495 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:43:55.867  1509  3495 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:43:55.909  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:43:55.911  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:43:55.951  1509  3496 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 15:43:55.951  1509  3496 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 15:43:55.951  1509  3496 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:43:55.951  1509  3496 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:43:55.978  3432  3874 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-05 15:43:55.979  3432  3873 E BooksSync: Soft error
07-05 15:43:55.979  3432  3873 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 15:43:55.979  3432  3873 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-05 15:43:55.979  3432  3873 E BooksSync: Sync error
07-05 15:43:55.979  3432  3873 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 15:43:55.979  3432  3873 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-05 15:43:55.979  3432  3873 I BooksSync: Finished books sync
,07-05 15:43:55.985   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 544864, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 15:44:33.080  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:44:33.082  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:44:33.126  1509  3495 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-05 15:44:33.126  1509  3495 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-05 15:44:33.126  1509  3495 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 15:44:33.126  1509  3495 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:44:33.156  2467  3881 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-05 15:44:33.156  2467  3881 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 15:44:33.156  2467  3881 E HttpOperation: 	at jdm.a(PG:82)
07-05 15:44:33.156  2467  3881 E HttpOperation: 	at jcs.o(PG:406)
07-05 15:44:33.156  2467  3881 E HttpOperation: 	at jcn.a(PG:1379)
07-05 15:44:33.156  2467  3881 E HttpOperation: 	at jcs.i(PG:143)
07-05 15:44:33.156  2467  3881 E HttpOperation: 	at blb.a(PG:3937)
07-05 15:44:33.156  2467  3881 E HttpOperation: 	at czp.a(PG:18188)
07-05 15:44:33.156  2467  3881 E HttpOperation: 	,at czp.a(PG:9081)
07-05 15:44:33.156  2467  3881 E HttpOperation: 	at czq.run(PG:1686)
07-05 15:44:33.156  2467  3881 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 15:44:33.156  2467  3881 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 15:44:33.156  2467  3881 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 15:44:33.156  2467  3881 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 15:44:33.156  2467  3881 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 15:44:33.156  2467  3881 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 15:44:33.156  2467  3881 E HttpOperation: 	at jdj.a(PG:4091)
07-05 15:44:33.156  2467  3881 E HttpOperation: 	at jdj.a(PG:1125)
07-05 15:44:33.156  2467  3881 E HttpOperation: 	at jdm.a(PG:77)
07-05 15:44:33.156  2467  3881 E HttpOperation: 	... 12 more
07-05 15:44:33.156  2467  3881 E HttpOperation: Caused by: faj: BadAuthentication
07-05 15:44:33.156  2467  3881 E HttpOperation: 	at fal.a(PG:38)
07-05 15:44:33.156  2467  3881 E HttpOperation: 	at jdj.a(PG:4089)
07-05 15:44:33.156  2467  3881 E HttpOperation: 	... 14 more
,07-05 15:44:33.217  1509  3496 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-05 15:44:33.217  1509  3496 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-05 15:44:33.217  1509  3496 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 15:44:33.217  1509  3496 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:44:33.233  2467  3881 E HttpOperation: [getmobileexperiments] Unexpected exception
07-05 15:44:33.233  2467  3881 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 15:44:33.233  2467  3881 E HttpOperation: 	at jdm.a(PG:82)
07-05 15:44:33.233  2467  3881 E HttpOperation: 	at jcs.o(PG:406)
07-05 15:44:33.233  2467  3881 E HttpOperation: 	at jcn.a(PG:1379)
07-05 15:44:33.233  2467  3881 E HttpOperation: 	at jcs.i(PG:143)
07-05 15:44:33.233  2467  3881 E HttpOperation: 	at hec.a(PG:42)
07-05 15:44:33.233  2467  3881 E HttpOperation: 	at hee.a(PG:102)
07-05 15:44:33.233  2467  3881 E HttpOperation: 	at czr.a(PG:65)
07-05 15:44:33.233  2467  3881 E HttpOperation: 	at kka.a(PG:108)
07-05 15:44:33.233  2467  3881 E HttpOperation: 	at czp.a(PG:19176)
07-05 15:44:33.233  2467  3881 E HttpOperation: 	at czp.a(PG:9081)
07-05 15:44:33.233  2467  3881 E HttpOperation: 	at czq.run(PG:1686)
07-05 15:44:33.233  2467  3881 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 15:44:33.233  2467  3881 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 15:44:33.233  2467  3881 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 15:44:33.233  2467  3881 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 15:44:33.233  2467  3881 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 15:44:33.233  2467  3881 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 15:44:33.233  2467  3881 E HttpOperation: 	at jdj.a(PG:4091)
07-05 15:44:33.233  2467  3881 E HttpOperation: 	at jdj.a(PG:1125)
07-05 15:44:33.233  2467  3881 E HttpOperation: 	at jdm.a(PG:77)
07-05 15:44:33.233  2467  3881 E HttpOperation: 	... 15 more
07-05 15:44:33.233  2467  3881 E HttpOperation: Caused by: faj: BadAuthentication
07-05 15:44:33.233  2467  3881 E HttpOperation: 	at fal.a(PG:38)
07-05 15:44:33.233  2467  3881 E HttpOperation: 	at jdj.a(PG:4089)
07-05 15:44:33.233  2467  3881 E HttpOperation: 	... 17 more
,07-05 15:44:33.233  2467  3881 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-05 15:44:33.233  2467  3881 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-05 15:44:33.233  2467  3881 E ExperimentLoader: 	at jdm.a(PG:82)
07-05 15:44:33.233  2467  3881 E ExperimentLoader: 	at jcs.o(PG:406)
07-05 15:44:33.233  2467  3881 E ExperimentLoader: 	at jcn.a(PG:1379)
07-05 15:44:33.233  2467  3881 E ExperimentLoader: 	at jcs.i(PG:143)
07-05 15:44:33.233  2467  3881 E ExperimentLoader: 	at hec.a(PG:42)
07-05 15:44:33.233  2467  3881 E ExperimentLoader: 	at hee.a(PG:102)
07-05 15:44:33.233  2467  3881 E ExperimentLoader: 	at czr.a(PG:65)
07-05 15:44:33.233  2467  3881 E ExperimentLoader: 	at kka.a(PG:108)
07-05 15:44:33.233  2467  3881 E ExperimentLoader: 	at czp.a(PG:19176)
07-05 15:44:33.233  2467  3881 E ExperimentLoader: 	at czp.a(PG:9081)
07-05 15:44:33.233  2467  3881 E ExperimentLoader: 	at czq.run(PG:1686)
07-05 15:44:33.233  2467  3881 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 15:44:33.233  2467  3881 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 15:44:33.233  2467  3881 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 15:44:33.233  2467  3881 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 15:44:33.233  2467  3881 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-05 15:44:33.233  2467  3881 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 15:44:33.233  2467  3881 E ExperimentLoader: 	at jdj.a(PG:4091)
07-05 15:44:33.233  2467  3881 E ExperimentLoader: 	at jdj.a(PG:1125)
07-05 15:44:33.233  2467  3881 E ExperimentLoader: 	at jdm.a(PG:77)
07-05 15:44:33.233  2467  3881 E ExperimentLoader: 	... 15 more
07-05 15:44:33.233  2467  3881 E ExperimentLoader: Caused by: faj: BadAuthentication
07-05 15:44:33.233  2467  3881 E ExperimentLoader: 	at fal.a(PG:38)
07-05 15:44:33.233  2467  3881 E ExperimentLoader: 	at jdj.a(PG:4089)
07-05 15:44:33.233  2467  3881 E ExperimentLoader: 	... 17 more
,07-05 15:44:33.435   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 581975, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-05 15:44:38.389   874  2106 D NetlinkSocketObserver: NeighborEvent{elapsedMs=587557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 15:44:55.042   874  2106 D NetlinkSocketObserver: NeighborEvent{elapsedMs=604210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 15:45:38.242   874  2106 D NetlinkSocketObserver: NeighborEvent{elapsedMs=647410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 15:45:54.882   874  2106 D NetlinkSocketObserver: NeighborEvent{elapsedMs=664050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 15:45:55.883  1509  1972 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 15:47:14.155  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:47:14.159  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:47:14.177  3737  3893 V GoogleAuthProtoRequest: [321] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 15:47:14.206  1509  2215 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-05 15:47:14.207  1509  2215 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-05 15:47:14.207  1509  2215 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:47:14.207  1509  2215 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:47:14.224  3737  3893 W ExperimentUpdateService: [321] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-05 15:47:14.225  3737  3893 W ExperimentUpdateService: [321] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 15:47:14.225  3737  3893 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 15:47:14.225  3737  3893 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-05 15:47:14.225  3737  3893 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-05 15:47:14.225  3737  3893 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-05 15:47:14.225  3737  3893 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-05 15:47:14.225  3737  3893 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-05 15:47:14.225  3737  3893 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-05 15:47:14.225  3737  3893 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-05 15:47:14.225  3737  3893 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-05 15:47:14.225  3737  3893 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-05 15:51:22.835  2986  3905 V KeepSync: Connecting to GoogleApiClient
,07-05 15:51:22.836   874  1530 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-05 15:51:22.899  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:51:22.901  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:51:22.935  1509  2215 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
07-05 15:51:22.935  1509  2215 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,07-05 15:51:22.935  1509  2215 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:51:22.936  1509  2215 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:51:22.961  1925  3906 V BaseAuthAsyncOperation: access token request failed
,07-05 15:51:22.962  2986  3905 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-05 15:51:23.026  1509  2052 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-05 15:51:23.026  1509  2052 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,07-05 15:51:23.026  1509  2052 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:51:23.026  1509  2052 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:51:23.047  2986  3905 E KeepSync: IOException
07-05 15:51:23.047  2986  3905 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-05 15:51:23.047  2986  3905 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-05 15:51:23.047  2986  3905 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-05 15:51:23.047  2986  3905 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-05 15:51:23.047  2986  3905 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-05 15:51:23.047  2986  3905 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-05 15:51:23.047  2986  3905 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-05 15:51:23.047  2986  3905 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-05 15:51:23.047  2986  3905 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-05 15:51:23.047  2986  3905 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-05 15:51:23.047  2986  3905 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-05 15:51:23.047  2986  3905 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-05 15:51:23.047  2986  3905 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-05 15:51:23.047  2986  3905 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-05 15:51:23.047  2986  3905 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 15:51:23.047  2986  3905 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 15:51:23.047  2986  3905 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-05 15:51:23.047  2986  3905 E KeepSync: 	... 10 more
07-05 15:51:23.047  2986  3905 W KeepSync: Sync result 2
,07-05 15:51:23.060   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 991818, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-05 15:52:31.257  3432  3911 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 15:52:31.273  3432  3912 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-05 15:52:31.283  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:52:31.285  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:52:31.308  1509  1882 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 15:52:31.308  1509  1882 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 15:52:31.308  1509  1882 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:52:31.308  1509  1882 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:52:31.332  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:52:31.333  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:52:31.353  1509  2215 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-05 15:52:31.354  1509  2215 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-05 15:52:31.354  1509  2215 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:52:31.354  1509  2215 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:52:31.375  3432  3912 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-05 15:52:31.376  3432  3911 E BooksSync: Soft error
07-05 15:52:31.376  3432  3911 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 15:52:31.376  3432  3911 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-05 15:52:31.376  3432  3911 E BooksSync: Sync error
07-05 15:52:31.376  3432  3911 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 15:52:31.376  3432  3911 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-05 15:52:31.376  3432  3911 I BooksSync: Finished books sync
,07-05 15:52:31.383   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1060149, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 15:53:21.632  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:53:21.636  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:53:21.692  1509  2052 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-05 15:53:21.692  1509  2052 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-05 15:53:21.692  1509  2052 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:53:21.692  1509  2052 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:53:21.723  2467  3915 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-05 15:53:21.723  2467  3915 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 15:53:21.723  2467  3915 E HttpOperation: 	at jdm.a(PG:82)
07-05 15:53:21.723  2467  3915 E HttpOperation: 	at jcs.o(PG:406)
07-05 15:53:21.723  2467  3915 E HttpOperation: 	at jcn.a(PG:1379)
07-05 15:53:21.723  2467  3915 E HttpOperation: 	at jcs.i(PG:143)
07-05 15:53:21.723  2467  3915 E HttpOperation: 	at blb.a(PG:3937)
07-05 15:53:21.723  2467  3915 E HttpOperation: 	at czp.a(PG:18188)
07-05 15:53:21.723  2467  3915 E HttpOperation: 	at czp.a(PG:9081)
07-05 15:53:21.723  2467  3915 E HttpOperation: 	at czq.run(PG:1686)
07-05 15:53:21.723  2467  3915 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 15:53:21.723  2467  3915 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 15:53:21.723  2467  3915 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 15:53:21.723  2467  3915 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 15:53:21.723  2467  3915 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 15:53:21.723  2467  3915 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 15:53:21.723  2467  3915 E HttpOperation: 	at jdj.a(PG:4091)
07-05 15:53:21.723  2467  3915 E HttpOperation: 	at jdj.a(PG:1125)
07-05 15:53:21.723  2467  3915 E HttpOperation: 	at jdm.a(PG:77)
07-05 15:53:21.723  2467  3915 E HttpOperation: 	... 12 more
07-05 15:53:21.723  2467  3915 E HttpOperation: Caused by: faj: BadAuthentication
07-05 15:53:21.723  2467  3915 E HttpOperation: 	at fal.a(PG:38)
07-05 15:53:21.723  2467  3915 E HttpOperation: 	at jdj.a(PG:4089)
07-05 15:53:21.723  2467  3915 E HttpOperation: 	... 14 more
,07-05 15:53:21.799  1509  3496 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-05 15:53:21.799  1509  3496 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-05 15:53:21.799  1509  3496 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:53:21.799  1509  3496 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:53:21.836  2467  3915 E HttpOperation: [getmobileexperiments] Unexpected exception
07-05 15:53:21.836  2467  3915 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 15:53:21.836  2467  3915 E HttpOperation: 	at jdm.a(PG:82)
07-05 15:53:21.836  2467  3915 E HttpOperation: 	at jcs.o(PG:406)
07-05 15:53:21.836  2467  3915 E HttpOperation: 	at jcn.a(PG:1379)
07-05 15:53:21.836  2467  3915 E HttpOperation: 	at jcs.i(PG:143)
07-05 15:53:21.836  2467  3915 E HttpOperation: 	at hec.a(PG:42)
07-05 15:53:21.836  2467  3915 E HttpOperation: 	at hee.a(PG:102)
07-05 15:53:21.836  2467  3915 E HttpOperation: 	at czr.a(PG:65)
07-05 15:53:21.836  2467  3915 E HttpOperation: 	at kka.a(PG:108)
07-05 15:53:21.836  2467  3915 E HttpOperation: 	at czp.a(PG:19176)
07-05 15:53:21.836  2467  3915 E HttpOperation: 	at czp.a(PG:9081)
07-05 15:53:21.836  2467  3915 E HttpOperation: 	at czq.run(PG:1686)
07-05 15:53:21.836  2467  3915 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 15:53:21.836  2467  3915 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 15:53:21.836  2467  3915 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 15:53:21.836  2467  3915 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 15:53:21.836  2467  3915 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 15:53:21.836  2467  3915 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 15:53:21.836  2467  3915 E HttpOperation: 	at jdj.a(PG:4091)
07-05 15:53:21.836  2467  3915 E HttpOperation: 	at jdj.a(PG:1125)
07-05 15:53:21.836  2467  3915 E HttpOperation: 	at jdm.a(PG:77)
07-05 15:53:21.836  2467  3915 E HttpOperation: 	... 15 more
07-05 15:53:21.836  2467  3915 E HttpOperation: Caused by: faj: BadAuthentication
07-05 15:53:21.836  2467  3915 E HttpOperation: 	at fal.a(PG:38)
07-05 15:53:21.836  2467  3915 E HttpOperation: 	at jdj.a(PG:4089)
07-05 15:53:21.836  2467  3915 E HttpOperation: 	... 17 more
,07-05 15:53:21.836  2467  3915 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-05 15:53:21.836  2467  3915 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-05 15:53:21.836  2467  3915 E ExperimentLoader: 	at jdm.a(PG:82)
07-05 15:53:21.836  2467  3915 E ExperimentLoader: 	at jcs.o(PG:406)
07-05 15:53:21.836  2467  3915 E ExperimentLoader: 	at jcn.a(PG:1379)
07-05 15:53:21.836  2467  3915 E ExperimentLoader: 	at jcs.i(PG:143)
07-05 15:53:21.836  2467  3915 E ExperimentLoader: 	at hec.a(PG:42)
,07-05 15:53:21.836  2467  3915 E ExperimentLoader: 	at hee.a(PG:102)
07-05 15:53:21.836  2467  3915 E ExperimentLoader: 	at czr.a(PG:65)
07-05 15:53:21.836  2467  3915 E ExperimentLoader: 	at kka.a(PG:108)
07-05 15:53:21.836  2467  3915 E ExperimentLoader: 	at czp.a(PG:19176)
07-05 15:53:21.836  2467  3915 E ExperimentLoader: 	at czp.a(PG:9081)
07-05 15:53:21.836  2467  3915 E ExperimentLoader: 	at czq.run(PG:1686)
07-05 15:53:21.836  2467  3915 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 15:53:21.836  2467  3915 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 15:53:21.836  2467  3915 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 15:53:21.836  2467  3915 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 15:53:21.836  2467  3915 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-05 15:53:21.836  2467  3915 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 15:53:21.836  2467  3915 E ExperimentLoader: 	at jdj.a(PG:4091)
07-05 15:53:21.836  2467  3915 E ExperimentLoader: 	at jdj.a(PG:1125)
07-05 15:53:21.836  2467  3915 E ExperimentLoader: 	at jdm.a(PG:77)
07-05 15:53:21.836  2467  3915 E ExperimentLoader: 	... 15 more
07-05 15:53:21.836  2467  3915 E ExperimentLoader: Caused by: faj: BadAuthentication
07-05 15:53:21.836  2467  3915 E ExperimentLoader: 	at fal.a(PG:38)
07-05 15:53:21.836  2467  3915 E ExperimentLoader: 	at jdj.a(PG:4089)
07-05 15:53:21.836  2467  3915 E ExperimentLoader: 	... 17 more
,07-05 15:53:21.963   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1110444, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-05 15:55:09.478   874   886 I UsageStatsService: User[0] Flushing usage stats to disk
,07-05 15:55:14.303  1925  3924 I EventLogService: Opted in for usage reporting
,07-05 15:55:14.317  1925  3924 I EventLogService: Aggregate from 1467725022464 (log), 1467725022464 (data)
,07-05 15:55:14.339  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:55:14.341  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 15:55:14.355  3737  3925 V GoogleAuthProtoRequest: [322] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 15:55:14.424  1509  2214 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-05 15:55:14.424  1509  2214 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-05 15:55:14.424  1509  2214 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 15:55:14.424  1509  2214 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 15:55:14.434  1925  3924 W EventLogAggregator: Unknown tag: snet_gcore
07-05 15:55:14.434  1925  3924 W EventLogAggregator: Unknown tag: snet_launch_service
,07-05 15:55:14.453  3737  3925 W ExperimentUpdateService: [322] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
07-05 15:55:14.453  3737  3925 W ExperimentUpdateService: [322] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 15:55:14.453  3737  3925 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 15:55:14.453  3737  3925 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-05 15:55:14.453  3737  3925 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-05 15:55:14.453  3737  3925 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-05 15:55:14.453  3737  3925 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-05 15:55:14.453  3737  3925 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-05 15:55:14.453  3737  3925 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-05 15:55:14.453  3737  3925 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-05 15:55:14.453  3737  3925 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-05 15:55:14.453  3737  3925 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-05 15:55:14.528  1925  3924 I ServiceDumpSys: dumping service [account]
,07-05 15:55:19.256   874  2106 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1228424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-05 15:55:27.549   874  2106 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1236717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1401000ms)
```
