#### Test 7976383036177d0_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main,
08-10 16:35:20.459  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 16:35:20.470  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 16:35:20.472  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 16:35:20.496  1514  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-10 16:35:20.497  1514  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-10 16:35:20.497  1514  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 16:35:20.497  1514  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-10 16:35:20.511  2581  2581 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-10 16:35:20.511  2581  2581 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-10 16:35:20.511  2581  2581 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
08-10 16:35:21.041  3315  3315 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-10 16:35:21.046  3315  3315 D AndroidRuntime: CheckJNI is OFF
08-10 16:35:21.089  3315  3315 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-10 16:35:21.139  3315  3315 I Radio-JNI: register_android_hardware_Radio DONE
08-10 16:35:21.161  3315  3315 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-10 16:35:21.165   874  1743 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-10 16:35:21.203  1803  3299 W SearchService: Abort, client detached.
08-10 16:35:21.214  3315  3315 D AndroidRuntime: Shutting down VM
08-10 16:35:21.214  1803  2106 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@2053535
08-10 16:35:21.215  1803  2123 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-10 16:35:21.215  1803  1803 I HotwordDetector: Closing mic
08-10 16:35:21.243   874   884 I ActivityManager: Start proc 3324:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-10 16:35:21.252  1803  1803 W ErrorReporter: reportError [type: 29, code: 917507]: null
08-10 16:35:21.281   374  2125 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-10 16:35:21.282   374  2125 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-10 16:35:21.289   374  1275 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-10 16:35:21.291  1803  2120 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-10 16:35:21.291  1803  2122 I MicroRecognitionRnrImpl: Detection finished
08-10 16:35:21.316  3324  3324 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-10 16:35:21.345  3324  3324 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-10 16:35:21.415  3324  3324 I LibraryLoader: Time to load native libraries: 65 ms (timestamps 7534-7599)
08-10 16:35:21.416  3324  3324 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 16:35:21.438  3324  3324 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b28ba4b}
08-10 16:35:21.438  3324  3324 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 16:35:21.439  3324  3324 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-10 16:35:21.444  3324  3324 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-10 16:35:21.446  3324  3324 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-10 16:35:21.513  3324  3339 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,08-10 16:35:21.519  3324  3324 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-10 16:35:21.531  3324  3324 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-10 16:35:21.531  3324  3324 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 16:35:21.531  3324  3324 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-10 16:35:21.531  3324  3324 I Adreno  : Build Date                       : 10/20/15,
08-10 16:35:21.531  3324  3324 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-10 16:35:21.531  3324  3324 I Adreno  : Local Branch                     : M14
08-10 16:35:21.531  3324  3324 I Adreno  : Remote Branch                    : 
08-10 16:35:21.531  3324  3324 I Adreno  : Remote Branch                    : 
08-10 16:35:21.531  3324  3324 I Adreno  : Reconstruct Branch               : 
,08-10 16:35:21.590   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4405fad:true
,08-10 16:35:21.633  3324  3324 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-10 16:35:21.647  3324  3324 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-10 16:35:21.692  3324  3362 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-10 16:35:21.702  3324  3348 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-10 16:35:21.734  3324  3362 I OpenGLRenderer: Initialized EGL, version 1.4
,08-10 16:35:21.790   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +573ms
,08-10 16:35:21.796  1653  1653 I Keyboard.Facilitator: onFinishInput()
,08-10 16:35:21.858  3324  3324 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3324
,08-10 16:35:21.969  3324  3324 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-10 16:35:22.050   874  1743 I ActivityManager: Killing 2695:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,08-10 16:35:22.082   874  1743 I ActivityManager: Killing 2999:com.qualcomm.telephony/1001 (adj 15): empty #18
,08-10 16:35:22.173  3324  3364 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1680672464
,08-10 16:35:22.178  3324  3364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-10 16:35:22.178  3324  3364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-10 16:35:22.178  3324  3364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-10 16:35:22.178  3324  3364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-10 16:35:22.178  3324  3364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-10 16:35:22.178  3324  3364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfa137e added. We now have 1 listener(s)
,08-10 16:35:22.181  3324  3364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-10 16:35:22.183  3324  3364 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 16:35:22.184  3324  3364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-10 16:35:22.184  3324  3364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 16:35:22.187  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-10 16:35:22.187  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-10 16:35:22.187  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-10 16:35:22.187  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-10 16:35:22.187  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-10 16:35:22.187  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-10 16:35:22.187  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-10 16:35:22.187  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-10 16:35:22.187  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-10 16:35:22.187  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-10 16:35:22.187  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-10 16:35:22.187  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-10 16:35:22.187  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-10 16:35:22.187  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-10 16:35:22.187  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaa77f5 added. We now have 1 listener(s)
,08-10 16:35:22.188  3324  3364 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 16:35:22.190   874  1302 D WifiService: New client listening to asynchronous messages
08-10 16:35:22.191  3324  3364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 16:35:22.191  3324  3364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-10 16:35:22.191  3324  3364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-10 16:35:22.191  3324  3364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-10 16:35:22.191  3324  3364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-10 16:35:22.193  3324  3364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 16:35:22.193  3324  3364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-10 16:35:22.195  3324  3364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 16:35:22.195  3324  3364 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 16:35:22.195  3324  3364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 16:35:22.195  3324  3364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 16:35:22.195  3324  3364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 16:35:22.195  3324  3364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 16:35:22.195  3324  3364 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 16:35:22.195  3324  3364 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 16:35:22.195  3324  3364 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 16:35:22.195  3324  3364 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-10 16:35:22.195  3324  3364 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 16:35:22.196  3324  3364 I io.jxcore.node.LifeCycleMonitor: start: OK
08-10 16:35:22.196  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 16:35:22.234  3324  3324 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-10 16:35:22.906  3324  3375 W jxcore-log: Initializing JXcore engine
,08-10 16:35:22.907  3324  3375 W jxcore-log: JXcore engine is ready
,08-10 16:35:22.939  3375  3375 W Thread-290: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8986 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-10 16:35:22.939  3375  3375 W Thread-290: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10824]" dev="sockfs" ino=10824 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-10 16:35:22.939  3375  3375 W Thread-290: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-10 16:35:22.943  3375  3375 W Thread-290: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[23774]" dev="sockfs" ino=23774 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-10 16:35:22.956  3324  3375 W jxcore-log: Starting JXcore engine
,08-10 16:35:23.035  3324  3375 W jxcore-log: Platform android
08-10 16:35:23.035  3324  3375 W jxcore-log: 
,08-10 16:35:23.035  3324  3375 W jxcore-log: Process ARCH arm
08-10 16:35:23.035  3324  3375 W jxcore-log: 
,08-10 16:35:23.199  3324  3375 I jxcore-log: JXcore Cordova bridge is ready!
08-10 16:35:23.199  3324  3375 I jxcore-log: 
,08-10 16:35:23.199  3324  3375 W jxcore-log: JXcore engine is started
,08-10 16:35:23.208  3324  3364 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-10 16:35:23.213  3324  3324 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-10 16:35:33.414  3324  3375 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-10 16:35:33.414  3324  3375 I jxcore-log: 
,08-10 16:35:33.416  3324  3375 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-10 16:35:33.416  3324  3375 I jxcore-log: 
,08-10 16:35:33.418  3324  3375 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 16:35:33.418  3324  3375 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 16:35:33.418  3324  3375 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 16:35:33.418  3324  3375 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 16:35:33.418  3324  3375 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 16:35:33.418  3324  3375 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 16:35:33.418  3324  3375 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 16:35:33.418  3324  3375 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 16:35:33.418  3324  3375 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 16:35:33.418  3324  3375 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 16:35:33.418  3324  3375 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 16:35:33.421  3324  3375 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-10 16:35:33.421  3324  3375 I jxcore-log: 
08-10 16:35:33.423  3324  3375 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-10 16:35:33.423  3324  3375 I jxcore-log: 
,08-10 16:35:33.742  3324  3375 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-10 16:35:33.742  3324  3375 I jxcore-log: Failed to execute UT.
08-10 16:35:33.742  3324  3375 I jxcore-log: 
,08-10 16:35:33.742  3324  3375 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-10 16:35:33.742  3324  3375 I jxcore-log: 
,08-10 16:35:33.745  3324  3375 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 16:35:33.745  3324  3375 I jxcore-log: 
,08-10 16:35:33.761  3324  3324 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-10 16:35:34.378  3381  3381 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-10 16:35:34.383  3381  3381 D AndroidRuntime: CheckJNI is OFF
,08-10 16:35:34.419  3381  3381 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-10 16:35:34.462  3381  3381 I Radio-JNI: register_android_hardware_Radio DONE
,08-10 16:35:34.482  3381  3381 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-10 16:35:34.499   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-10 16:35:34.500   874   887 I ActivityManager: Killing 3324:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-10 16:35:34.600   874  1679 D GraphicsStats: Buffer count: 2
,08-10 16:35:34.600   874   885 I WindowState: WIN DEATH: Window{7658e1d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-10 16:35:34.601   874  1302 D WifiService: Client connection lost with reason: 4
,08-10 16:35:34.627   874   887 W ActivityManager: Force removing ActivityRecord{687b8da u0 com.test.thalitest/.MainActivity t8}: app died, no saved state
,08-10 16:35:34.649   874   898 W PackageSettings: Skipping PackageSetting{252c4b6 com.example.hello/10273} due to missing metadata
,08-10 16:35:34.683   874   898 I art     : Starting a blocking GC Explicit
,08-10 16:35:34.707   874  1679 W ActivityManager: Spurious death for ProcessRecord{8d51a53 0:com.test.thalitest/u0a0}, curProc for 3324: null
,08-10 16:35:34.733   874   898 I art     : Explicit concurrent mark sweep GC freed 18161(1214KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 28MB/42MB, paused 852us total 42.626ms
,08-10 16:35:34.756   874   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-10 16:35:34.760  3381  3381 I art     : System.exit called, status: 0
,08-10 16:35:34.760  3381  3381 I AndroidRuntime: VM exiting with result code 0.
,08-10 16:35:34.770   874  1484 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3324 uid 10000
,08-10 16:35:34.772  1653  1653 I Keyboard.Facilitator: onFinishInput()
,08-10 16:35:34.777   874   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-10 16:35:34.803  1653  1653 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-10 16:35:34.803   874  1293 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-10 16:35:34.811  1844  2019 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-10 16:35:34.817  3194  3194 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-10 16:35:34.827  1653  3393 I Keyboard.Facilitator.DecoderInitializer: run(),
,08-10 16:35:34.844  1737  1737 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-10 16:35:34.853  1653  3393 I Decoder : createOrResetDecoder
,08-10 16:35:34.857  1756  1766 I art     : Background partial concurrent mark sweep GC freed 1808(86KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 28MB/44MB, paused 12.714ms total 32.898ms
,08-10 16:35:34.874  1803  1803 W ThreadPoolDumper: Queue length for executor AudioRouter with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,08-10 16:35:34.894  2739  3398 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-10 16:35:34.897  1514  1514 I ConfigService: onCreate
,08-10 16:35:34.914  1514  1514 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,08-10 16:35:34.914  1514  1514 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
08-10 16:35:34.920   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-10 16:35:34.922  1653  3393 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-10 16:35:34.930  1823  3403 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-10 16:35:34.930  1823  3403 D AccountUtils: Clearing selected account for com.test.thalitest
08-10 16:35:34.941  1823  3403 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
08-10 16:35:34.944  1803  3406 I MicroRecognitionRnrImpl: Starting detection.
08-10 16:35:34.946  1803  3407 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@70fa1dc
,08-10 16:35:34.954   374  3410 I AudioFlinger: AudioFlinger's thread 0xb1e00000 ready to run
08-10 16:35:34.955   374  1275 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-10 16:35:34.955  1823  3403 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-10 16:35:34.955  1823  3403 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 16:35:34.955  1823  3403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 16:35:34.955  1823  3403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 16:35:34.955  1823  3403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 16:35:34.955  1823  3403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 16:35:34.955  1823  3403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 16:35:34.955  1823  3403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 16:35:34.955  1823  3403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 16:35:34.955  1823  3403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 16:35:34.955  1823  3403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 16:35:34.955  1823  3403 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 16:35:34.955  1823  3403 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 16:35:34.955  1823  3403 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 16:35:34.955  1823  3403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 16:35:34.955  1823  3403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 16:35:34.955  1823  3403 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-10 16:35:34.955  1823  3403 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 16:35:34.955  1823  3403 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 16:35:34.955  1823  3403 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-10 16:35:34.955  1823  3403 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 16:35:34.955  1823  3403 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
08-10 16:35:34.955  1823  3403 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 16:35:34.955  1823  3403 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 16:35:34.955  1823  3403 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 16:35:34.955  1823  3403 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 16:35:34.955  1823  3403 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 16:35:34.955  1823  3403 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 16:35:34.955  1823  3403 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool,.java:177)
08-10 16:35:34.955  1823  3403 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 16:35:34.955  1823  3403 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 16:35:34.955  1823  3403 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 16:35:34.955  1823  3403 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 16:35:34.955  1823  3403 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 16:35:34.955  1823  3403 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 16:35:34.955  1823  3403 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 16:35:34.955  1823  3403 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 16:35:34.955  1823  3403 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-10 16:35:34.955  1823  3403 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 16:35:34.955  1823  3403 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 16:35:34.955  1823  3403 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-10 16:35:34.955  1823  3403 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 16:35:34.957  1823  3403 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,08-10 16:35:34.959  1803  3407 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@70fa1dc
,08-10 16:35:34.963  1823  1823 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-10 16:35:34.963  1823  1823 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-10 16:35:34.966   374  3410 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
08-10 16:35:34.966   374  3410 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
,08-10 16:35:34.966   374  3410 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,08-10 16:35:34.975   374  3410 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,08-10 16:35:34.975  1823  3413 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
08-10 16:35:34.975  1823  3413 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 16:35:34.975  1823  3413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 16:35:34.975  1823  3413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 16:35:34.975  1823  3413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 16:35:34.975  1823  3413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 16:35:34.975  1823  3413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 16:35:34.975  1823  3413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 16:35:34.975  1823  3413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 16:35:34.975  1823  3413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 16:35:34.975  1823  3413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 16:35:34.975  1823  3413 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 16:35:34.975  1823  3413 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 16:35:34.975  1823  3413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 16:35:34.975  1823  3413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 16:35:34.975  1823  3413 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-10 16:35:34.975  1823  3413 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-10 16:35:34.975  1823  3413 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-10 16:35:34.975  1823  3413 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-10 16:35:34.975  1823  3413 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 16:35:34.975  1823  3413 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 16:35:34.975  1823  3413 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-10 16:35:34.975  1823  3413 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-10 16:35:34.977  1823  1823 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-10 16:35:34.977  1823  1823 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-10 16:35:34.978  1803  3416 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-10 16:35:34.978  1823  3413 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
08-10 16:35:34.978  1823  3413 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 16:35:34.978  1823  3413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 16:35:34.978  1823  3413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 16:35:34.978  1823  3413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 16:35:34.978  1823  3413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 16:35:34.978  1823  3413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 16:35:34.978  1823  3413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 16:35:34.978  1823  3413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 16:35:34.978  1823  3413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 16:35:34.978  1823  3413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 16:35:34.978  1823  3413 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 16:35:34.978  1823  3413 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 16:35:34.978  1823  3413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 16:35:34.978  1823  3413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 16:35:34.978  1823  3413 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-10 16:35:34.978  1823  3413 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-10 16:35:34.978  1823  3413 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-10 16:35:34.978  1823  3413 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-10 16:35:34.978  1823  3413 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 16:35:34.978  1823  3413 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 16:35:34.978  1823  3413 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-10 16:35:34.978  1823  3413 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 16:35:34.980  1823  3413 W SQLiteOpenHelper: Opened metrics.db in read-only mode
08-10 16:35:34.980  1823  3417 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-10 16:35:34.980  1823  3413 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
08-10 16:35:34.980  1823  3413 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
,08-10 16:35:34.982  1823  3413 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
,08-10 16:35:34.982  1823  3413 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
08-10 16:35:34.982  1823  3413 I Process : Sending signal. PID: 1823 SIG: 9
08-10 16:35:34.984   278   278 E lowmemorykiller: Error writing /proc/1823/oom_score_adj; errno=22
,08-10 16:35:35.005  1803  3416 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-10 16:35:35.005   874  1691 I ActivityManager: Start proc 3420:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver,
,08-10 16:35:35.013  2739  3398 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,08-10 16:35:35.018   874  1761 I ActivityManager: Start proc 3432:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,08-10 16:35:35.019  1803  3416 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,--------- beginning of crash
08-10 16:35:35.020  1803  3416 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-10 16:35:35.020  1803  3416 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 1803
08-10 16:35:35.020  1803  3416 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
,08-10 16:35:35.020  1803  3416 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-10 16:35:35.020  1803  3416 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-10 16:35:35.020  1803  3416 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-10 16:35:35.020  1803  3416 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-10 16:35:35.020  1803  3416 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-10 16:35:35.020  1803  3416 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-10 16:35:35.020  1803  3416 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-10 16:35:35.020  1803  3416 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-10 16:35:35.020  1803  3416 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-10 16:35:35.020  1803  3416 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-10 16:35:35.020  1803  3416 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-10 16:35:35.020  1803  3416 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-10 16:35:35.020  1803  3416 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-10 16:35:35.020  1803  3416 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-10 16:35:35.020  1803  3416 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 16:35:35.020  1803  3416 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 16:35:35.020  1803  3416 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 16:35:35.020  1803  3416 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 16:35:35.024  2739  3398 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
,08-10 16:35:35.024  2739  3398 E AndroidRuntime: Process: android.process.acore, PID: 2739
08-10 16:35:35.024  2739  3398 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-10 16:35:35.024  2739  3398 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-10 16:35:35.024  2739  3398 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-10 16:35:35.024  2739  3398 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-10 16:35:35.024  2739  3398 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-10 16:35:35.024  2739  3398 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-10 16:35:35.024  2739  3398 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-10 16:35:35.024  2739  3398 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-10 16:35:35.024  2739  3398 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-10 16:35:35.024  2739  3398 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-10 16:35:35.024  2739  3398 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-10 16:35:35.024  2739  3398 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-10 16:35:35.024  2739  3398 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-10 16:35:35.024  2739  3398 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 16:35:35.024  2739  3398 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 16:35:35.024  2739  3398 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 16:35:35.024  2739  3398 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-10 16:35:35.028   874  3439 E DropBoxManagerService: Can't write: system_app_crash
08-10 16:35:35.028   874  3439 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
08-10 16:35:35.028   874  3439 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 16:35:35.028   874  3439 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 16:35:35.028   874  3439 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 16:35:35.028   874  3439 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 16:35:35.028   874  3439 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 16:35:35.028   874  3439 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 16:35:35.028   874  3439 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 16:35:35.028   874  3439 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 16:35:35.028   874  3439 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 16:35:35.028   874  3439 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 16:35:35.028   874  3439 E DropBoxManagerService: 	... 5 more
,08-10 16:35:35.031  1653  3393 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-10 16:35:35.035  1653  3393 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-10 16:35:35.035  1653  3393 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-10 16:35:35.040  1653  3393 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-10 16:35:35.040  1653  3393 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-10 16:35:35.041  1653  3393 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-10 16:35:35.041  1653  3393 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user,
08-10 16:35:35.041  1653  3393 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-10 16:35:35.041  1653  3393 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-10 16:35:35.041  1653  3393 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-10 16:35:35.042  1653  3393 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-10 16:35:35.042  1653  3393 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-10 16:35:35.042  1653  3393 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-10 16:35:35.043   874  3446 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-10 16:35:35.054   874  3447 E DropBoxManagerService: Can't write: system_app_crash
08-10 16:35:35.054   874  3447 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
08-10 16:35:35.054   874  3447 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 16:35:35.054   874  3447 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 16:35:35.054   874  3447 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 16:35:35.054   874  3447 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 16:35:35.054   874  3447 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 16:35:35.054   874  3447 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 16:35:35.054   874  3447 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 16:35:35.054   874  3447 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 16:35:35.054   874  3447 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 16:35:35.054   874  3447 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 16:35:35.054   874  3447 E DropBoxManagerService: 	... 5 more
,08-10 16:35:35.057  1803  1803 I HotwordWorkerImpl: onReady
,08-10 16:35:35.073   874  1743 I ActivityManager: Process com.google.android.gms (pid 1823) has died
08-10 16:35:35.073   874  1743 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
08-10 16:35:35.073   874  1743 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
08-10 16:35:35.074   874  1743 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
08-10 16:35:35.074   874  1743 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
08-10 16:35:35.074   874  1743 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
08-10 16:35:35.074   874  1743 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 21000ms
08-10 16:35:35.074   874  1743 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 31000ms
,08-10 16:35:35.074   874  1743 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 31000ms
08-10 16:35:35.086  3420  3420 W System  : ClassLoader referenced unknown path: /system/app/KeyChain/lib/arm
08-10 16:35:35.088   874  3446 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-10 16:35:35.088   874  3446 I Adreno  : Build Date                       : 10/20/15
08-10 16:35:35.088   874  3446 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-10 16:35:35.088   874  3446 I Adreno  : Local Branch                     : M14
08-10 16:35:35.088   874  3446 I Adreno  : Remote Branch                    : 
08-10 16:35:35.088   874  3446 I Adreno  : Remote Branch                    : 
08-10 16:35:35.088   874  3446 I Adreno  : Reconstruct Branch               : 
08-10 16:35:35.094  3420  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
08-10 16:35:35.093   874  3446 I OpenGLRenderer: Initialized EGL, version 1.4
,08-10 16:35:35.112  1756  1842 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-10 16:35:35.115  1756  1842 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-10 16:35:35.115  1756  1842 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1756
08-10 16:35:35.115  1756  1842 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-10 16:35:35.115  1756  1842 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-10 16:35:35.115  1756  1842 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-10 16:35:35.115  1756  1842 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-10 16:35:35.115  1756  1842 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-10 16:35:35.115  1756  1842 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-10 16:35:35.115  1756  1842 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-10 16:35:35.115  1756  1842 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-10 16:35:35.115  1756  1842 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 16:35:35.115  1756  1842 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 16:35:35.115  1756  1842 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 16:35:35.115  1756  1842 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-10 16:35:35.119   874  3454 E DropBoxManagerService: Can't write: system_app_crash
08-10 16:35:35.119   874  3454 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop103.tmp: open failed: EROFS (Read-only file system)
08-10 16:35:35.119   874  3454 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 16:35:35.119   874  3454 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 16:35:35.119   874  3454 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 16:35:35.119   874  3454 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 16:35:35.119   874  3454 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 16:35:35.119   874  3454 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 16:35:35.119   874  3454 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 16:35:35.119   874  3454 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 16:35:35.119   874  3454 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 16:35:35.119   874  3454 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 16:35:35.119   874  3454 E DropBoxManagerService: 	... 5 more
,08-10 16:35:35.121   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-10 16:35:35.122   874   886 E PackageManager: Failed to write settings, restoring backup
08-10 16:35:35.122   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-10 16:35:35.122   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-10 16:35:35.122   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-10 16:35:35.122   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-10 16:35:35.122   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-10 16:35:35.122   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 16:35:35.122   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-10 16:35:35.122   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 16:35:35.124   874   887 E DropBoxManagerService: Can't write: system_server_wtf
08-10 16:35:35.124   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-10 16:35:35.124   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 16:35:35.124   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 16:35:35.124   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 16:35:35.124   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 16:35:35.124   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 16:35:35.124   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 16:35:35.124   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-10 16:35:35.124   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-10 16:35:35.124   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-10 16:35:35.124   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 16:35:35.124   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 16:35:35.124   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-10 16:35:35.124   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 16:35:35.124   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-10 16:35:35.124   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 16:35:35.124   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 16:35:35.124   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 16:35:35.124   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 16:35:35.124   874   887 E DropBoxManagerService: 	... 13 more
08-10 16:35:35.125   874  1743 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
,08-10 16:35:35.125   874  1743 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-10 16:35:35.131   874  1743 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-10 16:35:35.131  3420  3450 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.keychain/databases/grants.db'.
08-10 16:35:35.131  3420  3450 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 16:35:35.131  3420  3450 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 16:35:35.131  3420  3450 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 16:35:35.131  3420  3450 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 16:35:35.131  3420  3450 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 16:35:35.131  3420  3450 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 16:35:35.131  3420  3450 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 16:35:35.131  3420  3450 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 16:35:35.131  3420  3450 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 16:35:35.131  3420  3450 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 16:35:35.131  3420  3450 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 16:35:35.131  3420  3450 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 16:35:35.131  3420  3450 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 16:35:35.131  3420  3450 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-10 16:35:35.131  3420  3450 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-10 16:35:35.131  3420  3450 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-10 16:35:35.131  3420  3450 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 16:35:35.131  3420  3450 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 16:35:35.131  3420  3450 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-10 16:35:35.131  3420  3450 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 16:35:35.131  3420  3450 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-10 16:35:35.131  3420  3450 E AndroidRuntime: Process: com.android.keychain, PID: 3420
08-10 16:35:35.131  3420  3450 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 16:35:35.131  3420  3450 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 16:35:35.131  3420  3450 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 16:35:35.131  3420  3450 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 16:35:35.131  3420  3450 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 16:35:35.131  3420  3450 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 16:35:35.131  3420  3450 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 16:35:35.131  3420  3450 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 16:35:35.131  3420  3450 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.j,ava:791)
08-10 16:35:35.131  3420  3450 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 16:35:35.131  3420  3450 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 16:35:35.131  3420  3450 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 16:35:35.131  3420  3450 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 16:35:35.131  3420  3450 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-10 16:35:35.131  3420  3450 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-10 16:35:35.131  3420  3450 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-10 16:35:35.131  3420  3450 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 16:35:35.131  3420  3450 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 16:35:35.131  3420  3450 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 16:35:35.131  3420  3450 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 16:35:35.134   874  1743 I ActivityManager: Killing 1756:com.google.android.googlequicksearchbox/u0a28 (adj 0): crash
,08-10 16:35:35.184   874  1675 D GraphicsStats: Buffer count: 2
,08-10 16:35:35.185  1803  1803 E AttachedClient: AttachedClient[7541962593025, ClientConfig[mFlags=[210d800202] mSuggestFlags=[3b] mClientStats=SearchBoxStats[gel/android-search-app]]]: failed callback onGenericEvent()
08-10 16:35:35.185  1803  1803 E AttachedClient: android.os.DeadObjectException
08-10 16:35:35.185  1803  1803 E AttachedClient: 	at android.os.BinderProxy.transactNative(Native Method)
08-10 16:35:35.185  1803  1803 E AttachedClient: 	at android.os.BinderProxy.transact(Binder.java:503)
08-10 16:35:35.185  1803  1803 E AttachedClient: 	at com.google.android.apps.gsa.search.shared.service.l.c(ISearchServiceUiCallback.java:578)
08-10 16:35:35.185  1803  1803 E AttachedClient: 	at com.google.android.search.core.service.a.c(AttachedClient.java:4725)
08-10 16:35:35.185  1803  1803 E AttachedClient: 	at com.google.android.search.core.service.a.b(AttachedClient.java:185)
08-10 16:35:35.185  1803  1803 E AttachedClient: 	at com.google.android.search.core.ad.c(SearchController.java:51069)
08-10 16:35:35.185  1803  1803 E AttachedClient: 	at com.google.android.search.core.service.SearchService.bca(SearchService.java:373)
08-10 16:35:35.185  1803  1803 E AttachedClient: 	at com.google.android.search.core.service.SearchService$1.run(SearchService.java:83)
08-10 16:35:35.185  1803  1803 E AttachedClient: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 16:35:35.185  1803  1803 E AttachedClient: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 16:35:35.185  1803  1803 E AttachedClient: 	at android.os.Looper.loop(Looper.java:148)
08-10 16:35:35.185  1803  1803 E AttachedClient: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 16:35:35.185  1803  1803 E AttachedClient: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 16:35:35.185  1803  1803 E AttachedClient: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 16:35:35.185  1803  1803 E AttachedClient: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-10 16:35:35.185  1803  1803 I SearchService: Ignoring already detached client
08-10 16:35:35.190  1803  2106 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@70fa1dc
08-10 16:35:35.190  1803  3407 E AudioRecord-JNI: Error -4 during AudioRecord native read
,08-10 16:35:35.191  1803  1803 I HotwordDetector: Closing mic
,08-10 16:35:35.214   874  1743 I ActivityManager: Start proc 3459:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-10 16:35:35.226   874  1679 I ActivityManager: Start proc 3470:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
,08-10 16:35:35.228   874  1675 W ActivityManager: Spurious death for ProcessRecord{82dcb03 0:com.google.android.googlequicksearchbox/u0a28}, curProc for 1756: null
08-10 16:35:35.233   874  3475 E DropBoxManagerService: Can't write: system_app_crash
08-10 16:35:35.233   874  3475 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop108.tmp: open failed: EROFS (Read-only file system)
08-10 16:35:35.233   874  3475 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 16:35:35.233   874  3475 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 16:35:35.233   874  3475 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 16:35:35.233   874  3475 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 16:35:35.233   874  3475 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 16:35:35.233   874  3475 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 16:35:35.233   874  3475 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 16:35:35.233   874  3475 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 16:35:35.233   874  3475 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 16:35:35.233   874  3475 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 16:35:35.233   874  3475 E DropBoxManagerService: 	... 5 more
,08-10 16:35:35.244   374  3410 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,08-10 16:35:35.244   374  3410 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
,08-10 16:35:35.251   374  1275 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-10 16:35:35.265   874   874 I ActivityManager: Start proc 3485:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,08-10 16:35:35.275  1803  3406 I MicroRecognitionRnrImpl: Detection finished
,08-10 16:35:35.278  1803  2120 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 16:35:35.279  3459  3459 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 16:35:35.279  3459  3459 D AndroidRuntime: Shutting down VM
08-10 16:35:35.287  3459  3459 E AndroidRuntime: FATAL EXCEPTION: main
08-10 16:35:35.287  3459  3459 E AndroidRuntime:, Process: com.google.android.googlequicksearchbox, PID: 3459
08-10 16:35:35.287  3459  3459 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-10 16:35:35.287  3459  3459 E AndroidRuntime: 	... 10 more
08-10 16:35:35.293   874  1769 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-10 16:35:35.295   874  3497 E DropBoxManagerService: Can't write: system_app_crash
08-10 16:35:35.295   874  3497 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
08-10 16:35:35.295   874  3497 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 16:35:35.295   874  3497 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 16:35:35.295   874  3497 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 16:35:35.295   874  3497 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 16:35:35.295   874  3497 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 16:35:35.295   874  3497 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 16:35:35.295   874  3497 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 16:35:35.295   874  3497 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 16:35:35.295   874  3497 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 16:35:35.295   874  3497 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 16:35:35.295   874  3497 E DropBoxManagerService: 	... 5 more
08-10 16:35:35.307  1803  1803 W ErrorReporter: reportError [type: 29, code: 917507]: null
,08-10 16:35:35.340   280   280 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
08-10 16:35:35.340   280   280 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
08-10 16:35:35.340   280   280 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
08-10 16:35:35.340   280   280 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
08-10 16:35:35.340   280   280 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-10 16:35:35.340   280   280 E qdoverlay: MdpCtrl close error in unset
08-10 16:35:35.341  3470  3470 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
08-10 16:35:35.361  3470  3470 I MultiDex: VM with version 2.1.0 has multidex support
08-10 16:35:35.361  3470  3470 I MultiDex: install
08-10 16:35:35.361  3470  3470 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-10 16:35:35.586   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
