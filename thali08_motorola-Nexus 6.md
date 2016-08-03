#### Test 79689775e3527ba_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
08-03 21:22:16.751   870  2108 D NetlinkSocketObserver: NeighborEvent{elapsedMs=361277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-03 21:22:17.396  3709  3709 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-03 21:22:17.401  3709  3709 D AndroidRuntime: CheckJNI is OFF
08-03 21:22:17.444  3709  3709 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-03 21:22:17.494  3709  3709 I Radio-JNI: register_android_hardware_Radio DONE
08-03 21:22:17.516  3709  3709 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-03 21:22:17.520   870  1380 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-03 21:22:17.563   870  1380 I ActivityManager: Start proc 3718:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-03 21:22:17.567  3709  3709 D AndroidRuntime: Shutting down VM
08-03 21:22:17.664  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-03 21:22:17.665  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-03 21:22:17.678  3718  3718 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-03 21:22:17.681  3599  3730 V GoogleAuthProtoRequest: [312] a.<init>: mAccountName set to: thalitester@gmail.com
08-03 21:22:17.703  3718  3718 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-03 21:22:17.707  1500  2044 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-03 21:22:17.707  1500  2044 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-03 21:22:17.707  1500  2044 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:22:17.707  1500  2044 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-03 21:22:17.709  3718  3718 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2232-2235)
08-03 21:22:17.709  3718  3718 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 21:22:17.720  3718  3718 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8b1bb27}
08-03 21:22:17.721  3718  3718 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 21:22:17.721  3718  3718 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-03 21:22:17.722  3599  3730 W ExperimentUpdateService: [312] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
08-03 21:22:17.722  3599  3730 W ExperimentUpdateService: [312] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-03 21:22:17.722  3599  3730 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-03 21:22:17.722  3599  3730 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-03 21:22:17.722  3599  3730 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-03 21:22:17.722  3599  3730 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-03 21:22:17.722  3599  3730 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-03 21:22:17.722  3599  3730 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-03 21:22:17.722  3599  3730 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-03 21:22:17.722  3599  3730 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-03 21:22:17.722  3599  3730 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-03 21:22:17.722  3599  3730 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
08-03 21:22:17.726  3718  3718 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-03 21:22:17.727  3718  3718 E SysUtils: ApplicationContext is null in ApplicationStatus
08-03 21:22:17.738  3718  3718 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-03 21:22:17.747  3718  3718 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-03 21:22:17.747  3718  3718 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-03 21:22:17.747  3718  3718 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-03 21:22:17.747  3718  3718 I Adreno  : Build Date                       : 10/20/15
08-03 21:22:17.747  3718  3718 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-03 21:22:17.747  3718  3718 I Adreno  : Local Branch                     : M14
08-03 21:22:17.747  3718  3718 I Adreno  : Remote Branch                    : 
08-03 21:22:17.747  3718  3718 I Adreno  : Remote Branch                    : 
08-03 21:22:17.747  3718  3718 I Adreno  : Reconstruct Branch               : 
08-03 21:22:17.778   870   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8c4ecef:true
,08-03 21:22:17.809  3718  3718 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-03 21:22:17.820  3718  3718 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-03 21:22:17.848  3718  3756 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-03 21:22:17.858  3718  3743 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-03 21:22:17.889  3718  3756 I OpenGLRenderer: Initialized EGL, version 1.4
,08-03 21:22:17.901  1655  1655 I Keyboard.Facilitator: onFinishInput()
,08-03 21:22:17.940   870   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +304ms (total +400ms)
,08-03 21:22:17.974  3718  3718 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3718
,08-03 21:22:18.115  3718  3718 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-03 21:22:18.348  3718  3757 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1658848976
,08-03 21:22:18.355  3718  3757 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-03 21:22:18.355  3718  3757 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-03 21:22:18.355  3718  3757 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-03 21:22:18.355  3718  3757 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-03 21:22:18.355  3718  3757 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-03 21:22:18.356  3718  3757 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193908a added. We now have 1 listener(s)
,08-03 21:22:18.360  3718  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-03 21:22:18.361  3718  3757 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-03 21:22:18.361  3718  3757 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-03 21:22:18.362  3718  3757 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-03 21:22:18.366  3718  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-03 21:22:18.366  3718  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-03 21:22:18.366  3718  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-03 21:22:18.366  3718  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-03 21:22:18.366  3718  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-03 21:22:18.366  3718  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-03 21:22:18.366  3718  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-03 21:22:18.366  3718  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-03 21:22:18.366  3718  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-03 21:22:18.366  3718  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-03 21:22:18.366  3718  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-03 21:22:18.366  3718  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-03 21:22:18.366  3718  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-03 21:22:18.366  3718  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-03 21:22:18.366  3718  3757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e0b171 added. We now have 1 listener(s)
08-03 21:22:18.366  3718  3757 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 21:22:18.372   870  1311 D WifiService: New client listening to asynchronous messages
,08-03 21:22:18.374  3718  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 21:22:18.374  3718  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-03 21:22:18.374  3718  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-03 21:22:18.374  3718  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-03 21:22:18.375  3718  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-03 21:22:18.378  3718  3757 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 21:22:18.379  3718  3757 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-03 21:22:18.389  3718  3757 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-03 21:22:18.389  3718  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 21:22:18.389  3718  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:18.389  3718  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:18.389  3718  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 21:22:18.389  3718  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 21:22:18.389  3718  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 21:22:18.389  3718  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 21:22:18.389  3718  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 21:22:18.389  3718  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-03 21:22:18.389  3718  3757 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 21:22:18.390  3718  3757 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-03 21:22:18.396  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:22:18.400  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:22:18.434  3718  3718 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-03 21:22:19.413  3718  3765 W jxcore-log: Initializing JXcore engine
,08-03 21:22:19.413  3718  3765 W jxcore-log: JXcore engine is ready
,08-03 21:22:19.453  3765  3765 W Thread-325: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8974 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-03 21:22:19.453  3765  3765 W Thread-325: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11975]" dev="sockfs" ino=11975 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-03 21:22:19.453  3765  3765 W Thread-325: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-03 21:22:19.453  3765  3765 W Thread-325: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25872]" dev="sockfs" ino=25872 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-03 21:22:19.469  3718  3765 W jxcore-log: Starting JXcore engine
,08-03 21:22:19.551  3718  3765 W jxcore-log: Platform android
08-03 21:22:19.551  3718  3765 W jxcore-log: 
,08-03 21:22:19.551  3718  3765 W jxcore-log: Process ARCH arm
08-03 21:22:19.551  3718  3765 W jxcore-log: 
,08-03 21:22:19.768  3718  3765 I jxcore-log: JXcore Cordova bridge is ready!
08-03 21:22:19.768  3718  3765 I jxcore-log: 
,08-03 21:22:19.768  3718  3765 W jxcore-log: JXcore engine is started
,08-03 21:22:19.775  3718  3757 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-03 21:22:19.782  3718  3718 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-03 21:22:35.252  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-03 21:22:35.252  3718  3765 I jxcore-log: 
,08-03 21:22:35.255  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-03 21:22:35.255  3718  3765 I jxcore-log: 
,08-03 21:22:35.266  3718  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 21:22:35.266  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:35.266  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:35.266  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 21:22:35.266  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 21:22:35.266  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 21:22:35.266  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 21:22:35.266  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 21:22:35.270  3718  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 21:22:35.272  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-03 21:22:35.272  3718  3765 I jxcore-log: 
08-03 21:22:35.274  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-03 21:22:35.274  3718  3765 I jxcore-log: 
,08-03 21:22:35.618  3718  3765 D ExecuteNativeTests: Running unit tests
,08-03 21:22:35.686  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-03 21:22:35.686  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb145bb added. We now have 2 listener(s)
08-03 21:22:35.687  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 21:22:35.687  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-03 21:22:35.688  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 21:22:35.688  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 21:22:35.689  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 added. We now have 2 listener(s)
08-03 21:22:35.689  3718  3765 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 21:22:35.690  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 21:22:35.696  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 21:22:35.711  3718  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 21:22:35.711  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:35.711  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:35.711  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 21:22:35.711  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 21:22:35.711  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 21:22:35.711  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 21:22:35.711  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 21:22:35.714  3718  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 21:22:35.715  3718  3765 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 21:22:35.720  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:22:35.722  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-03 21:22:35.723  3718  3765 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-03 21:22:35.723  3718  3765 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-03 21:22:35.725  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:22:35.728  3718  3765 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-03 21:22:35.729  3718  3765 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-03 21:22:35.729  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-03 21:22:35.730  3718  3765 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-03 21:22:35.730  3718  3765 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-03 21:22:35.731  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 21:22:35.732  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-03 21:22:35.732  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 21:22:35.732  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 21:22:35.732  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 21:22:35.732  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 21:22:35.732  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 21:22:35.732  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb145bb removed from the list
08-03 21:22:35.733  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:35.733  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 removed from the list
,08-03 21:22:35.733  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
08-03 21:22:35.733  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:35.734  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:35.734  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 21:22:35.736  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 21:22:35.736  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 21:22:35.736  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:35.736  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:35.737   870  2108 D NetlinkSocketObserver: NeighborEvent{elapsedMs=380263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
08-03 21:22:35.738  3718  3765 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-03 21:22:35.740  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 21:22:35.740  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 21:22:35.740  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 21:22:35.741  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 21:22:35.741  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:35.741  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 21:22:35.741  3718  3765 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb145bb not in the list
08-03 21:22:35.741  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:35.741  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:35.741  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
08-03 21:22:35.741  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:35.741  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 21:22:35.741  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:35.742  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:35.744  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 21:22:35.744  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 21:22:35.744  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 21:22:35.744  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
,08-03 21:22:35.751  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-03 21:22:35.751  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-03 21:22:35.751  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-03 21:22:35.751  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-03 21:22:35.751  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-03 21:22:35.751  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-03 21:22:35.751  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-03 21:22:35.751  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-03 21:22:35.752  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-03 21:22:35.752  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-03 21:22:35.752  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-03 21:22:35.752  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-03 21:22:35.752  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-03 21:22:35.752  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-03 21:22:35.752  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-03 21:22:35.752  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-03 21:22:35.752  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-03 21:22:35.752  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-03 21:22:35.752  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-03 21:22:35.752  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-03 21:22:35.753  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-03 21:22:35.753  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-03 21:22:35.753  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-03 21:22:35.753  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-03 21:22:35.753  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-03 21:22:35.753  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-03 21:22:35.753  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-03 21:22:35.753  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-03 21:22:35.753  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-03 21:22:35.753  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-03 21:22:35.754  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-03 21:22:35.754  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 21:22:35.754  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 21:22:35.754  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 21:22:35.754  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 21:22:35.754  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:35.754  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:35.754  3718  3765 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb145bb not in the list
,08-03 21:22:35.755  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:35.755  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:35.755  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
08-03 21:22:35.755  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:35.755  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:35.755  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:35.755  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:35.756  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 21:22:35.756  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 21:22:35.756  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:35.756  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:35.757  3718  3765 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-03 21:22:35.759  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 21:22:35.770  3718  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 21:22:35.770  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:35.770  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:35.770  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 21:22:35.770  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 21:22:35.770  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 21:22:35.770  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 21:22:35.770  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 21:22:35.772  3718  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 21:22:35.772  3718  3765 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 21:22:35.772  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-03 21:22:35.772  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 21:22:35.773  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 21:22:35.773  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 21:22:35.773  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 21:22:35.774  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:22:35.777  3718  3765 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-03 21:22:35.777  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 21:22:35.777  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-03 21:22:35.784  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-03 21:22:35.786  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-03 21:22:35.787  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-03 21:22:35.790  3718  3765 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-03 21:22:35.796  3718  3765 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-03 21:22:35.796  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-03 21:22:35.797  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-03 21:22:35.798  3718  3765 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-03 21:22:35.799  3718  3765 D BluetoothAdapter: STATE_ON
,08-03 21:22:35.807  2545  2757 D BtGatt.GattService: registerClient() - UUID=ac5db000-e436-4f24-bbee-3d8154e62863
,08-03 21:22:35.809  2545  2596 D BtGatt.GattService: onClientRegistered() - UUID=ac5db000-e436-4f24-bbee-3d8154e62863, clientIf=5
,08-03 21:22:35.812  3718  3729 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-03 21:22:35.813  2545  2559 D BtGatt.GattService: start scan with filters
,08-03 21:22:35.818  2545  2601 D BtGatt.ScanManager: handling starting scan
,08-03 21:22:35.818  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-03 21:22:35.818  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-03 21:22:35.819  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-03 21:22:35.819  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-03 21:22:35.821  2545  2601 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81c6679
,08-03 21:22:35.824  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 21:22:35.824  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-03 21:22:35.824  3718  3718 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-03 21:22:35.825  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-03 21:22:35.832  2545  2596 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-03 21:22:35.832  2545  2596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 21:22:35.833  2545  2601 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-03 21:22:35.834  3718  3765 I io.jxcore.node.ConnectionHelper: start: OK
,08-03 21:22:35.842  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 21:22:35.842  3718  3765 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-03 21:22:35.842  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-03 21:22:35.842  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-03 21:22:35.842  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:35.842  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 21:22:35.842  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-03 21:22:35.842  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 21:22:35.842  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
08-03 21:22:35.842  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 21:22:35.843  2545  2596 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-03 21:22:35.843  2545  2596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 21:22:35.844  2545  2601 D BtGatt.ScanManager: Starting BLE batch scan
,08-03 21:22:35.844  2545  2601 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-03 21:22:35.844  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 21:22:35.844  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-03 21:22:35.846  3718  3765 D BluetoothAdapter: STATE_ON
,08-03 21:22:35.847  2545  2559 D BtGatt.GattService: stopScan() - queue size =1
,08-03 21:22:35.849  2545  2758 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-03 21:22:35.849  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 21:22:35.850  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-03 21:22:35.850  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-03 21:22:35.850  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-03 21:22:35.851  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-03 21:22:35.854  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-03 21:22:35.855  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-03 21:22:35.855  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-03 21:22:35.856  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 21:22:35.857  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-03 21:22:35.859  3718  3718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-03 21:22:35.859  3718  3718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 21:22:35.859  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 21:22:35.859  3718  3718 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-03 21:22:35.860  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 21:22:35.860  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-03 21:22:35.860  3718  3765 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb145bb not in the list
08-03 21:22:35.860  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:35.861  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:35.861  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop,
08-03 21:22:35.861  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:35.862  2545  2596 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-03 21:22:35.862  3718  3765 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-03 21:22:35.862  2545  2596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 21:22:35.866  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 21:22:35.871  3718  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 21:22:35.871  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:35.871  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:35.871  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 21:22:35.871  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 21:22:35.871  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 21:22:35.871  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 21:22:35.871  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 21:22:35.872  3718  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 21:22:35.873  3718  3765 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 21:22:35.873  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 21:22:35.874  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 21:22:35.874  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 21:22:35.874  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 21:22:35.874  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 21:22:35.874  2545  2596 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-03 21:22:35.874  2545  2596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 21:22:35.876  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:22:35.877  3718  3765 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-03 21:22:35.877  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-03 21:22:35.882  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:22:35.884  2545  2596 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-03 21:22:35.884  2545  2596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 21:22:35.884  2545  2601 D BtGatt.ScanManager: stopping BLe Batch
,08-03 21:22:35.886  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-03 21:22:35.886  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-03 21:22:35.887  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-03 21:22:35.890  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-03 21:22:35.890  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-03 21:22:35.890  3718  3765 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-03 21:22:35.890  3718  3765 D BluetoothAdapter: STATE_ON
,08-03 21:22:35.892  2545  2757 D BtGatt.GattService: registerClient() - UUID=732fdd82-f415-48cc-92ab-0f9b00587c51
08-03 21:22:35.893  2545  2596 D BtGatt.GattService: onClientRegistered() - UUID=732fdd82-f415-48cc-92ab-0f9b00587c51, clientIf=5
,08-03 21:22:35.893  3718  3728 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-03 21:22:35.893  2545  2559 D BtGatt.GattService: start scan with filters
,08-03 21:22:35.895  2545  2596 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-03 21:22:35.895  2545  2596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 21:22:35.895  2545  2601 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-03 21:22:35.896  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-03 21:22:35.897  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-03 21:22:35.897  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-03 21:22:35.897  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-03 21:22:35.901  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 21:22:35.901  2545  2596 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-03 21:22:35.901  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-03 21:22:35.901  2545  2596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 21:22:35.902  3718  3718 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 21:22:35.903  2545  2601 D BtGatt.ScanManager: handling starting scan
,08-03 21:22:35.904  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-03 21:22:35.906  3718  3765 I io.jxcore.node.ConnectionHelper: start: OK
,08-03 21:22:35.909  2545  2596 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-03 21:22:35.909  2545  2596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 21:22:35.909  2545  2601 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-03 21:22:35.909  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 21:22:35.910  3718  3765 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-03 21:22:35.910  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-03 21:22:35.910  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-03 21:22:35.910  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:35.910  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-03 21:22:35.910  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-03 21:22:35.910  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 21:22:35.910  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 21:22:35.911  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 21:22:35.911  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-03 21:22:35.911  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-03 21:22:35.912  3718  3765 D BluetoothAdapter: STATE_ON
08-03 21:22:35.913  2545  2560 D BtGatt.GattService: stopScan() - queue size =1
08-03 21:22:35.913  2545  2758 D BtGatt.GattService: unregisterClient() - clientIf=5,
08-03 21:22:35.914  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 21:22:35.914  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-03 21:22:35.914  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
08-03 21:22:35.914  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-03 21:22:35.914  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-03 21:22:35.916  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-03 21:22:35.916  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-03 21:22:35.916  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-03 21:22:35.917  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-03 21:22:35.918  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-03 21:22:35.918  2545  2596 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-03 21:22:35.918  2545  2596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 21:22:35.919  2545  2601 D BtGatt.ScanManager: Starting BLE batch scan
08-03 21:22:35.919  2545  2601 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-03 21:22:35.919  3718  3718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 21:22:35.919  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 21:22:35.919  3718  3718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 21:22:35.919  3718  3718 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-03 21:22:35.919  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:35.920  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 21:22:35.920  3718  3765 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb145bb not in the list
08-03 21:22:35.920  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 21:22:35.920  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:35.920  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
08-03 21:22:35.920  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:35.921  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 21:22:35.921  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:35.922  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 21:22:35.922  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 21:22:35.922  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 21:22:35.922  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:35.922  3718  3765 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-03 21:22:35.924  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 21:22:35.928  3718  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 21:22:35.928  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:35.928  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:35.928  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 21:22:35.928  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 21:22:35.928  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 21:22:35.928  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 21:22:35.928  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 21:22:35.930  3718  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 21:22:35.930  3718  3765 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 21:22:35.930  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 21:22:35.930  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 21:22:35.930  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-03 21:22:35.931  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 21:22:35.931  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-03 21:22:35.932  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 21:22:35.935  3718  3765 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-03 21:22:35.935  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-03 21:22:35.935  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 21:22:35.937  2545  2596 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-03 21:22:35.937  2545  2596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 21:22:35.939  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-03 21:22:35.940  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-03 21:22:35.940  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-03 21:22:35.943  2545  2596 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-03 21:22:35.943  2545  2596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 21:22:35.944  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-03 21:22:35.945  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-03 21:22:35.945  3718  3765 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-03 21:22:35.946  3718  3765 D BluetoothAdapter: STATE_ON
,08-03 21:22:35.948  2545  2757 D BtGatt.GattService: registerClient() - UUID=6422cabd-0e96-480c-aeff-d47aa4812742
,08-03 21:22:35.948  2545  2596 D BtGatt.GattService: onClientRegistered() - UUID=6422cabd-0e96-480c-aeff-d47aa4812742, clientIf=5
,08-03 21:22:35.949  3718  3729 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-03 21:22:35.949  2545  2559 D BtGatt.GattService: start scan with filters
08-03 21:22:35.951  2545  2596 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-03 21:22:35.951  2545  2596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 21:22:35.951  2545  2601 D BtGatt.ScanManager: stopping BLe Batch
,08-03 21:22:35.952  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-03 21:22:35.952  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-03 21:22:35.953  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-03 21:22:35.953  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-03 21:22:35.955  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-03 21:22:35.955  3718  3718 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 21:22:35.955  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-03 21:22:35.957  2545  2596 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-03 21:22:35.957  2545  2596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 21:22:35.957  2545  2601 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-03 21:22:35.957  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-03 21:22:35.962  2545  2596 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-03 21:22:35.962  2545  2596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 21:22:35.963  3718  3765 I io.jxcore.node.ConnectionHelper: start: OK
08-03 21:22:35.963  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 21:22:35.964  3718  3765 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-03 21:22:35.964  2545  2601 D BtGatt.ScanManager: handling starting scan
,08-03 21:22:35.964  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-03 21:22:35.964  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-03 21:22:35.964  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 21:22:35.964  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 21:22:35.965  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-03 21:22:35.965  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 21:22:35.965  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-03 21:22:35.965  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 21:22:35.965  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 21:22:35.965  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-03 21:22:35.966  3718  3765 D BluetoothAdapter: STATE_ON
,08-03 21:22:35.967  2545  2559 D BtGatt.GattService: stopScan() - queue size =1
,08-03 21:22:35.967  2545  2758 D BtGatt.GattService: unregisterClient() - clientIf=5
08-03 21:22:35.968  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 21:22:35.968  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-03 21:22:35.968  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-03 21:22:35.968  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-03 21:22:35.968  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-03 21:22:35.970  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-03 21:22:35.970  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-03 21:22:35.970  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-03 21:22:35.970  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-03 21:22:35.971  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 21:22:35.971  2545  2596 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-03 21:22:35.971  2545  2596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 21:22:35.971  2545  2601 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-03 21:22:35.972  3718  3718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 21:22:35.972  3718  3718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-03 21:22:35.972  3718  3718 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 21:22:35.973  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 21:22:35.973  3718  3765 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-03 21:22:35.973  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 21:22:35.973  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-03 21:22:35.973  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 21:22:35.974  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:35.974  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 21:22:35.974  3718  3765 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb145bb not in the list
08-03 21:22:35.974  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:35.974  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
,08-03 21:22:35.974  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
08-03 21:22:35.975  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:35.975  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 21:22:35.976  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 21:22:35.977  2545  2596 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-03 21:22:35.977  2545  2596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 21:22:35.977  2545  2601 D BtGatt.ScanManager: Starting BLE batch scan
,08-03 21:22:35.977  2545  2601 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-03 21:22:35.977  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 21:22:35.978  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 21:22:35.978  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:35.978  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:35.978  3718  3765 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-03 21:22:35.979  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 21:22:35.979  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 21:22:35.979  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 21:22:35.979  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 21:22:35.979  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:35.980  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:35.980  3718  3765 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb145bb not in the list
08-03 21:22:35.980  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:35.980  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:35.980  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
,08-03 21:22:35.980  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:35.980  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:35.980  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:35.980  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:35.981  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 21:22:35.981  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 21:22:35.981  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:35.982  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:35.983  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-03 21:22:35.983  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 21:22:35.983  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 21:22:35.983  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 21:22:35.983  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 21:22:35.983  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:35.984  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:35.984  3718  3765 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb145bb not in the list
08-03 21:22:35.984  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 21:22:35.984  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:35.984  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
08-03 21:22:35.984  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:35.984  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:35.984  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:35.984  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 21:22:35.986  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 21:22:35.986  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 21:22:35.986  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:35.986  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
,08-03 21:22:35.987  3718  3765 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-03 21:22:35.987  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 21:22:35.987  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 21:22:35.987  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-03 21:22:35.987  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 21:22:35.987  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:35.987  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 21:22:35.987  3718  3765 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb145bb not in the list
08-03 21:22:35.987  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:35.988  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:35.988  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
,08-03 21:22:35.988  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:35.988  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:35.988  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:35.988  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:35.989  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 21:22:35.989  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 21:22:35.989  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:35.989  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:35.990  3718  3765 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-03 21:22:35.990  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 21:22:35.990  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 21:22:35.990  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 21:22:35.990  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 21:22:35.990  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:35.990  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:35.990  3718  3765 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb145bb not in the list
08-03 21:22:35.990  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 21:22:35.991  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:35.991  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
08-03 21:22:35.991  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:35.991  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:35.991  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:35.991  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 21:22:35.992  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 21:22:35.992  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 21:22:35.992  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 21:22:35.992  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:35.993  2545  2596 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-03 21:22:35.993  2545  2596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 21:22:35.993  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-03 21:22:35.995  3718  3765 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 21:22:35.995  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 21:22:35.995  3718  3765 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 21:22:35.995  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-03 21:22:35.995  3718  3765 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-03 21:22:35.995  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 21:22:35.996  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 21:22:35.996  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-03 21:22:35.996  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 21:22:35.997  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 21:22:35.997  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:35.997  3718  3765 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb145bb not in the list
08-03 21:22:35.997  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:35.997  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
,08-03 21:22:35.997  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
08-03 21:22:35.997  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 21:22:35.997  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:35.997  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:35.998  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:35.999  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 21:22:35.999  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 21:22:35.999  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:35.999  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list,
08-03 21:22:36.000  3718  3765 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 21:22:36.000  3718  3765 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-03 21:22:36.000  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-03 21:22:36.002  2545  2596 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-03 21:22:36.002  2545  2596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 21:22:36.006  3718  3765 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-03 21:22:36.006  3718  3765 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-03 21:22:36.006  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-03 21:22:36.007  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-03 21:22:36.007  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-03 21:22:36.007  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-03 21:22:36.007  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-03 21:22:36.007  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-03 21:22:36.007  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-03 21:22:36.007  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-03 21:22:36.007  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-03 21:22:36.007  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-03 21:22:36.007  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-03 21:22:36.007  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-03 21:22:36.007  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-03 21:22:36.007  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-03 21:22:36.008  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-03 21:22:36.008  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-03 21:22:36.008  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-03 21:22:36.008  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-03 21:22:36.008  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-03 21:22:36.008  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-03 21:22:36.008  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-03 21:22:36.008  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-03 21:22:36.008  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-03 21:22:36.008  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-03 21:22:36.008  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-03 21:22:36.009  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-03 21:22:36.009  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-03 21:22:36.009  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-03 21:22:36.009  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-03 21:22:36.009  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-03 21:22:36.009  3718  3765 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-03 21:22:36.010  3718  3765 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 21:22:36.010  3718  3765 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-03 21:22:36.010  2545  2596 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-03 21:22:36.010  3718  3765 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 21:22:36.011  2545  2596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 21:22:36.011  3718  3765 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 21:22:36.011  3718  3765 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-03 21:22:36.011  2545  2601 D BtGatt.ScanManager: stopping BLe Batch
08-03 21:22:36.011  3718  3765 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 21:22:36.011  3718  3765 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 21:22:36.011  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-03 21:22:36.015  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-03 21:22:36.016  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-03 21:22:36.016  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-03 21:22:36.016  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-03 21:22:36.017  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-03 21:22:36.017  3718  3765 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-03 21:22:36.017  3718  3765 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 21:22:36.017  3718  3765 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-03 21:22:36.018  2545  2596 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-03 21:22:36.018  2545  2596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 21:22:36.018  2545  2601 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-03 21:22:36.019  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 21:22:36.019  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 21:22:36.019  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 21:22:36.019  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 21:22:36.020  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.020  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.020  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-03 21:22:36.021  3718  3765 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb145bb not in the list
08-03 21:22:36.021  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:36.021  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:36.021  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
08-03 21:22:36.021  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.021  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.021  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.021  3718  3769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 389
08-03 21:22:36.021  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.022  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 21:22:36.022  3718  3765 I org.thaliproject.p2p.bt,connectorlib.DiscoveryManager: stopDiscovery
08-03 21:22:36.022  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:36.022  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:36.023  3718  3765 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-03 21:22:36.023  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 21:22:36.024  2545  2596 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-03 21:22:36.024  2545  2596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 21:22:36.024  3718  3768 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 389)
08-03 21:22:36.024  3718  3768 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 389)
08-03 21:22:36.025  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 21:22:36.025  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 21:22:36.025  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 21:22:36.025  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.025  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.025  3718  3765 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb145bb not in the list
08-03 21:22:36.025  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:36.025  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:36.025  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
08-03 21:22:36.025  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.025  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.025  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.025  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.026  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 21:22:36.026  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 21:22:36.026  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:36.027  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:36.027  3718  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-03 21:22:36.027  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 21:22:36.028  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 21:22:36.028  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 21:22:36.028  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 21:22:36.028  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.028  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.028  3718  3765 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb145bb not in the list
08-03 21:22:36.028  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:36.028  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:36.028  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
08-03 21:22:36.028  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.028  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.028  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.028  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.029  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 21:22:36.029  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 21:22:36.029  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:36.029  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:36.030  3718  3765 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-03 21:22:36.030  3718  3765 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-03 21:22:36.030  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 21:22:36.030  3718  3765 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-03 21:22:36.030  3718  3765 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-03 21:22:36.030  3718  3765 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-03 21:22:36.031  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 21:22:36.031  3718  3765 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-03 21:22:36.031  3718  3765 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-03 21:22:36.031  3718  3765 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-03 21:22:36.031  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 21:22:36.031  3718  3765 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-03 21:22:36.031  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 21:22:36.031  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 21:22:36.031  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 21:22:36.031  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 21:22:36.031  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.031  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.032  3718  3765 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb145bb not in the list
08-03 21:22:36.032  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:36.032  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:36.032  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
08-03 21:22:36.032  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.032  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.032  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.032  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.033  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 21:22:36.033  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 21:22:36.033  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:36.033  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:36.033  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 21:22:36.034  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.034  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.034  3718  3765 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb145bb not in the list
08-03 21:22:36.034  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:36.034  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:36.034  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
08-03 21:22:36.034  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.034  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.034  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:36.034  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:36.034  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 21:22:36.034  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.034  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.034  3718  3765 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb145bb not in the list
08-03 21:22:36.035  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 21:22:36.035  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 21:22:36.035  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 21:22:36.035  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 21:22:36.035  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.035  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.035  3718  3765 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb145bb not in the list
08-03 21:22:36.035  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:36.035  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:36.035  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
08-03 21:22:36.035  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.035  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.035  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.035  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.036  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 21:22:36.036  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 21:22:36.036  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:36.036  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:36.038  3718  3765 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-03 21:22:36.038  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 21:22:36.038  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-03 21:22:36.039  3718  3765 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-03 21:22:36.039  3718  3765 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-03 21:22:36.039  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-03 21:22:36.040  3718  3718 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-03 21:22:36.040  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-03 21:22:36.040  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 21:22:36.040  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-03 21:22:36.040  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-03 21:22:36.040  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-03 21:22:36.041  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.041  3718  3765 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-03 21:22:36.041  3718  3765 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb145bb not in the list
08-03 21:22:36.041  3718  3718 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-03 21:22:36.041  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:36.041  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 21:22:36.041  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 21:22:36.041  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 21:22:36.041  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.041  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.042  3718  3770 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 21:22:36.042  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 21:22:36.042  3718  3718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 21:22:36.042  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:36.042  3718  3718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 21:22:36.042  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 21:22:36.042  3718  3718 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 21:22:36.043  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 21:22:36.043  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 21:22:36.043  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 21:22:36.043  3718  3770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-03 21:22:36.043  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.043  3718  3770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-03 21:22:36.044  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.044  3718  3770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-03 21:22:36.044  3718  3765 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb145bb not in the list
08-03 21:22:36.044  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:36.044  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:36.044  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
08-03 21:22:36.044  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.044  3718  3718 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-03 21:22:36.044  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.044  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.044  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.045  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 21:22:36.045  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 21:22:36.045  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:36.045  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:36.046  3718  3765 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-03 21:22:36.046  3718  3765 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-03 21:22:36.046  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 21:22:36.046  3718  3765 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 21:22:36.047  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 21:22:36.047  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 21:22:36.047  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 21:22:36.047  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 21:22:36.047  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.047  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.047  3718  3765 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb145bb not in the list
08-03 21:22:36.047  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:36.047  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:36.047  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
08-03 21:22:36.047  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.047  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.047  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.047  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.048  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 21:22:36.048  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 21:22:36.048  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:36.048  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:36.051  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 21:22:36.051  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 21:22:36.051  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 21:22:36.051  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 21:22:36.051  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.051  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.052  3718  3765 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb145bb not in the list
08-03 21:22:36.052  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:36.052  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:36.052  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
08-03 21:22:36.052  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.052  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.052  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.052  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.053  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 21:22:36.053  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 21:22:36.053  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:36.053  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:36.054  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 21:22:36.054  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 21:22:36.054  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 21:22:36.054  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 21:22:36.054  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.054  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.054  3718  3765 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb145bb not in the list
08-03 21:22:36.054  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:36.054  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:36.054  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
08-03 21:22:36.054  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.054  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.054  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:22:36.054  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:22:36.055  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 21:22:36.055  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 21:22:36.055  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:22:36.055  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5bdad8 not in the list
08-03 21:22:36.056  3718  3765 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-03 21:22:36.056  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 21:22:36.057  3718  3765 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-03 21:22:36.057  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 21:22:36.057  3718  3765 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-03 21:22:36.057  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 21:22:36.058  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-03 21:22:36.059  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-03 21:22:36.059  3718  3765 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-03 21:22:36.062  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-03 21:22:36.062  3718  3765 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-03 21:22:36.062  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-03 21:22:36.063  3718  3765 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-03 21:22:36.063  3718  3765 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-03 21:22:36.063  3718  3765 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-03 21:22:36.063  3718  3765 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-03 21:22:36.064  3718  3765 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-03 21:22:36.064  3718  3765 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-03 21:22:36.064  3718  3765 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-03 21:22:36.064  3718  3765 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-03 21:22:36.065  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 21:22:36.065  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@36761fa added. We now have 2 listener(s)
08-03 21:22:36.066  3718  3765 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 21:22:36.067  3718  3765 D BluetoothAdapter: enable(): BT is already enabled..!
08-03 21:22:36.067   870  1380 D WifiService: setWifiEnabled: true pid=3718, uid=10000
08-03 21:22:36.067   870  1380 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-03 21:22:36.068  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 21:22:36.068  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@43b13ab added. We now have 3 listener(s)
08-03 21:22:36.068  3718  3765 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 21:22:36.073  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 21:22:36.073  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e67aa08 added. We now have 4 listener(s)
08-03 21:22:36.073  3718  3765 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 21:22:36.074  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 21:22:36.074  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@22205a1 added. We now have 5 listener(s)
08-03 21:22:36.075  3718  3765 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 21:22:36.076   870  1734 D WifiService: setWifiEnabled: false pid=3718, uid=10000
08-03 21:22:36.076   870  1734 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-03 21:22:36.085  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 21:22:36.088  2545  2592 D BluetoothAdapterState: Current state: ON, message: 23
,08-03 21:22:36.088  2545  2592 D BluetoothAdapterProperties: Setting state to 13
,08-03 21:22:36.088  2545  2592 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-03 21:22:36.088  2545  2592 D BluetoothAdapterProperties: onBluetoothDisable()
08-03 21:22:36.089  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 21:22:36.089  3718  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 21:22:36.089  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:36.089  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:36.089  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 21:22:36.089  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 21:22:36.089  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 21:22:36.089  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 21:22:36.089  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 21:22:36.091  2545  2545 D BluetoothMapService: onReceive
08-03 21:22:36.091  2545  2545 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 21:22:36.091  2545  2545 D BluetoothMapService: STATE_TURNING_OFF
08-03 21:22:36.091  2545  2545 D BluetoothMapService: MAP Service closeService in
08-03 21:22:36.091  2545  2545 D BluetoothMapMasInstance0: MAP Service shutdown
08-03 21:22:36.091  2545  2545 D ObexServerSockets0: shutdown(block = true)
,08-03 21:22:36.091  2545  2592 I BluetoothAdapterState: Entering PendingCommandState
08-03 21:22:36.091  2545  2545 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-03 21:22:36.092  2545  2545 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-03 21:22:36.092  2545  2759 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-03 21:22:36.092  2545  2743 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-03 21:22:36.092  2545  2760 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-03 21:22:36.092  2545  2545 I BtOppRfcommListener: stopping Accept Thread
08-03 21:22:36.093  2545  3267 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 21:22:36.093  2545  3267 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-03 21:22:36.094  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 21:22:36.096  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 21:22:36.096  3718  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 21:22:36.096   870  1310 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-03 21:22:36.096  3718  3765 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 21:22:36.096   870  1310 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-03 21:22:36.096   870  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-03 21:22:36.097   870  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 21:22:36.102   870  1310 E native  : do suspend true
,08-03 21:22:36.108   870   884 I ActivityManager: Start proc 3773:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-03 21:22:36.108  2545  2596 D BluetoothAdapterProperties: Scan Mode:20
,08-03 21:22:36.108  2545  2592 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-03 21:22:36.111  2545  2545 D HeadsetService: Received stop request...Stopping profile...
08-03 21:22:36.114  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 21:22:36.114  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 21:22:36.114  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:36.114  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:36.114  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 21:22:36.114  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 21:22:36.114  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 21:22:36.114  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 21:22:36.114  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 21:22:36.114  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 21:22:36.115  3718  3718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 21:22:36.119  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:22:36.119   870  2111 D DhcpClient: Clearing IP address
08-03 21:22:36.119   370   868 D CommandListener: Clearing all IP addresses on wlan0
,08-03 21:22:36.121  1772  2022 D BluetoothHeadset: Proxy object disconnected
,08-03 21:22:36.121   870   870 D BluetoothHeadset: Proxy object disconnected
,08-03 21:22:36.121  1366  1378 D BluetoothHeadset: Proxy object disconnected
,08-03 21:22:36.122   870   870 D BluetoothHeadset: Proxy object disconnected
08-03 21:22:36.122  1366  1366 D HeadsetProfile: Bluetooth service disconnected
,08-03 21:22:36.122   870   870 D BluetoothHeadset: Proxy object disconnected
08-03 21:22:36.122  2545  2545 D A2dpService: Received stop request...Stopping profile...
08-03 21:22:36.122  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 21:22:36.122   370   868 D CommandListener: Setting iface cfg
08-03 21:22:36.122  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 21:22:36.122  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:36.122  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:36.122  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 21:22:36.122  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 21:22:36.122  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 21:22:36.122  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 21:22:36.122  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 21:22:36.122  2545  2750 D A2dpStateMachine: Exit Disconnected: -1
08-03 21:22:36.123  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 21:22:36.123  3718  3718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 21:22:36.123   870   870 D BluetoothA2dp: Proxy object disconnected
08-03 21:22:36.124  1366  1366 D BluetoothA2dp: Proxy object disconnected
08-03 21:22:36.125  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:22:36.125  2545  2545 V BluetoothAdapterState: isTurningOff()=true
08-03 21:22:36.125  2545  2545 V BluetoothAdapterState: isTurningOn()=false
08-03 21:22:36.125  2545  2545 V BluetoothAdapterState: isBleTurningOn()=false
08-03 21:22:36.125  2545  2545 V BluetoothAdapterState: isBleTurningOff()=false
08-03 21:22:36.126  2545  2545 D HidService: Received stop request...Stopping profile...
08-03 21:22:36.126   870  1310 D WifiStateMachine: Start Disconnecting Watchdog 1
08-03 21:22:36.126  1500  2227 V NativeCrypto: Read error: ssl=0x9b6f5c00: I/O error during system call, Connection timed out
08-03 21:22:36.126  2545  2545 D HidService: Stopping Bluetooth HidService
,08-03 21:22:36.127   870  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-03 21:22:36.127   870  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-03 21:22:36.127  1500  2227 V NativeCrypto: SSL shutdown failed: ssl=0x9b6f5c00: I/O error during system call, Broken pipe
,08-03 21:22:36.129  1366  1366 D BluetoothInputDevice: Proxy object disconnected
08-03 21:22:36.129  1366  1366 D HidProfile: Bluetooth service disconnected
,08-03 21:22:36.129   870  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-03 21:22:36.129   870  1310 E native  : do suspend true
,08-03 21:22:36.130   400   400 E Parcel  : Reading a NULL string not supported here.
08-03 21:22:36.131  2545  2545 D HealthService: Received stop request...Stopping profile...
08-03 21:22:36.131  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 21:22:36.131  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 21:22:36.131  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:36.131  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:36.131  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 21:22:36.131  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 21:22:36.131  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 21:22:36.131  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 21:22:36.131  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 21:22:36.131  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 21:22:36.131  3718  3718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 21:22:36.133  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 21:22:36.134  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 21:22:36.134  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:36.134  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:36.134  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 21:22:36.134  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 21:22:36.134  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 21:22:36.134  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 21:22:36.134  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 21:22:36.134   870  1312 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-03 21:22:36.134  2545  2545 D PanService: Received stop request...Stopping profile...
08-03 21:22:36.134  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 21:22:36.134  3718  3718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 21:22:36.135  1366  1366 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-03 21:22:36.135  1366  1366 D PanProfile: Bluetooth service disconnected
08-03 21:22:36.136  2545  2545 D BluetoothMapService: Received stop request...Stopping profile...
08-03 21:22:36.137  2545  2545 D BluetoothMapService: stop()
08-03 21:22:36.138  2545  2545 D BluetoothMapAppObserver: deinitObservers()
08-03 21:22:36.138  2545  2545 D BluetoothMapAppObserver: removeReceiver()
08-03 21:22:36.141  1366  1366 D BluetoothMap: Proxy object disconnected
08-03 21:22:36.141  1366  1366 D MapProfile: Bluetooth service disconnected
08-03 21:22:36.141  2545  2545 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-03 21:22:36.141  2545  2545 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-03 21:22:36.142  2545  2545 V BluetoothAdapterState: isTurningOff()=true
08-03 21:22:36.142  2545  2545 V BluetoothAdapterState: isTurningOn()=false
08-03 21:22:36.142  2545  2545 V BluetoothAdapterState: isBleTurningOn()=false
08-03 21:22:36.142  2545  2545 V BluetoothAdapterState: isBleTurningOff()=false
08-03 21:22:36.142  2545  2596 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-03 21:22:36.142  2545  2727 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 21:22:36.142  2545  2727 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 21:22:36.142  2545  2727 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 21:22:36.143  2545  2596 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-03 21:22:36.144  2545  2545 V BluetoothAdapterState: isTurningOff()=true
08-03 21:22:36.144  2545  2545 V BluetoothAdapterState: isTurningOn()=false
08-03 21:22:36.144  2545  2545 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 21:22:36.144   870  2114 D DhcpClient: Receive thread stopped
08-03 21:22:36.144  2545  2545 V BluetoothAdapterState: isBleTurningOff()=false
08-03 21:22:36.144  2545  2545 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-03 21:22:36.145  2545  2545 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-03 21:22:36.145  2545  2545 V BluetoothAdapterState: isTurningOff()=true
08-03 21:22:36.146  2545  2545 V BluetoothAdapterState: isTurningOn()=false
08-03 21:22:36.146  2545  2545 V BluetoothAdapterState: isBleTurningOn()=false
08-03 21:22:36.146  2545  2545 V BluetoothAdapterState: isBleTurningOff()=false
08-03 21:22:36.147  2545  2727 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 21:22:36.147  2545  2727 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 21:22:36.147  2545  2727 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 21:22:36.147  2545  2727 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 21:22:36.147  2545  2727 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 21:22:36.147  2545  2727 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-03 21:22:36.148  2545  2596 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-03 21:22:36.148  2545  2596 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-03 21:22:36.148  2545  2545 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-03 21:22:36.148  2545  2596 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-03 21:22:36.148  2545  2545 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 21:22:36.148  2545  2545 V BluetoothAdapterState: isTurningOff()=true
08-03 21:22:36.148  2545  2545 V BluetoothAdapterState: isTurningOn()=false
08-03 21:22:36.148  2545  2545 V BluetoothAdapterState: isBleTurningOn()=false
08-03 21:22:36.148  2545  2545 V BluetoothAdapterState: isBleTurningOff()=false
08-03 21:22:36.149  2545  2545 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-03 21:22:36.149  2545  2545 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-03 21:22:36.150  2545  2545 D BluetoothMapService: MAP Service closeService in
08-03 21:22:36.150  2545  2545 V BluetoothAdapterState: isTurningOff()=true
08-03 21:22:36.150  2545  2545 V BluetoothAdapterState: isTurningOn()=false
08-03 21:22:36.150  2545  2545 V BluetoothAdapterState: isBleTurningOn()=false
08-03 21:22:36.150  2545  2545 V BluetoothAdapterState: isBleTurningOff()=false
08-03 21:22:36.151  2545  2592 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-03 21:22:36.151  2545  2592 D BluetoothAdapterProperties: Setting state to 15
08-03 21:22:36.151  2545  2592 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-03 21:22:36.151  1366  1807 D BluetoothMap: onBluetoothStateChange: up=false
,08-03 21:22:36.152   870   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 21:22:36.152  1366  1374 D BluetoothPan: onBluetoothStateChange on: false
08-03 21:22:36.153  2545  2592 I BluetoothAdapterState: Entering BleOnState
08-03 21:22:36.153  1366  1378 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-03 21:22:36.153   870   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 21:22:36.153   870   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 21:22:36.153   870   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 21:22:36.154  1366  1807 D BluetoothPbap: onBluetoothStateChange: up=false
08-03 21:22:36.156  1366  1374 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 21:22:36.157  1366  1378 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 21:22:36.160  1772  1894 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 21:22:36.161  2545  2592 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-03 21:22:36.161  2545  2592 D BluetoothAdapterProperties: Setting state to 16
08-03 21:22:36.161  2545  2592 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-03 21:22:36.161  2545  2592 D BluetoothAdapterProperties: onBleDisable
08-03 21:22:36.162  2545  2592 I BluetoothAdapterState: Entering PendingCommandState
08-03 21:22:36.162  2545  2593 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-03 21:22:36.163  2545  2596 D BluetoothAdapterProperties: Scan Mode:20
08-03 21:22:36.163  2545  2727 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-03 21:22:36.163  2545  2727 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 21:22:36.164  2545  2545 D BluetoothMapService: cleanup()
08-03 21:22:36.164  2545  2545 D BluetoothMapService: MAP Service closeService in
08-03 21:22:36.165  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 21:22:36.165  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 21:22:36.165  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:36.165  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:36.165  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 21:22:36.165  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 21:22:36.165  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 21:22:36.165  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 21:22:36.165  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 21:22:36.166  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 21:22:36.166  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 21:22:36.166  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:36.166  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:36.166  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 21:22:36.166  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 21:22:36.166  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 21:22:36.166  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 21:22:36.166  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 21:22:36.167  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 21:22:36.168  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 21:22:36.175   370   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-03 21:22:36.191   370   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-03 21:22:36.191   370   868 D CommandListener: Clearing all IP addresses on wlan0
08-03 21:22:36.192   870  1312 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-03 21:22:36.192   870  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-03 21:22:36.193   870  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-03 21:22:36.194   870   888 D Tethering: MasterInitialState.processMessage what=3
08-03 21:22:36.196  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 21:22:36.197  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 21:22:36.202  3256  3256 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@d59b439 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-03 21:22:36.202  1825  1825 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-03 21:22:36.208  3773  3773 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-03 21:22:36.211   870  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 21:22:36.214  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 21:22:36.214  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 21:22:36.214  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:36.214  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:36.214  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 21:22:36.214  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 21:22:36.214  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 21:22:36.214  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 21:22:36.214  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 21:22:36.214  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 21:22:36.214  3718  3718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 21:22:36.215   870  1310 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-03 21:22:36.216  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 21:22:36.216  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 21:22:36.216  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:36.216  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:36.216  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 21:22:36.216  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 21:22:36.216  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 21:22:36.216  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 21:22:36.216  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 21:22:36.216  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 21:22:36.216  3718  3718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 21:22:36.217  1694  2052 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 21:22:36.223  3773  3773 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-03 21:22:36.228  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 21:22:36.230   870   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c0e6178:true
,08-03 21:22:36.240   870  1380 I ActivityManager: Start proc 3793:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-03 21:22:36.251   370   868 E Netd    : netlink response contains error (No such file or directory)
,08-03 21:22:36.260  3773  3773 D LocalBluetoothProfileManager: Adding local MAP profile
,08-03 21:22:36.262  3773  3773 D BluetoothMap: Create BluetoothMap proxy object
,08-03 21:22:36.269  3773  3773 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-03 21:22:36.274  3793  3793 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-03 21:22:36.282  3773  3773 D DockEventReceiver: finishStartingService: stopping service
,08-03 21:22:36.291   870  1819 I ActivityManager: Killing 3256:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-03 21:22:36.364  2545  2596 I bt_hci  : shut_down
,08-03 21:22:36.374  2545  2602 D bt_hwcfg: hw_epilog_process
,08-03 21:22:36.374  2545  2602 I bt_vendor: low_power_mode_cb
,08-03 21:22:36.399  2545  2602 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-03 21:22:36.400  2545  2602 I bt_vendor: epilog_cb
08-03 21:22:36.400  2545  2602 I bt_hci  : epilog_finished_callback
,08-03 21:22:36.402  2545  2596 I bt_hci_h4: hal_close
,08-03 21:22:36.403  2545  2596 I bt_userial_vendor: device fd = 51 close
,08-03 21:22:36.464  3793  3793 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 21:22:36.464  3793  3793 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 21:22:36.464  3793  3793 D StrictMode: 	,at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at java.io.File.exists(File.java:361)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-03 21:22:36.464  3793  3793 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 21:22:36.464  3793  3793 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 21:22:36.464  3793  3793 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-03 21:22:36.465  3793  3793 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-03 21:22:36.465  3793  3793 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.r.e.b(PG:170)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-03 21:22:36.465  3793  3793 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.r.k.d(PG:583)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.r.e.b(PG:170)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-03 21:22:36.465  3793  3793 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at java.io.File.exists(File.java:361)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-03 21:22:36.465  3793  3793 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at java.io.File.exists(File.java:361)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-03 21:22:36.465  3793  3793 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 21:22:36.465  3793  3793 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-03 21:22:36.470  3773  3773 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-03 21:22:36.478  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 21:22:36.512   870  1380 I ActivityManager: Start proc 3824:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-03 21:22:36.514  3773  3773 D DockEventReceiver: finishStartingService: stopping service
,08-03 21:22:36.519   870   881 I ActivityManager: Killing 2618:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-03 21:22:36.543  3718  3718 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-03 21:22:36.555  2545  2593 D bt_stack_manager: event_shut_down_stack finished.
,08-03 21:22:36.555  2545  2592 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-03 21:22:36.567  2545  2592 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-03 21:22:36.567  2545  2545 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-03 21:22:36.569  2545  2545 D BtGatt.GattService: Received stop request...Stopping profile...
,08-03 21:22:36.569  2545  2545 D BtGatt.GattService: stop()
08-03 21:22:36.569  2545  2545 D BtGatt.AdvertiseManager: advertise clients cleared
,08-03 21:22:36.574  2545  2545 V BluetoothAdapterState: isTurningOff()=false
,08-03 21:22:36.575  2545  2545 V BluetoothAdapterState: isTurningOn()=false
08-03 21:22:36.575  2545  2545 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 21:22:36.575  2545  2545 V BluetoothAdapterState: isBleTurningOff()=true
08-03 21:22:36.576  2545  2592 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-03 21:22:36.577  2545  2592 D BluetoothAdapterProperties: Setting state to 10
08-03 21:22:36.577  2545  2592 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-03 21:22:36.578  2545  2592 I BluetoothAdapterState: Entering OffState
08-03 21:22:36.579   870   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-03 21:22:36.589  3824  3824 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-03 21:22:36.599  2545  2545 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-03 21:22:36.599  2545  2545 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-03 21:22:36.599  2545  2593 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-03 21:22:36.600  2545  2593 D bt_stack_manager: event_clean_up_stack finished.
08-03 21:22:36.600  2545  2545 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-03 21:22:36.604  2545  2545 I art     : System.exit called, status: 0
,08-03 21:22:36.604  2545  2545 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-03 21:22:36.682   870  1693 I ActivityManager: Process com.android.bluetooth (pid 2545) has died
,08-03 21:22:36.898  3824  3844 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-03 21:22:36.898  3824  3844 I Babel_SMS: MmsConfig.loadMmsSettings
08-03 21:22:36.900  3824  3844 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
08-03 21:22:36.900  3824  3844 I Babel_SMS: MmsConfig.loadFromDatabase
,08-03 21:22:36.925  3824  3844 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-03 21:22:36.925  3824  3844 I Babel_SMS: MmsConfig.loadFromResources
08-03 21:22:36.926  3824  3844 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-03 21:22:36.931  3824  3844 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-03 21:22:36.945  3824  3824 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 21:22:36.948  3824  3824 I Babel_Crash: startup - clean
,08-03 21:22:36.983  3793  3817 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-03 21:22:36.987  3824  3824 I Babel_telephony: TeleModule.launchCompleted
,08-03 21:22:37.000   870  2850 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-03 21:22:37.012  3824  3824 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-03 21:22:37.020  3824  3824 W Babel   : BAM#gBA: invalid account id: -1
,08-03 21:22:37.020  3824  3824 W Babel   : BAM#gBA: invalid account id: -1
,08-03 21:22:37.029  3824  3849 I Babel   : deleted: false for 0
,08-03 21:22:37.030  3824  3824 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-03 21:22:37.041   870  1693 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-03 21:22:37.070  1720  1720 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-03 21:22:37.077  1720  1720 D SystemUpdateService: onCreate
,08-03 21:22:37.086  1720  1720 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-03 21:22:37.102  1720  3851 I SystemUpdateService: active receiver: enabled
08-03 21:22:37.102  1720  1720 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-03 21:22:37.105  1720  2360 I iu.UploadsManager: num queued entries: 0
08-03 21:22:37.106  1720  2360 I iu.UploadsManager: num updated entries: 0
08-03 21:22:37.107  1720  2360 I iu.SyncManager: NEXT; no task
,08-03 21:22:37.109  1720  1720 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-03 21:22:37.110  1720  1720 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-03 21:22:37.112  1720  3851 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-03 21:22:37.113  1720  3851 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-03 21:22:37.113  1720  3851 I SystemUpdateService: now status is 0 (complete)
08-03 21:22:37.113  1720  3851 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-03 21:22:37.113  1720  3851 I SystemUpdateService: file has been verified
08-03 21:22:37.114  1720  3851 I SystemUpdateService: OTA package size = 12249756
,08-03 21:22:37.116  1720  3851 I SystemUpdateService: showing system update notification
,08-03 21:22:37.130   870  1734 I ActivityManager: Start proc 3853:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-03 21:22:37.141  3824  3824 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-03 21:22:37.142  1720  1720 D SystemUpdateService: onDestroy
,08-03 21:22:37.203  3853  3853 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-03 21:22:37.215  3853  3853 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-03 21:22:37.225  3853  3853 D SprintDMHelper: simOperator: 
,08-03 21:22:37.225  3853  3853 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-03 21:22:37.251  3824  3824 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-03 21:22:37.257  3824  3824 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-03 21:22:37.262   870  1682 I ActivityManager: Start proc 3866:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-03 21:22:37.271   870   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6449afa:true
,08-03 21:22:37.271  3824  3824 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-03 21:22:37.275  3824  3824 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-03 21:22:37.300  3824  3824 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-03 21:22:37.308   870   881 I ActivityManager: Killing 2950:android.process.acore/u0a5 (adj 15): empty #17
,08-03 21:22:37.438  3824  3824 I vclib   : onServiceConnected
,08-03 21:22:37.500   870   881 I ActivityManager: Start proc 3882:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-03 21:22:37.502  3824  3880 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-03 21:22:37.506   870  1702 I ActivityManager: Killing 3457:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-03 21:22:37.563  3882  3882 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-03 21:22:37.622  3882  3882 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-03 21:22:37.622  3882  3882 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-03 21:22:37.622  3882  3882 I GAv4    :   adb logcat -s GAv4
,08-03 21:22:37.640  3882  3882 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-03 21:22:37.646  3882  3882 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-03 21:22:37.678  3882  3899 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-03 21:22:37.794  3882  3882 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-03 21:22:37.834  3882  3882 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-03 21:22:37.843  3882  3882 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2366-2369)
,08-03 21:22:37.848  3882  3882 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-03 21:22:37.856  3882  3882 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a2764eb}
,08-03 21:22:37.857  3882  3882 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-03 21:22:37.857  3882  3882 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-03 21:22:37.865  3882  3882 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-03 21:22:37.866  3882  3882 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-03 21:22:37.882  3882  3882 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-03 21:22:37.893  3882  3882 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-03 21:22:37.893  3882  3882 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-03 21:22:37.893  3882  3882 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-03 21:22:37.893  3882  3882 I Adreno  : Build Date                       : 10/20/15
08-03 21:22:37.893  3882  3882 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-03 21:22:37.893  3882  3882 I Adreno  : Local Branch                     : M14
08-03 21:22:37.893  3882  3882 I Adreno  : Remote Branch                    : 
08-03 21:22:37.893  3882  3882 I Adreno  : Remote Branch                    : 
08-03 21:22:37.893  3882  3882 I Adreno  : Reconstruct Branch               : 
,08-03 21:22:37.941  3882  3928 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-03 21:22:37.954  3882  3882 I NSApplication: Starting up...
,08-03 21:22:37.981   870  1819 I ActivityManager: Start proc 3933:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-03 21:22:37.982   870  1819 I ActivityManager: Killing 3498:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-03 21:22:38.077  3933  3933 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-03 21:22:38.238   870  1702 I ActivityManager: Killing 3513:com.android.musicfx/u0a18 (adj 15): empty #17
,08-03 21:22:39.115   870  1379 D WifiService: setWifiEnabled: true pid=3718, uid=10000
08-03 21:22:39.115   870  1379 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 21:22:39.130   870  1310 D WifiConfigStore: Loading config and enabling all networks 
,08-03 21:22:39.139  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 21:22:39.140  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 21:22:39.140  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:39.140  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:39.140  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 21:22:39.140  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 21:22:39.140  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 21:22:39.140  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 21:22:39.140  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 21:22:39.140  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 21:22:39.140  3718  3718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 21:22:39.145  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 21:22:39.145  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 21:22:39.145  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:39.145  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:39.145  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 21:22:39.145  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 21:22:39.145  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 21:22:39.145  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 21:22:39.145  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 21:22:39.145  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 21:22:39.146  3718  3718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 21:22:39.178   870  1310 D WifiConfigStore: loaded 0 passpoint configs
,08-03 21:22:39.178   870  1310 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-03 21:22:39.179   870  1310 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-03 21:22:39.180   870  1310 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-03 21:22:39.181   870  1310 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-03 21:22:39.181   870  1310 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-03 21:22:39.181   870  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-03 21:22:39.181   870  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-03 21:22:39.194   870  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-03 21:22:39.194   370   868 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-03 21:22:39.196   370   868 D CommandListener: Setting iface cfg
,08-03 21:22:39.205   870  1308 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
,08-03 21:22:39.205   870  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-03 21:22:39.206   870  1310 E native  : do suspend true
,08-03 21:22:39.220   870  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 21:22:39.248   870  1308 D WifiNative-HAL: p2pGetDeviceAddress
,08-03 21:22:39.249   870  1308 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-03 21:22:40.594   870  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-03 21:22:40.651   870  1310 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.25 rxSuccessRate=20.06 delta 1000 -> 994
,08-03 21:22:40.656   870  1310 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-03 21:22:40.656   870  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 21:22:40.680   870  1310 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-03 21:22:40.739   870  1310 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-03 21:22:40.740  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-03 21:22:41.168  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-03 21:22:41.211  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-03 21:22:41.212  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-03 21:22:41.217   870  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 21:22:41.235   870  1310 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-03 21:22:41.236   870  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-03 21:22:41.236   870  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 21:22:41.251   870  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 21:22:41.262   370   868 D CommandListener: Setting iface cfg
,08-03 21:22:41.263   870  1310 D WifiStateMachine: Start Dhcp Watchdog 2,
,08-03 21:22:41.269   870  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-03 21:22:41.313   870  3955 D DhcpClient: Receive thread started
,08-03 21:22:41.394   870  1310 E native  : do suspend false
,08-03 21:22:41.405   870  2111 D DhcpClient: Broadcasting DHCPDISCOVER
,08-03 21:22:41.416   870  3955 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172438, domain null
,08-03 21:22:41.416   870  2111 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172438 seconds
,08-03 21:22:41.416   870  2111 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-03 21:22:41.428   870  3955 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-03 21:22:41.429   870  2111 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-03 21:22:41.430   370   868 D CommandListener: Setting iface cfg
,08-03 21:22:41.434   870  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-03 21:22:41.436   870  2111 D DhcpClient: Scheduling renewal in 86399s
08-03 21:22:41.436   870  1310 E native  : do suspend true
,08-03 21:22:41.453   870  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-03 21:22:41.453   870  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,08-03 21:22:41.454   870  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-03 21:22:41.458   870  1312 D ConnectivityService: Adding iface wlan0 to network 101
08-03 21:22:41.460   870  1310 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-03 21:22:41.525   870  1312 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-03 21:22:41.525   870  1312 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-03 21:22:41.526   870  1312 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-03 21:22:41.528   870  1312 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-03 21:22:41.529   870  1312 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-03 21:22:41.540   870  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-03 21:22:41.547   870  1312 D ConnectivityService: scheduleUnvalidatedPrompt 101
08-03 21:22:41.547   870  1312 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-03 21:22:41.547   870  1312 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-03 21:22:41.547   870  1310 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-03 21:22:41.547   870  1312 D ConnectivityService:    accepting network in place of null
08-03 21:22:41.548   870  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-03 21:22:41.549   870  1312 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-03 21:22:41.561   870  3954 D NetlinkSocketObserver: NeighborEvent{elapsedMs=386087, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-03 21:22:41.604   370   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 21:22:41.642   370   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 21:22:41.647   870  3953 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
08-03 21:22:41.650   870  1312 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-03 21:22:41.650   870  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 21:22:41.655   870  1312 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-03 21:22:41.657   870   888 D Tethering: MasterInitialState.processMessage what=3
,08-03 21:22:41.665  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 21:22:41.665  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 21:22:41.665  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:41.665  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:41.665  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 21:22:41.665  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 21:22:41.665  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 21:22:41.665  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 21:22:41.665  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 21:22:41.665  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 21:22:41.665  3718  3718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 21:22:41.667  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 21:22:41.667  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 21:22:41.667  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:41.667  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:41.667  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 21:22:41.667  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 21:22:41.667  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 21:22:41.667  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 21:22:41.667  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 21:22:41.667  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 21:22:41.667  3718  3718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 21:22:41.683  1720  1720 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-03 21:22:41.684  1825  1825 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-03 21:22:41.685  1720  1720 D SystemUpdateService: onCreate
,08-03 21:22:41.688  1720  1720 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-03 21:22:41.693  1720  3965 I SystemUpdateService: active receiver: enabled
,08-03 21:22:41.698  1720  3965 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-03 21:22:41.701  1720  3965 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-03 21:22:41.701  1720  3965 I SystemUpdateService: now status is 0 (complete)
08-03 21:22:41.701  1720  3965 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-03 21:22:41.702  1720  3965 I SystemUpdateService: file has been verified
08-03 21:22:41.702  1720  3965 I SystemUpdateService: OTA package size = 12249756
,08-03 21:22:41.710  1720  3965 I SystemUpdateService: showing system update notification
,08-03 21:22:41.718  1720  1720 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-03 21:22:41.722  1720  2360 I iu.UploadsManager: num queued entries: 0
,08-03 21:22:41.722  1720  2360 I iu.UploadsManager: num updated entries: 0
,08-03 21:22:41.723  1720  2360 I iu.SyncManager: NEXT; no task
,08-03 21:22:41.727  1720  1720 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-03 21:22:41.728  1720  1720 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-03 21:22:41.729  1720  3969 I MDM     : [192] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-03 21:22:41.729  1720  3969 W BaseAppContext: Using Auth Proxy for data requests.
08-03 21:22:41.731  3853  3853 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-03 21:22:41.731  1720  3969 V GoogleAuthProtoRequest: [192] a.<init>: mAccountName set to: thalitester@gmail.com
,08-03 21:22:41.734  1720  1720 D SystemUpdateService: onDestroy
,08-03 21:22:41.734  3853  3853 D SprintDMHelper: simOperator: 
08-03 21:22:41.734  3853  3853 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-03 21:22:41.740  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:22:41.742  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:22:41.756  3824  3824 I art     : Waiting for a blocking GC DisableMovingGc
,08-03 21:22:41.759   870  3953 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Aug 2016 19:22:41 GMT], X-Android-Received-Millis=[1470252161758], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470252161711]}
,08-03 21:22:41.760  3824  3824 I art     : Starting a blocking GC DisableMovingGc
,08-03 21:22:41.764   870  1312 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-03 21:22:41.764   870  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-03 21:22:41.764   870  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-03 21:22:41.765   870  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-03 21:22:41.784  1500  2042 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-03 21:22:41.784  1500  2042 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-03 21:22:41.784  1500  2042 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 21:22:41.784  1500  2042 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:22:41.805  1720  3969 E MDM     : [192] SitrepService.a: Error sending sitrep.
,08-03 21:22:41.926  3824  3973 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-03 21:22:41.930   870  2850 I ActivityManager: Killing 3304:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-03 21:22:42.120   870  1379 D WifiService: setWifiEnabled: false pid=3718, uid=10000
,08-03 21:22:42.121   870  1379 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 21:22:42.143  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-03 21:22:42.146   870  1310 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-03 21:22:42.147   870  1310 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-03 21:22:42.147   870  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-03 21:22:42.147   870  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 21:22:42.168   870  1310 E native  : do suspend true
,08-03 21:22:42.178   870  2111 D DhcpClient: Clearing IP address
08-03 21:22:42.178   370   868 D CommandListener: Clearing all IP addresses on wlan0
,08-03 21:22:42.188  1500  3978 V NativeCrypto: Read error: ssl=0x99678000: I/O error during system call, Connection timed out
,08-03 21:22:42.195  1500  3978 V NativeCrypto: SSL shutdown failed: ssl=0x99678000: I/O error during system call, Broken pipe
,08-03 21:22:42.195   370   868 D CommandListener: Setting iface cfg
,08-03 21:22:42.198   870  3955 D DhcpClient: Receive thread stopped
08-03 21:22:42.201   870  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-03 21:22:42.201   870  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-03 21:22:42.209   400   400 E Parcel  : Reading a NULL string not supported here.
08-03 21:22:42.210   870  1310 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-03 21:22:42.215   870  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-03 21:22:42.215   870  1310 E native  : do suspend true
,08-03 21:22:42.224   370   868 D CommandListener: Clearing all IP addresses on wlan0
08-03 21:22:42.225   870  1312 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-03 21:22:42.231   870  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-03 21:22:42.246   870  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 21:22:42.248  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 21:22:42.248  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 21:22:42.248  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:42.248  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:42.248  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 21:22:42.248  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 21:22:42.248  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 21:22:42.248  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,08-03 21:22:42.248  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 21:22:42.248  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 21:22:42.248  3718  3718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 21:22:42.249  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 21:22:42.249  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 21:22:42.249  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:42.249  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
08-03 21:22:42.249  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 21:22:42.249  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 21:22:42.249  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 21:22:42.249  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 21:22:42.249  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 21:22:42.249  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 21:22:42.250  3718  3718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 21:22:42.253   870  1310 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-03 21:22:42.255  1694  2052 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 21:22:42.264   370   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 21:22:42.290   370   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 21:22:42.292   870  1312 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-03 21:22:42.292   870  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 21:22:42.298   870   888 D Tethering: MasterInitialState.processMessage what=3
,08-03 21:22:42.300  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 21:22:42.303  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:22:42.315  1825  1825 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-03 21:22:42.318  1720  1720 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-03 21:22:42.322  1720  1720 D SystemUpdateService: onCreate
,08-03 21:22:42.326  1720  1720 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-03 21:22:42.341  1720  1720 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-03 21:22:42.347  1720  2360 I iu.UploadsManager: num queued entries: 0
,08-03 21:22:42.355  1720  1720 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-03 21:22:42.356  1720  1720 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-03 21:22:42.358  3853  3853 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-03 21:22:42.362  3853  3853 D SprintDMHelper: simOperator: 
08-03 21:22:42.362  3853  3853 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-03 21:22:42.367  1720  2360 I iu.UploadsManager: num updated entries: 0
,08-03 21:22:42.368  1720  2360 I iu.SyncManager: NEXT; no task
,08-03 21:22:42.372   370   868 E Netd    : netlink response contains error (No such file or directory)
,08-03 21:22:42.374  1720  3988 I SystemUpdateService: active receiver: enabled
,08-03 21:22:42.375   870  1312 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-03 21:22:42.387  3824  3992 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-03 21:22:42.388  1720  3988 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-03 21:22:42.391  1720  3988 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-03 21:22:42.391  1720  3988 I SystemUpdateService: now status is 0 (complete)
,08-03 21:22:42.391  1720  3988 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-03 21:22:42.391  1720  3988 I SystemUpdateService: file has been verified
08-03 21:22:42.391  1720  3988 I SystemUpdateService: OTA package size = 12249756
,08-03 21:22:42.398  1720  3988 I SystemUpdateService: showing system update notification
,08-03 21:22:42.428  1720  1720 D SystemUpdateService: onDestroy
,08-03 21:22:42.647   870  1312 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-03 21:22:45.174   870   888 I ActivityManager: Start proc 3994:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-03 21:22:45.294  3994  3994 D AdapterServiceConfig: Adding HeadsetService
,08-03 21:22:45.295  3994  3994 D AdapterServiceConfig: Adding A2dpService
08-03 21:22:45.295  3994  3994 D AdapterServiceConfig: Adding HidService
,08-03 21:22:45.295  3994  3994 D AdapterServiceConfig: Adding HealthService
,08-03 21:22:45.295  3994  3994 D AdapterServiceConfig: Adding PanService
,08-03 21:22:45.295  3994  3994 D AdapterServiceConfig: Adding GattService
,08-03 21:22:45.296  3994  3994 D AdapterServiceConfig: Adding BluetoothMapService
,08-03 21:22:45.309   870   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d3defc2:true
,08-03 21:22:45.310  3994  3994 D BluetoothAdapterState: make() - Creating AdapterState
,08-03 21:22:45.314  3994  3994 I bt_bluedroid: init
,08-03 21:22:45.315  3994  4006 I BluetoothAdapterState: Entering OffState
,08-03 21:22:45.323  3994  4007 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-03 21:22:45.324  3994  4007 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-03 21:22:45.324  3994  4007 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-03 21:22:45.325  3994  4007 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-03 21:22:45.328  3994  3994 I bt_bluedroid: get_profile_interface socket
,08-03 21:22:45.331  3994  3994 I bt_bluedroid: get_profile_interface sdp
,08-03 21:22:45.333  3994  4010 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-03 21:22:45.335  3994  4010 D BluetoothAdapterProperties: Name is: Nexus 6
,08-03 21:22:45.335  3994  4005 I bt_bluedroid: config_hci_snoop_log
,08-03 21:22:45.339   870   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-03 21:22:45.352  3994  4006 D BluetoothAdapterState: Current state: OFF, message: 0
,08-03 21:22:45.352  3994  4006 D BluetoothAdapterProperties: Setting state to 14
,08-03 21:22:45.353  3994  4006 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-03 21:22:45.358  3994  4006 D BluetoothBondStateMachine: make
,08-03 21:22:45.362  3994  4012 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-03 21:22:45.370  3994  4006 I BluetoothAdapterState: Entering PendingCommandState
,08-03 21:22:45.372  3994  3994 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-03 21:22:45.377  3994  3994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81c6679
,08-03 21:22:45.379  3994  3994 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-03 21:22:45.380  3994  3994 D BtGatt.GattService: Received start request. Starting profile...
08-03 21:22:45.380  3994  3994 D BtGatt.GattService: start()
,08-03 21:22:45.380  3994  3994 I bt_bluedroid: get_profile_interface gatt
08-03 21:22:45.382  3994  3994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81c6679
08-03 21:22:45.382  3994  3994 D BtGatt.AdvertiseManager: advertise manager created
,08-03 21:22:45.399  3994  3994 V BluetoothAdapterState: isTurningOff()=false
,08-03 21:22:45.399  3994  3994 V BluetoothAdapterState: isTurningOn()=false
,08-03 21:22:45.400  3994  3994 V BluetoothAdapterState: isBleTurningOn()=true
08-03 21:22:45.400  3994  3994 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 21:22:45.402  3994  4006 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-03 21:22:45.402  3994  4006 I bt_bluedroid: enable
,08-03 21:22:45.403  3994  4007 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-03 21:22:45.404  3994  4007 I bt_hci  : start_up
,08-03 21:22:45.425  3994  4007 I bt_vendor: alloc value 0xb39ec189
,08-03 21:22:45.425  3994  4007 I bt_vendor: init
08-03 21:22:45.425  3994  4007 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-03 21:22:45.426  3994  4007 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-03 21:22:45.535  3994  4007 D bt_hci  : start_up starting async portion
,08-03 21:22:45.535  3994  4015 I bt_hci  : event_finish_startup
,08-03 21:22:45.536  3994  4015 I bt_hci_h4: hal_open
,08-03 21:22:45.536  3994  4015 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-03 21:22:45.546  3994  4015 I bt_userial_vendor: device fd = 51 open
,08-03 21:22:45.578  3994  4015 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-03 21:22:45.609  3994  4015 D bt_hwcfg: Chipset BCM4354A2
,08-03 21:22:45.610  3994  4015 D bt_hwcfg: Target name = [BCM4354A2]
08-03 21:22:45.611  3994  4015 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-03 21:22:46.265  3994  4015 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-03 21:22:46.266  3994  4015 D bt_hwcfg: Settlement delay -- 100 ms
08-03 21:22:46.267  3994  4015 I bt_hwcfg: Setting fw settlement delay to 100 
,08-03 21:22:46.384  3994  4015 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-03 21:22:46.385  3994  4015 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-03 21:22:46.414  3994  4015 I bt_hwcfg: vendor lib fwcfg completed
,08-03 21:22:46.414  3994  4015 I bt_vendor: firmware callback
,08-03 21:22:46.414  3994  4015 I bt_hci  : firmware_config_callback
,08-03 21:22:46.425  3994  4017 I bt_btu  : btu_task pending for preload complete event
,08-03 21:22:46.426  3994  4017 I bt_btu_task: Bluetooth chip preload is complete
08-03 21:22:46.426  3994  4017 I bt_btu  : btu_task received preload complete event
,08-03 21:22:46.436  3994  4017 I         : BTE_InitTraceLevels -- TRC_HCI
,08-03 21:22:46.437  3994  4017 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-03 21:22:46.437  3994  4017 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-03 21:22:46.437  3994  4017 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-03 21:22:46.438  3994  4017 I         : BTE_InitTraceLevels -- TRC_AVRC
08-03 21:22:46.438  3994  4017 I         : BTE_InitTraceLevels -- TRC_A2D
08-03 21:22:46.438  3994  4017 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-03 21:22:46.438  3994  4017 I         : BTE_InitTraceLevels -- TRC_BTM
08-03 21:22:46.439  3994  4017 I         : BTE_InitTraceLevels -- TRC_GAP
08-03 21:22:46.439  3994  4017 I         : BTE_InitTraceLevels -- TRC_PAN
,08-03 21:22:46.439  3994  4017 I         : BTE_InitTraceLevels -- TRC_SDP
08-03 21:22:46.439  3994  4017 I         : BTE_InitTraceLevels -- TRC_GATT
08-03 21:22:46.440  3994  4017 I         : BTE_InitTraceLevels -- TRC_SMP
,08-03 21:22:46.440  3994  4017 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-03 21:22:46.440  3994  4017 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-03 21:22:46.573  3994  4017 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3969d9d
,08-03 21:22:46.574  3994  4017 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3969d9d 
,08-03 21:22:46.586  3994  4010 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-03 21:22:46.588  3994  4010 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-03 21:22:46.589  3994  4010 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-03 21:22:46.592  3994  4010 D BluetoothAdapterProperties: Name is: Nexus 6
,08-03 21:22:46.600  3994  4010 D BluetoothAdapterProperties: Scan Mode:20
,08-03 21:22:46.600  3994  4010 D BluetoothAdapterProperties: Discoverable Timeout:120,
,08-03 21:22:46.601  3994  4010 D bt_hci  : do_postload posting postload work item
,08-03 21:22:46.601  3994  4015 I bt_hci  : event_postload
08-03 21:22:46.601  3994  4015 I bt_vendor: sco_config_cb
,08-03 21:22:46.601  3994  4015 I bt_hci  : sco_config_callback postload finished.
08-03 21:22:46.607  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 21:22:46.608  3994  4010 D bt_bte_conf: Device ID record 1 : primary
08-03 21:22:46.608  3994  4010 D bt_bte_conf:   vendorId            = 000f
08-03 21:22:46.608  3994  4010 D bt_bte_conf:   vendorIdSource      = 0001
08-03 21:22:46.609  3994  4010 D bt_bte_conf:   product             = 1200
,08-03 21:22:46.609  3994  4010 D bt_bte_conf:   version             = 1436
08-03 21:22:46.609  3994  4010 D bt_bte_conf:   clientExecutableURL = 
08-03 21:22:46.609  3994  4010 D bt_bte_conf:   serviceDescription  = 
08-03 21:22:46.609  3994  4010 D bt_bte_conf:   documentationURL    = 
08-03 21:22:46.610  3994  4010 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-03 21:22:46.610  3994  4007 D bt_stack_manager: event_start_up_stack finished
08-03 21:22:46.611  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 21:22:46.612  3994  4006 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-03 21:22:46.613  3994  4006 D BluetoothAdapterProperties: Setting state to 15
08-03 21:22:46.613  3994  4006 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-03 21:22:46.615  3994  4015 I bt_vendor: low_power_mode_cb
08-03 21:22:46.616  3994  4006 I BluetoothAdapterState: Entering BleOnState
,08-03 21:22:46.619  3994  4006 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-03 21:22:46.619  3994  4006 D BluetoothAdapterProperties: Setting state to 11
08-03 21:22:46.619  3994  4006 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-03 21:22:46.625  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:22:46.626  3994  3994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81c6679
08-03 21:22:46.626  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 21:22:46.627  3994  3994 D HeadsetService: Received start request. Starting profile...
08-03 21:22:46.630  3994  3994 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-03 21:22:46.630  3994  3994 D HeadsetStateMachine: make
,08-03 21:22:46.637  3994  4006 I BluetoothAdapterState: Entering PendingCommandState
,08-03 21:22:46.641  3994  3994 D HeadsetStateMachine: max_hf_connections = 1,
,08-03 21:22:46.641  3994  3994 I bt_bluedroid: get_profile_interface handsfree
,08-03 21:22:46.641  3994  4010 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-03 21:22:46.641  3994  4010 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-03 21:22:46.649  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 21:22:46.649  3994  3994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81c6679
08-03 21:22:46.650  3994  3994 D A2dpService: Received start request. Starting profile...
,08-03 21:22:46.651  3994  3994 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-03 21:22:46.651  3994  3994 I bt_bluedroid: get_profile_interface avrcp
,08-03 21:22:46.657  3994  3994 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-03 21:22:46.657  3994  3994 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-03 21:22:46.657  3994  3994 D A2dpStateMachine: make
08-03 21:22:46.659  3994  3994 I bt_bluedroid: get_profile_interface a2dp
,08-03 21:22:46.659  3994  4010 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-03 21:22:46.662  3994  4025 D A2dpStateMachine: Enter Disconnected: -2
,08-03 21:22:46.663  3994  3994 I BluetoothHidServiceJni: classInitNative: succeeds
,08-03 21:22:46.665  3994  3994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81c6679
,08-03 21:22:46.666  3994  3994 D HidService: Received start request. Starting profile...
08-03 21:22:46.666  3773  3773 D BluetoothInputDevice: Proxy object connected
08-03 21:22:46.666  3994  3994 I bt_bluedroid: get_profile_interface hidhost
,08-03 21:22:46.666  3994  4010 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb394b3e5
08-03 21:22:46.666  3994  4010 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-03 21:22:46.666  3994  3994 D HidService: setHidService(): set to: null
08-03 21:22:46.666  3773  3773 D HidProfile: Bluetooth service connected
08-03 21:22:46.667  3994  3994 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-03 21:22:46.668  3994  3994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81c6679
08-03 21:22:46.668  3994  3994 D HealthService: Received start request. Starting profile...
,08-03 21:22:46.670  3994  3994 I bt_bluedroid: get_profile_interface health
,08-03 21:22:46.670  3994  3994 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-03 21:22:46.671  3994  3994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81c6679
,08-03 21:22:46.672  3994  3994 D PanService: Received start request. Starting profile...
08-03 21:22:46.672  3773  3773 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 21:22:46.672  3994  3994 D BluetoothPanServiceJni: initializeNative(L110): pan
08-03 21:22:46.672  3994  3994 I bt_bluedroid: get_profile_interface pan
,08-03 21:22:46.673  3994  4010 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-03 21:22:46.673  3773  3773 D PanProfile: Bluetooth service connected
,08-03 21:22:46.676  3994  3994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81c6679
,08-03 21:22:46.677  3773  3773 D BluetoothMap: Proxy object connected
08-03 21:22:46.677  3994  3994 D BluetoothMapService: Received start request. Starting profile...
08-03 21:22:46.677  3994  3994 D BluetoothMapService: start()
08-03 21:22:46.678  3773  3773 D MapProfile: Bluetooth service connected
08-03 21:22:46.678  3773  3773 D BluetoothMap: getConnectedDevices()
08-03 21:22:46.678  3773  3773 D BluetoothMap: Bluetooth is Not enabled
,08-03 21:22:46.680  3994  3994 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-03 21:22:46.680  3994  3994 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-03 21:22:46.681  3994  3994 D BluetoothMapAppObserver: createReceiver()
08-03 21:22:46.682  3994  3994 D BluetoothMapAppObserver: initObservers()
,08-03 21:22:46.682  3994  3994 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-03 21:22:46.690  3994  3994 V BluetoothAdapterState: isTurningOff()=false
08-03 21:22:46.690  3994  3994 V BluetoothAdapterState: isTurningOn()=true
08-03 21:22:46.690  3994  3994 V BluetoothAdapterState: isBleTurningOn()=false
08-03 21:22:46.690  3994  3994 V BluetoothAdapterState: isBleTurningOff()=false
08-03 21:22:46.691  3994  4023 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-03 21:22:46.693  3994  3994 V BluetoothAdapterState: isTurningOff()=false
08-03 21:22:46.694  3994  3994 V BluetoothAdapterState: isTurningOn()=true
08-03 21:22:46.694  3994  3994 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 21:22:46.694  3994  3994 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 21:22:46.695  3994  3994 V BluetoothAdapterState: isTurningOff()=false
08-03 21:22:46.695  3994  3994 V BluetoothAdapterState: isTurningOn()=true
,08-03 21:22:46.695  3994  3994 V BluetoothAdapterState: isBleTurningOn()=false
08-03 21:22:46.696  3994  3994 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 21:22:46.697  3994  3994 V BluetoothAdapterState: isTurningOff()=false
08-03 21:22:46.697  3994  3994 V BluetoothAdapterState: isTurningOn()=true
,08-03 21:22:46.697  3994  3994 V BluetoothAdapterState: isBleTurningOn()=false
08-03 21:22:46.698  3994  3994 V BluetoothAdapterState: isBleTurningOff()=false
08-03 21:22:46.698  3994  3994 V BluetoothAdapterState: isTurningOff()=false
,08-03 21:22:46.699  3994  3994 V BluetoothAdapterState: isTurningOn()=true
08-03 21:22:46.699  3994  3994 V BluetoothAdapterState: isBleTurningOn()=false
08-03 21:22:46.699  3994  3994 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 21:22:46.700  3994  3994 V BluetoothAdapterState: isTurningOff()=false
08-03 21:22:46.700  3994  3994 V BluetoothAdapterState: isTurningOn()=true
08-03 21:22:46.700  3994  3994 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 21:22:46.700  3994  3994 V BluetoothAdapterState: isBleTurningOff()=false
08-03 21:22:46.701  3994  4006 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-03 21:22:46.701  3994  4006 D BluetoothAdapterProperties: ScanMode =  20
,08-03 21:22:46.701  3994  4006 D BluetoothAdapterProperties: State =  11
,08-03 21:22:46.703  3994  4010 D BluetoothAdapterProperties: Scan Mode:21
,08-03 21:22:46.703  3994  4006 D BluetoothAdapterProperties: Setting state to 12
,08-03 21:22:46.703  3994  4006 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-03 21:22:46.703  3994  4010 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-03 21:22:46.704  3994  4006 I BluetoothAdapterState: Entering OnState
08-03 21:22:46.704  3773  3783 D BluetoothMap: onBluetoothStateChange: up=true
08-03 21:22:46.705  1366  1807 D BluetoothMap: onBluetoothStateChange: up=true
08-03 21:22:46.708   870   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 21:22:46.708  1366  1366 D BluetoothMap: Proxy object connected
08-03 21:22:46.708  1366  1366 D MapProfile: Bluetooth service connected
08-03 21:22:46.708  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 21:22:46.708  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:46.708  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:46.708  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 21:22:46.708  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 21:22:46.708  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 21:22:46.708  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 21:22:46.708  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 21:22:46.708  1366  1366 D BluetoothMap: getConnectedDevices()
,08-03 21:22:46.708  1366  1378 D BluetoothPan: onBluetoothStateChange on: true
08-03 21:22:46.709  1366  1807 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-03 21:22:46.710  1366  1366 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 21:22:46.710  1366  1366 D PanProfile: Bluetooth service connected
08-03 21:22:46.710  3994  3994 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-03 21:22:46.711  3718  3718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 21:22:46.711  1366  1366 D BluetoothInputDevice: Proxy object connected
08-03 21:22:46.711  1366  1366 D HidProfile: Bluetooth service connected
,08-03 21:22:46.711  3773  3785 D BluetoothPbap: onBluetoothStateChange: up=true
08-03 21:22:46.711  3994  3994 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-03 21:22:46.713   870   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 21:22:46.713   870   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 21:22:46.713   870   888 D BluetoothA2dp: onBluetoothStateChange: up=true
08-03 21:22:46.714  1366  1378 D BluetoothPbap: onBluetoothStateChange: up=true
08-03 21:22:46.715  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 21:22:46.715  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:46.715  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:46.715  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 21:22:46.715  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 21:22:46.715  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 21:22:46.715  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 21:22:46.715  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 21:22:46.716  1366  1807 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 21:22:46.716  3994  3994 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 21:22:46.716  3773  3783 D BluetoothPan: onBluetoothStateChange on: true
08-03 21:22:46.717  3773  3785 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-03 21:22:46.717  3718  3718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 21:22:46.717  1366  1374 D BluetoothA2dp: onBluetoothStateChange: up=true
08-03 21:22:46.719  1772  1894 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 21:22:46.722   870   870 I Telecom : BluetoothPhoneService: queryPhoneState
08-03 21:22:46.723  3994  3994 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 21:22:46.725  3773  3773 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-03 21:22:46.725  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 21:22:46.725  3994  3994 D ObexServerSockets: Succeed to create listening sockets 
08-03 21:22:46.726  3994  3994 D ObexServerSockets0: startAccept()
08-03 21:22:46.726  3994  3994 D ObexServerSockets0: prepareForNewConnect()
08-03 21:22:46.727  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:22:46.732  3994  4033 D ObexServerSockets0: Accepting socket connection...
,08-03 21:22:46.732  3994  3994 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-03 21:22:46.733  3994  4034 D ObexServerSockets0: Accepting socket connection...
08-03 21:22:46.733  3773  3773 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-03 21:22:46.733  3994  3994 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-03 21:22:46.736   870   870 D BluetoothA2dp: Proxy object connected
08-03 21:22:46.737  3994  3994 D BluetoothMapService: onReceive
,08-03 21:22:46.737  3994  3994 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 21:22:46.738  3994  3994 D BluetoothMapService: STATE_ON
,08-03 21:22:46.741  3773  3773 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-03 21:22:46.744  3773  3773 D BluetoothA2dp: Proxy object connected
,08-03 21:22:46.748  1366  1366 D BluetoothA2dp: Proxy object connected
,08-03 21:22:46.750  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 21:22:46.756  3773  3773 D DockEventReceiver: finishStartingService: stopping service
,08-03 21:22:46.756  1366  1366 D BluetoothPbap: Proxy object connected
08-03 21:22:46.756  1366  1366 D PbapServerProfile: Bluetooth service connected
08-03 21:22:46.758  3773  3773 D BluetoothPbap: Proxy object connected
,08-03 21:22:46.759  3773  3773 D PbapServerProfile: Bluetooth service connected
,08-03 21:22:46.765  3994  3994 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-03 21:22:46.765  3994  3994 D ObexServerSockets0: prepareForNewConnect()
08-03 21:22:46.768  3994  4038 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 21:22:46.785  3994  4042 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 21:22:46.787  3994  4042 I BtOppRfcommListener: Accept thread started.
,08-03 21:22:46.810  1772  1790 D BluetoothHeadset: Proxy object connected
,08-03 21:22:46.810   870   870 D BluetoothHeadset: Proxy object connected
,08-03 21:22:46.811  1366  1807 D BluetoothHeadset: Proxy object connected
,08-03 21:22:46.811  1366  1366 D HeadsetProfile: Bluetooth service connected
08-03 21:22:46.811   870   870 D BluetoothHeadset: Proxy object connected
08-03 21:22:46.811   870   870 D BluetoothHeadset: Proxy object connected
,08-03 21:22:46.813   870   888 D BluetoothHeadset: Proxy object connected
08-03 21:22:46.813   870   888 D BluetoothHeadset: Proxy object connected
,08-03 21:22:46.817  1366  1374 D BluetoothHeadset: Proxy object connected
,08-03 21:22:46.817  1366  1366 D HeadsetProfile: Bluetooth service connected
,08-03 21:22:46.820  1772  1797 D BluetoothHeadset: Proxy object connected
,08-03 21:22:46.836  3773  3783 D BluetoothHeadset: Proxy object connected
08-03 21:22:46.837  3773  3773 D HeadsetProfile: Bluetooth service connected
,08-03 21:22:48.138  3994  4006 D BluetoothAdapterState: Current state: ON, message: 23
,08-03 21:22:48.139  3994  4006 D BluetoothAdapterProperties: Setting state to 13
,08-03 21:22:48.139  3994  4006 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-03 21:22:48.142  3994  4006 D BluetoothAdapterProperties: onBluetoothDisable()
08-03 21:22:48.144  3994  4006 I BluetoothAdapterState: Entering PendingCommandState
08-03 21:22:48.154  3994  3994 D BluetoothMapService: onReceive
08-03 21:22:48.154  3994  3994 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 21:22:48.155  3994  3994 D BluetoothMapService: STATE_TURNING_OFF
08-03 21:22:48.156  3994  3994 D BluetoothMapService: MAP Service closeService in
08-03 21:22:48.156  3994  3994 D BluetoothMapMasInstance0: MAP Service shutdown
,08-03 21:22:48.157  3994  3994 D ObexServerSockets0: shutdown(block = true)
08-03 21:22:48.157  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 21:22:48.158  3994  4033 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-03 21:22:48.158  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 21:22:48.158  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:48.158  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:48.158  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 21:22:48.158  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 21:22:48.158  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 21:22:48.158  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 21:22:48.158  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 21:22:48.159  3994  3994 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-03 21:22:48.160  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 21:22:48.160  3994  4034 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-03 21:22:48.160  3994  4020 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-03 21:22:48.161  3718  3718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 21:22:48.161  3994  3994 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-03 21:22:48.163  3994  4010 D BluetoothAdapterProperties: Scan Mode:20
08-03 21:22:48.163  3994  3994 I BtOppRfcommListener: stopping Accept Thread
,08-03 21:22:48.163  3994  4006 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-03 21:22:48.166  3994  4042 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 21:22:48.166  3994  4042 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-03 21:22:48.170  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 21:22:48.171  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 21:22:48.171  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:48.171  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:48.171  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 21:22:48.171  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 21:22:48.171  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 21:22:48.171  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 21:22:48.171  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 21:22:48.172  3994  3994 D HeadsetService: Received stop request...Stopping profile...
08-03 21:22:48.172  3718  3718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 21:22:48.172  3718  3718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 21:22:48.174  3773  3783 D BluetoothHeadset: Proxy object disconnected
08-03 21:22:48.174  1772  2022 D BluetoothHeadset: Proxy object disconnected
08-03 21:22:48.175   870   870 D BluetoothHeadset: Proxy object disconnected
08-03 21:22:48.175  3994  3994 D A2dpService: Received stop request...Stopping profile...
,08-03 21:22:48.175  1366  1807 D BluetoothHeadset: Proxy object disconnected
08-03 21:22:48.175  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 21:22:48.175  3994  4025 D A2dpStateMachine: Exit Disconnected: -1
08-03 21:22:48.175   870   870 D BluetoothHeadset: Proxy object disconnected
08-03 21:22:48.175   870   870 D BluetoothHeadset: Proxy object disconnected
08-03 21:22:48.176  1366  1366 D HeadsetProfile: Bluetooth service disconnected
08-03 21:22:48.177  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:22:48.177  3773  3773 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-03 21:22:48.181   870   870 D BluetoothA2dp: Proxy object disconnected
08-03 21:22:48.181  1366  1366 D BluetoothA2dp: Proxy object disconnected
08-03 21:22:48.184  3994  3994 D HidService: Received stop request...Stopping profile...
08-03 21:22:48.184  3994  3994 D HidService: Stopping Bluetooth HidService
,08-03 21:22:48.184  3773  3773 D HeadsetProfile: Bluetooth service disconnected
08-03 21:22:48.185  3994  3994 V BluetoothAdapterState: isTurningOff()=true
08-03 21:22:48.185  3994  3994 V BluetoothAdapterState: isTurningOn()=false
08-03 21:22:48.185  3994  3994 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 21:22:48.185  3994  3994 V BluetoothAdapterState: isBleTurningOff()=false
08-03 21:22:48.186  1366  1366 D BluetoothInputDevice: Proxy object disconnected
08-03 21:22:48.186  1366  1366 D HidProfile: Bluetooth service disconnected
08-03 21:22:48.187  3994  3994 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-03 21:22:48.187  3994  4010 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-03 21:22:48.187  3994  4017 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 21:22:48.187  3994  4017 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 21:22:48.187  3994  4017 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-03 21:22:48.187  3994  3994 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 21:22:48.188  3994  4010 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-03 21:22:48.189  3994  3994 D HealthService: Received stop request...Stopping profile...
08-03 21:22:48.189  3773  3773 D DockEventReceiver: finishStartingService: stopping service
08-03 21:22:48.191  3994  3994 D PanService: Received stop request...Stopping profile...
08-03 21:22:48.191  3773  3773 D BluetoothA2dp: Proxy object disconnected
,08-03 21:22:48.192  3773  3773 D BluetoothInputDevice: Proxy object disconnected
08-03 21:22:48.192  3773  3773 D HidProfile: Bluetooth service disconnected
,08-03 21:22:48.192  1366  1366 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-03 21:22:48.192  1366  1366 D PanProfile: Bluetooth service disconnected
08-03 21:22:48.193  3994  3994 D BluetoothMapService: Received stop request...Stopping profile...
08-03 21:22:48.193  3994  3994 D BluetoothMapService: stop()
,08-03 21:22:48.196  3773  3773 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-03 21:22:48.196  3773  3773 D PanProfile: Bluetooth service disconnected
08-03 21:22:48.196  3994  3994 D BluetoothMapAppObserver: deinitObservers()
08-03 21:22:48.196  3994  3994 D BluetoothMapAppObserver: removeReceiver()
,08-03 21:22:48.198  1366  1366 D BluetoothMap: Proxy object disconnected
08-03 21:22:48.198  1366  1366 D MapProfile: Bluetooth service disconnected
,08-03 21:22:48.198  3994  3994 V BluetoothAdapterState: isTurningOff()=true
08-03 21:22:48.198  3994  3994 V BluetoothAdapterState: isTurningOn()=false
08-03 21:22:48.198  3994  3994 V BluetoothAdapterState: isBleTurningOn()=false
08-03 21:22:48.198  3994  3994 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 21:22:48.198  3773  3773 D BluetoothMap: Proxy object disconnected
,08-03 21:22:48.199  3773  3773 D MapProfile: Bluetooth service disconnected
08-03 21:22:48.200  3994  4017 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-03 21:22:48.200  3994  4017 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-03 21:22:48.200  3994  4017 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-03 21:22:48.201  3994  4017 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-03 21:22:48.201  3994  4017 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-03 21:22:48.201  3994  4017 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 21:22:48.201  3994  4010 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-03 21:22:48.202  3994  3994 V BluetoothAdapterState: isTurningOff()=true
08-03 21:22:48.202  3994  3994 V BluetoothAdapterState: isTurningOn()=false
08-03 21:22:48.202  3994  3994 V BluetoothAdapterState: isBleTurningOn()=false
08-03 21:22:48.202  3994  3994 V BluetoothAdapterState: isBleTurningOff()=false
08-03 21:22:48.203  3994  3994 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-03 21:22:48.203  3994  4010 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-03 21:22:48.203  3994  3994 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-03 21:22:48.203  3994  3994 V BluetoothAdapterState: isTurningOff()=true
08-03 21:22:48.204  3994  3994 V BluetoothAdapterState: isTurningOn()=false
08-03 21:22:48.204  3994  3994 V BluetoothAdapterState: isBleTurningOn()=false
08-03 21:22:48.204  3994  3994 V BluetoothAdapterState: isBleTurningOff()=false
08-03 21:22:48.204  3994  3994 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-03 21:22:48.204  3994  4010 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-03 21:22:48.204  3994  3994 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 21:22:48.204  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 21:22:48.205  3994  3994 V BluetoothAdapterState: isTurningOff()=true
08-03 21:22:48.205  3994  3994 V BluetoothAdapterState: isTurningOn()=false
08-03 21:22:48.205  3994  3994 V BluetoothAdapterState: isBleTurningOn()=false
08-03 21:22:48.205  3994  3994 V BluetoothAdapterState: isBleTurningOff()=false
08-03 21:22:48.205  3994  3994 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-03 21:22:48.205  3994  3994 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-03 21:22:48.206  3994  3994 D BluetoothMapService: MAP Service closeService in
08-03 21:22:48.207  3994  3994 V BluetoothAdapterState: isTurningOff()=true
08-03 21:22:48.207  3994  3994 V BluetoothAdapterState: isTurningOn()=false
08-03 21:22:48.207  3994  3994 V BluetoothAdapterState: isBleTurningOn()=false
08-03 21:22:48.207  3994  3994 V BluetoothAdapterState: isBleTurningOff()=false
08-03 21:22:48.207  3994  4006 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-03 21:22:48.207  3994  4006 D BluetoothAdapterProperties: Setting state to 15
08-03 21:22:48.207  3994  4006 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-03 21:22:48.208  3994  4006 I BluetoothAdapterState: Entering BleOnState
08-03 21:22:48.208  3994  3994 D BluetoothMapService: cleanup()
08-03 21:22:48.208  3994  3994 D BluetoothMapService: MAP Service closeService in
08-03 21:22:48.208  3773  3783 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 21:22:48.210  3773  3785 D BluetoothMap: onBluetoothStateChange: up=false
08-03 21:22:48.210  1366  1366 D BluetoothPbap: Proxy object disconnected
08-03 21:22:48.210  1366  1366 D PbapServerProfile: Bluetooth service disconnected
08-03 21:22:48.211  1366  1378 D BluetoothMap: onBluetoothStateChange: up=false
08-03 21:22:48.212   870   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 21:22:48.212  1366  1807 D BluetoothPan: onBluetoothStateChange on: false
08-03 21:22:48.213  3773  3773 D BluetoothPbap: Proxy object disconnected
08-03 21:22:48.213  3773  3773 D PbapServerProfile: Bluetooth service disconnected
08-03 21:22:48.214  1366  1374 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-03 21:22:48.214  3773  3783 D BluetoothPbap: onBluetoothStateChange: up=false
08-03 21:22:48.215   870   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 21:22:48.215   870   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 21:22:48.215   870   888 D BluetoothA2dp: onBluetoothStateC,hange: up=false
08-03 21:22:48.215  3773  3785 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 21:22:48.215  1366  1378 D BluetoothPbap: onBluetoothStateChange: up=false
08-03 21:22:48.216  1366  1807 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 21:22:48.217  3773  4048 D BluetoothPan: onBluetoothStateChange on: false
08-03 21:22:48.217  3773  4048 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-03 21:22:48.218  1366  1374 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 21:22:48.218  1772  1894 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-03 21:22:48.219  3994  4006 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-03 21:22:48.219  3994  4006 D BluetoothAdapterProperties: Setting state to 16
08-03 21:22:48.219  3994  4006 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-03 21:22:48.220  3994  4006 D BluetoothAdapterProperties: onBleDisable
,08-03 21:22:48.220  3994  4006 I BluetoothAdapterState: Entering PendingCommandState
08-03 21:22:48.220  3994  4007 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-03 21:22:48.221  3994  4017 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-03 21:22:48.221  3994  4017 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-03 21:22:48.225  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:22:48.225  3994  4010 D BluetoothAdapterProperties: Scan Mode:20
08-03 21:22:48.226  3773  3773 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-03 21:22:48.226  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:22:48.227  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 21:22:48.228  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:22:48.230  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 21:22:48.235  3773  3773 D DockEventReceiver: finishStartingService: stopping service
,08-03 21:22:48.421  3994  4010 I bt_hci  : shut_down
08-03 21:22:48.422  3994  4015 D bt_hwcfg: hw_epilog_process
08-03 21:22:48.423  3994  4015 I bt_vendor: low_power_mode_cb
,08-03 21:22:48.444  3994  4015 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-03 21:22:48.445  3994  4015 I bt_vendor: epilog_cb
08-03 21:22:48.445  3994  4015 I bt_hci  : epilog_finished_callback
,08-03 21:22:48.454  3994  4010 I bt_hci_h4: hal_close
,08-03 21:22:48.456  3994  4010 I bt_userial_vendor: device fd = 51 close
,08-03 21:22:48.582  3994  4007 D bt_stack_manager: event_shut_down_stack finished.
,08-03 21:22:48.583  3994  4006 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-03 21:22:48.589  3994  3994 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-03 21:22:48.589  3994  4006 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-03 21:22:48.592  3994  3994 D BtGatt.GattService: Received stop request...Stopping profile...
08-03 21:22:48.592  3994  3994 D BtGatt.GattService: stop()
,08-03 21:22:48.592  3994  3994 D BtGatt.AdvertiseManager: advertise clients cleared
,08-03 21:22:48.597  3994  3994 V BluetoothAdapterState: isTurningOff()=false
08-03 21:22:48.597  3994  3994 V BluetoothAdapterState: isTurningOn()=false
08-03 21:22:48.597  3994  3994 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 21:22:48.598  3994  3994 V BluetoothAdapterState: isBleTurningOff()=true
,08-03 21:22:48.599  3994  4006 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-03 21:22:48.599  3994  4006 D BluetoothAdapterProperties: Setting state to 10
08-03 21:22:48.599  3994  4006 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-03 21:22:48.601  3994  4006 I BluetoothAdapterState: Entering OffState
08-03 21:22:48.602   870   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-03 21:22:48.633  3994  3994 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-03 21:22:48.634  3994  3994 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-03 21:22:48.634  3994  4007 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-03 21:22:48.644  3994  3994 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-03 21:22:48.647  3994  4007 D bt_stack_manager: event_clean_up_stack finished.
,08-03 21:22:48.652  3994  3994 I art     : System.exit called, status: 0
,08-03 21:22:48.652  3994  3994 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-03 21:22:48.713   870  2850 I ActivityManager: Process com.android.bluetooth (pid 3994) has died
,08-03 21:22:49.554   870  1312 D ConnectivityService: handlePromptUnvalidated 101
,08-03 21:22:51.136  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
,08-03 21:22:51.136  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 21:22:54.144  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 21:22:54.144  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d153f87 added. We now have 6 listener(s)
08-03 21:22:54.145  3718  3765 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 21:22:54.148  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 21:22:54.149  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4d15eb4 added. We now have 7 listener(s)
,08-03 21:22:54.149  3718  3765 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 21:22:54.150  3718  3765 I System.out: IsBluetoothEnabled
,08-03 21:22:54.160  3718  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:22:54.213   870   888 I ActivityManager: Start proc 4054:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-03 21:22:54.341  4054  4054 D AdapterServiceConfig: Adding HeadsetService
,08-03 21:22:54.341  4054  4054 D AdapterServiceConfig: Adding A2dpService
08-03 21:22:54.341  4054  4054 D AdapterServiceConfig: Adding HidService
,08-03 21:22:54.342  4054  4054 D AdapterServiceConfig: Adding HealthService
08-03 21:22:54.342  4054  4054 D AdapterServiceConfig: Adding PanService
08-03 21:22:54.342  4054  4054 D AdapterServiceConfig: Adding GattService
08-03 21:22:54.342  4054  4054 D AdapterServiceConfig: Adding BluetoothMapService
,08-03 21:22:54.358   870   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5eda4f7:true
,08-03 21:22:54.358  4054  4054 D BluetoothAdapterState: make() - Creating AdapterState
,08-03 21:22:54.363  4054  4054 I bt_bluedroid: init
,08-03 21:22:54.364  4054  4066 I BluetoothAdapterState: Entering OffState
,08-03 21:22:54.369  4054  4067 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-03 21:22:54.370  4054  4067 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-03 21:22:54.370  4054  4067 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-03 21:22:54.370  4054  4067 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-03 21:22:54.372  4054  4054 I bt_bluedroid: get_profile_interface socket
,08-03 21:22:54.375  4054  4070 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-03 21:22:54.376  4054  4054 I bt_bluedroid: get_profile_interface sdp
,08-03 21:22:54.377  4054  4070 D BluetoothAdapterProperties: Name is: Nexus 6
,08-03 21:22:54.384  4054  4065 I bt_bluedroid: config_hci_snoop_log
,08-03 21:22:54.386   870   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-03 21:22:54.392  4054  4066 D BluetoothAdapterState: Current state: OFF, message: 0
,08-03 21:22:54.393  4054  4066 D BluetoothAdapterProperties: Setting state to 14
08-03 21:22:54.393  4054  4066 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-03 21:22:54.398  4054  4066 D BluetoothBondStateMachine: make
,08-03 21:22:54.401  4054  4071 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-03 21:22:54.408  4054  4066 I BluetoothAdapterState: Entering PendingCommandState
,08-03 21:22:54.410  4054  4054 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-03 21:22:54.419  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81c6679
,08-03 21:22:54.420  4054  4054 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-03 21:22:54.421  4054  4054 D BtGatt.GattService: Received start request. Starting profile...
,08-03 21:22:54.422  4054  4054 D BtGatt.GattService: start()
08-03 21:22:54.422  4054  4054 I bt_bluedroid: get_profile_interface gatt
,08-03 21:22:54.424  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81c6679
,08-03 21:22:54.425  4054  4054 D BtGatt.AdvertiseManager: advertise manager created
,08-03 21:22:54.435  4054  4054 V BluetoothAdapterState: isTurningOff()=false
,08-03 21:22:54.436  4054  4054 V BluetoothAdapterState: isTurningOn()=false
08-03 21:22:54.436  4054  4054 V BluetoothAdapterState: isBleTurningOn()=true
,08-03 21:22:54.436  4054  4054 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 21:22:54.436  4054  4066 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-03 21:22:54.437  4054  4066 I bt_bluedroid: enable
,08-03 21:22:54.437  4054  4067 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-03 21:22:54.438  4054  4067 I bt_hci  : start_up
,08-03 21:22:54.450  4054  4067 I bt_vendor: alloc value 0xb39ec189
,08-03 21:22:54.451  4054  4067 I bt_vendor: init
,08-03 21:22:54.451  4054  4067 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-03 21:22:54.451  4054  4067 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-03 21:22:54.559  4054  4067 D bt_hci  : start_up starting async portion
,08-03 21:22:54.559  4054  4074 I bt_hci  : event_finish_startup
08-03 21:22:54.560  4054  4074 I bt_hci_h4: hal_open
,08-03 21:22:54.560  4054  4074 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-03 21:22:54.572  4054  4074 I bt_userial_vendor: device fd = 51 open
,08-03 21:22:54.601  4054  4074 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-03 21:22:54.633  4054  4074 D bt_hwcfg: Chipset BCM4354A2
,08-03 21:22:54.634  4054  4074 D bt_hwcfg: Target name = [BCM4354A2]
,08-03 21:22:54.634  4054  4074 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-03 21:22:55.295  4054  4074 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-03 21:22:55.297  4054  4074 D bt_hwcfg: Settlement delay -- 100 ms
,08-03 21:22:55.297  4054  4074 I bt_hwcfg: Setting fw settlement delay to 100 
,08-03 21:22:55.414  4054  4074 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-03 21:22:55.415  4054  4074 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-03 21:22:55.444  4054  4074 I bt_hwcfg: vendor lib fwcfg completed
,08-03 21:22:55.445  4054  4074 I bt_vendor: firmware callback
08-03 21:22:55.445  4054  4074 I bt_hci  : firmware_config_callback
,08-03 21:22:55.456  4054  4076 I bt_btu  : btu_task pending for preload complete event
,08-03 21:22:55.456  4054  4076 I bt_btu_task: Bluetooth chip preload is complete
,08-03 21:22:55.456  4054  4076 I bt_btu  : btu_task received preload complete event
,08-03 21:22:55.470  4054  4076 I         : BTE_InitTraceLevels -- TRC_HCI
,08-03 21:22:55.470  4054  4076 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-03 21:22:55.470  4054  4076 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-03 21:22:55.471  4054  4076 I         : BTE_InitTraceLevels -- TRC_AVDT
08-03 21:22:55.471  4054  4076 I         : BTE_InitTraceLevels -- TRC_AVRC
08-03 21:22:55.471  4054  4076 I         : BTE_InitTraceLevels -- TRC_A2D
08-03 21:22:55.472  4054  4076 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-03 21:22:55.473  4054  4076 I         : BTE_InitTraceLevels -- TRC_BTM
08-03 21:22:55.473  4054  4076 I         : BTE_InitTraceLevels -- TRC_GAP
,08-03 21:22:55.474  4054  4076 I         : BTE_InitTraceLevels -- TRC_PAN
08-03 21:22:55.475  4054  4076 I         : BTE_InitTraceLevels -- TRC_SDP
08-03 21:22:55.475  4054  4076 I         : BTE_InitTraceLevels -- TRC_GATT
,08-03 21:22:55.475  4054  4076 I         : BTE_InitTraceLevels -- TRC_SMP
,08-03 21:22:55.475  4054  4076 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-03 21:22:55.476  4054  4076 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-03 21:22:55.606  4054  4076 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3969d9d
,08-03 21:22:55.606  4054  4076 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3969d9d 
,08-03 21:22:55.630  4054  4070 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-03 21:22:55.632  4054  4070 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-03 21:22:55.633  4054  4070 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-03 21:22:55.636  4054  4070 D BluetoothAdapterProperties: Name is: Nexus 6
,08-03 21:22:55.641  4054  4070 D BluetoothAdapterProperties: Scan Mode:20
,08-03 21:22:55.642  4054  4070 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-03 21:22:55.642  4054  4070 D bt_hci  : do_postload posting postload work item,
08-03 21:22:55.643  4054  4074 I bt_hci  : event_postload
08-03 21:22:55.643  4054  4074 I bt_vendor: sco_config_cb
08-03 21:22:55.644  4054  4074 I bt_hci  : sco_config_callback postload finished.
,08-03 21:22:55.647  4054  4070 D bt_bte_conf: Device ID record 1 : primary
08-03 21:22:55.647  4054  4070 D bt_bte_conf:   vendorId            = 000f
08-03 21:22:55.647  4054  4070 D bt_bte_conf:   vendorIdSource      = 0001
08-03 21:22:55.648  4054  4070 D bt_bte_conf:   product             = 1200
08-03 21:22:55.648  4054  4070 D bt_bte_conf:   version             = 1436
,08-03 21:22:55.648  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 21:22:55.648  4054  4070 D bt_bte_conf:   clientExecutableURL = 
08-03 21:22:55.648  4054  4070 D bt_bte_conf:   serviceDescription  = 
,08-03 21:22:55.648  4054  4070 D bt_bte_conf:   documentationURL    = 
08-03 21:22:55.649  4054  4070 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-03 21:22:55.650  4054  4067 D bt_stack_manager: event_start_up_stack finished
,08-03 21:22:55.651  4054  4066 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-03 21:22:55.652  4054  4066 D BluetoothAdapterProperties: Setting state to 15
08-03 21:22:55.652  4054  4066 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-03 21:22:55.653  4054  4074 I bt_vendor: low_power_mode_cb
08-03 21:22:55.654  4054  4066 I BluetoothAdapterState: Entering BleOnState
,08-03 21:22:55.659  4054  4066 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-03 21:22:55.660  4054  4066 D BluetoothAdapterProperties: Setting state to 11
08-03 21:22:55.660  4054  4066 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-03 21:22:55.672  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:22:55.673  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81c6679
,08-03 21:22:55.678  4054  4054 D HeadsetService: Received start request. Starting profile...
,08-03 21:22:55.682  4054  4054 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-03 21:22:55.683  4054  4054 D HeadsetStateMachine: make
,08-03 21:22:55.687  4054  4066 I BluetoothAdapterState: Entering PendingCommandState
,08-03 21:22:55.694  4054  4054 D HeadsetStateMachine: max_hf_connections = 1
,08-03 21:22:55.694  4054  4054 I bt_bluedroid: get_profile_interface handsfree
08-03 21:22:55.695  4054  4070 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-03 21:22:55.695  4054  4070 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-03 21:22:55.699  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81c6679
,08-03 21:22:55.700  4054  4054 D A2dpService: Received start request. Starting profile...
,08-03 21:22:55.701  4054  4054 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-03 21:22:55.702  4054  4054 I bt_bluedroid: get_profile_interface avrcp
,08-03 21:22:55.711  4054  4054 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-03 21:22:55.711  4054  4054 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-03 21:22:55.711  4054  4054 D A2dpStateMachine: make
,08-03 21:22:55.714  4054  4054 I bt_bluedroid: get_profile_interface a2dp
,08-03 21:22:55.715  4054  4070 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-03 21:22:55.718  4054  4054 I BluetoothHidServiceJni: classInitNative: succeeds
,08-03 21:22:55.718  4054  4084 D A2dpStateMachine: Enter Disconnected: -2
,08-03 21:22:55.721  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81c6679
,08-03 21:22:55.722  4054  4054 D HidService: Received start request. Starting profile...
,08-03 21:22:55.723  4054  4054 I bt_bluedroid: get_profile_interface hidhost
08-03 21:22:55.723  4054  4070 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb394b3e5
,08-03 21:22:55.723  4054  4070 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-03 21:22:55.723  4054  4054 D HidService: setHidService(): set to: null
,08-03 21:22:55.727  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 21:22:55.728  4054  4054 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-03 21:22:55.730  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81c6679
,08-03 21:22:55.731  4054  4054 D HealthService: Received start request. Starting profile...
,08-03 21:22:55.735  4054  4054 I bt_bluedroid: get_profile_interface health
,08-03 21:22:55.737  4054  4054 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-03 21:22:55.739  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81c6679
,08-03 21:22:55.741  4054  4054 D PanService: Received start request. Starting profile...
,08-03 21:22:55.742  4054  4054 D BluetoothPanServiceJni: initializeNative(L110): pan
08-03 21:22:55.742  4054  4054 I bt_bluedroid: get_profile_interface pan
,08-03 21:22:55.744  4054  4070 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-03 21:22:55.753  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81c6679
,08-03 21:22:55.755  4054  4054 D BluetoothMapService: Received start request. Starting profile...
,08-03 21:22:55.755  4054  4054 D BluetoothMapService: start()
,08-03 21:22:55.760  4054  4054 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-03 21:22:55.761  4054  4054 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-03 21:22:55.761  4054  4054 D BluetoothMapAppObserver: createReceiver()
,08-03 21:22:55.762  4054  4054 D BluetoothMapAppObserver: initObservers()
08-03 21:22:55.762  4054  4054 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-03 21:22:55.772  4054  4054 V BluetoothAdapterState: isTurningOff()=false
,08-03 21:22:55.772  4054  4054 V BluetoothAdapterState: isTurningOn()=true
,08-03 21:22:55.772  4054  4054 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 21:22:55.772  4054  4054 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 21:22:55.775  4054  4054 V BluetoothAdapterState: isTurningOff()=false
08-03 21:22:55.775  4054  4054 V BluetoothAdapterState: isTurningOn()=true
,08-03 21:22:55.775  4054  4054 V BluetoothAdapterState: isBleTurningOn()=false
08-03 21:22:55.775  4054  4054 V BluetoothAdapterState: isBleTurningOff()=false
08-03 21:22:55.775  4054  4082 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-03 21:22:55.775  4054  4054 V BluetoothAdapterState: isTurningOff()=false
,08-03 21:22:55.775  4054  4054 V BluetoothAdapterState: isTurningOn()=true
08-03 21:22:55.775  4054  4054 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 21:22:55.776  4054  4054 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 21:22:55.778  4054  4054 V BluetoothAdapterState: isTurningOff()=false
08-03 21:22:55.778  4054  4054 V BluetoothAdapterState: isTurningOn()=true
08-03 21:22:55.778  4054  4054 V BluetoothAdapterState: isBleTurningOn()=false,
08-03 21:22:55.779  4054  4054 V BluetoothAdapterState: isBleTurningOff()=false
08-03 21:22:55.779  4054  4054 V BluetoothAdapterState: isTurningOff()=false
08-03 21:22:55.779  4054  4054 V BluetoothAdapterState: isTurningOn()=true
08-03 21:22:55.779  4054  4054 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 21:22:55.779  4054  4054 V BluetoothAdapterState: isBleTurningOff()=false
08-03 21:22:55.779  4054  4054 V BluetoothAdapterState: isTurningOff()=false
08-03 21:22:55.779  4054  4054 V BluetoothAdapterState: isTurningOn()=true
08-03 21:22:55.779  4054  4054 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 21:22:55.779  4054  4054 V BluetoothAdapterState: isBleTurningOff()=false
08-03 21:22:55.780  4054  4066 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-03 21:22:55.780  4054  4066 D BluetoothAdapterProperties: ScanMode =  20
,08-03 21:22:55.780  4054  4066 D BluetoothAdapterProperties: State =  11
,08-03 21:22:55.782  4054  4066 D BluetoothAdapterProperties: Setting state to 12
,08-03 21:22:55.782  4054  4066 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-03 21:22:55.785  4054  4066 I BluetoothAdapterState: Entering OnState
,08-03 21:22:55.785  3773  3785 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-03 21:22:55.790  4054  4070 D BluetoothAdapterProperties: Scan Mode:21
08-03 21:22:55.790  4054  4054 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-03 21:22:55.791  4054  4070 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 21:22:55.793  4054  4054 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-03 21:22:55.793  3773  3783 D BluetoothMap: onBluetoothStateChange: up=true
08-03 21:22:55.796  4054  4054 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 21:22:55.798  1366  1378 D BluetoothMap: onBluetoothStateChange: up=true
08-03 21:22:55.800   870   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 21:22:55.800  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 21:22:55.800  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:55.800  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:55.800  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 21:22:55.800  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 21:22:55.800  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 21:22:55.800  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 21:22:55.800  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 21:22:55.800  4054  4054 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 21:22:55.800  1366  1807 D BluetoothPan: onBluetoothStateChange on: true
,08-03 21:22:55.803  1366  1374 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-03 21:22:55.804  4054  4054 D ObexServerSockets: Succeed to create listening sockets 
,08-03 21:22:55.804  4054  4054 D ObexServerSockets0: startAccept()
08-03 21:22:55.804  4054  4054 D ObexServerSockets0: prepareForNewConnect()
08-03 21:22:55.806  3718  3718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 21:22:55.807  3773  4048 D BluetoothPbap: onBluetoothStateChange: up=true
,08-03 21:22:55.809   870   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 21:22:55.810   870   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 21:22:55.810   870   888 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-03 21:22:55.811  3773  3785 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 21:22:55.812  4054  4054 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-03 21:22:55.812  4054  4054 D BluetoothSdpJni: SDP Create record success - handle: 0
08-03 21:22:55.812  4054  4091 D ObexServerSockets0: Accepting socket connection...
08-03 21:22:55.812  1366  1378 D BluetoothPbap: onBluetoothStateChange: up=true
08-03 21:22:55.814  4054  4092 D ObexServerSockets0: Accepting socket connection...
08-03 21:22:55.815   870   870 D BluetoothA2dp: Proxy object connected
08-03 21:22:55.815  3773  3773 D BluetoothA2dp: Proxy object connected
,08-03 21:22:55.816  1366  1366 D BluetoothMap: Proxy object connected
08-03 21:22:55.816  1366  1366 D MapProfile: Bluetooth service connected
08-03 21:22:55.816  1366  1366 D BluetoothMap: getConnectedDevices()
,08-03 21:22:55.818  1366  1374 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 21:22:55.819  1366  1366 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 21:22:55.819  1366  1366 D PanProfile: Bluetooth service connected
08-03 21:22:55.819  1366  1366 D BluetoothInputDevice: Proxy object connected
,08-03 21:22:55.819  1366  1366 D HidProfile: Bluetooth service connected
,08-03 21:22:55.820  3773  3773 D BluetoothMap: Proxy object connected
08-03 21:22:55.820  3773  3785 D BluetoothPan: onBluetoothStateChange on: true
08-03 21:22:55.820  3773  3773 D MapProfile: Bluetooth service connected
,08-03 21:22:55.821  3773  3773 D BluetoothMap: getConnectedDevices()
,08-03 21:22:55.830  3773  3773 D BluetoothPan: BluetoothPAN Proxy object connected
,08-03 21:22:55.831  3773  4048 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-03 21:22:55.830  3773  3773 D PanProfile: Bluetooth service connected
08-03 21:22:55.832  1366  1378 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-03 21:22:55.832  3773  3773 D BluetoothInputDevice: Proxy object connected
08-03 21:22:55.832  3773  3773 D HidProfile: Bluetooth service connected
08-03 21:22:55.833  1366  1366 D BluetoothA2dp: Proxy object connected
,08-03 21:22:55.833  1772  1894 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 21:22:55.835   870   870 I Telecom : BluetoothPhoneService: queryPhoneState
,08-03 21:22:55.836  4054  4054 D BluetoothMapService: onReceive
08-03 21:22:55.836  4054  4054 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 21:22:55.836  4054  4054 D BluetoothMapService: STATE_ON
08-03 21:22:55.836  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:22:55.841  3773  3773 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-03 21:22:55.846  3773  3773 D DockEventReceiver: finishStartingService: stopping service
,08-03 21:22:55.846  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 21:22:55.853  3773  3773 D BluetoothPbap: Proxy object connected
,08-03 21:22:55.853  3773  3773 D PbapServerProfile: Bluetooth service connected
,08-03 21:22:55.859  1366  1366 D BluetoothPbap: Proxy object connected
,08-03 21:22:55.859  1366  1366 D PbapServerProfile: Bluetooth service connected
,08-03 21:22:55.861  4054  4097 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 21:22:55.868  4054  4054 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-03 21:22:55.868  4054  4054 D ObexServerSockets0: prepareForNewConnect()
,08-03 21:22:55.872  4054  4101 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 21:22:55.874  4054  4101 I BtOppRfcommListener: Accept thread started.
,08-03 21:22:55.903  3773  3785 D BluetoothHeadset: Proxy object connected
,08-03 21:22:55.903  3773  3773 D HeadsetProfile: Bluetooth service connected
,08-03 21:22:55.904  1772  1790 D BluetoothHeadset: Proxy object connected
08-03 21:22:55.904   870   870 D BluetoothHeadset: Proxy object connected
08-03 21:22:55.904  1366  1374 D BluetoothHeadset: Proxy object connected
,08-03 21:22:55.905  1366  1366 D HeadsetProfile: Bluetooth service connected
,08-03 21:22:55.905   870   870 D BluetoothHeadset: Proxy object connected
08-03 21:22:55.905   870   870 D BluetoothHeadset: Proxy object connected,
,08-03 21:22:55.910   870   888 D BluetoothHeadset: Proxy object connected
,08-03 21:22:55.910   870   888 D BluetoothHeadset: Proxy object connected
08-03 21:22:55.911  3773  4048 D BluetoothHeadset: Proxy object connected
,08-03 21:22:55.911  3773  3773 D HeadsetProfile: Bluetooth service connected
,08-03 21:22:55.919  1366  1378 D BluetoothHeadset: Proxy object connected
,08-03 21:22:55.919  1366  1366 D HeadsetProfile: Bluetooth service connected
,08-03 21:22:55.933  1772  1797 D BluetoothHeadset: Proxy object connected
,08-03 21:22:56.180  3718  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 21:22:56.180  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:56.180  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:56.180  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 21:22:56.180  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 21:22:56.180  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 21:22:56.180  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 21:22:56.180  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 21:22:56.188  3718  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 21:22:56.192  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 21:22:56.193  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b385add added. We now have 8 listener(s)
,08-03 21:22:56.193  3718  3765 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 21:22:56.199   870   881 D WifiService: setWifiEnabled: false pid=3718, uid=10000
,08-03 21:22:56.199   870   881 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 21:22:56.209  3718  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:22:56.210   870  1380 D WifiService: setWifiEnabled: true pid=3718, uid=10000
08-03 21:22:56.210   870  1380 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 21:22:56.224   870  1310 D WifiConfigStore: Loading config and enabling all networks 
,08-03 21:22:56.239  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 21:22:56.239  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:56.239  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:56.239  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 21:22:56.239  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 21:22:56.239  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 21:22:56.239  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 21:22:56.239  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 21:22:56.246  3718  3718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 21:22:56.258   870  1310 D WifiConfigStore: loaded 0 passpoint configs
,08-03 21:22:56.258   870  1310 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-03 21:22:56.259   870  1310 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-03 21:22:56.260   870  1310 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-03 21:22:56.261   870  1310 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-03 21:22:56.261   870  1310 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-03 21:22:56.261   870  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-03 21:22:56.261   870  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-03 21:22:56.277   370   868 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-03 21:22:56.278   870  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-03 21:22:56.281   370   868 D CommandListener: Setting iface cfg
,08-03 21:22:56.329   870  1308 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
,08-03 21:22:56.330   870  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-03 21:22:56.332   870  1310 E native  : do suspend true
,08-03 21:22:56.353   870  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 21:22:56.357   870  1308 D WifiNative-HAL: p2pGetDeviceAddress
,08-03 21:22:56.383   870  1308 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-03 21:22:57.232  3718  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 21:22:57.232  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:57.232  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:57.232  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 21:22:57.232  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 21:22:57.232  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 21:22:57.232  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 21:22:57.232  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 21:22:57.239  3718  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 21:22:57.252  3718  4107 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-03 21:22:57.252  3718  4107 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-03 21:22:57.738   870  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-03 21:22:57.884   870  1310 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.94 rxSuccessRate=21.50 delta 1000 -> 994
,08-03 21:22:57.886   870  1310 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-03 21:22:57.886   870  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 21:22:57.907   870  1310 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-03 21:22:57.954   870  1310 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-03 21:22:57.958  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-03 21:22:58.390  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-03 21:22:58.428  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-03 21:22:58.429  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-03 21:22:58.433   870  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 21:22:58.447   870  1310 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-03 21:22:58.448   870  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-03 21:22:58.448   870  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 21:22:58.474   870  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 21:22:58.484   370   868 D CommandListener: Setting iface cfg
,08-03 21:22:58.487   870  1310 D WifiStateMachine: Start Dhcp Watchdog 3
,08-03 21:22:58.490   870  4110 D DhcpClient: Receive thread started
,08-03 21:22:58.493   870  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-03 21:22:58.581   870  1310 E native  : do suspend false
,08-03 21:22:58.600   870  2111 D DhcpClient: Broadcasting DHCPDISCOVER
,08-03 21:22:58.613   870  4110 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-03 21:22:58.614   870  2111 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-03 21:22:58.617   870  2111 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-03 21:22:58.632   870  4110 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-03 21:22:58.633   870  2111 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-03 21:22:58.638   370   868 D CommandListener: Setting iface cfg
,08-03 21:22:58.648   870  2111 D DhcpClient: Scheduling renewal in 86399s
,08-03 21:22:58.649   870  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-03 21:22:58.654   870  1310 E native  : do suspend true
,08-03 21:22:58.675   870  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-03 21:22:58.676   870  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,08-03 21:22:58.676   870  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-03 21:22:58.678   870  1310 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-03 21:22:58.679   870  1312 D ConnectivityService: Adding iface wlan0 to network 102
,08-03 21:22:58.739   870  1312 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-03 21:22:58.740   870  1312 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-03 21:22:58.743   870  1312 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-03 21:22:58.745   870  1312 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-03 21:22:58.747   870  1312 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-03 21:22:58.758   870  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-03 21:22:58.765   870  1312 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-03 21:22:58.765   870  1312 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-03 21:22:58.766   870  1312 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-03 21:22:58.766   870  1312 D ConnectivityService:    accepting network in place of null
08-03 21:22:58.766   870  1310 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-03 21:22:58.767   870  1312 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-03 21:22:58.770   870  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-03 21:22:58.772   870  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=403298, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-03 21:22:58.815   370   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 21:22:58.851   370   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 21:22:58.857   870  4108 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.46,2a00:1450:400d:803::200e
,08-03 21:22:58.857   870  1312 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-03 21:22:58.858   870  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 21:22:58.870   870   888 D Tethering: MasterInitialState.processMessage what=3
,08-03 21:22:58.875   870  1312 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-03 21:22:58.883  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 21:22:58.883  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:22:58.883  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:22:58.883  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 21:22:58.883  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 21:22:58.883  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 21:22:58.883  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 21:22:58.883  3718  3718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 21:22:58.887  3718  3718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 21:22:58.893  1825  1825 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-03 21:22:58.901  1720  1720 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-03 21:22:58.909  1720  1720 D SystemUpdateService: onCreate
,08-03 21:22:58.912  1720  1720 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-03 21:22:58.933  1720  4119 I SystemUpdateService: active receiver: enabled
,08-03 21:22:58.941  1720  4119 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-03 21:22:58.944  1720  1720 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-03 21:22:58.945  1720  2360 I iu.UploadsManager: num queued entries: 0
,08-03 21:22:58.946  1720  2360 I iu.UploadsManager: num updated entries: 0
,08-03 21:22:58.946  1720  2360 I iu.SyncManager: NEXT; no task
,08-03 21:22:58.954  1720  1720 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-03 21:22:58.956   870  4108 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Aug 2016 19:22:58 GMT], X-Android-Received-Millis=[1470252178956], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470252178915]}
08-03 21:22:58.957   870  1312 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-03 21:22:58.957   870  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-03 21:22:58.958   870  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-03 21:22:58.959   870  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-03 21:22:58.960  1720  1720 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-03 21:22:58.962  1720  4119 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-03 21:22:58.962  1720  4119 I SystemUpdateService: now status is 0 (complete)
08-03 21:22:58.962  1720  4119 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-03 21:22:58.963  1720  4119 I SystemUpdateService: file has been verified
08-03 21:22:58.963  3853  3853 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-03 21:22:58.963  1720  4119 I SystemUpdateService: OTA package size = 12249756
,08-03 21:22:58.968  1720  4121 I MDM     : [197] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-03 21:22:58.968  1720  4121 W BaseAppContext: Using Auth Proxy for data requests.
,08-03 21:22:58.970  3853  3853 D SprintDMHelper: simOperator: 
08-03 21:22:58.970  3853  3853 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-03 21:22:58.971  1720  4121 V GoogleAuthProtoRequest: [197] a.<init>: mAccountName set to: thalitester@gmail.com,
,08-03 21:22:58.976  1720  4119 I SystemUpdateService: showing system update notification
,08-03 21:22:59.003  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:22:59.005  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:22:59.070  1720  1720 D SystemUpdateService: onDestroy
,08-03 21:22:59.075  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-03 21:22:59.075  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-03 21:22:59.075  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 21:22:59.075  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:22:59.104  1720  4121 E MDM     : [197] SitrepService.a: Error sending sitrep.
,08-03 21:22:59.171  3824  4125 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-03 21:23:00.261  3718  4131 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-03 21:23:00.261  3718  4107 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-03 21:23:00.263  3718  4131 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-03 21:23:00.264  3718  4107 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-03 21:23:00.265  3718  4107 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 21:23:00.265  3718  4131 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 21:23:00.266  3718  4107 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 21:23:00.267  3718  4131 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-03 21:23:00.270  3718  4133 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 420, name: OutgoingSocketThread/Sender)
,08-03 21:23:00.271  3718  4107 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-03 21:23:00.273  3718  4131 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-03 21:23:00.274  3718  4134 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 421, name: IncomingSocketThread/Sender)
,08-03 21:23:00.275  3718  4135 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 422, name: OutgoingSocketThread/Receiver)
,08-03 21:23:00.276  3718  4135 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 422, thread name: OutgoingSocketThread/Receiver)
,08-03 21:23:00.276  3718  4135 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-03 21:23:00.276  3718  4135 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 422, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-03 21:23:00.278  3718  4136 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 423, name: IncomingSocketThread/Receiver)
,08-03 21:23:00.279  3718  4136 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 423, thread name: IncomingSocketThread/Receiver)
08-03 21:23:00.280  3718  4136 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-03 21:23:00.280  3718  4136 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 423, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-03 21:23:03.259  3718  3765 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-03 21:23:03.262  3718  3765 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-03 21:23:03.268  3718  3765 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@bf3f135 Bundle[{}]
,08-03 21:23:03.269  3718  3765 I io.jxcore.node.LifeCycleMonitor: start: OK
08-03 21:23:03.269  3718  3765 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-03 21:23:03.270  3718  3765 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-03 21:23:03.271  3718  3765 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-03 21:23:03.272  3718  3765 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-03 21:23:03.273  3718  3765 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-03 21:23:03.278  3718  3765 I System.out: Running OutgoingSocketThread
,08-03 21:23:03.281  3718  4137 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-03 21:23:03.282  3718  4137 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-03 21:23:06.293  3718  4137 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-03 21:23:06.293  3718  4137 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-03 21:23:06.294  3718  4137 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-03 21:23:06.294  3718  4138 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-03 21:23:06.295  3718  4137 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 21:23:06.295  3718  4138 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-03 21:23:06.295  3718  4138 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-03 21:23:06.298  3718  4140 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: OutgoingSocketThread/Sender)
,08-03 21:23:06.299  3718  4137 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-03 21:23:06.302  3718  4141 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 433, name: OutgoingSocketThread/Receiver)
08-03 21:23:06.302  3718  4138 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 21:23:06.303  3718  4138 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-03 21:23:06.304  3718  4141 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 433, thread name: OutgoingSocketThread/Receiver)
08-03 21:23:06.304  3718  4141 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,08-03 21:23:06.304  3718  4141 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 433, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-03 21:23:06.311  3718  4142 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 434, name: IncomingSocketThread/Sender)
,08-03 21:23:06.313  3718  4143 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 435, name: IncomingSocketThread/Receiver)
08-03 21:23:06.314  3718  4143 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 435, thread name: IncomingSocketThread/Receiver)
,08-03 21:23:06.314  3718  4143 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-03 21:23:06.315  3718  4143 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 435, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-03 21:23:06.773   870  1312 D ConnectivityService: handlePromptUnvalidated 102
,08-03 21:23:07.023  1500  1993 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-03 21:23:09.294  3718  3765 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 444)
,08-03 21:23:09.296  3718  3765 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-03 21:23:09.297  3718  3765 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 445)
,08-03 21:23:09.304  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-03 21:23:09.304  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69c3652 added. We now have 2 listener(s)
,08-03 21:23:09.306  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 21:23:09.306  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 21:23:09.306  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 21:23:09.306  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 21:23:09.306  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7c4d23 added. We now have 9 listener(s)
08-03 21:23:09.306  3718  3765 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 21:23:09.308  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 21:23:09.313  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 21:23:09.325  3718  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 21:23:09.325  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:23:09.325  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:23:09.325  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 21:23:09.325  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 21:23:09.325  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 21:23:09.325  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 21:23:09.325  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 21:23:09.332  3718  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 21:23:09.332  3718  3765 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 21:23:09.333  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 21:23:09.333  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@164c7d9 added. We now have 3 listener(s)
,08-03 21:23:09.339  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 21:23:09.339  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:23:09.339  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 21:23:09.340  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-03 21:23:09.340  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 21:23:09.341  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a3659e added. We now have 10 listener(s)
,08-03 21:23:09.341  3718  3765 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 21:23:09.341  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 21:23:09.342  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-03 21:23:09.342  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 21:23:09.342  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 21:23:09.342  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:23:09.343  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-03 21:23:09.343  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 21:23:09.343  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69c3652 removed from the list
,08-03 21:23:09.343  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 21:23:09.344  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7c4d23 removed from the list
08-03 21:23:09.345  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:23:09.346  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
,08-03 21:23:09.346  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:23:09.347  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 21:23:09.347  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 21:23:09.350  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 21:23:09.351  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 21:23:09.351  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:23:09.351  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7c4d23 not in the list
08-03 21:23:09.352  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 21:23:09.352  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:23:09.355  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 21:23:09.355  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 21:23:09.355  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:23:09.355  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a3659e removed from the list,
08-03 21:23:09.355  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 21:23:09.356  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:23:09.356  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:23:09.356  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 21:23:09.356  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@164c7d9 removed from the list
08-03 21:23:09.358  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 21:23:09.358  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fbc987f added. We now have 2 listener(s)
08-03 21:23:09.362  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 21:23:09.363  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 21:23:09.363  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 21:23:09.363  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 21:23:09.364  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afdd04c added. We now have 9 listener(s)
08-03 21:23:09.364  3718  3765 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 21:23:09.365  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 21:23:09.370  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 21:23:09.382  3718  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 21:23:09.382  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:23:09.382  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:23:09.382  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 21:23:09.382  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 21:23:09.382  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 21:23:09.382  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 21:23:09.382  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 21:23:09.388  3718  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 21:23:09.388  3718  3765 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 21:23:09.389  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-03 21:23:09.389  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5c3daa added. We now have 3 listener(s)
,08-03 21:23:09.393  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 21:23:09.393  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-03 21:23:09.394  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 21:23:09.394  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 21:23:09.394  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:23:09.394  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68c3d9b added. We now have 10 listener(s)
08-03 21:23:09.394  3718  3765 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 21:23:09.395  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 21:23:09.395  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-03 21:23:09.395  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 21:23:09.395  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 21:23:09.395  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-03 21:23:09.401  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:23:09.403  3718  3765 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-03 21:23:09.403  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-03 21:23:09.416  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-03 21:23:09.417  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-03 21:23:09.417  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-03 21:23:09.425  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-03 21:23:09.425  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-03 21:23:09.425  3718  3765 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-03 21:23:09.426  3718  3765 D BluetoothAdapter: STATE_ON
,08-03 21:23:09.429  4054  4093 D BtGatt.GattService: registerClient() - UUID=6264375e-d0f3-4408-84b4-8e0a475ee303
08-03 21:23:09.430  4054  4070 D BtGatt.GattService: onClientRegistered() - UUID=6264375e-d0f3-4408-84b4-8e0a475ee303, clientIf=5
,08-03 21:23:09.431  3718  3728 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-03 21:23:09.434  4054  4065 D BtGatt.GattService: start scan with filters
,08-03 21:23:09.443  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-03 21:23:09.443  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-03 21:23:09.443  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-03 21:23:09.443  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-03 21:23:09.444  4054  4073 D BtGatt.ScanManager: handling starting scan
,08-03 21:23:09.446  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 21:23:09.446  3718  3718 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 21:23:09.447  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-03 21:23:09.448  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-03 21:23:09.450  4054  4073 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81c6679
,08-03 21:23:09.455  3718  3765 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-03 21:23:09.455  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-03 21:23:09.455  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-03 21:23:09.456  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:23:09.456  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 21:23:09.456  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-03 21:23:09.456  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 21:23:09.456  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 21:23:09.456  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-03 21:23:09.456  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 21:23:09.456  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-03 21:23:09.457  3718  3765 D BluetoothAdapter: STATE_ON
,08-03 21:23:09.458  4054  4065 D BtGatt.GattService: stopScan() - queue size =1
08-03 21:23:09.458  4054  4064 D BtGatt.GattService: unregisterClient() - clientIf=5
08-03 21:23:09.459  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 21:23:09.459  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-03 21:23:09.459  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-03 21:23:09.459  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-03 21:23:09.459  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-03 21:23:09.461  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 21:23:09.461  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-03 21:23:09.461  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-03 21:23:09.461  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
08-03 21:23:09.462  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 21:23:09.464  3718  3718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 21:23:09.464  3718  3718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 21:23:09.464  3718  3718 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-03 21:23:09.467  4054  4070 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-03 21:23:09.467  4054  4070 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 21:23:09.468  4054  4073 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-03 21:23:09.469  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 21:23:09.469  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-03 21:23:09.469  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-03 21:23:09.470  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 21:23:09.470  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 21:23:09.471  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 21:23:09.471  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 21:23:09.471  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fbc987f removed from the list
08-03 21:23:09.471  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 21:23:09.472  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afdd04c removed from the list
08-03 21:23:09.472  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
08-03 21:23:09.472  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:23:09.475  4054  4070 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-03 21:23:09.475  4054  4070 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 21:23:09.475  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:23:09.475  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:23:09.476  4054  4073 D BtGatt.ScanManager: Starting BLE batch scan
08-03 21:23:09.476  4054  4073 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-03 21:23:09.478  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 21:23:09.478  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 21:23:09.478  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:23:09.479  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afdd04c not in the list
08-03 21:23:09.479  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:23:09.479  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 21:23:09.483  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 21:23:09.483  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 21:23:09.483  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:23:09.484  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68c3d9b removed from the list
08-03 21:23:09.484  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 21:23:09.484  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:23:09.484  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:23:09.485  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 21:23:09.485  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5c3daa removed from the list
,08-03 21:23:09.487  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-03 21:23:09.488  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e71877 added. We now have 2 listener(s)
,08-03 21:23:09.490  4054  4070 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-03 21:23:09.491  4054  4070 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 21:23:09.494  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-03 21:23:09.495  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 21:23:09.495  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 21:23:09.495  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 21:23:09.496  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e3dce4 added. We now have 9 listener(s)
08-03 21:23:09.496  3718  3765 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 21:23:09.498  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 21:23:09.499  4054  4070 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-03 21:23:09.499  4054  4070 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 21:23:09.501  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 21:23:09.506  3718  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 21:23:09.506  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:23:09.506  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:23:09.506  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 21:23:09.506  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 21:23:09.506  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 21:23:09.506  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 21:23:09.506  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 21:23:09.508  4054  4070 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-03 21:23:09.508  4054  4070 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 21:23:09.509  4054  4073 D BtGatt.ScanManager: stopping BLe Batch
,08-03 21:23:09.509  3718  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 21:23:09.509  3718  3765 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 21:23:09.510  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 21:23:09.510  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17ad802 added. We now have 3 listener(s)
,08-03 21:23:09.512  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 21:23:09.514  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 21:23:09.515  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 21:23:09.515  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 21:23:09.516  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 21:23:09.516  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 21:23:09.516  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2aac513 added. We now have 10 listener(s)
08-03 21:23:09.516  3718  3765 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 21:23:09.516  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 21:23:09.517  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 21:23:09.517  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 21:23:09.517  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 21:23:09.517  4054  4070 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-03 21:23:09.517  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 21:23:09.517  4054  4070 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 21:23:09.517  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 21:23:09.518  4054  4073 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-03 21:23:09.521  3718  3765 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-03 21:23:09.521  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-03 21:23:09.525  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-03 21:23:09.526  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-03 21:23:09.527  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-03 21:23:09.527  4054  4070 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-03 21:23:09.527  4054  4070 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 21:23:09.532  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-03 21:23:09.532  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-03 21:23:09.532  3718  3765 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-03 21:23:09.533  3718  3765 D BluetoothAdapter: STATE_ON
,08-03 21:23:09.537  4054  4064 D BtGatt.GattService: registerClient() - UUID=53c8359e-49cd-41cb-8622-6bc8769e7fbe
,08-03 21:23:09.538  4054  4070 D BtGatt.GattService: onClientRegistered() - UUID=53c8359e-49cd-41cb-8622-6bc8769e7fbe, clientIf=5
08-03 21:23:09.538  3718  3728 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-03 21:23:09.539  4054  4093 D BtGatt.GattService: start scan with filters
,08-03 21:23:09.543  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-03 21:23:09.543  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-03 21:23:09.544  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-03 21:23:09.544  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-03 21:23:09.544  4054  4073 D BtGatt.ScanManager: handling starting scan
,08-03 21:23:09.551  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-03 21:23:09.551  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-03 21:23:09.551  3718  3718 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 21:23:09.554  4054  4070 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-03 21:23:09.554  4054  4070 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 21:23:09.555  4054  4073 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-03 21:23:09.557  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-03 21:23:09.563  4054  4070 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-03 21:23:09.563  4054  4070 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 21:23:09.563  4054  4073 D BtGatt.ScanManager: Starting BLE batch scan
08-03 21:23:09.563  4054  4073 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-03 21:23:09.566  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-03 21:23:09.566  3718  3765 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-03 21:23:09.567  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 21:23:09.568  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-03 21:23:09.568  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 21:23:09.569  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 21:23:09.569  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 21:23:09.569  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 21:23:09.570  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 21:23:09.570  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e71877 removed from the list
08-03 21:23:09.570  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 21:23:09.571  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e3dce4 removed from the list
08-03 21:23:09.571  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
08-03 21:23:09.571  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 21:23:09.572  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-03 21:23:09.573  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-03 21:23:09.573  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:23:09.573  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-03 21:23:09.575  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 21:23:09.575  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 21:23:09.575  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:23:09.575  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e3dce4 not in the list
,08-03 21:23:09.575  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 21:23:09.575  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 21:23:09.575  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-03 21:23:09.575  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 21:23:09.575  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-03 21:23:09.576  3718  3765 D BluetoothAdapter: STATE_ON
08-03 21:23:09.578  4054  4090 D BtGatt.GattService: stopScan() - queue size =1
,08-03 21:23:09.579  4054  4065 D BtGatt.GattService: unregisterClient() - clientIf=5
08-03 21:23:09.579  4054  4070 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-03 21:23:09.579  4054  4070 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 21:23:09.579  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 21:23:09.580  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-03 21:23:09.580  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-03 21:23:09.580  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-03 21:23:09.580  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-03 21:23:09.582  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 21:23:09.582  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-03 21:23:09.582  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-03 21:23:09.582  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-03 21:23:09.583  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 21:23:09.585  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 21:23:09.585  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 21:23:09.586  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:23:09.586  3718  3718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 21:23:09.586  3718  3718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 21:23:09.586  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2aac513 removed from the list
08-03 21:23:09.586  3718  3718 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 21:23:09.586  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 21:23:09.586  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:23:09.586  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:23:09.586  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 21:23:09.587  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17ad802 removed from the list
,08-03 21:23:09.588  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 21:23:09.588  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f29f6f added. We now have 2 listener(s)
,08-03 21:23:09.591  4054  4070 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-03 21:23:09.591  4054  4070 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 21:23:09.592  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-03 21:23:09.592  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 21:23:09.592  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 21:23:09.593  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 21:23:09.593  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bbe47c added. We now have 9 listener(s)
08-03 21:23:09.593  3718  3765 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 21:23:09.594  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 21:23:09.597  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 21:23:09.601  4054  4070 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-03 21:23:09.601  4054  4070 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 21:23:09.601  4054  4073 D BtGatt.ScanManager: stopping BLe Batch
,08-03 21:23:09.604  3718  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 21:23:09.604  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:23:09.604  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:23:09.604  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 21:23:09.604  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 21:23:09.604  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 21:23:09.604  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 21:23:09.604  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 21:23:09.607  3718  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 21:23:09.607  3718  3765 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 21:23:09.607  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-03 21:23:09.608  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d7655a added. We now have 3 listener(s)
,08-03 21:23:09.609  4054  4070 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-03 21:23:09.609  4054  4070 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 21:23:09.610  4054  4073 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-03 21:23:09.610  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-03 21:23:09.610  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 21:23:09.610  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 21:23:09.611  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:23:09.611  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 21:23:09.611  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@533c38b added. We now have 10 listener(s)
08-03 21:23:09.611  3718  3765 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 21:23:09.611  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-03 21:23:09.611  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 21:23:09.612  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 21:23:09.612  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 21:23:09.612  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 21:23:09.614  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 21:23:09.617  3718  3765 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-03 21:23:09.618  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-03 21:23:09.618  4054  4070 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-03 21:23:09.618  4054  4070 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 21:23:09.623  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-03 21:23:09.624  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-03 21:23:09.624  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-03 21:23:09.629  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-03 21:23:09.629  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-03 21:23:09.629  3718  3765 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-03 21:23:09.630  3718  3765 D BluetoothAdapter: STATE_ON
,08-03 21:23:09.634  4054  4093 D BtGatt.GattService: registerClient() - UUID=6bcbc109-4464-4cf0-be75-6f5a97afe570
,08-03 21:23:09.635  4054  4070 D BtGatt.GattService: onClientRegistered() - UUID=6bcbc109-4464-4cf0-be75-6f5a97afe570, clientIf=5
08-03 21:23:09.635  3718  3729 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-03 21:23:09.636  4054  4064 D BtGatt.GattService: start scan with filters
,08-03 21:23:09.641  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-03 21:23:09.641  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-03 21:23:09.641  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-03 21:23:09.641  4054  4073 D BtGatt.ScanManager: handling starting scan
08-03 21:23:09.641  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-03 21:23:09.644  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-03 21:23:09.644  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-03 21:23:09.644  3718  3718 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 21:23:09.646  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-03 21:23:09.650  4054  4070 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-03 21:23:09.650  4054  4070 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 21:23:09.650  4054  4073 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-03 21:23:09.652  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 21:23:09.652  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 21:23:09.652  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-03 21:23:09.652  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 21:23:09.652  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:23:09.652  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 21:23:09.652  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 21:23:09.652  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f29f6f removed from the list
,08-03 21:23:09.653  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:23:09.653  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bbe47c removed from the list
,08-03 21:23:09.653  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
08-03 21:23:09.653  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 21:23:09.653  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-03 21:23:09.653  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-03 21:23:09.653  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:23:09.654  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 21:23:09.655  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 21:23:09.655  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 21:23:09.655  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:23:09.655  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bbe47c not in the list
08-03 21:23:09.655  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 21:23:09.655  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 21:23:09.655  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 21:23:09.655  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 21:23:09.655  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-03 21:23:09.656  3718  3765 D BluetoothAdapter: STATE_ON
08-03 21:23:09.657  4054  4093 D BtGatt.GattService: stopScan() - queue size =1
,08-03 21:23:09.658  4054  4065 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-03 21:23:09.658  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 21:23:09.658  4054  4070 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-03 21:23:09.658  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-03 21:23:09.658  4054  4070 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 21:23:09.659  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-03 21:23:09.659  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-03 21:23:09.659  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-03 21:23:09.659  4054  4073 D BtGatt.ScanManager: Starting BLE batch scan
,08-03 21:23:09.659  4054  4073 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-03 21:23:09.660  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-03 21:23:09.661  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-03 21:23:09.661  3718  3765 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-03 21:23:09.661  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 21:23:09.661  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 21:23:09.663  3718  3718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-03 21:23:09.663  3718  3718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 21:23:09.663  3718  3718 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 21:23:09.663  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 21:23:09.663  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 21:23:09.664  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 21:23:09.664  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@533c38b removed from the list
08-03 21:23:09.664  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 21:23:09.664  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 21:23:09.664  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:23:09.664  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-03 21:23:09.664  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d7655a removed from the list
08-03 21:23:09.665  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-03 21:23:09.665  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c190d67 added. We now have 2 listener(s)
08-03 21:23:09.667  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 21:23:09.667  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-03 21:23:09.667  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 21:23:09.668  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 21:23:09.668  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6a4714 added. We now have 9 listener(s)
08-03 21:23:09.668  3718  3765 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 21:23:09.668  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 21:23:09.671  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 21:23:09.678  3718  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 21:23:09.678  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 21:23:09.678  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 21:23:09.678  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 21:23:09.678  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 21:23:09.678  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 21:23:09.678  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 21:23:09.678  3718  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 21:23:09.679  4054  4070 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-03 21:23:09.679  4054  4070 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 21:23:09.682  3718  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 21:23:09.682  3718  3765 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 21:23:09.683  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-03 21:23:09.683  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5dd45b2 added. We now have 3 listener(s)
,08-03 21:23:09.685  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 21:23:09.685  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 21:23:09.685  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-03 21:23:09.685  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 21:23:09.686  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 21:23:09.686  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@41f1903 added. We now have 10 listener(s)
08-03 21:23:09.686  3718  3765 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 21:23:09.687  3718  3765 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 21:23:09.687  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 21:23:09.687  3718  3765 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 21:23:09.687  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 21:23:09.687  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:23:09.687  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 21:23:09.687  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 21:23:09.687  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c190d67 removed from the list
08-03 21:23:09.687  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 21:23:09.688  3718  3718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 21:23:09.688  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6a4714 removed from the list
08-03 21:23:09.688  3718  3765 D io.jxcore.node.ConnectivityMonitor: stop
08-03 21:23:09.688  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 21:23:09.689  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:23:09.689  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:23:09.690  4054  4070 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-03 21:23:09.690  4054  4070 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 21:23:09.690  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 21:23:09.691  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 21:23:09.691  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 21:23:09.691  3718  3765 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6a4714 not in the list
,08-03 21:23:09.691  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 21:23:09.691  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:23:09.692  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 21:23:09.692  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 21:23:09.692  3718  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 21:23:09.692  3718  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@41f1903 removed from the list
08-03 21:23:09.692  3718  3765 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 21:23:09.693  3718  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 21:23:09.693  3718  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 21:23:09.693  3718  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 21:23:09.693  3718  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5dd45b2 removed from the list
,08-03 21:23:09.694  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-03 21:23:09.694  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-03 21:23:09.694  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-03 21:23:09.694  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 21:23:09.694  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-03 21:23:09.694  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-03 21:23:09.701  4054  4070 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-03 21:23:09.701  4054  4070 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 21:23:09.702  4054  4073 D BtGatt.ScanManager: stopping BLe Batch
08-03 21:23:09.702  3718  4144 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 453, name: My test thread name)
,08-03 21:23:09.715  4054  4070 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-03 21:23:09.715  4054  4070 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 21:23:09.715  4054  4073 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-03 21:23:09.724  4054  4070 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-03 21:23:09.724  4054  4070 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 21:23:09.965  3718  3718 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-03 21:23:10.086  3718  3718 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-03 21:23:10.164  3718  3718 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-03 21:23:11.702  3718  3765 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 453
,08-03 21:23:11.702  3718  3765 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 453, name: My test thread name)
,08-03 21:23:11.709  3718  4145 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 454, name: My test thread name)
,08-03 21:23:11.709  3718  4145 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 454, thread name: My test thread name)
08-03 21:23:11.709  3718  4145 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 454, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-03 21:23:11.713  3718  3765 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-03 21:23:11.721  3718  4146 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 458, name: My test thread name)
,08-03 21:23:11.722  3718  4146 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 458, thread name: My test thread name): Test exception.
,08-03 21:23:11.723  3718  4146 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 458, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-03 21:23:11.725  3718  3765 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 82
08-03 21:23:11.725  3718  3765 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 82
,08-03 21:23:11.726  3718  3765 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-03 21:23:11.726  3718  3765 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-03 21:23:11.726  3718  3765 D com.test.thalitest.ThaliTestRunner: Total duration: 36041 ms
,08-03 21:23:11.731  3718  3765 I jxcore-log: Total number of executed tests:  82
08-03 21:23:11.731  3718  3765 I jxcore-log: 
08-03 21:23:11.733  3718  3765 I jxcore-log: Number of passed tests:  82
08-03 21:23:11.733  3718  3765 I jxcore-log: 
08-03 21:23:11.733  3718  3765 I jxcore-log: Number of failed tests:  0
08-03 21:23:11.733  3718  3765 I jxcore-log: 
,08-03 21:23:11.734  3718  3765 I jxcore-log: Number of ignored tests:  0
08-03 21:23:11.734  3718  3765 I jxcore-log: 
08-03 21:23:11.735  3718  3765 I jxcore-log: Total duration:  36041
08-03 21:23:11.735  3718  3765 I jxcore-log: 
,08-03 21:23:11.742  3718  3765 I jxcore-log: Unit Test app is loaded
08-03 21:23:11.742  3718  3765 I jxcore-log: 
,08-03 21:23:11.750  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 21:23:11.750  3718  3765 I jxcore-log: 
,08-03 21:23:11.755  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 21:23:11.755  3718  3765 I jxcore-log: 
,08-03 21:23:11.756  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 21:23:11.756  3718  3765 I jxcore-log: 
08-03 21:23:11.757  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 21:23:11.757  3718  3765 I jxcore-log: 
08-03 21:23:11.758  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 21:23:11.758  3718  3765 I jxcore-log: 
,08-03 21:23:11.760  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 21:23:11.760  3718  3765 I jxcore-log: 
,08-03 21:23:11.764  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 21:23:11.764  3718  3765 I jxcore-log: 
,08-03 21:23:11.766  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 21:23:11.766  3718  3765 I jxcore-log: 
,08-03 21:23:11.767  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 21:23:11.767  3718  3765 I jxcore-log: 
,08-03 21:23:11.768  3718  3718 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-03 21:23:11.768  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 21:23:11.768  3718  3765 I jxcore-log: 
08-03 21:23:11.769  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 21:23:11.769  3718  3765 I jxcore-log: 
,08-03 21:23:11.770  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 21:23:11.770  3718  3765 I jxcore-log: 
08-03 21:23:11.771  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-03 21:23:11.771  3718  3765 I jxcore-log: 
08-03 21:23:11.772  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 21:23:11.772  3718  3765 I jxcore-log: 
,08-03 21:23:11.773  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 21:23:11.773  3718  3765 I jxcore-log: 
08-03 21:23:11.774  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 21:23:11.774  3718  3765 I jxcore-log: 
,08-03 21:23:11.775  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 21:23:11.775  3718  3765 I jxcore-log: 
08-03 21:23:11.775  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 21:23:11.775  3718  3765 I jxcore-log: 
,08-03 21:23:11.776  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 21:23:11.776  3718  3765 I jxcore-log: 
08-03 21:23:11.777  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 21:23:11.777  3718  3765 I jxcore-log: 
,08-03 21:23:11.778  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 21:23:11.778  3718  3765 I jxcore-log: 
08-03 21:23:11.779  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 21:23:11.779  3718  3765 I jxcore-log: 
,08-03 21:23:11.779  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 21:23:11.779  3718  3765 I jxcore-log: 
08-03 21:23:11.780  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 21:23:11.780  3718  3765 I jxcore-log: 
,08-03 21:23:11.781  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 21:23:11.781  3718  3765 I jxcore-log: 
08-03 21:23:11.782  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 21:23:11.782  3718  3765 I jxcore-log: 
,08-03 21:23:11.782  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 21:23:11.782  3718  3765 I jxcore-log: 
08-03 21:23:11.783  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 21:23:11.783  3718  3765 I jxcore-log: 
08-03 21:23:11.784  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 21:23:11.784  3718  3765 I jxcore-log: 
08-03 21:23:11.784  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 21:23:11.784  3718  3765 I jxcore-log: 
08-03 21:23:11.785  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 21:23:11.785  3718  3765 I jxcore-log: 
,08-03 21:23:11.785  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 21:23:11.785  3718  3765 I jxcore-log: 
08-03 21:23:11.786  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 21:23:11.786  3718  3765 I jxcore-log: 
08-03 21:23:11.786  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-03 21:23:11.786  3718  3765 I jxcore-log: 
,08-03 21:23:11.787  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-03 21:23:11.787  3718  3765 I jxcore-log: 
08-03 21:23:11.787  3718  3765 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-03 21:23:11.787  3718  3765 I jxcore-log: 
,08-03 21:23:11.790  3718  3765 I jxcore-log: My device name is: motorola-Nexus 6
08-03 21:23:11.790  3718  3765 I jxcore-log: 
,08-03 21:23:11.790  3718  3765 I jxcore-log: WARN testUtils: myNameCallback not set!
08-03 21:23:11.790  3718  3765 I jxcore-log: 
,08-03 21:23:11.797  3718  4144 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 453, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,08-03 21:23:14.054  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-03 21:23:14.054  3718  3765 I jxcore-log: 
,08-03 21:23:14.666  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-03 21:23:14.666  3718  3765 I jxcore-log: 
,08-03 21:23:14.691  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-03 21:23:14.691  3718  3765 I jxcore-log: 
,08-03 21:23:16.039  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-03 21:23:16.039  3718  3765 I jxcore-log: 
,08-03 21:23:16.266  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-03 21:23:16.266  3718  3765 I jxcore-log: 
,08-03 21:23:16.272  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeTestMethod.js
08-03 21:23:16.272  3718  3765 I jxcore-log: 
,08-03 21:23:16.276  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-03 21:23:16.276  3718  3765 I jxcore-log: 
,08-03 21:23:16.293  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-03 21:23:16.293  3718  3765 I jxcore-log: 
,08-03 21:23:16.298  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-03 21:23:16.298  3718  3765 I jxcore-log: 
,08-03 21:23:16.969  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-03 21:23:16.969  3718  3765 I jxcore-log: 
,08-03 21:23:16.982  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-03 21:23:16.982  3718  3765 I jxcore-log: 
,08-03 21:23:16.993  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-03 21:23:16.993  3718  3765 I jxcore-log: 
,08-03 21:23:17.000  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-03 21:23:17.000  3718  3765 I jxcore-log: 
,08-03 21:23:17.049  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-03 21:23:17.049  3718  3765 I jxcore-log: 
,08-03 21:23:17.105  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-03 21:23:17.105  3718  3765 I jxcore-log: 
,08-03 21:23:17.113  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-03 21:23:17.113  3718  3765 I jxcore-log: 
,08-03 21:23:17.278  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-03 21:23:17.278  3718  3765 I jxcore-log: 
,08-03 21:23:17.305  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-03 21:23:17.305  3718  3765 I jxcore-log: 
,08-03 21:23:17.311  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-03 21:23:17.311  3718  3765 I jxcore-log: 
,08-03 21:23:17.317  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-03 21:23:17.317  3718  3765 I jxcore-log: 
,08-03 21:23:17.336  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-03 21:23:17.336  3718  3765 I jxcore-log: 
,08-03 21:23:17.419  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-03 21:23:17.419  3718  3765 I jxcore-log: 
,08-03 21:23:17.431  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-03 21:23:17.431  3718  3765 I jxcore-log: 
,08-03 21:23:17.459  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-03 21:23:17.459  3718  3765 I jxcore-log: 
,08-03 21:23:17.471  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-03 21:23:17.471  3718  3765 I jxcore-log: 
,08-03 21:23:17.490  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-03 21:23:17.490  3718  3765 I jxcore-log: 
,08-03 21:23:17.527  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-03 21:23:17.527  3718  3765 I jxcore-log: 
,08-03 21:23:17.729  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-03 21:23:17.729  3718  3765 I jxcore-log: 
,08-03 21:23:17.756  3718  3765 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-03 21:23:17.756  3718  3765 I jxcore-log: 
,08-03 21:23:17.765  3718  3765 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-03 21:23:17.766  3718  3765 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-03 21:23:17.766  3718  3765 I jxcore-log: 
,08-03 21:23:17.815  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 21:23:17.815  3718  3765 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,08-03 21:23:17.815  3718  3765 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 21:23:17.815  3718  3765 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,08-03 21:23:17.942  1655  1746 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-03 21:23:17.942  1655  1746 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-03 21:23:17.998   870  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=422523, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-03 21:23:17.999  1500  1500 I ConfigService: onCreate
,08-03 21:23:23.036  1500  1500 I ConfigService: onDestroy
,08-03 21:24:56.072  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:24:56.075  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:24:56.115  1500  1910 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-03 21:24:56.115  1500  1910 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-03 21:24:56.116  1500  1910 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:24:56.116  1500  1910 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:24:56.143  2482  4155 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-03 21:24:56.143  2482  4155 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-03 21:24:56.143  2482  4155 E HttpOperation: 	at jdm.a(PG:82)
08-03 21:24:56.143  2482  4155 E HttpOperation: 	at jcs.o(PG:406)
08-03 21:24:56.143  2482  4155 E HttpOperation: 	at jcn.a(PG:1379)
08-03 21:24:56.143  2482  4155 E HttpOperation: 	at jcs.i(PG:143)
08-03 21:24:56.143  2482  4155 E HttpOperation: 	at blb.a(PG:3937)
08-03 21:24:56.143  2482  4155 E HttpOperation: 	at czp.a(PG:18188)
08-03 21:24:56.143  2482  4155 E HttpOperation: 	at czp.a(PG:9081)
08-03 21:24:56.143  2482  4155 E HttpOperation: 	at czq.run(PG:1686)
08-03 21:24:56.143  2482  4155 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 21:24:56.143  2482  4155 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 21:24:56.143  2482  4155 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:24:56.143  2482  4155 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:24:56.143  2482  4155 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:24:56.143  2482  4155 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 21:24:56.143  2482  4155 E HttpOperation: 	at jdj.a(PG:4091)
08-03 21:24:56.143  2482  4155 E HttpOperation: 	at jdj.a(PG:1125)
08-03 21:24:56.143  2482  4155 E HttpOperation: 	at jdm.a(PG:77)
08-03 21:24:56.143  2482  4155 E HttpOperation: 	... 12 more
08-03 21:24:56.143  2482  4155 E HttpOperation: Caused by: faj: BadAuthentication
08-03 21:24:56.143  2482  4155 E HttpOperation: 	at fal.a(PG:38)
08-03 21:24:56.143  2482  4155 E HttpOperation: 	at jdj.a(PG:4089)
08-03 21:24:56.143  2482  4155 E HttpOperation: 	... 14 more
,08-03 21:24:56.234  1500  2044 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-03 21:24:56.234  1500  2044 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-03 21:24:56.234  1500  2044 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:24:56.234  1500  2044 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:24:56.274  2482  4155 E HttpOperation: [getmobileexperiments] Unexpected exception
08-03 21:24:56.274  2482  4155 E HttpOperation: java.io.IOException: Cannot obtain authentication token
,08-03 21:24:56.274  2482  4155 E HttpOperation: 	at jdm.a(PG:82)
08-03 21:24:56.274  2482  4155 E HttpOperation: 	at jcs.o(PG:406)
08-03 21:24:56.274  2482  4155 E HttpOperation: 	at jcn.a(PG:1379)
08-03 21:24:56.274  2482  4155 E HttpOperation: 	at jcs.i(PG:143)
08-03 21:24:56.274  2482  4155 E HttpOperation: 	at hec.a(PG:42)
08-03 21:24:56.274  2482  4155 E HttpOperation: 	at hee.a(PG:102)
08-03 21:24:56.274  2482  4155 E HttpOperation: 	at czr.a(PG:65)
08-03 21:24:56.274  2482  4155 E HttpOperation: 	at kka.a(PG:108)
08-03 21:24:56.274  2482  4155 E HttpOperation: 	at czp.a(PG:19176)
08-03 21:24:56.274  2482  4155 E HttpOperation: 	at czp.a(PG:9081)
08-03 21:24:56.274  2482  4155 E HttpOperation: 	at czq.run(PG:1686)
08-03 21:24:56.274  2482  4155 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 21:24:56.274  2482  4155 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 21:24:56.274  2482  4155 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:24:56.274  2482  4155 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:24:56.274  2482  4155 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:24:56.274  2482  4155 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 21:24:56.274  2482  4155 E HttpOperation: 	at jdj.a(PG:4091)
08-03 21:24:56.274  2482  4155 E HttpOperation: 	at jdj.a(PG:1125)
08-03 21:24:56.274  2482  4155 E HttpOperation: 	at jdm.a(PG:77)
08-03 21:24:56.274  2482  4155 E HttpOperation: 	... 15 more
08-03 21:24:56.274  2482  4155 E HttpOperation: Caused by: faj: BadAuthentication
08-03 21:24:56.274  2482  4155 E HttpOperation: 	at fal.a(PG:38)
08-03 21:24:56.274  2482  4155 E HttpOperation: 	at jdj.a(PG:4089)
08-03 21:24:56.274  2482  4155 E HttpOperation: 	... 17 more
08-03 21:24:56.274  2482  4155 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-03 21:24:56.274  2482  4155 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-03 21:24:56.274  2482  4155 E ExperimentLoader: 	at jdm.a(PG:82)
08-03 21:24:56.274  2482  4155 E ExperimentLoader: 	at jcs.o(PG:406)
08-03 21:24:56.274  2482  4155 E ExperimentLoader: 	at jcn.a(PG:1379)
08-03 21:24:56.274  2482  4155 E ExperimentLoader: 	at jcs.i(PG:143)
08-03 21:24:56.274  2482  4155 E ExperimentLoader: 	at hec.a(PG:42)
08-03 21:24:56.274  2482  4155 E ExperimentLoader: 	at hee.a(PG:102)
08-03 21:24:56.274  2482  4155 E ExperimentLoader: 	at czr.a(PG:65)
08-03 21:24:56.274  2482  4155 E ExperimentLoader: 	at kka.a(PG:108)
08-03 21:24:56.274  2482  4155 E ExperimentLoader: 	at czp.a(PG:19176)
08-03 21:24:56.274  2482  4155 E ExperimentLoader: 	at czp.a(PG:9081)
08-03 21:24:56.274  2482  4155 E ExperimentLoader: 	at czq.run(PG:1686)
08-03 21:24:56.274  2482  4155 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 21:24:56.274  2482  4155 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 21:24:56.274  2482  4155 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:24:56.274  2482  4155 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:24:56.274  2482  4155 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:24:56.274  2482  4155 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 21:24:56.274  2482  4155 E ExperimentLoader: 	at jdj.a(PG:4091)
08-03 21:24:56.274  2482  4155 E ExperimentLoader: 	at jdj.a(PG:1125)
08-03 21:24:56.274  2482  4155 E ExperimentLoader: 	at jdm.a(PG:77)
08-03 21:24:56.274  2482  4155 E ExperimentLoader: 	... 15 more
08-03 21:24:56.274  2482  4155 E ExperimentLoader: Caused ,by: faj: BadAuthentication
08-03 21:24:56.274  2482  4155 E ExperimentLoader: 	at fal.a(PG:38)
08-03 21:24:56.274  2482  4155 E ExperimentLoader: 	at jdj.a(PG:4089)
08-03 21:24:56.274  2482  4155 E ExperimentLoader: 	... 17 more
,08-03 21:24:56.408   870   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 520160, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-03 21:25:26.516  3422  4158 I BooksSync: Starting books sync for 61035162, extras: ade
,08-03 21:25:26.556  3422  4159 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-03 21:25:26.572  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:25:26.579  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:25:26.629  1500  2044 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-03 21:25:26.629  1500  2044 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-03 21:25:26.630  1500  2044 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:25:26.630  1500  2044 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:25:26.682  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:25:26.689  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:25:26.738  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-03 21:25:26.738  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-03 21:25:26.739  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:25:26.739  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:25:26.776  3422  4159 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-03 21:25:26.777  3422  4158 E BooksSync: Soft error
08-03 21:25:26.777  3422  4158 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 21:25:26.777  3422  4158 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-03 21:25:26.777  3422  4158 E BooksSync: Sync error
08-03 21:25:26.777  3422  4158 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 21:25:26.777  3422  4158 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-03 21:25:26.777  3422  4158 I BooksSync: Finished books sync
,08-03 21:25:26.791   870   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 544422, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-03 21:25:57.198  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:25:57.200  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:25:57.233  1500  2044 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-03 21:25:57.233  1500  2044 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-03 21:25:57.233  1500  2044 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:25:57.234  1500  2044 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:25:57.248  2482  4162 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-03 21:25:57.248  2482  4162 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-03 21:25:57.248  2482  4162 E HttpOperation: 	at jdm.a(PG:82)
08-03 21:25:57.248  2482  4162 E HttpOperation: 	at jcs.o(PG:406)
08-03 21:25:57.248  2482  4162 E HttpOperation: 	at jcn.a(PG:1379)
08-03 21:25:57.248  2482  4162 E HttpOperation: 	at jcs.i(PG:143)
08-03 21:25:57.248  2482  4162 E HttpOperation: 	at blb.a(PG:3937)
08-03 21:25:57.248  2482  4162 E HttpOperation: 	at czp.a(PG:18188)
08-03 21:25:57.248  2482  4162 E HttpOperation: 	at czp.a(PG:9081)
08-03 21:25:57.248  2482  4162 E HttpOperation: 	at czq.run(PG:1686)
08-03 21:25:57.248  2482  4162 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 21:25:57.248  2482  4162 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 21:25:57.248  2482  4162 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:25:57.248  2482  4162 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:25:57.248  2482  4162 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:25:57.248  2482  4162 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 21:25:57.248  2482  4162 E HttpOperation: 	at jdj.a(PG:4091)
08-03 21:25:57.248  2482  4162 E HttpOperation: 	at jdj.a(PG:1125)
08-03 21:25:57.248  2482  4162 E HttpOperation: 	at jdm.a(PG:77)
08-03 21:25:57.248  2482  4162 E HttpOperation: 	... 12 more
08-03 21:25:57.248  2482  4162 E HttpOperation: Caused by: faj: BadAuthentication
08-03 21:25:57.248  2482  4162 E HttpOperation: 	at fal.a(PG:38)
08-03 21:25:57.248  2482  4162 E HttpOperation: 	at jdj.a(PG:4089)
08-03 21:25:57.248  2482  4162 E HttpOperation: 	... 14 more
,08-03 21:25:57.338  1500  1892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-03 21:25:57.338  1500  1892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-03 21:25:57.338  1500  1892 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:25:57.338  1500  1892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:25:57.361  2482  4162 E HttpOperation: [getmobileexperiments] Unexpected exception
08-03 21:25:57.361  2482  4162 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-03 21:25:57.361  2482  4162 E HttpOperation: 	at jdm.a(PG:82)
08-03 21:25:57.361  2482  4162 E HttpOperation: 	at jcs.o(PG:406)
08-03 21:25:57.361  2482  4162 E HttpOperation: 	at jcn.a(PG:1379)
08-03 21:25:57.361  2482  4162 E HttpOperation: 	at jcs.i(PG:143)
08-03 21:25:57.361  2482  4162 E HttpOperation: 	at hec.a(PG:42)
08-03 21:25:57.361  2482  4162 E HttpOperation: 	at hee.a(PG:102)
08-03 21:25:57.361  2482  4162 E HttpOperation: 	at czr.a(PG:65)
08-03 21:25:57.361  2482  4162 E HttpOperation: 	at kka.a(PG:108)
08-03 21:25:57.361  2482  4162 E HttpOperation: 	at czp.a(PG:19176)
08-03 21:25:57.361  2482  4162 E HttpOperation: 	at czp.a(PG:9081)
08-03 21:25:57.361  2482  4162 E HttpOperation: 	at czq.run(PG:1686)
08-03 21:25:57.361  2482  4162 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 21:25:57.361  2482  4162 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 21:25:57.361  2482  4162 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:25:57.361  2482  4162 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:25:57.361  2482  4162 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:25:57.361  2482  4162 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 21:25:57.361  2482  4162 E HttpOperation: 	at jdj.a(PG:4091)
08-03 21:25:57.361  2482  4162 E HttpOperation: 	at jdj.a(PG:1125)
08-03 21:25:57.361  2482  4162 E HttpOperation: 	at jdm.a(PG:77)
08-03 21:25:57.361  2482  4162 E HttpOperation: 	... 15 more
08-03 21:25:57.361  2482  4162 E HttpOperation: Caused by: faj: BadAuthentication
08-03 21:25:57.361  2482  4162 E HttpOperation: 	at fal.a(PG:38)
08-03 21:25:57.361  2482  4162 E HttpOperation: 	at jdj.a(PG:4089)
08-03 21:25:57.361  2482  4162 E HttpOperation: 	... 17 more
08-03 21:25:57.362  2482  4162 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-03 21:25:57.362  2482  4162 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-03 21:25:57.362  2482  4162 E ExperimentLoader: 	at jdm.a(PG:82)
08-03 21:25:57.362  2482  4162 E ExperimentLoader: 	at jcs.o(PG:406)
08-03 21:25:57.362  2482  4162 E ExperimentLoader: 	at jcn.a(PG:1379)
08-03 21:25:57.362  2482  4162 E ExperimentLoader: 	at jcs.i(PG:143)
08-03 21:25:57.362  2482  4162 E ExperimentLoader: 	at hec.a(PG:42)
08-03 21:25:57.362  2482  4162 E ExperimentLoader: 	at hee.a(PG:102)
08-03 21:25:57.362  2482  4162 E ExperimentLoader: 	at czr.a(PG:65)
08-03 21:25:57.362  2482  4162 E ExperimentLoader: 	at kka.a(PG:108)
08-03 21:25:57.362  2482  4162 E ExperimentLoader: 	at czp.a(PG:19176)
08-03 21:25:57.362  2482  4162 E ExperimentLoader: 	at czp.a(PG:9081)
08-03 21:25:57.362  2482  4162 E ExperimentLoader: 	at czq.run(PG:1686)
08-03 21:25:57.362  2482  4162 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 21:25:57.362  2482  4162 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 21:25:57.362  2482  4162 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:25:57.362  2482  4162 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:25:57.362  2482  4162 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:25:57.362  2482  4162 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 21:25:57.362  2482  4162 E ExperimentLoader: 	at jdj.a(PG:4091)
08-03 21:25:57.362  2482  4162 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-03 21:25:57.362  2482  4162 E ExperimentLoader: 	at jdm.a(PG:77)
08-03 21:25:57.362  2482  4162 E ExperimentLoader: 	... 15 more
08-03 21:25:57.362  2482  4162 E ExperimentLoader: Caused by: faj: BadAuthentication
08-03 21:25:57.362  2482  4162 E ExperimentLoader: 	at fal.a(PG:38)
08-03 21:25:57.362  2482  4162 E ExperimentLoader: 	at jdj.a(PG:4089)
08-03 21:25:57.362  2482  4162 E ExperimentLoader: 	... 17 more
,08-03 21:25:57.499   870   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 552614, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-03 21:26:03.151   870  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=587677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-03 21:26:21.871   870  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=606397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-03 21:26:27.650  3422  4166 I BooksSync: Starting books sync for 61035162, extras: ade
,08-03 21:26:27.679  3422  4168 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-03 21:26:27.693  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:26:27.696  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:26:27.729  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-03 21:26:27.730  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-03 21:26:27.730  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 21:26:27.730  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-03 21:26:27.730  2869  4167 V KeepSync: Connecting to GoogleApiClient
,08-03 21:26:27.732   870  1734 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-03 21:26:27.770  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:26:27.779  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:26:27.831  1500  2044 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-03 21:26:27.831  1500  2044 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-03 21:26:27.831  1500  2044 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:26:27.831  1500  2044 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:26:27.853  3422  4168 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 21:26:27.854  3422  4166 E BooksSync: Soft error
08-03 21:26:27.854  3422  4166 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 21:26:27.854  3422  4166 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-03 21:26:27.854  3422  4166 E BooksSync: Sync error
08-03 21:26:27.854  3422  4166 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 21:26:27.854  3422  4166 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-03 21:26:27.854  3422  4166 I BooksSync: Finished books sync
,08-03 21:26:27.875   870   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 582182, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-03 21:26:27.891  1500  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-03 21:26:27.891  1500  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-03 21:26:27.891  1500  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:26:27.891  1500  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:26:27.905  1720  4169 V BaseAuthAsyncOperation: access token request failed
08-03 21:26:27.906  2869  4167 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-03 21:26:27.956  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-03 21:26:27.956  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-03 21:26:27.956  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 21:26:27.956  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:26:27.972  2869  4167 E KeepSync: IOException
08-03 21:26:27.972  2869  4167 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-03 21:26:27.972  2869  4167 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-03 21:26:27.972  2869  4167 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-03 21:26:27.972  2869  4167 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-03 21:26:27.972  2869  4167 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-03 21:26:27.972  2869  4167 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-03 21:26:27.972  2869  4167 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-03 21:26:27.972  2869  4167 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-03 21:26:27.972  2869  4167 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-03 21:26:27.972  2869  4167 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-03 21:26:27.972  2869  4167 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-03 21:26:27.972  2869  4167 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-03 21:26:27.972  2869  4167 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-03 21:26:27.972  2869  4167 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-03 21:26:27.972  2869  4167 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 21:26:27.972  2869  4167 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 21:26:27.972  2869  4167 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-03 21:26:27.972  2869  4167 E KeepSync: 	... 10 more
08-03 21:26:27.972  2869  4167 W KeepSync: Sync result 2
,08-03 21:26:27.979   870   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 588385, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-03 21:26:46.965   870  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=631490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-03 21:26:58.209  2869  4175 V KeepSync: Connecting to GoogleApiClient
08-03 21:26:58.209   870  1682 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-03 21:26:58.267  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:26:58.269  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:26:58.298  1500  2044 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-03 21:26:58.299  1500  2044 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-03 21:26:58.299  1500  2044 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:26:58.299  1500  2044 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:26:58.317  1720  4176 V BaseAuthAsyncOperation: access token request failed
,08-03 21:26:58.319  2869  4175 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-03 21:26:58.405  1500  1892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-03 21:26:58.406  1500  1892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-03 21:26:58.406  1500  1892 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 21:26:58.407  1500  1892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:26:58.421  2869  4175 E KeepSync: IOException
08-03 21:26:58.421  2869  4175 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-03 21:26:58.421  2869  4175 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-03 21:26:58.421  2869  4175 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-03 21:26:58.421  2869  4175 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-03 21:26:58.421  2869  4175 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-03 21:26:58.421  2869  4175 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-03 21:26:58.421  2869  4175 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-03 21:26:58.421  2869  4175 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-03 21:26:58.421  2869  4175 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-03 21:26:58.421  2869  4175 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-03 21:26:58.421  2869  4175 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-03 21:26:58.421  2869  4175 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-03 21:26:58.421  2869  4175 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-03 21:26:58.421  2869  4175 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-03 21:26:58.421  2869  4175 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 21:26:58.421  2869  4175 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 21:26:58.421  2869  4175 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-03 21:26:58.421  2869  4175 E KeepSync: 	... 10 more
08-03 21:26:58.421  2869  4175 W KeepSync: Sync result 2
,08-03 21:26:58.425   870   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 642553, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-03 21:27:05.658   870  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=650184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-03 21:27:28.788  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:27:28.794  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:27:28.852  1500  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-03 21:27:28.853  1500  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-03 21:27:28.853  1500  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 21:27:28.853  1500  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:27:28.873  2482  4179 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-03 21:27:28.873  2482  4179 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-03 21:27:28.873  2482  4179 E HttpOperation: 	at jdm.a(PG:82)
08-03 21:27:28.873  2482  4179 E HttpOperation: 	at jcs.o(PG:406)
08-03 21:27:28.873  2482  4179 E HttpOperation: 	at jcn.a(PG:1379)
08-03 21:27:28.873  2482  4179 E HttpOperation: 	at jcs.i(PG:143)
08-03 21:27:28.873  2482  4179 E HttpOperation: 	at blb.a(PG:3937)
08-03 21:27:28.873  2482  4179 E HttpOperation: 	at czp.a(PG:18188)
08-03 21:27:28.873  2482  4179 E HttpOperation: 	at czp.a(PG:9081)
08-03 21:27:28.873  2482  4179 E HttpOperation: 	at czq.run(PG:1686)
08-03 21:27:28.873  2482  4179 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 21:27:28.873  2482  4179 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 21:27:28.873  2482  4179 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:27:28.873  2482  4179 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:27:28.873  2482  4179 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:27:28.873  2482  4179 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 21:27:28.873  2482  4179 E HttpOperation: 	at jdj.a(PG:4091)
08-03 21:27:28.873  2482  4179 E HttpOperation: 	at jdj.a(PG:1125)
08-03 21:27:28.873  2482  4179 E HttpOperation: 	at jdm.a(PG:77)
08-03 21:27:28.873  2482  4179 E HttpOperation: 	... 12 more
08-03 21:27:28.873  2482  4179 E HttpOperation: Caused by: faj: BadAuthentication
08-03 21:27:28.873  2482  4179 E HttpOperation: 	at fal.a(PG:38)
08-03 21:27:28.873  2482  4179 E HttpOperation: 	at jdj.a(PG:4089)
08-03 21:27:28.873  2482  4179 E HttpOperation: 	... 14 more
,08-03 21:27:28.957  1500  1910 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-03 21:27:28.958  1500  1910 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-03 21:27:28.958  1500  1910 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 21:27:28.958  1500  1910 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:27:28.976  2482  4179 E HttpOperation: [getmobileexperiments] Unexpected exception
08-03 21:27:28.976  2482  4179 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-03 21:27:28.976  2482  4179 E HttpOperation: 	at jdm.a(PG:82)
08-03 21:27:28.976  2482  4179 E HttpOperation: 	at jcs.o(PG:406)
08-03 21:27:28.976  2482  4179 E HttpOperation: 	at jcn.a(PG:1379)
08-03 21:27:28.976  2482  4179 E HttpOperation: 	at jcs.i(PG:143)
08-03 21:27:28.976  2482  4179 E HttpOperation: 	at hec.a(PG:42)
08-03 21:27:28.976  2482  4179 E HttpOperation: 	at hee.a(PG:102)
08-03 21:27:28.976  2482  4179 E HttpOperation: 	at czr.a(PG:65)
08-03 21:27:28.976  2482  4179 E HttpOperation: 	at kka.a(PG:108)
08-03 21:27:28.976  2482  4179 E HttpOperation: 	at czp.a(PG:19176)
08-03 21:27:28.976  2482  4179 E HttpOperation: 	at czp.a(PG:9081)
08-03 21:27:28.976  2482  4179 E HttpOperation: 	at czq.run(PG:1686)
08-03 21:27:28.976  2482  4179 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 21:27:28.976  2482  4179 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 21:27:28.976  2482  4179 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:27:28.976  2482  4179 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:27:28.976  2482  4179 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:27:28.976  2482  4179 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 21:27:28.976  2482  4179 E HttpOperation: 	at jdj.a(PG:4091)
08-03 21:27:28.976  2482  4179 E HttpOperation: 	at jdj.a(PG:1125)
08-03 21:27:28.976  2482  4179 E HttpOperation: 	at jdm.a(PG:77)
08-03 21:27:28.976  2482  4179 E HttpOperation: 	... 15 more
08-03 21:27:28.976  2482  4179 E HttpOperation: Caused by: faj: BadAuthentication
08-03 21:27:28.976  2482  4179 E HttpOperation: 	at fal.a(PG:38)
08-03 21:27:28.976  2482  4179 E HttpOperation: 	at jdj.a(PG:4089)
08-03 21:27:28.976  2482  4179 E HttpOperation: 	... 17 more
,08-03 21:27:28.977  2482  4179 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-03 21:27:28.977  2482  4179 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-03 21:27:28.977  2482  4179 E ExperimentLoader: 	at jdm.a(PG:82)
08-03 21:27:28.977  2482  4179 E ExperimentLoader: 	at jcs.o(PG:406)
08-03 21:27:28.977  2482  4179 E ExperimentLoader: 	at jcn.a(PG:1379)
08-03 21:27:28.977  2482  4179 E ExperimentLoader: 	at jcs.i(PG:143)
08-03 21:27:28.977  2482  4179 E ExperimentLoader: 	at hec.a(PG:42)
08-03 21:27:28.977  2482  4179 E ExperimentLoader: 	at hee.a(PG:102)
08-03 21:27:28.977  2482  4179 E ExperimentLoader: 	at czr.a(PG:65)
08-03 21:27:28.977  2482  4179 E ExperimentLoader: 	at kka.a(PG:108)
08-03 21:27:28.977  2482  4179 E ExperimentLoader: 	at czp.a(PG:19176)
08-03 21:27:28.977  2482  4179 E ExperimentLoader: 	at czp.a(PG:9081)
08-03 21:27:28.977  2482  4179 E ExperimentLoader: 	at czq.run(PG:1686)
08-03 21:27:28.977  2482  4179 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 21:27:28.977  2482  4179 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 21:27:28.977  2482  4179 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:27:28.977  2482  4179 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:27:28.977  2482  4179 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:27:28.977  2482  4179 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 21:27:28.977  2482  4179 E ExperimentLoader: 	at jdj.a(PG:4091)
08-03 21:27:28.977  2482  4179 E ExperimentLoader: 	at jdj.a(PG:1125)
08-03 21:27:28.977  2482  4179 E ExperimentLoader: 	at jdm.a(PG:77)
08-03 21:27:28.977  2482  4179 E ExperimentLoader: 	... 15 more
08-03 21:27:28.977  2482  4179 E ExperimentLoader: Caused by: faj: BadAuthentication
08-03 21:27:28.977  2482  4179 E ExperimentLoader: 	at fal.a(PG:38)
08-03 21:27:28.977  2482  4179 E ExperimentLoader: 	at jdj.a(PG:4089)
08-03 21:27:28.977  2482  4179 E ExperimentLoader: 	... 17 more
,08-03 21:27:29.155   870   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 645385, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-03 21:27:44.238  3347  3347 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,08-03 21:27:44.371  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:27:44.392  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:27:44.396  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:27:44.444  3599  4182 V GoogleAuthProtoRequest: [314] a.<init>: mAccountName set to: thalitester@gmail.com
,08-03 21:27:44.479  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-03 21:27:44.479  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-03 21:27:44.479  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:27:44.480  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:27:44.488  1500  2044 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-03 21:27:44.488  1500  2044 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-03 21:27:44.488  1500  2044 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:27:44.488  1500  2044 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:27:44.511  3599  4182 W ExperimentUpdateService: [314] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-03 21:27:44.513  3599  4182 W ExperimentUpdateService: [314] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-03 21:27:44.513  3599  4182 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-03 21:27:44.513  3599  4182 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-03 21:27:44.513  3599  4182 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-03 21:27:44.513  3599  4182 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-03 21:27:44.513  3599  4182 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-03 21:27:44.513  3599  4182 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-03 21:27:44.513  3599  4182 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-03 21:27:44.513  3599  4182 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-03 21:27:44.513  3599  4182 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-03 21:27:44.513  3599  4182 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-03 21:27:44.522  3347  3347 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-03 21:27:44.556  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:27:44.634  1500  1892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-03 21:27:44.634  1500  1892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-03 21:27:44.635  1500  1892 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 21:27:44.635  1500  1892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:27:44.733  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:27:44.831  1500  1910 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-03 21:27:44.832  1500  1910 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-03 21:27:44.833  1500  1910 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 21:27:44.835  1500  1910 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:27:44.905  3347  3347 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-03 21:27:45.189  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:27:45.229  1500  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-03 21:27:45.230  1500  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-03 21:27:45.230  1500  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:27:45.231  1500  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:27:45.267  3347  3347 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
08-03 21:27:45.267  3347  3347 D Finsky  : [1] WearSupportService.startHygiene: disabled
,08-03 21:27:45.268  3347  3347 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,08-03 21:27:45.275  3347  3347 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,08-03 21:27:45.276  3347  3402 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-03 21:27:59.286  3422  4185 I BooksSync: Starting books sync for 61035162, extras: ade
,08-03 21:27:59.323  3422  4187 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-03 21:27:59.342  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:27:59.343  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:27:59.377  1500  1892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-03 21:27:59.377  1500  1892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-03 21:27:59.377  1500  1892 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 21:27:59.377  1500  1892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:27:59.402  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:27:59.403  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:27:59.421  2869  4186 V KeepSync: Connecting to GoogleApiClient
,08-03 21:27:59.426  1500  2044 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-03 21:27:59.426  1500  2044 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-03 21:27:59.426  1500  2044 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:27:59.427  1500  2044 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-03 21:27:59.427   870  1734 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-03 21:27:59.498  3422  4187 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-03 21:27:59.498  3422  4185 E BooksSync: Soft error
08-03 21:27:59.498  3422  4185 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 21:27:59.498  3422  4185 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-03 21:27:59.498  3422  4185 E BooksSync: Sync error
08-03 21:27:59.498  3422  4185 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 21:27:59.498  3422  4185 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-03 21:27:59.499  3422  4185 I BooksSync: Finished books sync
,08-03 21:27:59.514   870   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 674129, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-03 21:27:59.532  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:27:59.534  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:27:59.567  1500  2042 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-03 21:27:59.567  1500  2042 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-03 21:27:59.567  1500  2042 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:27:59.567  1500  2042 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:27:59.585  1720  4188 V BaseAuthAsyncOperation: access token request failed
,08-03 21:27:59.586  2869  4186 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-03 21:27:59.645  1500  2044 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-03 21:27:59.645  1500  2044 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-03 21:27:59.646  1500  2044 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:27:59.646  1500  2044 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:27:59.677  2869  4186 E KeepSync: IOException
08-03 21:27:59.677  2869  4186 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-03 21:27:59.677  2869  4186 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-03 21:27:59.677  2869  4186 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-03 21:27:59.677  2869  4186 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-03 21:27:59.677  2869  4186 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-03 21:27:59.677  2869  4186 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-03 21:27:59.677  2869  4186 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-03 21:27:59.677  2869  4186 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-03 21:27:59.677  2869  4186 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-03 21:27:59.677  2869  4186 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-03 21:27:59.677  2869  4186 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-03 21:27:59.677  2869  4186 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-03 21:27:59.677  2869  4186 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-03 21:27:59.677  2869  4186 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-03 21:27:59.677  2869  4186 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 21:27:59.677  2869  4186 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 21:27:59.677  2869  4186 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-03 21:27:59.677  2869  4186 E KeepSync: 	... 10 more
,08-03 21:27:59.677  2869  4186 W KeepSync: Sync result 2
,08-03 21:27:59.691   870   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 703047, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-03 21:28:00.248  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:28:00.312  1500  1910 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-03 21:28:00.313  1500  1910 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-03 21:28:00.313  1500  1910 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:28:00.314  1500  1910 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:28:00.360  3347  3347 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-03 21:28:00.360  3347  3347 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-03 21:28:00.360  3347  3347 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,08-03 21:28:03.964   870  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=708490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-03 21:28:20.572  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:28:20.582  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:28:20.583  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:28:20.621  1500  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-03 21:28:20.621  1500  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-03 21:28:20.621  1500  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:28:20.622  1500  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:28:20.665  3347  3347 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-03 21:28:20.665  3347  3347 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-03 21:28:20.665  3347  3347 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,08-03 21:28:22.672   870  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=727197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-03 21:28:36.485   870  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=741010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-03 21:28:40.858  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:28:40.870  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:28:40.876  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:28:40.942  1500  1892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-03 21:28:40.942  1500  1892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-03 21:28:40.942  1500  1892 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:28:40.942  1500  1892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:28:40.985  3347  3347 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-03 21:28:40.986  3347  3347 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-03 21:28:40.986  3347  3347 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-03 21:28:55.205   870  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=759731, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-03 21:29:01.341  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:29:01.354  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:29:01.359  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:29:01.417  1500  1892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-03 21:29:01.417  1500  1892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-03 21:29:01.417  1500  1892 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:29:01.417  1500  1892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:29:01.462  3347  3347 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-03 21:29:01.462  3347  3347 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-03 21:29:01.463  3347  3347 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-03 21:29:08.965   870  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=773490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-03 21:29:21.703  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:29:21.715  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:29:21.717  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:29:21.758  1500  1892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-03 21:29:21.759  1500  1892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-03 21:29:21.759  1500  1892 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 21:29:21.759  1500  1892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:29:21.804  3347  3347 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-03 21:29:21.805  3347  3347 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-03 21:29:21.806  3347  3347 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.,
,08-03 21:29:27.684   870  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=792210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-03 21:29:36.044  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:29:36.046  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:29:36.080  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-03 21:29:36.080  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-03 21:29:36.080  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:29:36.080  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:29:36.096  2482  4195 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-03 21:29:36.096  2482  4195 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-03 21:29:36.096  2482  4195 E HttpOperation: 	at jdm.a(PG:82)
08-03 21:29:36.096  2482  4195 E HttpOperation: 	at jcs.o(PG:406)
08-03 21:29:36.096  2482  4195 E HttpOperation: 	at jcn.a(PG:1379)
08-03 21:29:36.096  2482  4195 E HttpOperation: 	at jcs.i(PG:143)
08-03 21:29:36.096  2482  4195 E HttpOperation: 	at blb.a(PG:3937)
08-03 21:29:36.096  2482  4195 E HttpOperation: 	at czp.a(PG:18188)
08-03 21:29:36.096  2482  4195 E HttpOperation: 	at czp.a(PG:9081)
08-03 21:29:36.096  2482  4195 E HttpOperation: 	at czq.run(PG:1686)
08-03 21:29:36.096  2482  4195 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 21:29:36.096  2482  4195 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 21:29:36.096  2482  4195 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:29:36.096  2482  4195 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:29:36.096  2482  4195 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:29:36.096  2482  4195 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 21:29:36.096  2482  4195 E HttpOperation: 	at jdj.a(PG:4091)
08-03 21:29:36.096  2482  4195 E HttpOperation: 	at jdj.a(PG:1125)
08-03 21:29:36.096  2482  4195 E HttpOperation: 	at jdm.a(PG:77)
08-03 21:29:36.096  2482  4195 E HttpOperation: 	... 12 more
08-03 21:29:36.096  2482  4195 E HttpOperation: Caused by: faj: BadAuthentication
08-03 21:29:36.096  2482  4195 E HttpOperation: 	at fal.a(PG:38)
08-03 21:29:36.096  2482  4195 E HttpOperation: 	at jdj.a(PG:4089)
08-03 21:29:36.096  2482  4195 E HttpOperation: 	... 14 more
,08-03 21:29:36.159  1500  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-03 21:29:36.159  1500  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-03 21:29:36.159  1500  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:29:36.159  1500  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:29:36.192  2482  4195 E HttpOperation: [getmobileexperiments] Unexpected exception
08-03 21:29:36.192  2482  4195 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-03 21:29:36.192  2482  4195 E HttpOperation: 	at jdm.a(PG:82)
08-03 21:29:36.192  2482  4195 E HttpOperation: 	at jcs.o(PG:406)
08-03 21:29:36.192  2482  4195 E HttpOperation: 	at jcn.a(PG:1379)
08-03 21:29:36.192  2482  4195 E HttpOperation: 	at jcs.i(PG:143)
08-03 21:29:36.192  2482  4195 E HttpOperation: 	at hec.a(PG:42)
08-03 21:29:36.192  2482  4195 E HttpOperation: 	at hee.a(PG:102)
08-03 21:29:36.192  2482  4195 E HttpOperation: 	at czr.a(PG:65)
08-03 21:29:36.192  2482  4195 E HttpOperation: 	at kka.a(PG:108)
08-03 21:29:36.192  2482  4195 E HttpOperation: 	at czp.a(PG:19176)
08-03 21:29:36.192  2482  4195 E HttpOperation: 	at czp.a(PG:9081)
08-03 21:29:36.192  2482  4195 E HttpOperation: 	at czq.run(PG:1686)
08-03 21:29:36.192  2482  4195 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 21:29:36.192  2482  4195 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 21:29:36.192  2482  4195 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:29:36.192  2482  4195 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:29:36.192  2482  4195 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:29:36.192  2482  4195 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 21:29:36.192  2482  4195 E HttpOperation: 	at jdj.a(PG:4091)
08-03 21:29:36.192  2482  4195 E HttpOperation: 	at jdj.a(PG:1125)
08-03 21:29:36.192  2482  4195 E HttpOperation: 	at jdm.a(PG:77)
08-03 21:29:36.192  2482  4195 E HttpOperation: 	... 15 more
08-03 21:29:36.192  2482  4195 E HttpOperation: Caused by: faj: BadAuthentication
08-03 21:29:36.192  2482  4195 E HttpOperation: 	at fal.a(PG:38)
08-03 21:29:36.192  2482  4195 E HttpOperation: 	at jdj.a(PG:4089)
08-03 21:29:36.192  2482  4195 E HttpOperation: 	... 17 more
,08-03 21:29:36.193  2482  4195 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-03 21:29:36.193  2482  4195 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-03 21:29:36.193  2482  4195 E ExperimentLoader: 	at jdm.a(PG:82)
08-03 21:29:36.193  2482  4195 E ExperimentLoader: 	at jcs.o(PG:406)
08-03 21:29:36.193  2482  4195 E ExperimentLoader: 	at jcn.a(PG:1379)
08-03 21:29:36.193  2482  4195 E ExperimentLoader: 	at jcs.i(PG:143)
08-03 21:29:36.193  2482  4195 E ExperimentLoader: 	at hec.a(PG:42)
08-03 21:29:36.193  2482  4195 E ExperimentLoader: 	at hee.a(PG:102)
08-03 21:29:36.193  2482  4195 E ExperimentLoader: 	at czr.a(PG:65)
08-03 21:29:36.193  2482  4195 E ExperimentLoader: 	at kka.a(PG:108)
08-03 21:29:36.193  2482  4195 E ExperimentLoader: 	at czp.a(PG:19176)
08-03 21:29:36.193  2482  4195 E ExperimentLoader: 	at czp.a(PG:9081)
08-03 21:29:36.193  2482  4195 E ExperimentLoader: 	at czq.run(PG:1686)
08-03 21:29:36.193  2482  4195 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 21:29:36.193  2482  4195 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 21:29:36.193  2482  4195 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:29:36.193  2482  4195 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:29:36.193  2482  4195 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:29:36.193  2482  4195 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 21:29:36.193  2482  4195 E ExperimentLoader: 	at jdj.a(PG:4091)
08-03 21:29:36.193  2482  4195 E ExperimentLoader: 	at jdj.a(PG:1125)
08-03 21:29:36.193  2482  4195 E ExperimentLoader: 	at jdm.a(PG:77)
08-03 21:29:36.193  2482  4195 E ExperimentLoader: 	... 15 more
08-03 21:29:36.193  2482  4195 E ExperimentLoader: Caused by: faj: BadAuthentication
08-03 21:29:36.193  2482  4195 E ExperimentLoader: 	at fal.a(PG:38)
08-03 21:29:36.193  2482  4195 E ExperimentLoader: 	at jdj.a(PG:4089)
08-03 21:29:36.193  2482  4195 E ExperimentLoader: 	... 17 more
,08-03 21:29:36.309   870   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 800401, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-03 21:29:42.016  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:29:42.028  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:29:42.034  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:29:42.096  1500  2042 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-03 21:29:42.097  1500  2042 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-03 21:29:42.097  1500  2042 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:29:42.098  1500  2042 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:29:42.150  3347  3347 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-03 21:29:42.152  3347  3347 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-03 21:29:42.152  3347  3347 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-03 21:30:06.609  3422  4199 I BooksSync: Starting books sync for 61035162, extras: ade
,08-03 21:30:06.660  3422  4200 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-03 21:30:06.678  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:30:06.682  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:30:06.707  2869  4198 V KeepSync: Connecting to GoogleApiClient
,08-03 21:30:06.712   870   881 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-03 21:30:06.719  1500  2044 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-03 21:30:06.719  1500  2044 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-03 21:30:06.719  1500  2044 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 21:30:06.719  1500  2044 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:30:06.820  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:30:06.822  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:30:06.864  1500  2044 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-03 21:30:06.864  1500  2044 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-03 21:30:06.864  1500  2044 I GLSUser : [GLSUser] Extracting token using key: Auth,
08-03 21:30:06.864  1500  2044 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:30:06.894  3422  4200 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-03 21:30:06.895  3422  4199 E BooksSync: Soft error
08-03 21:30:06.895  3422  4199 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 21:30:06.895  3422  4199 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-03 21:30:06.895  3422  4199 E BooksSync: Sync error
08-03 21:30:06.895  3422  4199 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 21:30:06.895  3422  4199 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-03 21:30:06.895  3422  4199 I BooksSync: Finished books sync
,08-03 21:30:06.902  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:30:06.904  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:30:06.909   870   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 827498, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-03 21:30:06.953  1500  2042 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-03 21:30:06.953  1500  2042 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-03 21:30:06.954  1500  2042 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:30:06.954  1500  2042 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:30:06.970  1720  4201 V BaseAuthAsyncOperation: access token request failed
,08-03 21:30:06.971  2869  4198 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-03 21:30:07.031  1500  2044 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-03 21:30:07.031  1500  2044 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-03 21:30:07.031  1500  2044 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 21:30:07.031  1500  2044 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:30:07.052  2869  4198 E KeepSync: IOException
08-03 21:30:07.052  2869  4198 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-03 21:30:07.052  2869  4198 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-03 21:30:07.052  2869  4198 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-03 21:30:07.052  2869  4198 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-03 21:30:07.052  2869  4198 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-03 21:30:07.052  2869  4198 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-03 21:30:07.052  2869  4198 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-03 21:30:07.052  2869  4198 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-03 21:30:07.052  2869  4198 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-03 21:30:07.052  2869  4198 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-03 21:30:07.052  2869  4198 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-03 21:30:07.052  2869  4198 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-03 21:30:07.052  2869  4198 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-03 21:30:07.052  2869  4198 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-03 21:30:07.052  2869  4198 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 21:30:07.052  2869  4198 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 21:30:07.052  2869  4198 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-03 21:30:07.052  2869  4198 E KeepSync: 	... 10 more
,08-03 21:30:07.052  2869  4198 W KeepSync: Sync result 2
,08-03 21:30:07.057   870   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 824409, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-03 21:33:50.348  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:33:50.354  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:33:50.405  1500  1910 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-03 21:33:50.411  1500  1910 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-03 21:33:50.411  1500  1910 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 21:33:50.412  1500  1910 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:33:50.427  2482  4211 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-03 21:33:50.427  2482  4211 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-03 21:33:50.427  2482  4211 E HttpOperation: 	at jdm.a(PG:82)
08-03 21:33:50.427  2482  4211 E HttpOperation: 	at jcs.o(PG:406)
08-03 21:33:50.427  2482  4211 E HttpOperation: 	at jcn.a(PG:1379)
08-03 21:33:50.427  2482  4211 E HttpOperation: 	at jcs.i(PG:143)
08-03 21:33:50.427  2482  4211 E HttpOperation: 	at blb.a(PG:3937)
08-03 21:33:50.427  2482  4211 E HttpOperation: 	at czp.a(PG:18188)
08-03 21:33:50.427  2482  4211 E HttpOperation: 	at czp.a(PG:9081)
08-03 21:33:50.427  2482  4211 E HttpOperation: 	at czq.run(PG:1686)
08-03 21:33:50.427  2482  4211 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 21:33:50.427  2482  4211 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 21:33:50.427  2482  4211 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:33:50.427  2482  4211 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:33:50.427  2482  4211 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:33:50.427  2482  4211 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 21:33:50.427  2482  4211 E HttpOperation: 	at jdj.a(PG:4091)
08-03 21:33:50.427  2482  4211 E HttpOperation: 	at jdj.a(PG:1125)
08-03 21:33:50.427  2482  4211 E HttpOperation: 	at jdm.a(PG:77)
08-03 21:33:50.427  2482  4211 E HttpOperation: 	... 12 more
08-03 21:33:50.427  2482  4211 E HttpOperation: Caused by: faj: BadAuthentication
08-03 21:33:50.427  2482  4211 E HttpOperation: 	at fal.a(PG:38)
08-03 21:33:50.427  2482  4211 E HttpOperation: 	at jdj.a(PG:4089)
08-03 21:33:50.427  2482  4211 E HttpOperation: 	... 14 more
,08-03 21:33:50.497  1500  1892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-03 21:33:50.497  1500  1892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-03 21:33:50.497  1500  1892 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:33:50.497  1500  1892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:33:50.524  2482  4211 E HttpOperation: [getmobileexperiments] Unexpected exception
08-03 21:33:50.524  2482  4211 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-03 21:33:50.524  2482  4211 E HttpOperation: 	at jdm.a(PG:82)
08-03 21:33:50.524  2482  4211 E HttpOperation: 	at jcs.o(PG:406)
08-03 21:33:50.524  2482  4211 E HttpOperation: 	at jcn.a(PG:1379)
08-03 21:33:50.524  2482  4211 E HttpOperation: 	at jcs.i(PG:143)
08-03 21:33:50.524  2482  4211 E HttpOperation: 	at hec.a(PG:42)
08-03 21:33:50.524  2482  4211 E HttpOperation: 	at hee.a(PG:102)
08-03 21:33:50.524  2482  4211 E HttpOperation: 	at czr.a(PG:65)
08-03 21:33:50.524  2482  4211 E HttpOperation: 	at kka.a(PG:108)
08-03 21:33:50.524  2482  4211 E HttpOperation: 	at czp.a(PG:19176)
08-03 21:33:50.524  2482  4211 E HttpOperation: 	at czp.a(PG:9081)
08-03 21:33:50.524  2482  4211 E HttpOperation: 	at czq.run(PG:1686)
08-03 21:33:50.524  2482  4211 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 21:33:50.524  2482  4211 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 21:33:50.524  2482  4211 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:33:50.524  2482  4211 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:33:50.524  2482  4211 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:33:50.524  2482  4211 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 21:33:50.524  2482  4211 E HttpOperation: 	at jdj.a(PG:4091)
08-03 21:33:50.524  2482  4211 E HttpOperation: 	at jdj.a(PG:1125)
08-03 21:33:50.524  2482  4211 E HttpOperation: 	at jdm.a(PG:77)
08-03 21:33:50.524  2482  4211 E HttpOperation: 	... 15 more
08-03 21:33:50.524  2482  4211 E HttpOperation: Caused by: faj: BadAuthentication
08-03 21:33:50.524  2482  4211 E HttpOperation: 	at fal.a(PG:38)
08-03 21:33:50.524  2482  4211 E HttpOperation: 	at jdj.a(PG:4089)
08-03 21:33:50.524  2482  4211 E HttpOperation: 	... 17 more
,08-03 21:33:50.524  2482  4211 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-03 21:33:50.524  2482  4211 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-03 21:33:50.524  2482  4211 E ExperimentLoader: 	at jdm.a(PG:82)
08-03 21:33:50.524  2482  4211 E ExperimentLoader: 	at jcs.o(PG:406)
08-03 21:33:50.524  2482  4211 E ExperimentLoader: 	at jcn.a(PG:1379)
08-03 21:33:50.524  2482  4211 E ExperimentLoader: 	at jcs.i(PG:143)
08-03 21:33:50.524  2482  4211 E ExperimentLoader: 	at hec.a(PG:42)
08-03 21:33:50.524  2482  4211 E ExperimentLoader: 	at hee.a(PG:102)
08-03 21:33:50.524  2482  4211 E ExperimentLoader: 	at czr.a(PG:65)
08-03 21:33:50.524  2482  4211 E ExperimentLoader: 	at kka.a(PG:108)
08-03 21:33:50.524  2482  4211 E ExperimentLoader: 	at czp.a(PG:19176)
08-03 21:33:50.524  2482  4211 E ExperimentLoader: 	at czp.a(PG:9081)
08-03 21:33:50.524  2482  4211 E ExperimentLoader: 	at czq.run(PG:1686)
08-03 21:33:50.524  2482  4211 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 21:33:50.524  2482  4211 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 21:33:50.524  2482  4211 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:33:50.524  2482  4211 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:33:50.524  2482  4211 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:33:50.524  2482  4211 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 21:33:50.524  2482  4211 E ExperimentLoader: 	at jdj.a(PG:4091)
08-03 21:33:50.524  2482  4211 E ExperimentLoader: 	at jdj.a(PG:1125)
08-03 21:33:50.524  2482  4211 E ExperimentLoader: 	at jdm.a(PG:77)
08-03 21:33:50.524  2482  4211 E ExperimentLoader: 	... 15 more
08-03 21:33:50.524  2482  4211 E ExperimentLoader: Caused by: faj: BadAuthentication
08-03 21:33:50.524  2482  4211 E ExperimentLoader: 	at fal.a(PG:38)
08-03 21:33:50.524  2482  4211 E ExperimentLoader: 	at jdj.a(PG:4089)
08-03 21:33:50.524  2482  4211 E ExperimentLoader: 	... 17 more
,08-03 21:33:50.668   870   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1054276, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-03 21:34:20.835  3422  4216 I BooksSync: Starting books sync for 61035162, extras: ade
,08-03 21:34:20.878  3422  4217 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-03 21:34:20.893  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:34:20.895  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:34:20.924  1500  2042 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-03 21:34:20.924  1500  2042 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-03 21:34:20.924  1500  2042 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:34:20.925  1500  2042 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:34:20.954  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:34:20.956  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:34:20.968  2869  4215 V KeepSync: Connecting to GoogleApiClient
,08-03 21:34:20.968   870  1819 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-03 21:34:20.997  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-03 21:34:20.997  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-03 21:34:20.997  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 21:34:20.998  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:34:21.027  3422  4217 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-03 21:34:21.028  3422  4216 E BooksSync: Soft error
08-03 21:34:21.028  3422  4216 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 21:34:21.028  3422  4216 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-03 21:34:21.028  3422  4216 E BooksSync: Sync error
08-03 21:34:21.028  3422  4216 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 21:34:21.028  3422  4216 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-03 21:34:21.028  3422  4216 I BooksSync: Finished books sync
,08-03 21:34:21.044   870   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1078347, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-03 21:34:21.046  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:34:21.048  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,08-03 21:34:21.072  1500  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-03 21:34:21.072  1500  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-03 21:34:21.072  1500  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:34:21.072  1500  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,08-03 21:34:21.085  1720  4218 V BaseAuthAsyncOperation: access token request failed
,08-03 21:34:21.086  2869  4215 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-03 21:34:21.122  1500  2042 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-03 21:34:21.122  1500  2042 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-03 21:34:21.122  1500  2042 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 21:34:21.122  1500  2042 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:34:21.149  2869  4215 E KeepSync: IOException
08-03 21:34:21.149  2869  4215 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-03 21:34:21.149  2869  4215 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-03 21:34:21.149  2869  4215 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-03 21:34:21.149  2869  4215 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-03 21:34:21.149  2869  4215 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-03 21:34:21.149  2869  4215 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-03 21:34:21.149  2869  4215 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-03 21:34:21.149  2869  4215 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-03 21:34:21.149  2869  4215 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-03 21:34:21.149  2869  4215 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-03 21:34:21.149  2869  4215 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-03 21:34:21.149  2869  4215 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-03 21:34:21.149  2869  4215 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-03 21:34:21.149  2869  4215 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-03 21:34:21.149  2869  4215 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 21:34:21.149  2869  4215 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 21:34:21.149  2869  4215 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-03 21:34:21.149  2869  4215 E KeepSync: 	... 10 more
,08-03 21:34:21.149  2869  4215 W KeepSync: Sync result 2
,08-03 21:34:21.170   870   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1071969, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-03 21:36:21.172  1500  1993 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-03 21:36:34.684   870   883 I UsageStatsService: User[0] Flushing usage stats to disk
,08-03 21:37:59.627  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:37:59.632  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:37:59.641  3599  4231 V GoogleAuthProtoRequest: [315] a.<init>: mAccountName set to: thalitester@gmail.com
,08-03 21:37:59.698  1500  1892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-03 21:37:59.698  1500  1892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-03 21:37:59.698  1500  1892 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:37:59.698  1500  1892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:37:59.717  3599  4231 W ExperimentUpdateService: [315] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-03 21:37:59.717  3599  4231 W ExperimentUpdateService: [315] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-03 21:37:59.717  3599  4231 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-03 21:37:59.717  3599  4231 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-03 21:37:59.717  3599  4231 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-03 21:37:59.717  3599  4231 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-03 21:37:59.717  3599  4231 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-03 21:37:59.717  3599  4231 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-03 21:37:59.717  3599  4231 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-03 21:37:59.717  3599  4231 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-03 21:37:59.717  3599  4231 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-03 21:37:59.717  3599  4231 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-03 21:38:04.618   870  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1309143, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-03 21:38:14.245   870  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1318770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-03 21:42:17.957  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:42:17.963  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:42:18.013  1500  2044 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-03 21:42:18.013  1500  2044 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-03 21:42:18.013  1500  2044 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 21:42:18.013  1500  2044 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:42:18.046  2482  4241 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-03 21:42:18.046  2482  4241 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-03 21:42:18.046  2482  4241 E HttpOperation: 	at jdm.a(PG:82)
08-03 21:42:18.046  2482  4241 E HttpOperation: 	at jcs.o(PG:406)
08-03 21:42:18.046  2482  4241 E HttpOperation: 	at jcn.a(PG:1379)
08-03 21:42:18.046  2482  4241 E HttpOperation: 	at jcs.i(PG:143)
08-03 21:42:18.046  2482  4241 E HttpOperation: 	at blb.a(PG:3937)
08-03 21:42:18.046  2482  4241 E HttpOperation: 	at czp.a(PG:18188)
08-03 21:42:18.046  2482  4241 E HttpOperation: 	at czp.a(PG:9081)
08-03 21:42:18.046  2482  4241 E HttpOperation: 	at czq.run(PG:1686)
08-03 21:42:18.046  2482  4241 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 21:42:18.046  2482  4241 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 21:42:18.046  2482  4241 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:42:18.046  2482  4241 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:42:18.046  2482  4241 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:42:18.046  2482  4241 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 21:42:18.046  2482  4241 E HttpOperation: 	at jdj.a(PG:4091)
08-03 21:42:18.046  2482  4241 E HttpOperation: 	at jdj.a(PG:1125)
08-03 21:42:18.046  2482  4241 E HttpOperation: 	at jdm.a(PG:77)
08-03 21:42:18.046  2482  4241 E HttpOperation: 	... 12 more
08-03 21:42:18.046  2482  4241 E HttpOperation: Caused by: faj: BadAuthentication
08-03 21:42:18.046  2482  4241 E HttpOperation: 	at fal.a(PG:38)
08-03 21:42:18.046  2482  4241 E HttpOperation: 	at jdj.a(PG:4089)
08-03 21:42:18.046  2482  4241 E HttpOperation: 	... 14 more
,08-03 21:42:18.150  1500  1910 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-03 21:42:18.150  1500  1910 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-03 21:42:18.150  1500  1910 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 21:42:18.151  1500  1910 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:42:18.189  2482  4241 E HttpOperation: [getmobileexperiments] Unexpected exception
08-03 21:42:18.189  2482  4241 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-03 21:42:18.189  2482  4241 E HttpOperation: 	at jdm.a(PG:82)
08-03 21:42:18.189  2482  4241 E HttpOperation: 	at jcs.o(PG:406)
08-03 21:42:18.189  2482  4241 E HttpOperation: 	at jcn.a(PG:1379)
08-03 21:42:18.189  2482  4241 E HttpOperation: 	at jcs.i(PG:143)
08-03 21:42:18.189  2482  4241 E HttpOperation: 	at hec.a(PG:42)
08-03 21:42:18.189  2482  4241 E HttpOperation: 	at hee.a(PG:102)
08-03 21:42:18.189  2482  4241 E HttpOperation: 	at czr.a(PG:65)
08-03 21:42:18.189  2482  4241 E HttpOperation: 	at kka.a(PG:108)
08-03 21:42:18.189  2482  4241 E HttpOperation: 	at czp.a(PG:19176)
08-03 21:42:18.189  2482  4241 E HttpOperation: 	at czp.a(PG:9081)
08-03 21:42:18.189  2482  4241 E HttpOperation: 	at czq.run(PG:1686)
08-03 21:42:18.189  2482  4241 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 21:42:18.189  2482  4241 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 21:42:18.189  2482  4241 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:42:18.189  2482  4241 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:42:18.189  2482  4241 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:42:18.189  2482  4241 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 21:42:18.189  2482  4241 E HttpOperation: 	at jdj.a(PG:4091)
08-03 21:42:18.189  2482  4241 E HttpOperation: 	at jdj.a(PG:1125)
08-03 21:42:18.189  2482  4241 E HttpOperation: 	at jdm.a(PG:77)
08-03 21:42:18.189  2482  4241 E HttpOperation: 	... 15 more
08-03 21:42:18.189  2482  4241 E HttpOperation: Caused by: faj: BadAuthentication
08-03 21:42:18.189  2482  4241 E HttpOperation: 	at fal.a(PG:38)
08-03 21:42:18.189  2482  4241 E HttpOperation: 	at jdj.a(PG:4089)
08-03 21:42:18.189  2482  4241 E HttpOperation: 	... 17 more
08-03 21:42:18.189  2482  4241 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-03 21:42:18.189  2482  4241 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-03 21:42:18.189  2482  4241 E ExperimentLoader: 	at jdm.a(PG:82)
08-03 21:42:18.189  2482  4241 E ExperimentLoader: 	at jcs.o(PG:406)
08-03 21:42:18.189  2482  4241 E ExperimentLoader: 	at jcn.a(PG:1379)
08-03 21:42:18.189  2482  4241 E ExperimentLoader: 	at jcs.i(PG:143)
08-03 21:42:18.189  2482  4241 E ExperimentLoader: 	at hec.a(PG:42)
08-03 21:42:18.189  2482  4241 E ExperimentLoader: 	at hee.a(PG:102)
08-03 21:42:18.189  2482  4241 E ExperimentLoader: 	at czr.a(PG:65)
08-03 21:42:18.189  2482  4241 E ExperimentLoader: 	at kka.a(PG:108)
08-03 21:42:18.189  2482  4241 E ExperimentLoader: 	at czp.a(PG:19176)
08-03 21:42:18.189  2482  4241 E ExperimentLoader: 	at czp.a(PG:9081)
08-03 21:42:18.189  2482  4241 E ExperimentLoader: 	at czq.run(PG:1686)
08-03 21:42:18.189  2482  4241 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 21:42:18.189  2482  4241 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 21:42:18.189  2482  4241 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:42:18.189  2482  4241 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:42:18.189  2482  4241 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:42:18.189  2482  4241 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 21:42:18.189  2482  4241 E ExperimentLoader: 	at jdj.a(PG:4091)
08-03 21:42:18.189  2482  4241 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-03 21:42:18.189  2482  4241 E ExperimentLoader: 	at jdm.a(PG:77)
08-03 21:42:18.189  2482  4241 E ExperimentLoader: 	... 15 more
08-03 21:42:18.189  2482  4241 E ExperimentLoader: Caused by: faj: BadAuthentication
08-03 21:42:18.189  2482  4241 E ExperimentLoader: 	at fal.a(PG:38)
08-03 21:42:18.189  2482  4241 E ExperimentLoader: 	at jdj.a(PG:4089)
08-03 21:42:18.189  2482  4241 E ExperimentLoader: 	... 17 more
,08-03 21:42:18.316   870   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1562074, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-03 21:42:48.459  3422  4250 I BooksSync: Starting books sync for 61035162, extras: ade
,08-03 21:42:48.502  3422  4251 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-03 21:42:48.512  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:42:48.515  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:42:48.551  2869  4249 V KeepSync: Connecting to GoogleApiClient
,08-03 21:42:48.551   870  1734 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-03 21:42:48.554  1500  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-03 21:42:48.554  1500  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-03 21:42:48.554  1500  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:42:48.554  1500  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:42:48.608  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:42:48.610  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:42:48.626  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-03 21:42:48.626  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-03 21:42:48.626  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:42:48.626  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:42:48.638  3422  4251 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-03 21:42:48.638  3422  4250 E BooksSync: Soft error
08-03 21:42:48.638  3422  4250 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 21:42:48.638  3422  4250 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-03 21:42:48.638  3422  4250 E BooksSync: Sync error
08-03 21:42:48.638  3422  4250 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 21:42:48.638  3422  4250 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-03 21:42:48.639  3422  4250 I BooksSync: Finished books sync
,08-03 21:42:48.652   870   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1579399, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-03 21:42:48.657  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-03 21:42:48.658  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:42:48.694  1500  2044 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-03 21:42:48.694  1500  2044 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-03 21:42:48.694  1500  2044 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:42:48.694  1500  2044 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:42:48.712  1720  4252 V BaseAuthAsyncOperation: access token request failed
,08-03 21:42:48.713  2869  4249 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-03 21:42:48.764  1500  1892 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-03 21:42:48.764  1500  1892 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-03 21:42:48.764  1500  1892 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:42:48.764  1500  1892 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:42:48.806  2869  4249 E KeepSync: IOException
08-03 21:42:48.806  2869  4249 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-03 21:42:48.806  2869  4249 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-03 21:42:48.806  2869  4249 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-03 21:42:48.806  2869  4249 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-03 21:42:48.806  2869  4249 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-03 21:42:48.806  2869  4249 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-03 21:42:48.806  2869  4249 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-03 21:42:48.806  2869  4249 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-03 21:42:48.806  2869  4249 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-03 21:42:48.806  2869  4249 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-03 21:42:48.806  2869  4249 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-03 21:42:48.806  2869  4249 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-03 21:42:48.806  2869  4249 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-03 21:42:48.806  2869  4249 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-03 21:42:48.806  2869  4249 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 21:42:48.806  2869  4249 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 21:42:48.806  2869  4249 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-03 21:42:48.806  2869  4249 E KeepSync: 	... 10 more
,08-03 21:42:48.806  2869  4249 W KeepSync: Sync result 2
,08-03 21:42:48.812   870   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1566465, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-03 21:44:18.226  1500  1993 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,TIME-OUT KILL (timeout was 1400000ms),08-03 21:45:48.448  4260  4260 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-03 21:45:48.452  4260  4260 D AndroidRuntime: CheckJNI is OFF
08-03 21:45:48.488  4260  4260 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-03 21:45:48.529  4260  4260 I Radio-JNI: register_android_hardware_Radio DONE
08-03 21:45:48.550  4260  4260 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-03 21:45:48.559   870   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-03 21:45:48.561   870   884 I ActivityManager: Killing 3718:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-03 21:45:48.665   870  1739 I WindowState: WIN DEATH: Window{cb0efdf u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-03 21:45:48.666   870  1311 D WifiService: Client connection lost with reason: 4
08-03 21:45:48.667   870  1379 D GraphicsStats: Buffer count: 2
08-03 21:45:48.675   870   894 W PackageSettings: Skipping PackageSetting{83b7d42 com.example.hello/10273} due to missing metadata
08-03 21:45:48.708   870   884 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-03 21:45:48.708   870   884 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-03 21:45:48.709   870   884 E ActivityManager: Failure starting process com.test.thalitest
08-03 21:45:48.709   870   884 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-03 21:45:48.709   870   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-03 21:45:48.709   870   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-03 21:45:48.709   870   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-03 21:45:48.709   870   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-03 21:45:48.709   870   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-03 21:45:48.709   870   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-03 21:45:48.709   870   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-03 21:45:48.709   870   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-03 21:45:48.709   870   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-03 21:45:48.709   870   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-03 21:45:48.709   870   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-03 21:45:48.709   870   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-03 21:45:48.709   870   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-03 21:45:48.709   870   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-03 21:45:48.709   870   884 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:45:48.709   870   884 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:45:48.709   870   884 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 21:45:48.709   870   884 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-03 21:45:48.709   870   884 I ActivityManager:   Force finishing activity ActivityRecord{b131d2 u0 com.test.thalitest/.MainActivity t2}
08-03 21:45:48.722   870  1682 W ActivityManager: Spurious death for ProcessRecord{bb0f54b 0:com.test.thalitest/u0a0}, curProc for 3718: null
08-03 21:45:48.726   870   894 I art     : Starting a blocking GC Explicit
08-03 21:45:48.778   870   894 I art     : Explicit concurrent mark sweep GC freed 27638(2MB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 29MB/43MB, paused 777us total 51.756ms
08-03 21:45:48.800   870   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-03 21:45:48.808  4260  4260 I art     : System.exit called, status: 0
08-03 21:45:48.808  4260  4260 I AndroidRuntime: VM exiting with result code 0.
08-03 21:45:48.823   870   894 I ActivityManager: Start proc 4270:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-03 21:45:48.824   870   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-03 21:45:48.838   870   884 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-03 21:45:48.845  1694  2010 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-03 21:45:48.845  4054  4054 D BluetoothMapAppObserver: onReceive
08-03 21:45:48.846  4054  4054 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-03 21:45:48.847   870  1300 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-03 21:45:48.848  3484  3484 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-03 21:45:48.856  1655  1655 I Keyboard.Facilitator: resetDictionaries() : en_US
08-03 21:45:48.887  1655  4284 I Keyboard.Facilitator.DecoderInitializer: run()
08-03 21:45:48.895  1772  1772 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-03 21:45:48.899  1655  4284 I Decoder : createOrResetDecoder
08-03 21:45:48.909   870  1379 I ActivityManager: Start proc 4286:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-03 21:45:48.925   870   870 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-03 21:45:48.926   870  1379 I ActivityManager: Killing 3536:com.google.android.apps.docs/u0a46 (adj 15): empty #17
08-03 21:45:48.943   870  1819 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3718 uid 10000
08-03 21:45:48.945  1655  1655 I Keyboard.Facilitator: onFinishInput()
08-03 21:45:48.972  1500  1500 I ConfigService: onCreate
08-03 21:45:48.980  1784  1859 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-03 21:45:48.980  1500  4299 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-03 21:45:48.980  1500  4299 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 21:45:48.980  1500  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 21:45:48.980  1500  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 21:45:48.980  1500  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 21:45:48.980  1500  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 21:45:48.980  1500  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 21:45:48.980  1500  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 21:45:48.980  1500  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 21:45:48.980  1500  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 21:45:48.980  1500  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 21:45:48.980  1500  4299 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 21:45:48.980  1500  4299 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 21:45:48.980  1500  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 21:45:48.980  1500  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-03 21:45:48.980  1500  4299 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-03 21:45:48.980  1500  4299 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-03 21:45:48.980  1500  4299 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:45:48.982   870   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-03 21:45:48.983   870   883 E PackageManager: Failed to write settings, restoring backup
08-03 21:45:48.983   870   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-03 21:45:48.983   870   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-03 21:45:48.983   870   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-03 21:45:48.983   870   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-03 21:45:48.983   870   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-03 21:45:48.983   870   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:45:48.983   870   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:45:48.983   870   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 21:45:48.985  4286  4286 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-03 21:45:48.987  1500  4299 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-03 21:45:48.987  1500  4299 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 21:45:48.987  1500  4299 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 21:45:48.987  1500  4299 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 21:45:48.987  1500  4299 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 21:45:48.987  1500  4299 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 21:45:48.987  1500  4299 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 21:45:48.987  1500  4299 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 21:45:48.987  1500  4299 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 21:45:48.987  1500  4299 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 21:45:48.987  1500  4299 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 21:45:48.987  1500  4299 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 21:45:48.987  1500  4299 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 21:45:48.987  1500  4299 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 21:45:48.987  1500  4299 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-03 21:45:48.987  1500  4299 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-03 21:45:48.987  1500  4299 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-03 21:45:48.987  1500  4299 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:45:48.988   870   884 E DropBoxManagerService: Can't write: system_server_wtf
08-03 21:45:48.988   870   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-03 21:45:48.988   870   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 21:45:48.988   870   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 21:45:48.988   870   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 21:45:48.988   870   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 21:45:48.988   870   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 21:45:48.988   870   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 21:45:48.988   870   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-03 21:45:48.988   870   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-03 21:45:48.988   870   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-03 21:45:48.988   870   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 21:45:48.988   870   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 21:45:48.988   870   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:45:48.988   870   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 21:45:48.988   870   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-03 21:45:48.988   870   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 21:45:48.988   870   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 21:45:48.988   870   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 21:45:48.988   870   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 21:45:48.988   870   884 E DropBoxManagerService: 	... 13 more
08-03 21:45:48.992   870  2850 I ActivityManager: Start proc 4300:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-03 21:45:48.993  1784  1859 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-03 21:45:48.993  1784  1859 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1784
08-03 21:45:48.993  1784  1859 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 21:45:48.993  1784  1859 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-03 21:45:48.993  1784  1859 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-03 21:45:48.993  1784  1859 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-03 21:45:48.993  1784  1859 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-03 21:45:48.993  1784  1859 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-03 21:45:48.993  1784  1859 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-03 21:45:48.993  1784  1859 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-03 21:45:48.993  1784  1859 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 21:45:48.993  1784  1859 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 21:45:48.993  1784  1859 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:45:48.993  1784  1859 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 21:45:48.994  1500  4299 W SQLiteOpenHelper: Opened config.db in read-only mode
08-03 21:45:48.995   870  1702 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-03 21:45:48.995   870  4306 E DropBoxManagerService: Can't write: system_app_crash
08-03 21:45:48.995   870  4306 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-03 21:45:48.995   870  4306 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 21:45:48.995   870  4306 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 21:45:48.995   870  4306 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 21:45:48.995   870  4306 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 21:45:48.995   870  4306 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 21:45:48.995   870  4306 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 21:45:48.995   870  4306 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 21:45:48.995   870  4306 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 21:45:48.995   870  4306 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 21:45:48.995   870  4306 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 21:45:48.995   870  4306 E DropBoxManagerService: 	... 5 more
08-03 21:45:48.998  1784  1859 I Process : Sending signal. PID: 1784 SIG: 9
08-03 21:45:49.033  1655  4284 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-03 21:45:49.070  1655  4284 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-03 21:45:49.072  1655  4284 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-03 21:45:49.072  1655  4284 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-03 21:45:49.074  1655  4284 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-03 21:45:49.074  1655  4284 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-03 21:45:49.077  1655  4284 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-03 21:45:49.077  1655  4284 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-03 21:45:49.081  1655  4284 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-03 21:45:49.081  1655  4284 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-03 21:45:49.081  1655  4284 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-03 21:45:49.083  1655  4284 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-03 21:45:49.083  1655  4284 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-03 21:45:49.083  1655  4284 I PeriodicStatsRecorder: shouldRecordStats() = Time to Run
08-03 21:45:49.083  1655  4284 I PeriodicStatsRecorder: shouldRecordStats() = Time to Run
08-03 21:45:49.088  1655  4284 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.inputmethod.latin/shared_prefs/local_prefs.xml to backup file /data/user/0/com.google.android.inputmethod.latin/shared_prefs/local_prefs.xml.bak
08-03 21:45:49.120  4286  4286 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-03 21:45:49.124   870  1299 W InputDispatcher: channel 'dad02f com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
08-03 21:45:49.124   870  1299 E InputDispatcher: channel 'dad02f com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
08-03 21:45:49.125   870   880 D GraphicsStats: Buffer count: 1
08-03 21:45:49.125   870   880 I WindowState: WIN DEATH: Window{dad02f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-03 21:45:49.125   870   880 W InputDispatcher: Attempted to unregister already unregistered input channel 'dad02f com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
08-03 21:45:49.131   870  1702 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1784) has died
08-03 21:45:49.131   870  1702 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-03 21:45:49.132  1500  4322 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-03 21:45:49.132  1500  4322 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 21:45:49.132  1500  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 21:45:49.132  1500  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 21:45:49.132  1500  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 21:45:49.132  1500  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 21:45:49.132  1500  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 21:45:49.132  1500  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 21:45:49.132  1500  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 21:45:49.132  1500  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 21:45:49.132  1500  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 21:45:49.132  1500  4322 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 21:45:49.132  1500  4322 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 21:45:49.132  1500  4322 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 21:45:49.132  1500  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 21:45:49.132  1500  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-03 21:45:49.132  1500  4322 E SQLiteDatabase: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:100)
08-03 21:45:49.132  1500  4322 E SQLiteDatabase: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-03 21:45:49.132  1500  4322 E SQLiteDatabase: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-03 21:45:49.132  1500  4322 E SQLiteDatabase: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-03 21:45:49.132  1500  4322 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:45:49.132  1500  4322 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:45:49.132  1500  4322 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:45:49.134   870  1702 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-03 21:45:49.135  1500  4322 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
08-03 21:45:49.135  1500  4322 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 21:45:49.135  1500  4322 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 21:45:49.135  1500  4322 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 21:45:49.135  1500  4322 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 21:45:49.135  1500  4322 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 21:45:49.135  1500  4322 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 21:45:49.135  1500  4322 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 21:45:49.135  1500  4322 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 21:45:49.135  1500  4322 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 21:45:49.135  1500  4322 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 21:45:49.135  1500  4322 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 21:45:49.135  1500  4322 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 21:45:49.135  1500  4322 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 21:45:49.135  1500  4322 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 21:45:49.135  1500  4322 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-03 21:45:49.135  1500  4322 E SQLiteOpenHelper: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:100)
08-03 21:45:49.135  1500  4322 E SQLiteOpenHelper: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-03 21:45:49.135  1500  4322 E SQLiteOpenHelper: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-03 21:45:49.135  1500  4322 E SQLiteOpenHelper: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-03 21:45:49.135  1500  4322 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:45:49.135  1500  4322 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:45:49.135  1500  4322 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:45:49.137  1500  4322 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
08-03 21:45:49.137  1500  4322 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
08-03 21:45:49.144  1500  4322 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
08-03 21:45:49.144  1500  4322 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-03 21:45:49.144  1500  4322 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-03 21:45:49.144  1500  4322 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-03 21:45:49.144  1500  4322 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-03 21:45:49.144  1500  4322 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-03 21:45:49.144  1500  4322 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-03 21:45:49.144  1500  4322 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-03 21:45:49.144  1500  4322 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-03 21:45:49.144  1500  4322 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-03 21:45:49.144  1500  4322 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-03 21:45:49.144  1500  4322 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-03 21:45:49.144  1500  4322 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:45:49.144  1500  4322 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:45:49.144  1500  4322 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:45:49.148  4286  4318 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-03 21:45:49.148  4286  4318 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 21:45:49.148  4286  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 21:45:49.148  4286  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 21:45:49.148  4286  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 21:45:49.148  4286  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 21:45:49.148  4286  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 21:45:49.148  4286  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 21:45:49.148  4286  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 21:45:49.148  4286  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 21:45:49.148  4286  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 21:45:49.148  4286  4318 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 21:45:49.148  4286  4318 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 21:45:49.148  4286  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 21:45:49.148  4286  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-03 21:45:49.148  4286  4318 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-03 21:45:49.148  4286  4318 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-03 21:45:49.148  4286  4318 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-03 21:45:49.148  4286  4318 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-03 21:45:49.148  4286  4318 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:45:49.148  4286  4318 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:45:49.148  4286  4318 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 21:45:49.148  4286  4318 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-03 21:45:49.148  4286  4318 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 21:45:49.148  4286  4318 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 21:45:49.148  4286  4318 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 21:45:49.148  4286  4318 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 21:45:49.148  4286  4318 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 21:45:49.148  4286  4318 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 21:45:49.148  4286  4318 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 21:45:49.148  4286  4318 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 21:45:49.148  4286  4318 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 21:45:49.148  4286  4318 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 21:45:49.148  4286  4318 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 21:45:49.148  4286  4318 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 21:45:49.148  4286  4318 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 21:45:49.148  4286  4318 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-03 21:45:49.148  4286  4318 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-03 21:45:49.148  4286  4318 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-03 21:45:49.148  4286  4318 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-03 21:45:49.148  4286  4318 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-03 21:45:49.148  4286  4318 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:45:49.148  4286  4318 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:45:49.148  4286  4318 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 21:45:49.153   870   884 I ActivityManager: Start proc 4323:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-03 21:45:49.171   870  1734 I ActivityManager: Start proc 4336:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-03 21:45:49.173  4286  4334 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-03 21:45:49.183  1720  4321 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-03 21:45:49.185  1720  4321 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 21:45:49.202  4323  4323 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 21:45:49.202  4323  4323 D AndroidRuntime: Shutting down VM
08-03 21:45:49.213  4323  4323 E AndroidRuntime: FATAL EXCEPTION: main
08-03 21:45:49.213  4323  4323 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4323
08-03 21:45:49.213  4323  4323 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-03 21:45:49.213  4323  4323 E AndroidRuntime: 	... 10 more
08-03 21:45:49.215   870   880 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-03 21:45:49.216  4323  4323 I Process : Sending signal. PID: 4323 SIG: 9
08-03 21:45:49.217   870  4348 E DropBoxManagerService: Can't write: system_app_crash
08-03 21:45:49.217   870  4348 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-03 21:45:49.217   870  4348 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 21:45:49.217   870  4348 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 21:45:49.217   870  4348 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 21:45:49.217   870  4348 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 21:45:49.217   870  4348 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 21:45:49.217   870  4348 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 21:45:49.217   870  4348 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 21:45:49.217   870  4348 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 21:45:49.217   870  4348 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 21:45:49.217   870  4348 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 21:45:49.217   870  4348 E DropBoxManagerService: 	... 5 more
08-03 21:45:49.230  1720  4321 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-03 21:45:49.231  1720  4321 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-03 21:45:49.241  4336  4336 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-03 21:45:49.247   870  1380 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4323) has died
08-03 21:45:49.249   870  1380 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-03 21:45:49.256  4286  4318 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-03 21:45:49.266   870   884 I ActivityManager: Start proc 4351:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-03 21:45:49.270   870  2850 I ActivityManager: Killing 1825:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
08-03 21:45:49.277  4286  4334 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-03 21:45:49.277  4286  4334 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 21:45:49.277  4286  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 21:45:49.277  4286  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 21:45:49.277  4286  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 21:45:49.277  4286  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 21:45:49.277  4286  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 21:45:49.277  4286  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 21:45:49.277  4286  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 21:45:49.277  4286  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 21:45:49.277  4286  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 21:45:49.277  4286  4334 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 21:45:49.277  4286  4334 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 21:45:49.277  4286  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 21:45:49.277  4286  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 21:45:49.277  4286  4334 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-03 21:45:49.277  4286  4334 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-03 21:45:49.277  4286  4334 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-03 21:45:49.277  4286  4334 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-03 21:45:49.277  4286  4334 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-03 21:45:49.277  4286  4334 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-03 21:45:49.277  4286  4334 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-03 21:45:49.277  4286  4334 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:45:49.277  4286  4334 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:45:49.277  4286  4334 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 21:45:49.278  4286  4334 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-03 21:45:49.278  4286  4334 E AndroidRuntime: Process: android.process.acore, PID: 4286
08-03 21:45:49.278  4286  4334 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 21:45:49.278  4286  4334 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 21:45:49.278  4286  4334 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 21:45:49.278  4286  4334 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 21:45:49.278  4286  4334 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 21:45:49.278  4286  4334 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 21:45:49.278  4286  4334 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 21:45:49.278  4286  4334 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 21:45:49.278  4286  4334 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 21:45:49.278  4286  4334 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 21:45:49.278  4286  4334 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 21:45:49.278  4286  4334 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 21:45:49.278  4286  4334 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 21:45:49.278  4286  4334 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 21:45:49.278  4286  4334 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-03 21:45:49.278  4286  4334 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-03 21:45:49.278  4286  4334 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-03 21:45:49.278  4286  4334 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-03 21:45:49.278  4286  4334 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-03 21:45:49.278  4286  4334 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-03 21:45:49.278  4286  4334 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-03 21:45:49.278  4286  4334 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:45:49.278  4286  4334 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:45:49.278  4286  4334 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 21:45:49.287  4286  4318 I Process : Sending signal. PID: 4286 SIG: 9
08-03 21:45:49.303  1500  1500 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-03 21:45:49.304  1500  1500 D AndroidRuntime: Shutting down VM
08-03 21:45:49.304  1500  1500 E AndroidRuntime: FATAL EXCEPTION: main
08-03 21:45:49.304  1500  1500 E AndroidRuntime: Process: com.google.process.gapps, PID: 1500
08-03 21:45:49.304  1500  1500 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 21:45:49.304  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-03 21:45:49.304  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-03 21:45:49.304  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-03 21:45:49.304  1500  1500 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:45:49.304  1500  1500 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:45:49.304  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 21:45:49.304  1500  1500 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 21:45:49.304  1500  1500 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 21:45:49.304  1500  1500 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 21:45:49.304  1500  1500 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 21:45:49.304  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-03 21:45:49.304  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-03 21:45:49.304  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-03 21:45:49.304  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-03 21:45:49.304  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-03 21:45:49.304  1500  1500 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-03 21:45:49.304  1500  1500 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-03 21:45:49.304  1500  1500 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-03 21:45:49.304  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-03 21:45:49.304  1500  1500 E AndroidRuntime: 	... 8 more

```
