#### Test 83268893751f823_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,09-01 18:48:55.664   874   883 I art     : Background partial concurrent mark sweep GC freed 33397(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/43MB, paused 1.253ms total 125.739ms
09-01 18:48:55.731  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-01 18:48:55.744  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-01 18:48:55.746  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-01 18:48:55.766  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-01 18:48:55.766  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-01 18:48:55.766  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 18:48:55.767  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-01 18:48:55.779  2727  2727 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-01 18:48:55.779  2727  2727 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-01 18:48:55.780  2727  2727 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
09-01 18:48:56.253  3454  3454 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-01 18:48:56.257  3454  3454 D AndroidRuntime: CheckJNI is OFF
09-01 18:48:56.293  3454  3454 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-01 18:48:56.373  3454  3454 I Radio-JNI: register_android_hardware_Radio DONE
09-01 18:48:56.401  3454  3454 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-01 18:48:56.407   874  1996 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-01 18:48:56.446  3454  3454 D AndroidRuntime: Shutting down VM
09-01 18:48:56.448  2029  2053 W SearchService: Abort, client detached.
09-01 18:48:56.474  2029  2029 I HotwordDetector: Closing mic
09-01 18:48:56.475  2029  2334 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@1552c93
09-01 18:48:56.475  2029  2343 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-01 18:48:56.503   874  2061 I ActivityManager: Start proc 3464:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-01 18:48:56.525  2029  2029 W ErrorReporter: reportError [type: 29, code: 917507]: null
09-01 18:48:56.539   377  2345 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-01 18:48:56.540   377  2345 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-01 18:48:56.546   377  1283 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-01 18:48:56.548  2029  2338 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-01 18:48:56.549  2029  2342 I MicroRecognitionRnrImpl: Detection finished
09-01 18:48:56.603  3464  3464 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-01 18:48:56.643  3464  3464 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-01 18:48:56.654  3464  3464 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9772-9776)
09-01 18:48:56.654  3464  3464 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-01 18:48:56.675  3464  3464 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {78e7501}
,09-01 18:48:56.676  3464  3464 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-01 18:48:56.676  3464  3464 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-01 18:48:56.685  3464  3464 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-01 18:48:56.687  3464  3464 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-01 18:48:56.713  3464  3479 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,09-01 18:48:56.732  3464  3464 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-01 18:48:56.743  3464  3464 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-01 18:48:56.743  3464  3464 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-01 18:48:56.743  3464  3464 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-01 18:48:56.743  3464  3464 I Adreno  : Build Date                       : 10/20/15
09-01 18:48:56.743  3464  3464 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
,09-01 18:48:56.743  3464  3464 I Adreno  : Local Branch                     : M14
09-01 18:48:56.743  3464  3464 I Adreno  : Remote Branch                    : 
09-01 18:48:56.743  3464  3464 I Adreno  : Remote Branch                    : 
09-01 18:48:56.743  3464  3464 I Adreno  : Reconstruct Branch               : 
,09-01 18:48:56.825   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@85d8dd8:true
,09-01 18:48:56.876  3464  3464 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-01 18:48:56.893  3464  3464 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-01 18:48:56.990  3464  3502 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-01 18:48:57.002  3464  3488 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-01 18:48:57.037  3464  3502 I OpenGLRenderer: Initialized EGL, version 1.4
,09-01 18:48:57.095   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +610ms
,09-01 18:48:57.098  1877  1877 I Keyboard.Facilitator: onFinishInput()
,09-01 18:48:57.181  3464  3464 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3464
,09-01 18:48:57.378  3464  3464 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode,
,09-01 18:48:57.462   874   885 I ActivityManager: Killing 2510:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,09-01 18:48:57.494   874   885 I ActivityManager: Killing 3153:com.qualcomm.telephony/1001 (adj 15): empty #18
,09-01 18:48:57.621  3464  3504 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1682245328
,09-01 18:48:57.631  3464  3504 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-01 18:48:57.631  3464  3504 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-01 18:48:57.631  3464  3504 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-01 18:48:57.631  3464  3504 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-01 18:48:57.631  3464  3504 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-01 18:48:57.631  3464  3504 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@deac3ec added. We now have 1 listener(s)
,09-01 18:48:57.637  3464  3504 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-01 18:48:57.639  3464  3504 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
,09-01 18:48:57.648  3464  3504 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-01 18:48:57.649  3464  3504 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-01 18:48:57.661  3464  3504 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-01 18:48:57.661  3464  3504 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-01 18:48:57.661  3464  3504 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-01 18:48:57.661  3464  3504 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-01 18:48:57.661  3464  3504 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-01 18:48:57.661  3464  3504 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-01 18:48:57.661  3464  3504 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-01 18:48:57.661  3464  3504 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-01 18:48:57.661  3464  3504 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-01 18:48:57.661  3464  3504 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-01 18:48:57.661  3464  3504 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-01 18:48:57.661  3464  3504 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-01 18:48:57.661  3464  3504 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-01 18:48:57.661  3464  3504 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-01 18:48:57.662  3464  3504 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1dfdbb added. We now have 1 listener(s)
09-01 18:48:57.663  3464  3504 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 18:48:57.668   874  1312 D WifiService: New client listening to asynchronous messages
,09-01 18:48:57.672  3464  3504 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 18:48:57.672  3464  3504 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-01 18:48:57.673  3464  3504 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-01 18:48:57.674  3464  3504 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-01 18:48:57.674  3464  3504 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-01 18:48:57.676  3464  3504 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 18:48:57.676  3464  3504 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-01 18:48:57.679  3464  3504 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:48:57.679  3464  3504 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 18:48:57.679  3464  3504 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 18:48:57.679  3464  3504 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-01 18:48:57.679  3464  3504 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 18:48:57.679  3464  3504 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 18:48:57.679  3464  3504 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 18:48:57.679  3464  3504 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 18:48:57.679  3464  3504 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 18:48:57.679  3464  3504 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-01 18:48:57.679  3464  3504 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 18:48:57.680  3464  3504 I io.jxcore.node.LifeCycleMonitor: start: OK
09-01 18:48:57.680  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 18:48:57.838  3464  3464 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-01 18:48:58.226  3464  3473 I art     : Background sticky concurrent mark sweep GC freed 68367(6MB) AllocSpace objects, 17(1584KB) LOS objects, 29% free, 23MB/32MB, paused 1.152ms total 116.266ms
,09-01 18:48:58.872  3464  3512 W jxcore-log: Initializing JXcore engine
,09-01 18:48:58.872  3464  3512 W jxcore-log: JXcore engine is ready
,09-01 18:48:58.912  3512  3512 W Thread-282: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-01 18:48:58.912  3512  3512 W Thread-282: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9690]" dev="sockfs" ino=9690 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-01 18:48:58.912  3512  3512 W Thread-282: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-01 18:48:58.912  3512  3512 W Thread-282: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24787]" dev="sockfs" ino=24787 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-01 18:48:58.924  3464  3512 W jxcore-log: Starting JXcore engine
,09-01 18:48:59.003  3464  3512 W jxcore-log: Platform android
09-01 18:48:59.003  3464  3512 W jxcore-log: 
,09-01 18:48:59.003  3464  3512 W jxcore-log: Process ARCH arm
09-01 18:48:59.003  3464  3512 W jxcore-log: 
,09-01 18:48:59.197  3464  3512 I jxcore-log: JXcore Cordova bridge is ready!
09-01 18:48:59.197  3464  3512 I jxcore-log: 
,09-01 18:48:59.197  3464  3512 W jxcore-log: JXcore engine is started
,09-01 18:48:59.208  3464  3504 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-01 18:48:59.213  3464  3464 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-01 18:49:08.724  3464  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-01 18:49:08.724  3464  3512 I jxcore-log: 
,09-01 18:49:08.726  3464  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-01 18:49:08.726  3464  3512 I jxcore-log: 
,09-01 18:49:08.727  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:49:08.728  3464  3512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 18:49:08.728  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 18:49:08.728  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-01 18:49:08.728  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 18:49:08.728  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 18:49:08.728  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 18:49:08.728  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 18:49:08.728  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 18:49:08.728  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 18:49:08.728  3464  3512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 18:49:08.730  3464  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-01 18:49:08.730  3464  3512 I jxcore-log: 
,09-01 18:49:08.732  3464  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-01 18:49:08.732  3464  3512 I jxcore-log: 
,09-01 18:49:09.219  3464  3512 D executeNativeTests: Running unit tests
,09-01 18:49:09.277  3464  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 18:49:09.277  3464  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1607af added. We now have 2 listener(s)
,09-01 18:49:09.279  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 18:49:09.279  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 18:49:09.279  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 18:49:09.279  3464  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 18:49:09.279  3464  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc added. We now have 2 listener(s)
09-01 18:49:09.279  3464  3512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 18:49:09.279  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 18:49:09.281  3464  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 18:49:09.282  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:49:09.282  3464  3512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 18:49:09.282  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 18:49:09.282  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-01 18:49:09.282  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 18:49:09.282  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 18:49:09.282  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 18:49:09.282  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 18:49:09.282  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 18:49:09.282  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:49:09.282  3464  3512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 18:49:09.282  3464  3512 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 18:49:09.284  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 18:49:09.284  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-01 18:49:09.286  3464  3512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 18:49:09.286  3464  3512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-01 18:49:09.287  3464  3512 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-01 18:49:09.288  3464  3512 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-01 18:49:09.288  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-01 18:49:09.288  3464  3512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 18:49:09.288  3464  3512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 18:49:09.288  3464  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 18:49:09.288  3464  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 18:49:09.289  3464  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 18:49:09.289  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 18:49:09.289  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.289  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 18:49:09.289  3464  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 18:49:09.289  3464  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1607af removed from the list
09-01 18:49:09.289  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 18:49:09.289  3464  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc removed from the list
09-01 18:49:09.289  3464  3512 D io.jxcore.node.ConnectivityMonitor: stop
09-01 18:49:09.289  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.291  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.291  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.291  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 18:49:09.291  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 18:49:09.291  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.291  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.293  3464  3512 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-01 18:49:09.293  3464  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 18:49:09.293  3464  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 18:49:09.293  3464  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 18:49:09.293  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 18:49:09.294  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.294  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.294  3464  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1607af not in the list
09-01 18:49:09.294  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.294  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.294  3464  3512 D io.jxcore.node.ConnectivityMonitor: stop
09-01 18:49:09.294  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.294  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.294  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.294  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.294  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 18:49:09.294  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 18:49:09.294  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.294  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
,09-01 18:49:09.300  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
,09-01 18:49:09.300  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-01 18:49:09.301  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-01 18:49:09.301  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-01 18:49:09.301  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-01 18:49:09.301  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-01 18:49:09.301  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-01 18:49:09.301  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-01 18:49:09.301  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-01 18:49:09.301  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-01 18:49:09.301  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-01 18:49:09.301  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-01 18:49:09.301  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-01 18:49:09.301  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-01 18:49:09.301  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-01 18:49:09.301  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-01 18:49:09.301  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-01 18:49:09.301  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-01 18:49:09.301  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-01 18:49:09.301  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-01 18:49:09.301  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-01 18:49:09.301  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-01 18:49:09.302  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-01 18:49:09.302  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-01 18:49:09.302  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-01 18:49:09.302  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-01 18:49:09.302  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-01 18:49:09.302  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-01 18:49:09.302  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-01 18:49:09.302  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-01 18:49:09.302  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-01 18:49:09.302  3464  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 18:49:09.302  3464  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 18:49:09.302  3464  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 18:49:09.302  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 18:49:09.302  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.302  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.302  3464  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1607af not in the list
09-01 18:49:09.302  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.303  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
,09-01 18:49:09.303  3464  3512 D io.jxcore.node.ConnectivityMonitor: stop
09-01 18:49:09.303  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.303  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.303  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.303  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.303  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 18:49:09.303  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 18:49:09.303  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.303  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.304  3464  3512 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-01 18:49:09.305  3464  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 18:49:09.305  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:49:09.306  3464  3512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 18:49:09.306  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 18:49:09.306  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-01 18:49:09.306  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 18:49:09.306  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 18:49:09.306  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 18:49:09.306  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 18:49:09.306  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 18:49:09.306  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:49:09.306  3464  3512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 18:49:09.306  3464  3512 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 18:49:09.306  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 18:49:09.307  3464  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 18:49:09.307  3464  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 18:49:09.307  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 18:49:09.307  3464  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 18:49:09.307  3464  3512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-01 18:49:09.309  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
09-01 18:49:09.310  3464  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-01 18:49:09.310  3464  3464 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-01 18:49:09.311  3464  3512 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-01 18:49:09.311  3464  3512 I io.jxcore.node.ConnectionHelper: start: OK
09-01 18:49:09.312  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:49:09.312  3464  3512 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
09-01 18:49:09.313  3464  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 18:49:09.313  3464  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 18:49:09.313  3464  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-01 18:49:09.313  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.313  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-01 18:49:09.313  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 18:49:09.313  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 18:49:09.314  3464  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 18:49:09.314  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 18:49:09.314  3464  3512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 18:49:09.315  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 18:49:09.315  3464  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 18:49:09.316  3464  3464 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 18:49:09.316  3464  3464 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 18:49:09.316  3464  3464 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 18:49:09.316  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 18:49:09.316  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.316  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 18:49:09.316  3464  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1607af not in the list
09-01 18:49:09.316  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.316  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
,09-01 18:49:09.316  3464  3512 D io.jxcore.node.ConnectivityMonitor: stop
09-01 18:49:09.316  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.317  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.317  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.317  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 18:49:09.317  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 18:49:09.317  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.317  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.318  3464  3512 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-01 18:49:09.319  3464  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 18:49:09.319  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 18:49:09.320  3464  3512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 18:49:09.320  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 18:49:09.320  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-01 18:49:09.320  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 18:49:09.320  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 18:49:09.320  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 18:49:09.320  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 18:49:09.320  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 18:49:09.320  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:49:09.320  3464  3512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 18:49:09.320  3464  3512 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 18:49:09.320  3464  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 18:49:09.320  3464  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 18:49:09.320  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 18:49:09.320  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-01 18:49:09.320  3464  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 18:49:09.321  3464  3512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 18:49:09.322  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
09-01 18:49:09.322  3464  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-01 18:49:09.322  3464  3464 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-01 18:49:09.322  3464  3512 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-01 18:49:09.322  3464  3512 I io.jxcore.node.ConnectionHelper: start: OK
09-01 18:49:09.323  3464  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 18:49:09.323  3464  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-01 18:49:09.323  3464  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-01 18:49:09.323  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.323  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 18:49:09.323  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 18:49:09.323  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-01 18:49:09.323  3464  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 18:49:09.323  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 18:49:09.323  3464  3512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 18:49:09.323  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 18:49:09.324  3464  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 18:49:09.324  3464  3464 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 18:49:09.324  3464  3464 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 18:49:09.324  3464  3464 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 18:49:09.325  3464  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 18:49:09.325  3464  3512 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-01 18:49:09.325  3464  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 18:49:09.325  3464  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 18:49:09.325  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 18:49:09.325  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.325  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 18:49:09.325  3464  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1607af not in the list
09-01 18:49:09.325  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.325  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.325  3464  3512 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 18:49:09.325  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.326  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 18:49:09.326  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.327  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 18:49:09.327  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 18:49:09.327  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.327  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.328  3464  3512 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-01 18:49:09.328  3464  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 18:49:09.328  3464  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 18:49:09.328  3464  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 18:49:09.328  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 18:49:09.328  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.328  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.328  3464  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1607af not in the list
09-01 18:49:09.329  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.329  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.329  3464  3512 D io.jxcore.node.ConnectivityMonitor: stop
09-01 18:49:09.329  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.329  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 18:49:09.329  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.329  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.329  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 18:49:09.329  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 18:49:09.329  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.329  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.330  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-01 18:49:09.330  3464  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 18:49:09.330  3464  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 18:49:09.330  3464  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 18:49:09.330  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 18:49:09.330  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.330  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.330  3464  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1607af not in the list
09-01 18:49:09.330  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.330  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.330  3464  3512 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 18:49:09.330  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.330  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.330  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.331  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.331  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 18:49:09.331  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 18:49:09.331  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 18:49:09.331  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.331  3464  3512 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-01 18:49:09.331  3464  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 18:49:09.331  3464  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 18:49:09.331  3464  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 18:49:09.332  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 18:49:09.332  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.332  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.332  3464  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1607af not in the list
09-01 18:49:09.332  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.332  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.332  3464  3512 D io.jxcore.node.ConnectivityMonitor: stop
09-01 18:49:09.332  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.332  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.332  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.332  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.332  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 18:49:09.332  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 18:49:09.332  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.332  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.333  3464  3512 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-01 18:49:09.333  3464  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 18:49:09.333  3464  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-01 18:49:09.333  3464  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 18:49:09.333  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 18:49:09.333  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 18:49:09.333  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 18:49:09.333  3464  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1607af not in the list
09-01 18:49:09.333  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 18:49:09.333  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.334  3464  3512 D io.jxcore.node.ConnectivityMonitor: stop
09-01 18:49:09.334  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 18:49:09.334  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.334  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.334  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,09-01 18:49:09.334  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 18:49:09.334  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 18:49:09.334  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.334  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.334  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-01 18:49:09.335  3464  3512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 18:49:09.335  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 18:49:09.335  3464  3512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-01 18:49:09.335  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-01 18:49:09.335  3464  3512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 18:49:09.335  3464  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 18:49:09.335  3464  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 18:49:09.335  3464  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 18:49:09.335  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 18:49:09.335  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.335  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.335  3464  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1607af not in the list
09-01 18:49:09.335  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.335  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
,09-01 18:49:09.335  3464  3512 D io.jxcore.node.ConnectivityMonitor: stop
09-01 18:49:09.335  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.335  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.336  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 18:49:09.336  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.336  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 18:49:09.336  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 18:49:09.336  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.336  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.337  3464  3512 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-01 18:49:09.337  3464  3512 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-01 18:49:09.337  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-01 18:49:09.339  3464  3512 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 18:49:09.339  3464  3512 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-01 18:49:09.339  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-01 18:49:09.340  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-01 18:49:09.340  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-01 18:49:09.340  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-01 18:49:09.340  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-01 18:49:09.340  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-01 18:49:09.340  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-01 18:49:09.340  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-01 18:49:09.340  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-01 18:49:09.340  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-01 18:49:09.340  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-01 18:49:09.340  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-01 18:49:09.340  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-01 18:49:09.340  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-01 18:49:09.340  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-01 18:49:09.340  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-01 18:49:09.340  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-01 18:49:09.340  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-01 18:49:09.340  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-01 18:49:09.340  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-01 18:49:09.340  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-01 18:49:09.341  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-01 18:49:09.341  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-01 18:49:09.341  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-01 18:49:09.341  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-01 18:49:09.341  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-01 18:49:09.341  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-01 18:49:09.341  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-01 18:49:09.341  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-01 18:49:09.341  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-01 18:49:09.341  3464  3512 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-01 18:49:09.341  3464  3512 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 18:49:09.341  3464  3512 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-01 18:49:09.341  3464  3512 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 18:49:09.341  3464  3512 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 18:49:09.341  3464  3512 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-01 18:49:09.342  3464  3512 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 18:49:09.342  3464  3512 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 18:49:09.342  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-01 18:49:09.343  3464  3512 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
09-01 18:49:09.343  3464  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-01 18:49:09.343  3464  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-01 18:49:09.343  3464  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-01 18:49:09.344  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-01 18:49:09.344  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-01 18:49:09.344  3464  3512 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-01 18:49:09.344  3464  3512 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 18:49:09.344  3464  3512 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-01 18:49:09.345  3464  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 18:49:09.345  3464  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 18:49:09.345  3464  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 18:49:09.345  3464  3519 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 346)
09-01 18:49:09.345  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 18:49:09.345  3464  3519 E BluetoothDevice: Bluetooth is not enabled
09-01 18:49:09.345  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.345  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.345  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-01 18:49:09.345  3464  3519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): null (thread ID: 346)
09-01 18:49:09.345  3464  3519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 346)
09-01 18:49:09.346  3464  3519 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): null (thread ID: 346)
09-01 18:49:09.346  3464  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1607af not in the list
09-01 18:49:09.346  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.346  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.346  3464  3464 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> 00:11:22:33:44:55]: Failed to connect (tried 1 time(s)): null
09-01 18:49:09.346  3464  3519 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Failed to find a thread with ID 346
09-01 18:49:09.346  3464  3519 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 346)
09-01 18:49:09.347  3464  3464 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: Failed to connect (tried 1 time(s)): null
09-01 18:49:09.347  3464  3464 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 18:49:09.347  3464  3464 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 18:49:09.346  3464  3512 D io.jxcore.node.ConnectivityMonitor: stop
09-01 18:49:09.347  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.347  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.347  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.347  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.347  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 18:49:09.347  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 18:49:09.348  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.348  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.348  3464  3520 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 346
09-01 18:49:09.348  3464  3512 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-01 18:49:09.349  3464  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 18:49:09.349  3464  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 18:49:09.349  3464  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 18:49:09.349  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 18:49:09.349  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.349  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.349  3464  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1607af not in the list
09-01 18:49:09.350  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.350  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.350  3464  3512 D io.jxcore.node.ConnectivityMonitor: stop
09-01 18:49:09.350  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.350  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.350  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.350  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.351  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 18:49:09.351  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 18:49:09.351  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.351  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.351  3464  3512 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-01 18:49:09.352  3464  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 18:49:09.352  3464  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 18:49:09.352  3464  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 18:49:09.352  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 18:49:09.352  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.352  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.352  3464  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1607af not in the list
09-01 18:49:09.352  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.352  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.352  3464  3512 D io.jxcore.node.ConnectivityMonitor: stop
09-01 18:49:09.352  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.352  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.352  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.352  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.353  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 18:49:09.353  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 18:49:09.353  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.353  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.353  3464  3512 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-01 18:49:09.353  3464  3512 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-01 18:49:09.353  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 18:49:09.353  3464  3512 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-01 18:49:09.353  3464  3512 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-01 18:49:09.353  3464  3512 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-01 18:49:09.354  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 18:49:09.354  3464  3512 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-01 18:49:09.354  3464  3512 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-01 18:49:09.354  3464  3512 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-01 18:49:09.354  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 18:49:09.354  3464  3512 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-01 18:49:09.354  3464  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 18:49:09.354  3464  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 18:49:09.354  3464  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 18:49:09.354  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 18:49:09.354  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.354  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 18:49:09.354  3464  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1607af not in the list
09-01 18:49:09.354  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.354  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.354  3464  3512 D io.jxcore.node.ConnectivityMonitor: stop
09-01 18:49:09.355  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.355  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.355  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.355  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.355  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 18:49:09.355  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 18:49:09.355  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.355  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.355  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 18:49:09.355  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.356  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.356  3464  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1607af not in the list
09-01 18:49:09.356  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.356  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.356  3464  3512 D io.jxcore.node.ConnectivityMonitor: stop
09-01 18:49:09.356  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.356  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.356  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.356  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.356  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 18:49:09.356  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.356  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.356  3464  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1607af not in the list
09-01 18:49:09.356  3464  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 18:49:09.356  3464  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 18:49:09.356  3464  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 18:49:09.356  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 18:49:09.357  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.357  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.357  3464  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1607af not in the list
09-01 18:49:09.357  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.357  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.357  3464  3512 D io.jxcore.node.ConnectivityMonitor: stop
09-01 18:49:09.357  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.357  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.357  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.357  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.357  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 18:49:09.357  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 18:49:09.357  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.357  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.358  3464  3512 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-01 18:49:09.358  3464  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 18:49:09.358  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
09-01 18:49:09.359  3464  3512 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
09-01 18:49:09.359  3464  3464 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
09-01 18:49:09.359  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 18:49:09.359  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 18:49:09.359  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-01 18:49:09.359  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.359  3464  3512 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
09-01 18:49:09.359  3464  3464 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-01 18:49:09.360  3464  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1607af not in the list
09-01 18:49:09.360  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.360  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 18:49:09.360  3464  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 18:49:09.360  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 18:49:09.360  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.360  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.360  3464  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 18:49:09.360  3464  3464 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 18:49:09.360  3464  3464 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 18:49:09.361  3464  3464 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 18:49:09.361  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.361  3464  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 18:49:09.361  3464  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 18:49:09.361  3464  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 18:49:09.361  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 18:49:09.361  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.361  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.361  3464  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1607af not in the list
09-01 18:49:09.361  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.361  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.361  3464  3512 D io.jxcore.node.ConnectivityMonitor: stop
09-01 18:49:09.361  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.361  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.361  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.361  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.362  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 18:49:09.362  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManag,er: stopDiscovery
09-01 18:49:09.362  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.362  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.362  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-01 18:49:09.362  3464  3512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 18:49:09.362  3464  3512 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-01 18:49:09.363  3464  3512 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-01 18:49:09.363  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 18:49:09.363  3464  3512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 18:49:09.363  3464  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 18:49:09.363  3464  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 18:49:09.363  3464  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 18:49:09.363  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 18:49:09.363  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 18:49:09.363  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.363  3464  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1607af not in the list
09-01 18:49:09.363  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.363  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.363  3464  3512 D io.jxcore.node.ConnectivityMonitor: stop
09-01 18:49:09.363  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.363  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.363  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.363  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.364  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 18:49:09.364  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 18:49:09.364  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.364  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.365  3464  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 18:49:09.365  3464  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 18:49:09.365  3464  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 18:49:09.365  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 18:49:09.365  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.365  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.365  3464  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1607af not in the list
09-01 18:49:09.365  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.365  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.365  3464  3512 D io.jxcore.node.ConnectivityMonitor: stop
09-01 18:49:09.366  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.366  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.366  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.366  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.366  3464  3512 I org.thaliproject.p2p.btconnectorlib.Dis,coveryManager: stopAdvertising
09-01 18:49:09.366  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 18:49:09.366  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.366  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.366  3464  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 18:49:09.366  3464  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 18:49:09.367  3464  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 18:49:09.367  3464  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 18:49:09.367  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.367  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.367  3464  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1607af not in the list
09-01 18:49:09.367  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.367  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.367  3464  3512 D io.jxcore.node.ConnectivityMonitor: stop
09-01 18:49:09.367  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.367  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.367  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 18:49:09.367  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 18:49:09.368  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 18:49:09.368  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 18:49:09.368  3464  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 18:49:09.368  3464  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912c7bc not in the list
09-01 18:49:09.368  3464  3512 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-01 18:49:09.368  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 18:49:09.368  3464  3512 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-01 18:49:09.369  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 18:49:09.369  3464  3512 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-01 18:49:09.369  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 18:49:09.370  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incom,ing]
09-01 18:49:09.370  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-01 18:49:09.370  3464  3512 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-01 18:49:09.371  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-01 18:49:09.371  3464  3512 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-01 18:49:09.371  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-01 18:49:09.371  3464  3512 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-01 18:49:09.371  3464  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-01 18:49:09.371  3464  3512 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-01 18:49:09.371  3464  3512 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-01 18:49:09.371  3464  3512 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-01 18:49:09.372  3464  3512 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-01 18:49:09.372  3464  3512 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-01 18:49:09.372  3464  3512 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-01 18:49:09.372  3464  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 18:49:09.372  3464  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d44666 added. We now have 2 listener(s)
09-01 18:49:09.372  3464  3512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 18:49:09.373   874  1988 D WifiService: setWifiEnabled: true pid=3464, uid=10000
09-01 18:49:09.373   874  1988 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-01 18:49:09.375  3464  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 18:49:09.375  3464  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b93da7 added. We now have 3 listener(s)
09-01 18:49:09.376  3464  3512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 18:49:09.376  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:49:09.376  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:49:09.377  3464  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 18:49:09.377  3464  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5d25254 added. We now have 4 listener(s)
09-01 18:49:09.378  3464  3512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 18:49:09.379  3464  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 18:49:09.379  3464  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9ad5fd added. We now have 5 listener(s)
09-01 18:49:09.379  3464  3512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 18:49:09.379   874  2061 D WifiService: setWifiEnabled: false pid=3464, uid=10000
09-01 18:49:09.379   874  2061 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-01 18:49:09.386   874   891 I ActivityManager: Start proc 3523:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
09-01 18:49:09.387   874  1311 D WifiConfigStore: Loading config and enabling all networks 
09-01 18:49:09.389  3464  3464 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:49:09.390  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 18:49:09.390  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 18:49:09.390  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-01 18:49:09.390  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 18:49:09.390  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 18:49:09.390  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 18:49:09.390  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 18:49:09.390  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 18:49:09.390  3464  3464 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:49:09.390  3464  3464 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 18:49:09.399   874  1311 D WifiConfigStore: loaded 0 passpoint configs
09-01 18:49:09.400   874  1311 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-01 18:49:09.401   874  1311 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-01 18:49:09.402   874  1311 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-01 18:49:09.402   874  1311 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-01 18:49:09.402   874  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-01 18:49:09.402   874  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-01 18:49:09.409   874   887 I ActivityManager: Start proc 3534:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
09-01 18:49:09.410  3464  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 18:49:09.415  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:49:09.416  3464  3512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 18:49:09.416  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 18:49:09.416  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-01 18:49:09.416  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 18:49:09.416  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 18:49:09.416  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 18:49:09.416  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 18:49:09.416  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 18:49:09.416  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:49:09.416  3464  3512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 18:49:09.416  3464  3512 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 18:49:09.416  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 18:49:09.459   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-01 18:49:09.459   373   872 D CommandListener: Setting iface cfg
09-01 18:49:09.460   874  1310 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '109 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 109 Failed to set address (No such device)'
09-01 18:49:09.460   874  1310 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-01 18:49:09.462   874  1310 D WifiNative-HAL: p2pGetDeviceAddress
09-01 18:49:09.462   874  1310 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
09-01 18:49:09.462  3534  3534 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
09-01 18:49:09.478   874  1311 D WifiConfigStore: Retrieve network priorities after PNO.
09-01 18:49:09.480  3464  3464 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:49:09.480  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 18:49:09.480  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 18:49:09.480  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-01 18:49:09.480  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 18:49:09.480  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 18:49:09.480  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 18:49:09.480  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 18:49:09.480  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 18:49:09.480  3464  3464 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:49:09.480  3464  3464 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 18:49:09.481  3464  3464 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:49:09.481  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 18:49:09.481  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 18:49:09.481  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-01 18:49:09.481  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 18:49:09.481  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 18:49:09.481  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 18:49:09.481  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 18:49:09.481  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 18:49:09.481  3464  3464 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:49:09.481  3464  3464 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 18:49:09.483  2076  2313 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 18:49:09.484  3523  3523 D AdapterServiceConfig: Adding HeadsetService
09-01 18:49:09.485  3523  3523 D AdapterServiceConfig: Adding A2dpService
09-01 18:49:09.485  3523  3523 D AdapterServiceConfig: Adding HidService
09-01 18:49:09.485  3523  3523 D AdapterServiceConfig: Adding HealthService
09-01 18:49:09.485  3523  3523 D AdapterServiceConfig: Adding PanService
09-01 18:49:09.485  3523  3523 D AdapterServiceConfig: Adding GattService
09-01 18:49:09.485  3523  3523 D AdapterServiceConfig: Adding BluetoothMapService
,09-01 18:49:09.505  3534  3534 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
09-01 18:49:09.516   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@de315fe:true
09-01 18:49:09.516  3523  3523 D BluetoothAdapterState: make() - Creating AdapterState
09-01 18:49:09.519  3523  3523 I bt_bluedroid: init
09-01 18:49:09.519  3523  3560 I BluetoothAdapterState: Entering OffState
09-01 18:49:09.523  3523  3561 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-01 18:49:09.524  3523  3561 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-01 18:49:09.524  3523  3561 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-01 18:49:09.524  3523  3561 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-01 18:49:09.525   874  1988 I ActivityManager: Killing 2817:com.google.android.calendar/u0a37 (adj 15): empty #17
09-01 18:49:09.525  3523  3523 I bt_bluedroid: get_profile_interface socket
09-01 18:49:09.527  3523  3565 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-01 18:49:09.528  3523  3523 I bt_bluedroid: get_profile_interface sdp
,09-01 18:49:09.551  3523  3565 D BluetoothAdapterProperties: Name is: Nexus 6
,09-01 18:49:09.554  3523  3535 I bt_bluedroid: config_hci_snoop_log
,09-01 18:49:09.555   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,09-01 18:49:09.557  3523  3560 D BluetoothAdapterState: Current state: OFF, message: 0
,09-01 18:49:09.557  3523  3560 D BluetoothAdapterProperties: Setting state to 14
09-01 18:49:09.557  3523  3560 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-01 18:49:09.558  3523  3560 D BluetoothBondStateMachine: make
,09-01 18:49:09.559  3523  3566 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-01 18:49:09.561  3523  3560 I BluetoothAdapterState: Entering PendingCommandState
09-01 18:49:09.562  3523  3523 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
09-01 18:49:09.564  3523  3523 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e4183
,09-01 18:49:09.564  3523  3523 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-01 18:49:09.564  3523  3523 D BtGatt.GattService: Received start request. Starting profile...
09-01 18:49:09.564  3523  3523 D BtGatt.GattService: start()
09-01 18:49:09.564  3523  3523 I bt_bluedroid: get_profile_interface gatt
09-01 18:49:09.565  3523  3523 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e4183
09-01 18:49:09.565  3523  3523 D BtGatt.AdvertiseManager: advertise manager created
,09-01 18:49:09.570  3523  3523 V BluetoothAdapterState: isTurningOff()=false
09-01 18:49:09.570  3523  3523 V BluetoothAdapterState: isTurningOn()=false
,09-01 18:49:09.570  3523  3523 V BluetoothAdapterState: isBleTurningOn()=true
09-01 18:49:09.570  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
09-01 18:49:09.570  3523  3560 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-01 18:49:09.570  3523  3560 I bt_bluedroid: enable
09-01 18:49:09.570  3523  3561 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-01 18:49:09.571  3523  3561 I bt_hci  : start_up
,09-01 18:49:09.585  3523  3561 I bt_vendor: alloc value 0xb3a89189
,09-01 18:49:09.585  3523  3561 I bt_vendor: init
09-01 18:49:09.585  3523  3561 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-01 18:49:09.586  3523  3561 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-01 18:49:09.692  3523  3561 D bt_hci  : start_up starting async portion
,09-01 18:49:09.692  3523  3569 I bt_hci  : event_finish_startup
09-01 18:49:09.693  3523  3569 I bt_hci_h4: hal_open
09-01 18:49:09.693  3523  3569 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-01 18:49:09.700  3523  3569 I bt_userial_vendor: device fd = 51 open
,09-01 18:49:09.734  3523  3569 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-01 18:49:09.766  3523  3569 D bt_hwcfg: Chipset BCM4354A2
,09-01 18:49:09.766  3523  3569 D bt_hwcfg: Target name = [BCM4354A2]
09-01 18:49:09.768  3523  3569 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-01 18:49:09.861  3464  3464 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 18:49:10.446  3523  3569 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-01 18:49:10.447  3523  3569 D bt_hwcfg: Settlement delay -- 100 ms
,09-01 18:49:10.448  3523  3569 I bt_hwcfg: Setting fw settlement delay to 100 
,09-01 18:49:10.565  3523  3569 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-01 18:49:10.567  3523  3569 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-01 18:49:10.595  3523  3569 I bt_hwcfg: vendor lib fwcfg completed
,09-01 18:49:10.595  3523  3569 I bt_vendor: firmware callback
09-01 18:49:10.595  3523  3569 I bt_hci  : firmware_config_callback
,09-01 18:49:10.607  3523  3571 I bt_btu  : btu_task pending for preload complete event
,09-01 18:49:10.607  3523  3571 I bt_btu_task: Bluetooth chip preload is complete
09-01 18:49:10.608  3523  3571 I bt_btu  : btu_task received preload complete event
,09-01 18:49:10.618  3523  3571 I         : BTE_InitTraceLevels -- TRC_HCI
09-01 18:49:10.618  3523  3571 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-01 18:49:10.619  3523  3571 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-01 18:49:10.619  3523  3571 I         : BTE_InitTraceLevels -- TRC_AVDT
09-01 18:49:10.619  3523  3571 I         : BTE_InitTraceLevels -- TRC_AVRC
09-01 18:49:10.620  3523  3571 I         : BTE_InitTraceLevels -- TRC_A2D
09-01 18:49:10.620  3523  3571 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-01 18:49:10.620  3523  3571 I         : BTE_InitTraceLevels -- TRC_BTM
09-01 18:49:10.621  3523  3571 I         : BTE_InitTraceLevels -- TRC_GAP
09-01 18:49:10.621  3523  3571 I         : BTE_InitTraceLevels -- TRC_PAN
,09-01 18:49:10.621  3523  3571 I         : BTE_InitTraceLevels -- TRC_SDP
09-01 18:49:10.622  3523  3571 I         : BTE_InitTraceLevels -- TRC_GATT
,09-01 18:49:10.623  3523  3571 I         : BTE_InitTraceLevels -- TRC_SMP
09-01 18:49:10.623  3523  3571 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-01 18:49:10.623  3523  3571 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-01 18:49:10.759  3523  3571 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3a06d9d
,09-01 18:49:10.760  3523  3571 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3a06d9d 
,09-01 18:49:10.771  3523  3565 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-01 18:49:10.773  3523  3565 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-01 18:49:10.774  3523  3565 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-01 18:49:10.776  3523  3565 D BluetoothAdapterProperties: Name is: Nexus 6
,09-01 18:49:10.782  3523  3565 D BluetoothAdapterProperties: Scan Mode:20
,09-01 18:49:10.784  3523  3565 D BluetoothAdapterProperties: Discoverable Timeout:120
09-01 18:49:10.784  3523  3565 D bt_hci  : do_postload posting postload work item
09-01 18:49:10.784  3523  3569 I bt_hci  : event_postload
09-01 18:49:10.784  3523  3569 I bt_vendor: sco_config_cb
09-01 18:49:10.784  3523  3569 I bt_hci  : sco_config_callback postload finished.
09-01 18:49:10.787  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 18:49:10.790  3523  3569 I bt_vendor: low_power_mode_cb
,09-01 18:49:10.790  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 18:49:10.794  3523  3565 D bt_bte_conf: Device ID record 1 : primary
09-01 18:49:10.794  3523  3565 D bt_bte_conf:   vendorId            = 000f
,09-01 18:49:10.794  3523  3565 D bt_bte_conf:   vendorIdSource      = 0001
09-01 18:49:10.794  3523  3565 D bt_bte_conf:   product             = 1200
09-01 18:49:10.794  3523  3565 D bt_bte_conf:   version             = 1436
09-01 18:49:10.794  3523  3565 D bt_bte_conf:   clientExecutableURL = 
09-01 18:49:10.794  3523  3565 D bt_bte_conf:   serviceDescription  = 
09-01 18:49:10.794  3523  3565 D bt_bte_conf:   documentationURL    = 
09-01 18:49:10.794  3523  3565 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-01 18:49:10.795  3523  3561 D bt_stack_manager: event_start_up_stack finished
09-01 18:49:10.796  3523  3560 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-01 18:49:10.796  3523  3560 D BluetoothAdapterProperties: Setting state to 15
09-01 18:49:10.797  3523  3560 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-01 18:49:10.798  3523  3560 I BluetoothAdapterState: Entering BleOnState
,09-01 18:49:10.802  3523  3560 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-01 18:49:10.802  3523  3560 D BluetoothAdapterProperties: Setting state to 11
09-01 18:49:10.804  3523  3560 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-01 18:49:10.811  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 18:49:10.812  3523  3523 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e4183
,09-01 18:49:10.813  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 18:49:10.816  3523  3523 D HeadsetService: Received start request. Starting profile...
09-01 18:49:10.822  3523  3523 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-01 18:49:10.823  3523  3523 D HeadsetStateMachine: make
,09-01 18:49:10.835   874   887 I ActivityManager: Start proc 3580:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-01 18:49:10.838  3523  3523 D HeadsetStateMachine: max_hf_connections = 1
,09-01 18:49:10.839  3523  3523 I bt_bluedroid: get_profile_interface handsfree
09-01 18:49:10.840  3523  3565 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-01 18:49:10.840  3523  3565 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-01 18:49:10.846  3523  3523 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e4183
09-01 18:49:10.848  3523  3560 I BluetoothAdapterState: Entering PendingCommandState
,09-01 18:49:10.852   874   874 D BluetoothA2dp: Proxy object connected
,09-01 18:49:10.852  3523  3523 D A2dpService: Received start request. Starting profile...
09-01 18:49:10.852  3523  3523 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-01 18:49:10.853  3523  3523 I bt_bluedroid: get_profile_interface avrcp
,09-01 18:49:10.861  3523  3523 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-01 18:49:10.861  3523  3523 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-01 18:49:10.861  3523  3523 D A2dpStateMachine: make,
09-01 18:49:10.863  3523  3523 I bt_bluedroid: get_profile_interface a2dp
,09-01 18:49:10.864  3523  3565 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-01 18:49:10.867  3523  3523 I BluetoothHidServiceJni: classInitNative: succeeds
,09-01 18:49:10.868  3523  3523 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e4183
,09-01 18:49:10.869  3523  3593 D A2dpStateMachine: Enter Disconnected: -2
,09-01 18:49:10.870  1357  1357 D BluetoothInputDevice: Proxy object connected
09-01 18:49:10.870  3523  3523 D HidService: Received start request. Starting profile...
09-01 18:49:10.871  3523  3523 I bt_bluedroid: get_profile_interface hidhost
,09-01 18:49:10.871  1357  1357 D HidProfile: Bluetooth service connected
,09-01 18:49:10.871  3523  3565 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39e83e5
09-01 18:49:10.871  3523  3565 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-01 18:49:10.871  3523  3523 D HidService: setHidService(): set to: null
09-01 18:49:10.872  3523  3523 V BluetoothAdapterState: isTurningOff()=false
09-01 18:49:10.872  3523  3523 V BluetoothAdapterState: isTurningOn()=true
09-01 18:49:10.872  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 18:49:10.872  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
09-01 18:49:10.874  3523  3523 I BluetoothHealthServiceJni: classInitNative: succeeds
09-01 18:49:10.874  3523  3579 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-01 18:49:10.875  3523  3523 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e4183
09-01 18:49:10.876  3523  3523 D HealthService: Received start request. Starting profile...
,09-01 18:49:10.877  3523  3523 I bt_bluedroid: get_profile_interface health
09-01 18:49:10.878  3523  3523 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-01 18:49:10.879  3523  3523 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e4183
09-01 18:49:10.880  1357  1357 D BluetoothPan: BluetoothPAN Proxy object connected
,09-01 18:49:10.880  1357  1357 D PanProfile: Bluetooth service connected
09-01 18:49:10.880  3523  3523 D PanService: Received start request. Starting profile...
09-01 18:49:10.884  3523  3523 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-01 18:49:10.884  3523  3523 I bt_bluedroid: get_profile_interface pan
,09-01 18:49:10.884  3523  3565 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-01 18:49:10.887  3523  3523 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e4183
09-01 18:49:10.887  3580  3580 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-01 18:49:10.889  3523  3523 D BluetoothMapService: Received start request. Starting profile...
09-01 18:49:10.889  1357  1357 D BluetoothMap: Proxy object connected
09-01 18:49:10.889  3523  3523 D BluetoothMapService: start()
09-01 18:49:10.889  1357  1357 D MapProfile: Bluetooth service connected
09-01 18:49:10.889  1357  1357 D BluetoothMap: getConnectedDevices()
09-01 18:49:10.890  1357  1357 D BluetoothMap: Bluetooth is Not enabled
,09-01 18:49:10.891  3523  3523 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-01 18:49:10.891  3523  3523 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-01 18:49:10.891  3523  3523 D BluetoothMapAppObserver: createReceiver()
09-01 18:49:10.892  3523  3523 D BluetoothMapAppObserver: initObservers()
,09-01 18:49:10.892  3523  3523 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-01 18:49:10.898  3523  3523 V BluetoothAdapterState: isTurningOff()=false
09-01 18:49:10.898  3523  3523 V BluetoothAdapterState: isTurningOn()=true
09-01 18:49:10.898  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
09-01 18:49:10.898   874  1924 I ActivityManager: Killing 2978:com.google.android.gm/u0a78 (adj 15): empty #17
09-01 18:49:10.898  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
09-01 18:49:10.898  3523  3523 V BluetoothAdapterState: isTurningOff()=false
09-01 18:49:10.898  3523  3523 V BluetoothAdapterState: isTurningOn()=true
09-01 18:49:10.898  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
09-01 18:49:10.898  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
09-01 18:49:10.898  3523  3523 V BluetoothAdapterState: isTurningOff()=false
09-01 18:49:10.899  3523  3523 V BluetoothAdapterState: isTurningOn()=true
09-01 18:49:10.899  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
09-01 18:49:10.899  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
09-01 18:49:10.899  3523  3523 V BluetoothAdapterState: isTurningOff()=false
09-01 18:49:10.899  3523  3523 V BluetoothAdapterState: isTurningOn()=true
09-01 18:49:10.899  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
09-01 18:49:10.899  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
09-01 18:49:10.899  3523  3523 V BluetoothAdapterState: isTurningOff()=false
09-01 18:49:10.899  3523  3523 V BluetoothAdapterState: isTurningOn()=true
,09-01 18:49:10.899  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
09-01 18:49:10.899  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 18:49:10.900  3523  3560 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-01 18:49:10.900  3523  3560 D BluetoothAdapterProperties: ScanMode =  20
09-01 18:49:10.900  3523  3560 D BluetoothAdapterProperties: State =  11
,09-01 18:49:10.967  3523  3565 D BluetoothAdapterProperties: Scan Mode:21
09-01 18:49:10.967  3523  3560 D BluetoothAdapterProperties: Setting state to 12
,09-01 18:49:10.967  3523  3565 D BluetoothAdapterProperties: Discoverable Timeout:120
09-01 18:49:10.968  3523  3560 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-01 18:49:10.968  3523  3560 I BluetoothAdapterState: Entering OnState
,09-01 18:49:10.969  1357  2088 D BluetoothPbap: onBluetoothStateChange: up=true
,09-01 18:49:10.977  1357  1368 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-01 18:49:10.979  1357  1369 D BluetoothPan: onBluetoothStateChange on: true
09-01 18:49:10.979  1357  2088 D BluetoothMap: onBluetoothStateChange: up=true
09-01 18:49:10.980   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-01 18:49:10.980   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 18:49:10.985  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 18:49:10.985  1962  1980 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 18:49:10.986   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 18:49:10.987   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 18:49:10.994  3464  3464 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-01 18:49:10.994   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,09-01 18:49:10.999  3464  3464 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-01 18:49:11.001  3523  3523 D BluetoothMapService: onReceive
,09-01 18:49:11.001  3523  3523 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-01 18:49:11.001  3523  3523 D BluetoothMapService: STATE_ON
,09-01 18:49:11.004  3464  3464 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-01 18:49:11.006  1357  1646 D LocalBluetoothProfileManager: Adding local A2DP profile
09-01 18:49:11.009  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 18:49:11.009  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 18:49:11.009  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 18:49:11.009  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 18:49:11.009  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 18:49:11.009  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 18:49:11.009  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 18:49:11.009  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 18:49:11.011  3464  3464 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 18:49:11.016  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 18:49:11.016  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 18:49:11.016  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 18:49:11.016  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 18:49:11.016  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 18:49:11.016  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 18:49:11.016  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 18:49:11.016  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 18:49:11.018  3464  3464 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 18:49:11.019  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 18:49:11.020  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 18:49:11.021  3523  3523 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-01 18:49:11.022  3523  3523 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-01 18:49:11.023   874  1988 I ActivityManager: Start proc 3599:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-01 18:49:11.024  1357  1646 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-01 18:49:11.025  3523  3523 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 18:49:11.025  1357  1357 D BluetoothA2dp: Proxy object connected
09-01 18:49:11.027  3523  3523 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 18:49:11.028  3523  3523 D ObexServerSockets: Succeed to create listening sockets 
,09-01 18:49:11.028  3523  3523 D ObexServerSockets0: startAccept()
09-01 18:49:11.028  3523  3523 D ObexServerSockets0: prepareForNewConnect()
09-01 18:49:11.030  3523  3523 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-01 18:49:11.031  3523  3523 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-01 18:49:11.031  3523  3611 D ObexServerSockets0: Accepting socket connection...
09-01 18:49:11.031  3523  3610 D ObexServerSockets0: Accepting socket connection...
,09-01 18:49:11.056  3599  3599 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-01 18:49:11.086   874   891 D BluetoothHeadset: Proxy object connected
,09-01 18:49:11.087  1962  1981 D BluetoothHeadset: Proxy object connected
,09-01 18:49:11.088   874   891 D BluetoothHeadset: Proxy object connected
,09-01 18:49:11.088   874   891 D BluetoothHeadset: Proxy object connected
,09-01 18:49:11.131  1357  1369 D BluetoothHeadset: Proxy object connected
,09-01 18:49:11.134  1357  1357 D HeadsetProfile: Bluetooth service connected
,09-01 18:49:11.197  3599  3599 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at java.io.File.exists(File.java:361)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 18:49:11.197  3599  3599 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 18:49:11.197  3599  3599 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 18:49:11.197  3599  3599 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.r.e.b(PG:170)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 18:49:11.197  3599  3599 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.r.k.d(PG:583)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.r.e.b(PG:170)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 18:49:11.197  3599  3599 D StrictMode: StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at java.io.File.exists(File.java:361)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 18:49:11.197  3599  3599 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 18:49:11.198  3599  3599 D StrictMode: StrictMode policy violation; ~duration=52 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 18:49:11.198  3599  3599 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at java.io.File.exists(File.java:361)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 18:49:11.198  3599  3599 D StrictMode: StrictMode policy violation; ~duration=51 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 18:49:11.198  3599  3599 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 18:49:11.198  3599  3599 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 18:49:11.205  3580  3580 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 18:49:11.216  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 18:49:11.222   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@64303c:true
,09-01 18:49:11.241  1357  1357 D BluetoothPbap: Proxy object connected
,09-01 18:49:11.242  1357  1357 D PbapServerProfile: Bluetooth service connected
,09-01 18:49:11.255  3580  3580 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-01 18:49:11.260  3580  3580 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-01 18:49:11.261  3523  3630 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 18:49:11.270  3580  3580 D LocalBluetoothProfileManager: Adding local MAP profile
,09-01 18:49:11.274  3580  3580 D BluetoothMap: Create BluetoothMap proxy object
,09-01 18:49:11.284  3580  3580 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-01 18:49:11.288  3580  3580 D DockEventReceiver: finishStartingService: stopping service
,09-01 18:49:11.289  3580  3580 D BluetoothA2dp: Proxy object connected
,09-01 18:49:11.292  3523  3636 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 18:49:11.294  3523  3636 I BtOppRfcommListener: Accept thread started.
,09-01 18:49:11.295  3580  3580 D BluetoothInputDevice: Proxy object connected
,09-01 18:49:11.296  3580  3580 D HidProfile: Bluetooth service connected
,09-01 18:49:11.300  3580  3580 D BluetoothPan: BluetoothPAN Proxy object connected
,09-01 18:49:11.301  3580  3580 D PanProfile: Bluetooth service connected
09-01 18:49:11.301  3580  3580 D BluetoothMap: Proxy object connected
09-01 18:49:11.301  3580  3580 D MapProfile: Bluetooth service connected
,09-01 18:49:11.302  3580  3580 D BluetoothMap: getConnectedDevices()
,09-01 18:49:11.308  3580  3580 D BluetoothPbap: Proxy object connected
,09-01 18:49:11.308  3580  3580 D PbapServerProfile: Bluetooth service connected
,09-01 18:49:11.309   874  1949 I ActivityManager: Killing 3172:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-01 18:49:11.367  3580  3592 D BluetoothHeadset: Proxy object connected
,09-01 18:49:11.368  3580  3580 D HeadsetProfile: Bluetooth service connected
,09-01 18:49:11.484  3599  3623 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-01 18:49:11.496   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cced22b:true
,09-01 18:49:12.420   874  1971 D WifiService: setWifiEnabled: true pid=3464, uid=10000
,09-01 18:49:12.421   874  1971 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 18:49:12.433   874  1311 D WifiConfigStore: Loading config and enabling all networks 
,09-01 18:49:12.450  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 18:49:12.450  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 18:49:12.450  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 18:49:12.450  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 18:49:12.450  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 18:49:12.450  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 18:49:12.450  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 18:49:12.450  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 18:49:12.456  3464  3464 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 18:49:12.462  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 18:49:12.462  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 18:49:12.462  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 18:49:12.462  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 18:49:12.462  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 18:49:12.462  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 18:49:12.462  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 18:49:12.462  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 18:49:12.467  3464  3464 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 18:49:12.471   874  1311 D WifiConfigStore: loaded 0 passpoint configs
09-01 18:49:12.472   874  1311 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-01 18:49:12.473   874  1311 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-01 18:49:12.474   874  1311 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-01 18:49:12.474   874  1311 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-01 18:49:12.474   874  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-01 18:49:12.474   874  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-01 18:49:12.476  1466  1466 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-01 18:49:12.562   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-01 18:49:12.565   373   872 D CommandListener: Setting iface cfg
,09-01 18:49:12.566   874  1310 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '111 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 111 Failed to set address (No such device)'
,09-01 18:49:12.566   874  1310 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-01 18:49:12.569   874  1310 D WifiNative-HAL: p2pGetDeviceAddress
09-01 18:49:12.570   874  1310 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-01 18:49:12.597   874  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 18:49:12.602   874  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 18:49:12.981  1466  1466 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-01 18:49:13.021  1466  1466 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-01 18:49:13.022  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-01 18:49:13.031   874  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 18:49:13.044   874  1311 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-01 18:49:13.045   874  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-01 18:49:13.046   874  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 18:49:13.068   874  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 18:49:13.081   373   872 D CommandListener: Setting iface cfg
,09-01 18:49:13.091   874  1311 D WifiStateMachine: Start Dhcp Watchdog 1
,09-01 18:49:13.107   874  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-01 18:49:13.108   874  1313 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-01 18:49:13.110   874  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-01 18:49:13.120   874  3647 D DhcpClient: Receive thread started
,09-01 18:49:13.201   874  1311 E native  : do suspend false
,09-01 18:49:13.225   874  3646 D DhcpClient: Broadcasting DHCPDISCOVER
,09-01 18:49:13.242   874  3647 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 156921, domain null
,09-01 18:49:13.244   874  3646 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 156921 seconds
,09-01 18:49:13.249   874  3646 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-01 18:49:13.268   874  3647 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-01 18:49:13.269   874  3646 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-01 18:49:13.274   373   872 D CommandListener: Setting iface cfg
,09-01 18:49:13.284   874  3646 D DhcpClient: Scheduling renewal in 86399s
,09-01 18:49:13.288   874  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-01 18:49:13.299   874  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-01 18:49:13.302   874  1311 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,09-01 18:49:13.303   874  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-01 18:49:13.306   874  1313 D ConnectivityService: Adding iface wlan0 to network 100
,09-01 18:49:13.315   874  1311 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-01 18:49:13.352   874  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-01 18:49:13.352   874  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,09-01 18:49:13.355   874  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,09-01 18:49:13.358   874  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,09-01 18:49:13.360   874  1313 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,09-01 18:49:13.375   874  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-01 18:49:13.382   874  1313 D ConnectivityService: scheduleUnvalidatedPrompt 100
,09-01 18:49:13.382   874  1313 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
09-01 18:49:13.383   874  1311 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-01 18:49:13.383   874  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-01 18:49:13.384   874  1313 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
,09-01 18:49:13.384   874  1313 D ConnectivityService:    accepting network in place of null
,09-01 18:49:13.386   874  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} },
,09-01 18:49:13.415   874  3645 D NetlinkSocketObserver: NeighborEvent{elapsedMs=136536, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-01 18:49:13.432   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 18:49:13.478   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 18:49:13.482   874  1313 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,09-01 18:49:13.486   874  3644 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=89.25.215.93,2a00:1450:400d:803::200e
,09-01 18:49:13.497   874  1313 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-01 18:49:13.498   874  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-01 18:49:13.515   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-01 18:49:13.523   874  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
09-01 18:49:13.528  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 18:49:13.528  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 18:49:13.528  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 18:49:13.528  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 18:49:13.528  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 18:49:13.528  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 18:49:13.528  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 18:49:13.528  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 18:49:13.530  3464  3464 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 18:49:13.532   874  3644 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 01 Sep 2016 16:49:13 GMT], X-Android-Received-Millis=[1472748553531], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472748553519]}
,09-01 18:49:13.535  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 18:49:13.535  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 18:49:13.535  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 18:49:13.535  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 18:49:13.535  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 18:49:13.535  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 18:49:13.535  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 18:49:13.535  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 18:49:13.536   874  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-01 18:49:13.536   874  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
09-01 18:49:13.536   874  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-01 18:49:13.538  3464  3464 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 18:49:13.539   874  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-01 18:49:13.545   874   885 V BackupManagerService: Scheduling immediate backup pass
,09-01 18:49:13.548   874   874 V BackupManagerService: Running a backup pass
,09-01 18:49:13.549   874  1330 V BackupManagerService: clearing pending backups
,09-01 18:49:13.552  1731  1731 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-01 18:49:13.553   874  1330 V PerformBackupTask: Beginning backup of 16 targets
09-01 18:49:13.555  1731  1731 D SystemUpdateService: onCreate
09-01 18:49:13.555  2029  2029 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-01 18:49:13.559  1731  1731 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-01 18:49:13.563  1731  3662 I SystemUpdateService: active receiver: enabled
,09-01 18:49:13.583   874  1930 D AlarmManagerService: Setting time of day to sec=1472748553
,09-01 18:49:13.414   874  1930 W AlarmManagerService: Unable to set rtc to 1472748553: Invalid argument
,09-01 18:49:13.419   874  1330 D PerformBackupTask: invokeAgentForBackup on @pm@
,09-01 18:49:13.421  1731  3662 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-01 18:49:13.422  1731  3662 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-01 18:49:13.422  1731  3662 I SystemUpdateService: now status is 0 (complete)
09-01 18:49:13.423  1731  3662 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-01 18:49:13.423  1731  3662 I SystemUpdateService: file has been verified
09-01 18:49:13.424   874  1330 I PMBA    : Previous metadata 1570415 mismatch vs 2862625 - rewriting
09-01 18:49:13.426  1731  3662 I SystemUpdateService: OTA package size = 12249756
,09-01 18:49:13.433  1731  3662 I SystemUpdateService: showing system update notification
,09-01 18:49:13.460   874  3673 D GpsLocationProvider: NTP server returned: 1472748553414 (Thu Sep 01 18:49:13 GMT+02:00 2016) reference: 136705 certainty: 6 system time offset: -45
,09-01 18:49:13.460   874  3673 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,09-01 18:49:13.463  1731  1731 D SystemUpdateService: onDestroy
,09-01 18:49:13.484   874  1330 I BackupRestoreController: Getting widget state for user: 0
,09-01 18:49:13.495  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 18:49:13.496  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 18:49:13.507  1515  1515 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-01 18:49:13.527  1731  3679 I iu.SyncManager: SYNC; picasa accounts
,09-01 18:49:13.532  1731  1731 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,09-01 18:49:13.534  1731  1731 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-01 18:49:13.541  1731  3672 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,09-01 18:49:13.544  1731  1731 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-01 18:49:13.549  2076  2086 W GmsBackupTransport: Unknown package in backup request: @pm@
,09-01 18:49:13.551  1731  1731 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-01 18:49:13.550  2076  2086 V GmsBackupTransport: starting performBackup for @pm@
,09-01 18:49:13.553  1731  3675 I MDM     : [150] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-01 18:49:13.553  1731  3675 W BaseAppContext: Using Auth Proxy for data requests.
,09-01 18:49:13.556  1731  3679 I iu.UploadsManager: num queued entries: 0
09-01 18:49:13.556  1731  3679 I iu.UploadsManager: num updated entries: 0
09-01 18:49:13.557  1731  3679 I iu.SyncManager: NEXT; no task
09-01 18:49:13.564   874  1924 I ActivityManager: Start proc 3684:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-01 18:49:13.579  1731  3675 V GoogleAuthProtoRequest: [150] a.<init>: mAccountName set to: thalitester@gmail.com
,09-01 18:49:13.588  3534  3670 V GoogleAuthProtoRequest: [278] a.<init>: mAccountName set to: thalitester@gmail.com
,09-01 18:49:13.591  2076  2086 V GmsBackupTransport: performBackup done for @pm@
,09-01 18:49:13.603  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 18:49:13.615  3684  3684 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-01 18:49:13.622  1515  3213 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: android
,09-01 18:49:13.622  1515  3213 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> android without consulting the cloud.
09-01 18:49:13.622  1515  3213 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 18:49:13.622  1515  3213 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 18:49:13.628  3684  3684 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-01 18:49:13.632  1515  3213 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-01 18:49:13.632  1515  3213 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-01 18:49:13.632  1515  3213 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-01 18:49:13.632  1515  3213 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-01 18:49:13.632  1515  3213 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-01 18:49:13.632  1515  3213 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-01 18:49:13.632  1515  3213 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-01 18:49:13.633  1515  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-01 18:49:13.634  1515  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-01 18:49:13.634  1515  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 18:49:13.634  1515  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 18:49:13.638  2076  2427 W GmsBackupTransport: Error sending final backup to server: 
09-01 18:49:13.638  2076  2427 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
09-01 18:49:13.638  2076  2427 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1078)
09-01 18:49:13.638  2076  2427 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
09-01 18:49:13.638  2076  2427 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
09-01 18:49:13.638  2076  2427 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:583)
09-01 18:49:13.638  2076  2427 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
09-01 18:49:13.638  2076  2427 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:453)
09-01 18:49:13.638  2076  2427 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-01 18:49:13.638  2076  2427 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-01 18:49:13.638  2076  2427 W GmsBackupTransport: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-01 18:49:13.638  2076  2427 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-01 18:49:13.638  2076  2427 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-01 18:49:13.638  2076  2427 W GmsBackupTransport: 	... 1 more
,09-01 18:49:13.639  2076  2092 I GmsBackupTransport: Next backup will happen in 43199994 millis.
,09-01 18:49:13.640   874  1330 V KeyValueBackupJob: Scheduling k/v pass in 719 minutes
09-01 18:49:13.640  3684  3684 D SprintDMHelper: simOperator: 
09-01 18:49:13.640  3684  3684 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-01 18:49:13.661   874  1971 I ActivityManager: Start proc 3702:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-01 18:49:13.676  1731  3675 E MDM     : [150] SitrepService.a: Error sending sitrep.
,09-01 18:49:13.681  1731  1731 E ConnectivityChangeReceiver: Ignoring connectivity change
,09-01 18:49:13.687   874  1392 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/1731 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-01 18:49:13.692  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,09-01 18:49:13.692  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
09-01 18:49:13.693  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 18:49:13.693  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 18:49:13.710  3534  3670 W ExperimentUpdateService: [278] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,09-01 18:49:13.710  3534  3670 W ExperimentUpdateService: [278] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-01 18:49:13.710  3534  3670 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-01 18:49:13.710  3534  3670 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
09-01 18:49:13.710  3534  3670 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
09-01 18:49:13.710  3534  3670 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
09-01 18:49:13.710  3534  3670 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
09-01 18:49:13.710  3534  3670 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
09-01 18:49:13.710  3534  3670 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
09-01 18:49:13.710  3534  3670 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
09-01 18:49:13.710  3534  3670 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
09-01 18:49:13.710  3534  3670 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
09-01 18:49:13.717   874  1330 I BackupManagerService: Backup pass finished.
,09-01 18:49:13.860  1731  3674 W DriveInitializer: Awaiting to be initialized
,09-01 18:49:13.861  1731  3723 W DriveInitializer: Background init thread started
,09-01 18:49:13.889  1515  3676 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,09-01 18:49:13.932  1731  3723 W DriveInitializer: Background init thread ended
,09-01 18:49:13.960  3015  3720 V KeepSync: Connecting to GoogleApiClient
,09-01 18:49:13.961   874  1988 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-01 18:49:13.966   874  1392 I ActivityManager: Start proc 3738:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-01 18:49:14.006  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 18:49:14.011  1515  3754 I VacuumService: Vacuum at: now=1472748554011 tag=VacuumService
,09-01 18:49:14.029  1515  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-01 18:49:14.029  1515  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-01 18:49:14.029  1515  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 18:49:14.029  1515  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 18:49:14.032  1515  2722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-01 18:49:14.032  1515  2722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-01 18:49:14.032  1515  2722 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 18:49:14.032  1515  2722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 18:49:14.047  1731  3752 V BaseAuthAsyncOperation: access token request failed
,09-01 18:49:14.052  3266  3692 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-01 18:49:14.052  3266  3692 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-01 18:49:14.052  3266  3692 E HttpOperation: 	at jdm.a(PG:82)
09-01 18:49:14.052  3266  3692 E HttpOperation: 	at jcs.o(PG:406)
09-01 18:49:14.052  3266  3692 E HttpOperation: 	at jcn.a(PG:1379)
09-01 18:49:14.052  3266  3692 E HttpOperation: 	at jcs.i(PG:143)
09-01 18:49:14.052  3266  3692 E HttpOperation: 	at blb.a(PG:3937)
09-01 18:49:14.052  3266  3692 E HttpOperation: 	at czp.a(PG:18188)
09-01 18:49:14.052  3266  3692 E HttpOperation: 	at czp.a(PG:9081)
09-01 18:49:14.052  3266  3692 E HttpOperation: 	at czq.run(PG:1686)
09-01 18:49:14.052  3266  3692 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-01 18:49:14.052  3266  3692 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 18:49:14.052  3266  3692 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 18:49:14.052  3266  3692 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 18:49:14.052  3266  3692 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-01 18:49:14.052  3266  3692 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-01 18:49:14.052  3266  3692 E HttpOperation: 	at jdj.a(PG:4091)
09-01 18:49:14.052  3266  3692 E HttpOperation: 	at jdj.a(PG:1125)
09-01 18:49:14.052  3266  3692 E HttpOperation: 	at jdm.a(PG:77)
09-01 18:49:14.052  3266  3692 E HttpOperation: 	... 12 more
09-01 18:49:14.052  3266  3692 E HttpOperation: Caused by: faj: BadAuthentication
09-01 18:49:14.052  3266  3692 E HttpOperation: 	at fal.a(PG:38)
09-01 18:49:14.052  3266  3692 E HttpOperation: 	at jdj.a(PG:4089)
09-01 18:49:14.052  3266  3692 E HttpOperation: 	... 14 more
,09-01 18:49:14.052  3015  3720 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-01 18:49:14.047  2873  3737 I Babel   : connection state changed from UNKNOWN to CONNECTED
,09-01 18:49:14.056  3738  3738 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-01 18:49:14.142  1515  2058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-01 18:49:14.142  1515  2058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-01 18:49:14.142  1515  2058 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 18:49:14.142  1515  2058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 18:49:14.159  3266  3692 E HttpOperation: [getmobileexperiments] Unexpected exception
09-01 18:49:14.159  3266  3692 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-01 18:49:14.159  3266  3692 E HttpOperation: 	at jdm.a(PG:82)
09-01 18:49:14.159  3266  3692 E HttpOperation: 	at jcs.o(PG:406)
09-01 18:49:14.159  3266  3692 E HttpOperation: 	at jcn.a(PG:1379)
09-01 18:49:14.159  3266  3692 E HttpOperation: 	at jcs.i(PG:143)
09-01 18:49:14.159  3266  3692 E HttpOperation: 	at hec.a(PG:42)
09-01 18:49:14.159  3266  3692 E HttpOperation: 	at hee.a(PG:102)
09-01 18:49:14.159  3266  3692 E HttpOperation: 	at czr.a(PG:65)
09-01 18:49:14.159  3266  3692 E HttpOperation: 	at kka.a(PG:108)
09-01 18:49:14.159  3266  3692 E HttpOperation: 	at czp.a(PG:19176)
09-01 18:49:14.159  3266  3692 E HttpOperation: 	at czp.a(PG:9081)
09-01 18:49:14.159  3266  3692 E HttpOperation: 	at czq.run(PG:1686)
09-01 18:49:14.159  3266  3692 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-01 18:49:14.159  3266  3692 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 18:49:14.159  3266  3692 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 18:49:14.159  3266  3692 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 18:49:14.159  3266  3692 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-01 18:49:14.159  3266  3692 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-01 18:49:14.159  3266  3692 E HttpOperation: 	at jdj.a(PG:4091)
09-01 18:49:14.159  3266  3692 E HttpOperation: 	at jdj.a(PG:1125)
09-01 18:49:14.159  3266  3692 E HttpOperation: 	at jdm.a(PG:77)
09-01 18:49:14.159  3266  3692 E HttpOperation: 	... 15 more
09-01 18:49:14.159  3266  3692 E HttpOperation: Caused by: faj: BadAuthentication
09-01 18:49:14.159  3266  3692 E HttpOperation: 	at fal.a(PG:38)
09-01 18:49:14.159  3266  3692 E HttpOperation: 	at jdj.a(PG:4089)
09-01 18:49:14.159  3266  3692 E HttpOperation: 	... 17 more
,09-01 18:49:14.159  3266  3692 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-01 18:49:14.159  3266  3692 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-01 18:49:14.159  3266  3692 E ExperimentLoader: 	at jdm.a(PG:82)
09-01 18:49:14.159  3266  3692 E ExperimentLoader: 	at jcs.o(PG:406)
09-01 18:49:14.159  3266  3692 E ExperimentLoader: 	at jcn.a(PG:1379)
09-01 18:49:14.159  3266  3692 E ExperimentLoader: 	at jcs.i(PG:143)
09-01 18:49:14.159  3266  3692 E ExperimentLoader: 	at hec.a(PG:42)
09-01 18:49:14.159  3266  3692 E ExperimentLoader: 	at hee.a(PG:102)
09-01 18:49:14.159  3266  3692 E ExperimentLoader: 	at czr.a(PG:65)
09-01 18:49:14.159  3266  3692 E ExperimentLoader: 	at kka.a(PG:108)
09-01 18:49:14.159  3266  3692 E ExperimentLoader: 	at czp.a(PG:19176)
09-01 18:49:14.159  3266  3692 E ExperimentLoader: 	at czp.a(PG:9081)
09-01 18:49:14.159  3266  3692 E ExperimentLoader: 	at czq.run(PG:1686)
09-01 18:49:14.159  3266  3692 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-01 18:49:14.159  3266  3692 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 18:49:14.159  3266  3692 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 18:49:14.159  3266  3692 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 18:49:14.159  3266  3692 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-01 18:49:14.159  3266  3692 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-01 18:49:14.159  3266  3692 E ExperimentLoader: 	at jdj.a(PG:4091)
09-01 18:49:14.159  3266  3692 E ExperimentLoader: 	at jdj.a(PG:1125)
09-01 18:49:14.159  3266  3692 E ExperimentLoader: 	at jdm.a(PG:77)
09-01 18:49:14.159  3266  3692 E ExperimentLoader: 	... 15 more
09-01 18:49:14.159  3266  3692 E ExperimentLoader: Caused by: faj: BadAuthentication
09-01 18:49:14.159  3266  3692 E ExperimentLoader: 	at fal.a(PG:38)
09-01 18:49:14.159  3266  3692 E ExperimentLoader: 	at jdj.a(PG:4089)
09-01 18:49:14.159  3266  3692 E ExperimentLoader: 	... 17 more
,09-01 18:49:14.195  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-01 18:49:14.195  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-01 18:49:14.195  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 18:49:14.195  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 18:49:14.207  3015  3720 E KeepSync: IOException
09-01 18:49:14.207  3015  3720 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-01 18:49:14.207  3015  3720 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-01 18:49:14.207  3015  3720 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-01 18:49:14.207  3015  3720 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-01 18:49:14.207  3015  3720 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-01 18:49:14.207  3015  3720 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-01 18:49:14.207  3015  3720 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-01 18:49:14.207  3015  3720 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-01 18:49:14.207  3015  3720 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-01 18:49:14.207  3015  3720 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-01 18:49:14.207  3015  3720 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-01 18:49:14.207  3015  3720 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-01 18:49:14.207  3015  3720 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-01 18:49:14.207  3015  3720 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-01 18:49:14.207  3015  3720 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-01 18:49:14.207  3015  3720 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-01 18:49:14.207  3015  3720 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-01 18:49:14.207  3015  3720 E KeepSync: 	... 10 more
,09-01 18:49:14.207  3015  3720 W KeepSync: Sync result 2
,09-01 18:49:14.211   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 26198, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-01 18:49:14.231   874   886 I ActivityManager: Start proc 3758:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,09-01 18:49:14.266  3758  3758 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,09-01 18:49:14.300  3738  3738 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-01 18:49:14.300  3738  3738 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-01 18:49:14.300  3738  3738 I GAv4    :   adb logcat -s GAv4
,09-01 18:49:14.312   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 26186, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-01 18:49:14.312   874  2059 I ActivityManager: Killing 2622:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-01 18:49:14.362  3738  3738 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-01 18:49:14.367  3738  3738 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-01 18:49:14.387  3738  3776 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-01 18:49:14.460  3758  3758 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-01 18:49:14.467  3758  3758 I BooksApp: Created application version: 3.6.9 (30609)
,09-01 18:49:14.520  3738  3738 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-01 18:49:14.550  3738  3738 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-01 18:49:14.556  3738  3738 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7846-7848)
,09-01 18:49:14.556  3738  3738 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-01 18:49:14.568  3758  3799 I BooksSync: Starting books sync for 61035162, extras: ade
,09-01 18:49:14.574  3738  3738 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {545cbab}
,09-01 18:49:14.574  3738  3738 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-01 18:49:14.574  3738  3738 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-01 18:49:14.582  3738  3738 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-01 18:49:14.587  3738  3738 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-01 18:49:14.614  3738  3738 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-01 18:49:14.635  3738  3738 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-01 18:49:14.636  3738  3738 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-01 18:49:14.636  3738  3738 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-01 18:49:14.636  3738  3738 I Adreno  : Build Date                       : 10/20/15
09-01 18:49:14.636  3738  3738 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-01 18:49:14.636  3738  3738 I Adreno  : Local Branch                     : M14
09-01 18:49:14.636  3738  3738 I Adreno  : Remote Branch                    : 
09-01 18:49:14.636  3738  3738 I Adreno  : Remote Branch                    : 
09-01 18:49:14.636  3738  3738 I Adreno  : Reconstruct Branch               : 
,09-01 18:49:14.709  3738  3738 I NSApplication: Starting up...
,09-01 18:49:14.715  3738  3816 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-01 18:49:14.752   874  2057 I ActivityManager: Start proc 3821:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-01 18:49:14.754   874  2057 I ActivityManager: Killing 3247:android.process.acore/u0a5 (adj 15): empty #17
,09-01 18:49:14.828  3821  3821 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-01 18:49:14.938  3758  3837 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-01 18:49:14.981  1515  2404 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-01 18:49:14.981  1515  2404 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-01 18:49:14.982  1515  2404 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 18:49:14.982  1515  2404 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 18:49:15.023  1515  3213 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-01 18:49:15.023  1515  3213 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-01 18:49:15.023  1515  3213 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 18:49:15.023  1515  3213 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 18:49:15.039  3758  3837 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-01 18:49:15.040  3758  3799 E BooksSync: Soft error
09-01 18:49:15.040  3758  3799 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-01 18:49:15.040  3758  3799 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-01 18:49:15.041  3758  3799 E BooksSync: Sync error
09-01 18:49:15.041  3758  3799 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-01 18:49:15.041  3758  3799 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-01 18:49:15.041  3758  3799 I BooksSync: Finished books sync
,09-01 18:49:15.060   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26199, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-01 18:49:15.062   874  1971 I ActivityManager: Killing 3346:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-01 18:49:15.257   874  1949 D WifiService: setWifiEnabled: false pid=3464, uid=10000
,09-01 18:49:15.257   874  1949 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 18:49:15.276  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-01 18:49:15.284   874  1311 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-01 18:49:15.285   874  1311 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-01 18:49:15.285   874  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-01 18:49:15.285   874  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 18:49:15.300   874  3646 D DhcpClient: Clearing IP address
,09-01 18:49:15.302   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-01 18:49:15.308  1515  3714 V NativeCrypto: Read error: ssl=0x9b3eba00: I/O error during system call, Connection timed out
,09-01 18:49:15.316   373   872 D CommandListener: Setting iface cfg
,09-01 18:49:15.322  1515  3714 V NativeCrypto: SSL shutdown failed: ssl=0x9b3eba00: I/O error during system call, Broken pipe
,09-01 18:49:15.324   874  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-01 18:49:15.325   874  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-01 18:49:15.335   398   398 E Parcel  : Reading a NULL string not supported here.
,09-01 18:49:15.337   874  3647 D DhcpClient: Receive thread stopped
,09-01 18:49:15.337   874  1311 D WifiStateMachine: Start Disconnecting Watchdog 1
,09-01 18:49:15.338   874  1313 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-01 18:49:15.342   874  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-01 18:49:15.362   874  2057 I ActivityManager: Killing 3361:com.android.musicfx/u0a18 (adj 15): empty #17
,09-01 18:49:15.374   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 18:49:15.399   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-01 18:49:15.399   373   872 D CommandListener: Clearing all IP addresses on wlan0
09-01 18:49:15.400   874  1313 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-01 18:49:15.401   874  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-01 18:49:15.413   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-01 18:49:15.416   874  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 18:49:15.420  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 18:49:15.420  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 18:49:15.420  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 18:49:15.420  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 18:49:15.420  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 18:49:15.420  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 18:49:15.420  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 18:49:15.420  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 18:49:15.423   874  1311 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-01 18:49:15.424  2029  2029 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-01 18:49:15.425  3464  3464 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 18:49:15.429  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 18:49:15.429  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 18:49:15.429  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 18:49:15.429  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 18:49:15.429  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 18:49:15.429  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 18:49:15.429  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 18:49:15.429  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 18:49:15.430  2076  2313 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 18:49:15.431  3464  3464 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 18:49:15.435  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 18:49:15.435  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 18:49:15.435  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 18:49:15.435  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 18:49:15.435  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 18:49:15.435  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 18:49:15.435  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 18:49:15.435  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 18:49:15.438  3464  3464 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 18:49:15.441  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 18:49:15.454  1731  1731 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-01 18:49:15.456  1731  1731 D SystemUpdateService: onCreate
,09-01 18:49:15.459  1731  1731 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-01 18:49:15.462  1731  3849 I SystemUpdateService: active receiver: enabled
,09-01 18:49:15.467  1731  3849 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-01 18:49:15.470  1731  1731 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-01 18:49:15.471  1731  3679 I iu.UploadsManager: num queued entries: 0
,09-01 18:49:15.472  1731  3679 I iu.UploadsManager: num updated entries: 0
09-01 18:49:15.472  1731  3679 I iu.SyncManager: NEXT; no task
,09-01 18:49:15.473  1731  3849 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-01 18:49:15.473  1731  3849 I SystemUpdateService: now status is 0 (complete)
09-01 18:49:15.473  1731  3849 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-01 18:49:15.473  1731  3849 I SystemUpdateService: file has been verified
09-01 18:49:15.473  1731  3849 I SystemUpdateService: OTA package size = 12249756
,09-01 18:49:15.478  1731  3849 I SystemUpdateService: showing system update notification
,09-01 18:49:15.479  1731  1731 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-01 18:49:15.480  1731  1731 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-01 18:49:15.482  3684  3684 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-01 18:49:15.486  3684  3684 D SprintDMHelper: simOperator: 
,09-01 18:49:15.486  3684  3684 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-01 18:49:15.492  1731  1731 D SystemUpdateService: onDestroy
,09-01 18:49:15.507   373   872 E Netd    : netlink response contains error (No such file or directory)
,09-01 18:49:15.530  2873  3854 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-01 18:49:18.274  3523  3560 D BluetoothAdapterState: Current state: ON, message: 23
,09-01 18:49:18.275  3523  3560 D BluetoothAdapterProperties: Setting state to 13
,09-01 18:49:18.275  3523  3560 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-01 18:49:18.279  3523  3560 D BluetoothAdapterProperties: onBluetoothDisable()
09-01 18:49:18.284  3523  3560 I BluetoothAdapterState: Entering PendingCommandState
09-01 18:49:18.287  3523  3523 D BluetoothMapService: onReceive
09-01 18:49:18.288  3523  3523 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-01 18:49:18.288  3523  3523 D BluetoothMapService: STATE_TURNING_OFF
,09-01 18:49:18.289  3523  3523 D BluetoothMapService: MAP Service closeService in
09-01 18:49:18.289  3523  3523 D BluetoothMapMasInstance0: MAP Service shutdown
09-01 18:49:18.289  3523  3523 D ObexServerSockets0: shutdown(block = true)
09-01 18:49:18.291  3523  3610 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-01 18:49:18.295  3523  3523 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-01 18:49:18.295  3464  3464 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:49:18.296  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 18:49:18.296  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 18:49:18.296  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 18:49:18.296  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 18:49:18.296  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 18:49:18.296  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 18:49:18.296  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 18:49:18.296  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 18:49:18.296  3523  3611 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-01 18:49:18.297  3523  3573 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-01 18:49:18.297  3464  3464 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:49:18.298  3523  3523 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-01 18:49:18.298  3464  3464 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 18:49:18.298  3523  3523 I BtOppRfcommListener: stopping Accept Thread
,09-01 18:49:18.298  3523  3636 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-01 18:49:18.299  3523  3636 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-01 18:49:18.299  3523  3565 D BluetoothAdapterProperties: Scan Mode:20
,09-01 18:49:18.301  3523  3560 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-01 18:49:18.304  3464  3464 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:49:18.304  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 18:49:18.304  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 18:49:18.304  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 18:49:18.304  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 18:49:18.304  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 18:49:18.304  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 18:49:18.304  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 18:49:18.304  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 18:49:18.305  3464  3464 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:49:18.305  3464  3464 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 18:49:18.308  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 18:49:18.310  3523  3523 D HeadsetService: Received stop request...Stopping profile...
09-01 18:49:18.312  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 18:49:18.313  3580  3590 D BluetoothHeadset: Proxy object disconnected
09-01 18:49:18.313   874   874 D BluetoothHeadset: Proxy object disconnected
,09-01 18:49:18.314   874   874 D BluetoothHeadset: Proxy object disconnected
09-01 18:49:18.314  1962  2316 D BluetoothHeadset: Proxy object disconnected
,09-01 18:49:18.314  1357  1369 D BluetoothHeadset: Proxy object disconnected
,09-01 18:49:18.315   874   874 D BluetoothHeadset: Proxy object disconnected
09-01 18:49:18.315  3523  3523 D A2dpService: Received stop request...Stopping profile...
09-01 18:49:18.315  3523  3593 D A2dpStateMachine: Exit Disconnected: -1
09-01 18:49:18.316  1357  1357 D HeadsetProfile: Bluetooth service disconnected
09-01 18:49:18.316   874   874 D BluetoothA2dp: Proxy object disconnected
,09-01 18:49:18.317  1357  1357 D BluetoothA2dp: Proxy object disconnected
,09-01 18:49:18.318  3523  3523 D HidService: Received stop request...Stopping profile...
,09-01 18:49:18.318  3523  3523 D HidService: Stopping Bluetooth HidService
09-01 18:49:18.319  3523  3523 V BluetoothAdapterState: isTurningOff()=true
09-01 18:49:18.319  3523  3523 V BluetoothAdapterState: isTurningOn()=false
09-01 18:49:18.319  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
09-01 18:49:18.320  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
09-01 18:49:18.320  1357  1357 D BluetoothInputDevice: Proxy object disconnected
09-01 18:49:18.320  1357  1357 D HidProfile: Bluetooth service disconnected
09-01 18:49:18.321  3580  3580 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 18:49:18.322  3523  3523 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-01 18:49:18.322  3523  3565 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-01 18:49:18.322  3523  3571 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 18:49:18.322  3523  3571 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 18:49:18.322  3523  3571 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 18:49:18.323  3523  3565 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-01 18:49:18.323  3523  3523 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 18:49:18.323  3580  3580 D HeadsetProfile: Bluetooth service disconnected
09-01 18:49:18.323  3580  3580 D BluetoothA2dp: Proxy object disconnected
,09-01 18:49:18.323  3580  3580 D BluetoothInputDevice: Proxy object disconnected
09-01 18:49:18.323  3523  3523 D HealthService: Received stop request...Stopping profile...
,09-01 18:49:18.323  3580  3580 D HidProfile: Bluetooth service disconnected
09-01 18:49:18.326  3523  3523 D PanService: Received stop request...Stopping profile...
09-01 18:49:18.327  1357  1357 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-01 18:49:18.327  1357  1357 D PanProfile: Bluetooth service disconnected
09-01 18:49:18.328  3523  3523 V BluetoothAdapterState: isTurningOff()=true
09-01 18:49:18.328  3523  3523 V BluetoothAdapterState: isTurningOn()=false
,09-01 18:49:18.328  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 18:49:18.328  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
09-01 18:49:18.330  3523  3565 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-01 18:49:18.330  3523  3571 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-01 18:49:18.330  3523  3571 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 18:49:18.330  3523  3571 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 18:49:18.330  3523  3571 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 18:49:18.330  3523  3571 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 18:49:18.330  3523  3571 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 18:49:18.331  3523  3523 D BluetoothMapService: Received stop request...Stopping profile...
,09-01 18:49:18.331  3523  3523 D BluetoothMapService: stop()
09-01 18:49:18.332  3523  3523 D BluetoothMapAppObserver: deinitObservers()
09-01 18:49:18.332  3523  3523 D BluetoothMapAppObserver: removeReceiver()
,09-01 18:49:18.333  3523  3523 V BluetoothAdapterState: isTurningOff()=true
,09-01 18:49:18.334  3523  3523 V BluetoothAdapterState: isTurningOn()=false
09-01 18:49:18.334  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
09-01 18:49:18.334  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
09-01 18:49:18.334  3523  3523 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-01 18:49:18.334  1357  1357 D BluetoothMap: Proxy object disconnected
09-01 18:49:18.334  3523  3565 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-01 18:49:18.335  1357  1357 D MapProfile: Bluetooth service disconnected
09-01 18:49:18.335  3523  3523 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-01 18:49:18.335  3580  3580 D DockEventReceiver: finishStartingService: stopping service
09-01 18:49:18.336  3523  3523 V BluetoothAdapterState: isTurningOff()=true
,09-01 18:49:18.336  3523  3523 V BluetoothAdapterState: isTurningOn()=false
09-01 18:49:18.336  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
09-01 18:49:18.336  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
09-01 18:49:18.336  3523  3523 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-01 18:49:18.336  3523  3565 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-01 18:49:18.337  3523  3523 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-01 18:49:18.337  3523  3523 V BluetoothAdapterState: isTurningOff()=true
09-01 18:49:18.337  3523  3523 V BluetoothAdapterState: isTurningOn()=false
09-01 18:49:18.337  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
09-01 18:49:18.337  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 18:49:18.337  3523  3523 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-01 18:49:18.338  3523  3523 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-01 18:49:18.338  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 18:49:18.338  3523  3523 D BluetoothMapService: MAP Service closeService in
09-01 18:49:18.338  3523  3523 V BluetoothAdapterState: isTurningOff()=true
09-01 18:49:18.338  3523  3523 V BluetoothAdapterState: isTurningOn()=false
09-01 18:49:18.338  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
09-01 18:49:18.338  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
09-01 18:49:18.338  3523  3560 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-01 18:49:18.339  3523  3523 D BluetoothMapService: cleanup()
09-01 18:49:18.339  3523  3560 D BluetoothAdapterProperties: Setting state to 15
09-01 18:49:18.339  3523  3523 D BluetoothMapService: MAP Service closeService in
09-01 18:49:18.339  3523  3560 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-01 18:49:18.339  3523  3560 I BluetoothAdapterState: Entering BleOnState
09-01 18:49:18.340  3580  3590 D BluetoothPbap: onBluetoothStateChange: up=false
09-01 18:49:18.340  1357  1357 D BluetoothPbap: Proxy object disconnected
09-01 18:49:18.340  1357  1357 D PbapServerProfile: Bluetooth service disconnected
09-01 18:49:18.341  1357  1369 D BluetoothPbap: onBluetoothStateChange: up=false
09-01 18:49:18.343  3580  3592 D BluetoothMap: onBluetoothStateChange: up=false
09-01 18:49:18.344  1357  2088 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-01 18:49:18.345  3580  3590 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-01 18:49:18.345  1357  1368 D BluetoothPan: onBluetoothStateChange on: false
09-01 18:49:18.346  3580  3861 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-01 18:49:18.346  1357  1369 D BluetoothMap: onBluetoothStateChange: up=false
09-01 18:49:18.348   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 18:49:18.348   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 18:49:18.348  3580  3580 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-01 18:49:18.349  3580  3580 D PanProfile: Bluetooth service disconnected
,09-01 18:49:18.349  1962  2170 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 18:49:18.349   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-01 18:49:18.349   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 18:49:18.349  3580  3590 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 18:49:18.350  1357  2088 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 18:49:18.351  1357  1368 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 18:49:18.351  3580  3861 D BluetoothPan: onBluetoothStateChange on: false
09-01 18:49:18.352  3523  3560 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-01 18:49:18.352  3523  3560 D BluetoothAdapterProperties: Setting state to 16
09-01 18:49:18.352  3523  3560 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-01 18:49:18.352  3523  3560 D BluetoothAdapterProperties: onBleDisable
,09-01 18:49:18.353  3523  3560 I BluetoothAdapterState: Entering PendingCommandState
09-01 18:49:18.353  3523  3561 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-01 18:49:18.354  3523  3571 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-01 18:49:18.354  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 18:49:18.354  3523  3571 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 18:49:18.356  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 18:49:18.356  3523  3565 D BluetoothAdapterProperties: Scan Mode:20
09-01 18:49:18.357  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 18:49:18.358  3580  3580 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-01 18:49:18.361  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 18:49:18.362  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 18:49:18.369  3580  3580 D DockEventReceiver: finishStartingService: stopping service
,09-01 18:49:18.558  3523  3565 I bt_hci  : shut_down
,09-01 18:49:18.558  3523  3569 D bt_hwcfg: hw_epilog_process
,09-01 18:49:18.560  3523  3569 I bt_vendor: low_power_mode_cb
,09-01 18:49:18.581  3523  3569 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-01 18:49:18.581  3523  3569 I bt_vendor: epilog_cb
,09-01 18:49:18.581  3523  3569 I bt_hci  : epilog_finished_callback
,09-01 18:49:18.591  3523  3565 I bt_hci_h4: hal_close
,09-01 18:49:18.593  3523  3565 I bt_userial_vendor: device fd = 51 close
,09-01 18:49:18.711  3523  3561 D bt_stack_manager: event_shut_down_stack finished.
,09-01 18:49:18.712  3523  3560 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-01 18:49:18.716  3523  3560 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-01 18:49:18.716  3523  3523 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-01 18:49:18.718  3523  3523 D BtGatt.GattService: Received stop request...Stopping profile...,
,09-01 18:49:18.718  3523  3523 D BtGatt.GattService: stop()
,09-01 18:49:18.718  3523  3523 D BtGatt.AdvertiseManager: advertise clients cleared
,09-01 18:49:18.722  3523  3523 V BluetoothAdapterState: isTurningOff()=false
,09-01 18:49:18.722  3523  3523 V BluetoothAdapterState: isTurningOn()=false
09-01 18:49:18.723  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
09-01 18:49:18.723  3523  3523 V BluetoothAdapterState: isBleTurningOff()=true
09-01 18:49:18.723  3523  3560 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-01 18:49:18.724  3523  3560 D BluetoothAdapterProperties: Setting state to 10
09-01 18:49:18.724  3523  3560 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-01 18:49:18.725  3523  3560 I BluetoothAdapterState: Entering OffState
09-01 18:49:18.726   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-01 18:49:18.756  3523  3523 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-01 18:49:18.756  3523  3523 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-01 18:49:18.757  3523  3561 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-01 18:49:18.762  3523  3561 D bt_stack_manager: event_clean_up_stack finished.
,09-01 18:49:18.762  3523  3523 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-01 18:49:18.777  3523  3523 I art     : System.exit called, status: 0
,09-01 18:49:18.778  3523  3523 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-01 18:49:18.846   874   884 I ActivityManager: Process com.android.bluetooth (pid 3523) has died
,09-01 18:49:19.472  3758  3786 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-01 18:49:19.541  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 18:49:19.548  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 18:49:19.549  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 18:49:19.573  1515  2058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-01 18:49:19.574  1515  2058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-01 18:49:19.574  1515  2058 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 18:49:19.574  1515  2058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 18:49:19.596  2727  2727 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-01 18:49:19.597  2727  2727 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-01 18:49:19.597  2727  2727 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-01 18:49:19.906   874  1924 I ActivityManager: Killing 2199:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-01 18:49:21.219   874  1313 D ConnectivityService: handlePromptUnvalidated 100
,09-01 18:49:21.328   874   891 I ActivityManager: Start proc 3868:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-01 18:49:21.443  3868  3868 D AdapterServiceConfig: Adding HeadsetService
,09-01 18:49:21.444  3868  3868 D AdapterServiceConfig: Adding A2dpService
09-01 18:49:21.444  3868  3868 D AdapterServiceConfig: Adding HidService
09-01 18:49:21.444  3868  3868 D AdapterServiceConfig: Adding HealthService
,09-01 18:49:21.445  3868  3868 D AdapterServiceConfig: Adding PanService
09-01 18:49:21.445  3868  3868 D AdapterServiceConfig: Adding GattService
,09-01 18:49:21.445  3868  3868 D AdapterServiceConfig: Adding BluetoothMapService
,09-01 18:49:21.467   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44add3d:true
09-01 18:49:21.467  3868  3868 D BluetoothAdapterState: make() - Creating AdapterState
,09-01 18:49:21.472  3868  3868 I bt_bluedroid: init
,09-01 18:49:21.473  3868  3880 I BluetoothAdapterState: Entering OffState
,09-01 18:49:21.475  3868  3881 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-01 18:49:21.475  3868  3881 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-01 18:49:21.475  3868  3881 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-01 18:49:21.475  3868  3881 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-01 18:49:21.480  3868  3868 I bt_bluedroid: get_profile_interface socket
,09-01 18:49:21.481  3868  3868 I bt_bluedroid: get_profile_interface sdp
,09-01 18:49:21.486  3868  3879 I bt_bluedroid: config_hci_snoop_log
,09-01 18:49:21.488  3868  3884 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-01 18:49:21.489   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-01 18:49:21.493  3868  3884 D BluetoothAdapterProperties: Name is: Nexus 6
,09-01 18:49:21.502  3868  3880 D BluetoothAdapterState: Current state: OFF, message: 0
09-01 18:49:21.502  3868  3880 D BluetoothAdapterProperties: Setting state to 14
09-01 18:49:21.502  3868  3880 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-01 18:49:21.505  3868  3880 D BluetoothBondStateMachine: make
,09-01 18:49:21.510  3868  3885 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-01 18:49:21.516  3868  3880 I BluetoothAdapterState: Entering PendingCommandState
,09-01 18:49:21.517  3868  3868 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-01 18:49:21.520  3868  3868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e4183
,09-01 18:49:21.520  3868  3868 D BtGatt.DebugUtils: handleDebugAction() action=null
09-01 18:49:21.521  3868  3868 D BtGatt.GattService: Received start request. Starting profile...
,09-01 18:49:21.521  3868  3868 D BtGatt.GattService: start()
09-01 18:49:21.521  3868  3868 I bt_bluedroid: get_profile_interface gatt
,09-01 18:49:21.523  3868  3868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e4183
09-01 18:49:21.523  3868  3868 D BtGatt.AdvertiseManager: advertise manager created
,09-01 18:49:21.534  3868  3868 V BluetoothAdapterState: isTurningOff()=false
09-01 18:49:21.534  3868  3868 V BluetoothAdapterState: isTurningOn()=false
,09-01 18:49:21.535  3868  3868 V BluetoothAdapterState: isBleTurningOn()=true
09-01 18:49:21.535  3868  3868 V BluetoothAdapterState: isBleTurningOff()=false
09-01 18:49:21.537  3868  3880 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-01 18:49:21.537  3868  3880 I bt_bluedroid: enable
09-01 18:49:21.538  3868  3881 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-01 18:49:21.538  3868  3881 I bt_hci  : start_up
,09-01 18:49:21.549  3868  3881 I bt_vendor: alloc value 0xb3a89189
09-01 18:49:21.549  3868  3881 I bt_vendor: init
,09-01 18:49:21.549  3868  3881 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-01 18:49:21.549  3868  3881 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-01 18:49:21.656  3868  3881 D bt_hci  : start_up starting async portion
,09-01 18:49:21.657  3868  3888 I bt_hci  : event_finish_startup
09-01 18:49:21.657  3868  3888 I bt_hci_h4: hal_open
09-01 18:49:21.658  3868  3888 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-01 18:49:21.666  3868  3888 I bt_userial_vendor: device fd = 51 open
,09-01 18:49:21.698  3868  3888 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-01 18:49:21.730  3868  3888 D bt_hwcfg: Chipset BCM4354A2
09-01 18:49:21.730  3868  3888 D bt_hwcfg: Target name = [BCM4354A2]
,09-01 18:49:21.731  3868  3888 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-01 18:49:22.393  3868  3888 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-01 18:49:22.396  3868  3888 D bt_hwcfg: Settlement delay -- 100 ms
09-01 18:49:22.397  3868  3888 I bt_hwcfg: Setting fw settlement delay to 100 
,09-01 18:49:22.513  3868  3888 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-01 18:49:22.514  3868  3888 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-01 18:49:22.543  3868  3888 I bt_hwcfg: vendor lib fwcfg completed
,09-01 18:49:22.543  3868  3888 I bt_vendor: firmware callback
09-01 18:49:22.544  3868  3888 I bt_hci  : firmware_config_callback
,09-01 18:49:22.555  3868  3890 I bt_btu  : btu_task pending for preload complete event
,09-01 18:49:22.555  3868  3890 I bt_btu_task: Bluetooth chip preload is complete
09-01 18:49:22.556  3868  3890 I bt_btu  : btu_task received preload complete event
,09-01 18:49:22.568  3868  3890 I         : BTE_InitTraceLevels -- TRC_HCI
,09-01 18:49:22.568  3868  3890 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-01 18:49:22.568  3868  3890 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-01 18:49:22.569  3868  3890 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-01 18:49:22.569  3868  3890 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-01 18:49:22.569  3868  3890 I         : BTE_InitTraceLevels -- TRC_A2D
09-01 18:49:22.570  3868  3890 I         : BTE_InitTraceLevels -- TRC_BNEP
09-01 18:49:22.571  3868  3890 I         : BTE_InitTraceLevels -- TRC_BTM
09-01 18:49:22.571  3868  3890 I         : BTE_InitTraceLevels -- TRC_GAP
09-01 18:49:22.571  3868  3890 I         : BTE_InitTraceLevels -- TRC_PAN
09-01 18:49:22.571  3868  3890 I         : BTE_InitTraceLevels -- TRC_SDP
,09-01 18:49:22.572  3868  3890 I         : BTE_InitTraceLevels -- TRC_GATT
09-01 18:49:22.572  3868  3890 I         : BTE_InitTraceLevels -- TRC_SMP
09-01 18:49:22.572  3868  3890 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-01 18:49:22.572  3868  3890 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-01 18:49:22.707  3868  3890 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3a06d9d
,09-01 18:49:22.708  3868  3890 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3a06d9d 
,09-01 18:49:22.735  3868  3884 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-01 18:49:22.738  3868  3884 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-01 18:49:22.738  3868  3884 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-01 18:49:22.739  3868  3884 D BluetoothAdapterProperties: Name is: Nexus 6
09-01 18:49:22.741  3868  3884 D BluetoothAdapterProperties: Scan Mode:20
09-01 18:49:22.741  3868  3884 D BluetoothAdapterProperties: Discoverable Timeout:120
09-01 18:49:22.741  3868  3884 D bt_hci  : do_postload posting postload work item
,09-01 18:49:22.742  3868  3888 I bt_hci  : event_postload
09-01 18:49:22.742  3868  3888 I bt_vendor: sco_config_cb
09-01 18:49:22.742  3868  3888 I bt_hci  : sco_config_callback postload finished.
09-01 18:49:22.743  3868  3884 D bt_bte_conf: Device ID record 1 : primary
09-01 18:49:22.744  3868  3884 D bt_bte_conf:   vendorId            = 000f
09-01 18:49:22.744  3868  3884 D bt_bte_conf:   vendorIdSource      = 0001
09-01 18:49:22.744  3868  3884 D bt_bte_conf:   product             = 1200
09-01 18:49:22.744  3868  3884 D bt_bte_conf:   version             = 1436
09-01 18:49:22.744  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 18:49:22.745  3868  3884 D bt_bte_conf:   clientExecutableURL = 
09-01 18:49:22.745  3868  3884 D bt_bte_conf:   serviceDescription  = 
09-01 18:49:22.745  3868  3884 D bt_bte_conf:   documentationURL    = 
09-01 18:49:22.745  3868  3884 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-01 18:49:22.746  3868  3881 D bt_stack_manager: event_start_up_stack finished
,09-01 18:49:22.747  3868  3880 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-01 18:49:22.747  3868  3880 D BluetoothAdapterProperties: Setting state to 15
09-01 18:49:22.748  3868  3880 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-01 18:49:22.748  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 18:49:22.749  3868  3880 I BluetoothAdapterState: Entering BleOnState
09-01 18:49:22.751  3868  3888 I bt_vendor: low_power_mode_cb
,09-01 18:49:22.753  3868  3880 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-01 18:49:22.754  3868  3880 D BluetoothAdapterProperties: Setting state to 11
09-01 18:49:22.754  3868  3880 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-01 18:49:22.762  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 18:49:22.766  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 18:49:22.774  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 18:49:22.775  3868  3868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e4183
,09-01 18:49:22.776  3868  3868 D HeadsetService: Received start request. Starting profile...
,09-01 18:49:22.779  3868  3868 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-01 18:49:22.779  3868  3868 D HeadsetStateMachine: make
,09-01 18:49:22.785  3868  3880 I BluetoothAdapterState: Entering PendingCommandState
,09-01 18:49:22.788  3868  3868 D HeadsetStateMachine: max_hf_connections = 1
,09-01 18:49:22.788  3868  3868 I bt_bluedroid: get_profile_interface handsfree
09-01 18:49:22.789  3868  3884 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-01 18:49:22.789  3868  3884 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-01 18:49:22.792  3868  3868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e4183
,09-01 18:49:22.793  3868  3868 D A2dpService: Received start request. Starting profile...
,09-01 18:49:22.793  3868  3868 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-01 18:49:22.794  3868  3868 I bt_bluedroid: get_profile_interface avrcp
,09-01 18:49:22.799  3868  3868 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-01 18:49:22.799  3868  3868 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-01 18:49:22.799  3868  3868 D A2dpStateMachine: make
,09-01 18:49:22.800  3868  3868 I bt_bluedroid: get_profile_interface a2dp
09-01 18:49:22.800  3868  3884 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-01 18:49:22.802  3868  3899 D A2dpStateMachine: Enter Disconnected: -2
,09-01 18:49:22.804  3868  3868 I BluetoothHidServiceJni: classInitNative: succeeds
09-01 18:49:22.805  3868  3868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e4183
,09-01 18:49:22.806  3868  3868 D HidService: Received start request. Starting profile...
,09-01 18:49:22.806  3868  3868 I bt_bluedroid: get_profile_interface hidhost
09-01 18:49:22.806  3868  3868 D HidService: setHidService(): set to: null
09-01 18:49:22.806  3868  3884 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39e83e5
09-01 18:49:22.806  3868  3884 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-01 18:49:22.806  3868  3868 I BluetoothHealthServiceJni: classInitNative: succeeds
09-01 18:49:22.807  3868  3868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e4183
,09-01 18:49:22.808  3868  3868 D HealthService: Received start request. Starting profile...
,09-01 18:49:22.811  3868  3868 I bt_bluedroid: get_profile_interface health
,09-01 18:49:22.811  3868  3868 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-01 18:49:22.814  3868  3868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e4183
09-01 18:49:22.815  3868  3868 D PanService: Received start request. Starting profile...
,09-01 18:49:22.815  3868  3868 D BluetoothPanServiceJni: initializeNative(L110): pan
09-01 18:49:22.815  3868  3868 I bt_bluedroid: get_profile_interface pan
09-01 18:49:22.816  3868  3884 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-01 18:49:22.818  3868  3868 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54e4183
,09-01 18:49:22.819  3868  3868 D BluetoothMapService: Received start request. Starting profile...
09-01 18:49:22.819  3868  3868 D BluetoothMapService: start()
09-01 18:49:22.821  3868  3868 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-01 18:49:22.822  3868  3868 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-01 18:49:22.822  3868  3868 D BluetoothMapAppObserver: createReceiver()
,09-01 18:49:22.823  3868  3868 D BluetoothMapAppObserver: initObservers()
09-01 18:49:22.823  3868  3868 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-01 18:49:22.834  3868  3897 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-01 18:49:22.834  3868  3868 V BluetoothAdapterState: isTurningOff()=false
09-01 18:49:22.834  3868  3868 V BluetoothAdapterState: isTurningOn()=true
09-01 18:49:22.834  3868  3868 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 18:49:22.834  3868  3868 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 18:49:22.836  3868  3868 V BluetoothAdapterState: isTurningOff()=false
09-01 18:49:22.836  3868  3868 V BluetoothAdapterState: isTurningOn()=true
09-01 18:49:22.836  3868  3868 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 18:49:22.836  3868  3868 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 18:49:22.836  3868  3868 V BluetoothAdapterState: isTurningOff()=false
09-01 18:49:22.836  3868  3868 V BluetoothAdapterState: isTurningOn()=true
,09-01 18:49:22.837  3868  3868 V BluetoothAdapterState: isBleTurningOn()=false
09-01 18:49:22.837  3868  3868 V BluetoothAdapterState: isBleTurningOff()=false
09-01 18:49:22.837  3868  3868 V BluetoothAdapterState: isTurningOff()=false
,09-01 18:49:22.837  3868  3868 V BluetoothAdapterState: isTurningOn()=true
,09-01 18:49:22.837  3868  3868 V BluetoothAdapterState: isBleTurningOn()=false
09-01 18:49:22.837  3868  3868 V BluetoothAdapterState: isBleTurningOff()=false
09-01 18:49:22.837  3868  3868 V BluetoothAdapterState: isTurningOff()=false
09-01 18:49:22.837  3868  3868 V BluetoothAdapterState: isTurningOn()=true
,09-01 18:49:22.837  3868  3868 V BluetoothAdapterState: isBleTurningOn()=false
09-01 18:49:22.837  3868  3868 V BluetoothAdapterState: isBleTurningOff()=false
09-01 18:49:22.837  3868  3868 V BluetoothAdapterState: isTurningOff()=false
09-01 18:49:22.838  3868  3868 V BluetoothAdapterState: isTurningOn()=true
09-01 18:49:22.838  3868  3868 V BluetoothAdapterState: isBleTurningOn()=false
09-01 18:49:22.838  3868  3868 V BluetoothAdapterState: isBleTurningOff()=false
09-01 18:49:22.838  3868  3880 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-01 18:49:22.838  3868  3880 D BluetoothAdapterProperties: ScanMode =  20
09-01 18:49:22.839  3868  3880 D BluetoothAdapterProperties: State =  11
09-01 18:49:22.839  3868  3884 D BluetoothAdapterProperties: Scan Mode:21
09-01 18:49:22.840  3868  3884 D BluetoothAdapterProperties: Discoverable Timeout:120
09-01 18:49:22.841  3868  3880 D BluetoothAdapterProperties: Setting state to 12
09-01 18:49:22.841  3868  3880 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-01 18:49:22.841  3868  3880 I BluetoothAdapterState: Entering OnState
,09-01 18:49:22.841  3580  3590 D BluetoothPbap: onBluetoothStateChange: up=true
09-01 18:49:22.844  1357  2088 D BluetoothPbap: onBluetoothStateChange: up=true
09-01 18:49:22.844  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 18:49:22.844  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 18:49:22.844  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 18:49:22.844  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 18:49:22.844  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 18:49:22.844  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 18:49:22.844  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 18:49:22.844  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 18:49:22.846  3580  3861 D BluetoothMap: onBluetoothStateChange: up=true
,09-01 18:49:22.846  3464  3464 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 18:49:22.849  1357  1369 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-01 18:49:22.851  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 18:49:22.851  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 18:49:22.851  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 18:49:22.851  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 18:49:22.851  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 18:49:22.851  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 18:49:22.851  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 18:49:22.851  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 18:49:22.852  3868  3868 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-01 18:49:22.852  3868  3868 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-01 18:49:22.852  3580  3590 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 18:49:22.853  1357  1368 D BluetoothPan: onBluetoothStateChange on: true
09-01 18:49:22.854  3868  3868 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 18:49:22.854  3464  3464 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 18:49:22.857  3580  3861 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-01 18:49:22.857  3580  3580 D BluetoothMap: Proxy object connected
,09-01 18:49:22.857  3868  3868 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 18:49:22.857  3580  3580 D MapProfile: Bluetooth service connected
09-01 18:49:22.857  3580  3580 D BluetoothMap: getConnectedDevices()
09-01 18:49:22.859  3868  3868 D ObexServerSockets: Succeed to create listening sockets 
09-01 18:49:22.859  3868  3868 D ObexServerSockets0: startAccept()
09-01 18:49:22.859  3868  3868 D ObexServerSockets0: prepareForNewConnect()
09-01 18:49:22.859  1357  2088 D BluetoothMap: onBluetoothStateChange: up=true
,09-01 18:49:22.861   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 18:49:22.861  1357  1357 D BluetoothMap: Proxy object connected
09-01 18:49:22.861  1357  1357 D MapProfile: Bluetooth service connected
09-01 18:49:22.861  1357  1357 D BluetoothMap: getConnectedDevices()
,09-01 18:49:22.862   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 18:49:22.862  3868  3868 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-01 18:49:22.862  1962  1981 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 18:49:22.862  3868  3868 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-01 18:49:22.863   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 18:49:22.863   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 18:49:22.864  3580  3592 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 18:49:22.864  3868  3904 D ObexServerSockets0: Accepting socket connection...
09-01 18:49:22.865  3868  3905 D ObexServerSockets0: Accepting socket connection...
,09-01 18:49:22.866  3580  3580 D BluetoothInputDevice: Proxy object connected
,09-01 18:49:22.867  1357  1357 D BluetoothInputDevice: Proxy object connected
09-01 18:49:22.867  1357  1357 D HidProfile: Bluetooth service connected
09-01 18:49:22.867  1357  1369 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 18:49:22.868   874   874 D BluetoothA2dp: Proxy object connected
09-01 18:49:22.867  3580  3580 D HidProfile: Bluetooth service connected
09-01 18:49:22.868  1357  1368 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 18:49:22.870  1357  1357 D BluetoothPan: BluetoothPAN Proxy object connected
,09-01 18:49:22.870  1357  1357 D PanProfile: Bluetooth service connected
09-01 18:49:22.870  1357  1357 D BluetoothA2dp: Proxy object connected
09-01 18:49:22.871  3580  3590 D BluetoothPan: onBluetoothStateChange on: true
09-01 18:49:22.874  3580  3580 D BluetoothA2dp: Proxy object connected
,09-01 18:49:22.875  3868  3868 D BluetoothMapService: onReceive
09-01 18:49:22.876  3868  3868 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-01 18:49:22.876  3868  3868 D BluetoothMapService: STATE_ON
09-01 18:49:22.877   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-01 18:49:22.878  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 18:49:22.878  3580  3580 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 18:49:22.878  3580  3580 D PanProfile: Bluetooth service connected
09-01 18:49:22.880  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 18:49:22.884  3580  3580 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 18:49:22.892  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 18:49:22.893  3580  3580 D DockEventReceiver: finishStartingService: stopping service
,09-01 18:49:22.906  1357  1357 D BluetoothPbap: Proxy object connected
,09-01 18:49:22.906  1357  1357 D PbapServerProfile: Bluetooth service connected
09-01 18:49:22.906  3868  3868 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-01 18:49:22.906  3868  3868 D ObexServerSockets0: prepareForNewConnect()
,09-01 18:49:22.909  3580  3580 D BluetoothPbap: Proxy object connected
09-01 18:49:22.909  3580  3580 D PbapServerProfile: Bluetooth service connected
,09-01 18:49:22.919  3868  3911 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 18:49:22.938  3868  3915 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 18:49:22.939  3868  3915 I BtOppRfcommListener: Accept thread started.
,09-01 18:49:22.955  3580  3861 D BluetoothHeadset: Proxy object connected
,09-01 18:49:22.955   874   874 D BluetoothHeadset: Proxy object connected
,09-01 18:49:22.955  3580  3580 D HeadsetProfile: Bluetooth service connected
09-01 18:49:22.955   874   874 D BluetoothHeadset: Proxy object connected
09-01 18:49:22.956  1962  2316 D BluetoothHeadset: Proxy object connected
,09-01 18:49:22.956  1357  2088 D BluetoothHeadset: Proxy object connected
09-01 18:49:22.957  1357  1357 D HeadsetProfile: Bluetooth service connected
09-01 18:49:22.957   874   874 D BluetoothHeadset: Proxy object connected
,09-01 18:49:22.962   874   891 D BluetoothHeadset: Proxy object connected
,09-01 18:49:22.963  1962  2170 D BluetoothHeadset: Proxy object connected
,09-01 18:49:22.964   874   891 D BluetoothHeadset: Proxy object connected
,09-01 18:49:22.964   874   891 D BluetoothHeadset: Proxy object connected
,09-01 18:49:22.968  1357  1368 D BluetoothHeadset: Proxy object connected
,09-01 18:49:22.968  1357  1357 D HeadsetProfile: Bluetooth service connected
,09-01 18:49:24.276  3464  3512 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 18:49:24.277  3464  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 18:49:24.514  2727  2738 D Finsky  : [173] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,09-01 18:49:24.530  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 18:49:24.592  1515  3640 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-01 18:49:24.592  1515  3640 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-01 18:49:24.593  1515  3640 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 18:49:24.594  1515  3640 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 18:49:24.648  2727  2738 D Finsky  : [173] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,09-01 18:49:26.904   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-01 18:49:26.915  1877  1877 I Keyboard.Facilitator: onFinishInput()
,09-01 18:49:26.931   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-01 18:49:26.931   874   894 I Adreno  : Build Date                       : 10/20/15
09-01 18:49:26.931   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-01 18:49:26.931   874   894 I Adreno  : Local Branch                     : M14
09-01 18:49:26.931   874   894 I Adreno  : Remote Branch                    : 
09-01 18:49:26.931   874   894 I Adreno  : Remote Branch                    : 
09-01 18:49:26.931   874   894 I Adreno  : Reconstruct Branch               : 
,09-01 18:49:26.981   281   367 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (335 us)
,09-01 18:49:27.284  3464  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 18:49:27.288  3464  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ac3d4f9 added. We now have 6 listener(s)
09-01 18:49:27.288  3464  3512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 18:49:27.295  3464  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 18:49:27.298  3464  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1dbbc3e added. We now have 7 listener(s)
09-01 18:49:27.298  3464  3512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 18:49:27.302  3464  3512 I System.out: IsBluetoothEnabled
,09-01 18:49:27.311  3868  3880 D BluetoothAdapterState: Current state: ON, message: 23
,09-01 18:49:27.313  3868  3880 D BluetoothAdapterProperties: Setting state to 13
09-01 18:49:27.314  3868  3880 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-01 18:49:27.316  3868  3880 D BluetoothAdapterProperties: onBluetoothDisable()
,09-01 18:49:27.321  3868  3880 I BluetoothAdapterState: Entering PendingCommandState
09-01 18:49:27.323  3868  3884 D BluetoothAdapterProperties: Scan Mode:20
09-01 18:49:27.324  3868  3880 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-01 18:49:27.327  3868  3868 D HeadsetService: Received stop request...Stopping profile...
09-01 18:49:27.326  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:49:27.330  3464  3512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 18:49:27.330  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 18:49:27.330  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 18:49:27.330  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 18:49:27.330  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 18:49:27.330  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 18:49:27.330  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 18:49:27.330  3464  3512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 18:49:27.337  3868  3868 D A2dpService: Received stop request...Stopping profile...,
09-01 18:49:27.336  3464  3464 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:49:27.338  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 18:49:27.338  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 18:49:27.338  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 18:49:27.338  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 18:49:27.338  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 18:49:27.338  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 18:49:27.338  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 18:49:27.338  3464  3464 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 18:49:27.338  3868  3899 D A2dpStateMachine: Exit Disconnected: -1
09-01 18:49:27.336  3580  3590 D BluetoothHeadset: Proxy object disconnected
09-01 18:49:27.340   874   874 D BluetoothHeadset: Proxy object disconnected
09-01 18:49:27.340   874   874 D BluetoothHeadset: Proxy object disconnected
09-01 18:49:27.342  1357  1357 D BluetoothA2dp: Proxy object disconnected
09-01 18:49:27.343  1962  1980 D BluetoothHeadset: Proxy object disconnected
09-01 18:49:27.343  3580  3580 D HeadsetProfile: Bluetooth service disconnected
09-01 18:49:27.344  3464  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:49:27.345  3464  3512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 18:49:27.345  1357  2088 D BluetoothHeadset: Proxy object disconnected
09-01 18:49:27.345  1357  1357 D HeadsetProfile: Bluetooth service disconnected
09-01 18:49:27.345   874   874 D BluetoothHeadset: Proxy object disconnected
09-01 18:49:27.345  3868  3868 V BluetoothAdapterState: isTurningOff()=true
09-01 18:49:27.345  3868  3868 V BluetoothAdapterState: isTurningOn()=false
09-01 18:49:27.345   874   874 D BluetoothA2dp: Proxy object disconnected
09-01 18:49:27.345  3868  3868 V BluetoothAdapterState: isBleTurningOn()=false
09-01 18:49:27.345  3868  3868 V BluetoothAdapterState: isBleTurningOff()=false
09-01 18:49:27.346  3580  3580 D BluetoothA2dp: Proxy object disconnected
,09-01 18:49:27.347  3868  3868 D HidService: Received stop request...Stopping profile...
09-01 18:49:27.347  3868  3868 D HidService: Stopping Bluetooth HidService
09-01 18:49:27.348  3580  3580 D BluetoothInputDevice: Proxy object disconnected
,09-01 18:49:27.348  3580  3580 D HidProfile: Bluetooth service disconnected
,09-01 18:49:27.348  1357  1357 D BluetoothInputDevice: Proxy object disconnected
09-01 18:49:27.348  1357  1357 D HidProfile: Bluetooth service disconnected
,09-01 18:49:27.349  3464  3464 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 18:49:27.349  3464  3464 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 18:49:27.352  3868  3868 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-01 18:49:27.352  3868  3884 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-01 18:49:27.352  3868  3868 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 18:49:27.352  3868  3868 V BluetoothAdapterState: isTurningOff()=true
09-01 18:49:27.353  3868  3868 V BluetoothAdapterState: isTurningOn()=false
09-01 18:49:27.353  3868  3868 V BluetoothAdapterState: isBleTurningOn()=false
09-01 18:49:27.353  3868  3868 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 18:49:27.352  3868  3890 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-01 18:49:27.357  3868  3890 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 18:49:27.357  3868  3890 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 18:49:27.357  3868  3884 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-01 18:49:27.357  3868  3884 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-01 18:49:27.358  3868  3890 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-01 18:49:27.358  3868  3890 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 18:49:27.358  3868  3890 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 18:49:27.358  3868  3890 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 18:49:27.358  3868  3890 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 18:49:27.358  3868  3890 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 18:49:27.359  3868  3868 D HealthService: Received stop request...Stopping profile...
,09-01 18:49:27.361  3868  3868 D PanService: Received stop request...Stopping profile...
,09-01 18:49:27.362  1357  1357 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-01 18:49:27.363  1357  1357 D PanProfile: Bluetooth service disconnected
09-01 18:49:27.363  3868  3868 V BluetoothAdapterState: isTurningOff()=true
09-01 18:49:27.363  3580  3580 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-01 18:49:27.363  3868  3868 V BluetoothAdapterState: isTurningOn()=false
09-01 18:49:27.363  3868  3868 V BluetoothAdapterState: isBleTurningOn()=false
09-01 18:49:27.363  3580  3580 D PanProfile: Bluetooth service disconnected
09-01 18:49:27.363  3868  3868 V BluetoothAdapterState: isBleTurningOff()=false
09-01 18:49:27.364  3868  3868 D BluetoothMapService: Received stop request...Stopping profile...
09-01 18:49:27.364  3868  3868 D BluetoothMapService: stop()
,09-01 18:49:27.366  3868  3880 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-01 18:49:27.366  3868  3880 I BluetoothAdapterState: Deferring BLE_TURN_ON request...
09-01 18:49:27.366  3868  3868 D BluetoothMapAppObserver: deinitObservers()
,09-01 18:49:27.368  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 18:49:27.366  3868  3868 D BluetoothMapAppObserver: removeReceiver()
09-01 18:49:27.370  3580  3580 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-01 18:49:27.370  3868  3868 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-01 18:49:27.370  3868  3868 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-01 18:49:27.370  3868  3868 V BluetoothAdapterState: isTurningOff()=true
09-01 18:49:27.371  3868  3868 V BluetoothAdapterState: isTurningOn()=false
09-01 18:49:27.371  3868  3868 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 18:49:27.371  3868  3868 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 18:49:27.371  3868  3868 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-01 18:49:27.371  3868  3884 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-01 18:49:27.371  3868  3884 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-01 18:49:27.372  1357  1357 D BluetoothMap: Proxy object disconnected
09-01 18:49:27.373  1357  1357 D MapProfile: Bluetooth service disconnected
,09-01 18:49:27.373  3868  3868 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-01 18:49:27.374  3868  3868 V BluetoothAdapterState: isTurningOff()=true
09-01 18:49:27.374  3868  3868 V BluetoothAdapterState: isTurningOn()=false
09-01 18:49:27.374  3868  3868 V BluetoothAdapterState: isBleTurningOn()=false
09-01 18:49:27.374  3868  3868 V BluetoothAdapterState: isBleTurningOff()=false
09-01 18:49:27.374  3868  3868 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-01 18:49:27.374  3868  3868 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-01 18:49:27.376  3868  3868 D BluetoothMapService: MAP Service closeService in
,09-01 18:49:27.376  3868  3868 D BluetoothMapMasInstance0: MAP Service shutdown
,09-01 18:49:27.376  3868  3868 D ObexServerSockets0: shutdown(block = true)
,09-01 18:49:27.376  3868  3904 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-01 18:49:27.377  3868  3868 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-01 18:49:27.378  3868  3892 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-01 18:49:27.378  3868  3868 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-01 18:49:27.378  3868  3905 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-01 18:49:27.378  3868  3868 V BluetoothAdapterState: isTurningOff()=true
,09-01 18:49:27.378  3868  3868 V BluetoothAdapterState: isTurningOn()=false
,09-01 18:49:27.378  3580  3580 D BluetoothMap: Proxy object disconnected
09-01 18:49:27.378  3868  3868 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 18:49:27.378  3580  3580 D MapProfile: Bluetooth service disconnected
09-01 18:49:27.378  3868  3868 V BluetoothAdapterState: isBleTurningOff()=false
09-01 18:49:27.379  3868  3880 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-01 18:49:27.379  3868  3880 D BluetoothAdapterProperties: Setting state to 15
09-01 18:49:27.379  3868  3880 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-01 18:49:27.379  3868  3880 I BluetoothAdapterState: Entering BleOnState
09-01 18:49:27.379  3868  3880 D BluetoothAdapterState: Current state: BLE ON, message: 0
09-01 18:49:27.380  3580  3592 D BluetoothPbap: onBluetoothStateChange: up=false,
09-01 18:49:27.380  3868  3868 D BluetoothMapService: cleanup()
09-01 18:49:27.380  3868  3868 D BluetoothMapService: MAP Service closeService in
,09-01 18:49:27.381  1357  1368 D BluetoothPbap: onBluetoothStateChange: up=false
09-01 18:49:27.383  3580  3590 D BluetoothMap: onBluetoothStateChange: up=false
,09-01 18:49:27.383  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 18:49:27.383  1357  1369 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-01 18:49:27.385  3868  3868 I BtOppRfcommListener: stopping Accept Thread
,09-01 18:49:27.385  3868  3915 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-01 18:49:27.385  3580  3861 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 18:49:27.386  1357  2088 D BluetoothPan: onBluetoothStateChange on: false
09-01 18:49:27.386  3868  3915 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-01 18:49:27.386  3580  3592 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-01 18:49:27.387  1357  1368 D BluetoothMap: onBluetoothStateChange: up=false
09-01 18:49:27.391   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 18:49:27.392   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-01 18:49:27.392  1962  1981 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 18:49:27.392   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 18:49:27.392   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 18:49:27.392  3580  3590 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-01 18:49:27.393  1357  1369 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 18:49:27.393  1357  2088 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-01 18:49:27.393  3580  3861 D BluetoothPan: onBluetoothStateChange on: false
09-01 18:49:27.394  3868  3880 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-01 18:49:27.394  3868  3880 D BluetoothAdapterProperties: Setting state to 16
,09-01 18:49:27.395  3868  3880 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-01 18:49:27.395  3868  3880 D BluetoothAdapterProperties: onBleDisable
09-01 18:49:27.395  3868  3880 I BluetoothAdapterState: Entering PendingCommandState
,09-01 18:49:27.396  3868  3881 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-01 18:49:27.397  3868  3884 D BluetoothAdapterProperties: Scan Mode:20
09-01 18:49:27.397  3868  3890 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-01 18:49:27.397  3868  3890 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-01 18:49:27.398  3580  3580 D DockEventReceiver: finishStartingService: stopping service
09-01 18:49:27.400  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 18:49:27.401  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 18:49:27.402  3580  3580 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 18:49:27.407  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 18:49:27.422  3580  3580 D DockEventReceiver: finishStartingService: stopping service
,09-01 18:49:27.604  3868  3884 I bt_hci  : shut_down
,09-01 18:49:27.604  3868  3888 D bt_hwcfg: hw_epilog_process
,09-01 18:49:27.616  3464  3464 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-01 18:49:27.616  3464  3464 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-01 18:49:27.663  3868  3888 I bt_vendor: low_power_mode_cb
,09-01 18:49:27.664   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-01 18:49:27.665  3464  3464 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@62972df Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3de3a9f, 16908290=android.view.AbsSavedState$1@3de3a9f}, android:focusedViewId=100}]}]
,09-01 18:49:27.665  3464  3464 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-01 18:49:27.667  3464  3464 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-01 18:49:27.667  3464  3464 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-01 18:49:27.677   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-01 18:49:27.682   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-01 18:49:27.682   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
09-01 18:49:27.684   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
09-01 18:49:27.686  3868  3888 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-01 18:49:27.686  3868  3888 I bt_vendor: epilog_cb
09-01 18:49:27.686  3868  3888 I bt_hci  : epilog_finished_callback
09-01 18:49:27.688  3868  3884 I bt_hci_h4: hal_close
,09-01 18:49:27.688  3868  3884 I bt_userial_vendor: device fd = 51 close
,09-01 18:49:27.801  3868  3881 D bt_stack_manager: event_shut_down_stack finished.
,09-01 18:49:27.802  3868  3880 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-01 18:49:27.803  3868  3880 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-01 18:49:27.803  3868  3868 D BtGatt.DebugUtils: handleDebugAction() action=null
09-01 18:49:27.804  3868  3868 D BtGatt.GattService: Received stop request...Stopping profile...
09-01 18:49:27.804  3868  3868 D BtGatt.GattService: stop()
09-01 18:49:27.804  3868  3868 D BtGatt.AdvertiseManager: advertise clients cleared
,09-01 18:49:27.805  3868  3868 V BluetoothAdapterState: isTurningOff()=false
09-01 18:49:27.805  3868  3868 V BluetoothAdapterState: isTurningOn()=false
09-01 18:49:27.805  3868  3868 V BluetoothAdapterState: isBleTurningOn()=false
09-01 18:49:27.805  3868  3868 V BluetoothAdapterState: isBleTurningOff()=true
09-01 18:49:27.805  3868  3880 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-01 18:49:27.805  3868  3880 D BluetoothAdapterProperties: Setting state to 10
09-01 18:49:27.806  3868  3880 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-01 18:49:27.806  3868  3880 I BluetoothAdapterState: Entering OffState
,09-01 18:49:27.818  3580  3580 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-01 18:49:27.819  3464  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 18:49:27.823  3580  3580 D DockEventReceiver: finishStartingService: stopping service
,09-01 18:49:27.826  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 18:49:27.925   281   344 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-01 18:49:27.929   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-01 18:49:27.935   874  1337 D SurfaceControl: Excessive delay in setPowerMode(): 253ms
,09-01 18:49:27.941   874   894 I DreamManagerService: Entering dreamland.
,09-01 18:49:27.942   874   894 I PowerManagerService: Dozing...
,09-01 18:49:27.943   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-01 18:49:28.001   377   377 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-01 18:49:28.002   377   377 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-01 18:49:28.006   874  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 18:49:28.010   874  1311 E native  : do suspend false
,09-01 18:49:28.024  1950  3932 D NfcService: Discovery configuration equal, not updating.
,09-01 18:49:28.047   874  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 18:49:28.051   874  1311 E native  : do suspend true
,09-01 18:49:28.140   377  1284 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-01 18:49:28.141   377  1284 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-01 18:49:32.822  2076  2509 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-01 18:49:45.645  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 18:49:45.663  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 18:49:45.669  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 18:49:45.746  1515  3213 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-01 18:49:45.746  1515  3213 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-01 18:49:45.747  1515  3213 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 18:49:45.747  1515  3213 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 18:49:45.803  2727  2727 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-01 18:49:45.803  2727  2727 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-01 18:49:45.803  2727  2727 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-01 18:50:15.458   874  1313 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,09-01 18:50:17.763  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 18:50:17.777  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 18:50:17.782  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 18:50:17.836  1515  2058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-01 18:50:17.836  1515  2058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-01 18:50:17.837  1515  2058 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 18:50:17.837  1515  2058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 18:50:17.888  2727  2727 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-01 18:50:17.889  2727  2727 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-01 18:50:17.890  2727  2727 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-01 18:50:26.957  1877  1946 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-01 18:50:26.957  1877  1946 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-01 18:50:27.011  1515  1515 I ConfigService: onCreate
,09-01 18:50:32.096  1515  1515 I ConfigService: onDestroy
,09-01 18:50:38.276  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 18:50:38.285  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 18:50:38.289  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 18:50:38.323  1515  3640 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-01 18:50:38.323  1515  3640 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-01 18:50:38.323  1515  3640 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 18:50:38.323  1515  3640 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 18:50:38.357  2727  2727 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-01 18:50:38.358  2727  2727 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-01 18:50:38.358  2727  2727 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-01 18:51:14.198  1515  2177 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-01 18:52:27.806  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 18:52:27.819  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 18:52:27.823  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 18:52:27.875  1515  3213 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-01 18:52:27.875  1515  3213 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-01 18:52:27.875  1515  3213 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 18:52:27.875  1515  3213 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 18:52:27.907  1515  3213 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-01 18:52:27.907  1515  3213 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-01 18:52:27.907  1515  3213 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-01 18:52:27.907  1515  3213 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-01 18:52:27.907  1515  3213 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-01 18:52:27.907  1515  3213 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-01 18:52:27.907  1515  3213 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-01 18:52:27.924  2727  2756 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-01 18:52:27.924  2727  2756 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-01 18:52:27.924  2727  2756 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-01 18:52:27.924  2727  2756 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-01 18:52:27.924  2727  2756 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-01 18:52:27.924  2727  2756 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-01 18:52:27.924  2727  2756 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-01 18:57:28.072  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 18:57:28.097  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 18:57:28.105  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 18:57:28.213  1515  2404 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-01 18:57:28.213  1515  2404 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-01 18:57:28.214  1515  2404 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-01 18:57:28.214  1515  2404 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 18:57:28.265  1515  2404 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-01 18:57:28.265  1515  2404 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-01 18:57:28.265  1515  2404 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-01 18:57:28.265  1515  2404 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-01 18:57:28.265  1515  2404 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-01 18:57:28.265  1515  2404 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-01 18:57:28.265  1515  2404 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-01 18:57:28.280  2727  2756 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-01 18:57:28.280  2727  2756 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-01 18:57:28.280  2727  2756 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-01 18:57:28.280  2727  2756 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-01 18:57:28.280  2727  2756 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-01 18:57:28.280  2727  2756 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-01 18:57:28.280  2727  2756 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-01 19:02:28.420  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 19:02:28.436  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 19:02:28.441  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 19:02:28.532  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-01 19:02:28.533  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-01 19:02:28.533  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-01 19:02:28.534  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 19:02:28.585  1515  1526 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-01 19:02:28.585  1515  1526 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-01 19:02:28.585  1515  1526 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-01 19:02:28.585  1515  1526 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-01 19:02:28.585  1515  1526 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-01 19:02:28.585  1515  1526 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-01 19:02:28.585  1515  1526 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-01 19:02:28.601  2727  2756 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-01 19:02:28.601  2727  2756 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-01 19:02:28.601  2727  2756 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-01 19:02:28.601  2727  2756 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-01 19:02:28.601  2727  2756 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-01 19:02:28.601  2727  2756 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-01 19:02:28.601  2727  2756 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-01 19:07:15.501   874   886 I UsageStatsService: User[0] Flushing usage stats to disk
,09-01 19:07:28.733  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 19:07:28.752  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 19:07:28.757  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 19:07:28.825  1515  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-01 19:07:28.826  1515  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-01 19:07:28.826  1515  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 19:07:28.826  1515  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 19:07:28.852  1515  1525 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-01 19:07:28.852  1515  1525 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-01 19:07:28.852  1515  1525 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-01 19:07:28.852  1515  1525 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-01 19:07:28.852  1515  1525 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-01 19:07:28.852  1515  1525 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-01 19:07:28.852  1515  1525 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-01 19:07:28.862  2727  2756 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-01 19:07:28.862  2727  2756 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-01 19:07:28.862  2727  2756 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-01 19:07:28.862  2727  2756 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-01 19:07:28.862  2727  2756 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-01 19:07:28.862  2727  2756 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-01 19:07:28.862  2727  2756 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,TIME-OUT KILL (timeout was 1400000ms),09-01 19:12:27.247  4025  4025 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-01 19:12:27.251  4025  4025 D AndroidRuntime: CheckJNI is OFF
09-01 19:12:27.288  4025  4025 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-01 19:12:27.330  4025  4025 I Radio-JNI: register_android_hardware_Radio DONE
09-01 19:12:27.350  4025  4025 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-01 19:12:27.363   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-01 19:12:27.364   874   887 I ActivityManager: Killing 3464:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-01 19:12:27.456   874  1969 D GraphicsStats: Buffer count: 2
09-01 19:12:27.456   874  1988 I WindowState: WIN DEATH: Window{4bc1d08 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-01 19:12:27.457   874  1312 D WifiService: Client connection lost with reason: 4
09-01 19:12:27.486   874   897 W PackageSettings: Skipping PackageSetting{bd41be4 com.example.hello/10273} due to missing metadata
09-01 19:12:27.516   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-01 19:12:27.517   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-01 19:12:27.519   874   897 I art     : Starting a blocking GC Explicit
09-01 19:12:27.525   874   887 E ActivityManager: Failure starting process com.test.thalitest
09-01 19:12:27.525   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-01 19:12:27.525   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-01 19:12:27.525   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-01 19:12:27.525   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-01 19:12:27.525   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-01 19:12:27.525   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-01 19:12:27.525   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-01 19:12:27.525   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-01 19:12:27.525   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-01 19:12:27.525   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-01 19:12:27.525   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-01 19:12:27.525   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-01 19:12:27.525   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-01 19:12:27.525   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-01 19:12:27.525   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-01 19:12:27.525   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 19:12:27.525   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-01 19:12:27.525   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 19:12:27.525   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-01 19:12:27.526   874   887 I ActivityManager:   Force finishing activity ActivityRecord{8951289 u0 com.test.thalitest/.MainActivity t2}
09-01 19:12:27.536   874  1529 W ActivityManager: Spurious death for ProcessRecord{3a6d04b 0:com.test.thalitest/u0a0}, curProc for 3464: null
09-01 19:12:27.580   874   897 I art     : Explicit concurrent mark sweep GC freed 50796(3MB) AllocSpace objects, 16(428KB) LOS objects, 33% free, 29MB/43MB, paused 818us total 61.096ms
09-01 19:12:27.609   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-01 19:12:27.613  4025  4025 I art     : System.exit called, status: 0
09-01 19:12:27.613  4025  4025 I AndroidRuntime: VM exiting with result code 0.
09-01 19:12:27.615   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-01 19:12:27.624   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-01 19:12:27.639   874  1303 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-01 19:12:27.641  2076  2276 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-01 19:12:27.642  1877  1877 I Keyboard.Facilitator: resetDictionaries() : en_US
09-01 19:12:27.643  3332  3332 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-01 19:12:27.671   874  1924 I ActivityManager: Start proc 4043:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-01 19:12:27.677  1962  1962 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-01 19:12:27.691  1877  4041 I Keyboard.Facilitator.DecoderInitializer: run()
09-01 19:12:27.702  1877  4041 I Decoder : createOrResetDecoder
09-01 19:12:27.719  1515  1515 I ConfigService: onCreate
09-01 19:12:27.722   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-01 19:12:27.725  4043  4043 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-01 19:12:27.734   874  1924 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3464 uid 10000
09-01 19:12:27.736  1877  1877 I Keyboard.Facilitator: onFinishInput()
09-01 19:12:27.756  1877  4041 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-01 19:12:27.760   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-01 19:12:27.760   874   886 E PackageManager: Failed to write settings, restoring backup
09-01 19:12:27.760   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-01 19:12:27.760   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-01 19:12:27.760   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-01 19:12:27.760   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-01 19:12:27.760   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-01 19:12:27.760   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 19:12:27.760   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-01 19:12:27.760   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 19:12:27.765   874   887 E DropBoxManagerService: Can't write: system_server_wtf
09-01 19:12:27.765   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-01 19:12:27.765   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 19:12:27.765   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 19:12:27.765   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 19:12:27.765   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 19:12:27.765   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 19:12:27.765   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 19:12:27.765   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-01 19:12:27.765   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-01 19:12:27.765   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-01 19:12:27.765   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-01 19:12:27.765   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-01 19:12:27.765   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-01 19:12:27.765   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 19:12:27.765   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-01 19:12:27.765   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 19:12:27.765   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 19:12:27.765   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 19:12:27.765   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 19:12:27.765   874   887 E DropBoxManagerService: 	... 13 more
09-01 19:12:27.769  1982  2044 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-01 19:12:27.782   874  2061 I ActivityManager: Start proc 4060:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-01 19:12:27.782  1982  2044 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-01 19:12:27.782  1982  2044 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1982
09-01 19:12:27.782  1982  2044 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-01 19:12:27.782  1982  2044 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-01 19:12:27.782  1982  2044 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-01 19:12:27.782  1982  2044 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-01 19:12:27.782  1982  2044 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-01 19:12:27.782  1982  2044 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-01 19:12:27.782  1982  2044 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-01 19:12:27.782  1982  2044 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-01 19:12:27.782  1982  2044 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-01 19:12:27.782  1982  2044 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-01 19:12:27.782  1982  2044 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-01 19:12:27.782  1982  2044 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 19:12:27.784   874  2000 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-01 19:12:27.789  1982  2044 I Process : Sending signal. PID: 1982 SIG: 9
09-01 19:12:27.790   874  4068 E DropBoxManagerService: Can't write: system_app_crash
09-01 19:12:27.790   874  4068 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
09-01 19:12:27.790   874  4068 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 19:12:27.790   874  4068 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 19:12:27.790   874  4068 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 19:12:27.790   874  4068 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 19:12:27.790   874  4068 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 19:12:27.790   874  4068 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 19:12:27.790   874  4068 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 19:12:27.790   874  4068 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 19:12:27.790   874  4068 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 19:12:27.790   874  4068 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 19:12:27.790   874  4068 E DropBoxManagerService: 	... 5 more
09-01 19:12:27.796  1877  4041 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-01 19:12:27.797  1877  4041 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-01 19:12:27.797  1877  4041 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-01 19:12:27.799  1877  4041 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-01 19:12:27.799  1877  4041 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-01 19:12:27.799  1877  4041 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-01 19:12:27.799  1877  4041 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-01 19:12:27.800  1877  4041 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-01 19:12:27.800  1877  4041 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-01 19:12:27.800  1877  4041 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-01 19:12:27.800  1877  4041 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-01 19:12:27.800  1877  4041 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-01 19:12:27.800  1877  4041 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-01 19:12:27.806  4043  4043 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-01 19:12:27.823   874  2057 I ActivityManager: Start proc 4076:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-01 19:12:27.824  4043  4075 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-01 19:12:27.858   874  1302 W InputDispatcher: channel 'b921801 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
09-01 19:12:27.859   874  1302 E InputDispatcher: channel 'b921801 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
09-01 19:12:27.860   874  1971 D GraphicsStats: Buffer count: 1
09-01 19:12:27.860   874   884 I WindowState: WIN DEATH: Window{b921801 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-01 19:12:27.860   874   884 W InputDispatcher: Attempted to unregister already unregistered input channel 'b921801 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
09-01 19:12:27.878  4076  4076 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-01 19:12:27.890  4043  4058 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-01 19:12:27.890  4043  4058 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 19:12:27.890  4043  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 19:12:27.890  4043  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 19:12:27.890  4043  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 19:12:27.890  4043  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 19:12:27.890  4043  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 19:12:27.890  4043  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 19:12:27.890  4043  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 19:12:27.890  4043  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 19:12:27.890  4043  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 19:12:27.890  4043  4058 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 19:12:27.890  4043  4058 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 19:12:27.890  4043  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 19:12:27.890  4043  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-01 19:12:27.890  4043  4058 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-01 19:12:27.890  4043  4058 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-01 19:12:27.890  4043  4058 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-01 19:12:27.890  4043  4058 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-01 19:12:27.890  4043  4058 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 19:12:27.890  4043  4058 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-01 19:12:27.890  4043  4058 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 19:12:27.891  4043  4058 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-01 19:12:27.891  4043  4058 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 19:12:27.891  4043  4058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 19:12:27.891  4043  4058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 19:12:27.891  4043  4058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 19:12:27.891  4043  4058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 19:12:27.891  4043  4058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 19:12:27.891  4043  4058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 19:12:27.891  4043  4058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 19:12:27.891  4043  4058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 19:12:27.891  4043  4058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 19:12:27.891  4043  4058 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 19:12:27.891  4043  4058 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 19:12:27.891  4043  4058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 19:12:27.891  4043  4058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-01 19:12:27.891  4043  4058 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-01 19:12:27.891  4043  4058 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-01 19:12:27.891  4043  4058 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-01 19:12:27.891  4043  4058 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-01 19:12:27.891  4043  4058 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 19:12:27.891  4043  4058 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-01 19:12:27.891  4043  4058 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 19:12:27.893   874  2059 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1982) has died
09-01 19:12:27.893   874  2059 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-01 19:12:27.894   874  2059 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-01 19:12:27.911   874   887 I ActivityManager: Start proc 4093:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-01 19:12:27.940   874  1947 I ActivityManager: Killing 3385:com.google.android.apps.docs/u0a46 (adj 15): empty #17
09-01 19:12:27.948  1515  1515 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-01 19:12:27.949  1515  1515 D AndroidRuntime: Shutting down VM
09-01 19:12:27.950  1515  1515 E AndroidRuntime: FATAL EXCEPTION: main
09-01 19:12:27.950  1515  1515 E AndroidRuntime: Process: com.google.process.gapps, PID: 1515
09-01 19:12:27.950  1515  1515 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-01 19:12:27.950  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-01 19:12:27.950  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-01 19:12:27.950  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-01 19:12:27.950  1515  1515 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 19:12:27.950  1515  1515 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-01 19:12:27.950  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 19:12:27.950  1515  1515 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 19:12:27.950  1515  1515 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 19:12:27.950  1515  1515 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 19:12:27.950  1515  1515 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-01 19:12:27.950  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-01 19:12:27.950  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-01 19:12:27.950  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-01 19:12:27.950  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-01 19:12:27.950  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-01 19:12:27.950  1515  1515 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-01 19:12:27.950  1515  1515 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-01 19:12:27.950  1515  1515 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-01 19:12:27.950  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-01 19:12:27.950  1515  1515 E AndroidRuntime: 	... 8 more
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 19:12:27.957  4093  4093 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 19:12:27.957  4093  4093 D AndroidRuntime: Shutting down VM
09-01 19:12:27.964  4043  4058 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-01 19:12:27.969  4043  4075 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-01 19:12:27.969  4043  4075 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 19:12:27.969  4043  4075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 19:12:27.969  4043  4075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 19:12:27.969  4043  4075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 19:12:27.969  4043  4075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 19:12:27.969  4043  4075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 19:12:27.969  4043  4075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 19:12:27.969  4043  4075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 19:12:27.969  4043  4075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 19:12:27.969  4043  4075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 19:12:27.969  4043  4075 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 19:12:27.969  4043  4075 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 19:12:27.969  4043  4075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 19:12:27.969  4043  4075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-01 19:12:27.969  4043  4075 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-01 19:12:27.969  4043  4075 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-01 19:12:27.969  4043  4075 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-01 19:12:27.969  4043  4075 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-01 19:12:27.969  4043  4075 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-01 19:12:27.969  4043  4075 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-01 19:12:27.969  4043  4075 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-01 19:12:27.969  4043  4075 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 19:12:27.969  4043  4075 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-01 19:12:27.969  4043  4075 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 19:12:27.970  4043  4075 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-01 19:12:27.970  4043  4075 E AndroidRuntime: Process: android.process.acore, PID: 4043
09-01 19:12:27.970  4043  4075 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 19:12:27.970  4043  4075 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 19:12:27.970  4043  4075 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 19:12:27.970  4043  4075 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 19:12:27.970  4043  4075 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 19:12:27.970  4043  4075 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 19:12:27.970  4043  4075 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 19:12:27.970  4043  4075 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 19:12:27.970  4043  4075 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 19:12:27.970  4043  4075 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 19:12:27.970  4043  4075 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 19:12:27.970  4043  4075 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 19:12:27.970  4043  4075 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 19:12:27.970  4043  4075 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-01 19:12:27.970  4043  4075 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-01 19:12:27.970  4043  4075 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-01 19:12:27.970  4043  4075 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-01 19:12:27.970  4043  4075 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-01 19:12:27.970  4043  4075 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-01 19:12:27.970  4043  4075 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-01 19:12:27.970  4043  4075 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-01 19:12:27.970  4043  4075 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 19:12:27.970  4043  4075 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-01 19:12:27.970  4043  4075 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 19:12:27.970  4043  4058 I Process : Sending signal. PID: 4043 SIG: 9
09-01 19:12:27.992   874  4106 E DropBoxManagerService: Can't write: system_app_crash
09-01 19:12:27.992   874  4106 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
09-01 19:12:27.992   874  4106 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 19:12:27.992   874  4106 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 19:12:27.992   874  4106 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 19:12:27.992   874  4106 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 19:12:27.992   874  4106 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 19:12:27.992   874  4106 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 19:12:27.992   874  4106 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 19:12:27.992   874  4106 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 19:12:27.992   874  4106 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 19:12:27.992   874  4106 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 19:12:27.992   874  4106 E DropBoxManagerService: 	... 5 more
09-01 19:12:28.005   874  1969 I ActivityManager: Process android.process.acore (pid 4043) has died
09-01 19:12:28.005   874  1969 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
09-01 19:12:28.006   874  4107 E DropBoxManagerService: Can't write: system_app_crash
09-01 19:12:28.006   874  4107 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
09-01 19:12:28.006   874  4107 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 19:12:28.006   874  4107 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 19:12:28.006   874  4107 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 19:12:28.006   874  4107 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 19:12:28.006   874  4107 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 19:12:28.006   874  4107 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 19:12:28.006   874  4107 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 19:12:28.006   874  4107 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 19:12:28.006   874  4107 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 19:12:28.006   874  4107 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 19:12:28.006   874  4107 E DropBoxManagerService: 	... 5 more
09-01 19:12:28.007  4093  4093 E AndroidRuntime: FATAL EXCEPTION: main
09-01 19:12:28.007  4093  4093 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4093
09-01 19:12:28.007  4093  4093 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-01 19:12:28.007  4093  4093 E AndroidRuntime: 	... 10 more
09-01 19:12:28.009   874  1529 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-01 19:12:28.010  4093  4093 I Process : Sending signal. PID: 4093 SIG: 9
09-01 19:12:28.011  1515  1515 I Process : Sending signal. PID: 1515 SIG: 9
09-01 19:12:28.013   874  4108 E DropBoxManagerService: Can't write: system_app_crash
09-01 19:12:28.013   874  4108 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
09-01 19:12:28.013   874  4108 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 19:12:28.013   874  4108 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 19:12:28.013   874  4108 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 19:12:28.013   874  4108 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 19:12:28.013   874  4108 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 19:12:28.013   874  4108 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 19:12:28.013   874  4108 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 19:12:28.013   874  4108 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 19:12:28.013   874  4108 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 19:12:28.013   874  4108 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 19:12:28.013   874  4108 E DropBoxManagerService: 	... 5 more
09-01 19:12:28.023  1731  4091 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-01 19:12:28.023  1731  4091 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-01 19:12:28.029  1731  4091 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-01 19:12:28.029  1731  4091 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-01 19:12:28.058   874  1971 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4093) has died
09-01 19:12:28.059   874  1312 D WifiService: Client connection lost with reason: 4
09-01 19:12:28.062   874  1971 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-01 19:12:28.065   874  2000 I ActivityManager: Process com.google.process.gapps (pid 1515) has died
09-01 19:12:28.066   874  2000 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
09-01 19:12:28.066   874  2000 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 10999ms
09-01 19:12:28.066   874  2000 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 20999ms
09-01 19:12:28.073  1731  1731 W RocketImpressions: ClearcutLogger connection suspended: 1
09-01 19:12:28.098   874   887 I ActivityManager: Start proc 4109:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-01 19:12:28.113   874  1924 I ActivityManager: Start proc 4120:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService

```
