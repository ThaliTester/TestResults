#### Test 75789268ed88ae2_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
07-27 10:11:14.536   871  1972 D NetlinkSocketObserver: NeighborEvent{elapsedMs=305120, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 10:11:16.405  3707  3707 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-27 10:11:16.409  3707  3707 D AndroidRuntime: CheckJNI is OFF
07-27 10:11:16.445  3707  3707 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-27 10:11:16.487  3707  3707 I Radio-JNI: register_android_hardware_Radio DONE
07-27 10:11:16.507  3707  3707 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-27 10:11:16.510   871  1696 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-27 10:11:16.576   871  1696 I ActivityManager: Start proc 3717:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-27 10:11:16.585  3707  3707 D AndroidRuntime: Shutting down VM
07-27 10:11:16.694  3717  3717 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-27 10:11:16.723  3717  3717 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
07-27 10:11:16.733  3717  3717 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 7311-7317)
07-27 10:11:16.733  3717  3717 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 10:11:16.750  3717  3717 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {29bea31}
07-27 10:11:16.750  3717  3717 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 10:11:16.751  3717  3717 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-27 10:11:16.756  3717  3717 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-27 10:11:16.757  3717  3717 E SysUtils: ApplicationContext is null in ApplicationStatus
07-27 10:11:16.776  3717  3717 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-27 10:11:16.785  3717  3717 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-27 10:11:16.786  3717  3717 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-27 10:11:16.786  3717  3717 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-27 10:11:16.786  3717  3717 I Adreno  : Build Date                       : 10/20/15
07-27 10:11:16.786  3717  3717 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-27 10:11:16.786  3717  3717 I Adreno  : Local Branch                     : M14
07-27 10:11:16.786  3717  3717 I Adreno  : Remote Branch                    : 
07-27 10:11:16.786  3717  3717 I Adreno  : Remote Branch                    : 
07-27 10:11:16.786  3717  3717 I Adreno  : Reconstruct Branch               : 
,07-27 10:11:16.858   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2564d85:true
07-27 10:11:16.959  3717  3717 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-27 10:11:16.984  3717  3717 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
07-27 10:11:17.070  3717  3755 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
07-27 10:11:17.095  3717  3741 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
07-27 10:11:17.131  3717  3755 I OpenGLRenderer: Initialized EGL, version 1.4
07-27 10:11:17.146  1665  1665 I Keyboard.Facilitator: onFinishInput()
07-27 10:11:17.234   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +592ms (total +694ms)
07-27 10:11:17.272  3717  3717 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3717
07-27 10:11:17.429  3717  3717 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-27 10:11:17.646  3717  3757 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1679820496
07-27 10:11:17.656  3717  3757 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-27 10:11:17.656  3717  3757 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-27 10:11:17.656  3717  3757 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-27 10:11:17.656  3717  3757 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-27 10:11:17.656  3717  3757 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-27 10:11:17.656  3717  3757 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c22bcdc added. We now have 1 listener(s)
07-27 10:11:17.660  3717  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
07-27 10:11:17.661  3717  3757 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-27 10:11:17.662  3717  3757 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 10:11:17.662  3717  3757 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 10:11:17.666  3717  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-27 10:11:17.666  3717  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-27 10:11:17.666  3717  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-27 10:11:17.666  3717  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
07-27 10:11:17.666  3717  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-27 10:11:17.666  3717  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-27 10:11:17.666  3717  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-27 10:11:17.666  3717  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-27 10:11:17.666  3717  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-27 10:11:17.666  3717  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-27 10:11:17.666  3717  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-27 10:11:17.666  3717  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-27 10:11:17.666  3717  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-27 10:11:17.666  3717  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-27 10:11:17.666  3717  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b13f6b added. We now have 1 listener(s)
07-27 10:11:17.667  3717  3757 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 10:11:17.673   871  1317 D WifiService: New client listening to asynchronous messages
07-27 10:11:17.675  3717  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 10:11:17.675  3717  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-27 10:11:17.675  3717  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-27 10:11:17.675  3717  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-27 10:11:17.677  3717  3757 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 10:11:17.677  3717  3757 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
07-27 10:11:17.686  3717  3757 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
07-27 10:11:17.687  3717  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 10:11:17.687  3717  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:17.687  3717  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:17.687  3717  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 10:11:17.687  3717  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 10:11:17.687  3717  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 10:11:17.687  3717  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 10:11:17.687  3717  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 10:11:17.687  3717  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-27 10:11:17.687  3717  3757 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 10:11:17.687  3717  3757 I io.jxcore.node.LifeCycleMonitor: start: OK
07-27 10:11:17.690  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 10:11:17.692  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 10:11:17.738  3717  3717 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-27 10:11:18.274  3717  3764 W jxcore-log: Initializing JXcore engine
,07-27 10:11:18.274  3717  3764 W jxcore-log: JXcore engine is ready
,07-27 10:11:18.311  3764  3764 W Thread-330: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8932 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,07-27 10:11:18.311  3764  3764 W Thread-330: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9676]" dev="sockfs" ino=9676 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-27 10:11:18.311  3764  3764 W Thread-330: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-27 10:11:18.311  3764  3764 W Thread-330: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27758]" dev="sockfs" ino=27758 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-27 10:11:18.327  3717  3764 W jxcore-log: Starting JXcore engine
,07-27 10:11:18.409  3717  3764 W jxcore-log: Platform android
07-27 10:11:18.409  3717  3764 W jxcore-log: 
,07-27 10:11:18.409  3717  3764 W jxcore-log: Process ARCH arm
07-27 10:11:18.409  3717  3764 W jxcore-log: 
,07-27 10:11:18.572  3717  3764 I jxcore-log: JXcore Cordova bridge is ready!
07-27 10:11:18.572  3717  3764 I jxcore-log: 
,07-27 10:11:18.572  3717  3764 W jxcore-log: JXcore engine is started
,07-27 10:11:18.581  3717  3757 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-27 10:11:18.587  3717  3717 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-27 10:11:19.470   871   881 I ActivityManager: Start proc 3765:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,07-27 10:11:19.528  3765  3765 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,07-27 10:11:19.603  3765  3777 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-27 10:11:19.718  3765  3777 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-27 10:11:19.768  3765  3777 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-27 10:11:19.833  3765  3765 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,07-27 10:11:20.043  3765  3765 W InstanceID/Rpc: Found 10011
,07-27 10:11:20.162  3804  3804 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-330615845.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-330615845.dex
,07-27 10:11:20.170   871   882 I ActivityManager: Killing 2845:com.google.android.calendar/u0a37 (adj 15): empty #17
,07-27 10:11:20.233  3804  3804 I dex2oat : dex2oat took 78.981ms (threads: 4) arena alloc=372KB java alloc=29KB native alloc=1515KB free=1556KB
,07-27 10:11:21.698  3475  3847 I BooksSync: Starting books sync for 61035162, extras: ade
,07-27 10:11:21.761  3475  3848 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-27 10:11:21.771  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:11:21.773  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:11:21.790  1518  1950 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-27 10:11:21.790  1518  1950 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-27 10:11:21.791  1518  1950 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 10:11:21.791  1518  1950 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:11:21.811  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:11:21.813  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:11:21.833  1518  1949 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 10:11:21.833  1518  1949 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-27 10:11:21.834  1518  1949 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 10:11:21.834  1518  1949 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:11:21.851  3475  3848 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-27 10:11:21.851  3475  3847 E BooksSync: Soft error
07-27 10:11:21.851  3475  3847 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 10:11:21.851  3475  3847 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-27 10:11:21.852  3475  3847 E BooksSync: Sync error
07-27 10:11:21.852  3475  3847 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 10:11:21.852  3475  3847 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-27 10:11:21.852  3475  3847 I BooksSync: Finished books sync
,07-27 10:11:21.863   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 312177, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 10:11:25.173   871  1972 D NetlinkSocketObserver: NeighborEvent{elapsedMs=315757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-27 10:11:28.793  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-27 10:11:28.793  3717  3764 I jxcore-log: 
,07-27 10:11:28.796  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-27 10:11:28.796  3717  3764 I jxcore-log: 
,07-27 10:11:28.807  3717  3764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 10:11:28.807  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:28.807  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:28.807  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 10:11:28.807  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 10:11:28.807  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 10:11:28.807  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 10:11:28.807  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 10:11:28.815  3717  3764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 10:11:28.821  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-27 10:11:28.821  3717  3764 I jxcore-log: 
,07-27 10:11:28.829  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-27 10:11:28.829  3717  3764 I jxcore-log: 
,07-27 10:11:29.188  3717  3764 D ExecuteNativeTests: Running unit tests
,07-27 10:11:29.248  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 10:11:29.248  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c406241 added. We now have 2 listener(s)
,07-27 10:11:29.249  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-27 10:11:29.249  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 10:11:29.249  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 10:11:29.249  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 10:11:29.250  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 added. We now have 2 listener(s)
07-27 10:11:29.250  3717  3764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 10:11:29.251  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 10:11:29.254  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 10:11:29.271  3717  3764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 10:11:29.271  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:29.271  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:29.271  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 10:11:29.271  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 10:11:29.271  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 10:11:29.271  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 10:11:29.271  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 10:11:29.275  3717  3764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 10:11:29.276  3717  3764 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-27 10:11:29.286  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:29.286  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-27 10:11:29.287  3717  3764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-27 10:11:29.287  3717  3764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-27 10:11:29.291  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 10:11:29.292  3717  3764 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,07-27 10:11:29.293  3717  3764 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,07-27 10:11:29.293  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,07-27 10:11:29.294  3717  3764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-27 10:11:29.295  3717  3764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-27 10:11:29.298  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-27 10:11:29.300  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-27 10:11:29.300  3717  3764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-27 10:11:29.301  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-27 10:11:29.301  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 10:11:29.301  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 10:11:29.301  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 10:11:29.301  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c406241 removed from the list
07-27 10:11:29.301  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.301  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 removed from the list
07-27 10:11:29.302  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
07-27 10:11:29.302  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 10:11:29.302  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.302  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.303  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:29.303  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 10:11:29.303  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.303  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
,07-27 10:11:29.307  3717  3764 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-27 10:11:29.308  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-27 10:11:29.308  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 10:11:29.308  3717  3764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-27 10:11:29.309  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-27 10:11:29.309  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.309  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.309  3717  3764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c406241 not in the list
07-27 10:11:29.309  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 10:11:29.309  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
,07-27 10:11:29.310  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
07-27 10:11:29.310  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.310  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.310  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.310  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.311  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:29.312  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-27 10:11:29.312  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.312  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
,07-27 10:11:29.317  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-27 10:11:29.317  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,07-27 10:11:29.318  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-27 10:11:29.318  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-27 10:11:29.318  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-27 10:11:29.318  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,07-27 10:11:29.318  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-27 10:11:29.318  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-27 10:11:29.318  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-27 10:11:29.318  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,07-27 10:11:29.318  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-27 10:11:29.318  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-27 10:11:29.318  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-27 10:11:29.318  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-27 10:11:29.319  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-27 10:11:29.319  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-27 10:11:29.319  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-27 10:11:29.319  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-27 10:11:29.319  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-27 10:11:29.319  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-27 10:11:29.319  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-27 10:11:29.319  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-27 10:11:29.319  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-27 10:11:29.320  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-27 10:11:29.320  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-27 10:11:29.320  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-27 10:11:29.320  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-27 10:11:29.320  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-27 10:11:29.320  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-27 10:11:29.320  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-27 10:11:29.320  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-27 10:11:29.320  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 10:11:29.320  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 10:11:29.320  3717  3764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 10:11:29.321  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:29.321  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.321  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.321  3717  3764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c406241 not in the list
07-27 10:11:29.321  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.322  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.322  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
07-27 10:11:29.322  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.322  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.322  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.322  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.325  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:29.325  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 10:11:29.325  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.326  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.327  3717  3764 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-27 10:11:29.331  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 10:11:29.341  3717  3764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 10:11:29.341  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:29.341  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:29.341  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 10:11:29.341  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 10:11:29.341  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 10:11:29.341  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 10:11:29.341  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 10:11:29.345  3717  3764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 10:11:29.346  3717  3764 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 10:11:29.346  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 10:11:29.346  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 10:11:29.346  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 10:11:29.346  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-27 10:11:29.351  3717  3764 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-27 10:11:29.351  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-27 10:11:29.351  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 10:11:29.366  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 10:11:29.368  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-27 10:11:29.370  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-27 10:11:29.370  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-27 10:11:29.373  3717  3764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
07-27 10:11:29.377  3717  3764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
07-27 10:11:29.377  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-27 10:11:29.377  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-27 10:11:29.377  3717  3764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-27 10:11:29.379  3717  3764 D BluetoothAdapter: STATE_ON
07-27 10:11:29.383  2529  2665 D BtGatt.GattService: registerClient() - UUID=e0954ad1-a036-44b4-91ff-0d11ae91e447
07-27 10:11:29.384  2529  2554 D BtGatt.GattService: onClientRegistered() - UUID=e0954ad1-a036-44b4-91ff-0d11ae91e447, clientIf=5
07-27 10:11:29.386  3717  3727 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-27 10:11:29.389  2529  2667 D BtGatt.GattService: start scan with filters
,07-27 10:11:29.395  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-27 10:11:29.395  2529  2557 D BtGatt.ScanManager: handling starting scan
07-27 10:11:29.395  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-27 10:11:29.396  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,07-27 10:11:29.396  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-27 10:11:29.397  2529  2557 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d788d33
,07-27 10:11:29.398  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-27 10:11:29.398  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-27 10:11:29.399  3717  3717 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-27 10:11:29.400  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-27 10:11:29.403  3717  3764 I io.jxcore.node.ConnectionHelper: start: OK
,07-27 10:11:29.404  3717  3717 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 10:11:29.404  3717  3717 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,07-27 10:11:29.405  2529  2554 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-27 10:11:29.405  2529  2554 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-27 10:11:29.406  2529  2557 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-27 10:11:29.408  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-27 10:11:29.408  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-27 10:11:29.408  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.408  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-27 10:11:29.408  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,07-27 10:11:29.408  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-27 10:11:29.408  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-27 10:11:29.408  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-27 10:11:29.409  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-27 10:11:29.409  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-27 10:11:29.410  3717  3764 D BluetoothAdapter: STATE_ON
,07-27 10:11:29.411  2529  2667 D BtGatt.GattService: stopScan() - queue size =1
07-27 10:11:29.411  2529  2540 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-27 10:11:29.412  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 10:11:29.412  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-27 10:11:29.412  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-27 10:11:29.412  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-27 10:11:29.412  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-27 10:11:29.413  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-27 10:11:29.414  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-27 10:11:29.414  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-27 10:11:29.414  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-27 10:11:29.416  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-27 10:11:29.417  2529  2554 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-27 10:11:29.417  2529  2554 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:29.417  3717  3717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 10:11:29.417  3717  3717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 10:11:29.417  3717  3717 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 10:11:29.417  3717  3717 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 10:11:29.417  3717  3717 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,07-27 10:11:29.417  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:29.417  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.418  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 10:11:29.417  2529  2557 D BtGatt.ScanManager: Starting BLE batch scan
07-27 10:11:29.418  3717  3764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c406241 not in the list
07-27 10:11:29.418  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.418  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.418  2529  2557 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-27 10:11:29.418  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
07-27 10:11:29.418  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.418  3717  3764 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-27 10:11:29.420  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 10:11:29.425  3717  3764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 10:11:29.425  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:29.425  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:29.425  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 10:11:29.425  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 10:11:29.425  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 10:11:29.425  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 10:11:29.425  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 10:11:29.428  3717  3764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 10:11:29.428  3717  3764 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-27 10:11:29.428  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 10:11:29.428  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-27 10:11:29.428  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 10:11:29.428  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 10:11:29.430  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:29.432  3717  3764 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-27 10:11:29.432  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-27 10:11:29.433  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:29.435  2529  2554 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,07-27 10:11:29.435  2529  2554 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-27 10:11:29.436  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-27 10:11:29.436  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-27 10:11:29.436  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-27 10:11:29.438  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-27 10:11:29.438  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-27 10:11:29.439  3717  3764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-27 10:11:29.439  3717  3764 D BluetoothAdapter: STATE_ON
07-27 10:11:29.441  2529  2554 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-27 10:11:29.441  2529  2554 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-27 10:11:29.441  2529  2665 D BtGatt.GattService: registerClient() - UUID=b562375d-6668-481a-90d7-f8128c0844c7
07-27 10:11:29.442  2529  2554 D BtGatt.GattService: onClientRegistered() - UUID=b562375d-6668-481a-90d7-f8128c0844c7, clientIf=5
,07-27 10:11:29.442  3717  3727 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-27 10:11:29.442  2529  2667 D BtGatt.GattService: start scan with filters
,07-27 10:11:29.446  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-27 10:11:29.446  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-27 10:11:29.446  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-27 10:11:29.446  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-27 10:11:29.449  2529  2554 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,07-27 10:11:29.449  2529  2554 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:29.450  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-27 10:11:29.450  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-27 10:11:29.450  3717  3717 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-27 10:11:29.450  2529  2557 D BtGatt.ScanManager: stopping BLe Batch
,07-27 10:11:29.453  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-27 10:11:29.455  3717  3764 I io.jxcore.node.ConnectionHelper: start: OK
,07-27 10:11:29.455  3717  3717 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 10:11:29.455  3717  3717 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,07-27 10:11:29.458  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 10:11:29.458  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-27 10:11:29.458  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 10:11:29.458  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-27 10:11:29.458  2529  2554 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-27 10:11:29.458  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-27 10:11:29.458  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-27 10:11:29.458  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-27 10:11:29.458  2529  2554 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:29.458  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-27 10:11:29.459  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-27 10:11:29.459  2529  2557 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-27 10:11:29.459  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-27 10:11:29.460  3717  3764 D BluetoothAdapter: STATE_ON
07-27 10:11:29.460  2529  2665 D BtGatt.GattService: stopScan() - queue size =0
,07-27 10:11:29.461  2529  2667 D BtGatt.GattService: unregisterClient() - clientIf=5
07-27 10:11:29.461  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 10:11:29.461  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,07-27 10:11:29.461  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-27 10:11:29.461  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-27 10:11:29.461  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,07-27 10:11:29.464  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 10:11:29.464  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-27 10:11:29.464  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-27 10:11:29.464  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-27 10:11:29.465  2529  2554 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-27 10:11:29.465  2529  2554 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:29.465  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-27 10:11:29.466  2529  2557 D BtGatt.ScanManager: handling starting scan
07-27 10:11:29.466  3717  3717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 10:11:29.466  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:29.466  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 10:11:29.467  3717  3717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 10:11:29.467  3717  3717 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 10:11:29.467  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 10:11:29.467  3717  3764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c406241 not in the list
07-27 10:11:29.467  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.467  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.467  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
07-27 10:11:29.467  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.468  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.468  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 10:11:29.469  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:29.469  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-27 10:11:29.469  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.470  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.470  3717  3764 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-27 10:11:29.471  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 10:11:29.473  2529  2554 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-27 10:11:29.473  2529  2554 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:29.473  2529  2557 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-27 10:11:29.477  3717  3764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 10:11:29.477  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:29.477  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:29.477  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 10:11:29.477  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 10:11:29.477  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 10:11:29.477  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 10:11:29.477  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 10:11:29.480  2529  2554 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,07-27 10:11:29.480  2529  2554 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:29.480  3717  3764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 10:11:29.480  2529  2557 D BtGatt.ScanManager: Starting BLE batch scan
,07-27 10:11:29.480  3717  3764 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 10:11:29.480  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 10:11:29.480  2529  2557 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-27 10:11:29.480  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-27 10:11:29.480  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 10:11:29.480  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-27 10:11:29.484  3717  3764 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-27 10:11:29.484  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-27 10:11:29.485  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:29.488  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:29.491  2529  2554 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-27 10:11:29.491  2529  2554 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-27 10:11:29.491  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-27 10:11:29.492  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-27 10:11:29.492  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-27 10:11:29.496  2529  2554 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-27 10:11:29.496  2529  2554 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-27 10:11:29.496  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-27 10:11:29.496  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-27 10:11:29.496  3717  3764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-27 10:11:29.497  3717  3764 D BluetoothAdapter: STATE_ON
,07-27 10:11:29.500  2529  2667 D BtGatt.GattService: registerClient() - UUID=9c53ba06-81f8-47e9-8234-6cc3c06f879d
,07-27 10:11:29.500  2529  2554 D BtGatt.GattService: onClientRegistered() - UUID=9c53ba06-81f8-47e9-8234-6cc3c06f879d, clientIf=5
,07-27 10:11:29.501  3717  3728 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-27 10:11:29.501  2529  2540 D BtGatt.GattService: start scan with filters
,07-27 10:11:29.502  2529  2554 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,07-27 10:11:29.502  2529  2554 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:29.503  2529  2557 D BtGatt.ScanManager: stopping BLe Batch
,07-27 10:11:29.504  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-27 10:11:29.504  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,07-27 10:11:29.504  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-27 10:11:29.504  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-27 10:11:29.506  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-27 10:11:29.507  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-27 10:11:29.507  3717  3717 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-27 10:11:29.508  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-27 10:11:29.508  2529  2554 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-27 10:11:29.508  2529  2554 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:29.509  2529  2557 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-27 10:11:29.510  3717  3764 I io.jxcore.node.ConnectionHelper: start: OK
,07-27 10:11:29.510  3717  3717 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 10:11:29.510  3717  3717 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,07-27 10:11:29.510  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 10:11:29.511  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-27 10:11:29.511  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.511  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-27 10:11:29.511  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-27 10:11:29.511  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-27 10:11:29.511  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,07-27 10:11:29.511  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-27 10:11:29.511  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-27 10:11:29.511  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-27 10:11:29.512  3717  3764 D BluetoothAdapter: STATE_ON
07-27 10:11:29.512  2529  2540 D BtGatt.GattService: stopScan() - queue size =0
,07-27 10:11:29.513  2529  2541 D BtGatt.GattService: unregisterClient() - clientIf=5
07-27 10:11:29.513  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 10:11:29.513  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-27 10:11:29.513  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,07-27 10:11:29.513  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-27 10:11:29.513  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-27 10:11:29.515  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 10:11:29.515  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-27 10:11:29.515  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,07-27 10:11:29.515  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 10:11:29.515  2529  2554 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-27 10:11:29.515  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 10:11:29.516  2529  2554 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:29.516  3717  3717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-27 10:11:29.516  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 10:11:29.517  3717  3764 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-27 10:11:29.517  3717  3717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 10:11:29.517  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-27 10:11:29.517  3717  3717 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 10:11:29.517  3717  3764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 10:11:29.517  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:29.517  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 10:11:29.517  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-27 10:11:29.517  3717  3764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c406241 not in the list
07-27 10:11:29.517  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.517  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.517  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
07-27 10:11:29.517  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.518  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.518  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.518  2529  2557 D BtGatt.ScanManager: handling starting scan
07-27 10:11:29.518  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:29.519  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-27 10:11:29.519  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.519  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.519  3717  3764 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-27 10:11:29.520  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 10:11:29.520  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 10:11:29.520  3717  3764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 10:11:29.520  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:29.520  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.520  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 10:11:29.520  3717  3764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c406241 not in the list
07-27 10:11:29.520  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.520  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.520  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
07-27 10:11:29.520  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.520  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.521  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.521  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.521  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:29.522  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 10:11:29.522  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 10:11:29.522  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.523  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-27 10:11:29.523  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 10:11:29.523  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 10:11:29.523  3717  3764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 10:11:29.523  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:29.523  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 10:11:29.523  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.523  3717  3764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c406241 not in the list
07-27 10:11:29.523  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.523  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.524  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
07-27 10:11:29.524  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.524  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 10:11:29.524  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.524  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.525  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:29.525  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 10:11:29.525  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 10:11:29.525  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.526  3717  3764 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,07-27 10:11:29.526  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-27 10:11:29.526  2529  2554 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-27 10:11:29.526  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-27 10:11:29.526  2529  2554 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-27 10:11:29.526  3717  3764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 10:11:29.526  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-27 10:11:29.527  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 10:11:29.527  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.527  3717  3764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c406241 not in the list
07-27 10:11:29.527  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.527  2529  2557 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-27 10:11:29.527  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.527  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
,07-27 10:11:29.527  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.527  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.527  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.527  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 10:11:29.528  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:29.528  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-27 10:11:29.528  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 10:11:29.528  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.529  3717  3764 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-27 10:11:29.529  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-27 10:11:29.529  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 10:11:29.529  3717  3764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 10:11:29.529  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:29.529  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.529  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 10:11:29.529  3717  3764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c406241 not in the list
07-27 10:11:29.529  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.529  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.529  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
07-27 10:11:29.529  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.530  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 10:11:29.530  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.530  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.530  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:29.530  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-27 10:11:29.531  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.531  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.531  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-27 10:11:29.531  3717  3764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-27 10:11:29.531  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-27 10:11:29.531  3717  3764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-27 10:11:29.532  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-27 10:11:29.532  3717  3764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-27 10:11:29.532  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 10:11:29.532  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-27 10:11:29.532  3717  3764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 10:11:29.532  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:29.532  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.532  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.532  3717  3764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c406241 not in the list
07-27 10:11:29.532  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 10:11:29.532  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.533  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
07-27 10:11:29.533  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.533  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.533  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.533  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 10:11:29.534  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:29.534  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 10:11:29.534  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.534  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.535  2529  2554 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-27 10:11:29.535  2529  2554 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:29.535  3717  3764 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,07-27 10:11:29.535  3717  3764 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-27 10:11:29.535  2529  2557 D BtGatt.ScanManager: Starting BLE batch scan
07-27 10:11:29.535  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-27 10:11:29.535  2529  2557 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-27 10:11:29.538  3717  3764 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 10:11:29.538  3717  3764 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-27 10:11:29.538  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-27 10:11:29.538  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-27 10:11:29.538  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,07-27 10:11:29.538  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-27 10:11:29.538  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-27 10:11:29.538  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-27 10:11:29.539  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-27 10:11:29.539  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-27 10:11:29.539  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-27 10:11:29.539  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-27 10:11:29.539  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-27 10:11:29.539  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-27 10:11:29.539  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-27 10:11:29.539  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-27 10:11:29.539  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-27 10:11:29.539  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-27 10:11:29.539  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-27 10:11:29.539  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-27 10:11:29.539  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-27 10:11:29.539  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-27 10:11:29.540  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-27 10:11:29.540  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,07-27 10:11:29.540  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-27 10:11:29.540  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,07-27 10:11:29.540  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-27 10:11:29.540  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-27 10:11:29.540  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-27 10:11:29.540  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,07-27 10:11:29.540  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-27 10:11:29.540  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,07-27 10:11:29.540  3717  3764 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-27 10:11:29.540  3717  3764 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,07-27 10:11:29.541  3717  3764 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-27 10:11:29.541  3717  3764 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 10:11:29.541  3717  3764 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,07-27 10:11:29.541  3717  3764 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-27 10:11:29.541  3717  3764 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,07-27 10:11:29.541  3717  3764 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-27 10:11:29.541  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
07-27 10:11:29.544  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-27 10:11:29.545  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
07-27 10:11:29.545  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,07-27 10:11:29.545  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-27 10:11:29.545  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-27 10:11:29.545  3717  3764 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,07-27 10:11:29.546  3717  3764 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 10:11:29.546  3717  3764 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,07-27 10:11:29.546  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 10:11:29.546  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 10:11:29.547  3717  3764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-27 10:11:29.547  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:29.547  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.547  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.547  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-27 10:11:29.547  3717  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 394)
07-27 10:11:29.547  3717  3764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c406241 not in the list
,07-27 10:11:29.548  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.548  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
,07-27 10:11:29.548  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
07-27 10:11:29.548  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.548  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.548  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.548  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 10:11:29.549  3717  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 394
07-27 10:11:29.550  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:29.550  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 10:11:29.550  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.550  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.550  3717  3850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 10:11:29.550  3717  3764 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,07-27 10:11:29.551  2529  2554 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-27 10:11:29.551  2529  2554 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:29.551  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 10:11:29.551  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 10:11:29.551  3717  3764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 10:11:29.551  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:29.551  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.551  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.551  3717  3764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c406241 not in the list
,07-27 10:11:29.551  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.551  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list,
07-27 10:11:29.552  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
07-27 10:11:29.552  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 10:11:29.552  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.552  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.552  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.553  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-27 10:11:29.553  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 10:11:29.553  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 10:11:29.553  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.553  3717  3764 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-27 10:11:29.554  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 10:11:29.554  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 10:11:29.554  3717  3764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-27 10:11:29.554  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:29.554  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.554  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.554  3717  3764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c406241 not in the list
,07-27 10:11:29.554  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.554  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.554  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
07-27 10:11:29.554  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.554  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.554  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 10:11:29.554  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.554  3717  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 394)
07-27 10:11:29.555  2529  2662 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
07-27 10:11:29.555  3717  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 394)
07-27 10:11:29.556  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:29.556  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
07-27 10:11:29.556  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.556  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.556  3717  3764 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,07-27 10:11:29.556  3717  3764 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-27 10:11:29.556  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-27 10:11:29.556  3717  3764 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-27 10:11:29.556  3717  3764 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,07-27 10:11:29.557  3717  3764 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-27 10:11:29.557  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-27 10:11:29.557  3717  3764 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-27 10:11:29.557  3717  3764 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-27 10:11:29.557  3717  3764 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55,
07-27 10:11:29.557  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-27 10:11:29.557  3717  3764 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-27 10:11:29.557  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 10:11:29.557  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 10:11:29.557  3717  3764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 10:11:29.555  3717  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 394)
,07-27 10:11:29.558  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:29.558  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.558  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.558  3717  3764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c406241 not in the list
07-27 10:11:29.558  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.558  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.558  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
07-27 10:11:29.558  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 10:11:29.558  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.558  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.558  2529  2554 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-27 10:11:29.558  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.558  2529  2554 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-27 10:11:29.559  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:29.559  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 10:11:29.559  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.559  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.559  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-27 10:11:29.559  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.560  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.560  3717  3764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c406241 not in the list
07-27 10:11:29.560  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.560  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.560  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop,
07-27 10:11:29.560  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.560  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.560  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 10:11:29.560  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.560  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:29.560  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.560  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.560  3717  3764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c406241 not in the list
07-27 10:11:29.560  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 10:11:29.560  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 10:11:29.560  3717  3764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 10:11:29.561  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-27 10:11:29.561  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.561  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.561  3717  3764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c406241 not in the list
07-27 10:11:29.561  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.561  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
,07-27 10:11:29.561  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
07-27 10:11:29.561  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.561  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.561  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.561  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.562  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:29.562  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 10:11:29.562  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 10:11:29.562  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.563  3717  3764 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-27 10:11:29.563  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 10:11:29.564  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-27 10:11:29.565  3717  3764 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-27 10:11:29.565  3717  3764 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-27 10:11:29.565  3717  3717 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-27 10:11:29.565  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-27 10:11:29.565  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-27 10:11:29.565  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:29.565  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,07-27 10:11:29.566  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-27 10:11:29.566  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-27 10:11:29.566  3717  3852 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 10:11:29.566  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.566  3717  3764 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-27 10:11:29.566  3717  3717 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-27 10:11:29.566  3717  3764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c406241 not in the list
07-27 10:11:29.566  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.566  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-27 10:11:29.566  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-27 10:11:29.566  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-27 10:11:29.566  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.566  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.567  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 10:11:29.567  3717  3717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-27 10:11:29.567  3717  3717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 10:11:29.567  3717  3717 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 10:11:29.567  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.568  2529  2554 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-27 10:11:29.568  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 10:11:29.568  2529  2554 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:29.568  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 10:11:29.568  3717  3764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 10:11:29.568  2529  2557 D BtGatt.ScanManager: stopping BLe Batch
07-27 10:11:29.568  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:29.568  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.568  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.568  3717  3764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c406241 not in the list
07-27 10:11:29.568  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.568  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.568  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
07-27 10:11:29.568  3717  3852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-27 10:11:29.568  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 10:11:29.568  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.568  3717  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-27 10:11:29.568  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.568  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.568  3717  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-27 10:11:29.569  3717  3717 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-27 10:11:29.569  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:29.569  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 10:11:29.569  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.569  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.570  3717  3764 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-27 10:11:29.570  3717  3764 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-27 10:11:29.571  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,07-27 10:11:29.571  3717  3764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-27 10:11:29.571  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 10:11:29.571  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 10:11:29.571  3717  3764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 10:11:29.571  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:29.571  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.571  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.571  3717  3764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c406241 not in the list
07-27 10:11:29.571  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.571  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.571  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
07-27 10:11:29.571  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.571  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 10:11:29.571  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.571  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.572  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:29.572  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 10:11:29.573  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.573  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.575  2529  2554 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-27 10:11:29.575  2529  2554 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:29.575  2529  2557 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-27 10:11:29.575  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 10:11:29.575  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 10:11:29.575  3717  3764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 10:11:29.576  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:29.576  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.576  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.576  3717  3764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c406241 not in the list
,07-27 10:11:29.576  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.576  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.576  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
07-27 10:11:29.576  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.576  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.576  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.576  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.577  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:29.577  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 10:11:29.577  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.577  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.577  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 10:11:29.577  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 10:11:29.577  3717  3764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 10:11:29.577  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-27 10:11:29.578  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.578  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.578  3717  3764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c406241 not in the list
07-27 10:11:29.578  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.578  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.578  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
07-27 10:11:29.578  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.578  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.578  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:29.578  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:29.579  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-27 10:11:29.579  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 10:11:29.579  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:29.579  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fd3e6 not in the list
07-27 10:11:29.579  3717  3764 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-27 10:11:29.579  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-27 10:11:29.580  2529  2554 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-27 10:11:29.580  3717  3764 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-27 10:11:29.580  2529  2554 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:29.580  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-27 10:11:29.580  3717  3764 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-27 10:11:29.580  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-27 10:11:29.581  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-27 10:11:29.582  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,07-27 10:11:29.582  3717  3764 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-27 10:11:29.582  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-27 10:11:29.582  3717  3764 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-27 10:11:29.582  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-27 10:11:29.582  3717  3764 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-27 10:11:29.582  3717  3764 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-27 10:11:29.583  3717  3764 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-27 10:11:29.583  3717  3764 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-27 10:11:29.583  3717  3764 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-27 10:11:29.583  3717  3764 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-27 10:11:29.583  3717  3764 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-27 10:11:29.583  3717  3764 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-27 10:11:29.584  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 10:11:29.584  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d401858 added. We now have 2 listener(s)
,07-27 10:11:29.584  3717  3764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 10:11:29.585  3717  3764 D BluetoothAdapter: enable(): BT is already enabled..!
07-27 10:11:29.585   871  1402 D WifiService: setWifiEnabled: true pid=3717, uid=10000
07-27 10:11:29.585   871  1402 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-27 10:11:29.586  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 10:11:29.586  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7c55db1 added. We now have 3 listener(s)
07-27 10:11:29.586  3717  3764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 10:11:29.594  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 10:11:29.594  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@97b0296 added. We now have 4 listener(s)
07-27 10:11:29.594  3717  3764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 10:11:29.597  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 10:11:29.597  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a2dfe17 added. We now have 5 listener(s)
07-27 10:11:29.597  3717  3764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 10:11:29.600   871  1759 D WifiService: setWifiEnabled: false pid=3717, uid=10000
07-27 10:11:29.600   871  1759 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-27 10:11:29.604  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 10:11:29.605  2529  2549 D BluetoothAdapterState: Current state: ON, message: 23
,07-27 10:11:29.605  2529  2549 D BluetoothAdapterProperties: Setting state to 13
07-27 10:11:29.605  2529  2549 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-27 10:11:29.606  2529  2549 D BluetoothAdapterProperties: onBluetoothDisable()
,07-27 10:11:29.606  2529  2549 I BluetoothAdapterState: Entering PendingCommandState
,07-27 10:11:29.607  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 10:11:29.607  3717  3764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 10:11:29.607  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:29.607  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:29.607  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 10:11:29.607  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 10:11:29.607  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 10:11:29.607  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 10:11:29.607  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 10:11:29.607  2529  2554 D BluetoothAdapterProperties: Scan Mode:20
07-27 10:11:29.607  2529  2549 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,07-27 10:11:29.607  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 10:11:29.607  3717  3764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 10:11:29.607  3717  3764 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 10:11:29.609  2529  2529 D HeadsetService: Received stop request...Stopping profile...
,07-27 10:11:29.609  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:29.610  1737  1751 D BluetoothHeadset: Proxy object disconnected
,07-27 10:11:29.611   871   871 D BluetoothHeadset: Proxy object disconnected
,07-27 10:11:29.611   871   871 D BluetoothHeadset: Proxy object disconnected
07-27 10:11:29.611  1375  1387 D BluetoothHeadset: Proxy object disconnected
07-27 10:11:29.611  2529  2529 V BluetoothAdapterState: isTurningOff()=true
07-27 10:11:29.611  2529  2529 V BluetoothAdapterState: isTurningOn()=false
07-27 10:11:29.611  1375  1375 D HeadsetProfile: Bluetooth service disconnected
07-27 10:11:29.611  2529  2529 V BluetoothAdapterState: isBleTurningOn()=false
07-27 10:11:29.611  2529  2529 V BluetoothAdapterState: isBleTurningOff()=false
07-27 10:11:29.611   871   871 D BluetoothHeadset: Proxy object disconnected
07-27 10:11:29.613  2529  2529 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-27 10:11:29.613  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 10:11:29.613  2529  2554 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-27 10:11:29.613  2529  2529 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-27 10:11:29.613  2529  2645 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-27 10:11:29.613  2529  2645 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-27 10:11:29.613  2529  2645 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-27 10:11:29.613  2529  2554 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
07-27 10:11:29.615  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-27 10:11:29.615  2529  2529 D A2dpService: Received stop request...Stopping profile...
07-27 10:11:29.616  2529  2669 D A2dpStateMachine: Exit Disconnected: -1
07-27 10:11:29.617  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 10:11:29.617  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 10:11:29.617  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:29.617  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:29.617  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 10:11:29.617  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 10:11:29.617  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 10:11:29.617  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 10:11:29.617  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 10:11:29.618  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 10:11:29.618  3717  3717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 10:11:29.618  1375  1375 D BluetoothA2dp: Proxy object disconnected
07-27 10:11:29.618   871   871 D BluetoothA2dp: Proxy object disconnected
07-27 10:11:29.619   871  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,07-27 10:11:29.620  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:29.620  2529  2529 D HidService: Received stop request...Stopping profile...
07-27 10:11:29.620  2529  2529 D HidService: Stopping Bluetooth HidService
07-27 10:11:29.621   871  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
07-27 10:11:29.621   871  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-27 10:11:29.621   871  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 10:11:29.622  2529  2529 D HealthService: Received stop request...Stopping profile...
07-27 10:11:29.622  1375  1375 D BluetoothInputDevice: Proxy object disconnected,
07-27 10:11:29.622  1375  1375 D HidProfile: Bluetooth service disconnected
07-27 10:11:29.623  2529  2529 V BluetoothAdapterState: isTurningOff()=true
07-27 10:11:29.623  2529  2529 V BluetoothAdapterState: isTurningOn()=false
07-27 10:11:29.624  2529  2529 V BluetoothAdapterState: isBleTurningOn()=false
07-27 10:11:29.624  2529  2529 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 10:11:29.624  2529  2645 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-27 10:11:29.624  2529  2645 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-27 10:11:29.625  2529  2645 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 10:11:29.625  2529  2645 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 10:11:29.625  2529  2645 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,07-27 10:11:29.625  2529  2645 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 10:11:29.625  2529  2554 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-27 10:11:29.626  2529  2529 D PanService: Received stop request...Stopping profile...
,07-27 10:11:29.627  1375  1375 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-27 10:11:29.627  1375  1375 D PanProfile: Bluetooth service disconnected
07-27 10:11:29.627  2529  2529 V BluetoothAdapterState: isTurningOff()=true
07-27 10:11:29.627  2529  2529 V BluetoothAdapterState: isTurningOn()=false
07-27 10:11:29.627  2529  2529 V BluetoothAdapterState: isBleTurningOn()=false
,07-27 10:11:29.627  2529  2529 V BluetoothAdapterState: isBleTurningOff()=false
07-27 10:11:29.628  2529  2529 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-27 10:11:29.628  2529  2554 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-27 10:11:29.628  2529  2529 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-27 10:11:29.628  2529  2529 V BluetoothAdapterState: isTurningOff()=true
07-27 10:11:29.628  2529  2529 V BluetoothAdapterState: isTurningOn()=false
07-27 10:11:29.628  2529  2529 V BluetoothAdapterState: isBleTurningOn()=false
07-27 10:11:29.629  2529  2529 V BluetoothAdapterState: isBleTurningOff()=false
07-27 10:11:29.629  2529  2529 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,07-27 10:11:29.629  2529  2554 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-27 10:11:29.629   871  1316 E native  : do suspend true
07-27 10:11:29.629  2529  2529 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-27 10:11:29.630  2529  2529 D BluetoothMapService: Received stop request...Stopping profile...
07-27 10:11:29.630  2529  2529 D BluetoothMapService: stop()
07-27 10:11:29.630  2529  2529 D BluetoothMapAppObserver: deinitObservers()
07-27 10:11:29.630  2529  2529 D BluetoothMapAppObserver: removeReceiver()
,07-27 10:11:29.631  1375  1375 D BluetoothMap: Proxy object disconnected
07-27 10:11:29.631  1375  1375 D MapProfile: Bluetooth service disconnected
07-27 10:11:29.632  2529  2529 V BluetoothAdapterState: isTurningOff()=true
07-27 10:11:29.632  2529  2529 V BluetoothAdapterState: isTurningOn()=false
07-27 10:11:29.632  2529  2529 V BluetoothAdapterState: isBleTurningOn()=false
,07-27 10:11:29.632  2529  2529 V BluetoothAdapterState: isBleTurningOff()=false
07-27 10:11:29.632  2529  2529 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-27 10:11:29.632  2529  2529 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-27 10:11:29.633  2529  2529 D BluetoothMapService: MAP Service closeService in
07-27 10:11:29.633  2529  2529 D BluetoothMapMasInstance0: MAP Service shutdown
07-27 10:11:29.633  2529  2529 D ObexServerSockets0: shutdown(block = true)
07-27 10:11:29.633  2529  2682 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4,
07-27 10:11:29.634  2529  2529 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-27 10:11:29.634  2529  2662 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-27 10:11:29.634  2529  2683 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-27 10:11:29.634  2529  2529 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-27 10:11:29.634  2529  2529 V BluetoothAdapterState: isTurningOff()=true
07-27 10:11:29.635  2529  2529 V BluetoothAdapterState: isTurningOn()=false
07-27 10:11:29.635  2529  2529 V BluetoothAdapterState: isBleTurningOn()=false
07-27 10:11:29.635  2529  2529 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 10:11:29.635  2529  2529 D BluetoothMapService: cleanup()
07-27 10:11:29.635  2529  2529 D BluetoothMapService: MAP Service closeService in
07-27 10:11:29.635  2529  2549 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-27 10:11:29.635  2529  2549 D BluetoothAdapterProperties: Setting state to 15
07-27 10:11:29.635  2529  2549 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-27 10:11:29.636  2529  2549 I BluetoothAdapterState: Entering BleOnState
,07-27 10:11:29.640   371   869 D CommandListener: Clearing all IP addresses on wlan0
,07-27 10:11:29.640   871  1973 D DhcpClient: Clearing IP address
,07-27 10:11:29.643   371   869 D CommandListener: Setting iface cfg
,07-27 10:11:29.645  1518  2309 V NativeCrypto: Read error: ssl=0x9ad50c00: I/O error during system call, Connection timed out
,07-27 10:11:29.649  1518  2309 V NativeCrypto: SSL shutdown failed: ssl=0x9ad50c00: I/O error during system call, Broken pipe
,07-27 10:11:29.651   871  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-27 10:11:29.651   871  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
07-27 10:11:29.652   394   394 E Parcel  : Reading a NULL string not supported here.
07-27 10:11:29.655   871  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,07-27 10:11:29.657   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-27 10:11:29.657   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 10:11:29.658  1375  2032 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-27 10:11:29.659  2529  2529 I BtOppRfcommListener: stopping Accept Thread
07-27 10:11:29.659  2529  3271 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 10:11:29.652   871  1316 D WifiStateMachine: Start Disconnecting Watchdog 1
07-27 10:11:29.660  2529  3271 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-27 10:11:29.660   871  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-27 10:11:29.660   871  1316 E native  : do suspend true
,07-27 10:11:29.661  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 10:11:29.661  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 10:11:29.661  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:29.661  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:29.661  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 10:11:29.661  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 10:11:29.661  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 10:11:29.661  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 10:11:29.661  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 10:11:29.662  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-27 10:11:29.662  3717  3717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 10:11:29.662   871  1990 D DhcpClient: Receive thread stopped
,07-27 10:11:29.664  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 10:11:29.664  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 10:11:29.664  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:29.664  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:29.664  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 10:11:29.664  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 10:11:29.664  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 10:11:29.664  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 10:11:29.664  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 10:11:29.664  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 10:11:29.664  3717  3717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 10:11:29.671   871   884 I ActivityManager: Start proc 3856:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,07-27 10:11:29.672  1375  1387 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-27 10:11:29.672  1375  1385 D BluetoothMap: onBluetoothStateChange: up=false
07-27 10:11:29.673   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 10:11:29.673  1375  3716 D BluetoothPan: onBluetoothStateChange on: false
07-27 10:11:29.673  1375  2032 D BluetoothA2dp: onBluetoothStateChange: up=false
07-27 10:11:29.674  1375  1387 D BluetoothPbap: onBluetoothStateChange: up=false
07-27 10:11:29.676  1737  1751 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 10:11:29.676   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 10:11:29.676  2529  2549 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-27 10:11:29.676  2529  2549 D BluetoothAdapterProperties: Setting state to 16,
07-27 10:11:29.676  2529  2549 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-27 10:11:29.677  2529  2549 D BluetoothAdapterProperties: onBleDisable
07-27 10:11:29.677  2529  2549 I BluetoothAdapterState: Entering PendingCommandState
07-27 10:11:29.677  2529  2551 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-27 10:11:29.678  2529  2554 D BluetoothAdapterProperties: Scan Mode:20
07-27 10:11:29.680  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 10:11:29.681  2529  2645 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-27 10:11:29.681  2529  2645 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-27 10:11:29.681  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:29.682  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 10:11:29.683  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:29.699   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-27 10:11:29.712  3856  3856 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,07-27 10:11:29.721  3856  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-27 10:11:29.721   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-27 10:11:29.722   371   869 D CommandListener: Clearing all IP addresses on wlan0
,07-27 10:11:29.722   871  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-27 10:11:29.722   871  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 10:11:29.724   871   888 D Tethering: MasterInitialState.processMessage what=3
,07-27 10:11:29.727  3259  3259 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@e7da1e5 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,07-27 10:11:29.728  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:29.730  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:29.731   871  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-27 10:11:29.735  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-27 10:11:29.739   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@af4a59e:true
,07-27 10:11:29.749   871   882 I ActivityManager: Start proc 3874:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,07-27 10:11:29.751   871  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,07-27 10:11:29.753  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-27 10:11:29.753  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 10:11:29.753  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:29.753  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:29.753  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 10:11:29.753  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 10:11:29.753  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 10:11:29.753  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 10:11:29.753  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 10:11:29.754  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 10:11:29.754  3717  3717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 10:11:29.755   871  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-27 10:11:29.755  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 10:11:29.755  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 10:11:29.755  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:29.755  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:29.755  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 10:11:29.755  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 10:11:29.755  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 10:11:29.755  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 10:11:29.755  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 10:11:29.756  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 10:11:29.756  3717  3717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 10:11:29.757  1974  2156 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 10:11:29.766  3856  3856 D LocalBluetoothProfileManager: Adding local MAP profile
07-27 10:11:29.768  3856  3856 D BluetoothMap: Create BluetoothMap proxy object
,07-27 10:11:29.784  3856  3856 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-27 10:11:29.784   371   869 E Netd    : netlink response contains error (No such file or directory)
,07-27 10:11:29.785   871  1318 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,07-27 10:11:29.796  3874  3874 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,07-27 10:11:29.799  3856  3856 D DockEventReceiver: finishStartingService: stopping service
,07-27 10:11:29.804   871  1759 I ActivityManager: Killing 3259:com.google.android.music:main/u0a66 (adj 15): empty #17
,07-27 10:11:29.884  2529  2554 I bt_hci  : shut_down
,07-27 10:11:29.885  2529  2558 D bt_hwcfg: hw_epilog_process
,07-27 10:11:29.886  2529  2558 I bt_vendor: low_power_mode_cb
,07-27 10:11:29.906  2529  2558 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
07-27 10:11:29.906  2529  2558 I bt_vendor: epilog_cb
07-27 10:11:29.907  2529  2558 I bt_hci  : epilog_finished_callback
,07-27 10:11:29.916  2529  2554 I bt_hci_h4: hal_close
,07-27 10:11:29.917  2529  2554 I bt_userial_vendor: device fd = 51 close
,07-27 10:11:29.981  3874  3874 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at java.io.File.exists(File.java:361)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 10:11:29.981  3874  3874 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 10:11:29.981  3874  3874 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread.main(Act,ivityThread.java:5417)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 10:11:29.981  3874  3874 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.r.e.b(PG:170)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 10:11:29.981  3874  3874 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.r.k.d(PG:583)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.r.e.b(PG:170)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 10:11:29.981  3874  3874 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at java.io.File.exists(File.java:361)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 10:11:29.981  3874  3874 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at java.io.File.exists(File.java:361)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 10:11:29.981  3874  3874 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 10:11:29.982  3874  3874 D StrictMode: StrictMode policy violation; ~duration=57 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 10:11:29.982  3874  3874 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 10:11:29.982  3874  3874 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-27 10:11:29.982  3874  3874 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-27 10:11:29.982  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-27 10:11:29.982  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 10:11:29.982  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 10:11:29.982  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 10:11:29.982  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 10:11:29.982  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 10:11:29.982  3874  3874 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 10:11:29.982  3874  3874 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 10:11:29.982  3874  3874 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 10:11:29.982  3874  3874 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 10:11:29.982  3874  3874 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 10:11:29.982  3874  3874 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 10:11:29.982  3874  3874 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 10:11:29.982  3874  3874 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 10:11:29.982  3874  3874 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 10:11:29.982  3874  3874 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 10:11:29.982  3874  3874 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 10:11:29.993  3856  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-27 10:11:30.006  3856  3856 D DockEventReceiver: finishStartingService: stopping service
,07-27 10:11:30.015   871  1825 I ActivityManager: Killing 3306:com.android.providers.calendar/u0a3 (adj 15): empty #17
,07-27 10:11:30.061  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-27 10:11:30.086  2529  2551 D bt_stack_manager: event_shut_down_stack finished.
,07-27 10:11:30.086  2529  2549 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-27 10:11:30.089  1985  1985 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,07-27 10:11:30.090  2529  2549 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,07-27 10:11:30.090  2529  2529 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-27 10:11:30.091  2529  2529 D BtGatt.GattService: Received stop request...Stopping profile...
07-27 10:11:30.091  2529  2529 D BtGatt.GattService: stop()
07-27 10:11:30.091  2529  2529 D BtGatt.AdvertiseManager: advertise clients cleared
,07-27 10:11:30.093  2529  2529 V BluetoothAdapterState: isTurningOff()=false
,07-27 10:11:30.093  2529  2529 V BluetoothAdapterState: isTurningOn()=false
07-27 10:11:30.093  2529  2529 V BluetoothAdapterState: isBleTurningOn()=false
07-27 10:11:30.093  2529  2529 V BluetoothAdapterState: isBleTurningOff()=true
07-27 10:11:30.093  2529  2549 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-27 10:11:30.094  2529  2549 D BluetoothAdapterProperties: Setting state to 10
,07-27 10:11:30.094  2529  2549 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-27 10:11:30.099  2529  2549 I BluetoothAdapterState: Entering OffState
07-27 10:11:30.102   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,07-27 10:11:30.105  1985  1985 D SystemUpdateService: onCreate
,07-27 10:11:30.117  2529  2529 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-27 10:11:30.117  2529  2529 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-27 10:11:30.117  2529  2529 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-27 10:11:30.118  2529  2551 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-27 10:11:30.119  2529  2551 D bt_stack_manager: event_clean_up_stack finished.
,07-27 10:11:30.126  1985  1985 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-27 10:11:30.133  2529  2529 I art     : System.exit called, status: 0
,07-27 10:11:30.133  2529  2529 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-27 10:11:30.136  1985  1985 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-27 10:11:30.138  1985  2342 I iu.UploadsManager: num queued entries: 0
,07-27 10:11:30.138  1985  2342 I iu.UploadsManager: num updated entries: 0
,07-27 10:11:30.138  1985  2342 I iu.SyncManager: NEXT; no task
,07-27 10:11:30.143  1985  1985 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-27 10:11:30.145  1985  1985 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-27 10:11:30.153  1985  3908 I SystemUpdateService: active receiver: enabled
,07-27 10:11:30.161  1985  3908 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-27 10:11:30.163  1985  3908 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,07-27 10:11:30.163  1985  3908 I SystemUpdateService: now status is 0 (complete)
,07-27 10:11:30.163  1985  3908 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,07-27 10:11:30.163  1985  3908 I SystemUpdateService: file has been verified
,07-27 10:11:30.163  1985  3908 I SystemUpdateService: OTA package size = 12249756
,07-27 10:11:30.168   871  1759 I ActivityManager: Start proc 3910:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver,
,07-27 10:11:30.170  1985  3908 I SystemUpdateService: showing system update notification
,07-27 10:11:30.174   871  1759 I ActivityManager: Process com.android.bluetooth (pid 2529) has died
,07-27 10:11:30.205  1985  1985 D SystemUpdateService: onDestroy
,07-27 10:11:30.243  3910  3910 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,07-27 10:11:30.245  3910  3910 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-27 10:11:30.263  3910  3910 D SprintDMHelper: simOperator: 
,07-27 10:11:30.263  3910  3910 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-27 10:11:30.294   871   882 I ActivityManager: Start proc 3923:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,07-27 10:11:30.295   871   882 I ActivityManager: Killing 1684:android.process.acore/u0a5 (adj 15): empty #17
,07-27 10:11:30.316  3874  3894 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-27 10:11:30.335   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@feacbbd:true
,07-27 10:11:30.450  3340  3938 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,07-27 10:11:30.490   871  1402 I ActivityManager: Start proc 3939:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-27 10:11:30.525  3939  3939 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,07-27 10:11:30.581  3939  3939 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-27 10:11:30.581  3939  3939 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-27 10:11:30.581  3939  3939 I GAv4    :   adb logcat -s GAv4
,07-27 10:11:30.597  3939  3939 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-27 10:11:30.603  3939  3939 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-27 10:11:30.629  3939  3956 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-27 10:11:30.746  3939  3939 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,07-27 10:11:30.784  3939  3939 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-27 10:11:30.791  3939  3939 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1373-1375)
07-27 10:11:30.792  3939  3939 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-27 10:11:30.803  3939  3939 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5f3ce55}
,07-27 10:11:30.804  3939  3939 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 10:11:30.804  3939  3939 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-27 10:11:30.816  3939  3939 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-27 10:11:30.817  3939  3939 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-27 10:11:30.835  3939  3939 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-27 10:11:30.850  3939  3939 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-27 10:11:30.850  3939  3939 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-27 10:11:30.850  3939  3939 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-27 10:11:30.850  3939  3939 I Adreno  : Build Date                       : 10/20/15
07-27 10:11:30.850  3939  3939 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-27 10:11:30.850  3939  3939 I Adreno  : Local Branch                     : M14
07-27 10:11:30.850  3939  3939 I Adreno  : Remote Branch                    : 
07-27 10:11:30.850  3939  3939 I Adreno  : Remote Branch                    : 
07-27 10:11:30.850  3939  3939 I Adreno  : Reconstruct Branch               : 
,07-27 10:11:30.919  3939  3939 I NSApplication: Starting up...
07-27 10:11:30.919  3939  3985 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-27 10:11:30.965   871   881 I ActivityManager: Start proc 3990:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-27 10:11:30.967   871   881 I ActivityManager: Killing 3546:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,07-27 10:11:31.072  3990  3990 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-27 10:11:31.288   871   882 I ActivityManager: Killing 3563:com.android.musicfx/u0a18 (adj 15): empty #17
,07-27 10:11:31.351   871  1759 I ActivityManager: Start proc 4004:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,07-27 10:11:31.442  4004  4004 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,07-27 10:11:31.496  4004  4004 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-27 10:11:31.513   871  1373 I ActivityManager: Killing 2105:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,07-27 10:11:32.610   871  1373 D WifiService: setWifiEnabled: true pid=3717, uid=10000
,07-27 10:11:32.610   871  1373 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-27 10:11:32.624   871  1316 D WifiConfigStore: Loading config and enabling all networks 
,07-27 10:11:32.631  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-27 10:11:32.631  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 10:11:32.631  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:32.631  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:32.631  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 10:11:32.631  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 10:11:32.631  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 10:11:32.631  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 10:11:32.631  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 10:11:32.631  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-27 10:11:32.632  3717  3717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 10:11:32.635  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-27 10:11:32.635  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 10:11:32.635  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:32.635  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:32.635  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 10:11:32.635  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 10:11:32.635  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 10:11:32.635  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 10:11:32.635  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 10:11:32.636  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-27 10:11:32.636  3717  3717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 10:11:32.672   871  1316 D WifiConfigStore: loaded 0 passpoint configs
,07-27 10:11:32.672   871  1316 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-27 10:11:32.673   871  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,07-27 10:11:32.673   871  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-27 10:11:32.674   871  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,07-27 10:11:32.675   871  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,07-27 10:11:32.675   871  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-27 10:11:32.675   871  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-27 10:11:32.688   371   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,07-27 10:11:32.689   871  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-27 10:11:32.690   371   869 D CommandListener: Setting iface cfg
,07-27 10:11:32.691   871  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)',
,07-27 10:11:32.691   871  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-27 10:11:32.703   871  1316 E native  : do suspend true
,07-27 10:11:32.703   871  1314 D WifiNative-HAL: p2pGetDeviceAddress
,07-27 10:11:32.713   871  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,07-27 10:11:32.724   871  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,07-27 10:11:34.014   871  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-27 10:11:34.105   871  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.38 rxSuccessRate=13.12 delta 1000 -> 994
,07-27 10:11:34.107   871  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
07-27 10:11:34.107   871  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 10:11:34.129   871  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-27 10:11:34.186   871  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-27 10:11:34.190  1469  1469 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-27 10:11:34.607  1469  1469 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-27 10:11:34.643  1469  1469 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 10:11:34.643  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,07-27 10:11:34.647   871  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,07-27 10:11:34.653   871  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-27 10:11:34.653   871  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 10:11:34.654   871  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-27 10:11:34.671   871  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 10:11:34.682   371   869 D CommandListener: Setting iface cfg
,07-27 10:11:34.683   871  1316 D WifiStateMachine: Start Dhcp Watchdog 2
,07-27 10:11:34.691   871  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,07-27 10:11:34.708   871  4039 D DhcpClient: Receive thread started
,07-27 10:11:34.791   871  1316 E native  : do suspend false
,07-27 10:11:34.803   871  1973 D DhcpClient: Broadcasting DHCPDISCOVER
,07-27 10:11:34.815   871  4039 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172498, domain null
,07-27 10:11:34.816   871  1973 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172498 seconds
,07-27 10:11:34.819   871  1973 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,07-27 10:11:34.833   871  4039 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-27 10:11:34.834   871  1973 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-27 10:11:34.839   371   869 D CommandListener: Setting iface cfg
,07-27 10:11:34.846   871  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,07-27 10:11:34.850   871  1316 E native  : do suspend true
,07-27 10:11:34.853   871  1973 D DhcpClient: Scheduling renewal in 86399s
,07-27 10:11:34.874   871  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-27 10:11:34.881   871  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,07-27 10:11:34.884   871  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,07-27 10:11:34.888   871  1318 D ConnectivityService: Adding iface wlan0 to network 101
,07-27 10:11:34.897   871  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-27 10:11:34.943   871  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-27 10:11:34.943   871  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,07-27 10:11:34.944   871  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,07-27 10:11:34.945   871  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,07-27 10:11:34.946   871  1318 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,07-27 10:11:34.953   871  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-27 10:11:34.958   871  1318 D ConnectivityService: scheduleUnvalidatedPrompt 101
,07-27 10:11:34.958   871  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
07-27 10:11:34.959   871  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,07-27 10:11:34.959   871  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-27 10:11:34.959   871  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,07-27 10:11:34.959   871  1318 D ConnectivityService:    accepting network in place of null
,07-27 10:11:34.961   871  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-27 10:11:34.970   871  4038 D NetlinkSocketObserver: NeighborEvent{elapsedMs=325554, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-27 10:11:34.986   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-27 10:11:35.011   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-27 10:11:35.019   871  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,07-27 10:11:35.022   871  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 10:11:35.026   871  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,07-27 10:11:35.027   871   888 D Tethering: MasterInitialState.processMessage what=3
,07-27 10:11:35.040   871  4037 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:811::200e
,07-27 10:11:35.041  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 10:11:35.041  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 10:11:35.041  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:35.041  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:35.041  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 10:11:35.041  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 10:11:35.041  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 10:11:35.041  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 10:11:35.041  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 10:11:35.041  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 10:11:35.041  3717  3717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 10:11:35.049  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-27 10:11:35.050  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 10:11:35.050  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:35.050  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:35.050  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 10:11:35.050  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 10:11:35.050  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 10:11:35.050  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 10:11:35.050  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 10:11:35.050  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-27 10:11:35.050  3717  3717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 10:11:35.058  1985  1985 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,07-27 10:11:35.061  1985  1985 D SystemUpdateService: onCreate
,07-27 10:11:35.064  1985  1985 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-27 10:11:35.069  1985  4050 I SystemUpdateService: active receiver: enabled
,07-27 10:11:35.076  1985  4050 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-27 10:11:35.080  1985  4050 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,07-27 10:11:35.080  1985  4050 I SystemUpdateService: now status is 0 (complete)
07-27 10:11:35.080  1985  4050 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
07-27 10:11:35.080  1985  4050 I SystemUpdateService: file has been verified
07-27 10:11:35.080  1985  4050 I SystemUpdateService: OTA package size = 12249756
,07-27 10:11:35.085  1985  4050 I SystemUpdateService: showing system update notification
,07-27 10:11:35.091  1985  1985 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-27 10:11:35.093  1985  2342 I iu.UploadsManager: num queued entries: 0
,07-27 10:11:35.093  1985  2342 I iu.UploadsManager: num updated entries: 0
07-27 10:11:35.094  1985  2342 I iu.SyncManager: NEXT; no task
,07-27 10:11:35.099  1985  1985 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-27 10:11:35.100  1985  4054 I MDM     : [219] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
07-27 10:11:35.100  1985  4054 W BaseAppContext: Using Auth Proxy for data requests.
07-27 10:11:35.100  1985  1985 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-27 10:11:35.102  1985  4054 V GoogleAuthProtoRequest: [219] a.<init>: mAccountName set to: thalitester@gmail.com
07-27 10:11:35.103  1985  1985 D SystemUpdateService: onDestroy
07-27 10:11:35.104  3910  3910 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-27 10:11:35.108  3910  3910 D SprintDMHelper: simOperator: 
,07-27 10:11:35.108  3910  3910 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-27 10:11:35.111  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:11:35.114   871  4037 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jul 2016 08:11:35 GMT], X-Android-Received-Millis=[1469607095113], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1469607095084]}
,07-27 10:11:35.114  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-27 10:11:35.115   871  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-27 10:11:35.115   871  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,07-27 10:11:35.115   871  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-27 10:11:35.117   871  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-27 10:11:35.156  1518  1950 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,07-27 10:11:35.156  1518  1950 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
07-27 10:11:35.157  1518  1950 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:11:35.157  1518  1950 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:11:35.176  1985  4054 E MDM     : [219] SitrepService.a: Error sending sitrep.
,07-27 10:11:35.232  3340  4057 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-27 10:11:35.471   871  3634 I ActivityManager: Killing 3586:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,07-27 10:11:35.617   871  1759 D WifiService: setWifiEnabled: false pid=3717, uid=10000
,07-27 10:11:35.617   871  1759 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-27 10:11:35.632  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-27 10:11:35.633   871  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
07-27 10:11:35.633   871  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
07-27 10:11:35.633   871  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-27 10:11:35.633   871  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 10:11:35.645   871  1316 E native  : do suspend true
,07-27 10:11:35.654   871  1973 D DhcpClient: Clearing IP address
,07-27 10:11:35.654   371   869 D CommandListener: Clearing all IP addresses on wlan0
,07-27 10:11:35.658   371   869 D CommandListener: Setting iface cfg
,07-27 10:11:35.669  1518  4061 V NativeCrypto: Read error: ssl=0x9a6ff400: I/O error during system call, Connection timed out
,07-27 10:11:35.671   871  1316 D WifiStateMachine: Start Disconnecting Watchdog 2
07-27 10:11:35.671   871  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,07-27 10:11:35.672   871  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
07-27 10:11:35.672   871  4039 D DhcpClient: Receive thread stopped
07-27 10:11:35.673   871  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-27 10:11:35.673   871  1316 E native  : do suspend true
,07-27 10:11:35.674  1518  4061 V NativeCrypto: SSL shutdown failed: ssl=0x9a6ff400: I/O error during system call, Broken pipe
07-27 10:11:35.680   394   394 E Parcel  : Reading a NULL string not supported here.
,07-27 10:11:35.691   871  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,07-27 10:11:35.691   371   869 D CommandListener: Clearing all IP addresses on wlan0
,07-27 10:11:35.694   871  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-27 10:11:35.713   871  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,07-27 10:11:35.715  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-27 10:11:35.715  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 10:11:35.715  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:35.715  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:35.715  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 10:11:35.715  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 10:11:35.715  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 10:11:35.715  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 10:11:35.715  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 10:11:35.715  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 10:11:35.715  3717  3717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 10:11:35.716  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-27 10:11:35.716  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 10:11:35.716  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:35.716  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:35.716  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 10:11:35.716  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 10:11:35.716  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 10:11:35.716  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 10:11:35.716  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 10:11:35.716  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-27 10:11:35.716  3717  3717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 10:11:35.717  1974  2156 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
07-27 10:11:35.718   871  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-27 10:11:35.724   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-27 10:11:35.753   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-27 10:11:35.754   871  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-27 10:11:35.754   871  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-27 10:11:35.755   871   888 D Tethering: MasterInitialState.processMessage what=3
,07-27 10:11:35.760  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:35.760  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 10:11:35.768  1985  1985 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) },
,07-27 10:11:35.771  1985  1985 D SystemUpdateService: onCreate
,07-27 10:11:35.773  1985  1985 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-27 10:11:35.780  1985  4070 I SystemUpdateService: active receiver: enabled
,07-27 10:11:35.783  1985  1985 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-27 10:11:35.785  1985  2342 I iu.UploadsManager: num queued entries: 0
,07-27 10:11:35.790  1985  4070 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-27 10:11:35.792  1985  1985 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-27 10:11:35.793  1985  1985 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-27 10:11:35.795  3910  3910 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-27 10:11:35.798  3910  3910 D SprintDMHelper: simOperator: 
07-27 10:11:35.798  3910  3910 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-27 10:11:35.827  1985  2342 I iu.UploadsManager: num updated entries: 0
,07-27 10:11:35.831  3340  4074 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,07-27 10:11:35.836   371   869 E Netd    : netlink response contains error (No such file or directory)
,07-27 10:11:35.837  1985  4070 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,07-27 10:11:35.837  1985  4070 I SystemUpdateService: now status is 0 (complete)
,07-27 10:11:35.838  1985  4070 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,07-27 10:11:35.838  1985  4070 I SystemUpdateService: file has been verified
,07-27 10:11:35.838  1985  4070 I SystemUpdateService: OTA package size = 12249756
,07-27 10:11:35.838  1985  2342 I iu.SyncManager: NEXT; no task
,07-27 10:11:35.849  1985  4070 I SystemUpdateService: showing system update notification
,07-27 10:11:35.856  1985  1985 D SystemUpdateService: onDestroy
,07-27 10:11:36.018   871  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,07-27 10:11:38.672   871   888 I ActivityManager: Start proc 4077:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-27 10:11:38.801  4077  4077 D AdapterServiceConfig: Adding HeadsetService
,07-27 10:11:38.802  4077  4077 D AdapterServiceConfig: Adding A2dpService
,07-27 10:11:38.802  4077  4077 D AdapterServiceConfig: Adding HidService
,07-27 10:11:38.802  4077  4077 D AdapterServiceConfig: Adding HealthService
,07-27 10:11:38.802  4077  4077 D AdapterServiceConfig: Adding PanService
,07-27 10:11:38.802  4077  4077 D AdapterServiceConfig: Adding GattService
,07-27 10:11:38.803  4077  4077 D AdapterServiceConfig: Adding BluetoothMapService
,07-27 10:11:38.818  4077  4077 D BluetoothAdapterState: make() - Creating AdapterState
,07-27 10:11:38.818   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@da34ba0:true
,07-27 10:11:38.822  4077  4077 I bt_bluedroid: init
,07-27 10:11:38.823  4077  4089 I BluetoothAdapterState: Entering OffState
,07-27 10:11:38.825  4077  4090 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-27 10:11:38.825  4077  4090 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,07-27 10:11:38.825  4077  4090 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-27 10:11:38.825  4077  4090 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-27 10:11:38.826  4077  4077 I bt_bluedroid: get_profile_interface socket
,07-27 10:11:38.828  4077  4077 I bt_bluedroid: get_profile_interface sdp
,07-27 10:11:38.832  4077  4088 I bt_bluedroid: config_hci_snoop_log
,07-27 10:11:38.833   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
07-27 10:11:38.834  4077  4093 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-27 10:11:38.843  4077  4093 D BluetoothAdapterProperties: Name is: Nexus 6
,07-27 10:11:38.844  4077  4089 D BluetoothAdapterState: Current state: OFF, message: 0
,07-27 10:11:38.845  4077  4089 D BluetoothAdapterProperties: Setting state to 14
07-27 10:11:38.845  4077  4089 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-27 10:11:38.847  4077  4089 D BluetoothBondStateMachine: make
,07-27 10:11:38.849  4077  4094 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-27 10:11:38.851  4077  4089 I BluetoothAdapterState: Entering PendingCommandState
,07-27 10:11:38.852  4077  4077 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-27 10:11:38.855  4077  4077 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d788d33
,07-27 10:11:38.855  4077  4077 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-27 10:11:38.856  4077  4077 D BtGatt.GattService: Received start request. Starting profile...
,07-27 10:11:38.856  4077  4077 D BtGatt.GattService: start()
07-27 10:11:38.856  4077  4077 I bt_bluedroid: get_profile_interface gatt
,07-27 10:11:38.857  4077  4077 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d788d33
07-27 10:11:38.857  4077  4077 D BtGatt.AdvertiseManager: advertise manager created
,07-27 10:11:38.862  4077  4077 V BluetoothAdapterState: isTurningOff()=false
,07-27 10:11:38.862  4077  4077 V BluetoothAdapterState: isTurningOn()=false
07-27 10:11:38.862  4077  4077 V BluetoothAdapterState: isBleTurningOn()=true
07-27 10:11:38.862  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
07-27 10:11:38.862  4077  4089 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-27 10:11:38.863  4077  4089 I bt_bluedroid: enable
07-27 10:11:38.863  4077  4090 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-27 10:11:38.863  4077  4090 I bt_hci  : start_up
,07-27 10:11:38.869  4077  4090 I bt_vendor: alloc value 0xb3a40189
,07-27 10:11:38.869  4077  4090 I bt_vendor: init
07-27 10:11:38.869  4077  4090 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-27 10:11:38.869  4077  4090 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-27 10:11:38.977  4077  4090 D bt_hci  : start_up starting async portion
,07-27 10:11:38.978  4077  4097 I bt_hci  : event_finish_startup
07-27 10:11:38.978  4077  4097 I bt_hci_h4: hal_open
07-27 10:11:38.978  4077  4097 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-27 10:11:38.987  4077  4097 I bt_userial_vendor: device fd = 51 open
,07-27 10:11:39.020  4077  4097 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-27 10:11:39.051  4077  4097 D bt_hwcfg: Chipset BCM4354A2
,07-27 10:11:39.052  4077  4097 D bt_hwcfg: Target name = [BCM4354A2]
,07-27 10:11:39.053  4077  4097 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,07-27 10:11:39.710  4077  4097 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-27 10:11:39.712  4077  4097 D bt_hwcfg: Settlement delay -- 100 ms
,07-27 10:11:39.712  4077  4097 I bt_hwcfg: Setting fw settlement delay to 100 
,07-27 10:11:39.829  4077  4097 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-27 10:11:39.830  4077  4097 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,07-27 10:11:39.859  4077  4097 I bt_hwcfg: vendor lib fwcfg completed
,07-27 10:11:39.859  4077  4097 I bt_vendor: firmware callback
07-27 10:11:39.859  4077  4097 I bt_hci  : firmware_config_callback
,07-27 10:11:39.870  4077  4099 I bt_btu  : btu_task pending for preload complete event
,07-27 10:11:39.871  4077  4099 I bt_btu_task: Bluetooth chip preload is complete
,07-27 10:11:39.871  4077  4099 I bt_btu  : btu_task received preload complete event
,07-27 10:11:39.882  4077  4099 I         : BTE_InitTraceLevels -- TRC_HCI
,07-27 10:11:39.883  4077  4099 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-27 10:11:39.883  4077  4099 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-27 10:11:39.883  4077  4099 I         : BTE_InitTraceLevels -- TRC_AVDT
07-27 10:11:39.883  4077  4099 I         : BTE_InitTraceLevels -- TRC_AVRC
07-27 10:11:39.884  4077  4099 I         : BTE_InitTraceLevels -- TRC_A2D
07-27 10:11:39.884  4077  4099 I         : BTE_InitTraceLevels -- TRC_BNEP
07-27 10:11:39.884  4077  4099 I         : BTE_InitTraceLevels -- TRC_BTM
07-27 10:11:39.884  4077  4099 I         : BTE_InitTraceLevels -- TRC_GAP
07-27 10:11:39.884  4077  4099 I         : BTE_InitTraceLevels -- TRC_PAN
07-27 10:11:39.885  4077  4099 I         : BTE_InitTraceLevels -- TRC_SDP
07-27 10:11:39.885  4077  4099 I         : BTE_InitTraceLevels -- TRC_GATT
07-27 10:11:39.885  4077  4099 I         : BTE_InitTraceLevels -- TRC_SMP
07-27 10:11:39.885  4077  4099 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-27 10:11:39.885  4077  4099 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-27 10:11:40.015  4077  4099 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39bdd9d
07-27 10:11:40.016  4077  4099 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39bdd9d 
07-27 10:11:40.039  4077  4093 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
07-27 10:11:40.040  4077  4093 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-27 10:11:40.041  4077  4093 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-27 10:11:40.045  4077  4093 D BluetoothAdapterProperties: Name is: Nexus 6
,07-27 10:11:40.049  4077  4093 D BluetoothAdapterProperties: Scan Mode:20
07-27 10:11:40.049  4077  4093 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-27 10:11:40.050  4077  4093 D bt_hci  : do_postload posting postload work item
,07-27 10:11:40.050  4077  4097 I bt_hci  : event_postload
,07-27 10:11:40.050  4077  4097 I bt_vendor: sco_config_cb
,07-27 10:11:40.051  4077  4097 I bt_hci  : sco_config_callback postload finished.
,07-27 10:11:40.055  4077  4093 D bt_bte_conf: Device ID record 1 : primary
,07-27 10:11:40.056  4077  4093 D bt_bte_conf:   vendorId            = 000f
,07-27 10:11:40.056  4077  4093 D bt_bte_conf:   vendorIdSource      = 0001
,07-27 10:11:40.056  4077  4093 D bt_bte_conf:   product             = 1200,
,07-27 10:11:40.056  4077  4093 D bt_bte_conf:   version             = 1436
07-27 10:11:40.057  4077  4093 D bt_bte_conf:   clientExecutableURL = 
07-27 10:11:40.057  4077  4093 D bt_bte_conf:   serviceDescription  = 
07-27 10:11:40.057  4077  4093 D bt_bte_conf:   documentationURL    = 
,07-27 10:11:40.058  4077  4093 D bt_bte_conf: bte_load_did_conf no section named DID2.
,07-27 10:11:40.058  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 10:11:40.058  4077  4090 D bt_stack_manager: event_start_up_stack finished
07-27 10:11:40.063  4077  4097 I bt_vendor: low_power_mode_cb
07-27 10:11:40.063  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 10:11:40.064  4077  4089 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-27 10:11:40.065  4077  4089 D BluetoothAdapterProperties: Setting state to 15
07-27 10:11:40.065  4077  4089 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-27 10:11:40.066  4077  4089 I BluetoothAdapterState: Entering BleOnState
07-27 10:11:40.073  4077  4089 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-27 10:11:40.073  4077  4089 D BluetoothAdapterProperties: Setting state to 11
07-27 10:11:40.074  4077  4089 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-27 10:11:40.083  4077  4077 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d788d33
,07-27 10:11:40.084  4077  4077 D HeadsetService: Received start request. Starting profile...
,07-27 10:11:40.088  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:40.091  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:40.097  4077  4077 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-27 10:11:40.097  4077  4077 D HeadsetStateMachine: make
,07-27 10:11:40.103  4077  4089 I BluetoothAdapterState: Entering PendingCommandState
,07-27 10:11:40.108  4077  4077 D HeadsetStateMachine: max_hf_connections = 1
,07-27 10:11:40.108  4077  4077 I bt_bluedroid: get_profile_interface handsfree
,07-27 10:11:40.108  4077  4093 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-27 10:11:40.108  4077  4093 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,07-27 10:11:40.114  4077  4077 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d788d33
,07-27 10:11:40.114  4077  4077 D A2dpService: Received start request. Starting profile...
,07-27 10:11:40.115  4077  4077 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-27 10:11:40.115  4077  4077 I bt_bluedroid: get_profile_interface avrcp
,07-27 10:11:40.122  4077  4077 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-27 10:11:40.122  4077  4077 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-27 10:11:40.123  4077  4077 D A2dpStateMachine: make
,07-27 10:11:40.124  4077  4077 I bt_bluedroid: get_profile_interface a2dp
07-27 10:11:40.124  4077  4093 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-27 10:11:40.127  4077  4108 D A2dpStateMachine: Enter Disconnected: -2
,07-27 10:11:40.129  4077  4077 I BluetoothHidServiceJni: classInitNative: succeeds
,07-27 10:11:40.130  4077  4077 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d788d33
07-27 10:11:40.130  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-27 10:11:40.131  4077  4077 D HidService: Received start request. Starting profile...
07-27 10:11:40.131  3856  3856 D BluetoothInputDevice: Proxy object connected
,07-27 10:11:40.131  4077  4077 I bt_bluedroid: get_profile_interface hidhost
07-27 10:11:40.131  4077  4077 D HidService: setHidService(): set to: null
07-27 10:11:40.132  4077  4093 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb399f3e5
,07-27 10:11:40.132  3856  3856 D HidProfile: Bluetooth service connected
07-27 10:11:40.132  4077  4093 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-27 10:11:40.132  4077  4077 I BluetoothHealthServiceJni: classInitNative: succeeds
07-27 10:11:40.133  4077  4077 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d788d33
07-27 10:11:40.133  4077  4077 D HealthService: Received start request. Starting profile...
,07-27 10:11:40.135  4077  4077 I bt_bluedroid: get_profile_interface health
,07-27 10:11:40.135  4077  4077 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-27 10:11:40.136  4077  4077 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d788d33
,07-27 10:11:40.137  3856  3856 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 10:11:40.137  4077  4077 D PanService: Received start request. Starting profile...
,07-27 10:11:40.138  4077  4077 D BluetoothPanServiceJni: initializeNative(L110): pan
07-27 10:11:40.138  4077  4077 I bt_bluedroid: get_profile_interface pan
07-27 10:11:40.138  3856  3856 D PanProfile: Bluetooth service connected
07-27 10:11:40.138  4077  4093 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-27 10:11:40.141  4077  4077 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d788d33
,07-27 10:11:40.143  4077  4077 D BluetoothMapService: Received start request. Starting profile...
07-27 10:11:40.143  3856  3856 D BluetoothMap: Proxy object connected
07-27 10:11:40.143  4077  4077 D BluetoothMapService: start()
,07-27 10:11:40.143  3856  3856 D MapProfile: Bluetooth service connected
,07-27 10:11:40.144  3856  3856 D BluetoothMap: getConnectedDevices()
07-27 10:11:40.144  3856  3856 D BluetoothMap: Bluetooth is Not enabled
07-27 10:11:40.145  4077  4077 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-27 10:11:40.146  4077  4077 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-27 10:11:40.146  4077  4077 D BluetoothMapAppObserver: createReceiver()
,07-27 10:11:40.147  4077  4077 D BluetoothMapAppObserver: initObservers()
,07-27 10:11:40.147  4077  4077 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-27 10:11:40.155  4077  4077 V BluetoothAdapterState: isTurningOff()=false
,07-27 10:11:40.156  4077  4077 V BluetoothAdapterState: isTurningOn()=true
07-27 10:11:40.156  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
07-27 10:11:40.156  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 10:11:40.157  4077  4077 V BluetoothAdapterState: isTurningOff()=false
,07-27 10:11:40.158  4077  4077 V BluetoothAdapterState: isTurningOn()=true
07-27 10:11:40.158  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
,07-27 10:11:40.158  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
07-27 10:11:40.158  4077  4077 V BluetoothAdapterState: isTurningOff()=false
07-27 10:11:40.158  4077  4106 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-27 10:11:40.158  4077  4077 V BluetoothAdapterState: isTurningOn()=true
,07-27 10:11:40.158  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
07-27 10:11:40.158  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 10:11:40.160  4077  4077 V BluetoothAdapterState: isTurningOff()=false
,07-27 10:11:40.160  4077  4077 V BluetoothAdapterState: isTurningOn()=true
,07-27 10:11:40.160  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
,07-27 10:11:40.160  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 10:11:40.161  4077  4077 V BluetoothAdapterState: isTurningOff()=false
,07-27 10:11:40.161  4077  4077 V BluetoothAdapterState: isTurningOn()=true
,07-27 10:11:40.161  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
07-27 10:11:40.161  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 10:11:40.161  4077  4077 V BluetoothAdapterState: isTurningOff()=false
07-27 10:11:40.161  4077  4077 V BluetoothAdapterState: isTurningOn()=true
,07-27 10:11:40.161  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
,07-27 10:11:40.161  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 10:11:40.162  4077  4089 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-27 10:11:40.162  4077  4089 D BluetoothAdapterProperties: ScanMode =  20
07-27 10:11:40.162  4077  4089 D BluetoothAdapterProperties: State =  11
07-27 10:11:40.162  4077  4089 D BluetoothAdapterProperties: Setting state to 12
,07-27 10:11:40.162  4077  4089 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-27 10:11:40.163  4077  4089 I BluetoothAdapterState: Entering OnState
,07-27 10:11:40.164  3856  3868 D BluetoothMap: onBluetoothStateChange: up=true
07-27 10:11:40.165  3856  3869 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-27 10:11:40.165   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-27 10:11:40.166  4077  4093 D BluetoothAdapterProperties: Scan Mode:21
,07-27 10:11:40.167  4077  4093 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-27 10:11:40.167   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 10:11:40.167  1375  3716 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-27 10:11:40.168   871   871 D BluetoothA2dp: Proxy object connected
07-27 10:11:40.170  1375  1375 D BluetoothInputDevice: Proxy object connected
07-27 10:11:40.170  1375  1387 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 10:11:40.170  1375  1375 D HidProfile: Bluetooth service connected
,07-27 10:11:40.171  1375  1385 D BluetoothMap: onBluetoothStateChange: up=true
,07-27 10:11:40.173  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 10:11:40.173  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:40.173  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:40.173  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 10:11:40.173  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 10:11:40.173  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 10:11:40.173  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 10:11:40.173  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 10:11:40.174  1375  1375 D BluetoothMap: Proxy object connected
,07-27 10:11:40.174  1375  1375 D MapProfile: Bluetooth service connected
07-27 10:11:40.174  1375  1375 D BluetoothMap: getConnectedDevices()
07-27 10:11:40.174   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 10:11:40.174  1375  2032 D BluetoothPan: onBluetoothStateChange on: true
07-27 10:11:40.175  4077  4077 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-27 10:11:40.175  3717  3717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 10:11:40.176  4077  4077 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,07-27 10:11:40.177  1375  1375 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 10:11:40.177  1375  1375 D PanProfile: Bluetooth service connected
07-27 10:11:40.177  1375  3716 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 10:11:40.177  4077  4077 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 10:11:40.179  1375  1375 D BluetoothA2dp: Proxy object connected
07-27 10:11:40.179  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 10:11:40.179  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:40.179  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:40.179  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 10:11:40.179  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 10:11:40.179  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 10:11:40.179  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 10:11:40.179  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 10:11:40.179  1375  1387 D BluetoothPbap: onBluetoothStateChange: up=true
07-27 10:11:40.181  4077  4077 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 10:11:40.181  3856  3866 D BluetoothPbap: onBluetoothStateChange: up=true
,07-27 10:11:40.181  3717  3717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 10:11:40.182  4077  4077 D ObexServerSockets: Succeed to create listening sockets 
07-27 10:11:40.183  4077  4077 D ObexServerSockets0: startAccept()
07-27 10:11:40.183  4077  4077 D ObexServerSockets0: prepareForNewConnect()
07-27 10:11:40.184  1737  1953 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 10:11:40.185  3856  3868 D BluetoothPan: onBluetoothStateChange on: true
07-27 10:11:40.185   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 10:11:40.185  4077  4077 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,07-27 10:11:40.186  4077  4114 D ObexServerSockets0: Accepting socket connection...
07-27 10:11:40.185  4077  4077 D BluetoothSdpJni: SDP Create record success - handle: 0
07-27 10:11:40.187  4077  4115 D ObexServerSockets0: Accepting socket connection...
07-27 10:11:40.187  4077  4077 D BluetoothMapService: onReceive
07-27 10:11:40.187  4077  4077 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-27 10:11:40.187   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
07-27 10:11:40.187  4077  4077 D BluetoothMapService: STATE_ON
07-27 10:11:40.189  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 10:11:40.190  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:40.192  3856  3856 D LocalBluetoothProfileManager: Adding local A2DP profile
07-27 10:11:40.196  3856  3856 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-27 10:11:40.205  3856  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-27 10:11:40.206  3856  3856 D BluetoothA2dp: Proxy object connected
,07-27 10:11:40.210  4077  4077 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-27 10:11:40.210  4077  4077 D ObexServerSockets0: prepareForNewConnect()
,07-27 10:11:40.220  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-27 10:11:40.223  1375  1375 D BluetoothPbap: Proxy object connected
,07-27 10:11:40.223  1375  1375 D PbapServerProfile: Bluetooth service connected
,07-27 10:11:40.227  4077  4118 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 10:11:40.228  3856  3856 D DockEventReceiver: finishStartingService: stopping service
,07-27 10:11:40.228  3856  3856 D BluetoothPbap: Proxy object connected
07-27 10:11:40.229  3856  3856 D PbapServerProfile: Bluetooth service connected
,07-27 10:11:40.266  4077  4124 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 10:11:40.269  1737  1754 D BluetoothHeadset: Proxy object connected
,07-27 10:11:40.269   871   871 D BluetoothHeadset: Proxy object connected
07-27 10:11:40.270   871   871 D BluetoothHeadset: Proxy object connected
,07-27 10:11:40.270  4077  4124 I BtOppRfcommListener: Accept thread started.
,07-27 10:11:40.271  1375  1387 D BluetoothHeadset: Proxy object connected
,07-27 10:11:40.272  1375  2032 D BluetoothHeadset: Proxy object connected
,07-27 10:11:40.272  1375  1375 D HeadsetProfile: Bluetooth service connected
,07-27 10:11:40.272   871   871 D BluetoothHeadset: Proxy object connected
,07-27 10:11:40.274   871   888 D BluetoothHeadset: Proxy object connected
07-27 10:11:40.275  1375  1375 D HeadsetProfile: Bluetooth service connected,
,07-27 10:11:40.285  1737  1862 D BluetoothHeadset: Proxy object connected
07-27 10:11:40.285   871   888 D BluetoothHeadset: Proxy object connected
,07-27 10:11:40.300  3856  3868 D BluetoothHeadset: Proxy object connected
,07-27 10:11:40.301  3856  3856 D HeadsetProfile: Bluetooth service connected
,07-27 10:11:41.633  4077  4089 D BluetoothAdapterState: Current state: ON, message: 23
,07-27 10:11:41.633  4077  4089 D BluetoothAdapterProperties: Setting state to 13
07-27 10:11:41.633  4077  4089 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,07-27 10:11:41.635  4077  4089 D BluetoothAdapterProperties: onBluetoothDisable()
,07-27 10:11:41.644  4077  4077 D BluetoothMapService: onReceive
,07-27 10:11:41.645  4077  4077 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-27 10:11:41.646  4077  4077 D BluetoothMapService: STATE_TURNING_OFF
07-27 10:11:41.646  4077  4077 D BluetoothMapService: MAP Service closeService in
,07-27 10:11:41.647  4077  4077 D BluetoothMapMasInstance0: MAP Service shutdown
07-27 10:11:41.647  4077  4077 D ObexServerSockets0: shutdown(block = true)
07-27 10:11:41.648  4077  4114 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-27 10:11:41.645  4077  4089 I BluetoothAdapterState: Entering PendingCommandState
07-27 10:11:41.652  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-27 10:11:41.652  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 10:11:41.652  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:41.652  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:41.652  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 10:11:41.652  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 10:11:41.652  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 10:11:41.652  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 10:11:41.652  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 10:11:41.655  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-27 10:11:41.655  3717  3717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 10:11:41.656  4077  4077 D ObexServerSockets0: shutdown called from another thread - interrupt().
,07-27 10:11:41.657  4077  4115 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-27 10:11:41.658  4077  4093 D BluetoothAdapterProperties: Scan Mode:20
07-27 10:11:41.658  4077  4089 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-27 10:11:41.659  4077  4101 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-27 10:11:41.660  4077  4077 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-27 10:11:41.661  4077  4077 I BtOppRfcommListener: stopping Accept Thread
07-27 10:11:41.663  4077  4124 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 10:11:41.663  4077  4124 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-27 10:11:41.665  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 10:11:41.665  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 10:11:41.665  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:41.665  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:41.665  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 10:11:41.665  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 10:11:41.665  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 10:11:41.665  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 10:11:41.665  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 10:11:41.667  3717  3717 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-27 10:11:41.667  3717  3717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 10:11:41.667  3856  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-27 10:11:41.668  4077  4077 D HeadsetService: Received stop request...Stopping profile...
07-27 10:11:41.669  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:41.670  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 10:11:41.674  1737  1751 D BluetoothHeadset: Proxy object disconnected
07-27 10:11:41.674   871   871 D BluetoothHeadset: Proxy object disconnected
,07-27 10:11:41.674  3856  3869 D BluetoothHeadset: Proxy object disconnected
07-27 10:11:41.675   871   871 D BluetoothHeadset: Proxy object disconnected
,07-27 10:11:41.675  1375  2032 D BluetoothHeadset: Proxy object disconnected
,07-27 10:11:41.675  1375  1375 D HeadsetProfile: Bluetooth service disconnected
07-27 10:11:41.675   871   871 D BluetoothHeadset: Proxy object disconnected
07-27 10:11:41.676  4077  4077 D A2dpService: Received stop request...Stopping profile...
07-27 10:11:41.677  4077  4108 D A2dpStateMachine: Exit Disconnected: -1
,07-27 10:11:41.677  3856  3856 D DockEventReceiver: finishStartingService: stopping service
07-27 10:11:41.678   871   871 D BluetoothA2dp: Proxy object disconnected
,07-27 10:11:41.679  1375  1375 D BluetoothA2dp: Proxy object disconnected
07-27 10:11:41.678  3856  3856 D HeadsetProfile: Bluetooth service disconnected
07-27 10:11:41.681  3856  3856 D BluetoothA2dp: Proxy object disconnected
07-27 10:11:41.682  4077  4077 D HidService: Received stop request...Stopping profile...
,07-27 10:11:41.682  4077  4077 D HidService: Stopping Bluetooth HidService
07-27 10:11:41.683  3856  3856 D BluetoothInputDevice: Proxy object disconnected
07-27 10:11:41.683  3856  3856 D HidProfile: Bluetooth service disconnected
07-27 10:11:41.683  1375  1375 D BluetoothInputDevice: Proxy object disconnected
,07-27 10:11:41.683  1375  1375 D HidProfile: Bluetooth service disconnected
07-27 10:11:41.683  4077  4077 V BluetoothAdapterState: isTurningOff()=true
07-27 10:11:41.683  4077  4077 V BluetoothAdapterState: isTurningOn()=false
07-27 10:11:41.683  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
,07-27 10:11:41.683  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
07-27 10:11:41.684  4077  4077 D HealthService: Received stop request...Stopping profile...
,07-27 10:11:41.688  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-27 10:11:41.690  4077  4077 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,07-27 10:11:41.690  4077  4093 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-27 10:11:41.690  4077  4099 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-27 10:11:41.690  4077  4099 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-27 10:11:41.690  4077  4099 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-27 10:11:41.692  4077  4093 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
07-27 10:11:41.692  4077  4077 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,07-27 10:11:41.693  4077  4077 D PanService: Received stop request...Stopping profile...
,07-27 10:11:41.694  1375  1375 D BluetoothPan: BluetoothPAN Proxy object disconnected
,07-27 10:11:41.694  1375  1375 D PanProfile: Bluetooth service disconnected
07-27 10:11:41.695  4077  4077 D BluetoothMapService: Received stop request...Stopping profile...
07-27 10:11:41.694  3856  3856 D BluetoothPan: BluetoothPAN Proxy object disconnected
,07-27 10:11:41.695  4077  4077 D BluetoothMapService: stop()
07-27 10:11:41.695  3856  3856 D PanProfile: Bluetooth service disconnected
,07-27 10:11:41.695  4077  4077 D BluetoothMapAppObserver: deinitObservers()
07-27 10:11:41.695  4077  4077 D BluetoothMapAppObserver: removeReceiver()
,07-27 10:11:41.697  4077  4077 V BluetoothAdapterState: isTurningOff()=true
,07-27 10:11:41.697  1375  1375 D BluetoothMap: Proxy object disconnected
07-27 10:11:41.697  4077  4077 V BluetoothAdapterState: isTurningOn()=false
,07-27 10:11:41.697  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
07-27 10:11:41.697  1375  1375 D MapProfile: Bluetooth service disconnected
07-27 10:11:41.697  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
07-27 10:11:41.697  3856  3856 D BluetoothMap: Proxy object disconnected
,07-27 10:11:41.697  3856  3856 D MapProfile: Bluetooth service disconnected
07-27 10:11:41.699  4077  4093 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-27 10:11:41.699  4077  4099 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-27 10:11:41.699  4077  4099 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-27 10:11:41.699  4077  4099 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 10:11:41.699  4077  4099 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,07-27 10:11:41.699  4077  4099 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 10:11:41.699  4077  4099 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,07-27 10:11:41.703  4077  4077 V BluetoothAdapterState: isTurningOff()=true
,07-27 10:11:41.703  4077  4077 V BluetoothAdapterState: isTurningOn()=false
,07-27 10:11:41.703  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
07-27 10:11:41.704  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
07-27 10:11:41.704  4077  4077 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,07-27 10:11:41.704  4077  4093 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-27 10:11:41.705  4077  4077 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-27 10:11:41.705  4077  4077 V BluetoothAdapterState: isTurningOff()=true
07-27 10:11:41.705  4077  4077 V BluetoothAdapterState: isTurningOn()=false
07-27 10:11:41.705  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
,07-27 10:11:41.706  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
07-27 10:11:41.706  4077  4077 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-27 10:11:41.706  4077  4093 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-27 10:11:41.706  4077  4077 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-27 10:11:41.708  1375  1375 D BluetoothPbap: Proxy object disconnected
,07-27 10:11:41.708  1375  1375 D PbapServerProfile: Bluetooth service disconnected
07-27 10:11:41.708  3856  3856 D BluetoothPbap: Proxy object disconnected
07-27 10:11:41.708  4077  4077 V BluetoothAdapterState: isTurningOff()=true
07-27 10:11:41.708  3856  3856 D PbapServerProfile: Bluetooth service disconnected
,07-27 10:11:41.708  4077  4077 V BluetoothAdapterState: isTurningOn()=false
07-27 10:11:41.708  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
07-27 10:11:41.708  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
07-27 10:11:41.709  4077  4077 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,07-27 10:11:41.709  4077  4077 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-27 10:11:41.709  4077  4077 D BluetoothMapService: MAP Service closeService in
07-27 10:11:41.710  4077  4077 V BluetoothAdapterState: isTurningOff()=true
07-27 10:11:41.710  4077  4077 V BluetoothAdapterState: isTurningOn()=false
07-27 10:11:41.710  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
,07-27 10:11:41.710  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 10:11:41.710  4077  4077 D BluetoothMapService: cleanup()
,07-27 10:11:41.710  4077  4077 D BluetoothMapService: MAP Service closeService in
,07-27 10:11:41.711  4077  4089 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-27 10:11:41.711  4077  4089 D BluetoothAdapterProperties: Setting state to 15
07-27 10:11:41.711  4077  4089 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-27 10:11:41.712  4077  4089 I BluetoothAdapterState: Entering BleOnState
07-27 10:11:41.712  3856  3866 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 10:11:41.712  3856  3868 D BluetoothMap: onBluetoothStateChange: up=false
07-27 10:11:41.713  3856  3869 D BluetoothA2dp: onBluetoothStateChange: up=false
07-27 10:11:41.716  3856  3866 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-27 10:11:41.716   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
07-27 10:11:41.716   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 10:11:41.717  1375  1387 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-27 10:11:41.717  1375  2032 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-27 10:11:41.718  1375  1385 D BluetoothMap: onBluetoothStateChange: up=false
07-27 10:11:41.718   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 10:11:41.719  1375  3716 D BluetoothPan: onBluetoothStateChange on: false
07-27 10:11:41.720  1375  1387 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-27 10:11:41.721  1375  2032 D BluetoothPbap: onBluetoothStateChange: up=false
,07-27 10:11:41.721  3856  3868 D BluetoothPbap: onBluetoothStateChange: up=false
,07-27 10:11:41.722  1737  1953 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 10:11:41.723  3856  3869 D BluetoothPan: onBluetoothStateChange on: false
,07-27 10:11:41.723   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-27 10:11:41.724  4077  4089 D BluetoothAdapterState: Current state: BLE ON, message: 20
,07-27 10:11:41.724  4077  4089 D BluetoothAdapterProperties: Setting state to 16
07-27 10:11:41.724  4077  4089 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-27 10:11:41.725  4077  4089 D BluetoothAdapterProperties: onBleDisable
07-27 10:11:41.725  4077  4089 I BluetoothAdapterState: Entering PendingCommandState
07-27 10:11:41.725  4077  4090 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,07-27 10:11:41.726  4077  4093 D BluetoothAdapterProperties: Scan Mode:20
07-27 10:11:41.726  4077  4099 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-27 10:11:41.726  4077  4099 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-27 10:11:41.730  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 10:11:41.731  3856  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-27 10:11:41.732  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 10:11:41.734  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 10:11:41.735  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:41.738  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-27 10:11:41.741  3856  3856 D DockEventReceiver: finishStartingService: stopping service
,07-27 10:11:41.927  4077  4093 I bt_hci  : shut_down
,07-27 10:11:41.928  4077  4097 D bt_hwcfg: hw_epilog_process
,07-27 10:11:41.943  4077  4097 I bt_vendor: low_power_mode_cb
,07-27 10:11:41.964  4077  4097 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-27 10:11:41.964  4077  4097 I bt_vendor: epilog_cb
07-27 10:11:41.964  4077  4097 I bt_hci  : epilog_finished_callback
,07-27 10:11:41.969  4077  4093 I bt_hci_h4: hal_close
,07-27 10:11:41.970  4077  4093 I bt_userial_vendor: device fd = 51 close
,07-27 10:11:42.096  4077  4090 D bt_stack_manager: event_shut_down_stack finished.
,07-27 10:11:42.097  4077  4089 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-27 10:11:42.103  4077  4077 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-27 10:11:42.104  4077  4089 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,07-27 10:11:42.105  4077  4077 D BtGatt.GattService: Received stop request...Stopping profile...
,07-27 10:11:42.105  4077  4077 D BtGatt.GattService: stop()
07-27 10:11:42.106  4077  4077 D BtGatt.AdvertiseManager: advertise clients cleared
,07-27 10:11:42.111  4077  4077 V BluetoothAdapterState: isTurningOff()=false
,07-27 10:11:42.111  4077  4077 V BluetoothAdapterState: isTurningOn()=false
07-27 10:11:42.111  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
,07-27 10:11:42.112  4077  4077 V BluetoothAdapterState: isBleTurningOff()=true
07-27 10:11:42.113  4077  4089 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,07-27 10:11:42.115  4077  4089 D BluetoothAdapterProperties: Setting state to 10
,07-27 10:11:42.116  4077  4089 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-27 10:11:42.117  4077  4089 I BluetoothAdapterState: Entering OffState
,07-27 10:11:42.119   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,07-27 10:11:42.141  4077  4077 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-27 10:11:42.141  4077  4077 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,07-27 10:11:42.142  4077  4090 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-27 10:11:42.149  4077  4077 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-27 10:11:42.150  4077  4090 D bt_stack_manager: event_clean_up_stack finished.
,07-27 10:11:42.155  4077  4077 I art     : System.exit called, status: 0
07-27 10:11:42.156  4077  4077 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-27 10:11:42.219   871  1696 I ActivityManager: Process com.android.bluetooth (pid 4077) has died
,07-27 10:11:42.965   871  1318 D ConnectivityService: handlePromptUnvalidated 101
,07-27 10:11:44.629  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
,07-27 10:11:44.630  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 10:11:47.638  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-27 10:11:47.639  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@42123ed added. We now have 6 listener(s)
07-27 10:11:47.639  3717  3764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 10:11:47.643  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 10:11:47.644  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@15cb222 added. We now have 7 listener(s)
,07-27 10:11:47.644  3717  3764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 10:11:47.646  3717  3764 I System.out: IsBluetoothEnabled
,07-27 10:11:47.658  3717  3764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:47.706   871   888 I ActivityManager: Start proc 4135:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-27 10:11:47.833  4135  4135 D AdapterServiceConfig: Adding HeadsetService
,07-27 10:11:47.833  4135  4135 D AdapterServiceConfig: Adding A2dpService
07-27 10:11:47.833  4135  4135 D AdapterServiceConfig: Adding HidService
,07-27 10:11:47.833  4135  4135 D AdapterServiceConfig: Adding HealthService
07-27 10:11:47.834  4135  4135 D AdapterServiceConfig: Adding PanService
,07-27 10:11:47.834  4135  4135 D AdapterServiceConfig: Adding GattService
07-27 10:11:47.834  4135  4135 D AdapterServiceConfig: Adding BluetoothMapService
,07-27 10:11:47.852   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e28d01d:true
,07-27 10:11:47.852  4135  4135 D BluetoothAdapterState: make() - Creating AdapterState
,07-27 10:11:47.858  4135  4135 I bt_bluedroid: init
,07-27 10:11:47.859  4135  4147 I BluetoothAdapterState: Entering OffState
,07-27 10:11:47.864  4135  4148 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-27 10:11:47.865  4135  4148 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,07-27 10:11:47.865  4135  4148 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-27 10:11:47.865  4135  4148 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-27 10:11:47.867  4135  4135 I bt_bluedroid: get_profile_interface socket
,07-27 10:11:47.870  4135  4135 I bt_bluedroid: get_profile_interface sdp
,07-27 10:11:47.875  4135  4151 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-27 10:11:47.877  4135  4146 I bt_bluedroid: config_hci_snoop_log
,07-27 10:11:47.878  4135  4151 D BluetoothAdapterProperties: Name is: Nexus 6
,07-27 10:11:47.880   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,07-27 10:11:47.891  4135  4147 D BluetoothAdapterState: Current state: OFF, message: 0
,07-27 10:11:47.891  4135  4147 D BluetoothAdapterProperties: Setting state to 14
07-27 10:11:47.892  4135  4147 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-27 10:11:47.895  4135  4147 D BluetoothBondStateMachine: make
,07-27 10:11:47.899  4135  4152 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-27 10:11:47.903  4135  4147 I BluetoothAdapterState: Entering PendingCommandState
,07-27 10:11:47.907  4135  4135 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-27 10:11:47.915  4135  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d788d33
,07-27 10:11:47.917  4135  4135 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-27 10:11:47.918  4135  4135 D BtGatt.GattService: Received start request. Starting profile...
,07-27 10:11:47.918  4135  4135 D BtGatt.GattService: start()
07-27 10:11:47.919  4135  4135 I bt_bluedroid: get_profile_interface gatt
,07-27 10:11:47.921  4135  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d788d33
,07-27 10:11:47.921  4135  4135 D BtGatt.AdvertiseManager: advertise manager created
,07-27 10:11:47.935  4135  4135 V BluetoothAdapterState: isTurningOff()=false
,07-27 10:11:47.935  4135  4135 V BluetoothAdapterState: isTurningOn()=false
07-27 10:11:47.936  4135  4135 V BluetoothAdapterState: isBleTurningOn()=true
07-27 10:11:47.936  4135  4135 V BluetoothAdapterState: isBleTurningOff()=false
07-27 10:11:47.938  4135  4147 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,07-27 10:11:47.939  4135  4147 I bt_bluedroid: enable
07-27 10:11:47.940  4135  4148 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-27 10:11:47.941  4135  4148 I bt_hci  : start_up
,07-27 10:11:47.964  4135  4148 I bt_vendor: alloc value 0xb3a40189
07-27 10:11:47.964  4135  4148 I bt_vendor: init
07-27 10:11:47.964  4135  4148 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-27 10:11:47.965  4135  4148 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-27 10:11:48.074  4135  4148 D bt_hci  : start_up starting async portion
07-27 10:11:48.075  4135  4155 I bt_hci  : event_finish_startup
07-27 10:11:48.075  4135  4155 I bt_hci_h4: hal_open
07-27 10:11:48.076  4135  4155 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-27 10:11:48.086  4135  4155 I bt_userial_vendor: device fd = 51 open
,07-27 10:11:48.116  4135  4155 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-27 10:11:48.148  4135  4155 D bt_hwcfg: Chipset BCM4354A2
,07-27 10:11:48.149  4135  4155 D bt_hwcfg: Target name = [BCM4354A2]
,07-27 10:11:48.151  4135  4155 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,07-27 10:11:48.806  4135  4155 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-27 10:11:48.808  4135  4155 D bt_hwcfg: Settlement delay -- 100 ms
,07-27 10:11:48.808  4135  4155 I bt_hwcfg: Setting fw settlement delay to 100 
,07-27 10:11:48.924  4135  4155 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-27 10:11:48.926  4135  4155 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,07-27 10:11:48.956  4135  4155 I bt_hwcfg: vendor lib fwcfg completed
,07-27 10:11:48.956  4135  4155 I bt_vendor: firmware callback
07-27 10:11:48.956  4135  4155 I bt_hci  : firmware_config_callback
,07-27 10:11:48.967  4135  4157 I bt_btu  : btu_task pending for preload complete event
,07-27 10:11:48.968  4135  4157 I bt_btu_task: Bluetooth chip preload is complete
07-27 10:11:48.968  4135  4157 I bt_btu  : btu_task received preload complete event
,07-27 10:11:48.980  4135  4157 I         : BTE_InitTraceLevels -- TRC_HCI
,07-27 10:11:48.981  4135  4157 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-27 10:11:48.981  4135  4157 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-27 10:11:48.981  4135  4157 I         : BTE_InitTraceLevels -- TRC_AVDT
07-27 10:11:48.982  4135  4157 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-27 10:11:48.982  4135  4157 I         : BTE_InitTraceLevels -- TRC_A2D
07-27 10:11:48.982  4135  4157 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-27 10:11:48.982  4135  4157 I         : BTE_InitTraceLevels -- TRC_BTM
07-27 10:11:48.983  4135  4157 I         : BTE_InitTraceLevels -- TRC_GAP
07-27 10:11:48.983  4135  4157 I         : BTE_InitTraceLevels -- TRC_PAN
07-27 10:11:48.983  4135  4157 I         : BTE_InitTraceLevels -- TRC_SDP
07-27 10:11:48.983  4135  4157 I         : BTE_InitTraceLevels -- TRC_GATT
07-27 10:11:48.984  4135  4157 I         : BTE_InitTraceLevels -- TRC_SMP
07-27 10:11:48.984  4135  4157 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-27 10:11:48.984  4135  4157 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-27 10:11:49.118  4135  4157 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39bdd9d
,07-27 10:11:49.118  4135  4157 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39bdd9d 
,07-27 10:11:49.131  4135  4151 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,07-27 10:11:49.140  4135  4151 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-27 10:11:49.141  4135  4151 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61,
,07-27 10:11:49.144  4135  4151 D BluetoothAdapterProperties: Name is: Nexus 6,
,07-27 10:11:49.146  4135  4151 D BluetoothAdapterProperties: Scan Mode:20
,07-27 10:11:49.147  4135  4151 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-27 10:11:49.147  4135  4151 D bt_hci  : do_postload posting postload work item
,07-27 10:11:49.147  4135  4155 I bt_hci  : event_postload
07-27 10:11:49.147  4135  4155 I bt_vendor: sco_config_cb
07-27 10:11:49.147  4135  4155 I bt_hci  : sco_config_callback postload finished.
07-27 10:11:49.150  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:49.151  4135  4151 D bt_bte_conf: Device ID record 1 : primary
07-27 10:11:49.152  4135  4151 D bt_bte_conf:   vendorId            = 000f
07-27 10:11:49.152  4135  4151 D bt_bte_conf:   vendorIdSource      = 0001
07-27 10:11:49.152  4135  4151 D bt_bte_conf:   product             = 1200
07-27 10:11:49.152  4135  4151 D bt_bte_conf:   version             = 1436
07-27 10:11:49.152  4135  4151 D bt_bte_conf:   clientExecutableURL = 
,07-27 10:11:49.153  4135  4151 D bt_bte_conf:   serviceDescription  = 
07-27 10:11:49.153  4135  4151 D bt_bte_conf:   documentationURL    = 
07-27 10:11:49.153  4135  4151 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-27 10:11:49.154  4135  4148 D bt_stack_manager: event_start_up_stack finished
07-27 10:11:49.154  4135  4147 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-27 10:11:49.155  4135  4147 D BluetoothAdapterProperties: Setting state to 15
07-27 10:11:49.155  4135  4147 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-27 10:11:49.157  4135  4147 I BluetoothAdapterState: Entering BleOnState
,07-27 10:11:49.161  4135  4147 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-27 10:11:49.161  4135  4147 D BluetoothAdapterProperties: Setting state to 11
07-27 10:11:49.161  4135  4147 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-27 10:11:49.166  4135  4155 I bt_vendor: low_power_mode_cb
,07-27 10:11:49.171  4135  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d788d33
,07-27 10:11:49.173  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:49.174  4135  4135 D HeadsetService: Received start request. Starting profile...
,07-27 10:11:49.177  4135  4135 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-27 10:11:49.177  4135  4135 D HeadsetStateMachine: make
,07-27 10:11:49.188  4135  4147 I BluetoothAdapterState: Entering PendingCommandState
,07-27 10:11:49.189  4135  4135 D HeadsetStateMachine: max_hf_connections = 1
07-27 10:11:49.189  4135  4135 I bt_bluedroid: get_profile_interface handsfree
07-27 10:11:49.189  4135  4151 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,07-27 10:11:49.189  4135  4151 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,07-27 10:11:49.193  4135  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d788d33
,07-27 10:11:49.193  4135  4135 D A2dpService: Received start request. Starting profile...
,07-27 10:11:49.194  4135  4135 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-27 10:11:49.194  4135  4135 I bt_bluedroid: get_profile_interface avrcp
,07-27 10:11:49.200  4135  4135 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-27 10:11:49.201  4135  4135 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-27 10:11:49.201  4135  4135 D A2dpStateMachine: make
,07-27 10:11:49.202  4135  4135 I bt_bluedroid: get_profile_interface a2dp
,07-27 10:11:49.202  4135  4151 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-27 10:11:49.205  4135  4166 D A2dpStateMachine: Enter Disconnected: -2
,07-27 10:11:49.207  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-27 10:11:49.207  4135  4135 I BluetoothHidServiceJni: classInitNative: succeeds
07-27 10:11:49.208  4135  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d788d33
07-27 10:11:49.209  4135  4135 D HidService: Received start request. Starting profile...
07-27 10:11:49.209  4135  4135 I bt_bluedroid: get_profile_interface hidhost
07-27 10:11:49.209  4135  4151 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb399f3e5
,07-27 10:11:49.210  4135  4151 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-27 10:11:49.210  4135  4135 D HidService: setHidService(): set to: null
07-27 10:11:49.210  4135  4135 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-27 10:11:49.211  4135  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d788d33
,07-27 10:11:49.212  4135  4135 D HealthService: Received start request. Starting profile...
,07-27 10:11:49.213  4135  4135 I bt_bluedroid: get_profile_interface health
,07-27 10:11:49.214  4135  4135 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-27 10:11:49.215  4135  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d788d33
,07-27 10:11:49.216  4135  4135 D PanService: Received start request. Starting profile...
,07-27 10:11:49.216  4135  4135 D BluetoothPanServiceJni: initializeNative(L110): pan
07-27 10:11:49.216  4135  4135 I bt_bluedroid: get_profile_interface pan
07-27 10:11:49.217  4135  4151 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-27 10:11:49.220  4135  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d788d33
,07-27 10:11:49.221  4135  4135 D BluetoothMapService: Received start request. Starting profile...
07-27 10:11:49.221  4135  4135 D BluetoothMapService: start()
,07-27 10:11:49.223  4135  4135 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-27 10:11:49.224  4135  4135 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-27 10:11:49.224  4135  4135 D BluetoothMapAppObserver: createReceiver()
,07-27 10:11:49.225  4135  4135 D BluetoothMapAppObserver: initObservers()
,07-27 10:11:49.225  4135  4135 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-27 10:11:49.231  4135  4135 V BluetoothAdapterState: isTurningOff()=false
,07-27 10:11:49.231  4135  4135 V BluetoothAdapterState: isTurningOn()=true
07-27 10:11:49.231  4135  4135 V BluetoothAdapterState: isBleTurningOn()=false
07-27 10:11:49.231  4135  4135 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 10:11:49.232  4135  4135 V BluetoothAdapterState: isTurningOff()=false
,07-27 10:11:49.232  4135  4135 V BluetoothAdapterState: isTurningOn()=true
07-27 10:11:49.233  4135  4135 V BluetoothAdapterState: isBleTurningOn()=false
07-27 10:11:49.233  4135  4135 V BluetoothAdapterState: isBleTurningOff()=false
07-27 10:11:49.233  4135  4163 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-27 10:11:49.235  4135  4135 V BluetoothAdapterState: isTurningOff()=false
,07-27 10:11:49.235  4135  4135 V BluetoothAdapterState: isTurningOn()=true
07-27 10:11:49.235  4135  4135 V BluetoothAdapterState: isBleTurningOn()=false
07-27 10:11:49.235  4135  4135 V BluetoothAdapterState: isBleTurningOff()=false
07-27 10:11:49.235  4135  4135 V BluetoothAdapterState: isTurningOff()=false
,07-27 10:11:49.235  4135  4135 V BluetoothAdapterState: isTurningOn()=true
,07-27 10:11:49.235  4135  4135 V BluetoothAdapterState: isBleTurningOn()=false
07-27 10:11:49.235  4135  4135 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 10:11:49.235  4135  4135 V BluetoothAdapterState: isTurningOff()=false
07-27 10:11:49.235  4135  4135 V BluetoothAdapterState: isTurningOn()=true
07-27 10:11:49.235  4135  4135 V BluetoothAdapterState: isBleTurningOn()=false
,07-27 10:11:49.236  4135  4135 V BluetoothAdapterState: isBleTurningOff()=false
07-27 10:11:49.236  4135  4135 V BluetoothAdapterState: isTurningOff()=false
,07-27 10:11:49.236  4135  4135 V BluetoothAdapterState: isTurningOn()=true
07-27 10:11:49.236  4135  4135 V BluetoothAdapterState: isBleTurningOn()=false
07-27 10:11:49.236  4135  4135 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 10:11:49.236  4135  4147 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,07-27 10:11:49.236  4135  4147 D BluetoothAdapterProperties: ScanMode =  20
07-27 10:11:49.236  4135  4147 D BluetoothAdapterProperties: State =  11
,07-27 10:11:49.237  4135  4151 D BluetoothAdapterProperties: Scan Mode:21
07-27 10:11:49.237  4135  4151 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 10:11:49.237  4135  4147 D BluetoothAdapterProperties: Setting state to 12
,07-27 10:11:49.238  4135  4147 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-27 10:11:49.238  4135  4147 I BluetoothAdapterState: Entering OnState
07-27 10:11:49.238  3856  3866 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 10:11:49.239  3856  3868 D BluetoothMap: onBluetoothStateChange: up=true
,07-27 10:11:49.241  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 10:11:49.241  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:49.241  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:49.241  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 10:11:49.241  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 10:11:49.241  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 10:11:49.241  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 10:11:49.241  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 10:11:49.242  3856  3869 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 10:11:49.243  3717  3717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 10:11:49.244  3856  3866 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-27 10:11:49.246   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-27 10:11:49.246   871   871 D BluetoothA2dp: Proxy object connected
,07-27 10:11:49.247   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-27 10:11:49.248  3856  3856 D BluetoothMap: Proxy object connected
07-27 10:11:49.248  1375  1385 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-27 10:11:49.248  3856  3856 D MapProfile: Bluetooth service connected
,07-27 10:11:49.248  3856  3856 D BluetoothMap: getConnectedDevices()
,07-27 10:11:49.249  1375  1385 D BluetoothHeadset: onBluetoothStateChange: up=true,
07-27 10:11:49.249  1375  1375 D BluetoothInputDevice: Proxy object connected
,07-27 10:11:49.249  1375  1375 D HidProfile: Bluetooth service connected
07-27 10:11:49.250  1375  1387 D BluetoothMap: onBluetoothStateChange: up=true,
07-27 10:11:49.250  3856  3856 D BluetoothA2dp: Proxy object connected
07-27 10:11:49.251  4135  4135 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-27 10:11:49.252  4135  4135 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-27 10:11:49.252  3856  3856 D BluetoothInputDevice: Proxy object connected
07-27 10:11:49.252  3856  3856 D HidProfile: Bluetooth service connected
07-27 10:11:49.253  1375  1375 D BluetoothMap: Proxy object connected
,07-27 10:11:49.253  1375  1375 D MapProfile: Bluetooth service connected
07-27 10:11:49.253  1375  1375 D BluetoothMap: getConnectedDevices()
,07-27 10:11:49.253   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 10:11:49.254  4135  4135 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 10:11:49.254  1375  3716 D BluetoothPan: onBluetoothStateChange on: true
07-27 10:11:49.256  4135  4135 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 10:11:49.256  1375  1385 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 10:11:49.257  4135  4135 D ObexServerSockets: Succeed to create listening sockets 
,07-27 10:11:49.257  4135  4135 D ObexServerSockets0: startAccept()
07-27 10:11:49.257  4135  4135 D ObexServerSockets0: prepareForNewConnect()
07-27 10:11:49.258  1375  1375 D BluetoothA2dp: Proxy object connected
07-27 10:11:49.259  1375  2032 D BluetoothPbap: onBluetoothStateChange: up=true
,07-27 10:11:49.259  4135  4135 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-27 10:11:49.259  4135  4135 D BluetoothSdpJni: SDP Create record success - handle: 0
07-27 10:11:49.260  1375  1375 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 10:11:49.260  1375  1375 D PanProfile: Bluetooth service connected
07-27 10:11:49.261  3856  3868 D BluetoothPbap: onBluetoothStateChange: up=true
,07-27 10:11:49.262  4135  4172 D ObexServerSockets0: Accepting socket connection...
07-27 10:11:49.262  4135  4171 D ObexServerSockets0: Accepting socket connection...
07-27 10:11:49.263  1737  1953 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 10:11:49.263  3856  3866 D BluetoothPan: onBluetoothStateChange on: true
07-27 10:11:49.265   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 10:11:49.265  3856  3856 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 10:11:49.265  3856  3856 D PanProfile: Bluetooth service connected
,07-27 10:11:49.266   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
,07-27 10:11:49.266  4135  4135 D BluetoothMapService: onReceive
07-27 10:11:49.267  4135  4135 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-27 10:11:49.267  4135  4135 D BluetoothMapService: STATE_ON
07-27 10:11:49.267  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:49.272  3856  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-27 10:11:49.278  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-27 10:11:49.278  3856  3856 D DockEventReceiver: finishStartingService: stopping service
,07-27 10:11:49.287  3856  3856 D BluetoothPbap: Proxy object connected
,07-27 10:11:49.288  3856  3856 D PbapServerProfile: Bluetooth service connected
,07-27 10:11:49.290  1375  1375 D BluetoothPbap: Proxy object connected
,07-27 10:11:49.290  1375  1375 D PbapServerProfile: Bluetooth service connected
,07-27 10:11:49.297  4135  4135 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-27 10:11:49.297  4135  4135 D ObexServerSockets0: prepareForNewConnect()
07-27 10:11:49.297  4135  4177 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 10:11:49.320  4135  4181 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 10:11:49.321  4135  4181 I BtOppRfcommListener: Accept thread started.
,07-27 10:11:49.341  1737  1754 D BluetoothHeadset: Proxy object connected
,07-27 10:11:49.342   871   871 D BluetoothHeadset: Proxy object connected
,07-27 10:11:49.342  3856  3868 D BluetoothHeadset: Proxy object connected
,07-27 10:11:49.342   871   871 D BluetoothHeadset: Proxy object connected
07-27 10:11:49.342  3856  3856 D HeadsetProfile: Bluetooth service connected
07-27 10:11:49.343  1375  2032 D BluetoothHeadset: Proxy object connected
07-27 10:11:49.343  1375  1375 D HeadsetProfile: Bluetooth service connected
07-27 10:11:49.343   871   871 D BluetoothHeadset: Proxy object connected
,07-27 10:11:49.348   871   888 D BluetoothHeadset: Proxy object connected
,07-27 10:11:49.350  1375  1385 D BluetoothHeadset: Proxy object connected
,07-27 10:11:49.350  1375  1375 D HeadsetProfile: Bluetooth service connected
,07-27 10:11:49.354   871   888 D BluetoothHeadset: Proxy object connected
,07-27 10:11:49.363  1737  1862 D BluetoothHeadset: Proxy object connected
,07-27 10:11:49.366   871   888 D BluetoothHeadset: Proxy object connected
,07-27 10:11:49.681  3717  3764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 10:11:49.681  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:49.681  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:49.681  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 10:11:49.681  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 10:11:49.681  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 10:11:49.681  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 10:11:49.681  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 10:11:49.687  3717  3764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 10:11:49.693  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-27 10:11:49.693  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b0a64b3 added. We now have 8 listener(s)
,07-27 10:11:49.694  3717  3764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 10:11:49.700   871   881 D WifiService: setWifiEnabled: false pid=3717, uid=10000
,07-27 10:11:49.701   871   881 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-27 10:11:49.712  3717  3764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:49.714   871   882 D WifiService: setWifiEnabled: true pid=3717, uid=10000
07-27 10:11:49.714   871   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-27 10:11:49.729   871  1316 D WifiConfigStore: Loading config and enabling all networks 
,07-27 10:11:49.744  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 10:11:49.744  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:49.744  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:49.744  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 10:11:49.744  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 10:11:49.744  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 10:11:49.744  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 10:11:49.744  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 10:11:49.750  3717  3717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 10:11:49.759   871  1316 D WifiConfigStore: loaded 0 passpoint configs
,07-27 10:11:49.760   871  1316 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-27 10:11:49.760   871  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
07-27 10:11:49.761   871  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-27 10:11:49.762   871  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-27 10:11:49.762   871  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-27 10:11:49.762   871  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-27 10:11:49.763   871  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-27 10:11:49.781   871  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-27 10:11:49.781   371   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,07-27 10:11:49.783   371   869 D CommandListener: Setting iface cfg
,07-27 10:11:49.833   871  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
07-27 10:11:49.834   871  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-27 10:11:49.839   871  1316 E native  : do suspend true
,07-27 10:11:49.854   871  1314 D WifiNative-HAL: p2pGetDeviceAddress
,07-27 10:11:49.855   871  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,07-27 10:11:49.867   871  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,07-27 10:11:50.736  3717  3764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 10:11:50.736  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:50.736  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:50.736  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 10:11:50.736  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 10:11:50.736  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 10:11:50.736  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 10:11:50.736  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 10:11:50.742  3717  3764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 10:11:50.756  3717  3764 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-27 10:11:50.760  3717  3764 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-27 10:11:50.767  3717  3764 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2a4c98f Bundle[{}]
,07-27 10:11:50.767  3717  3764 I io.jxcore.node.LifeCycleMonitor: start: OK
07-27 10:11:50.768  3717  3764 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-27 10:11:50.768  3717  3764 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-27 10:11:50.769  3717  3764 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-27 10:11:50.770  3717  3764 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-27 10:11:50.771  3717  3764 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-27 10:11:50.777  3717  3764 I System.out: Running OutgoingSocketThread
,07-27 10:11:50.780  3717  4188 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 424)
,07-27 10:11:50.782  3717  4188 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47034
,07-27 10:11:50.782  3717  4188 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-27 10:11:51.182   871  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-27 10:11:51.301   871  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.00 rxSuccessRate=14.62 delta 1000 -> 994
,07-27 10:11:51.302   871  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
07-27 10:11:51.303   871  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 10:11:51.321   871  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-27 10:11:51.398   871  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-27 10:11:51.400  1469  1469 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-27 10:11:51.780  3717  3764 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 425)
,07-27 10:11:51.781  3717  3764 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 425)
,07-27 10:11:51.781  3717  3764 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 425)
07-27 10:11:51.782  3717  3764 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 425)
,07-27 10:11:51.794  3717  3764 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 430)
,07-27 10:11:51.795  3717  3764 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 430)
,07-27 10:11:51.795  3717  3764 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,07-27 10:11:51.797  3717  3764 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 431)
,07-27 10:11:51.798  3717  3764 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 433)
,07-27 10:11:51.800  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-27 10:11:51.800  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38d9a70 added. We now have 2 listener(s)
,07-27 10:11:51.802  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-27 10:11:51.802  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 10:11:51.802  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 10:11:51.803  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 10:11:51.803  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af911e9 added. We now have 9 listener(s)
07-27 10:11:51.803  3717  3764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 10:11:51.804  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 10:11:51.807  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 10:11:51.817  3717  3764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 10:11:51.817  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:51.817  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:51.817  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 10:11:51.817  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 10:11:51.817  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 10:11:51.817  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 10:11:51.817  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 10:11:51.821  3717  3764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 10:11:51.822  3717  3764 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-27 10:11:51.822  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 10:11:51.823  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c990f added. We now have 3 listener(s)
07-27 10:11:51.824  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 10:11:51.826  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:51.830  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-27 10:11:51.830  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 10:11:51.830  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 10:11:51.831  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 10:11:51.831  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@109ed9c added. We now have 10 listener(s)
07-27 10:11:51.832  3717  3764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 10:11:51.832  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-27 10:11:51.832  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 10:11:51.833  3717  3764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 10:11:51.834  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:51.834  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:51.834  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-27 10:11:51.834  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 10:11:51.835  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38d9a70 removed from the list
07-27 10:11:51.835  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:51.835  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af911e9 removed from the list
07-27 10:11:51.835  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
07-27 10:11:51.836  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:51.837  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:51.837  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 10:11:51.839  1469  1469 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-27 10:11:51.840  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:51.840  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 10:11:51.840  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 10:11:51.841  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af911e9 not in the list
07-27 10:11:51.841  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 10:11:51.841  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:51.844  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 10:11:51.845  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:51.845  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:51.847  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@109ed9c removed from the list
,07-27 10:11:51.847  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:51.848  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:51.849  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 10:11:51.849  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 10:11:51.849  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c990f removed from the list
,07-27 10:11:51.851  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 10:11:51.851  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a47e3a5 added. We now have 2 listener(s)
,07-27 10:11:51.860  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-27 10:11:51.860  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 10:11:51.860  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 10:11:51.860  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-27 10:11:51.860  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e96637a added. We now have 9 listener(s)
,07-27 10:11:51.860  3717  3764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 10:11:51.861  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 10:11:51.863  1469  1469 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-27 10:11:51.863  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,07-27 10:11:51.866  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 10:11:51.867  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-27 10:11:51.868   871  1316 D WifiConfigStore: Retrieve network priorities after PNO.
07-27 10:11:51.871  3717  3764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 10:11:51.871  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:51.871  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:51.871  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 10:11:51.871  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 10:11:51.871  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 10:11:51.871  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 10:11:51.871  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 10:11:51.874   871  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-27 10:11:51.874   871  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 10:11:51.875   871  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-27 10:11:51.875  3717  3764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 10:11:51.875  3717  3764 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 10:11:51.876  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 10:11:51.876  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e964788 added. We now have 3 listener(s)
07-27 10:11:51.877  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-27 10:11:51.877  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 10:11:51.878  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 10:11:51.878  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 10:11:51.878  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 10:11:51.878  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af81521 added. We now have 10 listener(s)
07-27 10:11:51.878  3717  3764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 10:11:51.878  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 10:11:51.878  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-27 10:11:51.878  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-27 10:11:51.878  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 10:11:51.878  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 10:11:51.879  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:51.880  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-27 10:11:51.882  3717  3764 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-27 10:11:51.882  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-27 10:11:51.885   871  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 10:11:51.887  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-27 10:11:51.888  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-27 10:11:51.888  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-27 10:11:51.892   371   869 D CommandListener: Setting iface cfg
07-27 10:11:51.892   871  1316 D WifiStateMachine: Start Dhcp Watchdog 3
,07-27 10:11:51.894  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-27 10:11:51.894  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-27 10:11:51.894  3717  3764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-27 10:11:51.895  3717  3764 D BluetoothAdapter: STATE_ON
,07-27 10:11:51.898   871  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
07-27 10:11:51.899  4135  4164 D BtGatt.GattService: registerClient() - UUID=03db956d-6450-494d-aca2-35bdeadb4c27
,07-27 10:11:51.899  4135  4151 D BtGatt.GattService: onClientRegistered() - UUID=03db956d-6450-494d-aca2-35bdeadb4c27, clientIf=5
,07-27 10:11:51.900  3717  3727 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-27 10:11:51.901  4135  4173 D BtGatt.GattService: start scan with filters
,07-27 10:11:51.904  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-27 10:11:51.904  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-27 10:11:51.904  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-27 10:11:51.904  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-27 10:11:51.904  4135  4154 D BtGatt.ScanManager: handling starting scan
,07-27 10:11:51.906  4135  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d788d33
,07-27 10:11:51.906  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-27 10:11:51.907  3717  3717 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-27 10:11:51.907  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-27 10:11:51.907   871  4193 D DhcpClient: Receive thread started
,07-27 10:11:51.909  4135  4151 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-27 10:11:51.909  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:51.909  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-27 10:11:51.909  4135  4154 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-27 10:11:51.912  1518  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-27 10:11:51.912  1518  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-27 10:11:51.912  1518  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:11:51.912  3717  3764 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-27 10:11:51.912  1518  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-27 10:11:51.912  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-27 10:11:51.912  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:51.912  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-27 10:11:51.913  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-27 10:11:51.913  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-27 10:11:51.913  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,07-27 10:11:51.913  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-27 10:11:51.913  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-27 10:11:51.913  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-27 10:11:51.914  3717  3764 D BluetoothAdapter: STATE_ON
07-27 10:11:51.914  4135  4173 D BtGatt.GattService: stopScan() - queue size =1
,07-27 10:11:51.915  4135  4151 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-27 10:11:51.915  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:51.915  4135  4154 D BtGatt.ScanManager: Starting BLE batch scan
07-27 10:11:51.915  4135  4154 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-27 10:11:51.915  4135  4145 D BtGatt.GattService: unregisterClient() - clientIf=5
07-27 10:11:51.916  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-27 10:11:51.916  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-27 10:11:51.916  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-27 10:11:51.916  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-27 10:11:51.916  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-27 10:11:51.917  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 10:11:51.917  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-27 10:11:51.917  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-27 10:11:51.917  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 10:11:51.919  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 10:11:51.920  3717  3717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 10:11:51.920  3717  3717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 10:11:51.920  3717  3717 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-27 10:11:51.922  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 10:11:51.923  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 10:11:51.923  3717  3764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 10:11:51.923  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:51.923  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 10:11:51.923  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 10:11:51.923  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 10:11:51.923  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a47e3a5 removed from the list
07-27 10:11:51.923  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:51.923  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e96637a removed from the list
07-27 10:11:51.923  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
,07-27 10:11:51.923  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:51.924  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:51.924  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:51.924  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:51.925  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 10:11:51.925  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:51.925  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e96637a not in the list
07-27 10:11:51.925  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:51.925  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 10:11:51.926  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 10:11:51.926  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:51.926  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:51.926  4135  4151 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-27 10:11:51.927  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:51.927  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af81521 removed from the list
07-27 10:11:51.927  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:51.927  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:51.927  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:51.927  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 10:11:51.927  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e964788 removed from the list
07-27 10:11:51.928  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 10:11:51.928  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fe25d added. We now have 2 listener(s)
07-27 10:11:51.930  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-27 10:11:51.930  1518  1529 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-27 10:11:51.930  1518  1529 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-27 10:11:51.930  1518  1529 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-27 10:11:51.930  1518  1529 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-27 10:11:51.930  1518  1529 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 10:11:51.930  1518  1529 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 10:11:51.930  1518  1529 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
07-27 10:11:51.930  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 10:11:51.930  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 10:11:51.931  4135  4151 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-27 10:11:51.932  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:51.932  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 10:11:51.933  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@579e7d2 added. We now have 9 listener(s)
07-27 10:11:51.933  3717  3764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 10:11:51.933  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 10:11:51.934  3380  3411 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-27 10:11:51.934  3380  3411 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-27 10:11:51.934  3380  3411 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-27 10:11:51.934  3380  3411 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-27 10:11:51.934  3380  3411 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-27 10:11:51.934  3380  3411 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-27 10:11:51.934  3380  3411 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 10:11:51.937  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 10:11:51.937  4135  4151 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-27 10:11:51.937  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:51.938  4135  4154 D BtGatt.ScanManager: stopping BLe Batch
,07-27 10:11:51.941  3717  3764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 10:11:51.941  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:51.941  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:51.941  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 10:11:51.941  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 10:11:51.941  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 10:11:51.941  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 10:11:51.941  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 10:11:51.942  3717  3764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 10:11:51.942  3717  3764 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 10:11:51.943  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 10:11:51.943  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f347fa0 added. We now have 3 listener(s)
07-27 10:11:51.943  4135  4151 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-27 10:11:51.943  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:51.944  4135  4154 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
07-27 10:11:51.944  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-27 10:11:51.944  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 10:11:51.944  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 10:11:51.944  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 10:11:51.945  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dfd4759 added. We now have 10 listener(s),
07-27 10:11:51.945  3717  3764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 10:11:51.945  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 10:11:51.945  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 10:11:51.945  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 10:11:51.946  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 10:11:51.946  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 10:11:51.947  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 10:11:51.947  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:51.948  4135  4151 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-27 10:11:51.948  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,07-27 10:11:51.950  3717  3764 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-27 10:11:51.950  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-27 10:11:51.953  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-27 10:11:51.953  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-27 10:11:51.953  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-27 10:11:51.955  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-27 10:11:51.956  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-27 10:11:51.956  3717  3764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-27 10:11:51.956  3717  3764 D BluetoothAdapter: STATE_ON
,07-27 10:11:51.958  4135  4173 D BtGatt.GattService: registerClient() - UUID=37d6f524-eee4-4667-9631-dd79b457e7fd
07-27 10:11:51.958  4135  4151 D BtGatt.GattService: onClientRegistered() - UUID=37d6f524-eee4-4667-9631-dd79b457e7fd, clientIf=5
,07-27 10:11:51.958  3717  3728 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-27 10:11:51.958  4135  4164 D BtGatt.GattService: start scan with filters
,07-27 10:11:51.960  4135  4154 D BtGatt.ScanManager: handling starting scan
,07-27 10:11:51.960  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-27 10:11:51.960  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-27 10:11:51.960  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-27 10:11:51.961  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-27 10:11:51.963  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-27 10:11:51.963  3717  3717 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-27 10:11:51.963  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-27 10:11:51.964  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-27 10:11:51.965  4135  4151 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-27 10:11:51.965  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:51.965  4135  4154 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-27 10:11:51.967  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 10:11:51.967  3717  3764 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,07-27 10:11:51.967  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 10:11:51.967  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 10:11:51.967  3717  3764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 10:11:51.967  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:51.967  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:51.967  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-27 10:11:51.968  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-27 10:11:51.968  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fe25d removed from the list
07-27 10:11:51.968  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:51.968  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@579e7d2 removed from the list
07-27 10:11:51.968  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
07-27 10:11:51.968  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 10:11:51.968  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:51.968  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,07-27 10:11:51.968  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:51.968  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 10:11:51.969  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:51.969  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 10:11:51.969  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:51.969  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@579e7d2 not in the list
,07-27 10:11:51.970  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-27 10:11:51.970  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-27 10:11:51.970  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-27 10:11:51.970  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-27 10:11:51.970  4135  4151 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,07-27 10:11:51.970  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-27 10:11:51.970  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:51.970  4135  4154 D BtGatt.ScanManager: Starting BLE batch scan
07-27 10:11:51.970  4135  4154 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-27 10:11:51.970  3717  3764 D BluetoothAdapter: STATE_ON
07-27 10:11:51.971  4135  4146 D BtGatt.GattService: stopScan() - queue size =1
07-27 10:11:51.971  4135  4145 D BtGatt.GattService: unregisterClient() - clientIf=5
07-27 10:11:51.972  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 10:11:51.972  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-27 10:11:51.972  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,07-27 10:11:51.972  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-27 10:11:51.972  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-27 10:11:51.973  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-27 10:11:51.973  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-27 10:11:51.973  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-27 10:11:51.973  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 10:11:51.973  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 10:11:51.974  3717  3717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 10:11:51.974  3717  3717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 10:11:51.974  3717  3717 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 10:11:51.974  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 10:11:51.975  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:51.975  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:51.975  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dfd4759 removed from the list
07-27 10:11:51.975  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-27 10:11:51.975  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:51.975  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:51.975  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 10:11:51.975  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f347fa0 removed from the list
07-27 10:11:51.976  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 10:11:51.976  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b20015 added. We now have 2 listener(s)
,07-27 10:11:51.977  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-27 10:11:51.977  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 10:11:51.977  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 10:11:51.977  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 10:11:51.978  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10e9f2a added. We now have 9 listener(s)
07-27 10:11:51.978  3717  3764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 10:11:51.978  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 10:11:51.979  4135  4151 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-27 10:11:51.979  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-27 10:11:51.981  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 10:11:51.983  4135  4151 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,07-27 10:11:51.984  3717  3764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 10:11:51.984  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:51.984  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:51.984  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 10:11:51.984  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 10:11:51.984  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 10:11:51.984  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 10:11:51.984  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 10:11:51.984  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-27 10:11:51.985  3717  3764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 10:11:51.985  3717  3764 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-27 10:11:51.985  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-27 10:11:51.986  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2ea2b8 added. We now have 3 listener(s)
07-27 10:11:51.986  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 10:11:51.987  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 10:11:51.987  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-27 10:11:51.987  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 10:11:51.987  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-27 10:11:51.987  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-27 10:11:51.987  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@abf8891 added. We now have 10 listener(s)
07-27 10:11:51.987  3717  3764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 10:11:51.987  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 10:11:51.987  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 10:11:51.987  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 10:11:51.987  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 10:11:51.988   871  1316 E native  : do suspend false
,07-27 10:11:51.989  4135  4151 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-27 10:11:51.989  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:51.989  4135  4154 D BtGatt.ScanManager: stopping BLe Batch
07-27 10:11:51.990  3717  3764 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-27 10:11:51.990  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-27 10:11:51.992  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-27 10:11:51.992  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-27 10:11:51.993  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-27 10:11:51.995  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-27 10:11:51.995  4135  4151 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-27 10:11:51.995  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,07-27 10:11:51.995  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:51.995  3717  3764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-27 10:11:51.995  4135  4154 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-27 10:11:51.995  3717  3764 D BluetoothAdapter: STATE_ON
,07-27 10:11:51.997  4135  4173 D BtGatt.GattService: registerClient() - UUID=0bc75b6b-3ede-44ff-83a7-7d36c2cf92bb
07-27 10:11:51.997  4135  4151 D BtGatt.GattService: onClientRegistered() - UUID=0bc75b6b-3ede-44ff-83a7-7d36c2cf92bb, clientIf=5
,07-27 10:11:51.997  3717  3756 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-27 10:11:51.997  4135  4145 D BtGatt.GattService: start scan with filters
,07-27 10:11:51.999   871  1973 D DhcpClient: Broadcasting DHCPDISCOVER
07-27 10:11:51.999  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-27 10:11:51.999  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-27 10:11:51.999  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-27 10:11:51.999  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-27 10:11:52.000  4135  4151 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-27 10:11:52.000  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-27 10:11:52.001  4135  4154 D BtGatt.ScanManager: handling starting scan
,07-27 10:11:52.002  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-27 10:11:52.002  3717  3717 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-27 10:11:52.002  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-27 10:11:52.003  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-27 10:11:52.006  4135  4151 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-27 10:11:52.006  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:52.006  4135  4154 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-27 10:11:52.007  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 10:11:52.007  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 10:11:52.007  3717  3764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-27 10:11:52.007  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:52.007  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:52.007  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-27 10:11:52.007  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 10:11:52.007  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b20015 removed from the list
07-27 10:11:52.007  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:52.007  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10e9f2a removed from the list
,07-27 10:11:52.007  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
07-27 10:11:52.007  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 10:11:52.008  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-27 10:11:52.008  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-27 10:11:52.008  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:52.008  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 10:11:52.008  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:52.008  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 10:11:52.008  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 10:11:52.008  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10e9f2a not in the list
07-27 10:11:52.008  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-27 10:11:52.008  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-27 10:11:52.008  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
07-27 10:11:52.009  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-27 10:11:52.009  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-27 10:11:52.009  3717  3764 D BluetoothAdapter: STATE_ON
07-27 10:11:52.009  4135  4145 D BtGatt.GattService: stopScan() - queue size =1,
07-27 10:11:52.010  4135  4164 D BtGatt.GattService: unregisterClient() - clientIf=5
07-27 10:11:52.010  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 10:11:52.010  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-27 10:11:52.010  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-27 10:11:52.010  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,07-27 10:11:52.010  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-27 10:11:52.011  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 10:11:52.011  4135  4151 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-27 10:11:52.011  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-27 10:11:52.011  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-27 10:11:52.011  3717  3764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,07-27 10:11:52.011  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 10:11:52.011  4135  4154 D BtGatt.ScanManager: Starting BLE batch scan
07-27 10:11:52.011  4135  4154 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-27 10:11:52.011  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 10:11:52.012  3717  3717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 10:11:52.012  3717  3717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 10:11:52.012  3717  3717 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 10:11:52.012  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 10:11:52.012  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-27 10:11:52.012  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:52.012  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@abf8891 removed from the list
07-27 10:11:52.012  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:52.012  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:52.012  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:52.012  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 10:11:52.012  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2ea2b8 removed from the list
,07-27 10:11:52.013  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 10:11:52.013  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3431ccd added. We now have 2 listener(s)
07-27 10:11:52.014  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-27 10:11:52.014  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 10:11:52.014  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-27 10:11:52.014  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 10:11:52.014  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7e982 added. We now have 9 listener(s)
07-27 10:11:52.014  3717  3764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 10:11:52.015  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 10:11:52.018  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 10:11:52.020  4135  4151 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-27 10:11:52.020  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:52.021  3717  3764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,07-27 10:11:52.021  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:52.021  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:52.021  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 10:11:52.021  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 10:11:52.021  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 10:11:52.021  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 10:11:52.021  3717  3764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 10:11:52.022  3717  3764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 10:11:52.022  3717  3764 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 10:11:52.022  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-27 10:11:52.022  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb710d0 added. We now have 3 listener(s)
07-27 10:11:52.023  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 10:11:52.024  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-27 10:11:52.024  4135  4151 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-27 10:11:52.024  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:52.024  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 10:11:52.024  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 10:11:52.024  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 10:11:52.024  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bf1b8c9 added. We now have 10 listener(s)
07-27 10:11:52.024  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 10:11:52.025  3717  3764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 10:11:52.025  3717  3764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 10:11:52.025   871  4193 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
07-27 10:11:52.025  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 10:11:52.025  3717  3764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 10:11:52.025  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:52.025   871  1973 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
07-27 10:11:52.025  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:52.026  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 10:11:52.026  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 10:11:52.026  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3431ccd removed from the list
07-27 10:11:52.026  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:52.026  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7e982 removed from the list
07-27 10:11:52.026  3717  3764 D io.jxcore.node.ConnectivityMonitor: stop
07-27 10:11:52.026  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:52.026  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:52.026  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:52.026   871  1973 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 ,serverid=192.168.1.1
07-27 10:11:52.027  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:52.027  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 10:11:52.027  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:52.027  3717  3764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7e982 not in the list
07-27 10:11:52.027  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:52.027  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:52.027  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 10:11:52.028  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 10:11:52.028  3717  3764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 10:11:52.028  3717  3764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bf1b8c9 removed from the list
07-27 10:11:52.028  3717  3764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 10:11:52.028  3717  3764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 10:11:52.028  3717  3764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 10:11:52.028  3717  3764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 10:11:52.028  3717  3764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb710d0 removed from the list
07-27 10:11:52.028  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-27 10:11:52.029  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-27 10:11:52.029  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-27 10:11:52.029  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-27 10:11:52.029  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-27 10:11:52.029  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-27 10:11:52.029  4135  4151 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-27 10:11:52.029  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:52.030  4135  4154 D BtGatt.ScanManager: stopping BLe Batch
,07-27 10:11:52.033  3717  4195 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: My test thread name)
,07-27 10:11:52.033  3717  4195 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 439, thread name: My test thread name)
07-27 10:11:52.033  3717  4195 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 439, name: My test thread name)
,07-27 10:11:52.034  4135  4151 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-27 10:11:52.035  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:52.035  4135  4154 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-27 10:11:52.036  3717  4196 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 441, name: My test thread name)
07-27 10:11:52.036  3717  4196 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 441, thread name: My test thread name)
,07-27 10:11:52.036  3717  4196 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 441, name: My test thread name)
,07-27 10:11:52.038  3717  3764 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 84
,07-27 10:11:52.038  3717  3764 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 84
,07-27 10:11:52.038  3717  3764 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,07-27 10:11:52.038  3717  3764 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-27 10:11:52.038  3717  3764 D com.test.thalitest.ThaliTestRunner: Total duration: 22792 ms
07-27 10:11:52.039  4135  4151 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-27 10:11:52.039  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-27 10:11:52.040  3717  3764 I jxcore-log: Total number of executed tests:  84
07-27 10:11:52.040  3717  3764 I jxcore-log: 
07-27 10:11:52.041  3717  3764 I jxcore-log: Number of passed tests:  84
07-27 10:11:52.041  3717  3764 I jxcore-log: 
07-27 10:11:52.041  3717  3764 I jxcore-log: Number of failed tests:  0
07-27 10:11:52.041  3717  3764 I jxcore-log: 
07-27 10:11:52.041  3717  3764 I jxcore-log: Number of ignored tests:  0
07-27 10:11:52.041  3717  3764 I jxcore-log: 
07-27 10:11:52.041  3717  3764 I jxcore-log: Total duration:  22792
07-27 10:11:52.041  3717  3764 I jxcore-log: 
,07-27 10:11:52.044  3717  3764 I jxcore-log: Unit Test app is loaded
07-27 10:11:52.044  3717  3764 I jxcore-log: 
,07-27 10:11:52.050  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 10:11:52.050  3717  3764 I jxcore-log: 
,07-27 10:11:52.052  3717  3717 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-27 10:11:52.054  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 10:11:52.054  3717  3764 I jxcore-log: 
,07-27 10:11:52.055  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 10:11:52.055  3717  3764 I jxcore-log: 
,07-27 10:11:52.056  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-27 10:11:52.056  3717  3764 I jxcore-log: 
,07-27 10:11:52.057  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-27 10:11:52.057  3717  3764 I jxcore-log: 
,07-27 10:11:52.059  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 10:11:52.059  3717  3764 I jxcore-log: 
,07-27 10:11:52.061  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-27 10:11:52.061  3717  3764 I jxcore-log: 
,07-27 10:11:52.063  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-27 10:11:52.063  3717  3764 I jxcore-log: 
,07-27 10:11:52.064  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 10:11:52.064  3717  3764 I jxcore-log: 
,07-27 10:11:52.065  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-27 10:11:52.065  3717  3764 I jxcore-log: 
,07-27 10:11:52.065  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-27 10:11:52.065  3717  3764 I jxcore-log: 
,07-27 10:11:52.066  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-27 10:11:52.066  3717  3764 I jxcore-log: 
,07-27 10:11:52.067  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-27 10:11:52.067  3717  3764 I jxcore-log: 
,07-27 10:11:52.068  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 10:11:52.068  3717  3764 I jxcore-log: 
,07-27 10:11:52.069  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 10:11:52.069  3717  3764 I jxcore-log: 
,07-27 10:11:52.070  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 10:11:52.070  3717  3764 I jxcore-log: 
,07-27 10:11:52.071  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 10:11:52.071  3717  3764 I jxcore-log: 
07-27 10:11:52.071  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 10:11:52.071  3717  3764 I jxcore-log: 
07-27 10:11:52.072  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 10:11:52.072  3717  3764 I jxcore-log: 
,07-27 10:11:52.074  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 10:11:52.074  3717  3764 I jxcore-log: 
,07-27 10:11:52.075  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 10:11:52.075  3717  3764 I jxcore-log: 
,07-27 10:11:52.076  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 10:11:52.076  3717  3764 I jxcore-log: 
,07-27 10:11:52.077  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 10:11:52.077  3717  3764 I jxcore-log: 
,07-27 10:11:52.077  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 10:11:52.077  3717  3764 I jxcore-log: 
,07-27 10:11:52.078  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 10:11:52.078  3717  3764 I jxcore-log: 
,07-27 10:11:52.079  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 10:11:52.079  3717  3764 I jxcore-log: 
,07-27 10:11:52.079  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 10:11:52.079  3717  3764 I jxcore-log: 
07-27 10:11:52.080  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 10:11:52.080  3717  3764 I jxcore-log: 
,07-27 10:11:52.081  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 10:11:52.081  3717  3764 I jxcore-log: 
07-27 10:11:52.081  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 10:11:52.081  3717  3764 I jxcore-log: 
,07-27 10:11:52.082  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 10:11:52.082  3717  3764 I jxcore-log: 
,07-27 10:11:52.083  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 10:11:52.083  3717  3764 I jxcore-log: 
,07-27 10:11:52.084  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 10:11:52.084  3717  3764 I jxcore-log: 
,07-27 10:11:52.085  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 10:11:52.085  3717  3764 I jxcore-log: 
,07-27 10:11:52.085  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 10:11:52.085  3717  3764 I jxcore-log: 
,07-27 10:11:52.086  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-27 10:11:52.086  3717  3764 I jxcore-log: 
07-27 10:11:52.086  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-27 10:11:52.086  3717  3764 I jxcore-log: 
07-27 10:11:52.087  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 10:11:52.087  3717  3764 I jxcore-log: 
07-27 10:11:52.087  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-27 10:11:52.087  3717  3764 I jxcore-log: 
07-27 10:11:52.088  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-27 10:11:52.088  3717  3764 I jxcore-log: 
07-27 10:11:52.088  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 10:11:52.088  3717  3764 I jxcore-log: 
,07-27 10:11:52.089  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-27 10:11:52.089  3717  3764 I jxcore-log: 
07-27 10:11:52.089  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-27 10:11:52.089  3717  3764 I jxcore-log: 
07-27 10:11:52.090  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 10:11:52.090  3717  3764 I jxcore-log: 
,07-27 10:11:52.093  3717  3764 I jxcore-log: My device name is: motorola-Nexus 6
07-27 10:11:52.093  3717  3764 I jxcore-log: 
,07-27 10:11:52.113   871  4193 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-27 10:11:52.113   871  1973 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
07-27 10:11:52.114   371   869 D CommandListener: Setting iface cfg
,07-27 10:11:52.116   871  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,07-27 10:11:52.118   871  1316 E native  : do suspend true
,07-27 10:11:52.118   871  1973 D DhcpClient: Scheduling renewal in 86399s
,07-27 10:11:52.128   871  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-27 10:11:52.129   871  1316 D WifiConfigStore: No blacklist allowed without epno enabled
07-27 10:11:52.129   871  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,07-27 10:11:52.132   871  1318 D ConnectivityService: Adding iface wlan0 to network 102
,07-27 10:11:52.133   871  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-27 10:11:52.173   871  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-27 10:11:52.173   871  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,07-27 10:11:52.174   871  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,07-27 10:11:52.175   871  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,07-27 10:11:52.176   871  1318 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,07-27 10:11:52.182   871  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,07-27 10:11:52.186   871  1318 D ConnectivityService: scheduleUnvalidatedPrompt 102
,07-27 10:11:52.186   871  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,07-27 10:11:52.186   871  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-27 10:11:52.187   871  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-27 10:11:52.187   871  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
07-27 10:11:52.187   871  1318 D ConnectivityService:    accepting network in place of null
,07-27 10:11:52.188   871  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-27 10:11:52.218   871  4192 D NetlinkSocketObserver: NeighborEvent{elapsedMs=342801, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-27 10:11:52.221   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-27 10:11:52.256   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-27 10:11:52.261   871  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,07-27 10:11:52.261   871  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-27 10:11:52.264   871   888 D Tethering: MasterInitialState.processMessage what=3
07-27 10:11:52.266   871  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
07-27 10:11:52.269  3717  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 10:11:52.269  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 10:11:52.269  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 10:11:52.269  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 10:11:52.269  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 10:11:52.269  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 10:11:52.269  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 10:11:52.269  3717  3717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 10:11:52.272  3717  3717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 10:11:52.289   871  4191 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:401b:801::200e
07-27 10:11:52.292  1985  1985 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
07-27 10:11:52.314  1985  1985 D SystemUpdateService: onCreate
07-27 10:11:52.316  1985  1985 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
07-27 10:11:52.331  1985  4205 I SystemUpdateService: active receiver: enabled
,07-27 10:11:52.367  1985  4205 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-27 10:11:52.379   871  4191 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jul 2016 08:11:52 GMT], X-Android-Received-Millis=[1469607112379], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1469607112340]}
,07-27 10:11:52.380   871  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-27 10:11:52.380   871  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,07-27 10:11:52.380   871  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,07-27 10:11:52.381   871  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-27 10:11:52.416  1985  4205 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,07-27 10:11:52.416  1985  4205 I SystemUpdateService: now status is 0 (complete)
07-27 10:11:52.416  1985  4205 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,07-27 10:11:52.416  1985  4205 I SystemUpdateService: file has been verified
07-27 10:11:52.416  1985  4205 I SystemUpdateService: OTA package size = 12249756
,07-27 10:11:52.434  1985  1985 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-27 10:11:52.442  1985  4209 I MDM     : [224] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,07-27 10:11:52.442  1985  4209 W BaseAppContext: Using Auth Proxy for data requests.
,07-27 10:11:52.444  1985  4209 V GoogleAuthProtoRequest: [224] a.<init>: mAccountName set to: thalitester@gmail.com
,07-27 10:11:52.448  1985  1985 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-27 10:11:52.449  1985  1985 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-27 10:11:52.435  1985  2342 I iu.UploadsManager: num queued entries: 0
,07-27 10:11:52.451  1985  2342 I iu.UploadsManager: num updated entries: 0
,07-27 10:11:52.453  3910  3910 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-27 10:11:52.457  3910  3910 D SprintDMHelper: simOperator: 
,07-27 10:11:52.457  3910  3910 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-27 10:11:52.493  4004  4206 V GoogleAuthProtoRequest: [350] a.<init>: mAccountName set to: thalitester@gmail.com
,07-27 10:11:52.501  1985  4205 I SystemUpdateService: showing system update notification
,07-27 10:11:52.452  1985  2342 I iu.SyncManager: NEXT; no task
,07-27 10:11:52.550  1985  1985 D SystemUpdateService: onDestroy
,07-27 10:11:52.552  1518  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,07-27 10:11:52.552  1518  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
07-27 10:11:52.552  1518  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:11:52.552  1518  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:11:52.554  1518  2207 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-27 10:11:52.554  1518  2207 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-27 10:11:52.554  1518  2207 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:11:52.554  1518  2207 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:11:52.577  1985  4209 E MDM     : [224] SitrepService.a: Error sending sitrep.
,07-27 10:11:52.582  4004  4206 W ExperimentUpdateService: [350] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-27 10:11:52.582  4004  4206 W ExperimentUpdateService: [350] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 10:11:52.582  4004  4206 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 10:11:52.582  4004  4206 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-27 10:11:52.582  4004  4206 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-27 10:11:52.582  4004  4206 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-27 10:11:52.582  4004  4206 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-27 10:11:52.582  4004  4206 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-27 10:11:52.582  4004  4206 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-27 10:11:52.582  4004  4206 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-27 10:11:52.582  4004  4206 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-27 10:11:52.582  4004  4206 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-27 10:11:52.620  3340  4213 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-27 10:11:56.193  3717  3764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-27 10:11:56.193  3717  3764 I jxcore-log: 
,07-27 10:11:56.589  3717  3764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-27 10:11:56.589  3717  3764 I jxcore-log: 
,07-27 10:11:56.613  3717  3764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-27 10:11:56.613  3717  3764 I jxcore-log: 
,07-27 10:11:56.618  3717  3764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-27 10:11:56.618  3717  3764 I jxcore-log: 
,07-27 10:11:56.634  3717  3764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-27 10:11:56.634  3717  3764 I jxcore-log: 
,07-27 10:11:56.639  3717  3764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-27 10:11:56.639  3717  3764 I jxcore-log: 
,07-27 10:11:58.665  3717  3764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-27 10:11:58.665  3717  3764 I jxcore-log: 
,07-27 10:11:58.677  3717  3764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-27 10:11:58.677  3717  3764 I jxcore-log: 
,07-27 10:11:58.687  3717  3764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-27 10:11:58.687  3717  3764 I jxcore-log: 
,07-27 10:11:58.845  3717  3764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-27 10:11:58.845  3717  3764 I jxcore-log: 
,07-27 10:11:59.655  3717  3764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-27 10:11:59.655  3717  3764 I jxcore-log: 
,07-27 10:11:59.713  3717  3764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-27 10:11:59.713  3717  3764 I jxcore-log: 
,07-27 10:11:59.721  3717  3764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-27 10:11:59.721  3717  3764 I jxcore-log: 
,07-27 10:11:59.922  3717  3764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-27 10:11:59.922  3717  3764 I jxcore-log: 
,07-27 10:11:59.945  3717  3764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-27 10:11:59.945  3717  3764 I jxcore-log: 
,07-27 10:11:59.950  3717  3764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-27 10:11:59.950  3717  3764 I jxcore-log: 
,07-27 10:11:59.956  3717  3764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-27 10:11:59.956  3717  3764 I jxcore-log: 
,07-27 10:11:59.972  3717  3764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-27 10:11:59.972  3717  3764 I jxcore-log: 
,07-27 10:11:59.993  3717  3764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-27 10:11:59.993  3717  3764 I jxcore-log: 
,07-27 10:12:00.080  3717  3764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-27 10:12:00.080  3717  3764 I jxcore-log: 
,07-27 10:12:00.086  3717  3764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-27 10:12:00.086  3717  3764 I jxcore-log: 
,07-27 10:12:00.114  3717  3764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-27 10:12:00.114  3717  3764 I jxcore-log: 
,07-27 10:12:00.127  3717  3764 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-27 10:12:00.129  3717  3764 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-27 10:12:00.129  3717  3764 I jxcore-log: 
,07-27 10:12:00.179  3717  3764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 10:12:00.179  3717  3764 I jxcore-log: 
,07-27 10:12:00.180  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-27 10:12:00.180  3717  3764 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
07-27 10:12:00.180  3717  3764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
07-27 10:12:00.180  3717  3764 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,07-27 10:12:00.192   871  1318 D ConnectivityService: handlePromptUnvalidated 102
,07-27 10:12:17.187  1665  1774 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-27 10:12:17.187  1665  1774 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-27 10:12:17.229  1518  1518 I ConfigService: onCreate
,07-27 10:12:22.276  1518  1518 I ConfigService: onDestroy,
,07-27 10:12:22.697  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:12:22.700  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:12:22.715  4004  4222 V GoogleAuthProtoRequest: [351] a.<init>: mAccountName set to: thalitester@gmail.com
,07-27 10:12:22.742  1518  2207 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-27 10:12:22.742  1518  2207 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-27 10:12:22.742  1518  2207 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:12:22.742  1518  2207 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:12:22.761  4004  4222 W ExperimentUpdateService: [351] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-27 10:12:22.761  4004  4222 W ExperimentUpdateService: [351] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 10:12:22.761  4004  4222 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 10:12:22.761  4004  4222 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-27 10:12:22.761  4004  4222 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-27 10:12:22.761  4004  4222 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-27 10:12:22.761  4004  4222 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-27 10:12:22.761  4004  4222 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-27 10:12:22.761  4004  4222 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-27 10:12:22.761  4004  4222 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-27 10:12:22.761  4004  4222 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-27 10:12:22.761  4004  4222 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-27 10:12:29.274   871  4192 D NetlinkSocketObserver: NeighborEvent{elapsedMs=379857, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 10:12:57.680   871  4192 D NetlinkSocketObserver: NeighborEvent{elapsedMs=408264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-27 10:13:23.186  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:13:23.191  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:13:23.201  4004  4226 V GoogleAuthProtoRequest: [352] a.<init>: mAccountName set to: thalitester@gmail.com
,07-27 10:13:23.234  1518  1950 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-27 10:13:23.235  1518  1950 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-27 10:13:23.235  1518  1950 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:13:23.235  1518  1950 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:13:23.253  4004  4226 W ExperimentUpdateService: [352] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-27 10:13:23.253  4004  4226 W ExperimentUpdateService: [352] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 10:13:23.253  4004  4226 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 10:13:23.253  4004  4226 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-27 10:13:23.253  4004  4226 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-27 10:13:23.253  4004  4226 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-27 10:13:23.253  4004  4226 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-27 10:13:23.253  4004  4226 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-27 10:13:23.253  4004  4226 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-27 10:13:23.253  4004  4226 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-27 10:13:23.253  4004  4226 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-27 10:13:23.253  4004  4226 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-27 10:13:34.267   871  4192 D NetlinkSocketObserver: NeighborEvent{elapsedMs=444850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 10:14:18.966  2886  4230 V KeepSync: Connecting to GoogleApiClient
07-27 10:14:18.967   871  1373 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-27 10:14:19.020  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:14:19.022  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:14:19.045  1518  1950 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-27 10:14:19.045  1518  1950 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,07-27 10:14:19.045  1518  1950 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 10:14:19.045  1518  1950 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:14:19.059  1985  4231 V BaseAuthAsyncOperation: access token request failed
,07-27 10:14:19.060  2886  4230 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-27 10:14:19.111  1518  2207 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-27 10:14:19.111  1518  2207 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,07-27 10:14:19.111  1518  2207 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:14:19.111  1518  2207 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:14:19.129  2886  4230 E KeepSync: IOException
07-27 10:14:19.129  2886  4230 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-27 10:14:19.129  2886  4230 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-27 10:14:19.129  2886  4230 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-27 10:14:19.129  2886  4230 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-27 10:14:19.129  2886  4230 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-27 10:14:19.129  2886  4230 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-27 10:14:19.129  2886  4230 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-27 10:14:19.129  2886  4230 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-27 10:14:19.129  2886  4230 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-27 10:14:19.129  2886  4230 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-27 10:14:19.129  2886  4230 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-27 10:14:19.129  2886  4230 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-27 10:14:19.129  2886  4230 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-27 10:14:19.129  2886  4230 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-27 10:14:19.129  2886  4230 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 10:14:19.129  2886  4230 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 10:14:19.129  2886  4230 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-27 10:14:19.129  2886  4230 E KeepSync: 	... 10 more
07-27 10:14:19.129  2886  4230 W KeepSync: Sync result 2
,07-27 10:14:19.136   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 489299, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-27 10:14:51.293  2886  4233 V KeepSync: Connecting to GoogleApiClient
07-27 10:14:51.293   871   882 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-27 10:14:51.352  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:14:51.355  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:14:51.395  1518  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
07-27 10:14:51.395  1518  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,07-27 10:14:51.395  1518  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:14:51.395  1518  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:14:51.422  1985  4234 V BaseAuthAsyncOperation: access token request failed
,07-27 10:14:51.423  2886  4233 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-27 10:14:51.488  1518  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-27 10:14:51.489  1518  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,07-27 10:14:51.489  1518  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:14:51.489  1518  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:14:51.506  2886  4233 E KeepSync: IOException
07-27 10:14:51.506  2886  4233 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-27 10:14:51.506  2886  4233 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-27 10:14:51.506  2886  4233 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-27 10:14:51.506  2886  4233 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-27 10:14:51.506  2886  4233 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-27 10:14:51.506  2886  4233 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-27 10:14:51.506  2886  4233 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-27 10:14:51.506  2886  4233 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-27 10:14:51.506  2886  4233 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-27 10:14:51.506  2886  4233 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-27 10:14:51.506  2886  4233 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-27 10:14:51.506  2886  4233 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-27 10:14:51.506  2886  4233 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-27 10:14:51.506  2886  4233 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-27 10:14:51.506  2886  4233 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 10:14:51.506  2886  4233 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 10:14:51.506  2886  4233 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-27 10:14:51.506  2886  4233 E KeepSync: 	... 10 more
,07-27 10:14:51.506  2886  4233 W KeepSync: Sync result 2
,07-27 10:14:51.513   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 521772, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-27 10:15:21.919  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:15:21.921  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:15:21.963  1518  1950 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 10:15:21.963  1518  1950 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-27 10:15:21.963  1518  1950 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 10:15:21.964  1518  1950 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:15:21.979  3421  4238 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-27 10:15:21.979  3421  4238 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 10:15:21.979  3421  4238 E HttpOperation: 	at jdm.a(PG:82)
07-27 10:15:21.979  3421  4238 E HttpOperation: 	at jcs.o(PG:406)
07-27 10:15:21.979  3421  4238 E HttpOperation: 	at jcn.a(PG:1379)
07-27 10:15:21.979  3421  4238 E HttpOperation: 	at jcs.i(PG:143)
07-27 10:15:21.979  3421  4238 E HttpOperation: 	at blb.a(PG:3937)
07-27 10:15:21.979  3421  4238 E HttpOperation: 	at czp.a(PG:18188)
07-27 10:15:21.979  3421  4238 E HttpOperation: 	at czp.a(PG:9081)
07-27 10:15:21.979  3421  4238 E HttpOperation: 	at czq.run(PG:1686)
07-27 10:15:21.979  3421  4238 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 10:15:21.979  3421  4238 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 10:15:21.979  3421  4238 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 10:15:21.979  3421  4238 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 10:15:21.979  3421  4238 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 10:15:21.979  3421  4238 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 10:15:21.979  3421  4238 E HttpOperation: 	at jdj.a(PG:4091)
07-27 10:15:21.979  3421  4238 E HttpOperation: 	at jdj.a(PG:1125)
07-27 10:15:21.979  3421  4238 E HttpOperation: 	at jdm.a(PG:77)
07-27 10:15:21.979  3421  4238 E HttpOperation: 	... 12 more
07-27 10:15:21.979  3421  4238 E HttpOperation: Caused by: faj: BadAuthentication
07-27 10:15:21.979  3421  4238 E HttpOperation: 	at fal.a(PG:38)
07-27 10:15:21.979  3421  4238 E HttpOperation: 	at jdj.a(PG:4089)
07-27 10:15:21.979  3421  4238 E HttpOperation: 	... 14 more
,07-27 10:15:22.025  1518  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-27 10:15:22.025  1518  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 10:15:22.025  1518  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:15:22.025  1518  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:15:22.063  3421  4238 E HttpOperation: [getmobileexperiments] Unexpected exception
07-27 10:15:22.063  3421  4238 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 10:15:22.063  3421  4238 E HttpOperation: 	at jdm.a(PG:82)
07-27 10:15:22.063  3421  4238 E HttpOperation: 	at jcs.o(PG:406)
07-27 10:15:22.063  3421  4238 E HttpOperation: 	at jcn.a(PG:1379)
07-27 10:15:22.063  3421  4238 E HttpOperation: 	at jcs.i(PG:143)
07-27 10:15:22.063  3421  4238 E HttpOperation: 	at hec.a(PG:42)
07-27 10:15:22.063  3421  4238 E HttpOperation: 	at hee.a(PG:102)
07-27 10:15:22.063  3421  4238 E HttpOperation: 	at czr.a(PG:65)
07-27 10:15:22.063  3421  4238 E HttpOperation: 	at kka.a(PG:108)
07-27 10:15:22.063  3421  4238 E HttpOperation: 	at czp.a(PG:19176)
07-27 10:15:22.063  3421  4238 E HttpOperation: 	at czp.a(PG:9081)
07-27 10:15:22.063  3421  4238 E HttpOperation: 	at czq.run(PG:1686)
07-27 10:15:22.063  3421  4238 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 10:15:22.063  3421  4238 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 10:15:22.063  3421  4238 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 10:15:22.063  3421  4238 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 10:15:22.063  3421  4238 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 10:15:22.063  3421  4238 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 10:15:22.063  3421  4238 E HttpOperation: 	at jdj.a(PG:4091)
07-27 10:15:22.063  3421  4238 E HttpOperation: 	at jdj.a(PG:1125)
07-27 10:15:22.063  3421  4238 E HttpOperation: 	at jdm.a(PG:77)
07-27 10:15:22.063  3421  4238 E HttpOperation: 	... 15 more
07-27 10:15:22.063  3421  4238 E HttpOperation: Caused by: faj: BadAuthentication
07-27 10:15:22.063  3421  4238 E HttpOperation: 	at fal.a(PG:38)
07-27 10:15:22.063  3421  4238 E HttpOperation: 	at jdj.a(PG:4089)
07-27 10:15:22.063  3421  4238 E HttpOperation: 	... 17 more
07-27 10:15:22.064  3421  4238 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-27 10:15:22.064  3421  4238 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-27 10:15:22.064  3421  4238 E ExperimentLoader: 	at jdm.a(PG:82)
07-27 10:15:22.064  3421  4238 E ExperimentLoader: 	at jcs.o(PG:406)
07-27 10:15:22.064  3421  4238 E ExperimentLoader: 	at jcn.a(PG:1379)
07-27 10:15:22.064  3421  4238 E ExperimentLoader: 	at jcs.i(PG:143)
07-27 10:15:22.064  3421  4238 E ExperimentLoader: 	at hec.a(PG:42)
07-27 10:15:22.064  3421  4238 E ExperimentLoader: 	at hee.a(PG:102)
07-27 10:15:22.064  3421  4238 E ExperimentLoader: 	at czr.a(PG:65)
07-27 10:15:22.064  3421  4238 E ExperimentLoader: 	at kka.a(PG:108)
07-27 10:15:22.064  3421  4238 E ExperimentLoader: 	at czp.a(PG:19176)
07-27 10:15:22.064  3421  4238 E ExperimentLoader: 	at czp.a(PG:9081)
07-27 10:15:22.064  3421  4238 E ExperimentLoader: 	at czq.run(PG:1686)
07-27 10:15:22.064  3421  4238 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 10:15:22.064  3421  4238 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 10:15:22.064  3421  4238 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 10:15:22.064  3421  4238 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 10:15:22.064  3421  4238 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-27 10:15:22.064  3421  4238 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 10:15:22.064  3421  4238 E ExperimentLoader: 	at jdj.a(PG:4091)
07-27 10:15:22.064  3421  4238 E ExperimentLoader: 	at jdj.a(PG:1,125)
07-27 10:15:22.064  3421  4238 E ExperimentLoader: 	at jdm.a(PG:77)
07-27 10:15:22.064  3421  4238 E ExperimentLoader: 	... 15 more
07-27 10:15:22.064  3421  4238 E ExperimentLoader: Caused by: faj: BadAuthentication
07-27 10:15:22.064  3421  4238 E ExperimentLoader: 	at fal.a(PG:38)
07-27 10:15:22.064  3421  4238 E ExperimentLoader: 	at jdj.a(PG:4089)
07-27 10:15:22.064  3421  4238 E ExperimentLoader: 	... 17 more
,07-27 10:15:22.193   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 529910, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-27 10:15:23.344  4004  4240 V GoogleAuthProtoRequest: [353] a.<init>: mAccountName set to: thalitester@gmail.com
,07-27 10:15:23.366  1518  1950 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-27 10:15:23.366  1518  1950 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,07-27 10:15:23.366  1518  1950 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:15:23.366  1518  1950 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:15:23.380  4004  4240 W ExperimentUpdateService: [353] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-27 10:15:23.381  4004  4240 W ExperimentUpdateService: [353] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 10:15:23.381  4004  4240 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 10:15:23.381  4004  4240 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-27 10:15:23.381  4004  4240 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-27 10:15:23.381  4004  4240 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-27 10:15:23.381  4004  4240 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-27 10:15:23.381  4004  4240 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-27 10:15:23.381  4004  4240 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-27 10:15:23.381  4004  4240 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-27 10:15:23.381  4004  4240 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-27 10:15:23.381  4004  4240 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-27 10:15:40.187   871  4192 D NetlinkSocketObserver: NeighborEvent{elapsedMs=570770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-27 10:15:52.278  3475  4242 I BooksSync: Starting books sync for 61035162, extras: ade
,07-27 10:15:52.311  3475  4243 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-27 10:15:52.326  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:15:52.328  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:15:52.363  1518  2207 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 10:15:52.363  1518  2207 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-27 10:15:52.364  1518  2207 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 10:15:52.364  1518  2207 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:15:52.393  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:15:52.395  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:15:52.420  1518  1949 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-27 10:15:52.420  1518  1949 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-27 10:15:52.420  1518  1949 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:15:52.421  1518  1949 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:15:52.444  3475  4243 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-27 10:15:52.445  3475  4242 E BooksSync: Soft error
07-27 10:15:52.445  3475  4242 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 10:15:52.445  3475  4242 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-27 10:15:52.445  3475  4242 E BooksSync: Sync error
07-27 10:15:52.445  3475  4242 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 10:15:52.445  3475  4242 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-27 10:15:52.445  3475  4242 I BooksSync: Finished books sync
,07-27 10:15:52.461   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 562439, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 10:15:52.754  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:15:52.755  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:15:52.791  1518  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 10:15:52.791  1518  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 10:15:52.791  1518  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 10:15:52.791  1518  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:15:52.809  3421  4245 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-27 10:15:52.809  3421  4245 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 10:15:52.809  3421  4245 E HttpOperation: 	at jdm.a(PG:82)
07-27 10:15:52.809  3421  4245 E HttpOperation: 	at jcs.o(PG:406)
07-27 10:15:52.809  3421  4245 E HttpOperation: 	at jcn.a(PG:1379)
07-27 10:15:52.809  3421  4245 E HttpOperation: 	at jcs.i(PG:143)
07-27 10:15:52.809  3421  4245 E HttpOperation: 	at blb.a(PG:3937)
07-27 10:15:52.809  3421  4245 E HttpOperation: 	at czp.a(PG:18188)
07-27 10:15:52.809  3421  4245 E HttpOperation: 	at czp.a(PG:9081)
07-27 10:15:52.809  3421  4245 E HttpOperation: 	at czq.run(PG:1686)
07-27 10:15:52.809  3421  4245 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 10:15:52.809  3421  4245 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 10:15:52.809  3421  4245 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 10:15:52.809  3421  4245 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 10:15:52.809  3421  4245 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 10:15:52.809  3421  4245 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 10:15:52.809  3421  4245 E HttpOperation: 	at jdj.a(PG:4091)
07-27 10:15:52.809  3421  4245 E HttpOperation: 	at jdj.a(PG:1125)
07-27 10:15:52.809  3421  4245 E HttpOperation: 	at jdm.a(PG:77)
07-27 10:15:52.809  3421  4245 E HttpOperation: 	... 12 more
07-27 10:15:52.809  3421  4245 E HttpOperation: Caused by: faj: BadAuthentication
07-27 10:15:52.809  3421  4245 E HttpOperation: 	at fal.a(PG:38)
07-27 10:15:52.809  3421  4245 E HttpOperation: 	at jdj.a(PG:4089)
07-27 10:15:52.809  3421  4245 E HttpOperation: 	... 14 more
,07-27 10:15:52.892  1518  1949 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 10:15:52.892  1518  1949 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-27 10:15:52.892  1518  1949 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 10:15:52.892  1518  1949 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:15:52.923  3421  4245 E HttpOperation: [getmobileexperiments] Unexpected exception
07-27 10:15:52.923  3421  4245 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 10:15:52.923  3421  4245 E HttpOperation: 	at jdm.a(PG:82)
07-27 10:15:52.923  3421  4245 E HttpOperation: 	at jcs.o(PG:406)
07-27 10:15:52.923  3421  4245 E HttpOperation: 	at jcn.a(PG:1379)
07-27 10:15:52.923  3421  4245 E HttpOperation: 	at jcs.i(PG:143)
07-27 10:15:52.923  3421  4245 E HttpOperation: 	at hec.a(PG:42)
07-27 10:15:52.923  3421  4245 E HttpOperation: 	at hee.a(PG:102)
07-27 10:15:52.923  3421  4245 E HttpOperation: 	at czr.a(PG:65)
07-27 10:15:52.923  3421  4245 E HttpOperation: 	at kka.a(PG:108)
07-27 10:15:52.923  3421  4245 E HttpOperation: 	at czp.a(PG:19176)
07-27 10:15:52.923  3421  4245 E HttpOperation: 	at czp.a(PG:9081)
07-27 10:15:52.923  3421  4245 E HttpOperation: 	at czq.run(PG:1686)
07-27 10:15:52.923  3421  4245 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 10:15:52.923  3421  4245 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 10:15:52.923  3421  4245 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 10:15:52.923  3421  4245 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 10:15:52.923  3421  4245 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 10:15:52.923  3421  4245 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 10:15:52.923  3421  4245 E HttpOperation: 	at jdj.a(PG:4091)
07-27 10:15:52.923  3421  4245 E HttpOperation: 	at jdj.a(PG:1125)
07-27 10:15:52.923  3421  4245 E HttpOperation: 	at jdm.a(PG:77)
07-27 10:15:52.923  3421  4245 E HttpOperation: 	... 15 more
07-27 10:15:52.923  3421  4245 E HttpOperation: Caused by: faj: BadAuthentication
07-27 10:15:52.923  3421  4245 E HttpOperation: 	at fal.a(PG:38)
07-27 10:15:52.923  3421  4245 E HttpOperation: 	at jdj.a(PG:4089)
07-27 10:15:52.923  3421  4245 E HttpOperation: 	... 17 more
,07-27 10:15:52.923  3421  4245 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-27 10:15:52.923  3421  4245 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-27 10:15:52.923  3421  4245 E ExperimentLoader: 	at jdm.a(PG:82)
07-27 10:15:52.923  3421  4245 E ExperimentLoader: 	at jcs.o(PG:406)
07-27 10:15:52.923  3421  4245 E ExperimentLoader: 	at jcn.a(PG:1379)
07-27 10:15:52.923  3421  4245 E ExperimentLoader: 	at jcs.i(PG:143)
07-27 10:15:52.923  3421  4245 E ExperimentLoader: 	at hec.a(PG:42)
07-27 10:15:52.923  3421  4245 E ExperimentLoader: 	at hee.a(PG:102)
07-27 10:15:52.923  3421  4245 E ExperimentLoader: 	at czr.a(PG:65)
07-27 10:15:52.923  3421  4245 E ExperimentLoader: 	at kka.a(PG:108)
07-27 10:15:52.923  3421  4245 E ExperimentLoader: 	at czp.a(PG:19176)
07-27 10:15:52.923  3421  4245 E ExperimentLoader: 	at czp.a(PG:9081)
07-27 10:15:52.923  3421  4245 E ExperimentLoader: 	at czq.run(PG:1686)
07-27 10:15:52.923  3421  4245 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 10:15:52.923  3421  4245 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 10:15:52.923  3421  4245 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 10:15:52.923  3421  4245 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 10:15:52.923  3421  4245 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-27 10:15:52.923  3421  4245 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 10:15:52.923  3421  4245 E ExperimentLoader: 	at jdj.a(PG:4091)
07-27 10:15:52.923  3421  4245 E ExperimentLoader: 	at jdj.a(PG:1125)
07-27 10:15:52.923  3421  4245 E ExperimentLoader: 	at jdm.a(PG:77)
07-27 10:15:52.923  3421  4245 E ExperimentLoader: 	... 15 more
07-27 10:15:52.923  3421  4245 E ExperimentLoader: Caused by: faj: BadAuthentication
07-27 10:15:52.923  3421  4245 E ExperimentLoader: 	at fal.a(PG:38)
07-27 10:15:52.923  3421  4245 E ExperimentLoader: 	at jdj.a(PG:4089)
07-27 10:15:52.923  3421  4245 E ExperimentLoader: 	... 17 more
,07-27 10:15:53.104   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 583103, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-27 10:16:16.720   871  4192 D NetlinkSocketObserver: NeighborEvent{elapsedMs=607304, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 10:16:23.299  3475  4249 I BooksSync: Starting books sync for 61035162, extras: ade
,07-27 10:16:23.340  3475  4250 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-27 10:16:23.353  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:16:23.355  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:16:23.361  2886  4248 V KeepSync: Connecting to GoogleApiClient
,07-27 10:16:23.363   871  1402 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-27 10:16:23.399  1518  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 10:16:23.399  1518  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-27 10:16:23.399  1518  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:16:23.399  1518  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:16:23.469  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:16:23.474  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:16:23.528  1518  1950 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 10:16:23.528  1518  1950 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-27 10:16:23.528  1518  1950 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 10:16:23.528  1518  1950 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:16:23.546  1518  1949 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-27 10:16:23.546  1518  1949 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-27 10:16:23.546  1518  1949 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 10:16:23.546  1518  1949 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:16:23.563  3475  4250 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-27 10:16:23.564  3475  4249 E BooksSync: Soft error
07-27 10:16:23.564  3475  4249 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 10:16:23.564  3475  4249 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-27 10:16:23.564  3475  4249 E BooksSync: Sync error
07-27 10:16:23.564  3475  4249 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 10:16:23.564  3475  4249 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-27 10:16:23.564  3475  4249 I BooksSync: Finished books sync
,07-27 10:16:23.573  1985  4251 V BaseAuthAsyncOperation: access token request failed
,07-27 10:16:23.574  2886  4248 V KeepSync: GoogleApiClient failed to connect with error code: 4
07-27 10:16:23.584   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 613449, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 10:16:23.655  1518  2168 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-27 10:16:23.655  1518  2168 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,07-27 10:16:23.655  1518  2168 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 10:16:23.655  1518  2168 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:16:23.673  2886  4248 E KeepSync: IOException
07-27 10:16:23.673  2886  4248 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-27 10:16:23.673  2886  4248 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-27 10:16:23.673  2886  4248 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-27 10:16:23.673  2886  4248 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-27 10:16:23.673  2886  4248 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-27 10:16:23.673  2886  4248 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-27 10:16:23.673  2886  4248 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-27 10:16:23.673  2886  4248 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-27 10:16:23.673  2886  4248 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-27 10:16:23.673  2886  4248 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-27 10:16:23.673  2886  4248 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-27 10:16:23.673  2886  4248 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-27 10:16:23.673  2886  4248 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-27 10:16:23.673  2886  4248 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-27 10:16:23.673  2886  4248 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 10:16:23.673  2886  4248 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 10:16:23.673  2886  4248 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-27 10:16:23.673  2886  4248 E KeepSync: 	... 10 more
07-27 10:16:23.673  2886  4248 W KeepSync: Sync result 2
,07-27 10:16:23.684   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 586202, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-27 10:16:52.087  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:16:52.110  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:16:52.119  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:16:52.227  1518  2168 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-27 10:16:52.228  1518  2168 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-27 10:16:52.228  1518  2168 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:16:52.229  1518  2168 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:16:52.276  1518  2168 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-27 10:16:52.276  1518  2168 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-27 10:16:52.276  1518  2168 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-27 10:16:52.276  1518  2168 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-27 10:16:52.276  1518  2168 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 10:16:52.276  1518  2168 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 10:16:52.276  1518  2168 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 10:16:52.285  3380  3411 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-27 10:16:52.285  3380  3411 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-27 10:16:52.285  3380  3411 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-27 10:16:52.285  3380  3411 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-27 10:16:52.285  3380  3411 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-27 10:16:52.285  3380  3411 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-27 10:16:52.285  3380  3411 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 10:16:54.030  1518  1949 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-27 10:16:54.031  1518  1949 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 10:16:54.031  1518  1949 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:16:54.031  1518  1949 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:16:54.052  3421  4263 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-27 10:16:54.052  3421  4263 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 10:16:54.052  3421  4263 E HttpOperation: 	at jdm.a(PG:82)
07-27 10:16:54.052  3421  4263 E HttpOperation: 	at jcs.o(PG:406)
07-27 10:16:54.052  3421  4263 E HttpOperation: 	at jcn.a(PG:1379)
07-27 10:16:54.052  3421  4263 E HttpOperation: 	at jcs.i(PG:143)
07-27 10:16:54.052  3421  4263 E HttpOperation: 	at blb.a(PG:3937)
07-27 10:16:54.052  3421  4263 E HttpOperation: 	at czp.a(PG:18188)
07-27 10:16:54.052  3421  4263 E HttpOperation: 	at czp.a(PG:9081)
07-27 10:16:54.052  3421  4263 E HttpOperation: 	at czq.run(PG:1686)
07-27 10:16:54.052  3421  4263 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 10:16:54.052  3421  4263 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 10:16:54.052  3421  4263 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 10:16:54.052  3421  4263 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 10:16:54.052  3421  4263 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 10:16:54.052  3421  4263 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 10:16:54.052  3421  4263 E HttpOperation: 	at jdj.a(PG:4091)
07-27 10:16:54.052  3421  4263 E HttpOperation: 	at jdj.a(PG:1125)
07-27 10:16:54.052  3421  4263 E HttpOperation: 	at jdm.a(PG:77)
07-27 10:16:54.052  3421  4263 E HttpOperation: 	... 12 more
07-27 10:16:54.052  3421  4263 E HttpOperation: Caused by: faj: BadAuthentication
07-27 10:16:54.052  3421  4263 E HttpOperation: 	at fal.a(PG:38)
07-27 10:16:54.052  3421  4263 E HttpOperation: 	at jdj.a(PG:4089)
07-27 10:16:54.052  3421  4263 E HttpOperation: 	... 14 more
,07-27 10:16:54.097  1518  1950 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 10:16:54.097  1518  1950 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-27 10:16:54.097  1518  1950 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:16:54.097  1518  1950 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:16:54.119  3421  4263 E HttpOperation: [getmobileexperiments] Unexpected exception
07-27 10:16:54.119  3421  4263 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 10:16:54.119  3421  4263 E HttpOperation: 	at jdm.a(PG:82)
07-27 10:16:54.119  3421  4263 E HttpOperation: 	at jcs.o(PG:406)
07-27 10:16:54.119  3421  4263 E HttpOperation: 	at jcn.a(PG:1379)
07-27 10:16:54.119  3421  4263 E HttpOperation: 	at jcs.i(PG:143)
07-27 10:16:54.119  3421  4263 E HttpOperation: 	at hec.a(PG:42)
07-27 10:16:54.119  3421  4263 E HttpOperation: 	at hee.a(PG:102)
07-27 10:16:54.119  3421  4263 E HttpOperation: 	at czr.a(PG:65)
07-27 10:16:54.119  3421  4263 E HttpOperation: 	at kka.a(PG:108)
07-27 10:16:54.119  3421  4263 E HttpOperation: 	at czp.a(PG:19176)
07-27 10:16:54.119  3421  4263 E HttpOperation: 	at czp.a(PG:9081)
07-27 10:16:54.119  3421  4263 E HttpOperation: 	at czq.run(PG:1686)
07-27 10:16:54.119  3421  4263 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 10:16:54.119  3421  4263 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 10:16:54.119  3421  4263 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 10:16:54.119  3421  4263 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 10:16:54.119  3421  4263 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 10:16:54.119  3421  4263 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 10:16:54.119  3421  4263 E HttpOperation: 	at jdj.a(PG:4091)
07-27 10:16:54.119  3421  4263 E HttpOperation: 	at jdj.a(PG:1125)
07-27 10:16:54.119  3421  4263 E HttpOperation: 	at jdm.a(PG:77)
07-27 10:16:54.119  3421  4263 E HttpOperation: 	... 15 more
07-27 10:16:54.119  3421  4263 E HttpOperation: Caused by: faj: BadAuthentication
07-27 10:16:54.119  3421  4263 E HttpOperation: 	at fal.a(PG:38)
07-27 10:16:54.119  3421  4263 E HttpOperation: 	at jdj.a(PG:4089)
07-27 10:16:54.119  3421  4263 E HttpOperation: 	... 17 more
,07-27 10:16:54.119  3421  4263 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-27 10:16:54.119  3421  4263 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-27 10:16:54.119  3421  4263 E ExperimentLoader: 	at jdm.a(PG:82)
07-27 10:16:54.119  3421  4263 E ExperimentLoader: 	at jcs.o(PG:406)
07-27 10:16:54.119  3421  4263 E ExperimentLoader: 	at jcn.a(PG:1379)
07-27 10:16:54.119  3421  4263 E ExperimentLoader: 	at jcs.i(PG:143)
07-27 10:16:54.119  3421  4263 E ExperimentLoader: 	at hec.a(PG:42)
07-27 10:16:54.119  3421  4263 E ExperimentLoader: 	at hee.a(PG:102)
07-27 10:16:54.119  3421  4263 E ExperimentLoader: 	at czr.a(PG:65)
07-27 10:16:54.119  3421  4263 E ExperimentLoader: 	at kka.a(PG:108)
07-27 10:16:54.119  3421  4263 E ExperimentLoader: 	at czp.a(PG:19176)
07-27 10:16:54.119  3421  4263 E ExperimentLoader: 	at czp.a(PG:9081)
07-27 10:16:54.119  3421  4263 E ExperimentLoader: 	at czq.run(PG:1686)
07-27 10:16:54.119  3421  4263 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 10:16:54.119  3421  4263 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 10:16:54.119  3421  4263 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 10:16:54.119  3421  4263 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 10:16:54.119  3421  4263 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-27 10:16:54.119  3421  4263 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 10:16:54.119  3421  4263 E ExperimentLoader: 	at jdj.a(PG:4091)
07-27 10:16:54.119  3421  4263 E ExperimentLoader: 	at jdj.a(PG:1125)
07-27 10:16:54.119  3421  4263 E ExperimentLoader: 	at jdm.a(PG:77)
07-27 10:16:54.119  3421  4263 E ExperimentLoader: 	... 15 more
07-27 10:16:54.119  3421  4263 E ExperimentLoader: Caused by: faj: BadAuthentication
07-27 10:16:54.119  3421  4263 E ExperimentLoader: 	at fal.a(PG:38)
07-27 10:16:54.119  3421  4263 E ExperimentLoader: 	at jdj.a(PG:4089)
07-27 10:16:54.119  3421  4263 E ExperimentLoader: 	... 17 more
,07-27 10:16:54.244   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 644338, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-27 10:16:57.306   871  4192 D NetlinkSocketObserver: NeighborEvent{elapsedMs=647890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-27 10:17:24.499  3475  4267 I BooksSync: Starting books sync for 61035162, extras: ade
,07-27 10:17:24.550  3475  4268 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-27 10:17:24.563  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:17:24.566  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:17:24.605  1518  2168 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 10:17:24.605  1518  2168 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-27 10:17:24.605  1518  2168 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:17:24.605  1518  2168 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:17:24.645  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:17:24.647  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:17:24.667  1518  2207 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 10:17:24.667  1518  2207 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-27 10:17:24.667  1518  2207 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:17:24.667  1518  2207 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,07-27 10:17:24.682  3475  4268 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-27 10:17:24.683  3475  4267 E BooksSync: Soft error
,07-27 10:17:24.683  3475  4267 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 10:17:24.683  3475  4267 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-27 10:17:24.683  3475  4267 E BooksSync: Sync error
07-27 10:17:24.683  3475  4267 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 10:17:24.683  3475  4267 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-27 10:17:24.683  3475  4267 I BooksSync: Finished books sync
,07-27 10:17:24.689   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 674977, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 10:17:29.147   871  4192 D NetlinkSocketObserver: NeighborEvent{elapsedMs=679730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 10:17:59.227   871  4192 D NetlinkSocketObserver: NeighborEvent{elapsedMs=709811, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-27 10:18:31.991  2886  4271 V KeepSync: Connecting to GoogleApiClient
07-27 10:18:31.991   871   881 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-27 10:18:32.071  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:18:32.076  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:18:32.117  1518  2207 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
07-27 10:18:32.117  1518  2207 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-27 10:18:32.117  1518  2207 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:18:32.117  1518  2207 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:18:32.135  1985  4272 V BaseAuthAsyncOperation: access token request failed
07-27 10:18:32.136  2886  4271 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-27 10:18:32.186  1518  1950 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-27 10:18:32.186  1518  1950 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-27 10:18:32.186  1518  1950 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:18:32.186  1518  1950 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:18:32.203  2886  4271 E KeepSync: IOException
07-27 10:18:32.203  2886  4271 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-27 10:18:32.203  2886  4271 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-27 10:18:32.203  2886  4271 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-27 10:18:32.203  2886  4271 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-27 10:18:32.203  2886  4271 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-27 10:18:32.203  2886  4271 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-27 10:18:32.203  2886  4271 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-27 10:18:32.203  2886  4271 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-27 10:18:32.203  2886  4271 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-27 10:18:32.203  2886  4271 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-27 10:18:32.203  2886  4271 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-27 10:18:32.203  2886  4271 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-27 10:18:32.203  2886  4271 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-27 10:18:32.203  2886  4271 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-27 10:18:32.203  2886  4271 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 10:18:32.203  2886  4271 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 10:18:32.203  2886  4271 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-27 10:18:32.203  2886  4271 E KeepSync: 	... 10 more
,07-27 10:18:32.203  2886  4271 W KeepSync: Sync result 2
,07-27 10:18:32.213   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 742477, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-27 10:18:35.813   871  4192 D NetlinkSocketObserver: NeighborEvent{elapsedMs=746397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 10:19:02.630  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:19:02.633  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:19:02.684  1518  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-27 10:19:02.684  1518  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-27 10:19:02.684  1518  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:19:02.684  1518  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:19:02.729  3421  4277 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-27 10:19:02.729  3421  4277 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 10:19:02.729  3421  4277 E HttpOperation: 	at jdm.a(PG:82)
07-27 10:19:02.729  3421  4277 E HttpOperation: 	at jcs.o(PG:406)
07-27 10:19:02.729  3421  4277 E HttpOperation: 	at jcn.a(PG:1379)
07-27 10:19:02.729  3421  4277 E HttpOperation: 	at jcs.i(PG:143)
07-27 10:19:02.729  3421  4277 E HttpOperation: 	at blb.a(PG:3937)
07-27 10:19:02.729  3421  4277 E HttpOperation: 	at czp.a(PG:18188)
07-27 10:19:02.729  3421  4277 E HttpOperation: 	at czp.a(PG:9081)
07-27 10:19:02.729  3421  4277 E HttpOperation: 	at czq.run(PG:1686)
07-27 10:19:02.729  3421  4277 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 10:19:02.729  3421  4277 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 10:19:02.729  3421  4277 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 10:19:02.729  3421  4277 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 10:19:02.729  3421  4277 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 10:19:02.729  3421  4277 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 10:19:02.729  3421  4277 E HttpOperation: 	at jdj.a(PG:4091)
07-27 10:19:02.729  3421  4277 E HttpOperation: 	at jdj.a(PG:1125)
07-27 10:19:02.729  3421  4277 E HttpOperation: 	at jdm.a(PG:77)
07-27 10:19:02.729  3421  4277 E HttpOperation: 	... 12 more
07-27 10:19:02.729  3421  4277 E HttpOperation: Caused by: faj: BadAuthentication
07-27 10:19:02.729  3421  4277 E HttpOperation: 	at fal.a(PG:38)
07-27 10:19:02.729  3421  4277 E HttpOperation: 	at jdj.a(PG:4089)
07-27 10:19:02.729  3421  4277 E HttpOperation: 	... 14 more
,07-27 10:19:02.809  1518  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 10:19:02.809  1518  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-27 10:19:02.809  1518  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 10:19:02.809  1518  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:19:02.837  3421  4277 E HttpOperation: [getmobileexperiments] Unexpected exception
07-27 10:19:02.837  3421  4277 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 10:19:02.837  3421  4277 E HttpOperation: 	at jdm.a(PG:82)
07-27 10:19:02.837  3421  4277 E HttpOperation: 	at jcs.o(PG:406)
07-27 10:19:02.837  3421  4277 E HttpOperation: 	at jcn.a(PG:1379)
07-27 10:19:02.837  3421  4277 E HttpOperation: 	at jcs.i(PG:143)
07-27 10:19:02.837  3421  4277 E HttpOperation: 	at hec.a(PG:42)
07-27 10:19:02.837  3421  4277 E HttpOperation: 	at hee.a(PG:102)
07-27 10:19:02.837  3421  4277 E HttpOperation: 	at czr.a(PG:65)
07-27 10:19:02.837  3421  4277 E HttpOperation: 	at kka.a(PG:108)
07-27 10:19:02.837  3421  4277 E HttpOperation: 	at czp.a(PG:19176)
07-27 10:19:02.837  3421  4277 E HttpOperation: 	at czp.a(PG:9081)
07-27 10:19:02.837  3421  4277 E HttpOperation: 	at czq.run(PG:1686)
07-27 10:19:02.837  3421  4277 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 10:19:02.837  3421  4277 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 10:19:02.837  3421  4277 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 10:19:02.837  3421  4277 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 10:19:02.837  3421  4277 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 10:19:02.837  3421  4277 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 10:19:02.837  3421  4277 E HttpOperation: 	at jdj.a(PG:4091)
07-27 10:19:02.837  3421  4277 E HttpOperation: 	at jdj.a(PG:1125)
07-27 10:19:02.837  3421  4277 E HttpOperation: 	at jdm.a(PG:77)
07-27 10:19:02.837  3421  4277 E HttpOperation: 	... 15 more
07-27 10:19:02.837  3421  4277 E HttpOperation: Caused by: faj: BadAuthentication
07-27 10:19:02.837  3421  4277 E HttpOperation: 	at fal.a(PG:38)
07-27 10:19:02.837  3421  4277 E HttpOperation: 	at jdj.a(PG:4089)
07-27 10:19:02.837  3421  4277 E HttpOperation: 	... 17 more
,07-27 10:19:02.838  3421  4277 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-27 10:19:02.838  3421  4277 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-27 10:19:02.838  3421  4277 E ExperimentLoader: 	at jdm.a(PG:82)
07-27 10:19:02.838  3421  4277 E ExperimentLoader: 	at jcs.o(PG:406)
07-27 10:19:02.838  3421  4277 E ExperimentLoader: 	at jcn.a(PG:1379)
07-27 10:19:02.838  3421  4277 E ExperimentLoader: 	at jcs.i(PG:143)
07-27 10:19:02.838  3421  4277 E ExperimentLoader: 	at hec.a(PG:42)
07-27 10:19:02.838  3421  4277 E ExperimentLoader: 	at hee.a(PG:102)
07-27 10:19:02.838  3421  4277 E ExperimentLoader: 	at czr.a(PG:65)
07-27 10:19:02.838  3421  4277 E ExperimentLoader: 	at kka.a(PG:108)
07-27 10:19:02.838  3421  4277 E ExperimentLoader: 	at czp.a(PG:19176)
07-27 10:19:02.838  3421  4277 E ExperimentLoader: 	at czp.a(PG:9081)
07-27 10:19:02.838  3421  4277 E ExperimentLoader: 	at czq.run(PG:1686)
07-27 10:19:02.838  3421  4277 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 10:19:02.838  3421  4277 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 10:19:02.838  3421  4277 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 10:19:02.838  3421  4277 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 10:19:02.838  3421  4277 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-27 10:19:02.838  3421  4277 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 10:19:02.838  3421  4277 E ExperimentLoader: 	at jdj.a(PG:4091)
07-27 10:19:02.838  3421  4277 E ExperimentLoader: 	at jdj.a(PG:1125)
07-27 10:19:02.838  3421  4277 E ExperimentLoader: 	at jdm.a(PG:77)
07-27 10:19:02.838  3421  4277 E ExperimentLoader: 	... 15 more
07-27 10:19:02.838  3421  4277 E ExperimentLoader: Caused by: faj: BadAuthentication
07-27 10:19:02.838  3421  4277 E ExperimentLoader: 	at fal.a(PG:38)
07-27 10:19:02.838  3421  4277 E ExperimentLoader: 	at jdj.a(PG:4089)
07-27 10:19:02.838  3421  4277 E ExperimentLoader: 	... 17 more
,07-27 10:19:03.023   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 766128, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-27 10:19:23.478  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:19:23.481  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:19:23.495  4004  4280 V GoogleAuthProtoRequest: [354] a.<init>: mAccountName set to: thalitester@gmail.com
,07-27 10:19:23.526  1518  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-27 10:19:23.526  1518  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-27 10:19:23.526  1518  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:19:23.526  1518  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:19:23.553  4004  4280 W ExperimentUpdateService: [354] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-27 10:19:23.553  4004  4280 W ExperimentUpdateService: [354] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 10:19:23.553  4004  4280 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 10:19:23.553  4004  4280 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-27 10:19:23.553  4004  4280 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-27 10:19:23.553  4004  4280 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-27 10:19:23.553  4004  4280 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-27 10:19:23.553  4004  4280 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-27 10:19:23.553  4004  4280 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-27 10:19:23.553  4004  4280 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-27 10:19:23.553  4004  4280 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-27 10:19:23.553  4004  4280 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-27 10:19:33.127  3475  4283 I BooksSync: Starting books sync for 61035162, extras: ade
,07-27 10:19:33.158  3475  4284 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-27 10:19:33.170  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:19:33.171  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:19:33.199  1518  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-27 10:19:33.199  1518  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-27 10:19:33.199  1518  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 10:19:33.199  1518  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:19:33.228  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:19:33.230  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:19:33.255  1518  2168 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 10:19:33.255  1518  2168 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-27 10:19:33.255  1518  2168 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 10:19:33.255  1518  2168 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:19:33.269  3475  4284 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-27 10:19:33.270  3475  4283 E BooksSync: Soft error
07-27 10:19:33.270  3475  4283 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 10:19:33.270  3475  4283 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-27 10:19:33.270  3475  4283 E BooksSync: Sync error
07-27 10:19:33.270  3475  4283 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 10:19:33.270  3475  4283 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-27 10:19:33.270  3475  4283 I BooksSync: Finished books sync
,07-27 10:19:33.283   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 796889, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 10:20:57.667   871  4192 D NetlinkSocketObserver: NeighborEvent{elapsedMs=888251, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-27 10:21:17.093   871  4192 D NetlinkSocketObserver: NeighborEvent{elapsedMs=907677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 10:21:57.574   871  4192 D NetlinkSocketObserver: NeighborEvent{elapsedMs=948157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-27 10:22:17.040   871  4192 D NetlinkSocketObserver: NeighborEvent{elapsedMs=967623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 10:22:48.763  2886  4294 V KeepSync: Connecting to GoogleApiClient
07-27 10:22:48.763   871  1824 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-27 10:22:48.824  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:22:48.828  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:22:48.870  1518  2207 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-27 10:22:48.871  1518  2207 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,07-27 10:22:48.871  1518  2207 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:22:48.871  1518  2207 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:22:48.895  1985  4295 V BaseAuthAsyncOperation: access token request failed
,07-27 10:22:48.896  2886  4294 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-27 10:22:48.969  1518  2168 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-27 10:22:48.970  1518  2168 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-27 10:22:48.970  1518  2168 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:22:48.970  1518  2168 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:22:48.990  2886  4294 E KeepSync: IOException
07-27 10:22:48.990  2886  4294 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-27 10:22:48.990  2886  4294 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-27 10:22:48.990  2886  4294 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-27 10:22:48.990  2886  4294 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-27 10:22:48.990  2886  4294 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-27 10:22:48.990  2886  4294 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-27 10:22:48.990  2886  4294 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-27 10:22:48.990  2886  4294 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-27 10:22:48.990  2886  4294 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-27 10:22:48.990  2886  4294 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-27 10:22:48.990  2886  4294 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-27 10:22:48.990  2886  4294 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-27 10:22:48.990  2886  4294 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-27 10:22:48.990  2886  4294 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-27 10:22:48.990  2886  4294 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 10:22:48.990  2886  4294 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 10:22:48.990  2886  4294 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-27 10:22:48.990  2886  4294 E KeepSync: 	... 10 more
,07-27 10:22:48.990  2886  4294 W KeepSync: Sync result 2
,07-27 10:22:49.004   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 999213, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-27 10:23:19.428  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:23:19.432  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:23:19.463  1518  1949 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-27 10:23:19.463  1518  1949 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 10:23:19.463  1518  1949 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:23:19.463  1518  1949 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:23:19.488  3421  4298 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-27 10:23:19.488  3421  4298 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 10:23:19.488  3421  4298 E HttpOperation: 	at jdm.a(PG:82)
07-27 10:23:19.488  3421  4298 E HttpOperation: 	at jcs.o(PG:406)
07-27 10:23:19.488  3421  4298 E HttpOperation: 	at jcn.a(PG:1379)
07-27 10:23:19.488  3421  4298 E HttpOperation: 	at jcs.i(PG:143)
07-27 10:23:19.488  3421  4298 E HttpOperation: 	at blb.a(PG:3937)
07-27 10:23:19.488  3421  4298 E HttpOperation: 	at czp.a(PG:18188)
07-27 10:23:19.488  3421  4298 E HttpOperation: 	at czp.a(PG:9081)
07-27 10:23:19.488  3421  4298 E HttpOperation: 	at czq.run(PG:1686)
07-27 10:23:19.488  3421  4298 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 10:23:19.488  3421  4298 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 10:23:19.488  3421  4298 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 10:23:19.488  3421  4298 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 10:23:19.488  3421  4298 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 10:23:19.488  3421  4298 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 10:23:19.488  3421  4298 E HttpOperation: 	at jdj.a(PG:4091)
07-27 10:23:19.488  3421  4298 E HttpOperation: 	at jdj.a(PG:1125)
07-27 10:23:19.488  3421  4298 E HttpOperation: 	at jdm.a(PG:77)
07-27 10:23:19.488  3421  4298 E HttpOperation: 	... 12 more
07-27 10:23:19.488  3421  4298 E HttpOperation: Caused by: faj: BadAuthentication
07-27 10:23:19.488  3421  4298 E HttpOperation: 	at fal.a(PG:38)
07-27 10:23:19.488  3421  4298 E HttpOperation: 	at jdj.a(PG:4089)
07-27 10:23:19.488  3421  4298 E HttpOperation: 	... 14 more
,07-27 10:23:19.573  1518  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 10:23:19.573  1518  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 10:23:19.573  1518  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:23:19.573  1518  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:23:19.594  3421  4298 E HttpOperation: [getmobileexperiments] Unexpected exception
07-27 10:23:19.594  3421  4298 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 10:23:19.594  3421  4298 E HttpOperation: 	at jdm.a(PG:82)
07-27 10:23:19.594  3421  4298 E HttpOperation: 	at jcs.o(PG:406)
07-27 10:23:19.594  3421  4298 E HttpOperation: 	at jcn.a(PG:1379)
07-27 10:23:19.594  3421  4298 E HttpOperation: 	at jcs.i(PG:143)
07-27 10:23:19.594  3421  4298 E HttpOperation: 	at hec.a(PG:42)
07-27 10:23:19.594  3421  4298 E HttpOperation: 	at hee.a(PG:102)
07-27 10:23:19.594  3421  4298 E HttpOperation: 	at czr.a(PG:65)
07-27 10:23:19.594  3421  4298 E HttpOperation: 	at kka.a(PG:108)
07-27 10:23:19.594  3421  4298 E HttpOperation: 	at czp.a(PG:19176)
07-27 10:23:19.594  3421  4298 E HttpOperation: 	at czp.a(PG:9081)
07-27 10:23:19.594  3421  4298 E HttpOperation: 	at czq.run(PG:1686)
07-27 10:23:19.594  3421  4298 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 10:23:19.594  3421  4298 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 10:23:19.594  3421  4298 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 10:23:19.594  3421  4298 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 10:23:19.594  3421  4298 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 10:23:19.594  3421  4298 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 10:23:19.594  3421  4298 E HttpOperation: 	at jdj.a(PG:4091)
07-27 10:23:19.594  3421  4298 E HttpOperation: 	at jdj.a(PG:1125)
07-27 10:23:19.594  3421  4298 E HttpOperation: 	at jdm.a(PG:77)
07-27 10:23:19.594  3421  4298 E HttpOperation: 	... 15 more
07-27 10:23:19.594  3421  4298 E HttpOperation: Caused by: faj: BadAuthentication
07-27 10:23:19.594  3421  4298 E HttpOperation: 	at fal.a(PG:38)
07-27 10:23:19.594  3421  4298 E HttpOperation: 	at jdj.a(PG:4089)
07-27 10:23:19.594  3421  4298 E HttpOperation: 	... 17 more
,07-27 10:23:19.594  3421  4298 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-27 10:23:19.594  3421  4298 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-27 10:23:19.594  3421  4298 E ExperimentLoader: 	at jdm.a(PG:82)
07-27 10:23:19.594  3421  4298 E ExperimentLoader: 	at jcs.o(PG:406)
07-27 10:23:19.594  3421  4298 E ExperimentLoader: 	at jcn.a(PG:1379)
07-27 10:23:19.594  3421  4298 E ExperimentLoader: 	at jcs.i(PG:143)
07-27 10:23:19.594  3421  4298 E ExperimentLoader: 	at hec.a(PG:42)
07-27 10:23:19.594  3421  4298 E ExperimentLoader: 	at hee.a(PG:102)
07-27 10:23:19.594  3421  4298 E ExperimentLoader: 	at czr.a(PG:65)
07-27 10:23:19.594  3421  4298 E ExperimentLoader: 	at kka.a(PG:108)
07-27 10:23:19.594  3421  4298 E ExperimentLoader: 	at czp.a(PG:19176)
07-27 10:23:19.594  3421  4298 E ExperimentLoader: 	at czp.a(PG:9081)
07-27 10:23:19.594  3421  4298 E ExperimentLoader: 	at czq.run(PG:1686)
07-27 10:23:19.594  3421  4298 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 10:23:19.594  3421  4298 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 10:23:19.594  3421  4298 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 10:23:19.594  3421  4298 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 10:23:19.594  3421  4298 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-27 10:23:19.594  3421  4298 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 10:23:19.594  3421  4298 E ExperimentLoader: 	at jdj.a(PG:4091)
07-27 10:23:19.594  3421  4298 E ExperimentLoader: 	at jdj.a(PG:1125)
07-27 10:23:19.594  3421  4298 E ExperimentLoader: 	at jdm.a(PG:77)
07-27 10:23:19.594  3421  4298 E ExperimentLoader: 	... 15 more
07-27 10:23:19.594  3421  4298 E ExperimentLoader: Caused by: faj: BadAuthentication
07-27 10:23:19.594  3421  4298 E ExperimentLoader: 	at fal.a(PG:38)
07-27 10:23:19.594  3421  4298 E ExperimentLoader: 	at jdj.a(PG:4089)
07-27 10:23:19.594  3421  4298 E ExperimentLoader: 	... 17 more
,07-27 10:23:19.686   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1016208, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-27 10:23:49.929  3475  4301 I BooksSync: Starting books sync for 61035162, extras: ade
,07-27 10:23:49.952  3475  4302 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-27 10:23:49.965  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:23:49.967  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:23:50.004  1518  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 10:23:50.004  1518  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-27 10:23:50.004  1518  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 10:23:50.004  1518  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:23:50.030  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:23:50.032  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:23:50.054  1518  2168 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 10:23:50.054  1518  2168 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-27 10:23:50.054  1518  2168 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:23:50.054  1518  2168 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:23:50.070  3475  4302 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-27 10:23:50.071  3475  4301 E BooksSync: Soft error
07-27 10:23:50.071  3475  4301 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 10:23:50.071  3475  4301 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-27 10:23:50.071  3475  4301 E BooksSync: Sync error
07-27 10:23:50.071  3475  4301 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 10:23:50.071  3475  4301 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-27 10:23:50.071  3475  4301 I BooksSync: Finished books sync
,07-27 10:23:50.079   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1047100, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 10:26:28.405   871   883 I UsageStatsService: User[0] Flushing usage stats to disk
,07-27 10:26:53.358  1985  4313 I EventLogService: Opted in for usage reporting
,07-27 10:26:53.359  1985  4313 I EventLogService: Aggregate from 1469606119024 (log), 1469606119024 (data)
,07-27 10:26:53.398  1985  4313 W EventLogAggregator: Unknown tag: snet_gcore
07-27 10:26:53.398  1985  4313 W EventLogAggregator: Unknown tag: snet_launch_service
,07-27 10:26:53.533  1985  4313 I ServiceDumpSys: dumping service [account]
,07-27 10:26:58.320   871  4192 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1248903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-27 10:27:01.626   871  4192 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1252210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 10:27:23.747  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:27:23.748  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:27:23.762  4004  4317 V GoogleAuthProtoRequest: [355] a.<init>: mAccountName set to: thalitester@gmail.com
,07-27 10:27:23.823  1518  2168 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-27 10:27:23.824  1518  2168 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-27 10:27:23.824  1518  2168 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:27:23.824  1518  2168 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:27:23.843  4004  4317 W ExperimentUpdateService: [355] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-27 10:27:23.844  4004  4317 W ExperimentUpdateService: [355] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 10:27:23.844  4004  4317 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 10:27:23.844  4004  4317 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-27 10:27:23.844  4004  4317 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-27 10:27:23.844  4004  4317 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-27 10:27:23.844  4004  4317 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-27 10:27:23.844  4004  4317 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-27 10:27:23.844  4004  4317 W ExperimentUpdateService: 	,at com.google.android.flib.a.a.a(SourceFile:167)
07-27 10:27:23.844  4004  4317 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-27 10:27:23.844  4004  4317 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-27 10:27:23.844  4004  4317 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-27 10:31:22.077  2886  4330 V KeepSync: Connecting to GoogleApiClient
,07-27 10:31:22.078   871  1824 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-27 10:31:22.136  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:31:22.141  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:31:22.177  1518  1950 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-27 10:31:22.177  1518  1950 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-27 10:31:22.178  1518  1950 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:31:22.178  1518  1950 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:31:22.203  1985  4331 V BaseAuthAsyncOperation: access token request failed
,07-27 10:31:22.204  2886  4330 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-27 10:31:22.271  1518  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-27 10:31:22.271  1518  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-27 10:31:22.271  1518  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:31:22.271  1518  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:31:22.292  2886  4330 E KeepSync: IOException
07-27 10:31:22.292  2886  4330 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-27 10:31:22.292  2886  4330 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-27 10:31:22.292  2886  4330 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-27 10:31:22.292  2886  4330 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-27 10:31:22.292  2886  4330 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-27 10:31:22.292  2886  4330 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-27 10:31:22.292  2886  4330 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-27 10:31:22.292  2886  4330 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-27 10:31:22.292  2886  4330 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-27 10:31:22.292  2886  4330 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-27 10:31:22.292  2886  4330 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-27 10:31:22.292  2886  4330 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-27 10:31:22.292  2886  4330 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-27 10:31:22.292  2886  4330 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-27 10:31:22.292  2886  4330 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 10:31:22.292  2886  4330 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 10:31:22.292  2886  4330 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-27 10:31:22.292  2886  4330 E KeepSync: 	... 10 more
07-27 10:31:22.292  2886  4330 W KeepSync: Sync result 2
,07-27 10:31:22.308   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1512420, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-27 10:31:52.710  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:31:52.713  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:31:52.771  1518  1950 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 10:31:52.771  1518  1950 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-27 10:31:52.771  1518  1950 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 10:31:52.771  1518  1950 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:31:52.788  3421  4334 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-27 10:31:52.788  3421  4334 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 10:31:52.788  3421  4334 E HttpOperation: 	at jdm.a(PG:82)
07-27 10:31:52.788  3421  4334 E HttpOperation: 	at jcs.o(PG:406)
07-27 10:31:52.788  3421  4334 E HttpOperation: 	at jcn.a(PG:1379)
07-27 10:31:52.788  3421  4334 E HttpOperation: 	at jcs.i(PG:143)
07-27 10:31:52.788  3421  4334 E HttpOperation: 	at blb.a(PG:3937)
07-27 10:31:52.788  3421  4334 E HttpOperation: 	at czp.a(PG:18188)
07-27 10:31:52.788  3421  4334 E HttpOperation: 	at czp.a(PG:9081)
07-27 10:31:52.788  3421  4334 E HttpOperation: 	at czq.run(PG:1686)
07-27 10:31:52.788  3421  4334 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 10:31:52.788  3421  4334 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 10:31:52.788  3421  4334 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 10:31:52.788  3421  4334 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 10:31:52.788  3421  4334 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 10:31:52.788  3421  4334 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 10:31:52.788  3421  4334 E HttpOperation: 	at jdj.a(PG:4091)
07-27 10:31:52.788  3421  4334 E HttpOperation: 	at jdj.a(PG:1125)
07-27 10:31:52.788  3421  4334 E HttpOperation: 	at jdm.a(PG:77)
07-27 10:31:52.788  3421  4334 E HttpOperation: 	... 12 more
07-27 10:31:52.788  3421  4334 E HttpOperation: Caused by: faj: BadAuthentication
07-27 10:31:52.788  3421  4334 E HttpOperation: 	at fal.a(PG:38)
07-27 10:31:52.788  3421  4334 E HttpOperation: 	at jdj.a(PG:4089)
07-27 10:31:52.788  3421  4334 E HttpOperation: ,	... 14 more
,07-27 10:31:52.867  1518  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 10:31:52.867  1518  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 10:31:52.867  1518  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:31:52.867  1518  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,07-27 10:31:52.887  3421  4334 E HttpOperation: [getmobileexperiments] Unexpected exception
07-27 10:31:52.887  3421  4334 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 10:31:52.887  3421  4334 E HttpOperation: 	at jdm.a(PG:82)
07-27 10:31:52.887  3421  4334 E HttpOperation: 	at jcs.o(PG:406)
07-27 10:31:52.887  3421  4334 E HttpOperation: 	at jcn.a(PG:1379)
07-27 10:31:52.887  3421  4334 E HttpOperation: 	at jcs.i(PG:143)
07-27 10:31:52.887  3421  4334 E HttpOperation: 	at hec.a(PG:42)
07-27 10:31:52.887  3421  4334 E HttpOperation: 	at hee.a(PG:102)
07-27 10:31:52.887  3421  4334 E HttpOperation: 	at czr.a(PG:65)
07-27 10:31:52.887  3421  4334 E HttpOperation: 	at kka.a(PG:108)
07-27 10:31:52.887  3421  4334 E HttpOperation: 	at czp.a(PG:19176)
07-27 10:31:52.887  3421  4334 E HttpOperation: 	at czp.a(PG:9081)
07-27 10:31:52.887  3421  4334 E HttpOperation: 	at czq.run(PG:1686)
07-27 10:31:52.887  3421  4334 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
,07-27 10:31:52.887  3421  4334 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 10:31:52.887  3421  4334 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 10:31:52.887  3421  4334 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 10:31:52.887  3421  4334 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 10:31:52.887  3421  4334 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 10:31:52.887  3421  4334 E HttpOperation: 	at jdj.a(PG:4091)
07-27 10:31:52.887  3421  4334 E HttpOperation: 	at jdj.a(PG:1125)
07-27 10:31:52.887  3421  4334 E HttpOperation: 	at jdm.a(PG:77)
07-27 10:31:52.887  3421  4334 E HttpOperation: 	... 15 more
07-27 10:31:52.887  3421  4334 E HttpOperation: Caused by: faj: BadAuthentication
07-27 10:31:52.887  3421  4334 E HttpOperation: 	at fal.a(PG:38)
07-27 10:31:52.887  3421  4334 E HttpOperation: 	at jdj.a(PG:4089)
07-27 10:31:52.887  3421  4334 E HttpOperation: 	... 17 more
07-27 10:31:52.887  3421  4334 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-27 10:31:52.887  3421  4334 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-27 10:31:52.887  3421  4334 E ExperimentLoader: 	at jdm.a(PG:82)
07-27 10:31:52.887  3421  4334 E ExperimentLoader: 	at jcs.o(PG:406)
07-27 10:31:52.887  3421  4334 E ExperimentLoader: 	at jcn.a(PG:1379)
07-27 10:31:52.887  3421  4334 E ExperimentLoader: 	at jcs.i(PG:143)
07-27 10:31:52.887  3421  4334 E ExperimentLoader: 	at hec.a(PG:42)
,07-27 10:31:52.887  3421  4334 E ExperimentLoader: 	at hee.a(PG:102)
07-27 10:31:52.887  3421  4334 E ExperimentLoader: 	at czr.a(PG:65)
07-27 10:31:52.887  3421  4334 E ExperimentLoader: 	at kka.a(PG:108)
07-27 10:31:52.887  3421  4334 E ExperimentLoader: 	at czp.a(PG:19176)
07-27 10:31:52.887  3421  4334 E ExperimentLoader: 	at czp.a(PG:9081)
07-27 10:31:52.887  3421  4334 E ExperimentLoader: 	at czq.run(PG:1686)
07-27 10:31:52.887  3421  4334 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 10:31:52.887  3421  4334 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 10:31:52.887  3421  4334 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 10:31:52.887  3421  4334 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 10:31:52.887  3421  4334 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-27 10:31:52.887  3421  4334 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 10:31:52.887  3421  4334 E ExperimentLoader: 	at jdj.a(PG:4091)
07-27 10:31:52.887  3421  4334 E ExperimentLoader: 	at jdj.a(PG:1125)
07-27 10:31:52.887  3421  4334 E ExperimentLoader: 	at jdm.a(PG:77)
07-27 10:31:52.887  3421  4334 E ExperimentLoader: 	... 15 more
07-27 10:31:52.887  3421  4334 E ExperimentLoader: Caused by: faj: BadAuthentication
07-27 10:31:52.887  3421  4334 E ExperimentLoader: 	at fal.a(PG:38)
07-27 10:31:52.887  3421  4334 E ExperimentLoader: 	at jdj.a(PG:4089)
07-27 10:31:52.887  3421  4334 E ExperimentLoader: 	... 17 more
,07-27 10:31:53.041   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1515471, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-27 10:32:23.252  3475  4338 I BooksSync: Starting books sync for 61035162, extras: ade
,07-27 10:32:23.290  3475  4339 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-27 10:32:23.306  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:32:23.311  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:32:23.340  1518  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-27 10:32:23.340  1518  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-27 10:32:23.340  1518  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 10:32:23.340  1518  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:32:23.378  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:32:23.383  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 10:32:23.421  1518  2207 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 10:32:23.421  1518  2207 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-27 10:32:23.421  1518  2207 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 10:32:23.422  1518  2207 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 10:32:23.446  3475  4339 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 10:32:23.448  3475  4338 E BooksSync: Soft error
07-27 10:32:23.448  3475  4338 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 10:32:23.448  3475  4338 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-27 10:32:23.448  3475  4338 E BooksSync: Sync error
07-27 10:32:23.448  3475  4338 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 10:32:23.448  3475  4338 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-27 10:32:23.448  3475  4338 I BooksSync: Finished books sync
,07-27 10:32:23.459   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1547155, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,TIME-OUT KILL (timeout was 1400000ms),07-27 10:34:48.641  4347  4347 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-27 10:34:48.646  4347  4347 D AndroidRuntime: CheckJNI is OFF
07-27 10:34:48.682  4347  4347 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-27 10:34:48.723  4347  4347 I Radio-JNI: register_android_hardware_Radio DONE
07-27 10:34:48.743  4347  4347 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-27 10:34:48.757   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
07-27 10:34:48.758   871   884 I ActivityManager: Killing 3717:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
07-27 10:34:48.851   871  1402 D GraphicsStats: Buffer count: 2
07-27 10:34:48.852   871  1759 I WindowState: WIN DEATH: Window{b9ea1f5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-27 10:34:48.855   871  1317 D WifiService: Client connection lost with reason: 4
07-27 10:34:48.878   871   895 W PackageSettings: Skipping PackageSetting{e493ad4 com.example.hello/10273} due to missing metadata
07-27 10:34:48.901   871   884 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
07-27 10:34:48.901   871   884 W PackageManager: Package com.test.thalitest is missing; assuming frozen
07-27 10:34:48.902   871   895 I art     : Starting a blocking GC Explicit
07-27 10:34:48.910   871   884 E ActivityManager: Failure starting process com.test.thalitest
07-27 10:34:48.910   871   884 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
07-27 10:34:48.910   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
07-27 10:34:48.910   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
07-27 10:34:48.910   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
07-27 10:34:48.910   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
07-27 10:34:48.910   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
07-27 10:34:48.910   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
07-27 10:34:48.910   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
07-27 10:34:48.910   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
07-27 10:34:48.910   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
07-27 10:34:48.910   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
07-27 10:34:48.910   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
07-27 10:34:48.910   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
07-27 10:34:48.910   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
07-27 10:34:48.910   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
07-27 10:34:48.910   871   884 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 10:34:48.910   871   884 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
07-27 10:34:48.910   871   884 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 10:34:48.910   871   884 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-27 10:34:48.913   871   884 I ActivityManager:   Force finishing activity ActivityRecord{7e3e4f6 u0 com.test.thalitest/.MainActivity t2}
07-27 10:34:48.930   871  1402 W ActivityManager: Spurious death for ProcessRecord{4c8002f 0:com.test.thalitest/u0a0}, curProc for 3717: null
07-27 10:34:48.970   871   895 I art     : Explicit concurrent mark sweep GC freed 22959(1496KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 29MB/43MB, paused 1.164ms total 66.844ms
07-27 10:34:48.994   871   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
07-27 10:34:48.996  4347  4347 I art     : System.exit called, status: 0
07-27 10:34:48.996  4347  4347 I AndroidRuntime: VM exiting with result code 0.
07-27 10:34:49.001   871   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
07-27 10:34:49.015   871   884 I ActivityManager: Exiting empty application process com.test.thalitest (null)
07-27 10:34:49.022  4135  4135 D BluetoothMapAppObserver: onReceive
07-27 10:34:49.022  4135  4135 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
07-27 10:34:49.024  1974  2069 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-27 10:34:49.027   871  1306 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-27 10:34:49.028  3532  3532 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
07-27 10:34:49.040  1665  1665 I Keyboard.Facilitator: resetDictionaries() : en_US
07-27 10:34:49.061  1665  4359 I Keyboard.Facilitator.DecoderInitializer: run()
07-27 10:34:49.065  1665  4359 I Decoder : createOrResetDecoder
07-27 10:34:49.074  1737  1737 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
07-27 10:34:49.086   871  1373 I ActivityManager: Start proc 4361:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
07-27 10:34:49.098  1518  1518 I ConfigService: onCreate
07-27 10:34:49.116   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-27 10:34:49.140  1518  4373 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/config.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
07-27 10:34:49.141  4361  4361 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
07-27 10:34:49.149   871   881 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3717 uid 10000
07-27 10:34:49.150  1665  1665 I Keyboard.Facilitator: onFinishInput()
07-27 10:34:49.153  1753  1826 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
07-27 10:34:49.153   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
07-27 10:34:49.154   871   883 E PackageManager: Failed to write settings, restoring backup
07-27 10:34:49.154   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
07-27 10:34:49.154   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
07-27 10:34:49.154   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
07-27 10:34:49.154   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
07-27 10:34:49.154   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
07-27 10:34:49.154   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 10:34:49.154   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
07-27 10:34:49.154   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 10:34:49.158   871   884 E DropBoxManagerService: Can't write: system_server_wtf
07-27 10:34:49.158   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
07-27 10:34:49.158   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-27 10:34:49.158   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-27 10:34:49.158   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-27 10:34:49.158   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-27 10:34:49.158   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-27 10:34:49.158   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-27 10:34:49.158   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
07-27 10:34:49.158   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
07-27 10:34:49.158   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
07-27 10:34:49.158   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 10:34:49.158   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 10:34:49.158   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
07-27 10:34:49.158   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 10:34:49.158   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-27 10:34:49.158   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-27 10:34:49.158   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-27 10:34:49.158   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-27 10:34:49.158   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-27 10:34:49.158   871   884 E DropBoxManagerService: 	... 13 more
07-27 10:34:49.166   871   882 I ActivityManager: Start proc 4374:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
07-27 10:34:49.166  1753  1826 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
07-27 10:34:49.166  1753  1826 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1753
07-27 10:34:49.166  1753  1826 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-27 10:34:49.166  1753  1826 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-27 10:34:49.166  1753  1826 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-27 10:34:49.166  1753  1826 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-27 10:34:49.166  1753  1826 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-27 10:34:49.166  1753  1826 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-27 10:34:49.166  1753  1826 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
07-27 10:34:49.166  1753  1826 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
07-27 10:34:49.166  1753  1826 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 10:34:49.166  1753  1826 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 10:34:49.166  1753  1826 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-27 10:34:49.166  1753  1826 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 10:34:49.169   871  1796 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-27 10:34:49.169   871  4380 E DropBoxManagerService: Can't write: system_app_crash
07-27 10:34:49.169   871  4380 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
07-27 10:34:49.169   871  4380 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-27 10:34:49.169   871  4380 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-27 10:34:49.169   871  4380 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-27 10:34:49.169   871  4380 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-27 10:34:49.169   871  4380 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-27 10:34:49.169   871  4380 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-27 10:34:49.169   871  4380 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-27 10:34:49.169   871  4380 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-27 10:34:49.169   871  4380 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-27 10:34:49.169   871  4380 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-27 10:34:49.169   871  4380 E DropBoxManagerService: 	... 5 more
07-27 10:34:49.173  1753  1826 I Process : Sending signal. PID: 1753 SIG: 9
07-27 10:34:49.178  1665  4359 I Keyboard.Facilitator.MainLanguageModelLoader: run()
07-27 10:34:49.215  1665  4359 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
07-27 10:34:49.216  1665  4359 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
07-27 10:34:49.216  1665  4359 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
07-27 10:34:49.218  1665  4359 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
07-27 10:34:49.218  1665  4359 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
07-27 10:34:49.218  1665  4359 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
07-27 10:34:49.218  1665  4359 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
07-27 10:34:49.219  1665  4359 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
07-27 10:34:49.219  1665  4359 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
07-27 10:34:49.219  1665  4359 I Keyboard.Facilitator.Delight2FileSweeper: run()
07-27 10:34:49.219  1665  4359 I Keyboard.Facilitator.RecurringTaskScheduler: run()
07-27 10:34:49.219  1665  4359 I StatsUtilsManager: startPeriodStatsRecorder() : Success
07-27 10:34:49.219  1665  4359 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
07-27 10:34:49.228  4361  4361 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
07-27 10:34:49.240   871  3634 D GraphicsStats: Buffer count: 1
07-27 10:34:49.240   871  1825 I WindowState: WIN DEATH: Window{f24b73d u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
07-27 10:34:49.245   871   882 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1753) has died
07-27 10:34:49.246   871   882 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
07-27 10:34:49.247   871   882 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
07-27 10:34:49.267   871   884 I ActivityManager: Start proc 4393:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-27 10:34:49.280   871  1824 I ActivityManager: Start proc 4406:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
07-27 10:34:49.305  4361  4401 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
07-27 10:34:49.313  4406  4406 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 10:34:49.317  4393  4393 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 10:34:49.317  4393  4393 D AndroidRuntime: Shutting down VM
07-27 10:34:49.327  4393  4393 E AndroidRuntime: FATAL EXCEPTION: main
07-27 10:34:49.327  4393  4393 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4393
07-27 10:34:49.327  4393  4393 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
07-27 10:34:49.327  4393  4393 E AndroidRuntime: 	... 10 more
07-27 10:34:49.330   871  1696 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-27 10:34:49.331  4393  4393 I Process : Sending signal. PID: 4393 SIG: 9
07-27 10:34:49.337   871  4419 E DropBoxManagerService: Can't write: system_app_crash
07-27 10:34:49.337   871  4419 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
07-27 10:34:49.337   871  4419 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-27 10:34:49.337   871  4419 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-27 10:34:49.337   871  4419 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-27 10:34:49.337   871  4419 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-27 10:34:49.337   871  4419 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-27 10:34:49.337   871  4419 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-27 10:34:49.337   871  4419 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-27 10:34:49.337   871  4419 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-27 10:34:49.337   871  4419 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-27 10:34:49.337   871  4419 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-27 10:34:49.337   871  4419 E DropBoxManagerService: 	... 5 more
07-27 10:34:49.339  1985  4416 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
07-27 10:34:49.346  1985  4416 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
07-27 10:34:49.352  1985  4416 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
07-27 10:34:49.353  1985  4416 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
07-27 10:34:49.356  1518  1518 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
07-27 10:34:49.357  1518  1518 D AndroidRuntime: Shutting down VM
07-27 10:34:49.357  1518  1518 E AndroidRuntime: FATAL EXCEPTION: main
07-27 10:34:49.357  1518  1518 E AndroidRuntime: Process: com.google.process.gapps, PID: 1518
07-27 10:34:49.357  1518  1518 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-27 10:34:49.357  1518  1518 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
07-27 10:34:49.357  1518  1518 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
07-27 10:34:49.357  1518  1518 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
07-27 10:34:49.357  1518  1518 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 10:34:49.357  1518  1518 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-27 10:34:49.357  1518  1518 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 10:34:49.357  1518  1518 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 10:34:49.357  1518  1518 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 10:34:49.357  1518  1518 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 10:34:49.357  1518  1518 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-27 10:34:49.357  1518  1518 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-27 10:34:49.357  1518  1518 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-27 10:34:49.357  1518  1518 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-27 10:34:49.357  1518  1518 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-27 10:34:49.357  1518  1518 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-27 10:34:49.357  1518  1518 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
07-27 10:34:49.357  1518  1518 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
07-27 10:34:49.357  1518  1518 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
07-27 10:34:49.357  1518  1518 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
07-27 10:34:49.357  1518  1518 E AndroidRuntime: 	... 8 more
07-27 10:34:49.358   871  1825 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4393) has died
07-27 10:34:49.359   871  1825 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
07-27 10:34:49.360  4361  4388 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
07-27 10:34:49.360  4361  4388 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 10:34:49.360  4361  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 10:34:49.360  4361  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-27 10:34:49.360  4361  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-27 10:34:49.360  4361  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 10:34:49.360  4361  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 10:34:49.360  4361  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 10:34:49.360  4361  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-27 10:34:49.360  4361  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-27 10:34:49.360  4361  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-27 10:34:49.360  4361  4388 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-27 10:34:49.360  4361  4388 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-27 10:34:49.360  4361  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 10:34:49.360  4361  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-27 10:34:49.360  4361  4388 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
07-27 10:34:49.360  4361  4388 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
07-27 10:34:49.360  4361  4388 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
07-27 10:34:49.360  4361  4388 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
07-27 10:34:49.360  4361  4388 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 10:34:49.360  4361  4388 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-27 10:34:49.360  4361  4388 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 10:34:49.360  4361  4388 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
07-27 10:34:49.360  4361  4388 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 10:34:49.360  4361  4388 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 10:34:49.360  4361  4388 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-27 10:34:49.360  4361  4388 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-27 10:34:49.360  4361  4388 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 10:34:49.360  4361  4388 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 10:34:49.360  4361  4388 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 10:34:49.360  4361  4388 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-27 10:34:49.360  4361  4388 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-27 10:34:49.360  4361  4388 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-27 10:34:49.360  4361  4388 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-27 10:34:49.360  4361  4388 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-27 10:34:49.360  4361  4388 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 10:34:49.360  4361  4388 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-27 10:34:49.360  4361  4388 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
07-27 10:34:49.360  4361  4388 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
07-27 10:34:49.360  4361  4388 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
07-27 10:34:49.360  4361  4388 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
07-27 10:34:49.360  4361  4388 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 10:34:49.360  4361  4388 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
07-27 10:34:49.360  4361  4388 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 10:34:49.367   871  4423 E DropBoxManagerService: Can't write: system_app_crash
07-27 10:34:49.367   871  4423 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
07-27 10:34:49.367   871  4423 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-27 10:34:49.367   871  4423 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-27 10:34:49.367   871  4423 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-27 10:34:49.367   871  4423 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-27 10:34:49.367   871  4423 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-27 10:34:49.367   871  4423 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-27 10:34:49.367   871  4423 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-27 10:34:49.367   871  4423 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-27 10:34:49.367   871  4423 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-27 10:34:49.367   871  4423 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-27 10:34:49.367   871  4423 E DropBoxManagerService: 	... 5 more
07-27 10:34:49.375   871   884 I ActivityManager: Start proc 4424:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-27 10:34:49.378  1518  1518 I Process : Sending signal. PID: 1518 SIG: 9
07-27 10:34:49.380   871   882 I ActivityManager: Killing 1807:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
07-27 10:34:49.419  4361  4388 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
07-27 10:34:49.423  4361  4401 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
07-27 10:34:49.423  4361  4401 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 10:34:49.423  4361  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 10:34:49.423  4361  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-27 10:34:49.423  4361  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-27 10:34:49.423  4361  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 10:34:49.423  4361  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 10:34:49.423  4361  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 10:34:49.423  4361  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-27 10:34:49.423  4361  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-27 10:34:49.423  4361  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-27 10:34:49.423  4361  4401 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-27 10:34:49.423  4361  4401 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-27 10:34:49.423  4361  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 10:34:49.423  4361  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 10:34:49.423  4361  4401 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
07-27 10:34:49.423  4361  4401 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
07-27 10:34:49.423  4361  4401 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
07-27 10:34:49.423  4361  4401 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
07-27 10:34:49.423  4361  4401 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
07-27 10:34:49.423  4361  4401 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-27 10:34:49.423  4361  4401 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-27 10:34:49.423  4361  4401 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 10:34:49.423  4361  4401 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-27 10:34:49.423  4361  4401 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 10:34:49.424  4361  4401 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
07-27 10:34:49.424  4361  4401 E AndroidRuntime: Process: android.process.acore, PID: 4361
07-27 10:34:49.424  4361  4401 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 10:34:49.424  4361  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 10:34:49.424  4361  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-27 10:34:49.424  4361  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-27 10:34:49.424  4361  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 10:34:49.424  4361  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 10:34:49.424  4361  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 10:34:49.424  4361  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-27 10:34:49.424  4361  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-27 10:34:49.424  4361  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-27 10:34:49.424  4361  4401 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-27 10:34:49.424  4361  4401 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-27 10:34:49.424  4361  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 10:34:49.424  4361  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 10:34:49.424  4361  4401 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
07-27 10:34:49.424  4361  4401 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
07-27 10:34:49.424  4361  4401 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
07-27 10:34:49.424  4361  4401 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
07-27 10:34:49.424  4361  4401 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
07-27 10:34:49.424  4361  4401 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-27 10:34:49.424  4361  4401 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-27 10:34:49.424  4361  4401 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 10:34:49.424  4361  4401 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-27 10:34:49.424  4361  4401 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 10:34:49.425  4361  4388 I Process : Sending signal. PID: 4361 SIG: 9
07-27 10:34:49.430   871  1317 D WifiService: Client connection lost with reason: 4
07-27 10:34:49.431   871  1317 D WifiService: Client connection lost with reason: 4
07-27 10:34:49.440   871  1796 I ActivityManager: Process com.google.process.gapps (pid 1518) has died
07-27 10:34:49.441   871  1796 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
07-27 10:34:49.441   871  1796 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
07-27 10:34:49.442   871  1796 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 21000ms
07-27 10:34:49.442   871  1796 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 31000ms
07-27 10:34:49.450  1985  1985 W RocketImpressions: ClearcutLogger connection suspended: 1

```
