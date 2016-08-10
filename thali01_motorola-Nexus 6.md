#### Test 797638305e9d4c1_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-10 15:46:48.350  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:46:48.373  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 15:46:48.378  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 15:46:48.431  1522  1991 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-10 15:46:48.431  1522  1991 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-10 15:46:48.431  1522  1991 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 15:46:48.431  1522  1991 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-10 15:46:48.459  2594  2594 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-10 15:46:48.460  2594  2594 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-10 15:46:48.460  2594  2594 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
08-10 15:46:48.919  3341  3341 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-10 15:46:48.924  3341  3341 D AndroidRuntime: CheckJNI is OFF
08-10 15:46:48.960  3341  3341 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-10 15:46:49.003  3341  3341 I Radio-JNI: register_android_hardware_Radio DONE
08-10 15:46:49.023  3341  3341 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-10 15:46:49.030   872  1685 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-10 15:46:49.080  1804  1815 W SearchService: Abort, client detached.
08-10 15:46:49.092  3341  3341 D AndroidRuntime: Shutting down VM
08-10 15:46:49.110  1804  1804 I HotwordDetector: Closing mic
08-10 15:46:49.110  1804  2130 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@96ec606
08-10 15:46:49.111  1804  2145 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-10 15:46:49.114   872   883 I ActivityManager: Start proc 3351:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-10 15:46:49.127  1804  1804 W ErrorReporter: reportError [type: 29, code: 917507]: null
08-10 15:46:49.176   374  2148 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-10 15:46:49.180   374  2148 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-10 15:46:49.190   374  1285 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-10 15:46:49.191  1804  2134 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-10 15:46:49.191  1804  2140 I MicroRecognitionRnrImpl: Detection finished
08-10 15:46:49.193  3351  3351 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-10 15:46:49.220  3351  3351 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-10 15:46:49.230  3351  3351 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 7310-7314)
08-10 15:46:49.230  3351  3351 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 15:46:49.245  3351  3351 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {de80018}
08-10 15:46:49.246  3351  3351 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 15:46:49.246  3351  3351 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-10 15:46:49.251  3351  3351 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-10 15:46:49.253  3351  3351 E SysUtils: ApplicationContext is null in ApplicationStatus
08-10 15:46:49.273  3351  3366 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
08-10 15:46:49.282  3351  3351 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-10 15:46:49.291  3351  3351 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 15:46:49.291  3351  3351 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 15:46:49.291  3351  3351 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-10 15:46:49.291  3351  3351 I Adreno  : Build Date                       : 10/20/15
08-10 15:46:49.291  3351  3351 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-10 15:46:49.291  3351  3351 I Adreno  : Local Branch                     : M14
08-10 15:46:49.291  3351  3351 I Adreno  : Remote Branch                    : 
08-10 15:46:49.291  3351  3351 I Adreno  : Remote Branch                    : 
08-10 15:46:49.291  3351  3351 I Adreno  : Reconstruct Branch               : 
,08-10 15:46:49.358   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b089f4e:true
,08-10 15:46:49.400  3351  3351 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-10 15:46:49.411  3351  3351 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-10 15:46:49.477  3351  3388 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-10 15:46:49.492  3351  3375 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-10 15:46:49.532  3351  3388 I OpenGLRenderer: Initialized EGL, version 1.4
,08-10 15:46:49.645   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +550ms
,08-10 15:46:49.653  1662  1662 I Keyboard.Facilitator: onFinishInput()
,08-10 15:46:49.730  3351  3351 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3351
,08-10 15:46:49.909   872  1854 I ActivityManager: Killing 2716:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,08-10 15:46:49.941   872  1854 I ActivityManager: Killing 3024:com.qualcomm.telephony/1001 (adj 15): empty #18
,08-10 15:46:49.964  3351  3351 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-10 15:46:50.204  3351  3391 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1701115600
,08-10 15:46:50.216  3351  3391 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-10 15:46:50.216  3351  3391 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-10 15:46:50.216  3351  3391 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-10 15:46:50.216  3351  3391 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-10 15:46:50.216  3351  3391 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-10 15:46:50.216  3351  3391 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2db21c added. We now have 1 listener(s)
,08-10 15:46:50.223  3351  3391 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61,
,08-10 15:46:50.224  3351  3391 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 15:46:50.225  3351  3391 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 15:46:50.226  3351  3391 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 15:46:50.230  3351  3391 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-10 15:46:50.230  3351  3391 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-10 15:46:50.230  3351  3391 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-10 15:46:50.230  3351  3391 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-10 15:46:50.230  3351  3391 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-10 15:46:50.230  3351  3391 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-10 15:46:50.230  3351  3391 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-10 15:46:50.230  3351  3391 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-10 15:46:50.230  3351  3391 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-10 15:46:50.230  3351  3391 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-10 15:46:50.230  3351  3391 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-10 15:46:50.230  3351  3391 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-10 15:46:50.230  3351  3391 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-10 15:46:50.230  3351  3391 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-10 15:46:50.230  3351  3391 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dcba5ab added. We now have 1 listener(s)
08-10 15:46:50.231  3351  3391 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 15:46:50.236   872  1315 D WifiService: New client listening to asynchronous messages
08-10 15:46:50.238  3351  3391 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 15:46:50.238  3351  3391 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-10 15:46:50.239  3351  3391 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-10 15:46:50.239  3351  3391 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-10 15:46:50.239  3351  3391 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-10 15:46:50.241  3351  3391 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 15:46:50.241  3351  3391 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-10 15:46:50.245  3351  3391 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:46:50.245  3351  3391 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 15:46:50.245  3351  3391 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:46:50.245  3351  3391 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 15:46:50.245  3351  3391 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 15:46:50.245  3351  3391 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 15:46:50.245  3351  3391 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 15:46:50.245  3351  3391 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 15:46:50.245  3351  3391 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 15:46:50.245  3351  3391 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-10 15:46:50.245  3351  3391 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 15:46:50.246  3351  3391 I io.jxcore.node.LifeCycleMonitor: start: OK
08-10 15:46:50.246  3351  3351 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 15:46:50.279  3351  3351 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-10 15:46:50.838  3351  3402 W jxcore-log: Initializing JXcore engine
,08-10 15:46:50.838  3351  3402 W jxcore-log: JXcore engine is ready
,08-10 15:46:50.873  3402  3402 W Thread-290: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8934 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-10 15:46:50.873  3402  3402 W Thread-290: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9795]" dev="sockfs" ino=9795 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-10 15:46:50.873  3402  3402 W Thread-290: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-10 15:46:50.888  3351  3402 W jxcore-log: Starting JXcore engine
,08-10 15:46:50.873  3402  3402 W Thread-290: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24604]" dev="sockfs" ino=24604 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,08-10 15:46:50.999  3351  3402 W jxcore-log: Platform android
08-10 15:46:50.999  3351  3402 W jxcore-log: 
,08-10 15:46:50.999  3351  3402 W jxcore-log: Process ARCH arm
08-10 15:46:50.999  3351  3402 W jxcore-log: 
,08-10 15:46:51.172  3351  3402 I jxcore-log: JXcore Cordova bridge is ready!
08-10 15:46:51.172  3351  3402 I jxcore-log: 
,08-10 15:46:51.172  3351  3402 W jxcore-log: JXcore engine is started
,08-10 15:46:51.183  3351  3391 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-10 15:46:51.186  3351  3351 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-10 15:47:01.222  3351  3402 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-10 15:47:01.222  3351  3402 I jxcore-log: 
,08-10 15:47:01.224  3351  3402 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-10 15:47:01.224  3351  3402 I jxcore-log: 
,08-10 15:47:01.226  3351  3402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 15:47:01.226  3351  3402 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 15:47:01.226  3351  3402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:47:01.226  3351  3402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 15:47:01.226  3351  3402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 15:47:01.226  3351  3402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 15:47:01.226  3351  3402 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 15:47:01.226  3351  3402 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 15:47:01.226  3351  3402 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 15:47:01.227  3351  3402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 15:47:01.227  3351  3402 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 15:47:01.229  3351  3402 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-10 15:47:01.229  3351  3402 I jxcore-log: 
,08-10 15:47:01.231  3351  3402 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-10 15:47:01.231  3351  3402 I jxcore-log: 
,08-10 15:47:01.560  3351  3402 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
,08-10 15:47:01.560  3351  3402 I jxcore-log: Failed to execute UT.
08-10 15:47:01.560  3351  3402 I jxcore-log: 
,08-10 15:47:01.560  3351  3402 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-10 15:47:01.560  3351  3402 I jxcore-log: 
,08-10 15:47:01.563  3351  3402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 15:47:01.563  3351  3402 I jxcore-log: 
,08-10 15:47:01.580  3351  3351 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-10 15:47:02.204  3408  3408 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-10 15:47:02.209  3408  3408 D AndroidRuntime: CheckJNI is OFF
,08-10 15:47:02.245  3408  3408 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-10 15:47:02.289  3408  3408 I Radio-JNI: register_android_hardware_Radio DONE
,08-10 15:47:02.309  3408  3408 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-10 15:47:02.321   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-10 15:47:02.322   872   885 I ActivityManager: Killing 3351:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-10 15:47:02.386   872  1857 D GraphicsStats: Buffer count: 2
,08-10 15:47:02.387   872  1685 I WindowState: WIN DEATH: Window{48177fe u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-10 15:47:02.387   872  1315 D WifiService: Client connection lost with reason: 4,
,08-10 15:47:02.409   872   885 W ActivityManager: Force removing ActivityRecord{2300887 u0 com.test.thalitest/.MainActivity t8}: app died, no saved state
,08-10 15:47:02.476   872   895 W PackageSettings: Skipping PackageSetting{1ba2267 com.example.hello/10273} due to missing metadata
,08-10 15:47:02.506   872   895 I art     : Starting a blocking GC Explicit
,08-10 15:47:02.516   872  1857 W ActivityManager: Spurious death for ProcessRecord{c3445dc 0:com.test.thalitest/u0a0}, curProc for 3351: null
,08-10 15:47:02.546   872   882 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3351 uid 10000
,08-10 15:47:02.548  1662  1662 I Keyboard.Facilitator: onFinishInput()
,08-10 15:47:02.589   872   895 I art     : Explicit concurrent mark sweep GC freed 18851(1260KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 28MB/42MB, paused 2.026ms total 77.284ms
,08-10 15:47:02.626   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-10 15:47:02.628  3408  3408 I art     : System.exit called, status: 0
08-10 15:47:02.628  3408  3408 I AndroidRuntime: VM exiting with result code 0.
08-10 15:47:02.633  1804  3422 I MicroRecognitionRnrImpl: Starting detection.
,08-10 15:47:02.635  1804  3423 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@366db8a
,08-10 15:47:02.636   374  3425 I AudioFlinger: AudioFlinger's thread 0xb3400000 ready to run
,08-10 15:47:02.640   374  1285 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-10 15:47:02.640  1804  3423 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@366db8a
,08-10 15:47:02.643   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-10 15:47:02.651   374  3425 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
,08-10 15:47:02.651   374  3425 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
08-10 15:47:02.651   374  3425 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,08-10 15:47:02.662   374  3425 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,08-10 15:47:02.662  1881  2034 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-10 15:47:02.663   872  1303 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-10 15:47:02.676  1761  1771 W art     : Suspending all threads took: 10.773ms
,08-10 15:47:02.677  1761  1771 I art     : Background partial concurrent mark sweep GC freed 3087(208KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 28MB/44MB, paused 11.318ms total 31.929ms
,08-10 15:47:02.687  3223  3223 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-10 15:47:02.688  1662  1662 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-10 15:47:02.706  1662  3429 I Keyboard.Facilitator.DecoderInitializer: run()
08-10 15:47:02.711  1747  1747 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-10 15:47:02.737  1804  1804 I HotwordWorkerImpl: onReady
,08-10 15:47:02.741  1662  3429 I Decoder : createOrResetDecoder
,08-10 15:47:02.719  2768  3430 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-10 15:47:02.763  1522  1522 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,08-10 15:47:02.763  1522  1522 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-10 15:47:02.781  1522  1522 I ConfigService: onCreate
,08-10 15:47:02.781  1866  3434 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-10 15:47:02.781  1866  3434 D AccountUtils: Clearing selected account for com.test.thalitest
,08-10 15:47:02.791  1866  3434 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-10 15:47:02.793   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-10 15:47:02.796  1866  1866 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-10 15:47:02.796  1866  1866 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-10 15:47:02.804  1866  3434 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-10 15:47:02.804  1866  3434 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 15:47:02.804  1866  3434 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 15:47:02.804  1866  3434 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 15:47:02.804  1866  3434 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 15:47:02.804  1866  3434 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 15:47:02.804  1866  3434 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 15:47:02.804  1866  3434 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 15:47:02.804  1866  3434 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 15:47:02.804  1866  3434 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 15:47:02.804  1866  3434 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 15:47:02.804  1866  3434 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 15:47:02.804  1866  3434 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 15:47:02.804  1866  3434 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 15:47:02.804  1866  3434 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 15:47:02.804  1866  3434 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 15:47:02.804  1866  3434 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-10 15:47:02.804  1866  3434 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 15:47:02.804  1866  3434 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:47:02.804  1866  3434 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:47:02.804  1866  3434 E SQLiteDatabase: ,	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-10 15:47:02.804  1866  3440 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
08-10 15:47:02.804  1866  3440 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 15:47:02.804  1866  3440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 15:47:02.804  1866  3440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 15:47:02.804  1866  3440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 15:47:02.804  1866  3440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 15:47:02.804  1866  3440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 15:47:02.804  1866  3440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 15:47:02.804  1866  3440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 15:47:02.804  1866  3440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 15:47:02.804  1866  3440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 15:47:02.804  1866  3440 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 15:47:02.804  1866  3440 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 15:47:02.804  1866  3440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
,08-10 15:47:02.804  1866  3440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 15:47:02.804  1866  3440 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-10 15:47:02.804  1866  3440 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-10 15:47:02.804  1866  3440 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-10 15:47:02.804  1866  3440 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-10 15:47:02.804  1866  3440 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 15:47:02.804  1866  3440 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:47:02.804  1866  3440 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:47:02.804  1866  3440 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 15:47:02.805  1866  3440 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
08-10 15:47:02.805  1866  3440 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 15:47:02.805  1866  3440 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 15:47:02.805  1866  3440 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 15:47:02.805  1866  3440 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 15:47:02.805  1866  3440 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 15:47:02.805  1866  3440 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 15:47:02.805  1866  3440 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 15:47:02.805  1866  3440 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 15:47:02.805  1866  3440 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 15:47:02.805  1866  3440 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 15:47:02.805  1866  3440 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 15:47:02.805  1866  3440 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 15:47:02.805  1866  3440 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 15:47:02.805  1866  3440 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 15:47:02.805  1866  3440 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-10 15:47:02.805  1866  3440 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-10 15:47:02.805  1866  3440 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-10 15:47:02.805  1866  3440 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-10 15:47:02.805  1866  3440 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 15:47:02.805  1866  3440 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:47:02.805  1866  3440 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:47:02.805  1866  3440 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-10 15:47:02.805  1866  3434 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
08-10 15:47:02.805  1866  3434 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 15:47:02.805  1866  3434 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 15:47:02.805  1866  3434 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 15:47:02.805  1866  3434 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 15:47:02.805  1866  3434 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 15:47:02.805  1866  3434 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 15:47:02.805  1866  3434 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 15:47:02.805  1866  3434 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 15:47:02.805  1866  3434 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 15:47:02.805  1866  3434 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 15:47:02.805  1866  3434 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 15:47:02.805  1866  3434 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 15:47:02.805  1866  3434 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 15:47:02.805  1866  3434 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 15:47:02.805  1866  3434 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 15:47:02.805  1866  3434 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-10 15:47:02.805  1866  3434 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 15:47:02.805  1866  3434 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:47:02.805  1866  3434 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:47:02.805  1866  3434 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 15:47:02.806  1866  3434 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
08-10 15:47:02.806  1866  3440 W SQLiteOpenHelper: Opened metrics.db in read-only mode
08-10 15:47:02.807  1866  3440 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
08-10 15:47:02.807  1866  3440 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
08-10 15:47:02.808  1866  3440 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
08-10 15:47:02.809  1866  3440 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
--------- beginning of crash
08-10 15:47:02.809  1866  3440 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
08-10 15:47:02.809  1866  3440 E AndroidRuntime: Process: com.google.android.gms, PID: 1866
08-10 15:47:02.809  1866  3440 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-10 15:47:02.809  1866  3440 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-10 15:47:02.809  1866  3440 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-10 15:47:02.809  1866  3440 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-10 15:47:02.809  1866  3440 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-10 15:47:02.809  1866  3440 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-10 15:47:02.809  1866  3440 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
08-10 15:47:02.809  1866  3440 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-10 15:47:02.809  1866  3440 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 15:47:02.809  1866  3440 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:47:02.809  1866  3440 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:47:02.809  1866  3440 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 15:47:02.811  1866  1866 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-10 15:47:02.812  1866  1866 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-10 15:47:02.818  2768  3430 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
08-10 15:47:02.821  1662  3429 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-10 15:47:02.822   872  3443 E DropBoxManagerService: Can't write: system_app_crash
08-10 15:47:02.822   872  3443 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
08-10 15:47:02.822   872  3443 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 15:47:02.822   872  3443 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 15:47:02.822   872  3443 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 15:47:02.822   872  3443 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 15:47:02.822   872  3443 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 15:47:02.822   872  3443 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 15:47:02.822   872  3443 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 15:47:02.822   872  3443 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 15:47:02.822   872  3443 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 15:47:02.822   872  3443 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 15:47:02.822   872  3443 E DropBoxManagerService: 	... 5 more
08-10 15:47:02.823  2768  3430 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-10 15:47:02.823  2768  3430 E AndroidRuntime: Process: android.process.acore, PID: 2768
08-10 15:47:02.823  2768  3430 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-10 15:47:02.823  2768  3430 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-10 15:47:02.823  2768  3430 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-10 15:47:02.823  2768  3430 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-10 15:47:02.823  2768  3430 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-10 15:47:02.823  2768  3430 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-10 15:47:02.823  2768  3430 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-10 15:47:02.823  2768  3430 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-10 15:47:02.823  2768  3430 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-10 15:47:02.823  2768  3430 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-10 15:47:02.823  2768  3430 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-10 15:47:02.823  2768  3430 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-10 15:47:02.823  2768  3430 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-10 15:47:02.823  2768  3430 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 15:47:02.823  2768  3430 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:47:02.823  2768  3430 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:47:02.823  2768  3430 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 15:47:02.827   872  3446 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-10 15:47:02.830  1804  3444 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-10 15:47:02.845  1866  3445 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-10 15:47:02.845  1866  3445 I Process : Sending signal. PID: 1866 SIG: 9
08-10 15:47:02.847   872  3447 E DropBoxManagerService: Can't write: system_app_crash
08-10 15:47:02.847   872  3447 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop103.tmp: open failed: EROFS (Read-only file system)
08-10 15:47:02.847   872  3447 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 15:47:02.847   872  3447 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 15:47:02.847   872  3447 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 15:47:02.847   872  3447 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 15:47:02.847   872  3447 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 15:47:02.847   872  3447 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 15:47:02.847   872  3447 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 15:47:02.847   872  3447 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 15:47:02.847   872  3447 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 15:47:02.847   872  3447 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 15:47:02.847   872  3447 E DropBoxManagerService: 	... 5 more
,08-10 15:47:02.859  1761  2132 E ReflectionEngine: Failed to save models
08-10 15:47:02.859  1761  2132 E ReflectionEngine: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/files/engine_16: open failed: EROFS (Read-only file system)
08-10 15:47:02.859  1761  2132 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 15:47:02.859  1761  2132 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 15:47:02.859  1761  2132 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 15:47:02.859  1761  2132 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.BT(ReflectionEngine.java:123)
08-10 15:47:02.859  1761  2132 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:240)
08-10 15:47:02.859  1761  2132 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-10 15:47:02.859  1761  2132 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-10 15:47:02.859  1761  2132 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-10 15:47:02.859  1761  2132 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 15:47:02.859  1761  2132 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 15:47:02.859  1761  2132 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 15:47:02.859  1761  2132 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 15:47:02.859  1761  2132 E ReflectionEngine: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-10 15:47:02.859  1761  2132 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 15:47:02.859  1761  2132 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 15:47:02.859  1761  2132 E ReflectionEngine: 	at java.lang.Thread.run(Thread.java:818)
08-10 15:47:02.859  1761  2132 E ReflectionEngine: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-10 15:47:02.859  1761  2132 E ReflectionEngine: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 15:47:02.859  1761  2132 E ReflectionEngine: 	at libcore.io.Posix.open(Native Method)
08-10 15:47:02.859  1761  2132 E ReflectionEngine: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 15:47:02.859  1761  2132 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 15:47:02.859  1761  2132 E ReflectionEngine: 	... 16 more
08-10 15:47:02.861  1804  3444 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-10 15:47:02.864   872  1684 I ActivityManager: Start proc 3450:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
08-10 15:47:02.870   872  3446 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-10 15:47:02.870   872  3446 I Adreno  : Build Date                       : 10/20/15
08-10 15:47:02.870   872  3446 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-10 15:47:02.870   872  3446 I Adreno  : Local Branch                     : M14
08-10 15:47:02.870   872  3446 I Adreno  : Remote Branch                    : 
08-10 15:47:02.870   872  3446 I Adreno  : Remote Branch                    : 
08-10 15:47:02.870   872  3446 I Adreno  : Reconstruct Branch               : 
08-10 15:47:02.879   872  3446 I OpenGLRenderer: Initialized EGL, version 1.4
08-10 15:47:02.882   872  1855 I ActivityManager: Start proc 3462:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-10 15:47:02.885  1804  3444 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
08-10 15:47:02.885  1804  3444 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-10 15:47:02.885  1804  3444 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 1804
08-10 15:47:02.885  1804  3444 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-10 15:47:02.885  1804  3444 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-10 15:47:02.885  1804  3444 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-10 15:47:02.885  1804  3444 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-10 15:47:02.885  1804  3444 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-10 15:47:02.885  1804  3444 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-10 15:47:02.885  1804  3444 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-10 15:47:02.885  1804  3444 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-10 15:47:02.885  1804  3444 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-10 15:47:02.885  1804  3444 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-10 15:47:02.885  1804  3444 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-10 15:47:02.885  1804  3444 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-10 15:47:02.885  1804  3444 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-10 15:47:02.885  1804  3444 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-10 15:47:02.885  1804  3444 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-10 15:47:02.885  1804  3444 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 15:47:02.885  1804  3444 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:47:02.885  1804  3444 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:47:02.885  1804  3444 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-10 15:47:02.900   872  3473 E DropBoxManagerService: Can't write: system_app_crash
08-10 15:47:02.900   872  3473 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop104.tmp: open failed: EROFS (Read-only file system)
08-10 15:47:02.900   872  3473 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 15:47:02.900   872  3473 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 15:47:02.900   872  3473 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 15:47:02.900   872  3473 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 15:47:02.900   872  3473 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 15:47:02.900   872  3473 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 15:47:02.900   872  3473 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 15:47:02.900   872  3473 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 15:47:02.900   872  3473 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 15:47:02.900   872  3473 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 15:47:02.900   872  3473 E DropBoxManagerService: 	... 5 more
,08-10 15:47:02.906  1761  2132 E ObservedEventLogger: Failed to write the stream file
08-10 15:47:02.906  1761  2132 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2427: open failed: EROFS (Read-only file system)
08-10 15:47:02.906  1761  2132 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 15:47:02.906  1761  2132 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 15:47:02.906  1761  2132 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-10 15:47:02.906  1761  2132 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-10 15:47:02.906  1761  2132 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-10 15:47:02.906  1761  2132 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-10 15:47:02.906  1761  2132 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-10 15:47:02.906  1761  2132 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-10 15:47:02.906  1761  2132 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 15:47:02.906  1761  2132 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 15:47:02.906  1761  2132 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 15:47:02.906  1761  2132 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 15:47:02.906  1761  2132 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-10 15:47:02.906  1761  2132 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 15:47:02.906  1761  2132 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 15:47:02.906  1761  2132 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
08-10 15:47:02.906  1761  2132 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-10 15:47:02.906  1761  2132 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 15:47:02.906  1761  2132 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-10 15:47:02.906  1761  2132 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 15:47:02.906  1761  2132 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 15:47:02.906  1761  2132 E ObservedEventLogger: 	... 16 more
,08-10 15:47:02.908  1761  1830 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-10 15:47:02.908  1761  2132 E ObservedEventLogger: Failed to write the stream file
08-10 15:47:02.908  1761  2132 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2431: open failed: EROFS (Read-only file system)
08-10 15:47:02.908  1761  2132 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 15:47:02.908  1761  2132 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 15:47:02.908  1761  2132 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-10 15:47:02.908  1761  2132 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-10 15:47:02.908  1761  2132 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-10 15:47:02.908  1761  2132 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-10 15:47:02.908  1761  2132 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-10 15:47:02.908  1761  2132 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-10 15:47:02.908  1761  2132 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 15:47:02.908  1761  2132 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 15:47:02.908  1761  2132 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 15:47:02.908  1761  2132 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 15:47:02.908  1761  2132 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-10 15:47:02.908  1761  2132 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 15:47:02.908  1761  2132 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 15:47:02.908  1761  2132 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
08-10 15:47:02.908  1761  2132 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-10 15:47:02.908  1761  2132 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 15:47:02.908  1761  2132 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-10 15:47:02.908  1761  2132 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 15:47:02.908  1761  2132 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 15:47:02.908  1761  2132 E ObservedEventLogger: 	... 16 more
,08-10 15:47:02.911  1761  1830 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-10 15:47:02.911  1761  1830 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1761
08-10 15:47:02.911  1761  1830 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-10 15:47:02.911  1761  1830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-10 15:47:02.911  1761  1830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-10 15:47:02.911  1761  1830 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-10 15:47:02.911  1761  1830 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-10 15:47:02.911  1761  1830 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-10 15:47:02.911  1761  1830 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-10 15:47:02.911  1761  1830 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-10 15:47:02.911  1761  1830 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 15:47:02.911  1761  1830 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 15:47:02.911  1761  1830 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:47:02.911  1761  1830 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-10 15:47:02.913   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak,
08-10 15:47:02.914   872  1854 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
08-10 15:47:02.914   872  1854 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-10 15:47:02.915   872  3477 E DropBoxManagerService: Can't write: system_app_crash
08-10 15:47:02.915   872  3477 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop107.tmp: open failed: EROFS (Read-only file system)
08-10 15:47:02.915   872  3477 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 15:47:02.915   872  3477 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 15:47:02.915   872  3477 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 15:47:02.915   872  3477 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 15:47:02.915   872  3477 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 15:47:02.915   872  3477 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 15:47:02.915   872  3477 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 15:47:02.915   872  3477 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 15:47:02.915   872  3477 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 15:47:02.915   872  3477 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 15:47:02.915   872  3477 E DropBoxManagerService: 	... 5 more
,08-10 15:47:02.916   872   884 E PackageManager: Failed to write settings, restoring backup
08-10 15:47:02.916   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-10 15:47:02.916   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-10 15:47:02.916   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-10 15:47:02.916   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-10 15:47:02.916   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-10 15:47:02.916   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:47:02.916   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:47:02.916   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-10 15:47:02.919   872  1854 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-10 15:47:02.921   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-10 15:47:02.921   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-10 15:47:02.921   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 15:47:02.921   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 15:47:02.921   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 15:47:02.921   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 15:47:02.921   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 15:47:02.921   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 15:47:02.921   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-10 15:47:02.921   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-10 15:47:02.921   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-10 15:47:02.921   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 15:47:02.921   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 15:47:02.921   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:47:02.921   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 15:47:02.921   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-10 15:47:02.921   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 15:47:02.921   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 15:47:02.921   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 15:47:02.921   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 15:47:02.921   872   885 E DropBoxManagerService: 	... 13 more
,08-10 15:47:02.926   872  1700 W WindowManager: Failed looking up window
08-10 15:47:02.926   872  1700 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@fbe2279 does not exist
08-10 15:47:02.926   872  1700 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8736)
08-10 15:47:02.926   872  1700 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8727)
08-10 15:47:02.926   872  1700 W WindowManager: 	at com.android.server.wm.WindowManagerService.relayoutWindow(WindowManagerService.java:3105)
08-10 15:47:02.926   872  1700 W WindowManager: 	at com.android.server.wm.Session.relayout(Session.java:198)
08-10 15:47:02.926   872  1700 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:284)
08-10 15:47:02.926   872  1700 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:130)
08-10 15:47:02.926   872  1700 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 15:47:02.929   872  1854 I ActivityManager: Killing 1761:com.google.android.googlequicksearchbox/u0a28 (adj 0): crash
,08-10 15:47:02.952   872  1684 D GraphicsStats: Buffer count: 2
,08-10 15:47:02.985  3450  3450 W System  : ClassLoader referenced unknown path: /system/app/KeyChain/lib/arm
,08-10 15:47:02.988  3450  3450 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
,08-10 15:47:02.990  1662  3429 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-10 15:47:02.993  1662  3429 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-10 15:47:02.993  1662  3429 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-10 15:47:02.995  1662  3429 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-10 15:47:02.995  1662  3429 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-10 15:47:02.996  1662  3429 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-10 15:47:02.996  1662  3429 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-10 15:47:02.998  1662  3429 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-10 15:47:02.998  1662  3429 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-10 15:47:02.998  1662  3429 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-10 15:47:03.000   872  1854 I ActivityManager: Start proc 3483:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-10 15:47:03.003   872  1389 I ActivityManager: Process com.google.android.gms (pid 1866) has died
08-10 15:47:03.004   872  1389 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
,08-10 15:47:03.005   872  1389 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
,08-10 15:47:03.005   872  1389 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
08-10 15:47:03.005   872  1389 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 11000ms
08-10 15:47:03.005   872  1389 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20999ms
,08-10 15:47:03.005   872  1389 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20999ms
,08-10 15:47:03.005   872  1389 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20999ms
,08-10 15:47:03.011   872  1685 W ActivityManager: Spurious death for ProcessRecord{4f1712f 0:com.google.android.googlequicksearchbox/u0a28}, curProc for 1761: null
,08-10 15:47:03.015  1804  1804 E AttachedClient: AttachedClient[7563437429398, ClientConfig[mFlags=[210d800202] mSuggestFlags=[3b] mClientStats=SearchBoxStats[gel/android-search-app]]]: failed callback onGenericEvent()
08-10 15:47:03.015  1804  1804 E AttachedClient: android.os.DeadObjectException
08-10 15:47:03.015  1804  1804 E AttachedClient: 	at android.os.BinderProxy.transactNative(Native Method)
08-10 15:47:03.015  1804  1804 E AttachedClient: 	at android.os.BinderProxy.transact(Binder.java:503)
08-10 15:47:03.015  1804  1804 E AttachedClient: 	at com.google.android.apps.gsa.search.shared.service.l.c(ISearchServiceUiCallback.java:578)
08-10 15:47:03.015  1804  1804 E AttachedClient: 	at com.google.android.search.core.service.a.c(AttachedClient.java:4725)
08-10 15:47:03.015  1804  1804 E AttachedClient: 	at com.google.android.search.core.service.a.b(AttachedClient.java:185)
08-10 15:47:03.015  1804  1804 E AttachedClient: 	at com.google.android.search.core.ad.c(SearchController.java:51069)
08-10 15:47:03.015  1804  1804 E AttachedClient: 	at com.google.android.search.core.service.SearchService.bca(SearchService.java:373)
08-10 15:47:03.015  1804  1804 E AttachedClient: 	at com.google.android.search.core.service.SearchService$1.run(SearchService.java:83)
08-10 15:47:03.015  1804  1804 E AttachedClient: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 15:47:03.015  1804  1804 E AttachedClient: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 15:47:03.015  1804  1804 E AttachedClient: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:47:03.015  1804  1804 E AttachedClient: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 15:47:03.015  1804  1804 E AttachedClient: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 15:47:03.015  1804  1804 E AttachedClient: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 15:47:03.015  1804  1804 E AttachedClient: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-10 15:47:03.015  1804  1804 I SearchService: Ignoring already detached client
,08-10 15:47:03.055  3483  3483 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 15:47:03.055  3483  3483 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 15:47:03.056  3483  3483 D AndroidRuntime: Shutting down VM
08-10 15:47:03.058  1804  2130 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@366db8a
08-10 15:47:03.058  1804  3423 E AudioRecord-JNI: Error -4 during AudioRecord native read,
08-10 15:47:03.059  1804  1804 I HotwordDetector: Closing mic
08-10 15:47:03.060  3483  3483 E AndroidRuntime: FATAL EXCEPTION: main
08-10 15:47:03.060  3483  3483 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3483
08-10 15:47:03.060  3483  3483 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-10 15:47:03.060  3483  3483 E Androi,dRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-10 15:47:03.060  3483  3483 E AndroidRuntime: 	... 10 more
08-10 15:47:03.060  1662  3429 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-10 15:47:03.060  1662  3429 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-10 15:47:03.060  1662  3429 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-10 15:47:03.062   872  3497 E DropBoxManagerService: Can't write: system_app_crash
08-10 15:47:03.062   872  3497 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
08-10 15:47:03.062   872  3497 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 15:47:03.062   872  3497 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 15:47:03.062   872  3497 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 15:47:03.062   872  3497 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 15:47:03.062   872  3497 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 15:47:03.062   872  3497 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 15:47:03.062   872  3497 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 15:47:03.062   872  3497 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 15:47:03.062   872  3497 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 15:47:03.062   872  3497 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 15:47:03.062   872  3497 E DropBoxManagerService: 	... 5 more
08-10 15:47:03.069   872  1855 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-10 15:47:03.085   872  1389 I ActivityManager: Start proc 3500:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
08-10 15:47:03.093  1804  1804 W ErrorReporter: reportError [type: 29, code: 917507]: null
,08-10 15:47:03.116  3450  3496 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.keychain/databases/grants.db'.
08-10 15:47:03.116  3450  3496 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 15:47:03.116  3450  3496 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 15:47:03.116  3450  3496 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 15:47:03.116  3450  3496 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 15:47:03.116  3450  3496 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 15:47:03.116  3450  3496 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 15:47:03.116  3450  3496 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 15:47:03.116  3450  3496 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 15:47:03.116  3450  3496 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 15:47:03.116  3450  3496 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 15:47:03.116  3450  3496 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 15:47:03.116  3450  3496 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 15:47:03.116  3450  3496 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 15:47:03.116  3450  3496 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-10 15:47:03.116  3450  3496 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-10 15:47:03.116  3450  3496 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-10 15:47:03.116  3450  3496 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 15:47:03.116  3450  3496 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:47:03.116  3450  3496 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:47:03.116  3450  3496 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-10 15:47:03.116  3450  3496 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-10 15:47:03.116  3450  3496 E AndroidRuntime: Process: com.android.keychain, PID: 3450
08-10 15:47:03.116  3450  3496 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 15:47:03.116  3450  3496 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 15:47:03.116  3450  3496 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 15:47:03.116  3450  3496 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 15:47:03.116  3450  3496 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 15:47:03.116  3450  3496 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 15:47:03.116  3450  3496 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 15:47:03.116  3450  3496 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 15:47:03.116  3450  3496 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 15:47:03.116  3450  3496 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 15:47:03.116  3450  3496 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 15:47:03.116  3450  3496 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 15:47:03.116  3450  3496 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 15:47:03.116  3450  3496 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-10 15:47:03.116  3450  3496 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-10 15:47:03.116  3450  3496 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-10 15:47:03.116  3450  3496 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 15:47:03.116  3450  3496 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:47:03.116  3450  3496 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:47:03.116  3450  3496 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-10 15:47:03.125   374  3425 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,08-10 15:47:03.126   374  3425 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
,08-10 15:47:03.132   374  1285 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-10 15:47:03.139   872  3513 E DropBoxManagerService: Can't write: system_app_crash
08-10 15:47:03.139   872  3513 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
08-10 15:47:03.139   872  3513 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 15:47:03.139   872  3513 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 15:47:03.139   872  3513 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 15:47:03.139   872  3513 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 15:47:03.139   872  3513 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 15:47:03.139   872  3513 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 15:47:03.139   872  3513 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 15:47:03.139   872  3513 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 15:47:03.139   872  3513 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 15:47:03.139   872  3513 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 15:47:03.139   872  3513 E DropBoxManagerService: 	... 5 more
,08-10 15:47:03.140  1804  3422 I MicroRecognitionRnrImpl: Detection finished
,08-10 15:47:03.141  1804  2134 I MicroRecognitionRnrImpl: Stopping hotword detection.
,08-10 15:47:03.147   872   872 I ActivityManager: Start proc 3514:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,08-10 15:47:03.185  3514  3514 W System  : ClassLoader referenced unknown path: /system/app/DocumentsUI/lib/arm
,08-10 15:47:03.203   281   281 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,08-10 15:47:03.204   281   281 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
08-10 15:47:03.204   281   281 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
08-10 15:47:03.204   281   281 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
08-10 15:47:03.204   281   281 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-10 15:47:03.204   281   281 E qdoverlay: MdpCtrl close error in unset
,08-10 15:47:03.207  3500  3500 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-10 15:47:03.225  3500  3500 I MultiDex: VM with version 2.1.0 has multidex support
08-10 15:47:03.225  3500  3500 I MultiDex: install
08-10 15:47:03.225  3500  3500 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-10 15:47:03.251   872   882 I ActivityManager: Start proc 3527:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider

```
